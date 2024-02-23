<template>
        <q-page>
        <!-- <div> -->
          <div style="height: 100%; background-position: center; background-repeat: no-repeat; background-size: cover; background-image: url(https://img.freepik.com/premium-vector/abstract-blue-wave-banner-template-design_998164-96.jpg?w=1380); object-fit: contain;">
            <!-- <div class="col"> -->
            <div class="text-center q-py-xl">
              <h4 class="sec1">Frontend Developer Course with Placement</h4>
              <h4 class="sec111">Get a dream tech job with 100% Placement Guarantee</h4>
              <div>
                <marquee class="marq" behavior="" direction="" width="1000px">
                <img class="marq1" src="https://blog.harveydelaney.com/content/images/size/w2000/2019/08/react.jpg" width="230px" style="object-fit: contain; overflow: hidden; background-repeat: no-repeat;" alt="">
                <img class="marq1" src="https://www.audero.it/blog/wp-content/uploads/2014/09/front-end-stack.png" width="325px" style="object-fit: contain; overflow: hidden; background-repeat: no-repeat;" alt="">
                <img class="marq1" src="https://ruky.me/wp-content/uploads/2021/08/bootstrap-5-releases-with-major-changes.jpg" width="220px" style="object-fit: contain; overflow: hidden; background-repeat: no-repeat;" alt="">
              </marquee>
              </div>
              <h4 class="sec11">Pay Upto 80% Course Fee After Getting a Job.</h4>
              <h4 class="sec12"><b>Earn up to 10 LPA</b></h4>
              <!-- <h4 class="sec13 q-mt-xl" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Our Enrollment Process</h4> -->
              <p class="sec14">Click Here To Enquire Our Education Curriculum</p>
              <!-- <q-btn push color="light-blue-2" text-color="deep-purple-10" style="width: 200px; height: 50px;" label="Enroll Now" /> -->
              <div>
              <q-btn class="q-mt-xl" push @click="open('top')" color="light-blue-2 text-weight-bold" text-color="deep-purple-10" style="letter-spacing: 2px; font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; width: 200px; height: 50px;" label="Enquiery" />

              <q-dialog v-model="dialog" :position="position">
                <q-card style="width: 350px" class="bg-light-blue-1">
                  <q-linear-progress :value="1" color="deep-purple-10" />
                  <q-card-section>
                    <div>
                      <div class="q-pa-md text-center text-brown-14"><b style="letter-spacing: 2px;">Take your first step in EdexTech</b></div>
                      <!-- <div class="text-grey">Fitz & The Tantrums</div> -->
                      <div class="q-pa-xl flex items-center q-gutter-xl">
                        <q-input color="blue-10" outlined v-model="text" label="Name">
                          <template v-slot:append>
                        <q-avatar>
                          <img src="https://digikull.com/_next/static/media/user.b051d75a.png">
                        </q-avatar>
                          </template>
                        </q-input>
                        <q-input color="blue-10" outlined v-model="text" label="Gmail">
                          <template v-slot:append>
                        <q-avatar>
                          <img src="https://digikull.com/_next/static/media/gmail.fdeca59f.png">
                        </q-avatar>
                          </template>
                        </q-input>
                        <q-input color="blue-10" outlined v-model="text" label="Contact No.">
                          <template v-slot:append>
                        <q-avatar>
                          <img src="https://digikull.com/_next/static/media/whatapp.92e48152.png">
                        </q-avatar>
                          </template>
                        </q-input>
                        <!-- <div class=""> -->
                          <q-btn color="light-blue-2 text-weight-bold" text-color="deep-purple-10" style="letter-spacing: 2px; font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; width: 200px; height: 50px;" label="SUBMIT">
                          <q-tooltip class="bg-pink-10">Submit</q-tooltip>
                          </q-btn>
                        <!-- </div> -->
                      </div>

                    </div>
                    <q-space />
                    <!-- <q-btn flat round icon="fast_rewind" />
                    <q-btn flat round icon="pause" />
                    <q-btn flat round icon="fast_forward" /> -->
                  </q-card-section>
                  <q-linear-progress :value="1" color="deep-purple-10" />
                </q-card>
              </q-dialog>
              </div>
            </div>
            <!-- </div> -->
          </div>


    <section style="background-image: linear-gradient(to right, rgba(255, 255, 255, 0.733), rgb(206, 224, 251));">
      <div class="row q-px-xl">
        <div class="q-mt-md col-12 col-lg-6">
        <!-- <h4 class="text-center" style="font-size: 1rem; word-spacing: 2px; font-family:Verdana, Geneva, Tahoma, sans-serif ;">
          <b>FrontEnd Developer Courses</b>
        </h4> -->
        <div class="text-center">
      <h4 style="font-size: 2rem; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">
      <b> FrontEnd Developer Courses</b>
    </h4></div>
        <p class="text-center">Are you ready to take your first step into the dynamic realm of web development? This comprehensive Front-End Development Course offers an immersive learning experience that equips you with the skills to craft captivating user interfaces and seamless interactions. Whether you're aspiring to become a certified front-end developer or simply want to learn the ropes of modern web design, this course is tailored to meet your goals.</p>
        <div>
            <!-- <ul class=""> -->
              <div class="sec234">
                <div class="q-pa-md text-center">
                <q-expansion-item
                  class="shadow-1 overflow-hidden"
                  style="border-radius: 30px"
                  icon="fa-brands fa-html5"
                  label="HTML"
                  header-class="bg-indigo-2 text-brown-10"
                  expand-icon-class="text-indigo-10"
                >
                <q-card>
                  <q-card-section>
                    Dive into the heart of modern web development with React, the widely acclaimed JavaScript library for building user interfaces. You'll master the art of creating reusable components, managing state, and crafting responsive designs that adapt seamlessly to various devices and screen sizes.
                  </q-card-section>
                </q-card>
                </q-expansion-item>
                </div>
              </div><br>
              <div class="sec234">
                <div class="q-pa-md text-center">
                <q-expansion-item
                  class="shadow-1 overflow-hidden"
                  style="border-radius: 30px"
                  icon="fa-brands fa-css3-alt"
                  label="CSS"
                  header-class="bg-purple-2 text-brown-10"
                  expand-icon-class="text-purple-10"
                >
                <q-card>
                  <q-card-section>
                    Discover how to maintain the state of your application in a centralized and predictable manner using Redux. Harness the power of this state management library to streamline data flow, enhance maintainability, and simplify debugging in your projects.
                  </q-card-section>
                </q-card>
                </q-expansion-item>
                </div>
              </div><br>
              <div class="sec234">
                <div class="q-pa-md text-center">
                <q-expansion-item
                  class="shadow-1 overflow-hidden"
                  style="border-radius: 30px"
                  icon="fa-brands fa-js"
                  label="JavaScript"
                  header-class="bg-amber-2 text-brown-10"
                  expand-icon-class="text-amber-10"
                >
                <q-card>
                  <q-card-section>
                    Build a strong foundation in JavaScript, the language that underpins the web. Learn the latest features of ES6 (ECMAScript 2015) to write clean, efficient, and modern code. From variables and functions to asynchronous programming, you'll grasp essential concepts that empower you to create dynamic and interactive web applications.
                  </q-card-section>
                </q-card>
                </q-expansion-item>
                </div>
              </div><br>
              <div class="sec234">
                <div class="q-pa-md text-center">
                <q-expansion-item
                  class="shadow-1 overflow-hidden"
                  style="border-radius: 30px"
                  icon="fa-solid fa-certificate"
                  label="Certification Opportunity"
                  header-class="bg-deep-orange-2 text-brown-10"
                  expand-icon-class="text-orange-10"
                >
                <q-card>
                  <q-card-section>
                    Upon successful completion of the course, you'll earn a Front-End Developer Certification, showcasing your proficiency in crafting engaging user interfaces and implementing cutting-edge web technologies.
                  </q-card-section>
                </q-card>
                </q-expansion-item>
                </div>
              </div><br>
              <div class="sec234">
                <div class="q-pa-md text-center">
                <q-expansion-item
                  class="shadow-1 overflow-hidden"
                  style="border-radius: 30px"
                  icon="fa-solid fa-chalkboard-user"
                  label="Flexible Learning"
                  header-class="bg-blue-grey-2 text-brown-10"
                  expand-icon-class="text-grey-10"
                >
                <q-card>
                  <q-card-section>
                    Our course is designed to accommodate various learning styles and schedules. Whether you're a working professional or a student, you can choose from part-time or full-time options to suit your availability.
                  </q-card-section>
                </q-card>
                </q-expansion-item>
                </div>
              </div><br>
              <div class="sec234">
                <div class="q-pa-md text-center">
                <q-expansion-item
                  class="shadow-1 overflow-hidden"
                  style="border-radius: 30px"
                  icon="fa-solid fa-indian-rupee-sign"
                  label="Affordable Fees"
                  header-class="bg-lime-2 text-brown-10"
                  expand-icon-class="text-lime-10"
                >
                <q-card>
                  <q-card-section>
                    We believe in making quality education accessible. Our Front-End Developer Course offers competitive and transparent pricing, ensuring you receive exceptional value for your investment in your education and career.
                  </q-card-section>
                </q-card>
                </q-expansion-item>
                </div>
              </div><br>
              <div class="sec234">
                <div class="q-pa-md text-center">
                <q-expansion-item
                  class="shadow-1 overflow-hidden"
                  style="border-radius: 30px"
                  icon="fa-solid fa-book-open-reader"
                  label="Comprehensive Syllabus"
                  header-class="bg-light-green-2 text-brown-10"
                  expand-icon-class="text-green-10"
                >
                <q-card>
                  <q-card-section>
                    The course syllabus covers a wide range of topics, including HTML5, CSS3, responsive design principles, version control with Git, and more. You'll graduate with a holistic understanding of front-end web development that prepares you for real-world challenges
                  </q-card-section>
                </q-card>
                </q-expansion-item>
                </div>
              </div><br>
              <div class="sec234">
                <div class="q-pa-md text-center">
                <q-expansion-item
                  class="shadow-1 overflow-hidden"
                  style="border-radius: 30px"
                  icon="fa-solid fa-house-circle-check"
                  label="Find a Course Near You"
                  header-class="bg-cyan-2 text-brown-10"
                  expand-icon-class="text-cyan-10"
                >
                <q-card>
                  <q-card-section>
                    With multiple learning centers across the region, finding a Front-End Developer Course near you has never been easier. Join our community of learners, collaborate with peers, and receive hands-on guidance from experienced instructors.
                  </q-card-section>
                </q-card>
                </q-expansion-item>
                </div>
              </div>
            <!-- </ul> -->
        </div>

        <div class="flex justify-center">
          <div style="margin-top: 40px;">
          <p class="sec231 flex">
            <img width="31" height="31" style="color:transparent" src="https://digikull.com/_next/static/media/check_mark.c8ad281a.webp">
            <div class="flex items-center">7+ technologies you will learn</div>
          </p>
          <p class="sec231 flex">
            <img width="31" height="31" style="color:transparent" src="https://digikull.com/_next/static/media/check_mark.c8ad281a.webp">
            <div class="flex items-center">30+ assignments</div>
          </p>
          <p class="sec231 flex">
            <img width="31" height="31" style="color:transparent" src="https://digikull.com/_next/static/media/check_mark.c8ad281a.webp">
            <div class="flex items-center">Unlimited Mock interviews</div>
          </p>
          </div>
        </div>

      </div>
      <div class="col-12 col-lg-6" style="overflow-x: hidden; overflow-y: hidden; overflow: hidden;">
        <div class="row text-center flex flex-center">
          <div class="box col-lg-6 q-gutter-xl q-pa-xl">
            <div class="boxhover q-pa-xl" style="background-color: rgb(8,33,62); border-radius: 20px; width: 200px; height: 200px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.7), 0 6px 20px 0 rgba(0, 0, 0, 0.25);">
              <img src="https://digikull.com/_next/static/media/time.0bde4799.webp" width="50" alt="">
              <div class="text-white q-mt-md">
                <p style="font-size: 11px;"><b style="color: rgb(0,241,19); ">130+ Hrs</b> of live interactive classes</p>
              </div>
            </div>
            <div class="boxhover q-pa-xl" style="background-color: rgb(8,33,62); border-radius: 20px; width: 200px; height: 200px;  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.7), 0 6px 20px 0 rgba(0, 0, 0, 0.25);">
              <img src="https://digikull.com/_next/static/media/guarantee.e5e5af80.webp" width="50" alt="">
              <div class="text-white q-mt-md">
                <p style="font-size: 11px;"><b style="color: rgb(199,204,9);">100 %</b> placement Guarantee</p>
              </div>
            </div>
            <div class="boxhover q-pa-xl" style="background-color: rgb(8,33,62); border-radius: 20px; width: 200px; height: 200px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.7), 0 6px 20px 0 rgba(0, 0, 0, 0.25);">
              <img src="https://digikull.com/_next/static/media/react.ef7bacca.webp" width="70" alt="">
              <div class="text-white q-mt-md">
                <p style="font-size: 11px;"><b style="color: rgb(0,216,255);">React JS</b> 45+ Hrs live classes</p>
              </div>
            </div>
            <div class="boxhover q-pa-xl" style="background-color: rgb(8,33,62); border-radius: 20px; width: 200px; height: 200px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.7), 0 6px 20px 0 rgba(0, 0, 0, 0.25);">
              <img src="https://digikull.com/_next/static/media/css.91e7082c.webp" width="80" alt="">
              <div class="text-white q-mt-md">
                <p style="font-size: 11px;"><b style="color: red;">CSS</b> 10+ Hrs live classes</p>
              </div>
            </div>
          </div>
          <div class="box col-lg-6 q-gutter-xl q-mt-xs q-pa-xl">
            <div class="boxhover q-pa-xl" style="background-color: rgb(8,33,62); border-radius: 20px; width: 200px; height: 200px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.7), 0 6px 20px 0 rgba(0, 0, 0, 0.25);">
              <img src="https://digikull.com/_next/static/media/real_project.2d15f23e.webp" width="60" alt="">
              <div class="text-white q-mt-md">
                <p style="font-size: 11px;"><b style="color: rgb(0,12,237);">1 month</b> of close to real project</p>
              </div>
            </div>
            <div class="boxhover q-pa-xl" style="background-color: rgb(8,33,62); border-radius: 20px; width: 200px; height: 200px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.7), 0 6px 20px 0 rgba(0, 0, 0, 0.25);">
              <img src="https://digikull.com/_next/static/media/doubt.cd885f6a.webp" width="60" alt="">
              <div class="text-white q-mt-xs">
                <p style="font-size: 11px;"><b style="color: rgb(245,1,4);">120 hrs</b> of doubt clearing and project mentoring</p>
              </div>
            </div>
            <div class="boxhover q-pa-xl" style="background-color: rgb(8,33,62); border-radius: 20px; width: 200px; height: 200px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.7), 0 6px 20px 0 rgba(0, 0, 0, 0.25);">
              <img src="https://digikull.com/_next/static/media/html.61792547.webp" width="70" alt="">
              <div class="text-white q-mt-xs">
                <p style="font-size: 11px;"><b style="color: rgb(242,103,52);">HTML</b> 10+ Hrs live classes</p>
              </div>
            </div>
            <div class="boxhover q-pa-xl" style="background-color: rgb(8,33,62); border-radius: 20px; width: 200px; height: 200px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.7), 0 6px 20px 0 rgba(0, 0, 0, 0.25);">
              <img src="https://digikull.com/_next/static/media/js.d64af41c.webp" width="70" alt="">
              <div class="text-white q-mt-xs">
                <p style="font-size: 11px;"><b style="color: rgb(247,132,54);">JavaScript</b> 50+ Hrs live classes</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      </div>
    </section>

    <div class="row q-pa-xl">
          <div class="col-12 col-md-6 text-center">
            <div class="q-gutter-y-md">
              <div class="q-gutter-sm">
              <q-chip color="purple-2" style="height: 40px;">
                <q-avatar style="width: 70px; height: 40px;" color="purple" text-color="white">96%</q-avatar>
                <div style="width: 230px;" class="text-center">Placement Rate</div>
              </q-chip>
              <q-chip color="pink-2" style="height: 40px;">
                <q-avatar style="width: 70px; height: 40px;" color="pink" text-color="white">200+</q-avatar>
                <div style="width: 230px;" class="text-center">Student Enrolled</div>
              </q-chip>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6 text-center">
            <div class="q-gutter-y-md">
              <div class="q-gutter-sm">
              <q-chip color="red-2" style="height: 40px;">
                <q-avatar style="width: 70px; height: 40px;" color="red" text-color="white">8LPA</q-avatar>
                <div style="width: 230px;" class="text-center">Highest Salary</div>
              </q-chip>
              <q-chip color="deep-purple-2" style="height: 40px;">
                <q-avatar style="width: 70px; height: 40px;" color="deep-purple" text-color="white">3.5LPA</q-avatar>
                <div style="width: 230px;" class="text-center">Average Salary</div>
              </q-chip>
              </div>
            </div>
          </div>
        </div>
  <!-- </div> -->
