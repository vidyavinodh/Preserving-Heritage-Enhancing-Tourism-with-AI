🏛️ Preserving Heritage & Enhancing Tourism with AI
📌 Project Overview

This project leverages Artificial Intelligence (AI) to support heritage preservation and tourism enhancement. It combines deep learning for image classification with data analytics and recommendation systems to provide meaningful insights and improve tourist experiences.

## 📂 Dataset

Due to size limitations, the full dataset is not included in this repository.

The solution is divided into two key components:

# Heritage Image Classification (Deep Learning)
Tourism Data Analysis & Recommendation System
# Objectives
Classify heritage structures automatically from images
Analyze tourism data to uncover trends and user preferences
Build a recommendation system for personalized travel suggestions
# Part 1: Heritage Image Classification
📁 Dataset & Preprocessing
Dataset consists of images representing various heritage sites
Applied preprocessing techniques:
Image resizing
Pixel normalization
Used data augmentation to improve generalization:
Rotation
Flipping
Zooming
# Model Architecture
Implemented Transfer Learning using MobileNet
Leveraged pre-trained weights for efficient learning
Fine-tuned the model for multi-class image classification
# 📊 Results
Test Accuracy: 93%
Validation Accuracy: 95% (after augmentation)
# Key Insights
Transfer learning significantly reduces training time
Data augmentation improves robustness and prevents overfitting
Model performs well across diverse heritage image categories
🚀 Conclusion (Part 1)

The MobileNet-based model successfully classifies heritage site images with high accuracy, making it suitable for automated heritage recognition systems.

# 📊 Part 2: Tourism Data Analysis
🔍 Exploratory Data Analysis (EDA)

Analyzed datasets containing:

User information
Tourist locations
Ratings and preferences
Key Visualizations:
Distribution of tourist destinations
Popular cities and regions
User rating behavior
# 📈 Key Findings
Certain cities have consistently higher user ratings
Nature and entertainment tourism dominate user preferences
Ratings play a critical role in destination popularity
# 🧾 Tourism Type Classification
Tourism descriptions were processed using NLP techniques
Keyword extraction used to classify locations into:
1. Nature
2. Historical/Cultural
3. Entertainment
4. Shopping
5. Religious

This categorization helps identify the most relevant tourism types for different locations.

# Recommendation System
⚙️ Approach
Built using Collaborative Filtering
Created a User-Item Matrix:
Rows → Users
Columns → Places
Values → Ratings
Applied Cosine Similarity to find similar destinations
# 📊 Results
Recommends tourist destinations based on user preferences
Suggests similar places based on rating patterns
Enhances personalized travel experiences

# Tech Stack
Python
TensorFlow / Keras
Pandas, NumPy
Scikit-learn
NLP techniques
Matplotlib, Seaborn

# 📈 Overall Conclusion

This project demonstrates how AI can be used to:

Automate heritage site recognition using deep learning
Analyze tourism patterns through data-driven insights
Enhance user experience with recommendation systems

It highlights the integration of Computer Vision, NLP, and Recommender Systems in solving real-world problems.

# 🚀 Future Improvements
Deploy as a web or mobile application
Use advanced architectures (EfficientNet, Vision Transformers)
Implement hybrid recommendation systems
Add real-time, location-based recommendations