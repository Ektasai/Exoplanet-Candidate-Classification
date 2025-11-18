#  Exoplanet-Candidate-Classification

 Used NASA’s Kepler space telescope data to build a machine learning system that can tell whether a star’s light pattern comes from a **real planet** or a **false signal**.
 https://www.kaggle.com/datasets/nasa/kepler-exoplanet-search-results

---

##  Main Goals
- Preprocess and clean the Kepler dataset.  
- Train multiple models (Logistic Regression, Random Forest, XGBoost, Deep Learning).  
- Tune hyperparameters for better accuracy and balanced classification.  
- Use **Explainable AI** (feature importance + SHAP values) to understand predictions.  
- Compare results for **planet candidates vs false positives**.  

---

##  Results
- Achieved **~98% accuracy** with tuned Random Forest and XGBoost models.  
- Identified key features (e.g., transit depth, duration, vetting flags) strongly influencing predictions.  
- SHAP plots showed the models make **scientifically meaningful decisions**.  

---

##  Future Improvements
- Time-Series Analysis: Use Kepler light curves (flux vs. time) and apply CNNs/RNNs for direct classification from raw signals.
- Multimodal Learning: Combine tabular KOI features with light curve embeddings for improved accuracy.
- Transfer Learning: Adapt models trained on Kepler data for TESS or future missions (e.g., PLATO, JWST).
- Automated Model Deployment: Deploy as an interactive web app or API for astronomers to test KOIs in real time.


