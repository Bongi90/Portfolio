<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abongile Valashiya Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>

    <header>
        <nav>
            <div class="nav-left">
                <a href="#">Abongile Valashiya</a>
            </div>
            <div class="nav-right">
                <a href="#about">About</a>
                <a href="#experience">Experience</a>
                <a href="#skills">Skills</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <main>
        <section id="hero" class="hero">
            <div class="hero-content">
                <h1>Hi, I'm Abongile!</h1>
                <p>A passionate professional with a background in administration and a focus on AI data training. Eager to contribute my skills to innovative projects.</p>
                <div class="social-icons">
                    <a href="#" target="_blank"><i class="fab fa-linkedin"></i></a>
                    <a href="#" target="_blank"><i class="fab fa-github"></i></a>
                </div>
            </div>
        </section>

        <section id="about" class="about">
            <div class="section-inner">
                <h2>About Me</h2>
                <p>A highly organized and tech-savvy administrative professional with 10+ years of experience streamlining operations and a recent foray into the exciting world of AI data training. My career has been defined by my ability to efficiently manage complex tasks, communicate effectively, and adapt quickly to new challenges. My core strengths include executive support, project management, communication, adaptability, and technical proficiency. I am passionate about leveraging my skills to provide exceptional support in a dynamic and innovative environment.</p>
            </div>
        </section>

        <section id="experience" class="experience">
            <div class="section-inner">
                <h2>Experience</h2>
                <article>
                    <h3>Advanced Al Data Trainer</h3>
                    <p class="company">Invisible Technologies (March 2024 - March 2025)</p>
                    <ul>
                        <li>Worked closely with a team of trainers under protocols developed by leading Al researchers.</li>
                        <li>Trained Al to read, write, summarize knowledge, and interpret meaning, akin to a language arts teacher.</li>
                        <li>Generated examples of ideal conversations, acting as both the User and the Al.</li>
                        <li>Collected sources to help Al read and distinguish between facts, context, and patterns of behavior.</li>
                        <li>Continuously evaluated Al based on safety, accuracy, and beneficial criteria.</li>
                        <li>Tested Al by trying to "break" it, documenting breaks, and recommending improvements to training methods.</li>
                    </ul>
                </article>

                <article>
                    <h3>Administration Clerk</h3>
                    <p class="company">TB HIV CARE NPO (January 2013 - January 2024)</p>
                    <ul>
                        <li>Calendar Management: Coordinate and manage client schedules, including scheduling meetings, appointments, and events.</li>
                        <li>Email Management: Organize, prioritize, and respond to client emails, ensuring timely communication and task completion.</li>
                        <li>Project Management: Assist with the planning, execution, and monitoring of various client projects, ensuring deadlines and deliverables are met.</li>
                        <li>Travel Planning: Arrange travel logistics for clients, including booking flights, accommodations, and creating detailed itineraries.</li>
                        <li>Document Preparation: Create, edit, and format documents, presentations, and reports as needed.</li>
                        <li>Client Communication: Serve as the main point of contact for clients, maintaining professional and effective communication at all times.</li>
                        <li>Research & Data Entry: Conduct research and manage data to support client projects and business needs.</li>
                    </ul>
                </article>
            </div>
        </section>

        <section id="skills" class="skills">
            <div class="section-inner">
                <h2>Skills</h2>
                <ul class="skills-grid">
                    <li>Data Management</li>
                    <li>Analytical Abilities</li>
                    <li>Technical Skills</li>
                    <li>Problem-Solving</li>
                    <li>Communication</li>
                    <li>Adaptability</li>
                    <li>Teamwork</li>
                    <li>Confidentiality</li>
                </ul>
            </div>
        </section>

        <section id="projects" class="projects">
            <div class="section-inner">
                <h2>Projects</h2>
                <div class="projects-grid">
                    <article class="project">
                        <h3>AI Training Project</h3>
                        <p>Contributed to a project focused on training AI models for natural language processing tasks.</p>
                        <a href="#">Learn More</a>
                    </article>
                    <article class="project">
                        <h3>Data Management System</h3>
                        <p>Assisted in the implementation of a new data management system for TB HIV CARE NPO.</p>
                        <a href="#">Learn More</a>
                    </article>
                    </div>
            </div>
        </section>

        <section id="contact" class="contact">
            <div class="section-inner">
                <h2>Contact</h2>
                <p>I'm always open to new opportunities. Feel free to reach out!</p>
                <a href="mailto:avalashiya90@gmail.com" class="email-link">Email Me</a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Abongile Valashiya</p>
    </footer>

