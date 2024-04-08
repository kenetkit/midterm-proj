<template>
  <div class="body">
    <!-- NavBar -->
      <nav class="navbar fixed-top navbar-expand-lg">

        <div class="container-fluid">

          <!-- NavBar Toggler   -->
            <a class="navbar-toggler" id="navBarCollapse" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" style="width: 45px;">
              <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="white" class="bi bi-list" viewBox="4 0 16 16">
                <path fill-rule="evenodd" d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5m0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5m0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5"/>
              </svg>
            </a>
          
          <!-- NavBar Links -->
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item py-1">
                  <a class="nav-link px-4" id="homeLink" href="#home">Home</a>
                </li>
                <li class="nav-item py-1">
                  <a class="nav-link px-4" id="bioLink" href="#layouts">Layouts</a>
                </li>
                <li class="nav-item py-1">
                  <a class="nav-link px-4" id="bioLink" href="#bio">Biography</a>
                </li>
                <li class="nav-item py-1">
                  <a class="nav-link px-4" id="releasesLink" href="#releases">Releases</a>
                </li>
                <li class="nav-item py-1">
                  <a class="nav-link px-4" id="socialsLink" href="#socials">Socials</a>
                </li>
              </ul>
            </div>

        </div>

      </nav>

    <!-- Main Screen -->
      <div class="container-sm-fluid" id="mainScreen">

          <div class="col-md-12 d-flex flex-column" id="home">
            <div class="img">
              <img src="../public/background.png">
            </div>
          </div>

        <div class="padding">
          <!-- Home -->
          <div class="col-md-12 d-flex flex-column" id="pageContent">            
              <div class="homeCont">
                <div class="textHeader">
                  <h1 class="headerText">Hello, stranger!</h1>
                  <p class="paragraphText">Welcome to my portfolio! My name is Jan Kenneth Calo, and I am a music producer and graphic artist with a passion for creating captivating sounds and visually stunning designs.</p>
                </div>
              </div>
          </div>

          <!-- Layouts -->
          <div class="col-md-12 d-flex flex-column" id="pageContent">            
              <div class="layoutCont" id="layouts">
                <div class="textHeader">
                  <h1 class="headerText">Layouts</h1>
                  <div class="col-md-8 d-flex flex-column" id="carouselSlides">
                    <div id="carouselExampleFade" class="carousel slide carousel-fade">
                      <div class="carousel-inner" id="carouselBorder">
                        <div class="carousel-item active">
                          <img src="../public/slide1.jpg" class="d-block" id="carouselItem" alt="Rick and Morty">
                        </div>
                        <div class="carousel-item">
                          <img src="../public/slide2.jpg" class="d-block" id="carouselItem3" alt="We Heal As One">
                        </div>
                        <div class="carousel-item">
                          <img src="../public/slide3.jpeg" class="d-block" id="carouselItem2" alt="Marjorie">
                        </div>
                      </div>
                      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                      </button>
                      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                      </button>
                    </div>
                  </div>
                </div>
              </div>
          </div>

          <!-- Biography -->
          <div class="col-md-12 d-flex flex-column" id="pageContent">
              <div class="bioCont" id="bio">
                <div class="textHeader">
                  <h1 class="headerText">Biography</h1>
                  <p class="paragraphText">Throughout my expansive career as a DJ, producer, remixer, and graphic artist, I somehow carved out a long-lasting legacy within the electronic music world.</p> 
                  <p class="paragraphText">Hailing from Lapu-Lapu, a city tucked deep within the Philippines, my journey began at age 11 when I started to play the piano.When music turned into an obsession 
                  from just a hobby, at age 12, I started to practice and produce dance music on my computer. With the help of FL Studio, I managed to create big and booming beats for almost 10 years, 
                  up until this very day. And a few years ago, I posted my very first, unofficial remix of "River Flows In You" by Yiruma. </p> 
                  <p class="paragraphText">Aside from making music, I also practiced and made digital graphics. I use Adobe Photoshop for photo manipulation and Adobe Illustrator for vector art and illustrations. In my senior 
                  high school years, our major course was graphic design, which helped me hone my graphic design skills.</p> 
                  <p class="paragraphText">A few years later, when the pandemic hit the nation, I started my online freelancing job to earn money for myself. Unfortunately, there are a lot of good competitors, and it really outshined me. 
                  I never gave up until I got my first foreign customer. I was earning $5 per project—not much, but it helped me with my daily needs. As the months went by and many foreign clients later, I received numerous 5-star 
                  ratings from them, which made me happy about my freelancing job.</p>
                  <p class="paragraphText">In September of 2020, I released my first remix track, "Wake Up" by Elaine, officially on YouTube. It garnered 13k+ views and 270+ likes as of writing this article. As I have seen the 
                  numbers and am overwhelmed by the reactions, I decided to post more of my remixes and originals online up until now.</p> 
                  <p class="paragraphText">Now, I am working on some new unofficial remixes for Ariana Grande, Dua Lipa, and more, dominated by either of the two genres: Big Room Techno and Tech House, depending on the style I want 
                  that fits on the track.I forgot to mention that I have also started my TikTok and Soundcloud accounts, and I will share my socials down below for you guys to check out my other tracks. That would be all for my biography. Thanks for reading!</p>
                </div>
              </div>
          </div>

          <!-- Releases -->
          <div class="col-md-12 d-flex flex-column" id="pageContent">
              <div class="relCont" id="releases">
                <div class="textHeader">
                  <h1 class="headerText">Releases</h1>

                  <div class="anotherCarousel">
                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/down.jpg" class="card-img-top" alt="Down (Kenneth Kit Remix)" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Down (Kenneth Kit Remix)</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white;">Eggnarok</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=Gdju3Su7QH0" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/sinulog.jpg" class="card-img-top" alt="Sinulog Theme" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Sinulog Theme (Big Room Edit)</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white;">Kenneth Kit</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=F-r1PxINS_I" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/carefree.jpg" class="card-img-top" alt="Carefree" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Carefree</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white; padding-bottom: 21px;">Kenneth Kit</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=0i8JNBKLRcs" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/sweetestpie.jpg" class="card-img-top" alt="Sweetest Pie (Kenneth Kit Remix)" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Sweetest Pie (Kenneth Kit Remix)</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 12px; color: white; padding-bottom: 3px;">Megan Thee Stallion, Dua Lipa</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=Ezoc5ZxPAis" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/blt.jpg" class="card-img-top" alt="Bizarre Love Triangle" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Bizarre Love Triangle</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white; padding-bottom: 21px;">Kenneth Kit</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=4muZD3UBnNw" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/blindspot.jpg" class="card-img-top" alt="Blindspot (Kenneth Kit Remix)" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Blindspot (Kenneth Kit Remix)</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white;">Nurko, Devon Baldwin</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=z6xV0-aKzZ0" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/sofia.jpg" class="card-img-top" alt="Sofia (Kenneth Kit Remix)" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Sofia (Kenneth Kit Remix)</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white;">Clairo</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=CC9QGbdzFog" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/nothing.jpg" class="card-img-top" alt="Nothing Good Comes Easy (Kenneth Kit Remix)" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 14px; color: white; padding-top: 8px;">Nothing Good Comes Easy (Kenneth Kit Remix)</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white;">Felix Cartal, Elohim</p>
                            <div class="ytCont">
                              <a href="https://soundcloud.com/user-703281780/felix-cartal-feat-elohim-nothing-good-comes-easy-kenneth-kit-remix-2" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" fill="currentColor" style="width: 39px; height: 39px; float: left;" id="soundcloud">
                                  <path d="M111.4 256.3l5.8 65-5.8 68.3c-.3 2.5-2.2 4.4-4.4 4.4s-4.2-1.9-4.2-4.4l-5.6-68.3 5.6-65c0-2.2 1.9-4.2 4.2-4.2 2.2 0 4.1 2 4.4 4.2zm21.4-45.6c-2.8 0-4.7 2.2-5 5l-5 105.6 5 68.3c.3 2.8 2.2 5 5 5 2.5 0 4.7-2.2 4.7-5l5.8-68.3-5.8-105.6c0-2.8-2.2-5-4.7-5zm25.5-24.1c-3.1 0-5.3 2.2-5.6 5.3l-4.4 130 4.4 67.8c.3 3.1 2.5 5.3 5.6 5.3 2.8 0 5.3-2.2 5.3-5.3l5.3-67.8-5.3-130c0-3.1-2.5-5.3-5.3-5.3zM7.2 283.2c-1.4 0-2.2 1.1-2.5 2.5L0 321.3l4.7 35c.3 1.4 1.1 2.5 2.5 2.5s2.2-1.1 2.5-2.5l5.6-35-5.6-35.6c-.3-1.4-1.1-2.5-2.5-2.5zm23.6-21.9c-1.4 0-2.5 1.1-2.5 2.5l-6.4 57.5 6.4 56.1c0 1.7 1.1 2.8 2.5 2.8s2.5-1.1 2.8-2.5l7.2-56.4-7.2-57.5c-.3-1.4-1.4-2.5-2.8-2.5zm25.3-11.4c-1.7 0-3.1 1.4-3.3 3.3L47 321.3l5.8 65.8c.3 1.7 1.7 3.1 3.3 3.1 1.7 0 3.1-1.4 3.1-3.1l6.9-65.8-6.9-68.1c0-1.9-1.4-3.3-3.1-3.3zm25.3-2.2c-1.9 0-3.6 1.4-3.6 3.6l-5.8 70 5.8 67.8c0 2.2 1.7 3.6 3.6 3.6s3.6-1.4 3.9-3.6l6.4-67.8-6.4-70c-.3-2.2-2-3.6-3.9-3.6zm241.4-110.9c-1.1-.8-2.8-1.4-4.2-1.4-2.2 0-4.2.8-5.6 1.9-1.9 1.7-3.1 4.2-3.3 6.7v.8l-3.3 176.7 1.7 32.5 1.7 31.7c.3 4.7 4.2 8.6 8.9 8.6s8.6-3.9 8.6-8.6l3.9-64.2-3.9-177.5c-.4-3-2-5.8-4.5-7.2zm-26.7 15.3c-1.4-.8-2.8-1.4-4.4-1.4s-3.1.6-4.4 1.4c-2.2 1.4-3.6 3.9-3.6 6.7l-.3 1.7-2.8 160.8s0 .3 3.1 65.6v.3c0 1.7.6 3.3 1.7 4.7 1.7 1.9 3.9 3.1 6.4 3.1 2.2 0 4.2-1.1 5.6-2.5 1.7-1.4 2.5-3.3 2.5-5.6l.3-6.7 3.1-58.6-3.3-162.8c-.3-2.8-1.7-5.3-3.9-6.7zm-111.4 22.5c-3.1 0-5.8 2.8-5.8 6.1l-4.4 140.6 4.4 67.2c.3 3.3 2.8 5.8 5.8 5.8 3.3 0 5.8-2.5 6.1-5.8l5-67.2-5-140.6c-.2-3.3-2.7-6.1-6.1-6.1zm376.7 62.8c-10.8 0-21.1 2.2-30.6 6.1-6.4-70.8-65.8-126.4-138.3-126.4-17.8 0-35 3.3-50.3 9.4-6.1 2.2-7.8 4.4-7.8 9.2v249.7c0 5 3.9 8.6 8.6 9.2h218.3c43.3 0 78.6-35 78.6-78.3.1-43.6-35.2-78.9-78.5-78.9zm-296.7-60.3c-4.2 0-7.5 3.3-7.8 7.8l-3.3 136.7 3.3 65.6c.3 4.2 3.6 7.5 7.8 7.5 4.2 0 7.5-3.3 7.5-7.5l3.9-65.6-3.9-136.7c-.3-4.5-3.3-7.8-7.5-7.8zm-53.6-7.8c-3.3 0-6.4 3.1-6.4 6.7l-3.9 145.3 3.9 66.9c.3 3.6 3.1 6.4 6.4 6.4 3.6 0 6.4-2.8 6.7-6.4l4.4-66.9-4.4-145.3c-.3-3.6-3.1-6.7-6.7-6.7zm26.7 3.4c-3.9 0-6.9 3.1-6.9 6.9L227 321.3l3.9 66.4c.3 3.9 3.1 6.9 6.9 6.9s6.9-3.1 6.9-6.9l4.2-66.4-4.2-141.7c0-3.9-3-6.9-6.9-6.9z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/takeiteasy.jpg" class="card-img-top" alt="Take It Easy" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Take It Easy</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white; padding-bottom: 21px;">Kenneth Kit</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=myOEO9kutfs" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/never.jpg" class="card-img-top" alt="Never Let Me Go" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Never Let Me Go</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white; padding-bottom: 21px;">Kenneth Kit</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=1Uy9SUfQGLM" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/aiminghigh.jpg" class="card-img-top" alt="Aiming High (Kenneth Kit Remix)" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Aiming High (Kenneth Kit Remix)</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 13px; color: white; padding-bottom: 1px;">Chris Red, Andrea Hamilton</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=WThfBcZCPQM" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/losecontrol.jpg" class="card-img-top" alt="Lose Control (Kenneth Kit Remix)" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Lose Control (Kenneth Kit Remix)</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white;">Complexion of Sound</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=_V_1XiKcC5s" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/bring.jpg" class="card-img-top" alt="Bring Me Back (Kenneth Kit Remix)" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Bring Me Back (Kenneth Kit Remix)</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white; padding-bottom: 1px;">Miles Away, Claire Ridgely</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=2OogFB9O7oc" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/cry.jpg" class="card-img-top" alt="Cry (Just A Little)" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Cry (Just A Little)</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white; padding-bottom: 21px;">Kenneth Kit</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=Y7YU_9fGxL8" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/lkmh.jpg" class="card-img-top" alt="Love Keeps Me High" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Love Keeps Me High</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white; padding-bottom: 24px;">Kenneth Kit</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=CfnIOAiehMc" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                    <div class="individual">
                      <div class="card" style="width: 12rem; background-color: #2b2b2b; border: none;">
                        <img src="../public/wakeup.jpg" class="card-img-top" alt="Wake Up (Kenneth Kit Remix)" id="relImg">
                          <div class="card-body" style="padding: 4px;">
                            <h5 class="card-title" style="font-family: headerfont; font-size: 17px; color: white; padding-top: 8px;">Wake Up (Kenneth Kit Remix)</h5>
                            <p class="card-text" style="font-family: paragraphfont; font-size: 14px; color: white;">Elaine</p>
                            <div class="ytCont">
                              <a href="https://www.youtube.com/watch?v=ttKQaQw6EPk" target="_blank">
                                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                                  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                                </svg>
                              </a>
                            </div>
                          </div>
                      </div>
                    </div>

                  </div>
                  
                </div>
              </div>
          </div>

            <!-- Socials -->
            <div class="col-md-12 d-flex flex-column" id="pageContent">
              <div class="socialsCont" id="socials">
                <div class="textHeader">
                  <h1 class="headerText">Socials</h1>
                    <div class="socialsDiv">
                      <div class="linkDiv2">
                        <a href="https://facebook.com/kennethkit.19" target="_blank">
                          <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16" id="facebook">
                            <path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951"/>
                          </svg>
                        </a>                 
                      </div>

                      <div class="linkDiv">
                        <a href="https://instagram.com/kenet_kt" target="_blank">
                          <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16" id="instagram">
                            <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.9 3.9 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233s.008-2.388.046-3.231c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92m-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217m0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334"/>
                          </svg>
                        </a>                   
                      </div>

                      <div class="linkDiv">
                        <a href="https://www.youtube.com/channel/UCB2Qbc_4EwJTKsW4Let89gw" target="_blank">
                          <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16" id="youtube">
                            <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"/>
                          </svg>
                        </a>            
                      </div>

                      
                      <div class="linkDiv">
                        <a href="https://www.tiktok.com/@kenneth_kit" target="_blank">
                          <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" class="bi bi-tiktok" viewBox="0 0 16 16" id="tiktok">
                            <path d="M9 0h1.98c.144.715.54 1.617 1.235 2.512C12.895 3.389 13.797 4 15 4v2c-1.753 0-3.07-.814-4-1.829V11a5 5 0 1 1-5-5v2a3 3 0 1 0 3 3z"/>
                          </svg>
                        </a>                 
                      </div>

                      <div class="linkDiv">
                        <a href="https://soundcloud.com/user-703281780" target="_blank">
                          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" fill="currentColor" style="width: 30px; height: 30px; float: left;" id="soundcloud">
                            <path d="M111.4 256.3l5.8 65-5.8 68.3c-.3 2.5-2.2 4.4-4.4 4.4s-4.2-1.9-4.2-4.4l-5.6-68.3 5.6-65c0-2.2 1.9-4.2 4.2-4.2 2.2 0 4.1 2 4.4 4.2zm21.4-45.6c-2.8 0-4.7 2.2-5 5l-5 105.6 5 68.3c.3 2.8 2.2 5 5 5 2.5 0 4.7-2.2 4.7-5l5.8-68.3-5.8-105.6c0-2.8-2.2-5-4.7-5zm25.5-24.1c-3.1 0-5.3 2.2-5.6 5.3l-4.4 130 4.4 67.8c.3 3.1 2.5 5.3 5.6 5.3 2.8 0 5.3-2.2 5.3-5.3l5.3-67.8-5.3-130c0-3.1-2.5-5.3-5.3-5.3zM7.2 283.2c-1.4 0-2.2 1.1-2.5 2.5L0 321.3l4.7 35c.3 1.4 1.1 2.5 2.5 2.5s2.2-1.1 2.5-2.5l5.6-35-5.6-35.6c-.3-1.4-1.1-2.5-2.5-2.5zm23.6-21.9c-1.4 0-2.5 1.1-2.5 2.5l-6.4 57.5 6.4 56.1c0 1.7 1.1 2.8 2.5 2.8s2.5-1.1 2.8-2.5l7.2-56.4-7.2-57.5c-.3-1.4-1.4-2.5-2.8-2.5zm25.3-11.4c-1.7 0-3.1 1.4-3.3 3.3L47 321.3l5.8 65.8c.3 1.7 1.7 3.1 3.3 3.1 1.7 0 3.1-1.4 3.1-3.1l6.9-65.8-6.9-68.1c0-1.9-1.4-3.3-3.1-3.3zm25.3-2.2c-1.9 0-3.6 1.4-3.6 3.6l-5.8 70 5.8 67.8c0 2.2 1.7 3.6 3.6 3.6s3.6-1.4 3.9-3.6l6.4-67.8-6.4-70c-.3-2.2-2-3.6-3.9-3.6zm241.4-110.9c-1.1-.8-2.8-1.4-4.2-1.4-2.2 0-4.2.8-5.6 1.9-1.9 1.7-3.1 4.2-3.3 6.7v.8l-3.3 176.7 1.7 32.5 1.7 31.7c.3 4.7 4.2 8.6 8.9 8.6s8.6-3.9 8.6-8.6l3.9-64.2-3.9-177.5c-.4-3-2-5.8-4.5-7.2zm-26.7 15.3c-1.4-.8-2.8-1.4-4.4-1.4s-3.1.6-4.4 1.4c-2.2 1.4-3.6 3.9-3.6 6.7l-.3 1.7-2.8 160.8s0 .3 3.1 65.6v.3c0 1.7.6 3.3 1.7 4.7 1.7 1.9 3.9 3.1 6.4 3.1 2.2 0 4.2-1.1 5.6-2.5 1.7-1.4 2.5-3.3 2.5-5.6l.3-6.7 3.1-58.6-3.3-162.8c-.3-2.8-1.7-5.3-3.9-6.7zm-111.4 22.5c-3.1 0-5.8 2.8-5.8 6.1l-4.4 140.6 4.4 67.2c.3 3.3 2.8 5.8 5.8 5.8 3.3 0 5.8-2.5 6.1-5.8l5-67.2-5-140.6c-.2-3.3-2.7-6.1-6.1-6.1zm376.7 62.8c-10.8 0-21.1 2.2-30.6 6.1-6.4-70.8-65.8-126.4-138.3-126.4-17.8 0-35 3.3-50.3 9.4-6.1 2.2-7.8 4.4-7.8 9.2v249.7c0 5 3.9 8.6 8.6 9.2h218.3c43.3 0 78.6-35 78.6-78.3.1-43.6-35.2-78.9-78.5-78.9zm-296.7-60.3c-4.2 0-7.5 3.3-7.8 7.8l-3.3 136.7 3.3 65.6c.3 4.2 3.6 7.5 7.8 7.5 4.2 0 7.5-3.3 7.5-7.5l3.9-65.6-3.9-136.7c-.3-4.5-3.3-7.8-7.5-7.8zm-53.6-7.8c-3.3 0-6.4 3.1-6.4 6.7l-3.9 145.3 3.9 66.9c.3 3.6 3.1 6.4 6.4 6.4 3.6 0 6.4-2.8 6.7-6.4l4.4-66.9-4.4-145.3c-.3-3.6-3.1-6.7-6.7-6.7zm26.7 3.4c-3.9 0-6.9 3.1-6.9 6.9L227 321.3l3.9 66.4c.3 3.9 3.1 6.9 6.9 6.9s6.9-3.1 6.9-6.9l4.2-66.4-4.2-141.7c0-3.9-3-6.9-6.9-6.9z"/>
                          </svg>
                        </a>           
                      </div>

                      <div class="linkDiv">
                        <a href="https://twitter.com/kennethkit_19" target="_blank">
                          <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" class="bi bi-twitter-x" viewBox="0 0 16 16" id="x">
                            <path d="M12.6.75h2.454l-5.36 6.142L16 15.25h-4.937l-3.867-5.07-4.425 5.07H.316l5.733-6.57L0 .75h5.063l3.495 4.633L12.601.75Zm-.86 13.028h1.36L4.323 2.145H2.865z"/>
                          </svg>
                        </a>                  
                      </div>




                  
                    </div>
                  
                </div>
              </div>
          </div>

        </div>
      </div>

  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

