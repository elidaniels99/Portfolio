# Portfolio

<html>
<head>
<style>
.text {
  color: green;
  transition: color 0.3s ease;
}

.text:hover {
  color: red;
}
</style>
</head>
<body>

<h1 class="text">ELI DANIELS: DATA SCIENTIST</h1>

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

## [Emotion Recognition using Deep Learning](https://github.com/elidaniels99/Emotion_Recognition){:target="_blank" style="color: white;"}
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

## [Web APIs & NLP](https://github.com/elidaniels99/Web-APIs-NLP){:target="_blank" style="color: white;"}
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

## [Fitness Activity Recommender](https://github.com/elidaniels99/FitnessActivityRecommender){:target="_blank" style="color: white;"}
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
- K-Means Clustering Model to determine how the model would classify our known classifications of underweight, normal weight, overweight, and obese for optimized value of K.
- DBSCAN Model to compare the difference between the optimized value of K while comparing silhouette scores.
- Random Forests Model to predict activity type for users based on their fitness and health data.

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        /* Your existing CSS styles here */

        /* Parallax background */
        .parallax {
            background-image: url('your-background-image.jpg');
            background-attachment: fixed;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            height: 100vh;
        }

        /* Content container with background color */
        .content-container {
            background-color: rgba(0, 0, 0, 0.7); /* Adjust the background color and opacity */
            color: white;
            padding: 20px;
        }
    </style>
</head>
<body>
    <!-- Parallax section -->
    <div class="parallax">
        <!-- Content container -->
        <div class="content-container">
            <!-- Your portfolio content here -->
            <h1>ELI DANIELS: DATA SCIENTIST</h1>
            
            <!-- Rest of your portfolio content -->

            <!-- Navigation links with smooth scrolling -->
            <nav>
                <ul>
                    <li><a href="#section-skills" data-scroll>Skills</a></li>
                    <li><a href="#section-software" data-scroll>Software</a></li>
                    <li><a href="#section-certifications" data-scroll>Certifications</a></li>
                    <!-- Add more links as needed -->
                </ul>
            </nav>
        </div>
    </div>

    <!-- Sections with content and corresponding IDs -->
    <div id="section-skills">
        <!-- Skills section content here -->
    </div>
    <div id="section-software">
        <!-- Software section content here -->
    </div>
    <div id="section-certifications">
        <!-- Certifications section content here -->
    </div>

    <!-- Include the smooth-scroll.js library -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/smooth-scroll/16.1.3/smooth-scroll.min.js"></script>
    
    <!-- Initialize smooth-scroll.js -->
    <script>
        var scroll = new SmoothScroll('a[data-scroll]', {
            speed: 1000, // Adjust the scrolling speed as needed
            offset: 50, // Offset for scroll position (e.g., for fixed headers)
        });
    </script>
</body>
</html>

