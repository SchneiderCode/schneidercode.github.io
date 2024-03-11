---
title: Circuit Check 
layout: default
description: "Circuit Check is an interactive debugging tool I developed to support novices in physical computing. Through it's user-interface, novices can easily observe live sensor readings, test actuators, and even pause/unpause their running program. The development of Circuit Check was supported by the National Science Foundation under Award <a href=\u0022https://www.nsf.gov/awardsearch/showAward?AWD_ID=1742081\u0022>#1742081</a>."
banner: Circuit-Check-Banner.png
bannerAlt: A diagram labeling Circuit Check's primary components, which include a button for pausing a project's code and a dashboard for observing sensors and testing actuators. A student is shown using Circuit Check to test an LED.  
media_images: [] 
media_videos: []
---

<h1> Circuit Check </h1>

<div class="row">
  <div class="col-12 col-lg-6">
    <p>
     Circuit Check, an interactive debugging tool I developed to target the needs of novices, specifically middle and high school students, learning to build and program electronic textiles (e-textiles) - a form of physical computing system where students develop free-formed circuits that are sewn together with conductive thread. Through Circuit Check's interface, students can quickly and easily observe and test any part of their project's hardware. Similar features are provided by other debugging tools, but the unique aspect of Circuit Check is that it enables hardware exploration <b><i>without requiring software modifications</i></b>. This enables students to tinker and learn about their project's hardware, separately from its software. This separation of hardware and software helps to reduce the problem space for debugging and also makes it easier for teachers to coach students through the steps of hardware testing. </p>
     <p>
     But while I developed Circuit Check for e-textiles, it can support any physical computing project that uses either the BBC micro:bit or Adafruit Circuit Playground.
     </p>
  </div>
  <div class="col-12 col-lg-6">
    <div class="ratio ratio-16x9">
      <video class="rounded" playsinline controls muted>
          <source src="/assets/videos/cc_demo_whale.mp4" cl type="video/mp4">
          Your browser does not support the video tag.
      </video>
    </div>
  </div>
</div>

<hr>

<h2 class="mt-4">Why is debugging so hard?!?</h2>

<p>Debugging, i.e. finding and fixing errors, is notoriously difficult in software programming. That difficulty only increases when dealing with physical computing systems, like e-textiles, where even the simplest of bugs can be caused by a myriad of hardware and software issues. For example, an LED not turning on could be caused by a short circuit, a loose connection in the circuit, or even be broken/burned out LED (hardware error). The LED could also not be turning on due to a software error, like an incorrect condition or a missing piece of code. Any or all of these errors could be present in a buggy project! But Circuit Check can help simplify the debugging process by enabling students to quickly check for hardware errors. </p>

<img src="/assets/images/potential_errors.png" class="d-block w-50 mx-auto" alt="A diagram of potential hardware and software errors causing an LED to not turn on in an e-textile project">

<hr>

<h2 class="mt-4 mb-3">Debugging with Circuit Check</h2>

<div class="row">
  <div class="col-12 col-lg-5">
    <div class="ratio ratio-16x9">
      <video class="rounded" playsinline controls muted>
        <source src="/assets/videos/Circuit_Check_Demo_No_Sound.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  </div>
  <div class="col-12 col-lg-7">
    <div id="carouselUseCC" class="carousel carousel-dark slide">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <h3 class="text-center">User Interface</h3>
          <img src="/assets/images/CC UI.png" class="d-block w-100 " alt="Diagram of Circuit Check's UI">
        </div>
        <div class="carousel-item">
          <h3 class="text-center">Observing Sensors</h3>
           <img src="/assets/images/Testing Sensor.png" class="d-block w-100" alt="Demo of observing a light sensor with Circuit Check">
        </div>
        <div class="carousel-item">
          <h3 class="text-center">Testing Actuators</h3>
          <img src="/assets/images/Testing LED.png" class="d-block w-100 " alt="Demo of testing an LED with Circuit Check">
        </div>
      </div>
      <div class="carousel-indicators" style="position:relative">
        <button type="button" data-bs-target="#carouselUseCC" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Circuit Check's UI"></button>
        <button type="button" data-bs-target="#carouselUseCC" data-bs-slide-to="1" aria-label="Observing a Sensor"></button>
        <button type="button" data-bs-target="#carouselUseCC" data-bs-slide-to="2" aria-label="Testing an Actuator"></button>
      </div>
    </div>
  </div>
</div>

<hr>

