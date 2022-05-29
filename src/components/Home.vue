<template>
  <div class="body">
    <mq-layout mq="mobile">
          <div class="container">
              <div class="head">
                  <div class="headContainer">
                      <div class="top">
                      <div class="logo">
                        <img v-bind:src="Images.passport" alt="logo" id="logo">
                        <div id="logoOverlay"></div>
                      </div>
                        <div @click="hamburger()" class="menu_btn">
                            <div class="menu-btn__burger"></div>
                        </div>
                    </div>
                  </div>
                  <div class="menu">
                    <p @click="hideMenu()" ><a href="#section-two"><span>01.<br></span> About</a></p>
                    <p @click="hideMenu()" ><a href="#section-three"><span>02.<br></span> Work</a></p>
                    <p @click="hideMenu()" ><a href="#section-four"><span>03.<br></span> Contact</a></p>
                    <p @click="hideMenu()"  id="resumeBtn"><a href="https://drive.google.com/file/d/1j0Pa1lCBtHeA-_s7beVNcBYo7_LY-eAs/view" target="blank">Resume</a></p>
                  </div>
                  <div @click="hideMenu()" class="blur"></div>
              </div>
              <div class="contents">
                  <div class="section-one">
                      <h5>Hi, my name is </h5>
                      <h2 id="name">David Oluwagbemiga. </h2>
                      <h2>I build things for the web.</h2>
                      <p>I'm a software engineer specializing in building exceptional digital experiences.
                          Currently, I'm focused on building accessible, human-centered products. </p>
                  </div>
                  <a href="" name="section-two"></a>
                <div class="section-two">
                    <div class="aboutText">
                        <p id="heading"><strong>--- </strong><span>01.</span> <b>About me</b><strong> ----------</strong></p>
                        <p id="text">
                            <span>I'm <i> David Oluwagbemiga</i></span> A highly skilled front and backend web developer with excellent knowledge in Interface design and development and comprehensive experience managing multiple clients.
                            <br><br> Very proficient in <span>graphic design,</span>  using applications such as photoshop as a design tools.
                            Excellent at NoSQL  database development and management. <br><br> I am a graduate with vast knowledge in <span>front-end</span> and <span>back-end technologies</span><span></span> .
                            Passionate and <span>hardworking</span> to deliver on deadlines I have great <span>abilities</span> to work alone and with a team. I'm also an incredibly fast learner.
                        </p>
                    </div>
                    <div class="recentTech">
                        <p>
                            Here are a few technologies I've been working with recently:
                        </p>
                        <ul>
                            <li>Javascript</li>
                            <li>CSS(SASS)</li>
                            <li>Express</li>
                            <li>HTML5</li>
                            <li>Github & Git </li>
                            <li>Photoshop</li>
                            <li>Java/PHP</li>
                        </ul>
                        <ul>
                            <li>Vue</li>
                            <li>Vue Project</li>
                            <li>VueX</li>
                            <li>Node.js</li>
                            <li>Heroku</li>
                            <li>REST APIs</li>
                            <li>MongoDB</li>
                        </ul>
                        <ul id="moreSkills">
                            <li>Project Management</li>
                            <li>Agile Methodologies</li>
                            <li>AdobeXD</li>
                            <li>Design Patterns & Principles</li>
                            <li>Understands UI/UX Principles</li>
                        </ul>
                    </div>
                    <div class="aboutImg">
                        <img :src="Images.passport" id="aboutImg">
                        <div class="frame"></div>
                    </div>
              </div>
                  <a href="" name="section-three"></a>
              <div class="section-three">
                <p id="heading"><strong>--- </strong><span>02.</span> <b>Works</b><strong> ----------</strong></p>
                <div class="works">
                    <div class="work-01">
                        <div id="img">
                        <img :src="Images.workOne" id="workOne"></div>
                        <div class="contents">
                            <h4>Featured Projects</h4>
                            <h2><a href="https://burnvermin.github.io/PlayStationCompanion/">PlayStation Companion </a></h2>
                            <p>A futuristic concept for the PlayStation 5 created by Joshua Oluwagbemiga.
                                A place where players can manage their consoles,
                                track achievements and much more. <i style="font-size: 10px;">2021</i><br>
                                <i>Joshua: <a href="https://twitter.com/JoAccord">JoAccord</a> @Twitter</i><br>
                                <i>Dribbble: <a href="https://dribbble.com/shots/11897442-PlayStation-5-Concept-UI-InVision-Studio">PlayStation 5 Concept UI</a></i>
                            </p>
                            <ul>
                                <li>Vue</li>
                                <li>VsCode</li>
                                <li>Grid Components</li>
                                <li>CSS(SASS)</li>
                                <li>Javascript</li>
                                <li>Github</li>
                            </ul>
                            <div class="icons">
                                <a href="https://github.com/burnvermin/PlayStationCompanion"><i class="fa-brands fa-github"></i></a>
                                <a href="https://burnvermin.github.io/PlayStationCompanion/"><i class="fa-solid fa-broom-ball"></i></a>
                            </div>
                        </div>
                    </div>
                    <div class="work-01">
                        <div id="img">
                        <img :src="Images.workTwo" id="workTwo"></div>
                        <div class="contents">
                            <h4>Featured Projects</h4>
                            <h2><a href="">Taxey </a></h2>
                            <p>A Web app where users can book rides from one place to another.
                                This was created by me. This only contains the client side. <i style="font-size: 10px;">2022</i><br>
                            </p>
                            <ul>
                                <li>Vue Project</li>
                                <li>Express</li>
                                <li>MongoDB</li>
                                <li>Node.js</li>
                                <li>REST APIs</li>
                                <li>Heroku</li>
                                <li>CSS(SASS)</li>
                                <li>Javascript</li>
                                <li>Github</li>
                                <li>AdobeXD</li>
                            </ul>
                            <div class="icons">
                                <a href=""><i class="fa-brands fa-github"></i></a>
                                <a href=""><i class="fa-solid fa-broom-ball"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
              </div>
                  <a href="" name="section-four"></a>
              <div class="section-four">
                  <p id="heading"><strong></strong><span>03. What's Next?</span><strong></strong></p>
                  <p id="heading"> <b>Get In Touch</b></p>
                  <p id="note">
                      I hold an advance diploma in software engineering and a university IT finalist of Middlesex Malta
                      and have been in this field for 4years+ building personal project and freelance projects.
                      Constantly honing my skills waiting for the right opportunity.
                  </p>
                  <p>I am currently open to new opportunities and my inbox is always open.</p>
                    <p>If you want to get in touch, I’ll get back to you as soon as possible!</p>
                  <button><a href="mailto: kingdavidoluwagbemiga@gmail.com">Say Hello</a></button>
              </div>
              <div class="footer">
                  <a href="https://github.com/burnvermin"><i class="fa-brands fa-github"></i></a>
                  <a href="https://twitter.com/KoningDavid_I"><i class="fa-brands fa-twitter"></i></a>
                  <a href="https://www.instagram.com/koningdavid_i/"><i class="fa-brands fa-instagram"></i></a>
                  <a href="https://www.linkedin.com/in/oluwagbemiga-david-049592165/"><i class="fa-brands fa-linkedin"></i></a>
                    <p>Designed &#38; Built by David Oluwagbemiga</p>
              </div>
          </div>
      </div>
    </mq-layout>
    <mq-layout mq="tablet+" class="container2">
          <div class="container">
              <div class="head">
                  <div class="headContainer">
                      <div class="top">
                      <div class="logo">
                        <img v-bind:src="Images.passport" alt="logo" id="logo">
                        <div id="logoOverlay"></div>
                        </div>
                        <div class="menu">
                            <p ><a href="#section-two"><span>01.</span> About</a></p>
                            <p ><a href="#section-three"><span>02.</span> Work</a></p>
                            <p ><a href="#section-four"><span>03.</span> Contact</a></p>
                            <p id="resumeBtn"><a href="https://drive.google.com/file/d/1j0Pa1lCBtHeA-_s7beVNcBYo7_LY-eAs/view" target="blank">Resume</a></p>
                        </div>
                    </div>
                  </div>
              </div>
              <div class="contents">
                  <div class="section-one">
                      <h5>Hi, my name is </h5>
                      <h2 id="name">David Oluwagbemiga. </h2>
                      <h2>I build things for the web.</h2>
                      <p>I'm a software engineer specializing in building exceptional digital experiences.
                          Currently, I'm focused on building accessible, human-centered products. </p>
                  </div>
                  <a href="" name="section-two"></a>
                <div class="section-two">
                    <p id="heading"><strong>--- </strong><span>01.</span> <b>About me</b><strong> ----------</strong></p>
                    <div class="aboutText">
                        <div class="text">
                            <p id="text">
                                <span>I'm <i> David Oluwagbemiga</i></span> A highly skilled front and backend web developer with excellent knowledge in Interface design and development and comprehensive experience managing multiple clients.
                                <br><br> Very proficient in <span>graphic design,</span>  using applications such as photoshop as a design tools.
                                Excellent at NoSQL  database development and management. <br><br> I am a graduate with vast knowledge in <span>front-end</span> and <span>back-end technologies</span><span></span> .
                                Passionate and <span>hardworking</span> to deliver on deadlines I have great <span>abilities</span> to work alone and with a team. I'm also an incredibly fast learner.
                            </p>
                            <div class="recentTech">
                                <p>
                                    Here are a few technologies I've been working with recently:
                                </p>
                                <ul>
                                    <li>Javascript</li>
                                    <li>CSS(SASS)</li>
                                    <li>Express</li>
                                    <li>HTML5</li>
                                    <li>Github & Git </li>
                                    <li>Photoshop</li>
                                    <li>Java/PHP</li>
                                </ul>
                                <ul>
                                    <li>Vue</li>
                                    <li>Vue Project</li>
                                    <li>VueX</li>
                                    <li>Node.js</li>
                                    <li>Heroku</li>
                                    <li>REST APIs</li>
                                    <li>MongoDB</li>
                                </ul>
                                <ul id="moreSkills">
                                    <li>Project Management</li>
                                    <li>Agile Methodologies</li>
                                    <li>AdobeXD</li>
                                    <li>Design Patterns & Principles</li>
                                    <li>Understands UI/UX Principles</li>
                                </ul>
                            </div>
                        </div>
                        <div class="aboutImg">
                            <img :src="Images.passport" id="aboutImg">
                            <div class="frame"></div>
                        </div>
                    </div>
              </div>
                  <a href="" name="section-three"></a>
              <div class="section-three">
                <p id="heading"><strong>--- </strong><span>02.</span> <b>Works</b><strong> ----------</strong></p>
                <div class="works">
                    <div class="work-01">
                        <div id="img">
                        <img :src="Images.workOne" id="workOne">
                        <div class="frame"></div>
                        </div>
                        <div class="contents">
                            <h4>Featured Project</h4>
                            <h2><a href="https://burnvermin.github.io/PlayStationCompanion/">PlayStation Companion </a></h2>
                            <p>A futuristic concept for the PlayStation 5 created by Joshua Oluwagbemiga.
                                A place where players can manage their consoles,
                                track achievements and much more. <i style="font-size: 10px;">2021</i><br>
                                <i>Joshua: <a href="https://twitter.com/JoAccord">JoAccord</a> @Twitter</i><br>
                                <i>Dribbble: <a href="https://dribbble.com/shots/11897442-PlayStation-5-Concept-UI-InVision-Studio">PlayStation 5 Concept UI</a></i>
                            </p>
                            <ul>
                                <li>Vue</li>
                                <li>VsCode</li>
                                <li>Grid Components</li>
                                <li>CSS(SASS)</li>
                                <li>Javascript</li>
                                <li>Github</li>
                            </ul>
                            <div class="icons">
                                <a href="https://github.com/burnvermin/PlayStationCompanion"><i class="fa-brands fa-github"></i></a>
                                <a href="https://burnvermin.github.io/PlayStationCompanion/"><i class="fa-solid fa-broom-ball"></i></a>
                            </div>
                        </div>
                    </div>
                    <div class="work-01">
                        <div id="img">
                        <img :src="Images.workTwo" id="workTwo">
                        <div class="frame"></div>
                        </div>
                        <div class="contents">
                            <h4>Featured Project</h4>
                            <h2><a href="">Taxey </a></h2>
                            <p>A Web app where users can book rides from one place to another.
                                This was created by me. This only contains the client side. <i style="font-size: 10px;">2022</i><br>
                            </p>
                            <ul>
                                <li>Vue Project</li>
                                <li>Express</li>
                                <li>MongoDB</li>
                                <li>Node.js</li>
                                <li>REST APIs</li>
                                <li>Heroku</li>
                                <li>CSS(SASS)</li>
                                <li>Javascript</li>
                                <li>Github</li>
                                <li>AdobeXD</li>
                            </ul>
                            <div class="icons">
                                <a href=""><i class="fa-brands fa-github"></i></a>
                                <a href=""><i class="fa-solid fa-broom-ball"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
              </div>
                  <a href="" name="section-four"></a>
              <div class="section-four">
                  <p id="heading"><strong></strong><span>03. What's Next?</span><strong></strong></p>
                  <p id="heading"> <b>Get In Touch</b></p>
                  <p id="note">
                      I hold an advance diploma in software engineering and a university IT finalist of Middlesex Malta
                      and have been in this field for 4years+ building personal project and freelance projects.
                      Constantly honing my skills waiting for the right opportunity.
                  </p>
                  <p>I am currently open to new opportunities and my inbox is always open.</p>
                    <p>If you want to get in touch, I’ll get back to you as soon as possible!</p>
                  <button><a href="mailto: kingdavidoluwagbemiga@gmail.com">Say Hello</a></button>
              </div>
              <div class="footer">
                  <div class="links">
                    <p>|</p>
                    <a href="https://github.com/burnvermin"><i class="fa-brands fa-github"></i></a><br>
                    <a href="https://twitter.com/KoningDavid_I"><i class="fa-brands fa-twitter"></i></a><br>
                    <a href="https://www.instagram.com/koningdavid_i/"><i class="fa-brands fa-instagram"></i></a><br>
                    <a href="https://www.linkedin.com/in/oluwagbemiga-david-049592165/"><i class="fa-brands fa-linkedin"></i></a><br>
                    <p>|</p>
                  </div>
                  <a href="mailto: kingdavidoluwagbemiga@gmail.com"><p id="mail">kingdavidoluwagbemiga@gmail.com-------</p></a>
                  <p>Designed &#38; Built by David Oluwagbemiga</p>
              </div>
          </div>
      </div>
    </mq-layout>
  </div>
