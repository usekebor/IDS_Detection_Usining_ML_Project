# IDS_Detection_Usining_ML_Project
# Problem Statement	
Many modern systems, like smart home gadgets, wireless sensor networks (WSNs), and time-sensitive networks (TSNs), are very vulnerable to cyberattacks such as denial-of-service (DoS) and low-rate DoS (LDoS). Traditional intrusion detection systems (IDS) struggle to detect these advanced threats effectively due to limited adaptability and outdated rules (Topsakal, Cevher and Ergenç, 2025). To fix this, machine learning (ML) based could be used, However, due to data imbalance and high false positives, it is less reliable to implement machine learning (ML) based IDS hard to implement reliably (Afroz, Nyakwende and Goswami 2025). This project would address the lack of low effectiveness and inaccuracies in ML-based IDS for real-time detection across different network environments.

# Background & Literature Review
Machine learning has shown strong potential in detecting network intrusions, especially in smart environments and TSNs. Topsakal, Cevher and Ergenç (2025) state that prior research has explored ML models like Support Vector Machines (SVM), k-Nearest Neighbors (KNN), and ensemble methods to identify intrusions with high accuracy. However, most of these studies faced challenges such as poor dataset quality, high false positives and lack of real-time deployment. For example, LDoS attacks in TSNs are hard to detect because of their dynamic traffic changes (Topsakal et al., 2025). Furthermore,Fares et al. (2025) illustrate that in most smart homes and WSNs, low memory and energy limit the smart devices limit the performance IDs. Consequently, this project builds on these works by developing an efficient and adaptable IDS using ML techniques, which addresses data imbalance and aiming for real-time detection with reduced false positives.

# Research Questions	
1. How well can machine learning detect low-rate and complex intrusion attacks in TSNs, smart homes, and WSNs?
2. What impact does dataset quality and imbalance have on ML-based IDS accuracy?
3. Which ML algorithm offers the best balance between detection accuracy and speed for real-time use?
4. How can false positives be minimised while maintaining high detection performance?

# Project Aims	
To design and implement a machine learning-based intrusion detection system that accurately detects modern cyberattacks in TSNs, smart homes, and WSNs with improved real-time performance and low false positives.

# Project Objectives	
1. Develop a labelled dataset containing normal and attack traffic from selected environments
2. Evaluate and compare machine learning (ML) algorithms for intrusion detection performance.
3. Implement feature selection and oversampling techniques to handle data imbalance.
4. Deploy and test the IDS in a simulated or real-time environment.
5. Minimise false positives while maintaining high accuracy and low latency detection.

# Feasibility, Significance and Potential for Innovation	
# Feasibility
Resources: I would use the Python language, Jupyter Notebooks, and available public datasets for the development and implementation of the model for this project.
Timeline: The timeline of this project would be properly illustrated in a Gantt chart, with the Work divided into various sections such as data preparation, model development, evaluation, deployment, and reporting.

# Significance
Academic Impact: This project could contribute to the increasing research on the implementation of ML in IDS to mitigate cyberattacks.
Practical impact: This project could also be useful for industries that are deploying IoT, automotive TSN, and sensor networks for the improvement of threat detection and reduction of system downtime.

# Potential Innovation:
•	This Project would combine real-time detection and ML-based modelling for different network types.
•	This Project would introduce strategies to improve dataset quality and model efficiency, which would move beyond traditional static or rule-based IDS.
•	This project would also contribute to emerging cybersecurity network solutions.

# References

AFROZ, M., NYAKWENDE, E. and GOSWAMI, B., 2025. Intrusion Detection in Smart Home Environments: A Machine Learning Approach. Transportation Research Procedia, 84, pp. 243–250.
https://www.sciencedirect.com/science/article/pii/S2352146525001176

FARES, H. et al., 2025. Intrusion Detection in Wireless Sensor Networks using Machine Learning. Procedia Computer Science, 252, pp. 912–921.
https://www.sciencedirect.com/science/article/pii/S1877050925000523

TOPSAKAL, M., CEVHER, S. and ERGENÇ, D., 2025. A machine learning-based intrusion detection framework with labeled dataset generation for IEEE 802.1 time-sensitive networking. Journal of Systems Architecture, , pp. 103408.
https://www.sciencedirect.com/science/article/pii/S1383762125000803

