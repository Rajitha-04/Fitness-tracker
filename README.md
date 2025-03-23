**Personal Fitness Tracker - Streamlit Web App**  

**Overview**  

This is a **Streamlit-based web application** that predicts **calories burned** during physical activity based on user inputs like **age, BMI, exercise duration, heart rate, and body temperature**. The app uses **machine learning (Random Forest Regressor)** to provide real-time predictions and displays similar results from the dataset.


 **Features**  
 
✅ **User Inputs**: Age, BMI, Duration, Heart Rate, Body Temperature, and Gender  
✅ **Real-time Prediction**: Displays estimated **calories burned**  
✅ **Progress Bars**: Visual indicators while processing inputs  
✅ **Similar Records**: Shows 5 users with similar calorie burns  
✅ **Statistical Insights**: Compares user stats with dataset  


**Tech Stack Used**  

 **1. Programming Language**  
- **Python**  

 **2. Libraries Used**  
 
- `streamlit` - Web UI framework  
- `numpy` - Numerical calculations  
- `pandas` - Data handling  
- `matplotlib` & `seaborn` - Data visualization  
- `scikit-learn` - Machine Learning 

**Dataset Used**  

- **calories.csv** - Contains calories burned per user  
- **exercise.csv** - Includes user exercise details  

 **How It Works**  

1. **User enters values** (Age, BMI, etc.) in the sidebar  
2. **Machine Learning model processes data** in the background  
3. **Predicted Calories Burned** is displayed  
4. **Similar users' data** and **comparative statistics** are shown  


**Future Enhancements**  

🚀 **Add more health parameters** (e.g., step count, sleep quality)  
🚀 **Improve accuracy** using deep learning  
🚀 **Deploy online** using **Hugging Face Spaces** or **Heroku**  