<div>

    <div class="text-center">
      <h4 style="font-size: 2rem; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">
      <b> Portions We Cover To Become A Frontent Developer</b>
    </h4>
  </div>

<div class="flex justify-evenly">
    <div class="q-pa-md">
    <div style="max-width: auto">
      <q-tabs
        v-model="tab"
        align="justify"
        narrow-indicator
        class="q-mb-lg"
      >
        <q-tab class="text-indigo-10" name="mails" label="HTML" />
        <q-tab class="text-deep-purple-10" name="alarms" label="CSS" />
        <q-tab class="text-indigo-10" name="movies" label="BOOTSTRAP" />
      </q-tabs>

      <div class="q-gutter-y-sm">
        <q-tab-panels
          v-model="tab"
          animated
          transition-prev="scale"
          transition-next="scale"
          class=""
        >
          <q-tab-panel name="mails" class="text-indigo-10 bg-indigo-1">
            <div class="text-h6 text-center">PART - 1</div>
              1.&nbsp;Introduction of HTML <br>
              2.&nbsp;HTML Elements <br>
              3.&nbsp;HTML Attributes <br>
              4.&nbsp;HTML Headings <br>
              5.&nbsp;HTML Styles <br>
              6.&nbsp;HTML Comments <br>
              7.&nbsp;HTML Colors <br>
          </q-tab-panel>

          <q-tab-panel name="alarms" class="text-deep-purple-10 bg-deep-purple-1">
            <div class="text-h6 text-center">PART - 1</div>
              1.&nbsp;Introduction of CSS <br>
              2.&nbsp;Basics of CSS comments <br>
              3.&nbsp;CSS Links <br>
              4.&nbsp;CSS Borders <br>
              5.&nbsp;CSS Margins <br>
              6.&nbsp;CSS Fonts <br>
              7.&nbsp;CSS Align <br>
              8.&nbsp;CSS Borders
          </q-tab-panel>

          <q-tab-panel name="movies" class="text-indigo-10 bg-indigo-1">
            <div class="text-h6 text-center">PART - 1</div>
              1.&nbsp;Introduction of Bootstrap5 <br>
              2.&nbsp;Bootstrap setup <br>
              3.&nbsp;Breakpoints <br>
              4.&nbsp;Containers <br>
              5.&nbsp;Grid <br>
              6.&nbsp;Gutters
          </q-tab-panel>
        </q-tab-panels>

        <q-tab-panels
          v-model="tab"
          animated
          transition-prev="fade"
          transition-next="fade"
          class="text-white"
        >
          <q-tab-panel name="mails" class="text-indigo-10 bg-indigo-1">
            <div class="text-h6 text-center">PART - 2</div>
              8.&nbsp;HTML Links <br>
              9.&nbsp;HTML Formatting
              10.&nbsp;HTML Block and Inline Elements<br>
              11.&nbsp;HTML Div Element<br>
              12.&nbsp;HTML Layout<br>
              13.&nbsp;HTML Responsive
          </q-tab-panel>

          <q-tab-panel name="alarms" class="text-deep-purple-10 bg-deep-purple-1">
            <div class="text-h6 text-center">PART - 2</div>
              9.&nbsp;&nbsp;&nbsp;CSS Advanced<br>
              10.&nbsp;CSS Colors <br>
              11.&nbsp;CSS Gradients <br>
              12.&nbsp;CSS Transitions <br>
              13.&nbsp;CSS Animations <br>
              14.&nbsp;CSS The object-position Property
          </q-tab-panel>

          <q-tab-panel name="movies" class="text-indigo-10 bg-indigo-1">
            <div class="text-h6 text-center">PART - 2</div>
              7.&nbsp;Form Control <br>
              8.&nbsp;Select,Check & Radio Boxes <br>
              9.&nbsp;Range <br>
          </q-tab-panel>
        </q-tab-panels>

        <q-tab-panels
          v-model="tab"
          animated
          transition-prev="jump-up"
          transition-next="jump-down"
          class="text-white"
        >
          <q-tab-panel name="mails" class="text-indigo-10 bg-indigo-1">
            <div class="text-h6 text-center">PART - 3</div>
              14.&nbsp;HTML Forms<br>
              15.&nbsp;HTML Form Attributes<br>
              16.&nbsp;HTML Form Elements<br>
              17.&nbsp;HTML Input Types<br>
              18.&nbsp;HTML Input Attributes<br>
              19.&nbsp;HTML API's<br>
          </q-tab-panel>

          <q-tab-panel name="alarms" class="text-deep-purple-10 bg-deep-purple-1">
            <div class="text-h6 text-center">PART - 3</div>
              15.&nbsp;CSS Responsive<br>
              16.&nbsp;CSS Grid<br>
              16.&nbsp;CSS Flex<br>
          </q-tab-panel>

          <q-tab-panel name="movies" class="text-indigo-10 bg-indigo-1">
            <div class="text-h6 text-center">PART - 3</div>
              10.&nbsp;Floating Labels <br>
              11.&nbsp;Layout <br>
              12.&nbsp;Components Handling
          </q-tab-panel>
        </q-tab-panels>
      </div>
    </div>
  </div>
  <div class="borde" style="border-left: 1px solid rgb(162, 162, 248);"></div>
  <div class="q-pa-md">
    <div style="max-width: auto">
      <q-tabs
        v-model="tabu"
        align="justify"
        narrow-indicator
        class="q-mb-lg"
      >
        <q-tab class="text-indigo-10" name="js" label="JavaScript" />
        <q-tab class="text-deep-purple-10" name="bootstrap" label="VueJs" />
        <q-tab class="text-indigo-10" name="react" label="React" />
      </q-tabs>

      <div class="q-gutter-y-sm">
        <q-tab-panels
          v-model="tabu"
          animated
          transition-prev="scale"
          transition-next="scale"
          class=""
        >
          <q-tab-panel name="js" class="text-indigo-10 bg-indigo-1">
            <div class="text-h6 text-center">PART - 1</div>
              1.&nbsp;Introduction of JavaScript <br>
              2.&nbsp;JS Comments <br>
              3.&nbsp;JS Datatypes <br>
              4.&nbsp;JS Variables <br>
              5.&nbsp;JS String <br>
              6.&nbsp;JS Object <br>
              7.&nbsp;JS Nested Objects
          </q-tab-panel>

          <q-tab-panel name="bootstrap" class="text-deep-purple-10 bg-deep-purple-1">
            <div class="text-h6 text-center">PART - 1</div>
              1.&nbsp;Introduction of Vue Js <br>
              2.&nbsp;Vue Directives <br>
              3.&nbsp;Vue v-bind <br>
              4.&nbsp;Vue v-if <br>
              5.&nbsp;Vue v-show <br>
              6.&nbsp;Vue v-for <br>
              7.&nbsp;Vue Events <br>
              8.&nbsp;Vue Methods <br>
              9.&nbsp;Vue v-model
          </q-tab-panel>

          <q-tab-panel name="react" class="text-indigo-10 bg-indigo-1">
            <div class="text-h6 text-center">PART - 1</div>
              1.&nbsp;Introduction of React Js <br>
              2.&nbsp;React Components <br>
              3.&nbsp;React Class <br>
              4.&nbsp;React Props <br>
              5.&nbsp;React Events <br>
              6.&nbsp;React Conditions
          </q-tab-panel>
        </q-tab-panels>

        <q-tab-panels
          v-model="tabu"
          animated
          transition-prev="fade"
          transition-next="fade"
          class="text-white"
        >
        <q-tab-panel name="js" class="text-indigo-10 bg-indigo-1">
          <div class="text-h6 text-center">PART - 2</div>
              8.&nbsp;JS For in loop <br>
              9.&nbsp;JS For of loop <br>
              10.&nbsp;JS Functions <br>
              11.&nbsp;JS Function Expressions
              12.&nbsp;JS Hoisting <br>
              13.&nbsp;JS Variable Hoisting <br>
              14.&nbsp;JS Events <br>
              15.&nbsp;JS UseCapture
          </q-tab-panel>

          <q-tab-panel name="bootstrap" class="text-deep-purple-10 bg-deep-purple-1">
            <div class="text-h6 text-center">PART - 2</div>
              10.&nbsp;Vue Computed properties<br>
              11.&nbsp;Vue Watchers <br>
              12.&nbsp;Vue Templates <br>
              13.&nbsp;Vue Components <br>
              14.&nbsp;Vue Props <br>
              15.&nbsp;Vue $emit()
          </q-tab-panel>

          <q-tab-panel name="react" class="text-indigo-10 bg-indigo-1">
            <div class="text-h6 text-center">PART - 2</div>
              7.&nbsp;React Lists <br>
              8.&nbsp;React Forms <br>
              9.&nbsp;React Router <br>
              10.&nbsp;What is React Hook?<br>
              11.&nbsp;Use state<br>
              12.&nbsp;Use Effect
          </q-tab-panel>
        </q-tab-panels>

        <q-tab-panels
          v-model="tabu"
          animated
          transition-prev="jump-up"
          transition-next="jump-down"
          class="text-white"
        >
        <q-tab-panel name="js" class="text-indigo-10 bg-indigo-1">
          <div class="text-h6 text-center">PART - 3</div>
              16.&nbsp;JS Cookies <br>
              17.&nbsp;JS Session Storage <br>
              18.&nbsp;JS Local Storage <br>
              19.&nbsp;JS Page redirection <br>
              20.&nbsp;JS Map <br>
              21.&nbsp;JS DOM <br>
              22.&nbsp;JS BOM <br>
              23.&nbsp;JS Logical errors <br>
              24.&nbsp;JS asynchronous
        </q-tab-panel>

          <q-tab-panel name="bootstrap" class="text-deep-purple-10 bg-deep-purple-1">
            <div class="text-h6 text-center">PART - 3</div>
              14.&nbsp;Vue Slots<br>
              15.&nbsp;Vue v-slot <br>
              16.&nbsp;Vue Scoped slots <br>
              17.&nbsp;Vue Routing
          </q-tab-panel>

          <q-tab-panel name="react" class="text-indigo-10 bg-indigo-1">
            <div class="text-h6 text-center">PART - 3</div>
              13.&nbsp;Use Context<br>
              14.&nbsp;Use Reducer
          </q-tab-panel>
        </q-tab-panels>
      </div>
    </div>
  </div>
  </div>
