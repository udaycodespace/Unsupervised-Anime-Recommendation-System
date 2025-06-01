# Project Title: Unsupervised Anime Recommendation System 🎯

## Objective 🔍  
Build a content-based anime recommendation engine using unsupervised learning (clustering) without relying on any user preference history.

---

## About the Project 📘  
This project was developed as part of a 4-week Internship Program organized by Edunet Foundation on AI with Azure, starting 13th May 2025. The internship provided hands-on experience with real-world AI applications.  
The system recommends anime titles based on textual features like synopsis and genre, grouped using clustering algorithms such as K-Means. 

---

## Visual Overview  📊
![Project Overview](./project_overview.png)  
*A concise image explaining the project flow and technologies used.* 🖼️

---

## How It Works 🛠️  

1. **Load Dataset**: Anime dataset with titles, genres, synopsis, and scores.  
2. **Preprocess Text**: Clean and vectorize synopses using TF-IDF.  
3. **Clustering**: Apply K-Means to cluster similar anime titles.  
4. **Recommend**: For a selected anime, recommend others from the same cluster. 🔄

---

## Example Use Case 💡  
**Input**: Recommend anime similar to _"Naruto"_  
**Output**: Returns titles with similar themes like _"Angel Beats!"_, _"Platinum End"_, etc. 🎥

---

## How to Run ▶️  

1. Open the Jupyter Notebook `Unsupervised_Anime_Recommendation_System.ipynb` in Google Colab or your local environment.
2. Run all cells sequentially:
    - Load and explore dataset
    - Preprocess and vectorize data
    - Fit K-Means model
    - Enter an anime title and get recommendations 💻

---

## Tools and Technologies Used 🧰  
- Python (Google Colab)  
- Pandas, NumPy  
- Scikit-learn (TF-IDF & KMeans)  
- Matplotlib / Seaborn *(optional for visualization)*  
- NLTK *(optional for text preprocessing)* 🧪

---

## Sample Test Cases 🧪  

```python
get_recommendations('Death Note')
get_recommendations('Naruto')
get_recommendations('Blx')  # typo test with fuzzy matching
```

---

## Future Enhancements 🔮  

- Build a web app interface (Flask or Streamlit)  
- Integrate collaborative filtering for better personalization  
- Expand dataset with user reviews and ratings  
- Add filters (e.g., genre, score range) 🚀

---

## Credits 🙌  

Project adapted from the work of [Rohit Shelar](https://github.com/therohitshelar97/MovieRecommendationUsingUnsupervisedLearning/blob/main/Movie%20Recommendation.ipynb)

Special thanks to our mentors:
- Rohit Shelar (Sir)
- Karthiga S (Mam)
- Thoquif (Sir) 🙏

Their guidance was invaluable throughout this internship.

---

## Author 📌  

**Somapuram Uday**  
4th Year Computer Science Student  
GPREC(A), Kurnool, Andhra Pradesh  
Intern at Edunet Foundation AI + Azure Virtual Internship 🎓

---

## What to Do Next ✅  

- Clone this repo  
- Run the notebook in Google Colab or your local environment  
- Feel free to improve the project and contribute  
- For suggestions or improvements, contact me! 📬
