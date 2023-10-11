# YogaSensei
[Youtube Link]([url](https://www.youtube.com/watch?v=oSZjsI99uf4))
 
YogaSensei is a revolutionary web application designed to enhance the yoga practice experience using computer vision, NLP, and machine learning (deep + transfer). Its primary aim is to provide real-time feedback and corrections to yoga practitioners, helping them perfect their poses and achieve a deeper understanding of yoga asanas, along with practice and test modes, offering tailored suggestions, personalized recommendations, meditation and health tips, dashboard to view progress, a leaderboard feature to foster healthy competition and user community to interact and share their progress with friends and family.
Technical Aspects:
- **Web Application**: YogaSensei is accessible through a web browser, making it convenient and platform-independent.
- **Real-time Feedback**: YogaSensei leverages real-time analysis of users' yoga poses, thanks to advanced computer vision and machine learning algorithms.
- **Keypoint Detection**: YogaSensei employs pose estimation algorithms to detect key body landmarks in real time, allowing for precise analysis of posture.
 
YogaSensei offers two distinct modes to cater to users at different stages of their yoga journey: Practice Mode and Test Mode.
- **Practice Mode**: Users can practice yoga poses while receiving immediate feedback on their alignment and posture. YogaSensei compares their pose to a reference frame and suggests corrections in real time.
- **Test Mode**: In this mode, users can record or upload videos of their yoga sessions. The application then analyzes each frame, classifying them as correct, incorrect, partially correct, or none. Users receive detailed scores and feedback.
- **Machine Learning Models**: YogaSensei employs a combination of Convolutional Neural Networks (CNNs) for image analysis and fine-tuned pre-trained models (e.g., Xception, MobileNet) for pose classification.
- **Scoring Algorithm**: The application's scoring algorithm calculates scores based on the percentage of correct frames, partially correct frames, and incorrect frames in the video. It provides users with a detailed breakdown of their performance.
- **[Extensive Dataset Development (32000+ images and videos) ]([url](https://drive.google.com/drive/folders/1F7YfuSDeu9NVW50MX1XWolbK0f8sKBR6))**: YogaSensei's accuracy and effectiveness hinge on the quality and diversity of its dataset. To train its machine learning models effectively, YogaSensei undertook the creation of an extensive dataset, encompassing thousands of images and videos.
- **Labeling and Classification**: The dataset was divided into two parts: labeled and unlabeled. Unlabeled videos had their keypoints extracted and 3D coordinates stored, which were used to generate labeled videos with lines connecting keypoints. Classes included correct, incorrect, partially correct, and none, with further subdivisions.
YogaSensei employs a variety of machine learning models to classify yoga poses accurately. These models are designed to handle the intricacies of human body movement and alignment.
- **CNNs (Convolutional Neural Networks)**: CNNs are used for image analysis, enabling YogaSensei to identify and classify yoga poses based on image data.
- **Fine-tuning Pre-trained Models**: YogaSensei leverages transfer learning by fine-tuning pre-trained models, such as Xception, MobileNetV2, DenseNet121, InceptionV3, Resnet50a etc. These models are trained on large datasets and adapted for pose classification.
 
To achieve high accuracy while preventing overfitting, YogaSensei employs a range of strategies during model development.
- **Data Augmentation, Hyperparameter Tuning, Learning Rate Scheduling**
- **Transfer Learning**: Pre-trained models serve as a starting point, allowing YogaSensei to leverage features learned from large datasets on similar tasks. Fine-tuning adapts these models for pose classification.
 
YogaSensei takes model evaluation seriously and employs a comprehensive set of performance metrics to assess the quality of its machine learning models. The selection process is guided by a weighted evaluation approach and the TOPSIS algorithm.
 
**Parameters** - Accuracy, Precision, Recall,F1 Score, Average Inference Time per Image, Average Specificity, F2 Score, Inference Speed, Model Complexity
 
- **Ensemble Methods**: Ensemble methods, such as combining predictions from multiple top-performing models, are considered to further enhance accuracy and reliability.
- **Regular Model Updates**: The application maintains a commitment to continuous model improvement, incorporating user feedback and expanding the dataset to adapt to changing needs.
All of the above aspects have been accomplished and currently we are working on expanding the variations of each asana, introducing more asanas, and building the user community feature.
Thus, we firmly believe that YogaSensei can play a Crucial role in the engagement of common people and masses to perform yoga anywhere and everywhere conveniently through mobile devices and holds a strong entrepreneurial potential. 