</div>

  <div style="background-color: rgba(209, 206, 206, 0.349);" class="q-mb-md">
    <div>
      <div class="flex flex-center text-center" style="font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">
      <h4 style="font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;"><b> Why Choose Us ?</b></h4>
      <div class="q-pa-md text-center q-px-xl" style=" word-spacing: 5px; font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif">
        We accept students from all education background, The Eligibility Criteria to be part of our Placement gaurantee program is that you should be passionate about learning digital technologies and your dedication for six months.
      </div>
      </div>
    </div>

    <div class="row q-px-xl q-pa-xl">
        <div class="col-12 col-md-6 col-lg-3">
          <q-card class="my-card">
            <q-card-section>
              <div class="text-h6 choose"><img src="https://digikull.com/_next/static/media/online_classes.4e472cb5.webp" height="60" alt=""></div>
              <div class="text-subtitle2 text-center">Live Interactive Sessions</div>
            </q-card-section>
            <q-separator />
            <q-card-actions vertical>
              <div class="q-pa-md text-center">
                The trainer does not proceed to the next topic until all doubts are clear.
              </div>
            </q-card-actions>
          </q-card>
          </div>

          <div class="col-12 col-md-6 col-lg-3">
          <q-card class="my-card">
            <q-card-section>
              <div class="text-h6 choose"><img src="https://digikull.com/_next/static/media/live.80a2c456.webp" height="60" alt=""></div>
              <div class="text-subtitle2 text-center">Live Practice Sessions.</div>
            </q-card-section>
            <q-separator />
            <q-card-actions vertical>
              <div class="q-pa-md text-center">
                We hand hold to solve the basic problem by sharing your screen.
              </div>
            </q-card-actions>
          </q-card>
          </div>

          <div class="col-12 col-md-6 col-lg-3">
          <q-card class="my-card">
            <q-card-section>
              <div class="text-h6 choose"><img src="https://digikull.com/_next/static/media/doubts.80caf866.webp" height="60" alt=""></div>
              <div class="text-subtitle2 text-center">Live Doubt Clearing Sessions.</div>
            </q-card-section>
            <q-separator />
            <q-card-actions vertical>
              <div class="q-pa-md text-center">
                Not only chat support,If you are stuck on any of your assignment share screen to ask doubts.
              </div>
            </q-card-actions>
          </q-card>
          </div>

          <div class="col-12 col-md-6 col-lg-3">
          <q-card class="my-card">
            <q-card-section>
              <div class="text-h6 choose"><img src="https://digikull.com/_next/static/media/mock.c7772fed.webp" height="60" alt=""></div>
              <div class="text-subtitle2 text-center">Unlimited Mock Interviews</div>
            </q-card-section>
            <q-separator />
            <q-card-actions vertical>
              <div class="q-pa-md text-center">
                Practice, Practice and Practice. Give unlimited mock and get feedback.
              </div>
            </q-card-actions>
          </q-card>
          </div>
      </div>
  </div>

    <div class="row q-pa-xl">
      <div class="col-12 col-lg-8">
        <div>
          <div class="text-center">
            <h4 style="font-size: 2rem; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">
            <b> What Our Students Says</b>
          </h4>
        </div>
        <div class="row q-mt-xl">
        <div class="col-12 col-md-6">
        <div class="q-pa-md">
        <q-list bordered class="rounded-borders bg-light-blue-1">
        <q-expansion-item>
          <template v-slot:header>
          <q-item-section avatar>
            <q-avatar>
          <img src="https://cdn.quasar.dev/img/boy-avatar.png">
        </q-avatar>
          </q-item-section>
          <q-item-section>
            Vasanth
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            "Its really PROUD to be a part of such great ACADEMY...!! The classes are superb with all the required facilities and so COOPERATING faculty. You can even share any kind of problem with the FACULTIES. All over the academy team in very INSPIRING and full of ENTHUSIASM..The most admiring part is that the tutors focus on CONCEPTUAL development..!! So I recommend students aspiring for 'Full stack developer' to join "EDEX TECH ACADEMY" for enhancing your knowledge and to get best RESULTS..!!👍👍👍"
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-6">
        <div class="q-pa-md">
        <q-list bordered class="rounded-borders bg-light-blue-1">
        <q-expansion-item>
          <template v-slot:header>
          <q-item-section avatar>
            <q-avatar>
          <img src="https://cdn.quasar.dev/img/boy-avatar.png">
        </q-avatar>
          </q-item-section>
          <q-item-section>
            Selina
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            I want to express my gratitude to Edex Tech for offering an exceptional full-stack developer course. The course structure is comprehensive, covering both front-end and back-end development extensively. The knowledgeable instructors have been instrumental in enhancing my skills, making this learning experience a standout in my career. The practical projects provided hands-on experience, solidifying my understanding of key concepts. The support from the Edex Tech team has been remarkable, with prompt responses to queries and additional resources for further learning. I highly recommend Edex Tech for their commitment to delivering a top-notch full-stack developer course. It has truly been a valuable investment in my professional journey. Thank you, Edex Tech, for your excellence and support!
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-6">
        <div class="q-pa-md">
        <q-list bordered class="rounded-borders bg-light-blue-1">
        <q-expansion-item>
          <template v-slot:header>
          <q-item-section avatar>
            <q-avatar>
          <img src="https://cdn.quasar.dev/img/boy-avatar.png">
        </q-avatar>
          </q-item-section>
          <q-item-section>
            Rubini
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            I'm truly grateful to Edex Tech for the exceptional full-stack developer course they offer. The well-structured curriculum and skilled instructors have significantly boosted my proficiency in both front-end and back-end development. This learning experience stands out as the pinnacle of my career, and I extend my sincere appreciation to Edex Tech for their outstanding support and guidance. The hands-on projects provided a practical edge, and the trainers' expertise ensured a comprehensive understanding of complex concepts. The responsive support from the Edex Tech team further enhanced the overall experience. I highly recommend Edex Tech to anyone seeking a top-notch full-stack developer course – it's a valuable investment in professional growth. Thank you, Edex Tech, for your commitment to excellence!
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-6">
        <div class="q-pa-md">
        <q-list bordered class="rounded-borders bg-light-blue-1">
        <q-expansion-item>
          <template v-slot:header>
          <q-item-section avatar>
            <q-avatar>
          <img src="https://cdn.quasar.dev/img/boy-avatar.png">
        </q-avatar>
          </q-item-section>
          <q-item-section>
            Naresh
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            Good Environment! The best and very intellectual way of teaching. Teaching is very smooth with mam and Sir and are very friendly. The concepts are very clear. They use new and cool ways to teach and focus on using what you learn in real life. Coaching is more on practical knowledge.

