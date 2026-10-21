This mini-project brings together everything you've learned: proper document structure, semantic headings (h1 through h6), clean div containers with descriptive classes and IDs, text formatting tags (strong, em, i), line breaks (br), separators (hr), and all required sections (Page Title/Heading, About Me, Education, Technical Skills, Hobbies, and Contact Information)—all built using pure HTML without external CSS.

index.html Code
Save the following code into a file named index.html:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Introduction Mini-Project</title>
</head>
<body data-project-id="html-foundations-final">

    <!-- Header & Main Heading Section -->
    <div id="header-section" class="container header-container">
        <h1 class="main-title">Alex Morgan</h1>
        <p class="subtitle"><em>Full-Stack Software Engineering Student & Open Source Enthusiast</em></p>
    </div>

    <hr>

    <!-- About Me Section -->
    <div id="about-section" class="container content-section">
        <h2 class="section-heading">About Me</h2>
        <p class="about-text">Hello and welcome! I am a dedicated technology student focused on building a strong foundation in web development and software architecture. I enjoy learning how browsers render code, solving logical problems, and creating user-friendly digital experiences. When I am not writing code, you can find me reading sci-fi novels or exploring nature trails.</p>
    </div>

    <hr>

    <!-- Education Section -->
    <div id="education-section" class="container content-section">
        <h2 class="section-heading">Education</h2>
        
        <div class="education-item">
            <h3 class="degree-title">Bachelor of Science in Computer Science</h3>
            <h4 class="institution">State University <span class="year-span" style="font-weight: normal;">(2022 — 2026)</span></h4>
            <p>Focused on core computer science fundamentals, data structures, algorithms, and modern web engineering principles.<br>
            Graduating with a <strong>strong</strong> academic record and consistent honors.</p>
            
            <h5>Relevant Coursework</h5>
            <h6>Web Architecture, Database Management Systems, and Object-Oriented Programming</h6>
        </div>
    </div>

    <hr>

    <!-- Technical Skills Section -->
    <div id="skills-section" class="container content-section">
        <h2 class="section-heading">Technical Skills</h2>
        <p>Here are the primary technologies and tools I specialize in:</p>
        <ul class="skills-list">
            <li><strong>HTML5 & CSS3:</strong> Creating semantic, structured, and accessible web layouts.</li>
            <li><em>JavaScript (ES6+):</em> Adding dynamic logic, interactivity, and asynchronous data handling.</li>
            <li><i>Git & GitHub:</i> Managing version control workflows and collaborative development.</li>
            <li><strong>Command Line:</strong> Navigating Unix/Linux environments efficiently.</li>
        </ul>
    </div>

    <hr>

    <!-- Hobbies Section -->
    <div id="hobbies-section" class="container content-section">
        <h2 class="section-heading">Hobbies & Interests</h2>
        <p>Outside of academics and coding, I love staying active and creative:</p>
        <p class="hobbies-details">
            <span><strong>Reading:</strong> Exploring science fiction and technology history books.</span><br>
            <span><em>Photography:</em> Capturing urban street architecture and landscapes.</span><br>
            <span><i>Cycling:</i> Long-distance weekend bike rides.</span>
        </p>
    </div>

    <hr>

    <!-- Contact Information Section -->
    <div id="contact-section" class="container content-section">
        <h2 class="section-heading">Contact Information</h2>
        <p>Feel free to reach out for project collaboration, networking, or inquiries:</p>
        <p class="contact-details">
            <span><strong>Email:</strong> alex.morgan@example.com</span><br>
            <span><em>LinkedIn:</em> linkedin.com/in/alexmorgan-dev</span><br>
            <span><i>GitHub:</i> github.com/ry703606-code</span>
        </p>
    </div>

</body>
</html>
How to Complete Your Submission & GitHub Upload
Save the File: Make sure the code above is saved precisely as index.html in your project directory.

Test Locally: Open index.html in your web browser (like Chrome) to verify that all sections render properly, headings flow logically, and all required text formatting appears correctly.

Commit to Git & GitHub:
Open your terminal/command prompt in your project folder and run the following commands:

Bash
git init
git add index.html
git commit -m "Complete Assignment 2.5 H