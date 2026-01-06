Research-Practicum

Innovative Use of Behavioural Data and Explainable AI for Early Gambling Addiction Detection


Project Overview
This project investigates the early detection of gambling addiction by analysing player behavioural data collected from online gambling platforms. The study combines unsupervised clustering with deep learning–based time-series forecasting to identify high-risk gambling patterns and predict behavioural escalation over time. The work is motivated by the need for data-driven responsible gambling interventions that operate continuously and at scale.


Objectives
- To segment gambling users into behavioural risk groups using clustering techniques
- To model temporal gambling behaviour using sequential deep learning models
- To forecast future betting behaviour for high-risk users
- To evaluate model accuracy, efficiency, and real-time suitability
- To provide interpretability of predictions using explainable AI techniques


Methodology Summary
1. Data Preprocessing  
Raw transactional and behavioural data are cleaned, encoded, scaled, and transformed into time-series format using rolling windows.

2. Behavioural Segmentation  
K-Means clustering is applied to identify distinct gambling behaviour profiles. Forecasting models are trained only on the high-risk cluster to enable focused prediction and reduce computational cost.

3. Time-Series Forecasting  
Multiple deep learning models are implemented and compared, including:
- LSTM
- GRU
- BiLSTM
- BiLSTM with Cross-Attention

4. Model Evaluation  
Performance is assessed using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE). System-level metrics such as latency and throughput are also measured to assess real-time feasibility.

5. Explainability  
Local Interpretable Model-agnostic Explanations (LIME) are used to explain individual predictions and identify influential behavioural features.


Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
- LIME


Repository Structure
- README.txt – Project overview and documentation
- Notebooks / scripts – Data processing, modelling, and evaluation code
- Configuration files – Environment and dependency setup
- Supporting outputs – Plots, metrics, and model results


Results Summary
The BiLSTM with Cross-Attention achieved the lowest forecasting error and demonstrated improved sensitivity to behavioural spikes associated with gambling risk. The combined clustering–forecasting approach supports early identification of escalating gambling behaviour while maintaining interpretability and operational efficiency.


Ethical Considerations
This project uses anonymised behavioural data and focuses on harm prevention and responsible gambling. No personally identifiable information is used.




