<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>John Doe | Frontend Developer</title>
   
  </head>
  <body>
    <header>
      <nav aria-label="Main navigation">
        <h1>John Doe</h1>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#articles">Articles</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>

      <section class="hero" id="home">
        <h2>Frontend Developer</h2>
      </section>
    </header>

    <main>
      <article class="grid-container" aria-label="Profile information">
        <aside class="project" id="projects">
          <h3>Projects</h3>
          <ul>
            <li>HTML Only Portfolio</li>
            <li>Calculator</li>
            <li>Quiz App</li>
            <li>Countdown Timer</li>
            <li>Product Upcoming Page</li>
          </ul>
        </aside>

        <section class="experience" aria-label="Professional experience">
          <div class="content">
            <h3 class="content-title">Roadmap.sh</h3>
            <p>
              Solved all frontend projects with a focus on clean UI, responsive
              design, and practical implementation.
            </p>
            <a href="#contact" class="links">Visit my profile</a>
          </div>

          <div class="content">
            <h3 class="content-title">OpenSourceWork</h3>
            <p>
              Contributed to 50 open-source projects and built personal projects
              that received 200 GitHub stars.
            </p>
            <a href="#contact" class="links">Visit my GitHub profile</a>
          </div>
        </section>

        <section class="education" aria-label="Education details">
          <div class="content">
            <p>
              Graduated with a 3.76 out of 4 CGPA. Won the Acme Hackathon and
              organized 30 sessions.
            </p>

            <p><strong>Courses taken</strong></p>
            <ul>
              <li>Object-Oriented Programming</li>
              <li>Data Structures and Algorithms</li>
              <li>Web Engineering</li>
              <li>Artificial Intelligence</li>
              <li>Human-Computer Interaction</li>
              <li>Computer Graphics</li>
              <li>Database Management Systems</li>
              <li>Distributed Database Systems</li>
              <li>Discrete Mathematics</li>
            </ul>
          </div>
        </section>
      </article>

      <section class="reviews" aria-label="Teacher reviews">
        <h2>Reviews from my Teachers</h2>

        <div class="card-container">
          <figure>
            <blockquote>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nulla
              quisquam eveniet atque doloremque tenetur.
            </blockquote>
            <h4>Mark Cannaley</h4>
            <span>Assistant Professor</span>
          </figure>

          <figure>
            <blockquote>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nulla
              quisquam eveniet atque doloremque tenetur.
            </blockquote>
            <h4>Yuri Samiki</h4>
            <span>Assistant Professor</span>
          </figure>

          <figure>
            <blockquote>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nulla
              quisquam eveniet atque doloremque tenetur.
            </blockquote>
            <h4>Ellen Smethir</h4>
            <span>Assistant Professor</span>
          </figure>
        </div>
      </section>
    </main>

    <footer class="contacts" id="contact">
      <form action="#" method="post">
        <label>
          Name
          <input
            type="text"
            name="name"
            placeholder="Enter your name"
            required
          />
        </label>

        <label>
          Email
          <input
            type="email"
            name="email"
            placeholder="Enter your email"
            required
          />
        </label>

        <label>
          Message
          <textarea
            name="message"
            placeholder="Write your message here..."
            required
          ></textarea>
        </label>

        <button type="submit">Submit</button>
      </form>

      <p>© 2026 All rights reserved.</p>
    </footer>
  </body>
</html>