// export default {
//   name: 'App',
//   components: {
//     HelloWorld
//   }
// }

export default {
  methods: {
    handleDrag(event) {
      const svgElement = document.getElementById('dragIcon');
      const svgRect = svgElement.getBoundingClientRect();
      const mouseX = event.clientX - svgRect.left;
      const mouseY = event.clientY - svgRect.top;

      svgElement.setAttribute('x', mouseX);
      svgElement.setAttribute('y', mouseY);
    }
    
  }
}

let touchStartX = 0;
let touchStartY = 0;

document.addEventListener('touchstart', function(event) {
    if (event.touches.length === 2) {
        touchStartX = event.touches[0].clientX;
        touchStartY = event.touches[0].clientY;
    }
});

document.addEventListener('touchmove', function(event) {
    if (event.touches.length === 2) {
        let touchEndX = event.touches[0].clientX;
        let touchEndY = event.touches[0].clientY;

        // Calculate the distance moved
        let deltaX = touchEndX - touchStartX;
        let deltaY = touchEndY - touchStartY;

        // Perform scrolling based on the deltaX and deltaY values
        window.scrollBy(-deltaX, -deltaY);

        // Update the starting position for the next move
        touchStartX = touchEndX;
        touchStartY = touchEndY;
    }
});

</script>