</template>

<script>

import passport from '../assets/Images/dp.png'
import five from '../assets/Images/five.png'
import seven from '../assets/Images/seven.png'

export default {
  props: {

  },
  data () {
    return {
      Images: {
        passport: passport,
        workOne: seven,
        workTwo: five
      },
      menuOpen: false

    }
  },
  computed: {

  },

  mounted: function () {
    const menu = document.querySelector('.menu')
    const blur = document.querySelector('.blur')
    menu.classList.add('show')
    blur.classList.add('show')
  },
  methods: {
    hamburger () {
      const menuBtn = document.querySelector('.menu_btn')
      const menu = document.querySelector('.menu')
      const blur = document.querySelector('.blur')
      if (!this.menuOpen) {
        menuBtn.classList.add('open')
        menu.classList.remove('show')
        blur.classList.remove('show')
        document.querySelector('.headContainer').classList.add('showHeadContainer')
        this.menuOpen = true
      } else {
        menuBtn.classList.remove('open')
        menu.classList.add('show')
        blur.classList.add('show')
        document.querySelector('.headContainer').classList.remove('showHeadContainer')
        this.menuOpen = false
      }
    },
    hideMenu () {
      const menuBtn = document.querySelector('.menu_btn')
      const menu = document.querySelector('.menu')
      const blur = document.querySelector('.blur')
      menuBtn.classList.remove('open')
      menu.classList.add('show')
      blur.classList.add('show')
      document.querySelector('.headContainer').classList.remove('showHeadContainer')
      this.menuOpen = false
    }
  }

}
</script>