Thanks to Edex Tech...
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-6">
        <div class="q-pa-md">
        <q-list bordered class="rounded-borders bg-light-blue-1">
        <q-expansion-item>
          <template v-slot:header>
          <q-item-section avatar>
            <q-avatar>
          <img src="https://cdn.quasar.dev/img/boy-avatar.png">
        </q-avatar>
          </q-item-section>
          <q-item-section>
            Nagajothi
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            I highly appreciate Edex Tech for offering an exceptional full-stack developer course. The comprehensive curriculum and skilled trainers have significantly enhanced my skills in both front-end and back-end development. This learning experience has been the best in my career, and I am sincerely grateful to Edex Tech for their outstanding support and guidance.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-6">
        <div class="q-pa-md">
        <q-list bordered class="rounded-borders bg-light-blue-1">
        <q-expansion-item>
          <template v-slot:header>
          <q-item-section avatar>
            <q-avatar>
          <img src="https://cdn.quasar.dev/img/boy-avatar.png">
        </q-avatar>
          </q-item-section>
          <q-item-section>
            Ponraj
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            awesome😊 the class’s and training was excellent with good interaction.
The instructor spoke very clear and was very knowledgeable and patient. all the staff members are also very friendly….
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-6">
        <div class="q-pa-md">
        <q-list bordered class="rounded-borders bg-light-blue-1">
        <q-expansion-item>
          <template v-slot:header>
          <q-item-section avatar>
            <q-avatar>
          <img src="https://cdn.quasar.dev/img/boy-avatar.png">
        </q-avatar>
          </q-item-section>
          <q-item-section>
            Goodwin
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            The training program exceeded my expectations in terms of content quality and depth. The instructors were highly knowledgeable, approachable, and skilled at conveying complex concepts in a way that was easy to understand. Their real-world experience added immense value to the training. My training experience at EdexTech IT solutions Company has been immensely valuable. I feel more confident in applying the skills I've acquired, and I appreciate the company's dedication to providing exceptional training services. I look forward to engaging in future opportunities with Edextech IT solutions Company.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-6">
        <div class="q-pa-md">
        <q-list bordered class="rounded-borders bg-light-blue-1">
        <q-expansion-item>
          <template v-slot:header>
          <q-item-section avatar>
            <q-avatar>
          <img src="https://cdn.quasar.dev/img/boy-avatar.png">
        </q-avatar>
          </q-item-section>
          <q-item-section>
            Vijay
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            First of all big thanks for Edex team❤️ I have made a good decision in my career. Coach and mentors are very knowledgeable to explain concepts and clarify doubts. I feel grateful to be a part of it. Thanks to my coaches, mentors and their support.😊
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <!-- <div class="col-12 col-md-6">
        <div class="q-pa-md">
        <q-list bordered class="rounded-borders bg-light-blue-1">
        <q-expansion-item>
          <template v-slot:header>
          <q-item-section avatar>
            <q-avatar>
          <img src="https://cdn.quasar.dev/img/boy-avatar.png">
        </q-avatar>
          </q-item-section>
          <q-item-section>
            Person9
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
              <q-icon name="star" color="blue" size="15px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            awesome😊 the class’s and training was excellent with good interaction.