<style>
#app {
  font-family: navFont;
  text-align: center;
}

@font-face{
  font-family: navFont;
  src: url(/src/assets/roboto/Roboto-Regular.ttf);
}

@font-face{
  font-family: paragraphFont;
  src: url(/src/assets/roboto/Roboto-Light.ttf);
}

@font-face{
  font-family: headerFont;
  src: url(/src/assets/roboto/Roboto-Medium.ttf);
}



.body{
  max-width: 100%;
  height: 100%;
  background-color: #181818;
}

.navbar{
  position: fixed;
  background-color: #212121;
}

#navBarCollapse{
  border: none;
}

/* .navbar-nav .nav-link {
  color: rgb(192, 192, 192);
}

.navbar-nav .nav-link.active {
  color: white !important;
} */

#homeLink{
  color: rgb(199, 199, 199);
}

#homeLink:active{
  color: white;
}

#homeLink:hover{
  color: white;
}

#bioLink{
  color: rgb(199, 199, 199);
}

#bioLink:active{
  color: white;
}

#bioLink:hover{
  color: white;
}

#releasesLink{
  color: rgb(199, 199, 199);
}

#releasesLink:active{
  color: white;
}

#releasesLink:hover{
  color: white;
}

#socialsLink{
  color: rgb(199, 199, 199);
}

