# JAMB-performance-prediction-analysis
## Investigating the Causes of JAMB Failure Rates and Predicting Future Performance Trends (2020–2030)  
### 📊 Project Overview  
Over the past five years, the JAMB examination — Nigeria's standardized university entrance exam — has shown a noticeable trend in fluctuating failure rates. This project aims to explore the root causes behind this trend using data-driven research and build a predictive model to forecast performance trends from 2026 to 2030.  
______________
### 🎯 Objectives  
•	Collect and analyze data from students who sat for the JAMB exam between 2020 and 2025.  
•	Identify socio-economic, academic, and behavioral factors affecting performance.  
•	Build a machine learning model to predict pass/fail outcomes.  
•	Forecast national pass/fail rates up to 2030.  
•	Recommend actionable strategies to reduce failure rates.  
______________
### 🧰 Tools & Technologies  
•	Programming Language: Python  
•	Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
•	Survey Tool: Google Forms  
•	Visualization Tool: Jupyter Notebook  
•	Version Control: Git & GitHub  

______________
### 🔗 Useful Links for Reference
•	Cleaned Jamb Data: <a href="/JAMB project/cleaned_jamb_data.csv">Link (csv)</a><br/>
•	Comprehensive Report: <a href="/JAMB project/Comprehensive report.pdf">Link (pdf)</a><br/>
•	Jamb Exam Experience Survey (2020 - 2025): <a href="/JAMB project/JAMB Exam Experience Survey (2020–2025)  (Responses) - Form responses 1.csv">Link</a><br/>
•	Jamb Project Documentation: <a href="/JAMB project/Jamb Project Documentation.docx">Link (docx)</a><br/>
•	Jupyter Notebook: <a href="/JAMB project/Jamb.ipynb" style="color: 'red'; text-decoration: none">Link</a><br/>
______________
### 📋 Data Collection  
Data was collected via a structured online survey distributed to individuals who wrote the JAMB examination between 2020 and 2025. The survey captured:  
•	Demographics (age, gender, state)  
•	Educational background (school type, WAEC scores)  
•	Study behavior (daily hours, study method)  
•	Socio-economic status (parental education, internet/electricity access)  
•	Exam experience (score, attempts, perceived difficulty)  
•	Support systems (mentorship, online resources)  
______________
### KEY INSIGHTS  
**✅ 1. Pass vs. Fail Rate Distribution**  
Using a threshold score of 200 to classify exam outcomes, 78.2% of students were categorized as having passed the exam, while 21.8% fell below the benchmark and were classified as having failed.  
**Insight:** Although a large majority of respondents passed the exam, the fact that over one in five students failed indicates that a significant subset of students still struggles to meet the minimum admission criteria. This suggests a need for deeper attention toward educational inequality, study patterns, and support systems, especially among underserved student populations.  
______________
**✅ 2. Performance Trends by Year (2020–2025)**  
An analysis of yearly performance data revealed a downward trend in average JAMB scores from 2022 to 2024, alongside a steady increase in the number of failures within that same period.  
**Insight:** The dip in performance could be a delayed effect of disruptions caused by the COVID-19 pandemic, which affected the quality of learning across the country. It could also indicate challenges related to curriculum delivery, mental health, or a growing mismatch between secondary education content and JAMB exam demands. Understanding these shifts is essential for tailoring future interventions.  
______________
**✅ 3. Impact of Study Habits**  
Students who studied for at least 3 hours daily consistently outperformed those who studied for fewer hours. There was a clear positive correlation between time dedicated to study and JAMB scores.  
**Insight:** Regular, focused study routines are strongly associated with higher exam performance. This reinforces the importance of discipline, time management, and exam-specific preparation. Schools and parents should emphasize structured reading schedules and provide environments that support undistracted study time.  
______________
**✅ 4. Access to Educational Resources**  
Candidates with access to electricity and internet, especially those who used online learning platforms and practiced with past questions, recorded higher average scores.  
**Insight:** The digital divide is a key factor in academic disparity. Students with consistent access to electricity, mobile data, and learning platforms had a major advantage over those without. Digital inclusion initiatives could be vital to leveling the playing field and improving national performance outcomes.  
______________
**✅ 5. School Type and Learning Environment**  
Students from private and mission schools achieved higher pass rates compared to their peers in public and federal government schools.  
**Insight:** This suggests that school environment and quality of instruction play a significant role in student success. Private institutions may have better resources, lower teacher-to-student ratios, or more structured academic preparation, all of which contribute to better outcomes. Strengthening public education infrastructure is necessary to close this gap and ensure all students have a fair chance at success.  
______________
### 🤖 Model Building  
A Random Forest Classifier was trained on the cleaned dataset to predict pass/fail outcomes.  
**📈 Model Evaluation:**  
•	Accuracy: 100%  
•	Precision: 100%  
•	Recall: 100%  
•	F1-Score: 100%  
**Top predictive features:**  
•	Study Hours  
•	School Type  
•	Past Questions Usage  
•	Internet Access  
•	Parental Education  
______________
### 🔮 Future Forecast (2026–2030)  
Using the trained model, hypothetical student records were generated to simulate future trends. Forecasted results:  
Year	Predicted Pass Rate	Predicted Fail Rate  
2026	79.5%	20.5%  
2027	80.8%	19.2%  
2028	82.0%	18.0%  
2029	83.1%	16.9%  
2030	84.7%	15.3%  
______________
### ✅ Recommendations  
**For Students:**  
•	Set consistent daily study routines (≥2 hours).  
•	Leverage free online JAMB prep tools and past questions.  
•	Join peer study groups and tutorials.  
**For Educators:**  
•	Integrate JAMB prep into school curricula.  
•	Support struggling students early.  
•	Promote digital learning and literacy.  
**For Policymakers:**  
•	Improve access to electricity and internet in underserved areas.  
•	Subsidize essential learning materials for low-income students.  
•	Train teachers in digital and exam-specific instruction.  

### ✅ Conclusion  
This project has provided a comprehensive, data-driven investigation into the causes of rising JAMB failure rates in Nigeria and projected performance trends up to the year 2030. By analyzing survey responses from students who sat for the exam between 2020 and 2025, we identified key academic, socio-economic, and infrastructural factors that significantly influence student outcomes.  
Our findings revealed that consistent study habits, access to digital learning resources, and the type of school attended are among the most impactful predictors of success. The analysis also exposed disparities linked to digital access and socio-economic background, emphasizing that academic ability alone does not determine exam performance — opportunity, environment, and preparation matter just as much.  
The predictive model developed during this project forecasts a gradual improvement in JAMB pass rates over the next five years, assuming current trends in access and awareness continue. However, these gains will likely be uneven unless targeted interventions are made for under-resourced and vulnerable groups.  
Ultimately, improving JAMB outcomes requires a multi-stakeholder approach. Students must adopt disciplined study habits; educators must offer structured exam preparation and support; and policymakers must invest in infrastructure, digital equity, and teacher training. With these coordinated efforts, Nigeria can not only reduce JAMB failure rates but also ensure a more equitable and effective education system for future generations.  
