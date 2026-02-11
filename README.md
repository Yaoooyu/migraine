## 🧪 Experimental Results

### Model Performance
Our analysis shows that the **AutoGluon Ensemble** model achieved the highest predictive accuracy. By stacking multiple base learners, the model effectively captured non-linear patterns in migraine symptoms compared to traditional baselines.
<p align="center">
  <img src="e6a6f6517f458aa07161847b40f286a2.png" alt="A-Mel" height="400px">
</p>
<p align="center">
  <b>Fig. 1.</b> Whole structure for A-Mel<br>
</p>
- **Top Performer:** AutoGluon (Accuracy: **0.798558**, AUC: **0.711631**)




---

### Feature Importance
Using SHAP interpretability analysis
<p align="center">
  <img src="shap_beeswarm_plot.png" alt="A-Mel" height="400px">
</p>
<p align="center">
  <b>Fig. 1.</b> Whole structure for A-Mel<br>
</p>
- **Key Features:** PIR, BMI.



