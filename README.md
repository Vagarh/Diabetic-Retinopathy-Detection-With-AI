# Diabetic Retinopathy Detection With AI

## Description

Diabetic retinopathy is the leading cause of blindness among the working-age population in the developed world, affecting over 93 million people globally. According to the US Centers for Disease Control and Prevention, 29.1 million people in the United States have diabetes, and the World Health Organization estimates that 347 million people are affected worldwide. Diabetic Retinopathy (DR) is an eye disease closely associated with long-term diabetes, and it is estimated that between 40% and 45% of Americans with diabetes suffer from some stage of DR. The progression of this disease can lead to significant vision impairment or even blindness if not detected and treated promptly. Unfortunately, DR often remains asymptomatic until it reaches an advanced stage, making timely detection challenging.

Currently, DR detection is a manual, labor-intensive process requiring trained clinicians to analyze and evaluate digital color fundus photographs of the retina. This process is time-consuming, with results often delayed by a day or two, leading to lost follow-ups, miscommunication, and delayed treatment. Clinicians typically identify DR by detecting lesions related to the vascular abnormalities caused by the disease. While this method is effective, it is resource-intensive, requiring specialized expertise and equipment that may not be readily available in regions with high diabetes prevalence, where DR detection is most urgently needed. As the global diabetic population continues to grow, the existing infrastructure to prevent blindness due to DR will become increasingly insufficient.

The need for an automated, comprehensive DR screening method has long been recognized. Significant progress has been made in using image classification, pattern recognition, and machine learning to address this issue. By leveraging color fundus photography, this project aims to push the boundaries of automated DR detection, striving to develop models with realistic clinical potential. The ultimate goal is to create models that can be open-sourced, thereby maximizing their impact on improving DR detection and, consequently, patient outcomes.

For context, Google and Aravind Eye Hospital have been working on similar initiatives, demonstrating the potential of AI in detecting eye diseases (see [Google's collaboration with Aravind Eye Hospital](https://venturebeat.com/2019/02/25/google-works-with-aravind-eye-hospital-to-deploy-ai-that-can-detect-eye-disease/)).

The data for this project is sourced from [Kaggle's Diabetic Retinopathy Detection competition](https://www.kaggle.com/c/diabetic-retinopathy-detection).

## Objectives

1. **Theoretical Understanding**: 
   - Gain a deep understanding of the theory and intuition behind Deep Neural Networks (DNNs), Residual Networks (ResNets), and Convolutional Neural Networks (CNNs).
   
2. **Data Handling**: 
   - Utilize Python libraries to import, preprocess, and visualize retinal images effectively.
   
3. **Data Augmentation**: 
   - Apply data augmentation techniques to enhance the generalization capability of the model.
   
4. **Model Development**: 
   - Construct a deep learning model based on Convolutional Neural Networks and Residual Blocks using Keras with TensorFlow 2.0 as the backend.
   
5. **Model Training**: 
   - Compile and fit the deep learning model to the training data, optimizing it for performance.
   
6. **Performance Evaluation**: 
   - Assess the trained CNN's performance and ensure its generalization by evaluating various key performance indicators (KPIs), such as accuracy, precision, and recall.

This project aspires to contribute to the global effort to mitigate the impact of diabetic retinopathy by advancing the development of AI-driven diagnostic tools, potentially offering timely and accurate screenings to populations at risk.
