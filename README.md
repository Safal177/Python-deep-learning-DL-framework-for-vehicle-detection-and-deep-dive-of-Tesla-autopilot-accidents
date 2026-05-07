# Python-deep-learning-DL-framework-for-vehicle-detection-and-deep-dive-of-Tesla-autopilot-accidents

# Project title:
Automatic vehicle detection using deep learning (computer vision) and Tesla autopilot accident analysis

# Project background:
With the accelerated development of autonomous driving systems, detection accuracy for vehicles and awareness for real-world traffic accident patterns are significant. This project leverages a combination of (1) a Python deep learning associated with object detection computer vision model to pinpoint vehicles in images, and (2) a statistical analysis of Tesla crash data to examine fatal crash cases and autopilot-related incidents.
For AI supported transportation systems, coupling of computer vision with real-world data analysis supports both application development and practical findings.

# Project objective:
•	Construct a convolutional neural network (CNN) model for vehicle detection and bounding box prediction.
•	With labeled image data, train and then evaluate the model.
•	Analyze the Tesla accident dataset using end-to-end Exploratory Data Analysis (EDA) approaches.
•	Research on driver behavior including death trends and some risks factors involved in autopilot.
•	Examine accident trends by uncovering key findings from dataset

# Core technologies:
•	Jupyter notebook (Python) | NumPy | Pandas | Matplotlib | Seaborn | TensorFlow (Keras) |  Scikit-learn. 

# Project elements:

Project # 1: Vehicle detection using CNN deep approach
•	Dataset preparation: normalization of pixel values | bounding box resizing | conversion of class labels into one-hot vectors 
•	Develop a deep learning CNN model with two outputs [vehicle localization (regression for bounding box) and classification]
•	Training the model: Train-test split including validation with batch training
•	Model evaluation criteria: Accuracy | loss (bounding box and classification) 

Project # 2: Tesla accident data analysis used for Data Science
•	Dataset cleansing process: dropped duplicate rows | addressed missing values | converted categorical data into numerical values
•	Exploratory Data Analysis (EDA) applied for: accident distribution by year, date, state, and country | analysis of deaths per accident | Tesla driver and passenger death cases | cyclist and pedestrian participation in accidents | Tesla collision frequency with other vehicles | distribution of accidents across Tesla models | confirmed distribution of autopilot deaths, and high performing in bounding box predictions

# Results:
With a CNN model:
•	trained an object detection model with obtaining reliable results
•	accuracy (about 100%) in classification task
•	Strong in bounding box predictions
•	Model correctly classified vehicles in the dataset (images).

# Data analysis outcomes:
•	One death in most crashes                                                                                                              
•	In Tesla occupant deaths, about 16% of accidents  
•	Frequency of higher accidents observed in some Tesla models
•	Autopilot deaths confirmed as accurate deaths are not frequent.

# Model output:
•	Training loss obtained from bounding box is about 0.64. 
•	Model with unseen image dataset works well. 
•	Accuracy involved for image classification is 100%.
•	Test dataset with CNN model works well.

# Project conclusion:
End-to-end AI workflow is clearly shown in this project. It has 
•	CNN Model: Recognizes vehicles in images dataset with high precision and appropriate for self-driving applications.
•	Data science analysis: Gathers primary accident patterns over time engaging Tesla vehicles, increase consciousness of safety issues for drivers, pedestrians, and occupants
The combination of computer vision (deep learning) and real-world data analytics helps open valuable patterns in AI safety and transportation applications.

# Project file:
capstone__one_automatic_detection_of_vehicles_deep_learning_framework_analyze_usage_autopilot.ipynb

