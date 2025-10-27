# PPE-Detection
An overview of the project
 This project's main goal is to use machine learning and deep learning techniques to create a computer vision-based PPE (personal protective equipment) detection system.
 It automatically determines whether construction site workers are donning the necessary safety gear, including masks, safety vests, and hard hats.

 The YOLOv8 real-time object detection technology is used in the system's construction, and a Streamlit dashboard is used for an interactive, user-friendly interface that displays compliance levels.

 aims

 Create an AI model that can recognize personal protective equipment (PPE) like safety vests, masks, and hardhats.

 Group employees according to their degree of compliance:

 Green: Every piece of PPE was found (Compliant)

 Yellow: One or two PPE items were found (partially compliant).

 Red: No PPE found (Non-Compliant)

 Install the model on Streamlit Cloud for inference and monitoring in real time.
 Specifications of the Model
 YOLOv8 is the model used.
 Because of its high detection accuracy, quick inference speed, and simplicity of integration with Python, YOLOv8 was selected.
 Six classes were taught to the model: Hardhat, Mask, Safety Vest, No-Hardhat, No-Mask, and No-Safety Vest.

 Process Workflow

 Construction workers' PPE photos were gathered and labeled as part of the dataset preparation process.  Divide the data into 30 percent testing and 70 percent training.

 Model Training: Pre-trained weights were used to train the YOLOv8 model on Google Colab.

 Model Evaluation: The accuracy and consistency of the model were assessed by testing it on unseen images.

 Deployment: Streamlit Cloud was used to create and implement an interactive dashboard.
 Result
 PPE items can be accurately detected by the system in a variety of background and lighting conditions.
 It can be scaled for industrial use and assists in automating safety compliance monitoring on building sites.
 Clear visual detections and well-organized compliance reporting demonstrated the model's high accuracy.

 How to Operate Nearby

 Make a clone.

 Pip install -r requirements.txt can be used to install dependencies.

 The command streamlit run app.py can be used to launch the application.

 Potential Enhancements
 • Include additional PPE categories such as boots, goggles, and gloves.
 • Enhanced detection in congested and low-light conditions.
 • Connect to CCTV cameras to enable real-time surveillance.
 • To improve generalization, fine-tune YOLOv8 using a larger dataset.
 conclusion
 This project shows how computer vision and artificial intelligence can be used to address practical safety issues.
 This system offers an automated, precise, and user-friendly method of guaranteeing safety compliance on building sites by training and implementing a YOLOv8 model for PPE detection.
 From data preparation to real-time deployment and monitoring, it embodies an entire AI workflow.
