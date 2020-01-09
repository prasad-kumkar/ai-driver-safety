# Deep Learning based driver monitoring system (activity & object recognition)
**Submission for**: Mercedes Benz Digital Challenge : Team Big Brains
**Name of College**: VELLORE INSTITUTE OF TECHNOLOGY , VELLORE
**Name of Team Members**:Prasad Kumkar, Tanishq Agrawal
**Theme of the Challenge**:Deep Learning based driver monitoring system (activity & object recognition)
**Problem Statement Chosen**:AI based computer Vision:
In recent years there has been a lot of focus on developing driver monitoring software for integration in passenger cars and other vehicles to facilitate better safety and other functions that improve the user experience. By studying a person’s posture and body movements, intelligent interior vehicle algorithms can draw conclusions about a person’s alertness, attention and focus.

Tomorrow’s cabin sensing features will include detection of passenger position, safety belt status and forgotten objects, as well as enabling multimodal functionality such as deeper AI and mood recognition.So the car is able to seamlessly transfer control of the vehicle to an awake and able driver, call for help in a medical emergency, or offer to play the perfect song for the moment.

**Solution Approach:
By Computer Vision**

1. Identification of the driver in order to allow the vehicle to automatically restore its preferences and settings.

2.Activity recognition:
   2.1 Deep learning model for recognition of continuous driver’s activity. 
   2.2 This includes activities such as driver talking on the phone, eating while driving the vehicle.              These activities will alert the system and make the driver more aware of the dangerous situation.
3.Detecting levels of driver impairment: 
  3.1 Using a camera and microphone for detecting drowsiness, distraction, yawn, eye closure, and       joy in real-time.
  3.2 Monitor driver fatigue and alert him when potential drowsiness situation is detected.
  3.3 Monitor driver attentiveness by ensuring he’s keeping his eyes on the road and that he is aware of any dangerous situation.
  3.4 Pilot a user interface thanks to the eyes by automatically selecting HMI areas.
4.Hand gesture control:
    A trained neural network to detect hand gestures for volume/ channel control or any other in built functionality of the car.
5.An intelligent steering wheel that monitors the heart rate to detect potential drowsiness of the driver. This is made by embedding the hand-grip heart rate monitor into the steering wheel of the vehicle.
6.After detection of the driver’s fatigue while driving, the driver can be alerted with special sensors or an electric impulse bracelet.

**Driving Style Classifier-AI**:The Driving style is simply analyzed by computational methodologies (Artificial Intelligence) and applied computing of transportation.

**Implementations of all Classifications Usinh Fuzzy Logic model**
Fuzzy Logic Model-A branch of Artificial Intelligence (AI), which will characterize the uncertainty in the data by adding truth and false concepts from common logic to a machine-generated model.

**Aggressive Driving Style Criteria: (Input Variables)**

1.Sudden Accelerations or Decelerations
2.Sudden Braking 
3.Sharp Turns
4.Set of events like start, stop, speed and turns 
5.Maximum and minimum rpm of the engine  
6.Number of Red light Jumps
7.Number of Tailgating cases
8.Number of Aggressive Honking 
9.Number of Wrong side Overtaking  

**Steps Involved**
1.Fuzzification: 
    This stage defines the membership functions and linguistic variables of the inputs.
2.Rules Evaluation: 
    In this stage, we will apply the fuzzy logic rules to calculate the output
3.Defuzzification:  
   The final conversion of the inputs to crisp results.

**Threshold Criteria**:(to be set for all classifications)
Example- the Threshold for harsh accelerations and decelerations has to be decided in by the System In accordance with the type of Road it is running on For example a city road or a state Highway or a National Highway. Because the speed limits will be different.

**Novelty**:
Our solution is a combination of three different approaches, which increases accuracy. This is a more intuitive use of the new generation of driver assistance functions. 
Most solutions being tested are based on just image processing. Combining computer vision, driving style, and heartbeat analysis and testing them has not been tried before. 


**Implementation Plan**:
Implementation is divided into the following parts:
1.Data acquisition :
A camera module is attached in front of the user which is continuously monitoring the activity of the driver. The hand-grip heart rate sensor embedded onto the steering wheel gives us the bpm of the driver.
2.Pre-processing :
Filtering on sensor data.
3.Data processing/ Feature Extraction:
AI/ Deep learning-based image processing for detecting the activity of the driver.
4.Classification:
Fuzzy classifier to classify the driver’s state by scaling drowsiness, distraction, yawn, eye closure, and joy in real-time based on the threshold values.












