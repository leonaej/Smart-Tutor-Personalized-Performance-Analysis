# Smart-Tutor-Personalized-Performance-Analysis
Smart Tutor: A personalized learning system integrating Learning Process Knowledge Tracing (LPKT) and Graph Neural Networks (GNN) to model student learning behavior, predict performance, and recommend tailored tutorials for improved learning outcomes.

## 🔹Overview
**Smart Tutor** is an intelligent, adaptive learning environment that tracks student progress and predicts knowledge states over time. The system addresses the limitations of one-size-fits-all learning by integrating **Learning Process Knowledge Tracing (LPKT)** and **Graph Neural Networks (GNN)** to capture both temporal learning patterns and conceptual relationships.

The goal is to create a **personalized tutoring system** that identifies a student’s weak areas and recommends targeted tutorials and quizzes for efficient learning.

## 🔹Core Idea
- **LPKT Module:** Models sequential learning, capturing how knowledge evolves over time.  
- **GNN Module:** Models relationships between concepts using graph structures.  
- **Fusion Layer:** Combines temporal and relational understanding for accurate knowledge prediction.  

This joint LPKT + GNN model predicts the probability of correct answers, enabling adaptive feedback and personalization in learning systems.

## 🔹Dataset
The model uses the **EdNet: KT1 dataset**, which contains over 100 million student interactions with timestamps, questions, and concept mappings.  
Key preprocessing steps include:
- Cleaning incomplete or untagged responses  
- Normalizing timestamps to model learning and forgetting  
- Building concept graphs based on question relationships  
- Applying an 80/20 temporal train-test split  

## 🔹Experimental Design
- **Metrics:** Accuracy, AUC, and RMSE  
- **Baselines:** Standard LPKT and Graph-only models  
- **Validation:** Temporal split and multiple training runs for statistical significance (paired t-test, Wilcoxon test)

Expected improvements include:
- +3–5% AUC increase over baselines  
- Statistically significant performance gains (p < 0.05)

## 🔹Potential Impact
Smart Tutor demonstrates how AI can be used *for learning*, not to replace it. By combining LPKT and GNN, it delivers:
- Personalized learning recommendations  
- Improved student engagement and retention  
- Foundations for scalable, explainable educational AI  

## 🔹 Paper Included
- The paper describing the approache (`Paper.pdf`) is included in the root folder.


