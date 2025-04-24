# 🧠 Team Member Recommendation System

A smart, interactive **Team Member Recommendation System** that helps project managers find the most suitable team members for new projects based on **skills**, **past project experience**, and **semantic relevance**. Built with `Streamlit` and powered by `SentenceTransformer` for contextual matching.

---

## 🚀 Features

- 🔍 **Semantic Matching** using `SentenceTransformer` (`all-MiniLM-L6-v2`)
- 📊 **Streamlit Dashboard** for interactive team recommendations
- 📁 **Synthetic Dataset** for demo purposes (easy to extend)
- ✅ Cosine similarity-based ranking
- 🔧 Easy to plug into real-world HR/project management systems

---

## 🧠 How It Works

1. Team members have **skills** and **project history**.
2. A new project is described with **required skills** and a **brief description**.
3. The system uses SentenceTransformers to embed these into vectors.
4. **Cosine similarity** measures how closely each team member matches the project.
5. Results are **ranked and displayed** in an interactive Streamlit app.

---

## 📦 Installation

1. **Clone the Repository**:
```bash
git clone https://github.com/your-username/team-member-recommendation.git
cd team-member-recommendation

    Install Required Libraries:

pip install -r requirements.txt

    Run the App:

streamlit run team_recommender_app_embeddings.py

📁 File Structure

.
├── team_recommender_app_embeddings.py  # Main Streamlit app
├── README.md
├── requirements.txt

🛠 Requirements

    Python 3.8+

    streamlit

    pandas

    sentence-transformers

    scikit-learn

📈 Sample Output

🤖 Future Enhancements

    Add filters: experience, location, availability

    Role-based recommendations (e.g., ML engineer, DevOps)

    Real-time integration with HR/project management systems

    Visualizations: radar charts, network graphs

👨‍💻 Author

[Your Name]
Data Scientist | Geospatial Analyst | ML Engineer
LinkedIn • GitHub
📄 License

MIT License. Feel free to use and modify for commercial or educational purposes.


---

Let me know if you'd like this README tailored with your actual name, GitHub, or LinkedIn links—or if you'd like a version with **demo screenshots** and **deployment steps** for platforms like **Streamlit Cloud** or **Render**.

