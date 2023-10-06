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

:root {
  --color-black: #161616;
  --color-white: #fff;
  --size: 170px; /* Fully responsive */
}

/* Cat */
.cat {
  position: relative;
  height: var(--size);
  width: calc(var(--size) * 1.13);
}

/* Ears */
.ear {
  position: absolute;
  top: -30%;
  height: 60%;
  width: 25%;
  background: var(--color-white);
}

/* Ear hair */
.ear::before,
.ear::after {
  content: '';
  position: absolute;
  bottom: 24%;
  height: 10%;
  width: 5%;
  border-radius: 50%;
  background: var(--color-black);
}

.ear::after {
  transform-origin: 50% 100%;
}

.ear--left {
  left: -7%;
  border-radius: 70% 30% 0% 0% / 100% 100% 0% 0%;
  transform: rotate(-15deg);
}

.ear--left::before,
.ear--left::after {
  right: 10%;
}

.ear--left::after {
  transform: rotate(-45deg);
}

.ear--right {
  right: -7%;
  border-radius: 30% 70% 0% 0% / 100% 100% 0% 0%;
  transform: rotate(15deg);
}

.ear--right::before,
.ear--right::after {
  left: 10%;
}

.ear--right::after {
  transform: rotate(45deg);
}

/* Face */
.face {
  position: absolute;
  height: 100%;
  width: 100%;
  background: var(--color-black);
  border-radius: 50%;
}

/* Eyes */
.eye {
  position: absolute;
  top: 35%;
  height: 30%;
  width: 31%;
  background: var(--color-white);
  border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
}

/* Eyelids */
.eye::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  height: 0;
  width: 100%;
  border-radius: 0 0 50% 50% / 0 0 40% 40%;
  background: var(--color-black);
  animation: blink 4s infinite ease-in;
}

@keyframes blink {
  0% { height: 0; }
  90% { height: 0; }
  92.5% { height: 100%; }
  95% { height: 0; }
  97.5% { height: 100%; }
  100% { height: 0; }
}

/* Tips of the eyes */
.eye::before {
  content: '';
  position: absolute;
  top: 60%;
  height: 10%;
  width: 15%;
  background: var(--color-white);
  border-radius: 50%;
}

.eye--left {
  left: 0;
}

.eye--left::before {
  right: -5%;
}

.eye--right {
  right: 0;
}

.eye--right::before {
  left: -5%;
}

/* Pupils */
.eye-pupil {
  position: absolute;
  top: 25%;
  height: 50%;
  width: 20%;
  background: var(--color-black);
  border-radius: 50%;
  animation: look-around 4s infinite;
}

@keyframes look-around {
  0% { transform: translate(0); }
  5% { transform: translate(50%, -25%); }
  10% { transform: translate(50%, -25%); }
  15% { transform: translate(-100%, -25%); }
  20% { transform: translate(-100%, -25%); }
  25% { transform: translate(0, 0); }
  100% { transform: translate(0, 0); }
}

.eye-pupil.eye--left {
  right: 30%;
}

.eye-pupil.eye--right {
  left: 30%;
}

/* Glare on the pupil */
.eye-pupil::after {
  content: '';
  position: absolute;
  top: 30%;
  right: -5%;
  height: 20%;
  width: 35%;
  border-radius: 50%;
  background: var(--color-white);
}

/* Muzzle */
.muzzle {
  position: absolute;
  top: 60%;
  left: 50%;
  height: 6%;
  width: 10%;
  background: var(--color-white);
  transform: translateX(-50%);
  border-radius: 50% 50% 50% 50% / 30% 30% 70% 70%;
}

/* General page styling */
html {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  background: var(--color-black);
}
