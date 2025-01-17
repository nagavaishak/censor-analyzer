# censor-analyzer

# Social Media Censoring using visual sentiment analysis

Objective:
The project aims to create a dynamic system that identifies and filters inappropriate content (e.g., vulgar or offensive images) in real time on a social media platform. This platform resembles apps like Instagram or Facebook, allowing users to upload images, browse feeds, and interact with other users while ensuring safety through automated content moderation.

Tech Stack:
Front-End:

Flutter: Used for building a cross-platform app that runs on Android, iOS, and Windows.
Dart: Programming language powering Flutter.
Back-End:

Firebase APIs: For authentication, real-time database management, and cloud storage.
Machine Learning:

InceptionV3 (Transfer Learning Model):
Used for image classification.
Pre-trained on the ImageNet dataset with 78.1%+ accuracy.
TensorFlow: Framework used for model training and implementation.
TFLite (TensorFlow Lite): Optimized for mobile and embedded devices, enabling real-time classification.
Development Tools:

Visual Studio Code
Android Studio
Netron (Model visualization)
Google Colab (Model training and preprocessing)
Programming Languages:

Python (for ML model training and preprocessing)
Dart (for the app's business logic and interface)
Key Features:
Real-Time Image Moderation:

Filters offensive or vulgar content before upload.
Provides warnings to users if inappropriate content is detected.
Fully Functional Social Media App:

User registration and login.
Feed to browse posts.
User interactions like comments, likes, and profile searches.
Machine Learning Integration:

Pre-trained InceptionV3 model fine-tuned to detect specific types of inappropriate content (e.g., gore).
Classification accuracy: 96.67%.
Scalable and Cross-Platform:

Single codebase supports multiple platforms.
Future Improvements:
Extending moderation capabilities to detect nudity, profane text, and other harmful content.
Enhancing the dataset and model to increase accuracy further.
Adding more features to improve app usability and performance.