<style scoped lang="scss">
    *{
        box-sizing: border-box;
    }

    $lightCyanColor: rgb(5, 255, 255);
    $darkCyanColor: rgb(3, 53, 100);
    $darkerCyanColor: rgb(0, 20, 39);
    $grey: rgb(177, 177, 177);

    .body {
        background-color: $darkerCyanColor;
        width: 100%;
        height: 100%;
        padding: 0px;
        color: $grey;
    }
    //Mobile Styles
    .container {
        position: relative;
        .head {
            position: relative;
            .headContainer {
                position: fixed;
                width: 100%;
                z-index: 5;
                background-color: rgba(0, 20, 39, .5);
                backdrop-filter: blur(5px);
                left: 0;
                top: 0;
                padding: 10px;
            }
            .headContainer.showHeadContainer {
                background-color: rgba(255, 255, 255, 0);
                backdrop-filter: blur(0px);
            }
            .top {
                .logo {
                    position: relative;
                    width: 60px;
                    height: 60px;
                    z-index: 6;
                    #logo{
                        margin-top: 5px;
                        margin-left: 5px;
                        width: 50px;
                        height: 50px;
                        border-radius: 50px;
                    }
                    #logoOverlay {
                        position: absolute;
                        top: 0;
                        border-radius: 50px;
                        opacity: .2;
                        width: 60px;
                        height: 60px;
                        background-color: $lightCyanColor;
                        z-index: 2;
                    }
                }
            }
            .menu_btn {
                position: absolute;
                right: 5%;
                top: 25%;
                height: 50px;
                padding-top: 10%;
                display: flex;
                justify-content: right;
                align-items: right;
                cursor: pointer;
                transition: all .5s ease-in-out;
                z-index: 6;
                transform: scale(.7);

                 .menu-btn__burger{
                    width: 40px;
                    height: 3px;
                    margin-top: -55%;
                    background: $lightCyanColor;
                    border-radius: 5px;
                    transition: all .2s ease-in-out;
                }
                .menu-btn__burger::before {
                    content: '';
                    position: absolute;
                    top: 35%;
                    right: 0;
                    width: 50px;
                    height: 3px;
                    background: $lightCyanColor;
                    border-radius: 5px ;
                    transition: all .2s ease-in-out;

                }
                .menu-btn__burger::after {
                    content: '';
                    position: absolute;
                    right: 0;
                    width: 30px;
                    height: 3px;
                    background: $lightCyanColor;
                    border-radius: 5px ;
                    transition: all .2s ease-in-out;
                }
            }
            .menu-btn__burger::before {
                transform: translateY(-12px);
            }
            .menu-btn__burger::after {
                transform: translateY(12px);
            }
            .menu_btn.open .menu-btn__burger {
                background: transparent;
            }
            .menu_btn.open .menu-btn__burger::before {
                transform: rotate(45deg) ;
            }
            .menu_btn.open .menu-btn__burger::after {
                width: 50px;
                transform: rotate(-45deg);
            }
            .menu.show, .blur.show {
                display: none;
            }

            .menu {
                text-align: center;
                position: fixed;
                background-color: $darkCyanColor;
                width: 80%;
                height: 100%;
                top: 0;
                right: 0;
                display: flex;
                flex-direction: column;
                align-items: center;
                justify-content: center;
                z-index: 4;
                box-shadow: 5px 20px 20px #000000;

                p {
                    a {
                        text-decoration: none;
                        color: #fff;
                        span {
                            color: $lightCyanColor;
                        }
                    }

                    a:hover {
                        font-weight: bold;
                        color: $lightCyanColor;
                    }
                }
                #resumeBtn {
                    border-color: $lightCyanColor;
                    border-style: solid;
                    border-width: 2px;
                    border-radius: 5px;
                    position: relative;
                    padding: 10px 20px;
                    left: 0;
                    color: $lightCyanColor;
                }

                #resumeBtn:hover {
                    a {
                        font-weight: normal;
                    }
                    background-color: rgba(5, 255, 255, .1);
                }

            }

            .blur {
                position: fixed;
                width: 50vw;
                height: 100vh;
                top: 0;
                left: 0;
                backdrop-filter: blur(5px);
                z-index: 3;
            }
        }
        .contents {
            padding: 25px;
            position: relative;
            .section-one {
                margin-top: 50%;
                p {
                    font-size: 18px;
                    margin: 0;
                }
                h5 {
                    color: $lightCyanColor;
                    font-size: 18px;
                    margin: 0;
                }
                h2 {
                    font-weight: bolder;
                    font-size: 40px;
                    margin: 0;
                    padding: 15px 0px;
                }
                #name {
                    color: white;
                }
            }
            p {
                span {
                    color: $lightCyanColor;
                }
            }
            #heading {
                b {
                    font-size: 20px;
                    color: white;
                }
            }
            .section-two {
                margin-top: 55%;
                .aboutText {
                    text-align: center;
                }
                .recentTech {
                    position: relative;
                    p {
                        margin: auto;
                        text-align: left;
                    }
                    ul {
                        width: 40%;
                        margin-left: -2%;
                        float: left;
                        li {
                            text-align: left;
                            list-style-type: circle;
                            list-style: none;
                        }
                        li::before {
                            content: "\2023";
                            color: $lightCyanColor;
                            font-weight: bold;
                            display: inline-block;
                            transform: rotate(180deg);
                            width: .8em;
                            margin-right: 10px;
                            margin-left: -2.5em;
                        }
                    }
                    #moreSkills {
                        width: 80%;
                    }
                }
                .aboutImg {
                    clear: both;
                    position: relative;
                    padding-top: 5%;
                    width: 220px;
                    justify-content: center;
                    #aboutImg  {
                        width: 100%;
                        margin-left: 15%;
                        position: relative;
                        border-radius: 5px;
                        z-index: 1;
                    }
                    .frame {
                        position: absolute;
                        width: 100%;
                        height: 91%;
                        border: 2px solid $lightCyanColor;
                        background-color: rgba(5, 255, 255, .5);
                        border-radius: 5px;
                        top: 15%;
                        left: 25%;
                        transition: all 200ms ease-in-out;
                        z-index: 1;
                    }
                }
                .aboutImg:hover {
                    .frame {
                        top: 12%;
                        left: 22%;
                        background-color: rgba(5, 255, 255, 0);
                        z-index: 0;
                        transition: all 200ms ease-in-out;
                    }
                }
            }
            .section-three {
                margin-top: 50%;
                text-align: center;
                #heading {
                    margin: 0 0 15% 0;
                }
                .works {
                    .work-01 {
                        position: relative;
                        padding: 15% 0;
                        #img {
                            overflow-X: scroll;
                            z-index: 1;
                            img {
                                width: 200%
                            }
                        }
                        .contents {
                            position: absolute;
                            text-align: left;
                            padding-top: 20%;
                            top: 0;
                            height: 100%;
                            z-index: 2;
                            background-color: rgba(0, 20, 39, .92);
                            h4, h2, p {
                                margin: 0;
                            }
                            h4 {
                                color: $lightCyanColor;
                                font-size: 14px;
                                padding: 2px 0px;
                            }
                            h2 {
                                color: #fff;
                                font-size: 20px;
                                a {
                                    text-decoration: none;
                                    color: #fff;
                                }
                                a:hover {
                                    color: $lightCyanColor;
                                }
                            }
                            p {
                                font-size: 14px;
                                padding: 20px 0px;
                                a {
                                    text-decoration: none;
                                    color: #fff;
                                }
                                a:hover {
                                    color: $lightCyanColor;
                                }
                            }
                            ul {
                                font-size: 12px;
                                list-style: none;
                                padding: 0;
                                li {
                                    float: left;
                                    padding: 5px 5px 0px 5px;
                                }
                            }
                            .icons {
                                clear: both;
                                padding: 20px 0px;
                                position: relative;
                                cursor: pointer;
                                i:hover {
                                    color: $lightCyanColor;
                                }
                                a {
                                    text-decoration: none;
                                    color: inherit;
                                }
                                i {
                                    padding-left: 2%;
                                }

                            }

                        }
                    }
                }
            }
            .section-four {
                text-align: center;
                margin-top: 50%;
                #heading b {
                    font-size: 28px;
                    font-weight: bolder;
                }
                #note{
                    text-align: left;
                }
                button {
                    border-color: $lightCyanColor;
                    background-color: transparent;
                    border-style: solid;
                    border-width: 2px;
                    border-radius: 5px;
                    position: relative;
                    padding: 10px 20px;
                    left: 0;
                    margin: 20px auto;
                    cursor: pointer;
                    a{
                        color: $lightCyanColor;
                        text-decoration: none;
                    }
                }
                button:hover {
                    background-color: rgba(5, 255, 255, .1);
                }
            }
            .footer {
                margin-top: 40%;
                padding: 5%;
                text-align: center;
                a {
                    text-decoration: none;
                    padding: 10px 0 0 30px;
                    color: $grey;
                    font-size: 28px;
                }
                a:hover {
                    color: $lightCyanColor;
                }
                p {
                    padding: 10px 0 ;
                    font-size: 14px;
                }
            }
        }
    }
    .container2 {
        .container {
            .head {
                .headContainer {
                    position: fixed;
                    width: 100%;
                    z-index: 5;
                    background-color: rgba(0, 20, 39, .5);
                    backdrop-filter: blur(5px);
                    left: 2%;
                    padding: 50px 10px 10px 10px;
                }
                .menu {
                    text-align: center;
                    position: absolute;
                    background: none;
                    width: auto;
                    height: auto;
                    top: 25%;
                    right: 5%;
                    display: flex;
                    flex-direction: row;
                    z-index: 4;
                    box-shadow: 0px 0px 0px 0px;

                    p {
                        padding: 5px 30px 0 0px;
                        a {
                            text-decoration: none;
                            color: #fff;
                            span {
                                color: $lightCyanColor;
                            }
                        }

                        a:hover {
                            font-weight: bold;
                            color: $lightCyanColor;
                        }
                    }
                    #resumeBtn {
                        border-color: $lightCyanColor;
                        border-style: solid;
                        border-width: 2px;
                        border-radius: 5px;
                        position: relative;
                        padding: 10px 20px;
                        left: 0;
                        color: $lightCyanColor;
                    }

                    #resumeBtn:hover {
                        a {
                            font-weight: normal;
                        }
                        background-color: rgba(5, 255, 255, .1);
                    }

                }
            }
            .contents {
                padding: 5% 15%;
                position: relative;
                .section-one {
                    margin-top: 25%;
                    p {
                        font-size: 18px;
                        margin: 0;
                    }
                    h5 {
                        color: $lightCyanColor;
                        font-size: 18px;
                        margin: 0;
                    }
                    h2 {
                        font-weight: bolder;
                        font-size: 40px;
                        margin: 0;
                        padding: 15px 0px;
                    }
                    #name {
                        color: white;
                        padding-bottom: 0px;
                    }
                }
                p {
                    span {
                        color: $lightCyanColor;
                    }
                }
                #heading {
                    b {
                        font-size: 20px;
                        color: white;
                    }
                }
                .section-two {
                    margin-top: 55%;
                    #heading {
                        margin-bottom: 20%;
                    }
                    .aboutText {
                        text-align: left;
                        display: flex;
                        flex-direction: row;
                        .text {
                            flex: 60%;
                            p {
                                margin: 0;
                            }
                        }
                    }
                    .recentTech {
                        position: relative;
                        p {
                            margin: auto;
                            text-align: left;
                        }
                        ul {
                            width: 40%;
                            margin-left: -2%;
                            float: left;
                            li {
                                text-align: left;
                                list-style-type: circle;
                                list-style: none;
                            }
                            li::before {
                                content: "\2023";
                                color: $lightCyanColor;
                                font-weight: bold;
                                display: inline-block;
                                transform: rotate(180deg);
                                width: .8em;
                                margin-right: 10px;
                                margin-left: -2.5em;
                            }
                        }
                        #moreSkills {
                            width: 80%;
                        }
                    }
                    .aboutImg {
                        clear: both;
                        position: relative;
                        justify-content: center;
                        flex: 40%;
                        height: 40%;
                        padding-top: 0;
                        margin-left: 2%;
                        .text {
                            padding-top: 0;
                        }
                        #aboutImg  {
                            margin: 0;
                            width: 100%;
                            height: 100%;
                            position: relative;
                            border-radius: 5px;
                            z-index: 1;
                        }
                        .frame {
                            position: absolute;
                            width: 100%;
                            height: 100%;
                            border: 2px solid $lightCyanColor;
                            background-color: rgba(5, 255, 255, .5);
                            border-radius: 5px;
                            top: 7%;
                            left: 10%;
                            transition: all 200ms ease-in-out;
                            z-index: 1;
                        }
                    }
                    .aboutImg:hover {
                        .frame {
                            top: 4%;
                            left: 7%;
                            background-color: rgba(5, 255, 255, 0);
                            z-index: 0;
                            transition: all 200ms ease-in-out;
                        }
                    }
                }
                .section-three {
                    margin-top: 20%;
                    text-align: center;
                    #heading {
                        margin: 0 0 15% 0;
                    }
                    .works {
                        .work-01 {
                            position: relative;
                            padding: 0% 0 10%;
                            #img:hover {
                                transform: scale(1.1);
                                transition: all 500ms;
                                z-index: 9;
                                .frame {
                                    z-index: -1;
                                }

                            }
                            #img {
                                position: relative;
                                overflow-X: hidden;
                                width: 60%;
                                z-index: 0;
                                left: 0;
                                transition: all 500ms;
                                img {
                                    width: 100%;
                                }
                                img:hover{
                                    z-index: 5;
                                }
                                .frame {
                                    position: absolute;
                                    width: 100%;
                                    height: 100%;
                                    top: 0;
                                    background-color: rgba(0, 20, 39, .7);
                                    border-radius: 5px;
                                    transition: all 200ms ease-in-out;
                                    z-index: 0;
                                }
                            }
                            .contents {
                                position: absolute;
                                text-align: right;
                                padding-top: 0%;
                                padding: 0%;
                                height: 90%;
                                width: 70%;
                                top: 0;
                                right: 0;
                                z-index: 4;
                                background:none;
                                margin: 5% 0;
                                h4, h2, p {
                                    margin: 0;
                                }
                                h4 {
                                    color: $lightCyanColor;
                                    font-size: 14px;
                                    padding: 2px 0px;
                                }
                                h2 {
                                    color: #fff;
                                    font-size: 20px;
                                    a {
                                        text-decoration: none;
                                        color: #fff;
                                    }
                                    a:hover {
                                        color: $lightCyanColor;
                                    }
                                }
                                p {
                                    background-color: $darkCyanColor;
                                    border-radius: 5px;
                                    font-size: 14px;
                                    padding: 20px 20px;
                                    float: right;
                                    margin-top: 2%;
                                    a {
                                        text-decoration: none;
                                        color: #fff;
                                    }
                                    a:hover {
                                        color: $lightCyanColor;
                                    }
                                }
                                ul {
                                    clear: both;
                                    font-size: 12px;
                                    list-style: none;
                                    padding: 0;
                                    li {
                                        float: right;
                                        padding: 5px 5px 0px 5px;
                                    }
                                }
                                .icons {
                                    clear: both;
                                    padding: 20px 0px;
                                    position: relative;
                                    cursor: pointer;
                                    i:hover {
                                        color: $lightCyanColor;
                                    }
                                    a {
                                        text-decoration: none;
                                        color: inherit;
                                    }
                                    i {
                                        padding-left: 2%;
                                    }

                                }

                            }
                        }
                    }
                }
                .section-four {
                    text-align: center;
                    margin-top: 5%;
                    width: 50%;
                    margin: auto;
                    #heading b {
                        font-size: 28px;
                        font-weight: bolder;
                    }
                    #note{
                        text-align: center;
                    }
                    button {
                        border-color: $lightCyanColor;
                        background-color: transparent;
                        border-style: solid;
                        border-width: 2px;
                        border-radius: 5px;
                        position: relative;
                        padding: 10px 20px;
                        left: 0;
                        margin: 20px auto;
                        cursor: pointer;
                        a{
                            color: $lightCyanColor;
                            text-decoration: none;
                        }
                    }
                    button:hover {
                        background-color: rgba(5, 255, 255, .1);
                    }
                }
                .footer {
                    margin-top: 0%;
                    padding: 5%;
                    text-align: center;
                    .links {
                        position: fixed;
                        bottom: 0;
                        left: 2%;
                    }
                    a {
                        text-decoration: none;
                        padding: 20px;
                        color: $grey;
                        font-size: 28px;
                    }
                    a:hover {
                        color: $lightCyanColor;
                    }
                    p {
                        padding: 10px 0 ;
                        font-size: 14px;
                    }
                    #mail {
                        position: fixed;
                        bottom: 13%;
                        transform: rotate(90deg);
                        right: -3%;
                    }
                }
            }
        }
    }
</style>
