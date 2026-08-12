
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baron Offei-Darko | Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>BARON OFFEI-DARKO</h1>
            <h2 class="subtitle">Data Scientist</h2>
            <div class="contact-info">
                <a href="https://www.linkedin.com/in/baron-offei-darko-077b1b171/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
                <a href="mailto:baronoffeid@gmail.com"><i class="fas fa-envelope"></i> baronoffeid@gmail.com</a>
                <span><i class="fas fa-map-marker-alt"></i> Canterbury</span>
                <span><i class="fas fa-phone"></i> +44 7459144832</span>
            </div>
        </div>
    </header>

    <main class="container">
        <!-- Education Section -->
        <section id="education">
            <h2 class="section-title"><i class="fas fa-graduation-cap"></i> Education & Qualifications</h2>
            
            <div class="card">
                <div class="card-header">
                    <h3>University of Kent</h3>
                    <span class="date">Sept 2025 - Present</span>
                </div>
                <p class="degree">MSc Data Science</p>
                <p class="grade">Projected: <strong>DISTINCTION</strong></p>
            </div>

            <div class="card">
                <div class="card-header">
                    <h3>Anglia Ruskin University (Cambridge)</h3>
                </div>
                <p class="degree">BEng. Computer Science (Hons)</p>
                <p class="grade">Grade: <strong>UPPER SECOND CLASS</strong></p>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h2 class="section-title"><i class="fas fa-code"></i> Technical Skills</h2>
            <div class="card">
                <div class="skill-category">
                    <h3>Proficient</h3>
                    <div class="tags">
                        <span>Python</span><span>SQL</span><span>Tableau</span><span>NumPy</span><span>Matplotlib</span>
                        <span>R</span><span>Deep Learning</span><span>Active Directory</span><span>CRM</span>
                        <span>Microsoft Office Suite (Word, Excel, PowerPoint, Outlook, Access)</span>
                    </div>
                </div>
                <div class="skill-category mt-2">
                    <h3>Familiar</h3>
                    <div class="tags">
                        <span>Machine Learning</span><span>LLM</span><span>Pandas</span><span>AWS</span><span>Microsoft Azure</span>
                        <span>Node.js</span><span>Java</span><span>C</span><span>HTML</span><span>Power BI</span>
                        <span>MATLAB</span><span>Microsoft Windows Server</span><span>PowerShell</span><span>IT Systems</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects">
            <h2 class="section-title"><i class="fas fa-project-diagram"></i> Work Experience & Projects</h2>
            
            <div class="card project-card">
                <h3>Deep Learning Image Classification (QuickDraw dataset)</h3>
                <ul>
                    <li>Developed an end-to-end computer vision pipeline to classify 15 complex categories from a 112,500-image dataset.</li>
                    <li>Achieved 92.26% accuracy by implementing a custom VGG-style CNN, utilising targeted dropout layers and early stopping callbacks to eliminate overfitting.</li>
                    <li>Engineered efficient data pipelines using stratified sampling and optimised hyperparameter tuning (batch size, dropout rates and architecture) to ensure rapid, stable convergence.</li>
                </ul>
            </div>

            <div class="card project-card">
                <h3>Facial Recognition in MATLAB</h3>
                <ul>
                    <li>Developed a facial recognition system in MATLAB using the AlexNet neural network, training the convolutional neural network on images of five pro footballers for identity classification.</li>
                    <li>Achieved about 95% model accuracy in correctly identifying individuals, demonstrating strong model performance and effective dataset preparation.</li>
                    <li>Applied deep learning techniques for image classification, including transfer learning, data processing and model evaluation, to optimise recognition accuracy.</li>
                </ul>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2026 Baron Offei-Darko. Hosted on <a href="https://baron017.github.io" style="color: var(--accent-color);">baron017.github.io</a></p>
        </div>
    </footer>
</body>
</html>

