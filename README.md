<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eli Daniels - Data Scientist Portfolio</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #121212; /* Dark background color */
            color: #FFFFFF; /* Text color */
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #212121; /* Header background color */
            padding: 20px;
            text-align: center;
        }

        h1 {
            font-size: 36px;
        }

        nav {
            text-align: center;
            margin-top: 20px;
        }

        nav a {
            text-decoration: none;
            color: #FFFFFF;
            margin: 0 15px;
        }

        .section {
            padding: 40px 0;
        }

        .section-header {
            font-size: 28px;
            text-align: center;
        }

        .section-content {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.5;
        }

        .project {
            margin: 40px 0;
            display: flex;
            align-items: center;
        }

        .project-image {
            flex: 1;
        }

        .project-image img {
            max-width: 100%;
            height: auto;
        }

        .project-description {
            flex: 2;
            padding-left: 20px;
        }

        .project-description p {
            margin-top: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Eli Daniels - Data Scientist</h1>
        <nav>
            <a href="#profile">Profile</a>
            <a href="#skills">Skills</a>
            <a href="#software">Software</a>
            <a href="#certifications">Certifications</a>
            <a href="#projects">Projects</a>
        </nav>
    </header>

    <section id="profile" class="section">
        <div class="section-header">Profile</div>
        <div class="section-content">
            Data-driven entrepreneur and versatile data scientist with a proven track record of leveraging diverse skill sets to seize opportunities. Proficient in data modeling and processing, as well as programming languages including Python and SwiftUI. Procuring, cleaning and interpreting data from varying sources to create solutions and overcome challenges.
        </div>
    </section>

    <section id="skills" class="section">
        <div class="section-header">Skills</div>
        <div class="section-content">
            <ul>
                <li>Python</li>
                <li>SQL</li>
                <li>Pandas</li>
                <li>NLP</li>
                <li>Keras</li>
                <li>Tensor Flow</li>
                <li>Data Visualization</li>
                <li>Data Cleaning</li>
                <li>Predictive Modeling</li>
                <li>Database Structures</li>
                <li>Agile Methodologies</li>
                <li>Statistical Analysis</li>
                <li>User Experience</li>
            </ul>
        </div>
    </section>

    <section id="software" class="section">
        <div class="section-header">Software</div>
        <div class="section-content">
            <ul>
                <li>Jupyter Notebook</li>
                <li>Visual Studio Code</li>
                <li>Tableau</li>
                <li>Power BI</li>
                <li>Google Analytics</li>
                <li>MongoDB</li>
                <li>MySQL</li>
                <li>Google Suite</li>
            </ul>
        </div>
    </section>

    <section id="certifications" class="section">
        <div class="section-header">Certifications</div>
        <div class="section-content">
            <ul>
                <li>General Assembly: Data Science Immersive</li>
                <li>IBM Data Science Professional: Python for Data Science, AI & Development</li>
                <li>Databases and SQL for Data Science with Python</li>
                <li>UX Design Process: Empathize, Define, and Ideate</li>
            </ul>
        </div>
    </section>

    <section id="projects" class="section">
        <div class="section-header">Projects</div>
        
        <div class="project">
            <div class="project-image">
                <img src="assets/Emotion-image.jpg" alt="Emotion Recognition" width="300" height="200">
            </div>
            <div class="project-description">
                <p>
                    Developed and implemented a deep learning-based emotion recognition model for facial images. Conducted data preprocessing, feature extraction, and model training using Python, TensorFlow, and Keras. Created an interactive web application using Streamlit to provide a user-friendly interface.
                </p>
                <p><strong>Streamlit App:</strong></p>
                <ul>
                    <li><strong>Image Emotion Recognition:</strong> Upload an image to detect and display emotions expressed in human faces. The app uses deep learning to recognize emotions like happiness, sadness, surprise, anger, disgust, neutral.</li>
                    <li><strong>Live Webcam Emotion Detection:</strong> Experience real-time emotion detection through your webcam. Toggle the webcam feed, and see your own emotions overlaid on the live video.</li>
                </ul>
            </div>
        </div>

        <div class="project">
            <div class="project-image">
                <img src="assets/NLP.jpg" alt="Web APIs & NLP" width="300" height="200">
            </div>
            <div class="project-description">
                <p>
                    Scraped and parsed data from subreddits enabling the collection of subscriber counts, posts, and relevant metrics for comprehensive comparative analysis. Employed advanced Natural Language Processing (NLP) techniques, including tokenization, lemmatization, and stopwords removal, to perform in-depth text analysis. This process facilitated sentiment analysis, keyword extraction, and content type classification, shedding light on user engagement and content preferences in these communities.
                </p>
            </div>
        </div>

        <div class="project">
            <div class="project-image">
                <img src="assets/fitnessimage.png" alt="Fitness Activity Recommender" width="300" height="200">
            </div>
            <div class="project-description">
                <p>
                    Assist individuals in achieving their fitness goals by analyzing fitness activity through data from two distinct tracking devices, being Apple Watch vs Fitbit. Leveraging data from these devices, including health-related attributes, we will calculate BMI, combine user-specific insights, and employ a predictive activity type model to create recommended fitness activities personalized to the individual to help them attain a BMI within the "normal" range.
                </p>
            </div>
        </div>
    </section>
</body>
</html>