#socialsLink:active{
  color: white;
}

#socialsLink:hover{
  color: white;
}

/* .col-md-12{
  border: 2px solid red;
} */

.img {
  height: 200px;
  overflow: hidden; 
}

.img img {
  width: 100%;
  height: auto;
  display: block;
  max-width: 100%;
  transform: scale(1.5); 
}

.padding{
  padding: 8px; 
}

#pageContent{
  padding: 8px; 
}

.homeCont { 
  background-color: #212121; 
  border-radius: 10px; 
  max-height: 100%;
} 

.textHeader{
  padding-left: 22px;
  padding-right: 22px;
}

.headerText{
  font-family: headerFont;
  color: white;
  font-size: 48px;
  text-align: left;
  padding-top: 12px;
}

.paragraphText{
  font-family: paragraphFont;
  color: white;
  font-size: 18px;
  text-align: left;
  padding-top: 5px;
}

.layoutCont{ 
  background-color: #212121; 
  border-radius: 10px; 
  max-height: 100%;
}

#carouselExampleFade{
  padding-top: 15px;
  padding-bottom: 24px;
  max-width: 100%;
  width: 1000px;
  margin: auto;
}

#carouselSlides{
  margin: auto;
}

#carouselItem{
  height: 425px;
  max-height: 100%;
  transform: scale(1.3);
}

