<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <link rel="stylesheet" href="src/styles.css" />
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Cabin:wght@400;500;600;700&display=swap" rel="stylesheet">
        <title>Portfolio</title>
    </head>
    <body>
        <section class="hero">
            <nav>
                <!-- <div>LOGO</div> -->
                <ul id="nav-list">
                    <li><a href="#about-me">About Me</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact-me">Contact</a></li>
                </ul>
                <button class="hamburger" id="hamburger">
                   <a>
                    <svg width="24" height="24" xmlns="http://www.w3.org/2000/svg" fill="#ffffff" fill-rule="evenodd" clip-rule="evenodd"><path d="M12 16c1.656 0 3 1.344 3 3s-1.344 3-3 3-3-1.344-3-3 1.344-3 3-3zm0 1c1.104 0 2 .896 2 2s-.896 2-2 2-2-.896-2-2 .896-2 2-2zm0-8c1.656 0 3 1.344 3 3s-1.344 3-3 3-3-1.344-3-3 1.344-3 3-3zm0 1c1.104 0 2 .896 2 2s-.896 2-2 2-2-.896-2-2 .896-2 2-2zm0-8c1.656 0 3 1.344 3 3s-1.344 3-3 3-3-1.344-3-3 1.344-3 3-3zm0 1c1.104 0 2 .896 2 2s-.896 2-2 2-2-.896-2-2 .896-2 2-2z"/></svg>
                   </a>
                </button>
            </nav>
            <div class="hero-area">
                <div class="hero-text">
                    <h1>Lillian Aisha Wood</h1>
                    <p>Full Stack Intern @ WTRI</p>
                    <div class="button"><a href="#about-me">About Me</a></div>
                </div>
                <div class="socials">
                    <a href=https://www.linkedin.com/in/lillian-wood-b49ab3172?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B1%2BaFARIxRd6hzckfHhKJlw%3D%3D" class="social">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="#ffffff" width="50" height="50" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                    </a>
                    <a href="https://github.com/lilly-pad" class="social">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="#ffffff" width="50" height="50" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
                    </a>
                </div>
            </div>
            
        </section>
        <section class="sub-section" id="about-me">
            <div class="information">
                <h2>About Me</h2>
                <p>Hello! My name is Lillian Wood.</p>
            </div>
            <div class="headshot-container">
                <img class="headshot" src="src/images/me.jpg" alt="Lillian Wood Headshot"/>
            </div>
        </section>
        <section class="sub-section-alternative" id="projects">
            <h2>Projects</h2>
            <div class="project-container">
                <div class="project-card">
                    <img class="project-image" src="" alt="Project One"/>
                    <h3>Project One</h3>
                    <p class="subtext">This is project one.</p>
                    <hr/>
                    <p class="subtext"><a class="project-link" href="https://github.com/lilly-pad/COGS-118B-Final-Project">View Here</a></p>
                </div>
                <div class="project-card">
                    <img class="project-image" src="" alt="Project Two"/>
                    <h3>Project Two</h3>
                    <p class="subtext">This is project two.</p>
                    <hr/>
                    <p class="subtext"><a class="project-link" href="https://github.com/lilly-pad/COGS-118B-Final-Project">View Here</a></p>
                </div>
                <div class="project-card">
                    <img class="project-image" src="" alt="Project Three"/>
                    <h3>Project Three</h3>
                    <p class="subtext">This is project three.</p>
                    <hr/>
                    <p class="subtext"><a class="project-link" href="https://github.com/lilly-pad/COGS-118B-Final-Project">View Here</a></p>
                </div>
                <div class="project-card">
                    <img class="project-image" src="" alt="Project Four"/>
                    <h3>Project Four</h3>
                    <p class="subtext">This is project four.</p>
                    <hr/>
                    <p class="subtext"><a class="project-link" href="https://github.com/lilly-pad/COGS-118B-Final-Project">View Here</a></p>
                </div>
            </div>
        </section>
        <footer id="#contact-me">
            <h2>Contact Me!</h2>
        </footer>


        <script src="src/app.js"></script>
    </body>
</html>
