# Intrusion-Detection-System-using-Machine-Learning
# Problem description 
Intrusion detection using machine learning is a field that harnesses algorithms and techniques to automatically identify and classify malicious or anomalous activities within computer networks or systems. By analyzing network traffic patterns and other relevant data, machine learning approaches have the potential to detect and respond to security threats effectively.

The primary focus of this project is to implement a comprehensive set of robust predictive models, specifically classifiers, that have the ability to distinguish between "bad connections" associated with intrusions or attacks and "good" connections representing normal network behavior. By deploying these predictive models, the system will contribute to enhancing the overall security of computer networks and systems by providing proactive identification of malicious activities.

The project involves various stages, including EDA, feature extraction, model training, and evaluation. Firstly, a deep analysis of the dataset is conducted. Next, relevant features are extracted from the data.

The core of the project lies in training a robust set of predictive models, leveraging machine learning algorithms such as decision trees, support vector machines,.... These models will be trained on the labeled dataset to learn the underlying patterns and characteristics associated with malicious or anomalous activities. Through this training process, the models will acquire the ability to accurately distinguish between normal and potentially threatening network connections.

To ensure the effectiveness and reliability of the developed models, an evaluation will be conducted using appropriate performance metrics. This evaluation will assess the models' accuracy, precision, recall, and other relevant measures to determine their capability in detecting and classifying security threats.

# Dataset 
The KDD Intrusion Detection Dataset consists of a wide variety of intrusions simulated in a military network environment. It was created to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. The LAN was focused like a real environment and blasted with multiple attacks. A connection is a sequence of TCP packets starting and ending at some time duration between which data flows to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labeled as either normal or as an attack with exactly one specific attack type. Each connection record consists of about 100 bytes.
For each TCP/IP connection, 41 quantitative and qualitative features are obtained from normal and attack data (3 qualitative and 38 quantitative features) . The class variable has two categories:
• Normal
• Anomalous

# Approach
The goal of this project is to test a set of classifiers for the categorization of network flows as either normal or anomalous. A different subsets of the features provided in the dataset will are used to train the ML classifiers. Three approaches including : correlated features, LASO and random forst are used to select the best features.
ML methods like Naive Bayes, random forest, SVM, xgboost are  applied to the problem and evaluated in order to assess the feasibility of using traditional machine learning approaches.
