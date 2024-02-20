<template>
        <q-page>
        <!-- <div> -->
          <div class="q-mt-md flex flex-center" style= "line-height: 9vw; height: 100vh; background-position: center; background-repeat: no-repeat; background-size: cover; background-image: url(https://img.freepik.com/premium-vector/abstract-blue-wave-banner-template-design_998164-96.jpg?w=1380); object-fit: contain;">
            <!-- <div class="col"> -->
            <div class="text-center">
              <h4 class="sec1">Frontend Developer Course with Placement</h4>
              <div>
                <marquee behavior="" direction="">
                <img src="https://blog.harveydelaney.com/content/images/size/w2000/2019/08/react.jpg" width="250px" style="object-fit: contain; overflow: hidden; background-repeat: no-repeat;" alt="">
                <img src="https://www.audero.it/blog/wp-content/uploads/2014/09/front-end-stack.png" width="345px" style="object-fit: contain; overflow: hidden; background-repeat: no-repeat;" alt="">
                <img src="https://ruky.me/wp-content/uploads/2021/08/bootstrap-5-releases-with-major-changes.jpg" width="240px" style="object-fit: contain; overflow: hidden; background-repeat: no-repeat;" alt="">
              </marquee>
              </div>
              <h4 class="sec11">Pay Upto 80% Course Fee After Getting a Job.</h4>
              <h4 class="sec12"><b>Earn up to 15 LPA</b></h4>
              <!-- <q-btn push color="light-blue-2" text-color="deep-purple-10" style="width: 200px; height: 50px;" label="Enroll Now" /> -->
              <div class="q-gutter-sm">
              <q-btn push @click="open('top')" color="light-blue-2 text-weight-bold" text-color="deep-purple-10" style="letter-spacing: 2px; font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; width: 200px; height: 50px;" label="Enroll Now" />

              <q-dialog v-model="dialog" :position="position">
                <q-card style="width: 350px" class="bg-light-blue-1">
                  <q-linear-progress :value="1" color="deep-purple-10" />
                  <q-card-section>
                    <div>
                      <div class="q-pa-md text-center text-brown-14"><b style="letter-spacing: 2px;">Take your first step in ExamsDaily</b></div>
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
      <div class="row q-pa-xl">
        <div class="col-12 col-lg-6">
        <h4 class="text-center" style="font-size: 2.5vmax; word-spacing: 2px; font-family:Verdana, Geneva, Tahoma, sans-serif ;">
          <b>FrontEnd Developer Courses</b>
        </h4>
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

    <div class="row">
          <div class="col-12 col-md-6 text-center">
            <div class="q-pa-md q-gutter-y-md">
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
            <div class="q-pa-md q-gutter-y-md">
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
    <div class="text-center"><h4 style="font-size: 2rem; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;"><b> What Our Students Says</b></h4></div>
    <div class="row q-pa-md">
      <div class="col-12 col-md-4 col-sm-6">
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
            Person1
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-4 col-sm-6">
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
            Person2
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-4 col-sm-6">
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
            Person3
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-4 col-sm-6">
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
            Person4
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-4 col-sm-6">
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
            Person5
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-4 col-sm-6">
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
            Person6
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-4 col-sm-6">
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
            Person7
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-4 col-sm-6">
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
            Person8
          </q-item-section>
          <q-item-section side>
            <div class="row items-center">
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
      </div>
      </div>
      <div class="col-12 col-md-4 col-sm-6">
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
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
              <q-icon name="star" color="blue" size="24px" />
            </div>
          </q-item-section>
        </template>
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-separator />
      </q-list>
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
                Not only chat support, but If you are stuck on any of your assignment share screen to ask doubts.
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



  <div style="background-image: linear-gradient(to left, rgb(183, 205, 239), rgb(206, 224, 251));">
          <div class="q-pa-xl q-gutter-sm flex justify-center">
            <q-breadcrumbs separator="---" class="text-blue-14" active-color="secondary">
              <q-breadcrumbs-el class="text-blue-10" icon="home" />
              <q-breadcrumbs-el class="text-blue-10" label="Courses" icon="widgets" />
              <q-breadcrumbs-el class="text-blue-10" label="Reviews" icon="navigation" />
            </q-breadcrumbs>
          </div>
          <div style="border-bottom: 1px solid rgb(108, 108, 236);" class="q-ml-xl q-mr-xl"></div>
        <div class="footersec">
        <div class="row q-pa-xl text-center">
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
            <div class="row q-pa-xl text-center text-indigo-10">
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
    font-size: 2rem;
    font-weight: 600;
    /* width: 90%; */
    margin: auto;
    background-clip: text;
    color: transparent;
    background: linear-gradient(to left,rgb(22, 42, 139),rgb(126, 125, 125),rgb(22, 42, 139));
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

