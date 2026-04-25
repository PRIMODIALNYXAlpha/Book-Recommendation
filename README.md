# 📚 Book Recommendation System

## 📌 Overview

This project is a **Machine Learning-based Book Recommendation System** that suggests books based on user preferences using **Collaborative Filtering** and **Cosine Similarity**.

It includes:

* Data preprocessing
* Model training
* Recommendation engine
* Interactive web interface using Streamlit

---

## 🚀 Features

* 📖 Recommend top 5 similar books
* 🤖 Uses collaborative filtering
* 📊 Works on large real-world dataset
* 🌐 Interactive UI using Streamlit

---

## 🧠 Machine Learning Approach

* Collaborative Filtering based on user ratings
* Cosine Similarity for measuring similarity
* Data filtering:

  * Active users (>200 ratings)
  * Popular books (>50 ratings)

---

## 🗂️ Project Structure

```
Book-Recommendation/
│
├── train.py
├── app.py
├── requirements.txt
├── README.md
├── Books.csv
├── Ratings.csv
├── Users.csv
```

---

## 📊 Dataset

Dataset used: **Book-Crossing Dataset**

---

# ⚙️ Installation & Setup (Mac / VS Code)

## 🔹 Step 1: Clone Repository

```
git clone https://github.com/PRIMODIALNYXAlpha/Book-Recommendation.git
cd Book-Recommendation
```

---

## 🔹 Step 2: Install Dependencies

```
pip3 install -r requirements.txt
```

---

# ▶️ How to Run (STEP-BY-STEP)

## 🔹 Step 1: Make sure dataset is present

Place these files inside the project folder:

* Books.csv
* Ratings.csv
* Users.csv

---

## 🔹 Step 2: Train the Model

Run this in terminal:

```
python3 train.py
```

✅ This will generate:

* pivot.pkl
* similarity.pkl

---

## 🔹 Step 3: Run the Streamlit App

```
streamlit run app.py
```

If it doesn’t work:

```
python3 -m streamlit run app.py
```

---

## 🔹 Step 4: Open in Browser

* It will automatically open
* If not, go to:

```
http://localhost:8501
```

---

## 🎯 Output

* Select a book
* Click “Recommend”
* Get top 5 similar books

---

## 🖥️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit

---

## 🔥 Future Improvements

* Add book cover images
* Search functionality
* Deploy online
* Improve UI

---

## 🧠 Key Learnings

* Recommendation systems
* Data preprocessing
* Cosine similarity
* Streamlit app development

---

## 👨‍💻 Author

**Tarun SR**

---

## ⭐ Conclusion

This project demonstrates how machine learning can be used to build intelligent recommendation systems using real-world data.

---

⭐ *Star this repo if you like it!*
