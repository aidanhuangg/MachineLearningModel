# MachineLearningModel
Inspiration
A single traumatic brain injury caused by a car accidents, falls, concussions, etc can cause Dementia or Schizophrenia which go un-detected and grow worse over time. Dementia is a general term for loss of memory, language, problem-solving and other thinking abilities, moreover it includes Alzheimer's disease and Parkinson's disease. People with dementia have problems with thinking and remembering that affects their ability to manage their daily life. During uncertain times like these where people avoid going to the hospital, we present a simple a web-app tool to detect neurological problems such as Alzheimer and Schizophrenia with maximum accuracy.

What it does
Now you must be wondering, how can we detect neurological problems without MRI and some brains scans ? The answer simple, you just have to draw a clock face.

The user just needs to draw a clock-face on our web-app, or scan and upload one and our machine learning model will predict whether they need medical attention or not. We use the famous clock-drawing test to screen people for signs of neurological problems, such as Alzheimer’s and other dementias. The clock-drawing test is often used in combination with other, more thorough screening tests, but even when used by itself, it can provide helpful insight into a person’s cognitive ability.

Healthy-Drawing


UnHealthy-Drawing


How we built it
Used Angular (1.x) for the website
Made our dataset from scratch for clock-faces
Used CNN to make our Machine Learning model
We used Flask API to connect the website with our model
CNN model
For the detection we had used CNN architecture, which can be summarised as: 

Accuracy
The following was the accuracy vs epoch graph: 

Part of web-app screenshots
High Risk - Drawn on our web-app


No Risk - Uploaded scanned image from device


Challenges we ran into
Creating the dataset was the main challenge, there were no already datasets of hand drawn clock-faces, so we had to create dataset of our own which was extremely time consuming. Since we had a small dataset, we ran into trouble to train our model, and gain high accuracy. However, after hours of grinding we were finally able to create a good enough model with accuracy that is sufficient for the incubation stage.

Accomplishments that we're proud of
Generating a non-existing dataset
Creating a ML model with optimum accuracy
Creating a way for users to draw directly on our web-app
Doing all this in 2 days
What's next for Detect Neurological problems
We want to improve our model accuracy and achieve the best result we can. Maybe we will work with other diseases and make it an online diagnosis for multiple diseases.
