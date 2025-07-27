# -Antimatter-vs-Matter-Classification-using-Physics-Inspired-Features-and-Ensemble-Learning
This project presents a high-accuracy machine learning pipeline for classifying matter and antimatter particles using synthetic physics data. It simulates realistic particle properties such as momentum, pseudorapidity, invariant mass, and decay behavior, and utilizes an ensemble of XGBoost, Deep Neural Networks (DNN), and k-Nearest Neighbors (kNN) for classification.

⸻

🧠 Key Highlights
	•	📊 Physics-derived Feature Engineering
Includes domain-specific features like total momentum, β (velocity), γ (Lorentz factor), invariant mass, angular separation (ΔR), and particle ID heuristics.
	•	🤖 Ensemble of State-of-the-Art Models
Combines XGBoost, DNN, and kNN using soft voting and a weighted ensemble for peak performance.
	•	🎯 Target Accuracy Achieved: >99%
Final weighted ensemble reaches 99.34% accuracy on 5,000 unseen test samples.
	•	📈 Explainable AI Ready
Framework supports SHAP for interpretability and physics validation of model predictions.


📁 antimatter-classifier/
├── antimatter_classifier.py      # Main code (complete model pipeline)
├── requirements.txt              # Required packages
├── README.md                     # This file
└── results/
    ├── roc_curve.png
    ├── shap_summary.png
    └── predictions.csv

Minimal requirements:
numpy
pandas
scikit-learn
xgboost
matplotlib
tensorflow
shap



This will:
	•	Generate synthetic matter and antimatter particle data
	•	Compute physics-inspired features
	•	Train XGBoost, DNN, and kNN models
	•	Perform ensemble learning
	•	Output the accuracy and best-performing model
	•	Save predictions and plots in the results/ folder



 🔍 Use Cases
	•	Particle physics simulations and collider data analysis
	•	CERN-like educational projects
	•	Model interpretability in high-energy physics using SHAP
	•	Benchmarking classification pipelines for scientific ML



📚 Literature & Citations
	1.	Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep Learning. MIT Press.
	2.	Lundberg, S. M., & Lee, S. I. (2017). A unified approach to interpreting model predictions. NeurIPS.
	3.	Chen, T., & Guestrin, C. (2016). XGBoost: A scalable tree boosting system. KDD.
	4.	CERN Open Data Portal: https://opendata.cern.ch
	5.	De Oliveira, L., et al. (2016). Jet-images—deep learning edition. JHEP, 2016(7), 69.
	6.	Bhat, P. C. (2011). Multivariate Analysis Methods in Particle Physics. Ann. Rev. Nucl. Part. Sci., 61:281-309.
	7.	Guest, D., Cranmer, K., & Whiteson, D. (2018). Deep learning and its application to LHC physics. Annual Review of Nuclear and Particle Science, 68, 161–181.



 Atharva Anup Wasnik
 ML Researcher | Physics Enthusiast