/* --- Blue Theme Variables --- */
:root {
    --bg-main: #0B192C;         /* Deep Navy Background */
    --bg-card: #1A365D;         /* Slightly lighter blue for cards */
    --text-main: #E2E8F0;       /* Light grayish-blue for readable text */
    --text-muted: #94A3B8;      /* Muted text for dates and subtitles */
    --accent-color: #60A5FA;    /* Bright light blue for highlights */
    --accent-hover: #93C5FD;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    background-color: var(--bg-main);
    color: var(--text-main);
    line-height: 1.6;
}

.container {
    max-width: 900px;
    margin: 0 auto;
    padding: 0 20px;
}

/* --- Header --- */
header {
    background: linear-gradient(to right, #1E3A8A, #172554);
    padding: 60px 0 40px;
    border-bottom: 3px solid var(--accent-color);
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
}

header h1 {
    font-size: 2.8rem;
    letter-spacing: 2px;
    margin-bottom: 5px;
    color: #ffffff;
}

.subtitle {
    color: var(--accent-color);
    font-size: 1.2rem;
    font-weight: 400;
    margin-bottom: 25px;
}

.contact-info {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    font-size: 0.95rem;
}

.contact-info a, .contact-info span {
    color: var(--text-main);
    text-decoration: none;
    display: flex;
    align-items: center;
    gap: 8px;
    transition: color 0.3s;
}

.contact-info a:hover {
    color: var(--accent-color);
}

/* --- Main Content --- */
main {
    padding: 50px 20px;
}

section {
    margin-bottom: 50px;
}

.section-title {
    font-size: 1.8rem;
    color: var(--accent-color);
    margin-bottom: 25px;
    display: flex;
    align-items: center;
    gap: 12px;
    border-bottom: 1px solid rgba(96, 165, 250, 0.2);
    padding-bottom: 10px;
}

/* --- Cards --- */
.card {
    background-color: var(--bg-card);
    padding: 25px;
    border-radius: 10px;
    margin-bottom: 20px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    border: 1px solid rgba(255, 255, 255, 0.05);
    transition: transform 0.2s, box-shadow 0.2s;
}

.card:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

.card-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    margin-bottom: 10px;
}

.card-header h3 {
    color: #ffffff;
    font-size: 1.3rem;
}

.date {
    color: var(--accent-color);
    font-weight: bold;
    font-size: 0.9rem;
}

.degree {
    font-size: 1.1rem;
    margin-bottom: 5px;
}

.grade strong {
    color: var(--accent-color);
}

/* --- Skills Tags --- */
.skill-category h3 {
    color: #ffffff;
    margin-bottom: 15px;
    font-size: 1.1rem;
}

.mt-2 {
    margin-top: 25px;
}

.tags {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.tags span {
    background-color: rgba(96, 165, 250, 0.15);
    color: var(--accent-color);
    padding: 6px 14px;
    border-radius: 20px;
    font-size: 0.9rem;
    border: 1px solid rgba(96, 165, 250, 0.3);
}

/* --- Projects --- */
.project-card h3 {
    color: #ffffff;
    margin-bottom: 15px;
    font-size: 1.3rem;
}

.project-card ul {
    list-style-type: none;
    padding-left: 0;
}

.project-card ul li {
    position: relative;
    padding-left: 20px;
    margin-bottom: 12px;
    color: var(--text-muted);
}

.project-card ul li::before {
    content: "▹";
    position: absolute;
    left: 0;
    color: var(--accent-color);
    font-weight: bold;
}

/* --- Footer --- */
footer {
    text-align: center;
    padding: 30px;
    color: var(--text-muted);
    background-color: rgba(0,0,0,0.2);
    margin-top: 40px;
}

/* --- Mobile Responsiveness --- */
@media (max-width: 600px) {
    .card-header {
        flex-direction: column;
    }
    .date {
        margin-top: 5px;
    }
    header h1 {
        font-size: 2.2rem;
    }
}
