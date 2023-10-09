<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Your CSS styles here */
        .title {
            text-align: center;
            font-size: 36px;
            padding: 20px;
            white-space: nowrap;
            overflow: hidden;
            border-right: 3px solid green; /* Cursor effect */
            animation: typing 2s steps(40) forwards, blink-caret 0.5s step-end infinite;
        }

        @keyframes typing {
            from {
                width: 0;
            }
            to {
                width: 100%;
            }
        }

        @keyframes blink-caret {
            from, to {
                border-color: transparent;
            }
            50% {
                border-color: green;
            }
        }
    </style>
</head>
<body>
    <!-- Your content here -->
    <h1 class="title">ELI DANIELS: DATA SCIENTIST</h1>
</body>
</html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moving Green Dots Background</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: black;
        }

        /* Create a class for the green dot */
        .green-dot {
            position: fixed;
            width: 5px;
            height: 5px;
            background-color: green;
            border-radius: 100%;
        }
    </style>
</head>
<body>
    <!-- JavaScript to create and move green dots -->
    <script>
        // Function to create a green dot at a random position
        function createGreenDot() {
            const dot = document.createElement("div");
            dot.classList.add("green-dot");
            dot.style.left = `${Math.random() * 100}vw`;
            dot.style.top = `${Math.random() * 100}vh`;
            document.body.appendChild(dot);

            // Animate the dot's movement
            dot.animate(
                [
                    { transform: "translate(-10px, -10px)" },
                    { transform: "translate(10px, 10px)" },
                ],
                {
                    duration: 2000 + Math.random() * 3000, // Randomize the duration
                    iterations: Infinity,
                    direction: "alternate", // Make it bounce back and forth
                }
            );
        }

        // Create multiple green dots to cover the viewport
        for (let i = 0; i < 100; i++) { // You can adjust the number of dots
            createGreenDot();
        }
    </script>
</body>
</html>


Data-driven entrepreneur and versatile data scientist with a proven track record of leveraging diverse skill sets to seize opportunities. Proficient in data modeling and processing, as well as programming languages including Python and SwiftUI. Procuring, cleaning and interpreting data from varying sources to create solutions and overcome challenges.
                  
## Skills:
Python - SQL - Pandas - NLP - Keras - Tensor Flow - Data Visualization - Data Cleaning - Predictive Modeling - Database Structures - Agile Methodologies - Statistical Analysis - User Experience 

## Software: 
Jupyter Notebook - Visual Studio Code - Tableau - Power BI - Google Analytics - MongoDB - MySQL - Google Suite 

### CERTIFICATIONS 
General Assembly: Data Science Immersive
- - - - 
IBM Data Science Professional: Python for Data Science, AI & Development
- - - -
Databases and SQL for Data Science with Python 
- - - -
UX Design Process: Empathize, Define, and Ideate 

<style>
  .project-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
  }

  .project {
    background-color: #f5f5f5;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    max-width: 300px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  }

  .project-image img {
    max-width: 100%;
    height: auto;
    border-radius: 4px;
  }

  .project-description {
    margin-top: 10px;
  }

  .project-title a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
  }
</style>

<div class="project-container">
  <div class="project">
    <div class="project-image">
      <img src="assets/Emotion-image.jpg" alt="Emotion Recognition">
    </div>
    <div class="project-description">
      <div class="project-title"><a href="https://github.com/elidaniels99/Emotion_Recognition" target="_blank">Emotion Recognition using Deep Learning</a></div>
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
      <img src="assets/NLP.jpg" alt="Web APIs & NLP">
    </div>
    <div class="project-description">
      <div class="project-title"><a href="https://github.com/elidaniels99/Web-APIs-NLP" target="_blank">Web APIs & NLP</a></div>
      <p>
        Scraped and parsed data from subreddits enabling the collection of subscriber counts, posts, and relevant metrics for comprehensive comparative analysis. Employed advanced Natural Language Processing (NLP) techniques, including tokenization, lemmatization, and stopwords removal, to perform in-depth text analysis. This process facilitated sentiment analysis, keyword extraction, and content type classification, shedding light on user engagement and content preferences in these communities.
      </p>
    </div>
  </div>

  <div class="project">
    <div class="project-image">
      <img src="assets/fitnessimage.png" alt="Fitness Activity Recommender">
    </div>
    <div class="project-description">
      <div class="project-title"><a href="https://github.com/elidaniels99/FitnessActivityRecommender" target="_blank">Fitness Activity Recommender</a></div>
      <p>
        Assist individuals in achieving their fitness goals by analyzing fitness activity through data from two distinct tracking devices, being Apple Watch vs Fitbit. Leveraging data from these devices, including health-related attributes, we will calculate BMI, combine user-specific insights, and employ a predictive activity type model to create recommended fitness activities personalized to the individual to help them attain a BMI within the "normal" range.
      </p>
      <p><strong>Key Models:</strong></p>
      <ul>
        <li>K-Means Clustering Model to determine how the model would classify our known classifications of underweight, normal weight, overweight, and obese for optimized value of K.</li>
        <li>DBSCAN Model to compare the difference between the optimized value of K while comparing silhouette scores.</li>
        <li>Random Forests Model to predict activity type for users based on their fitness and health data.</li>
      </ul>
    </div>
  </div>
</div>


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Randomly Moving Square</title>
    <style>
        .moving-square {
            width: 100px;
            height: 100px;
            background-color: red;
            position: fixed;
            animation: changePosition 5s linear infinite, changeColor 5s linear infinite;
        }

        @keyframes changePosition {
            0% {
                left: 0;
                top: 0;
            }
            25% {
                left: calc(100% - 100px);
                top: 0;
            }
            50% {
                left: calc(100% - 100px);
                top: calc(100% - 100px);
            }
            75% {
                left: 0;
                top: calc(100% - 100px);
            }
            100% {
                left: 0;
                top: 0;
            }
        }

        @keyframes changeColor {
            0% {
                background-color: red;
            }
            25% {
                background-color: blue;
            }
            50% {
                background-color: green;
            }
            75% {
                background-color: yellow;
            }
            100% {
                background-color: red;
            }
        }
    </style>
</head>
<body>
    <div class="moving-square"></div>

    <script>
        const square = document.querySelector(".moving-square");

        function randomPosition() {
            const maxX = window.innerWidth - square.clientWidth;
            const maxY = window.innerHeight - square.clientHeight;
            const randomX = Math.random() * maxX;
            const randomY = Math.random() * maxY;
            square.style.left = randomX + "px";
            square.style.top = randomY + "px";
        }

        // Initial random position
        randomPosition();

        // Update position every 5 seconds for a slower movement
        setInterval(randomPosition, 5000);
    </script>
</body>
</html>
