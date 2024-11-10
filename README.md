# ForecastLogic
The primary objective is to create a demand forecasting system that predicts inventory needs and recommends order quantities based on historical product demand. This model will serve as a decision-making tool, helping reduce inventory costs and prevent stockouts by providing insights into future demand patterns.


Project Proposal Outline
1) Team Members and Experience
      Edna Salazar – Demand Planner with experience in inventory management, data analysis, and logistics. Skills include time series forecasting and Material Requirements Planning (MRP).

3) Main Idea/Goal
      Goal: The primary objective is to create a demand forecasting system that predicts inventory needs and recommends order quantities based on historical product demand. This model will serve as a decision-making tool, helping reduce inventory costs and prevent stockouts by providing insights into future demand patterns.

      Techniques Considered: Begin with ARIMA for foundational time series forecasting and later extend to LSTM models if possible. The focus is on how these models contribute to data-driven decision-making in inventory management.

      Learning Goals: Understand the practical application of time series models in forecasting, evaluate model accuracy, and optimize the decision-making process for inventory management.

5) Resources Needed

   •	Learning Resources: study materials on ARIMA and LSTM models, time series forecasting chapters, and documentation for Python libraries (statsmodels for ARIMA and TensorFlow for LSTM). Relevant research papers include: 

   o	Demand Forecasting for Irregular Demands in Business Aircraft Spare Parts Supply Chains by using Artificial Intelligence (AI). Demand Forecasting for Irregular Demands in Business Aircraft Spare Parts Supply Chains by using Artificial Intelligence (AI) - ScienceDirect.

   o	Utilizing machine learning to enhance optimal inventory management : case : aviation industry spart parts. Utilizing machine learning to enhance optimal inventory management : case : aviation industry spart parts - LUTPub.

   o	An Adaptive Time Series Forecasting Model for Aircraft Component Supply Chain Demand Prediction. demand forecasting aerospace industry using machine learning - Google Scholar.


   •	Code Resources: Python, using libraries like statsmodels for ARIMA and TensorFlow/Keras for LSTM implementation.

   •	Data Resources: Historical demand data (from my current forecasts files), with daily or weekly frequency to align with typical inventory cycles.

   •	Computational Resources: Local systems should be sufficient for ARIMA, with optional cloud-based resources (e.g., Google Colab, Google Scholar).

7) Anticipated Deliverables


   •	Interim Submission: Implementation of the ARIMA model with preliminary results on accuracy, demand predictions, and order quantity suggestions.

   •	Final Submission: Refined ARIMA results, a trained LSTM model (if feasible), a comparative report on model performance, and an analysis on forecast accuracy and its impact on inventory decisions.

  Testing and Evaluation Plan: Measure the forecasting accuracy using metrics like Mean Absolute Error (MAE) or Mean Squared Error (MSE). Additionally, I will compare the model order quantities with actual demand to determine its practical decision-support value.

7) Task Breakdown and Timeline

    •	Key Deliverables

    •	Core Deliverable: A working ARIMA model for demand forecasting, including evaluation and analysis of forecast accuracy.

    •	Optional Deliverable: An initial LSTM model if time allows, focusing on testing its baseline performance for comparison.

    •	Timeline and Task Breakdown:

  Week 1: Data Collection and Preprocessing
      
      Collect and preprocess the historical demand data.
      
      Perform data exploration and check for seasonality, trends, and any data anomalies.
      
      Prepare data in a time series format suitable for ARIMA modeling.
      
      Goal: Complete a cleaned and well-structured dataset.
      
  Week 2: ARIMA Model Implementation
      
      Research ARIMA model parameters (p, d, q) and apply a parameter selection strategy, such as grid search or auto-ARIMA.
      
      Train and tune the ARIMA model on the prepared dataset.
      
      Goal: A preliminary ARIMA model with baseline forecasts.

  Week 3: Evaluation and Refinement
      
      Evaluate the ARIMA model’s forecasting accuracy using MAE or MSE.
      
      Fine-tune ARIMA parameters based on evaluation metrics to improve performance.
      
      Goal: Finalized ARIMA model with documented performance results and forecasting accuracy.

  Week 4: Decision-Making Analysis and Reporting
      
      Translate the ARIMA model’s forecast output into actionable insights for order quantity decisions.
      
      Develop a decision-making framework, suggesting how forecast results impact order quantities.
      
      Prepare interim results and a short report on ARIMA performance and decision insights.
      
      Goal: Clear analysis and initial report showing ARIMA model’s demand forecasting impact on inventory planning.

  Week 5: Optional LSTM Model and Finalization
      
      Primary Task: Complete final documentation, detailing model performance and decision-support impact.
      
      Optional Task (time permitting): Implement a basic LSTM model to compare against ARIMA. This could be a preliminary LSTM model to test feasibility and initial accuracy.
      
      Goal: Submit the final project with completed ARIMA model, analysis, and optional LSTM findings if achievable.
