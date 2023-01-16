# Diabetic-Retinopathy-Detection

Diabetic retinopathy (DR) is one of the most common reasons for human vision loss in the working-age population of the world. The disease gets severe if it is not treated properly at its early stages. If DR is diagnosed early enough, vision deterioration may be delayed or even prevented. In this study, we propose an automatic grading system to detect the presence and severity of the Diabetic Retinopathy directly from fundus images via transfer learning. The proposed methodology consists of building a deep convolutional neural network on the top of RESNET50 for the classification of fundal images based on severity of the image. The system is developed by using a high-quality dataset of DR medical images provided at Kaggles’ APTOS (ASIA PACIFIC TELE OPHTHALMOLOGY SOCIETY) challenge in which all fundus images are taken by Aravind Eye Hospital. We evaluate the model designed using 5 metrics. Results show that our model has a high accuracy of 93% with Quadratic Kappa Score of 95%. Meanwhile it has precision of 88%, Recall of 85% and F1 score of 86%. We also have developed a Web Application where end users can upload the fundus images of both eyes and get tested with the severity of their eyes. Our model provides consistent detection results with high accuracy and specificity instantaneously. Hence, this work helps ophthalmologists by providing insights during the diagnostic process. The application developed is hosted at the url: http://18.205.216.30:5000/ using amazonec2@aws.

<img width="544" alt="image" src="https://user-images.githubusercontent.com/47912649/212686181-e341a36d-6638-4148-93e8-a4a700f35a75.png">
<img width="507" alt="image" src="https://user-images.githubusercontent.com/47912649/212686238-a7105bd9-7427-4e5b-8056-ab54d0f85866.png">

DR Stages

<img width="518" alt="image" src="https://user-images.githubusercontent.com/47912649/212686301-202a5a8b-030c-41a7-8bcd-5ece3a4b0741.png">



TSNE visualisation

<img width="468" alt="image" src="https://user-images.githubusercontent.com/47912649/212686363-24b18c5d-5705-4893-8931-c3da6cef5ae2.png">

Preprocessed Image 

<img width="1009" alt="image" src="https://user-images.githubusercontent.com/47912649/212686625-8a7da7cb-055c-4102-858f-d6673c30ece4.png">
