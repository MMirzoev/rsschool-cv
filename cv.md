# Mirshod Mirzoev

## Contacts:
- Github: [Mirshod-rgb](https://github.com/Mirshod-rgb)
- LinkedIn: [Mirshod Mirzoev](https://www.linkedin.com/in/mirshod-mirzoev-6b575779)
- E-mail : mirshod.mirzaev@mail.ru
- Mobile : +998906353612

## Short Bio:

I hold a bachelor's degree in banking and started working as a specialist of corporate customer service in a commercial bank. For the past four years, I have been working as a procurement specialist for a South Korean textile manufacturing company. A high sense of responsibility, propensity for teamwork, honesty and perseverance have provided a number of achievements over my career in banking and finance. My interest in programming has arisen from using various Excel formulas to carry out everyday tasks. I originally started learning to code at freeCodeCamp.org in 2020, and have successfully completed "Responsive Web Design" course with five projects in HTML and CSS. My goal is to become a full-time programmer in the near future. In my view, my interest in creating effective codes that solve a problem with a minimum number of steps is the main reason that keeps me motivated to learn new things and achieve my goal. 

## Skills:  

HTML, CSS, Git, VS Code, Codepen.

## Links to my projects:

- [My Portfolio Webpage](https://codepen.io/MirshodM/full/PomoZrP)
- [Tribute Page](https://codepen.io/MirshodM/full/ZEpYdmX)
- [Survey Form](https://codepen.io/MirshodM/full/mdrwROj)
- [Product Landing Page](https://codepen.io/MirshodM/full/bGwYZVr)
- [Technical Documentation Webpage](https://codepen.io/MirshodM/full/bGwJBEQ)

## Sample Codes from 'My Portfolio Webpage': 
```css
<style>

@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');

/*background-color: #2d3645;*/

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Open Sans', sans-serif;
  color: white;
  max-width: 100vw;
}
html {
  box-sizing: border-box;
  width: 100%;
}

@media (max-width: 460px) {
  html {
    font-size: 75%;
  }
}

a {
  text-decoration: none;
  font-weight: bold;
}
.nav {
  display: flex;
  justify-content: flex-end;
  position: fixed;
  background: #11102b;
  width: 100%;
  top: 0;
  left: 0;
  z-index: 111;
}
nav a {
  font-size: 1.325rem;
  padding: 1.5rem;
  display: block;
}
.nav-buttons {
  display: flex;
  margin-right: 2rem;
  list-style: none;
}
.nav-buttons a:hover {
  background: #7d0615;
}
@media (max-width: 460px) {
  .nav {
    justify-content: center;
  }
}
#welcome-section {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 100%;
  height: 100vh;
  background-image: url("https://media-exp1.licdn.com/dms/image/C561BAQGpxRlo9gp3cQ/company-background_10000/0/1548686474966?e=2159024400&v=beta&t=kc7MUYbXutHt2pvcb6ljpEcvhyp7jMLZf_OlSEnuh0M");
}

#welcome-section h1 {
  font-size: 3rem;
  font-weight: 600;
}
#welcome-section h2 {
  font-size: 2rem;
  font-weight: 500;
  letter-spacing: 0.125rem;
}
#projects {
  text-align: center;
  padding: 3rem;
  background: #35364f;
}
.portfolio-title {
  max-width: 700px;
  margin: 0 auto 3rem;
  font-size: 2rem;
  font-weight: 400;
}
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
  grid-gap: 4rem;
}
@media (max-width: 460px) {
    .projects-grid {
      display: flex;
      flex-direction: column;
    }
}
.project-image {
  display: block;
  width: 100%;
  height: 400px;
  object-fit: contain;
  background: linear-gradient(135deg, #e1e1e1 25%, transparent 25%) -50px 0,
    linear-gradient(225deg, #e1e1e1 25%, transparent 25%) -50px 0,
    linear-gradient(315deg, #e1e1e1 25%, transparent 25%),
    linear-gradient(45deg, #e1e1e1 25%, transparent 25%);
  background-size: 100px 100px;
  background-color: #cfd8dc;
}
@media (max-width: 460px) {
  .project-image {
    height: 200px;
  }
}
.project-tile {
  background: #28293d;
  box-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
  border-radius: 2px;
}
.project-title {
  font-size: 1.1rem;
  padding: 0.8rem;
  letter-spacing: 0.125rem;
  transition: transform 0.2s ease;
}
.project:hover {
  .project-title {transform: scale(1.1);}
}
#contacts {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  background: #26223d;
  padding: 15px;
}
.contacts-heading {
  max-width: 700px;
  font-size: 1.8rem;
  font-weight: 400;
}
.contact-list {
  display: flex;
  justify-content: center;
  width: 100%;
  max-width: 980px;
  margin-top: 1rem;
}
.contact-button {
  font-size: 1.4rem;
  display: inline-block;
  padding: 0.5rem 2rem;
  transition: transform 0.2s ease;

}
.contact-button:hover {
  transform: scale(1.1);
  font-weight: 400;
}
@media (max-width: 460px) {
  .contact-list {
    display: grid;
    grid-template-columns: auto auto;
    padding: 10px;
  }
}

footer {
  background-color: #26223d;
  display: flex;
  justify-content: center;
  padding: 1.5rem 3rem;
}
footer p {
  color: #929294;
  padding: 0rem 1.5rem;
}
@media (max-width: 460px) {
  footer {
    flex-direction: column;
    text-align: center;
  }  
}
</style>
<link
  rel="stylesheet"
  href="https://use.fontawesome.com/releases/v5.8.2/css/all.css"
  integrity="sha384-oS3vJWv+0UjzBfQzYUhtDYW+Pj2yciDJxpsK1OYPAYjqT085Qq/1cq5FLXAZQ7Ay"
  crossorigin="anonymous"
/>
<nav id="navbar" class="nav">
  <ul class="nav-buttons">
    <li>
      <a href="#welcome-section">Profile</a>
    </li>
    <li>
      <a href="#projects">Projects</a>
    </li>
    <li>
      <a href="#contacts">Contact</a>
    </li>
  </ul>
</nav>
<div class="portfolio">
  <section id="welcome-section">  
    <h1>Hello, I am Mirshod</h1>
    <h2>a web developer</h2>
  </section> 
  <section id="projects">
      <h1 class="portfolio-title">My portfolio</h1>
        <div class="projects-grid">
          <a href="https://codepen.io/MirshodM/full/ZEpYdmX" class="project-tile" target="_blank"><img class="project-image" src="https://raw.githubusercontent.com/Mirshod-rgb/das/main/MF%20fcc.JPG" alt="project-1"><p class="project-title">Tribute Page</p>
        </a>
         <a href="https://codepen.io/MirshodM/full/mdrwROj" class="project-tile" target="_blank"><img class="project-image" src="https://raw.githubusercontent.com/Mirshod-rgb/das/main/lemonform.JPG" alt="project-2"><p class="project-title">Survey Form</p>
        </a>
          <a href="https://codepen.io/MirshodM/full/bGwYZVr" class="project-tile" target="_blank"><img class="project-image" src="https://raw.githubusercontent.com/Mirshod-rgb/das/main/Prlandpage.JPG" alt="project-3"><p class="project-title">Product Landing Page</p>
        </a>
           <a href="https://codepen.io/MirshodM/full/bGwJBEQ" class="project-tile" target="_blank"><img class="project-image" src="https://raw.githubusercontent.com/Mirshod-rgb/das/main/Techdocpage.JPG" alt="project-3"><p class="project-title">Technical Documentation Webpage</p>
        </a>
    </div>
  </section>
  <section id="contacts" class="contacts">
    <h1 class="contacts-heading">Contacts</h1>
  <div class="contact-list">
    <a href="https://uz.linkedin.com/in/mirshod-mirzoev-6b575779" target="_blank" class="contact-button"><i class="fab fa-linkedin-in"></i> LinkedIn</a>
    <a href="https://www.google.com/intl/ru/gmail/about/" target="_blank" class="contact-button"><i class="fas fa-envelope-open-text"></i> Gmail</a>
     <a href="https://github.com/Mirshod-rgb" target="_blank" id="profile-link" class="contact-button"><i class="fab fa-github-square"></i> Github</a>
     <a href="https://www.skype.com/ru/" target="_blank" class="contact-button"><i class="fab fa-skype"></i> Skype</a>
    </div>
  </section>
</div>
<footer><p>
    &copy; Mirshod Mirzoev, inspired by
    <a href="https://www.freecodecamp.com/" target="_blank"
      >freeCodeCamp <i class="fab fa-free-code-camp"></i
    ></a>
  </p>
  <br><p>Terms</p> 
  <p>Privacy</p>
  </footer>

```

## Work experience:

1 Feb 2018–Present	**Senior Specialist of Procurement department** <br>
	POSCO International Textile LLC Bukhara Branch (Foreign Company)<br>
<br>	
5 Oct 2015–30 Jun 2016	**Specialist of Corporate customer service department**<br>
	Kapitalbank Bukhara branch, Joint Stock Commercial Bank (JSCB)<br>
 <br> 
## Education:

13 Dec 2021-present: **JS/Frontend Development** <br>
  RS School (EPAM Training)<br>
<br>
18 Nov 2020-present: **Web development** <br>
  freeCodeCamp.org<br>
<br>
1 Sep 2011–30 Jun 2015:	**Bachelor's degree in Banking**<br>
	Tashkent Institute of Finance<br>
<br>
## Languages:
	
Uzbek, Russian, English *(C1-IELTS 7.5)*, Korean and Arabic.