#carouselItem2{
  height: 425px;
  max-height: 100%;
  transform: scale(1.8);
  margin: auto;
}

#carouselItem3{
  height: 425px;
  max-height: 100%;
  transform: scale(1.8);
}

#carouselBorder{
  border-radius: 10px;
}

.bioCont{ 
  background-color: #212121; 
  border-radius: 10px; 
  max-height: 100%;
} 

.anotherCarousel{
  padding-bottom: 15px;
  display: flex;
  overflow-x: auto;
}

.anotherCarousel::-webkit-scrollbar{
  width: 3px;
  height: 12px;
}

.anotherCarousel::-webkit-scrollbar-thumb{
  opacity: 0;
}

.anotherCarousel::-webkit-scrollbar-thumb:hover{
  opacity: 1;
  width: 3px;
  background-color: #3a3a3a;
  border-radius: 5px;
  transition: 0.3s;
}

.anotherCarousel::-webkit-scrollbar-track{
  background-color: #1d1d1d;
  border-radius: 5px;
}

.individual{
  padding-right: 8px;
}

.card{
  overflow: auto;
  padding: 8px;
}

.card-title{
  text-align: left;
}

.card-text{
  text-align: left;
}

#relImg{
  border-radius: 5px;
}

#youtube{
  color: white;
  display: flex;
  justify-content: flex-start;
  transition: 0.2s;
}