The instructor spoke very clear and was very knowledgeable and patient. all the staff members are also very friendly….
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div> -->
        </div>
      </div>
    </div>
    <div class="col-12 col-lg-4 flex flex-center">
      <q-card style="max-height: fit-content; width: auto" class="bg-light-blue-1">
                  <q-linear-progress :value="1" color="deep-purple-10" />
                  <q-card-section>
                    <div>
                      <div class="q-pa-md text-center text-brown-14"><b style="letter-spacing: 2px;">Take your first step in EdexTech</b></div>
                      <!-- <div class="text-grey">Fitz & The Tantrums</div> -->
                      <div class="q-pa-xl flex items-center q-gutter-xl justify-center">
                        <q-input color="blue-10" outlined v-model="text" label="Name">
                          <template v-slot:append>
                        <q-avatar>
                          <img src="https://digikull.com/_next/static/media/user.b051d75a.png">
                        </q-avatar>
                          </template>
                        </q-input>
                        <q-input color="blue-10" outlined v-model="text" label="Gmail">
                          <template v-slot:append>
                        <q-avatar>
                          <img src="https://digikull.com/_next/static/media/gmail.fdeca59f.png">
                        </q-avatar>
                          </template>
                        </q-input>
                        <q-input color="blue-10" outlined v-model="text" label="Contact No.">
                          <template v-slot:append>
                        <q-avatar>
                          <img src="https://digikull.com/_next/static/media/whatapp.92e48152.png">
                        </q-avatar>
                          </template>
                        </q-input>
                        <!-- <div class=""> -->
                          <q-btn color="light-blue-2 text-weight-bold" text-color="deep-purple-10" style="letter-spacing: 2px; font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; width: 200px; height: 50px;" label="SEND ENQUIRE">
                          <q-tooltip class="bg-pink-10">Send Enquire</q-tooltip>
                          </q-btn>
                        <!-- </div> -->
                      </div>

                    </div>
                    <q-space />
                    <!-- <q-btn flat round icon="fast_rewind" />
                    <q-btn flat round icon="pause" />
                    <q-btn flat round icon="fast_forward" /> -->
                  </q-card-section>
                  <q-linear-progress :value="1" color="deep-purple-10" />
                </q-card>
    </div>
  </div>



  <div style="background-image: linear-gradient(to left, rgb(183, 205, 239), rgb(206, 224, 251));">
          <div class="q-pa-md q-gutter-sm flex justify-center">
            <q-breadcrumbs separator="---" class="text-blue-14" active-color="secondary">
              <q-breadcrumbs-el class="text-blue-10" icon="home" />
              <q-breadcrumbs-el class="text-blue-10" label="Courses" icon="widgets" />
              <q-breadcrumbs-el class="text-blue-10" label="Reviews" icon="navigation" />
            </q-breadcrumbs>
          </div>
          <div style="border-bottom: 1px solid rgb(108, 108, 236);" class="q-ml-xl q-mr-xl"></div>
        <div class="footersec">
        <div class="row q-pa-md text-center">
          <div class="col-lg-3 col-6 text-indigo-10 q-mb-xl">
          <div><b>About</b></div>
          <div class="q-mt-md">
            <div>About Edex</div>
            <div>Careers</div>
            <!-- <div>PlayStation Studios</div>
            <div>PlayStation Productions</div> -->
            <div>Corporate</div>
          </div>
        </div>
        <div class="col-lg-3 col-6 text-indigo-10">
          <div><b>Values</b></div>
          <div class="q-mt-md">
            <div>Proficiency in HTML and CSS</div>
            <div>JavaScript basics.</div>
            <div>Responsive design.</div>
            <div>UI frameworks and CSS-transforming tools.</div>
            <div>User Accessibility.</div>
          </div>
        </div>
        <div class="col-lg-3 col-6 text-indigo-10">
          <div><b>Support</b></div>
          <div class="q-mt-md">
            <div>Support hub</div>
            <!-- <div> Safety</div> -->
            <div>Status</div>
            <!-- <div>PlayStation Repairs</div> -->
            <div>Password reset</div>
          </div>
        </div>
        <div class="col-lg-3 col-6 text-indigo-10">
          <div class="text-indigo-10"><b>Resources</b></div>
          <div class="q-mt-md">
            <div>Git</div>
            <div>HTML&CSS</div>
            <div>Bootstrap</div>
            <div>Javascript</div>
            <div>Podcasts</div>
            <div>Testing</div>
          </div>
        </div>
            </div>
           </div>

           <div style="border-bottom: 1px solid rgb(108, 108, 236);" class="q-ml-xl q-mr-xl"></div>

           <div class="footsec">
            <div class="row q-pa-md text-center text-indigo-10">
          <div class="col-12 col-md-2 q-mt-md">
            Careers
          </div>
          <div class="col-12 col-md-2 q-mt-md">
            Terms
          </div>
          <div class="col-12 col-md-2 q-mt-md">
            Subscribe
          </div>
          <div class="col-12 col-md-2 q-mt-md">
            Our Courses
          </div>
          <div class="col-12 col-md-2 q-mt-md">
            Partner With Us
          </div>
          <div class="col-12 col-md-2 q-mt-md">
            Join the conversation
          </div>
        </div>
           </div>
      </div>

  </q-page>