</body>
</html>
/* Basic Reset */
body, h1, h2, h3, p, ul, li {
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; /* A modern font */
    line-height: 1.6;
    background-color: #f0f0f0; /* Light gray background */
    color: #333;
}

/* Navigation */
header {
    background-color: #ffffff; /* White header */
    color: #333;
    padding: 1rem 0;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Subtle shadow */
    position: sticky;
    top: 0;
    z-index: 100; /* Ensure it stays on top */
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1rem;
}

.nav-left a {
    color: #333;
    text-decoration: none;
    font-size: 1.5rem;
    font-weight: bold;
}

.nav-right a {
    color: #333;
    text-decoration: none;
    margin-left: 1rem;
    transition: color 0.3s ease; /* Smooth color transition */
}

.nav-right a:hover {
    color: #007bff; /* Highlight on hover */
}

/* Hero Section */
.hero {
    background-color: #ffffff;
    padding: 5rem 0;
    text-align: center;
}

.hero-content {
    max-width: 800px;
    margin: 0 auto;
}

.hero h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.1rem;
    color: #555;
    margin-bottom: 2rem;
}

.social-icons a {
    margin: 0 0.5rem;
    color: #333;
    font-size: 1.5rem;
    transition: color 0.3s ease;
}

.social-icons a:hover {
    color: #007bff;
}

/* Sections */
section {
    max-width: 1200px;
    margin: 2rem auto;
    padding: 2rem;
    background-color: #ffffff;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* More pronounced shadow */
    border-radius: 8px; /* Rounded corners */
}

.section-inner {
    max-width: 1000px;
    margin: 0 auto;
}

h2 {
    font-size: 2rem;
    border-bottom: 2px solid #ccc;
    padding-bottom: 0.5rem;
    margin-bottom: 1.5rem;
    color: #333;
}

/* About Section */
.about p {
    font-size: 1.1rem;
    color: #555;
}

/* Experience Section */
.experience article {
    margin-bottom: 2rem;
    padding-bottom: 2rem;
    border-bottom: 1px solid #eee;
}

.experience article:last-child {
    border-bottom: none;
    margin-bottom: 0;
    padding-bottom: 0;
}

.experience h3 {
    font-size: 1.5rem;
    margin-bottom: 0.5rem;
}

.company {
    font-weight: bold;
    color: #007bff;
    margin-bottom: 0.5rem;
}

.experience ul {
    list-style: disc;
    margin-left: 1.5rem;
    color: #555;
}

/* Skills Section */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 1rem;
    list-style: none;
}

.skills-grid li {
    background-color: #e7f0ff; /* Light blue background */
    padding: 0.75rem 1.25rem;
    border-radius: 5px;
    transition: background-color 0.3s ease, color 0.3s ease;
    text-align: center;
    color: #333;
}

.skills-grid li:hover {
    background-color: #007bff;
    color: #fff;
}

/* Projects Section */
.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.project {
    border: 1px solid #ddd;
    padding: 2rem;
    border-radius: 8px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 12px rgba(0, 0, 0, 0.15);
}

.project h3 {
    font-size: 1.5rem;
    margin-top: 0;
    margin-bottom: 1rem;
}

.project p {
    color: #555;
    font-size: 1.1rem;
}

.project a {
    display: inline-block;
    background-color: #007bff;
    color: #fff;
    padding: 0.5rem 1rem;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 1rem;
    transition: background-color 0.3s ease;
}

.project a:hover {
    background-color: #0056b3;
}

/* Contact Section */
.contact p {
    font-size: 1.1rem;
    color: #555;
    margin-bottom: 2rem;
}

.email-link {
    display: inline-block;
    background-color: #007bff;
    color: #fff;
    padding: 0.75rem 1.5rem;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 1rem;
    transition: background-color 0.3s ease;
    font-weight: bold;
}

.email-link:hover {
    background-color: #0056b3;
}

/* Footer */
footer {
    text-align: center;
    padding: 1.5rem 0;
    background-color: #333;
    color: #fff;
    font-size: 0.9rem;
}

/* Media Queries for Responsiveness */
@media (max-width: 768px) {
    nav {
        flex-direction: column;
        align-items: flex-start;
    }

    .nav-right {
        margin-top: 1rem;
    }

    .hero h1 {
        font-size: 2rem;
    }

    .skills-grid {
        grid-template-columns: 1fr;
    }

    .projects-grid {
        grid-template-columns: 1fr;
    }
}
