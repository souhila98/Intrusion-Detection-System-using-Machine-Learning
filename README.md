# Intrusion-Detection-System-using-Machine-Learning
# Problem description 
In the realm of cybersecurity, machine learning plays a crucial role in intrusion detection by employing algorithms and techniques to automatically identify and classify malicious or anomalous activities within computer networks or systems. These machine learning approaches analyze network traffic patterns and relevant data to effectively detect and respond to security threats.

The primary objective of this project is to implement a comprehensive set of robust predictive models, specifically classifiers, capable of distinguishing between "bad connections" associated with intrusions or attacks and "good" connections representing normal network behavior. By deploying these predictive models, the system aims to enhance the overall security of computer networks and systems by proactively identifying malicious activities.

The project involves several stages, including exploratory data analysis (EDA), feature extraction, model training, and evaluation. Initially, a thorough analysis of the dataset is conducted, followed by the extraction of relevant features from the data.

The core of the project lies in training a robust set of predictive models using machine learning algorithms such as decision trees, support vector machines, and others [2]. These models are trained on a labeled dataset to learn the underlying patterns and characteristics associated with malicious or anomalous activities. Through this training process, the models acquire the ability to accurately distinguish between normal and potentially threatening network connections.

To ensure the effectiveness and reliability of the developed models, an evaluation will be conducted using appropriate performance metrics. This evaluation will assess the models' accuracy, precision, recall, and other relevant measures to determine their capability in detecting and classifying security threats.

# Dataset 
The KDD Intrusion Detection Dataset comprises a diverse range of intrusions simulated within a military network environment. It was specifically designed to gather raw TCP/IP dump data for a network by simulating a typical LAN used by the US Air Force. The LAN was structured to mimic a real environment and subjected to multiple attacks. In this context, a connection refers to a sequence of TCP packets that transmits data between a source IP address and a target IP address under a specific protocol, with a defined starting and ending time duration. Each connection is classified as either normal or an attack, with a unique attack type assigned to it. Each connection record contains approximately 100 bytes of data.

The dataset provides 41 quantitative and qualitative features for each TCP/IP connection, obtained from both normal and attack data. These features include 3 qualitative and 38 quantitative attributes. The class variable consists of two categories: "Normal" and "Anomalous."

# Approach
The objective of this project is to evaluate a set of classifiers to categorize network flows as either normal or anomalous. Different subsets of features from the dataset are used to train machine learning (ML) classifiers. Three approaches, namely correlated features, LASO, and random forest, are employed to select the best features. ML methods such as Naive Bayes, random forest, SVM, and xgboost are applied to the problem and assessed to determine the feasibility of using traditional ML approaches.
