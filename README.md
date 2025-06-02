<h1>Bearing Diagnostic Using Machine Learning ⚙️📊

<h1>Bearing Analysis using HUST bearing: a practical dataset for ball bearing fault diagnosis</h1>

<h2>Project Overview</h2>
This study presents a practical approach to ball bearing fault diagnosis using the HUST (Huazhong University of Science and Technology) bearing dataset, which contains vibration signal data from various bearing health conditions. The objective is to accurately classify different types of bearing faults — such as inner race faults, outer race faults, and ball defects — as well as distinguish them from normal operational conditions.</h1> 
This project presents a bearing fault diagnosis system in rotating machinery using **K-Nearest Neighbor (KNN) classification** based on vibration signal analysis. The system supports **Condition-Based Maintenance (CBM)** by enabling early detection of various bearing faults such as **inner race defects, outer race defects, and ball faults**, helping prevent catastrophic failures and reduce maintenance costs. Signal processing and statistical feature extraction are integrated to provide an accurate and efficient diagnostic solution. <br /> 

<h2>Key Features</h2>

<b>✅ Real-Time Condition Monitoring – Capable of identifying various types of bearing faults using vibration signals.</b>

<b>✅ High Accuracy – KNN classifier achieves up to 96.4% accuracy for bearing fault classification.</b>

<b>✅ Feature Extraction & Selection – Combines Ensemble Empirical Mode Decomposition (EEMD) and Distance Evaluation Technique (DET) for optimal input features.</b>

<b>✅ MATLAB-Based Implementation – All processing stages including feature extraction, training, and testing are carried out in MATLAB.</b>

<b>✅ Multi-Speed Testing – Evaluated under different shaft speeds (e.g., 500 RPM, 1000 RPM, 1500 RPM) to ensure robustness across conditions.</b>

<h2>Development Process</h2>

<b>1️⃣ Data Collection – Vibration signals obtained from accelerometers mounted on bearing housings with various fault types and severities.</b>

<b>2️⃣ Signal Processing – Applied both time-domain and frequency-domain techniques to extract informative statistical features.</b>

<b>3️⃣ Feature Selection – EEMD and DET used to reduce dimensionality and retain only relevant indicators for classification.</b>

<b>4️⃣ Machine Learning Model – KNN classifier trained to distinguish between healthy and faulty bearing conditions (inner race, outer race, ball fault).</b>

<b>5️⃣ Model Evaluation – Performance assessed using accuracy, confusion matrix, precision, recall, and F1-score.</b>

<h2>Results & Impact</h2>

<b>🚀 Achieved average classification accuracy of 96.4%, validating the effectiveness of KNN for bearing fault diagnosis.</b>

<b>🚀 Simple and efficient classification method, suitable for low-power embedded systems.</b>

<b>🚀 Helps reduce downtime and extends equipment life through early fault detection and targeted maintenance.</b>

<h2>Future Improvements</h2>

<b>🔹 Integration with wireless IoT sensors for real-time bearing health monitoring.</b>

<b>🔹 Extension to detect compound bearing faults and other rotating component failures.</b>

<b>🔹 Comparison with ensemble and deep learning models (e.g., Random Forest, CNN) for performance enhancement.</b>

<p align="center">
Scatter Plot Of K Nearest Neighbour: <br/>
<img src="https://imgur.com/R3pDw6m.png" height="80%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confussion Matrix Of K Nearest Neighbour:  <br/>
<img src="https://imgur.com/a9AcqVX.png" height="80%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
Summary Of K Nearest Neighbour: <br/>
<img src="https://imgur.com/LtGFybc.png" height="80%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
