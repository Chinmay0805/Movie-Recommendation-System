# Movie-Recommendation-System



## 📌 Project Overview
The **Movie Recommendation System** is a machine learning model designed to suggest movies based on user preferences. It utilizes collaborative filtering and content-based filtering techniques to enhance the recommendation accuracy.

---

## 🚀 Features
✅ Personalized movie recommendations based on user preferences  
✅ Uses **TF-IDF Vectorization** for content-based filtering  
✅ Implements **Cosine Similarity** for finding similar movies  
✅ Supports **Collaborative Filtering** using **Singular Value Decomposition (SVD)**  
✅ Interactive search feature for finding recommendations quickly  

---

## 🛠️ Tech Stack
| Component | Tool/Library |
|-----------|-------------|
| **Programming Language** | Python |
| **Data Handling** | Pandas, NumPy |
| **Machine Learning** | Scikit-learn, Surprise Library |
| **Natural Language Processing** | TF-IDF (Term Frequency-Inverse Document Frequency) |
| **Similarity Measures** | Cosine Similarity |
| **Visualization** | Matplotlib, Seaborn |

---

## 🔥 How It Works
1. **Data Collection:** Loads movie dataset containing movie titles, genres, and user ratings.
2. **Feature Extraction:** Uses **TF-IDF Vectorization** to analyze movie descriptions and genres.
3. **Similarity Calculation:** Applies **Cosine Similarity** to find movies with similar content.
4. **Collaborative Filtering:** Uses **SVD** to predict user preferences based on past ratings.
5. **Recommendation:** Generates top similar movies based on user selection.

---

## 📊 Dataset
The system is trained on a **public movie dataset** containing:  
🎥 Movie Titles  
🎭 Genres  
⭐ User Ratings  
📃 Descriptions  

---

## 📌 Installation & Usage
### 🔧 Install Dependencies
```bash
pip install pandas numpy scikit-learn surprise matplotlib seaborn
```

### 🚀 Run the Project
```bash
python movie_recommendation.py
```

---

## 📊 Output Example
- **Top 5 recommended movies for a given title**
- **Graphical visualization of recommendation accuracy**
- **User-based and item-based collaborative filtering results**

---

## 📜 Future Enhancements
✅ Implement deep learning models like AutoEncoders  
✅ Improve recommendation quality with hybrid filtering  
✅ Deploy as a web app using Flask or Streamlit  

---

## 🌟 Contribute
Feel free to **fork**, **improve**, and **contribute** to this project! 🎥🚀

---


