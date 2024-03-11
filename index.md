---
title: Michael Schneider
layout: default
---
<div data-bs-spy="scroll" data-bs-target="#site_nav" data-bs-smooth-scroll="true" class="scrollspy-example" tabindex="0">

<div id="about-me">
  <h2>About Me</h2>
  <div class="border border-2 border-dark p-3 rounded-4">
    <div class="row">
      <div class="col-12 col-lg-4">
        <div class="card rounded-4 text-bg-dark w-75 mx-auto"> 
          <img src="assets/images/profile_square.jpg" alt="A headshot of Michael Schneider" class="rounded-4 mt-4 mx-auto d-block" width="80%">
          <div class="card-body">
            <h5 class="card-title text-center mb-2">Michael Schneider</h5> 
            <h6 class="card-subtitle text-center mb-1 opacity-50">PhD Student, CU Boulder <img src="assets/images/ralphie.png" style="height:1rem"/></h6> 
          </div>
        </div>
        <div class="w-75 mx-auto mt-2">
          {% include carousel.html %}
        </div>
      </div>
      <div class="col-12 col-lg-8 d-flex flex-wrap align-items-center fs-4">
        <p>
          I am a Ph.D. in Computer Science at the University of Colorado Boulder, where I research and develop tools to support middle and high school students in debugging physical computing and electronic textile (e-textile) projects.
        </p>
        <p>
        I am graduating in August 2024 and am currently applying for Software Engineering positions. I am especially interested in positions focused on tool development, where I can work to create novel technologies that empower engineers (of all skill levels).
        </p>
        <table class="table table-borderless mb-0">
            <tr class="border-top border-bottom border-2 border-dark">
              <td class="table-active w-25">Languages & Frameworks</td>
              <td class="w-75">C++, Javascript, Typescript, R, Java, C#, React.js, and Node.js</td>
            </tr>
            <tr>
              <td class="table-active w-25">Developer Interests</td>
              <td class="w-75">Web (Full Stack), Embedded Systems, Data Analysis, Machine Learning & AI</td>
            </tr>
            <tr class="border-top border-bottom border-2 border-dark">
              <td class="table-active w-25">Research Interests</td>
              <td class="w-75" >Software Engineering Practices, Debugging, Computer Science Education, Embedded Systems</td>
            </tr>
          </table>
      </div>
    </div>
  </div>
</div>

<br>
<br>

<div id="publications">
  <h2 class="align-middle me-3">Publications</h2>
  <div class="border border-2 border-dark p-3 rounded-4">
    {% include publications.html %}
  </div>
</div>

<br>
<br>

<div id="projects">
  <h2 class="align-middle me-3">Projects</h2>
  <div class="border border-2 border-dark p-3 rounded-4">
    {% include projects.html %}
  </div>
</div>

<div style="min-height: 25vh;"></div>