<template>
  <main class="page-content" aria-label="Content">
    <div class="wrapper">
      <div class="container mx-auto intro-container">
        <h3>About Me</h3>
        <div class="flex flex-col md:flex-row">
          <div
            class="pr-4 pl-42 md:w-1/3 pr-4 pl-4 lg:w-1/4 pr-4 pl-4 no-print"
          >
            <span
              class="profile-img"
              style="background-image: url(profile.jpg)"
            ></span>
          </div>
          <div
            class="pr-4 pl-42 md:w-2/3 pr-4 pl-4 lg:w-3/4 pr-4 pl-4 :flex-growprint-12"
          >
            <p>
              Hi, my name’s Brett and I’m a senior network system administrator.
              As well as administrating systems I also have experience making
              software and web apps. I have worked at a number of companies
              gaining teamwork and leadership skills.
            </p>
            <p>
              I am most skilled in: <mark>AWS</mark> and
              <mark>Eating Pizza</mark>
            </p>
          </div>
        </div>
      </div>
      <div class="container mx-auto list-container">
        <h3>Projects</h3>
        <div class="flex flex-wrap  layout layout-top-middle">
          <div
            class="sm:w-1/6 pr-4 pl-42 sm:w-1/3 pr-4 pl-4 md:w-1/4 pr-4 pl-4 :flex-growprint-12 details"
          >
            <h4>Super awesome project</h4>
            <a href="http://github.com/sproogen" target="_blank" class="link"
              >github.com/sproogen</a
            >
            <p class="no-print aditional-links">
              <a
                href="http://github.com/sproogen/modern-resume-theme"
                target="_blank"
                class=""
              >
                <i
                  class="fab fa-github"
                  title="sproogen/modern-resume-theme"
                ></i>
              </a>
            </p>
          </div>
          <div
            class="sm:w-1/6 pr-4 pl-42 sm:w-2/3 pr-4 pl-4 md:w-3/4 pr-4 pl-4 :flex-growprint-12 content"
          >
            <p class="quote">
              This is probably one of the greatest apps ever created, if you
              don't agree you're probably wrong.
            </p>
            <p>
              I started this project as a way if learning <mark>React</mark> and
              it has since grown into a fully fledged app. I have learned many
              skills through this and been I’m very proud of having this in my
              portfolio. If you don’t have a project as awesome as this I would
              advise you make one.
            </p>
          </div>
        </div>
      </div>
      <div class="container mx-auto list-container">
        <h3>Experience</h3>
        <div class="flex flex-col md:flex-row layout layout-left">
          <div
            class="pr-4 pl-42 md:w-1/3 pr-4 pl-4 lg:w-1/4 pr-4 pl-4 :flex-growprint-12 details"
          >
            <h4>The Boring Company</h4>
            <p><b>Senior Network System Administrator</b></p>
            <p>November 2017 - Present</p>
            <a href="http://boringcompany.com/" target="_blank" class="link"
              >boringcompany.com</a
            >
            <p class="no-print aditional-links"></p>
          </div>
          <div
            class="pr-4 pl-42 md:w-2/3 pr-4 pl-4 lg:w-3/4 pr-4 pl-4 :flex-growprint-12 content"
          >
            <p class="quote">
              Solving 21st century problems by diging holes and making game
              changing products like the *not a flamethrower*
            </p>
            <p>
              Every company needs its networks properly administered and The
              Boring Compay is no exception. Digging holes is hard and I play my
              part making sure the whole company stays connected. I lead a team
              of 5 people and enjoy driving the company to try new technologies.
            </p>
          </div>
        </div>
      </div>
      <div class="container mx-auto list-container">
        <h3>Education</h3>
        <div class="flex flex-col md:flex-row layout layout-left">
          <div
            class="pr-4 pl-42 md:w-1/3 pr-4 pl-4 lg:w-1/4 pr-4 pl-4 :flex-growprint-12 details"
          >
            <h4>Harvard University</h4>
            <p><b>BSc Computer Science</b></p>
            <p>2010 - 2013</p>
            <p class="no-print aditional-links"></p>
          </div>
          <div
            class="pr-4 pl-42 md:w-2/3 pr-4 pl-4 lg:w-3/4 pr-4 pl-4 :flex-growprint-12 content"
          >
            <p class="quote">
              Established in 1636, Harvard is the oldest higher education
              institution in the United States, and is widely regarded in terms
              of its influence, reputation, and academic pedigree as a leading
              university in not just the US but also the world.
            </p>
            <p>
              During my time at Harvard I learnt most of my key skills that have
              I have taken through my career such as teamwork and working to
              tight deadlines. I thouroughly enjoyed my time as university and
              learnt a lot about a healthy work life balance.
            </p>
            <p>
              I spent a lot of my free time as a committee member of the
              <em>Harvard Mountaineering Club</em> taking on roles such as
              <em>Trip Secretary</em> and <em>Vice-President</em>.
            </p>
          </div>
        </div>
      </div>
      <div class="container mx-auto text-container">
        <h3>A Little More About Me</h3>
        <div class="flex flex-wrap">
          <div class="pr-4 pl-42">
            <p>
              Alongside my interests in networks and software engineering some
              of my other interests and hobbies are:
            </p>
            <ul>
              <li>Rock climbing</li>
              <li>Gaming</li>
              <li>Knitting</li>
              <li>
                <a href="https://www.youtube.com/"
                  >Becoming a ninja</a
                >
              </li>
            </ul>
            <p>
              Look at this cool image<br />
              <img src="landscape-trees.jpg" alt="Trees" title="Trees" />
            </p>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {};
</script>
