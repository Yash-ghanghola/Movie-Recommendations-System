# 🎬 Movie Recommendation System

A smart movie recommendation web app built with **Python**, **Streamlit**, and **TMDB API**. It recommends top 5 similar movies based on your selection and displays their posters in real-time.

---

## 🚀 Features

- ✅ Recommends 5 similar movies using a pre-trained similarity model
- 🖼️ Fetches movie posters via **TMDB API**
- 🧠 Uses **cosine similarity** on movie vectors
- ⚡ Fast and responsive UI with **Streamlit**
- 🔁 Real-time interaction, clean layout

---

## 🔧 Tech Stack

- **Python 3**
- **pandas**, **scikit-learn**, **pickle**
- **Streamlit** (for web UI)
- **requests** (for API calls)
- **TMDB API** (for movie poster images)
- Developed using **PyCharm** & tested in **Jupyter Notebook**

---

## 📁 Project Structure

```bash
├── app.py                     # Main Streamlit app
├── Movies_dict.pkl            # Pickled dictionary of movie data
├── similarity.pkl             # Pickled similarity matrix
├── README.md                  # You're here!
