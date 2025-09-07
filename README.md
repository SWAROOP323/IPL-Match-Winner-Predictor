# 🏏 **IPL Win Probability Predictor**  

🚀 An interactive application that predicts the **winning probability** of teams in an IPL (Indian Premier League) match using **Machine Learning**.  
Built with **Streamlit**, this app provides real-time insights into match outcomes based on live match parameters.  

---

# ✨ **Features**  

- ✅ **Win Probability Prediction** – for both batting and bowling teams.  
- ✅ **User-Friendly Interface** – built with **Streamlit**.  
- ✅ **Considers Match Parameters** like:  
  - Batting team  
  - Bowling team  
  - Host city  
  - Target score  
  - Current score  
  - Overs completed  
  - Wickets fallen  
- ✅ **Pre-trained ML Model** – trained on historical IPL match data.  

---

# 📂 **Project Structure**  

- `app.py` : Main Streamlit application.  
- `model.pkl` : Trained ML model.  
- `pipe.pkl` : Pre-processing + model pipeline.  
- `team.pkl` : Pickled list of IPL teams.  
- `city.pkl` : Pickled list of host cities.  
- `requirements.txt` : Python dependencies.  
- `IPL_Win_Prob.ipynb` : Notebook for model training & analysis.  
- `Practice.ipynb` : Experimental notebook.  
- `Data/` : Dataset used for training.  
- `render.yaml` : Deployment configuration (Render).  

---

# ▶️ **Usage**  

1. Run the application:  streamlit run app.py

3. Open your browser at 👉 http://localhost:8501

4. Select match parameters (teams, city, target, score, overs, wickets).

5. Click "Predict Probability" to view win chances 🏆.

---

# 🧠 **Model Training**  

📊 The ML model was trained using **historical IPL data**.  
The `IPL_Win_Prob.ipynb` notebook includes:  

- Data preprocessing  
- Feature engineering  
- Model selection  
- Training & evaluation  

---

# 📦 **Dependencies**  

- streamlit  
- pandas  
- numpy  
- scikit-learn  
- flask *(optional, for deployment)*  
- gunicorn *(for production use)*  

---

# 🤝 **Contributing**  

Contributions are always welcome! 🎉  

- Open issues  
- Submit pull requests  
- Suggest improvements  

---

# 📜 **License**  

This project is licensed under the **MIT License** – see the LICENSE file for details.  

---

# 📬 **Contact**  

💡 For questions, suggestions, or collaborations, reach out:  

- GitHub: https://github.com/SWAROOP323
- Email: swaroopmanchala323@gmail.com  

