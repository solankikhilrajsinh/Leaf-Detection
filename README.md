# Leaf-Detection
This project is a mobile-based Leaf Disease Detection System developed using Kotlin, Android development, Firebase, and a trained machine learning model. The system identifies plant leaf diseases from images using a convolutional neural network trained on a Kaggle leaf disease dataset. It delivers real-time predictions through a streamlined mobile interface supported by a cloud-connected backend. The project integrates UI/UX design, model training, frontend development, and Firebase services to provide a complete end-to-end solution.

# Features
- Detection and classification of plant leaf diseases from uploaded or captured images
- CNN-based machine learning model trained on the Kaggle leaf disease dataset
- Native Android app using Kotlin for smooth and responsive performance
- Firebase integration for storage, authentication, and real-time database usage
- User-friendly UI/UX built with modern design principles
- Backend logic for image preprocessing and prediction handling
- Scalable architecture for future model upgrades

# Tech Stack
- Kotlin (Android Development)
- Python (Model Training)
- TensorFlow / Keras
- Firebase (Storage, Authentication, Database)
- Android XML UI
- Kaggle Leaf Disease Dataset

# Dataset
The model is trained on a comprehensive Kaggle dataset containing labeled leaf images. Each entry includes:
- High-quality leaf images
- Disease classification labels
- Healthy vs. multiple disease categories
The dataset is split into training, validation, and testing sets to ensure robust model performance.

# How It Works
1. Leaf images from the user are uploaded or captured via the Android app.
2. The image is preprocessed and sent to the trained ML model.
3. The CNN model predicts the disease category.
4. Firebase handles storage and data communication between app and backend.
5. The app displays prediction results along with confidence levels, offering a clean and intuitive user experience.

# Conclusion
The Leaf Disease Detection System demonstrates a complete pipeline—from dataset preparation and model training to mobile app development and cloud integration. It provides accurate disease classification, a polished UI/UX, and strong backend support through Firebase. This project showcases the practical application of AI in agriculture and the potential for real-world deployment.