#youtube:hover{
  color: #FF0000;
}

.relCont{ 
  background-color: #212121; 
  border-radius: 10px;
  height: 445px; 
  max-height: 100%;
} 

#soundcloud{
  color: white;
  transition: 0.2s;
}

#soundcloud:hover{
  color: #ff5500;
}

.socialsCont{ 
  background-color: #212121; 
  border-radius: 10px;
  max-height: 100%;
}

.socialsDiv{
  padding-left: 0px;
  float: left;
  display: flex;
  flex-direction: inline;
}

.linkDiv{
  padding-bottom: 20px;
  padding-left: 18px;
  display: flex;
  flex-direction: inline;
}

.linkDiv2{
  padding-bottom: 20px;
  display: flex;
  flex-direction: inline;
}

#facebook{
  color: white;
  transition: 0.2s;
}

#facebook:hover{
  color: #1877F2;
}

#tiktok{
  color: white;
  transition: 0.2s;
}

#tiktok:hover{
  color: #ff0050;
}

#instagram{
  color: white;
  transition: 0.2s;
}

#instagram:hover{
  color: #FCAF45;
}

#x{
  color: white;
  transition: 0.2s;
}

#x:hover{
  color: #AAB8C2;
}



@media only screen and (max-width: 720px) {

  .img {
  height: 265px;
  max-height: 100%;
  overflow: hidden; 
  }

  .img img {
    transform: scale(3.5);
  }

  .headerText{
  font-family: headerFont;
  color: white;
  font-size: 32px;
  text-align: left;
  padding-top: 15px;
  }

.paragraphText{
  font-family: paragraphFont;
  color: white;
  font-size: 20px;
  text-align: left;
  padding-top: 5px;
  }

  #carouselExampleFade{
  padding-top: 15px;
  width: 100%;
  margin: auto;
  }

  #carouselSlides{
    margin: auto;
  }

  #carouselItem{
    height: 350px;
    max-height: 100%;
    transform: scale(1.2);
  }

  #carouselItem2{
    height: 350px;
    max-height: 100%;
    transform: scale(1.5);
    margin: auto;
  }

  #carouselItem3{
  height: 350px;
  max-height: 100%;
  transform: scale(1.3);
  }

  #carouselBorder{
    border-radius: 10px;
  }

  .card{
  padding: 8px;
  }

  .anotherCarousel::-webkit-scrollbar{
    visibility:hidden;
  }

  .anotherCarousel::-webkit-scrollbar-thumb{
    visibility:hidden;
  }

  .anotherCarousel::-webkit-scrollbar-track{
    visibility:hidden;
  }

  .relCont{ 
    background-color: #212121; 
    border-radius: 10px;
    height: 410px; 
    max-height: 100%;
  } 

}

</style>