<h2 class="mt-4 mb-3">Adding Circuit Check's Library/Extension</h2>
<div class="row border-bottom">
  <div class="col-12 col-lg-6">
    <div id="carouselMakeCodeExtension" class="carousel carousel-dark slide">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="/assets/images/makecode_1.png" class="d-block w-100" alt="Step 1 of adding a MakeCode Extension for Circuit Check">
        </div>
        <div class="carousel-item">
          <img src="/assets/images/makecode_2.png" class="d-block w-100" alt="Step 2 of adding a MakeCode Extension for Circuit Check">
        </div>
        <div class="carousel-item">
          <img src="/assets/images/makecode_3.png" class="d-block w-100" alt="Step 3 of adding a MakeCode Extension for Circuit Check">
        </div>
        <div class="carousel-item">
          <img src="/assets/images/makecode_4.png" class="d-block w-100" alt="Step 4 of adding a MakeCode Extension for Circuit Check">
        </div>
        <div class="carousel-item">
          <img src="/assets/images/makecode_5.png" class="d-block w-100" alt="Step 5 of adding a MakeCode Extension for Circuit Check">
        </div>
        <div class="carousel-item ">
          <img src="/assets/images/makecode_6.png" class="d-block w-100" alt="Step 6 of adding a MakeCode Extension for Circuit Check">
        </div>
        <div class="carousel-item">
          <img src="/assets/images/makecode_7.png" class="d-block w-100" alt="Step 7 of adding a MakeCode Extension for Circuit Check">
        </div>
      </div>
      <div class="carousel-indicators" style="position:relative">
        <button type="button" data-bs-target="#carouselMakeCodeExtension" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Step 1" style="text-indent:0;">1</button>
        <button type="button" data-bs-target="#carouselMakeCodeExtension" data-bs-slide-to="1" aria-label="Step 2" style="text-indent:0;">2</button>
        <button type="button" data-bs-target="#carouselMakeCodeExtension" data-bs-slide-to="2" aria-label="Step 3" style="text-indent:0;">3</button>
        <button type="button" data-bs-target="#carouselMakeCodeExtension" data-bs-slide-to="3" aria-label="Step 4" style="text-indent:0;">4</button>
        <button type="button" data-bs-target="#carouselMakeCodeExtension" data-bs-slide-to="4" aria-label="Step 5" style="text-indent:0;">5</button>
        <button type="button" data-bs-target="#carouselMakeCodeExtension" data-bs-slide-to="5" aria-label="Step 6" style="text-indent:0;">6</button>
        <button type="button" data-bs-target="#carouselMakeCodeExtension" data-bs-slide-to="6" aria-label="Step 7" style="text-indent:0;">7</button>
      </div>
    </div>
  </div>
  <div class="col-12 col-lg-4">
    <h3>MakeCode Extension</h3>
    <p>Here are the github links for the Circuit Check extensions for MakeCode. Select the one that matches the version of the micro:bit being used. </p>
    <p>V1 micro:bit - <a href="https://github.com/SchneiderCode/circuit-check-extension">https://github.com/SchneiderCode/circuit-check-extension</a></p>
    <p>V2 micro:bit -<a href="https://github.com/SchneiderCode/circuit-check-extension-v2">https://github.com/SchneiderCode/circuit-check-extension-v2</a></p>
  </div>
</div>
<div class="row mt-3">
  <div class="col-12 col-lg-6">
    <img src="/assets/images/Arduino_Starter_Detailed.png" class="d-block w-100" alt="Diagram of Circuit Check's Arduino Code">
  </div>
  <div class="col-12 col-lg-4">
    <h3 >Arduino Library</h3>
    <p>To use Circuit Check with Arduino and the Adafruit Circuit Playground, add the provided Circuit Check Library. </p>
    <a href="https://drive.google.com/file/d/1-xzA5qj7IWIJdkQOvRPITLUq3emW5nOH/view?usp=sharing">Circuit Check Zipped Library</a>
  </div>
</div>

<hr>

<h2 class="mt-4">Acknowledgements</h2>
<p>Circuit Check's development was supported by the National Science Foundation under Award <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1742081">#1742081 - Debugging by Design</a>. The Debugging by Design project page can be found <a href="https://cucraftlab.org/debugging-by-design/">here</a>. Circuit Check's development was supported by the <a href="https://cucraftlab.org/">Craft Tech Lab</a>, the <a href="https://www.colorado.edu/atlas/">ATLAS Institute</a>, and the <a href="https://www.colorado.edu/ics">Institute of Cognitive Science</a> at <a href="https://www.colorado.edu/">The University of Colorado, Boulder </a>. <br>Lastly, I could not have created Circuit Check without the guidance and support of <a href="https://www.colorado.edu/atlas/ann-eisenberg">Ann Eisenberg</a>, <a href="https://www.colorado.edu/atlas/mark-d-gross">Mark Gross</a>, <a href="https://cehs.usu.edu/itls/people/deborah-fields">Deborah Fields</a>, <a href="https://www.colorado.edu/ics/tamara-sumner">Tamara Sumner</a>, <a href="https://chrisnhill.com/">Chris Hill</a>, and so many other wonderful researchers and teachers!</p>
