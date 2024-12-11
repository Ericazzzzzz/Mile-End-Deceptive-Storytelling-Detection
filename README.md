# **Exploring Audio Features for Deceptive Storytelling Detection Using Machine Learning**

## 📝 **Project Overview**
This project addresses the complex challenge of detecting deceptive storytelling using audio analysis, an underexplored area in deception research. By leveraging machine learning, the project frames deception detection as a binary classification task (truthful vs. deceptive), relying solely on non-invasive audio features. Unlike traditional methods, such as polygraphs, this approach provides a portable, accessible, and scalable solution for real-world applications.

---

## 🌟 **Key Contributions**
- **End-to-End Machine Learning Pipeline**: Designed and implemented a complete workflow, from data preprocessing and feature extraction to model training and evaluation, using real-world datasets from MLEnd.
- **🎶 Audio Feature Engineering**: Extracted meaningful features like power, pitch mean, pitch standard deviation, and voice fraction from 30-second audio segments using Librosa.
- **🤖 Model Development and Evaluation**:
  - Trained multiple machine learning models, including Logistic Regression, SVM, and XGBoost, to classify audio narratives.
  - Achieved the highest F1 score of 0.42, successfully identifying patterns in nuanced and imbalanced data.
  - Evaluated model performance using detailed metrics (true positives, true negatives, false positives, false negatives) to derive actionable insights.
- **💡 Innovative Methodology**: Demonstrated the feasibility of deception detection using speech data, eliminating the reliance on physiological cues and enabling a user-friendly approach.

---

## 🛠️ **Technical Stack**
- **Programming & Libraries**: Python, Librosa, PyDub, Scikit-learn, XGBoost, Matplotlib, Seaborn.
- **Skills Demonstrated**: Audio signal processing, feature engineering, model evaluation, and performance optimization.

---

## 🚀 **Impact**
This project paves the way for non-invasive deception detection tools with applications in law enforcement, psychological research, and private consulting. While the models achieved moderate performance, the project highlights critical areas for improvement and future research, including expanding datasets and exploring advanced deep learning techniques.

---

Feel free to explore the code and contribute ideas for further enhancements! 🌟


