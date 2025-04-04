# Climate-classification-for-chatbot
Classified seasonal weather patterns of 1000+ locations using fuzzy c-means and other soft clustering methods. Processed raw data to extract daily stats, binned temperature/humidity, calculated HDH/CDH, and summarized cluster properties. Useful for urban planning and energy modeling. 

Weather Pattern Classification – Hyderabad & 1000+ Locations

This project focuses on classifying seasonal weather patterns using unsupervised machine learning. I worked with weather data from Hyderabad and over 1000 locations across India to find hidden patterns in climate using clustering methods.

As part of this, I also started working on a research paper based on my findings and the analysis I did.



What I Did:
	•	Cleaned and processed large weather datasets
	•	Calculated daily stats like:
	•	Min & max temperature
	•	Mean humidity
	•	Solar radiation
	•	Binned temperature and humidity into comfort levels
	•	Detected day and night based on radiation values
	•	Calculated Heating Degree Hours (HDH) and Cooling Degree Hours (CDH)
	•	Grouped locations with similar seasonal behavior using different clustering techniques
	•	Summarized each cluster by temperature bin counts and average wind speed
	•	Skipped complex stats like covariance to keep things efficient



Algorithms Used

I applied and compared multiple clustering methods:
	•	Fuzzy C-Means
	•	K-Means
	•	DBSCAN
	•	HDBSCAN
	•	Also tried Random Forest to check results




Why This Project

I wanted to explore how unsupervised learning can help understand weather and climate without using any labeled data. This kind of work can help in urban planning, energy modeling, and even future climate research.



Tools & Libraries
	•	Python
	•	Pandas, NumPy
	•	scikit-learn, fcmeans
	•	Matplotlib, Seaborn