<!-- </q-page-container> -->

</template>

<script>
import { ref,onBeforeUnmount } from 'vue'

export default {
  name: 'IndexPage',
  data () {
    const counter = ref(0)
    let timer
    const dialog = ref(false)
    const position = ref('top')

    function stopCounting () {
      clearInterval(timer)
    }

    onBeforeUnmount(stopCounting)
    return {
      slide: ref(1),
      lorem: 'FrontEnd Developer',
      counter,
      dialog,
      position,
      tab: ref('mails'),
      tabu: ref('js'),

      open (pos) {
        position.value = pos
        dialog.value = true
      },

      startCounting () {
        timer = setInterval(() => {
          counter.value++
        }, 1000)
      },

      stopCounting
    }
  }
}
</script>

<style>

  .sec1{
    font-size: 1.3rem;
    font-weight: 600;
    /* width: 90%; */
    margin: auto;
    background-clip: text;
    color: transparent;
    background: linear-gradient(to left,rgb(22, 42, 139),rgb(235, 112, 5));
    /* background: linear-gradient(to left,rgb(1,111,187),rgb(237,212,90),rgb(232,104,70)); */
    -webkit-background-clip: text;
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  }

  .sec111{
    font-size: 1.3rem;
    font-weight: 600;
    /* width: 90%; */
    margin: auto;
    background-clip: text;
    color: transparent;
    background: linear-gradient(to left,rgb(235, 112, 5),rgb(22, 42, 139));
    /* background: linear-gradient(to left,rgb(1,111,187),rgb(237,212,90),rgb(232,104,70)); */
    -webkit-background-clip: text;
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  }

  .sec11{
    font-size: 1.3rem;
    font-weight: 800;
    /* width: 90%; */
    margin: auto;
    background-clip: text;
    color: transparent;
    background: linear-gradient(to left, rgb(197, 96, 96), blue);
    /* background: linear-gradient(to left,rgb(1,111,187),rgb(237,212,90),rgb(232,104,70)); */
    -webkit-background-clip: text;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
  }

  .sec12{
    font-size: 1.3rem;
    font-weight: 500;
    /* width: 90%; */
    /* margin: auto; */
    background-clip: text;
    color: transparent;
    background: linear-gradient(to left, blue,red);
    /* background: linear-gradient(to left,rgb(1,111,187),rgb(237,212,90),rgb(232,104,70)); */
    -webkit-background-clip: text;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }

  .sec13{
    font-size: 1.3rem;
    font-weight: 500;
    /* width: 20%; */
    margin: auto;
    background-clip: text;
    color: transparent;
    background: linear-gradient(to left, rgb(165, 87, 115),rgb(59, 38, 194));
    /* border: 1px solid brown; */
    /* background: linear-gradient(to left,rgb(1,111,187),rgb(237,212,90),rgb(232,104,70)); */
    -webkit-background-clip: text;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }

  .sec14{
    font-size: 1.3rem;
    font-weight: 500;
    /* width: 90%; */
    margin: auto;
    background-clip: text;
    color: transparent;
    background: linear-gradient(to left, blue,red);
    /* background: linear-gradient(to left,rgb(1,111,187),rgb(237,212,90),rgb(232,104,70)); */
    -webkit-background-clip: text;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }

  .sec233{
    word-spacing: 3px; letter-spacing: 1px;
    /* font-family: Poppins; */
  }
  .sec234{
    font-family:Verdana, Geneva, Tahoma, sans-serif;
  }

  @media screen and (max-width: 783px){
    .box
    {
        display: flex;
        overflow-x: scroll;
    }
}

@media screen and (max-width: 754px){
    .borde
    {
        display: none;
    }
}

@media screen and (max-width: 1057px){
    .marq
    {
        max-width:fit-content;
    }
    .marq1
    {
        height: 110px;
        width: auto;
    }
}

@media screen and (max-width: 425px){
    .marq
    {
        max-width: 350px;
    }
    .marq1
    {
        height: 110px;
        width: auto;
    }
}

@media screen and (max-width: 325px){
    .marq
    {
        max-width: 200px;
    }
    .marq1
    {
        height: 100px;
        width: 200;
    }
}

.choose{
    /* height: 5rem;
    width: 5rem;
    border: 1px solid #dadada;
    border-radius: 50%; */
    display: flex;
    align-items: center;
    justify-content: center;
    /* max-height: 5.5rem;
    margin-bottom: 0.5rem; */
}

.boxhover{
  transition: .5s;
}

.boxhover:hover{
  transform: scale(1.1);
  transition: .5s;
}

</style>

