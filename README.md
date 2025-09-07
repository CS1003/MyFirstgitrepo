**EPX/USD Price Prediction using GRU: Deep Learning Approach to Cryptocurrency Forecasting**

This project focuses on predicting EPX/USD cryptocurrency price movements using advanced deep learning techniques and financial indicators. The goal is to design a reliable predictive model that can help in analyzing potential price trends with high accuracy.

**🔑 Key Features**

Cryptocurrency Pair: EPX/USD

Model Used: Gated Recurrent Unit (GRU)

GRUs are chosen over traditional RNNs and LSTMs for their efficiency, ability to handle sequential dependencies, and faster training times.

Data Processing: Sliding window approach for time-series forecasting.

**Technical Indicators:**

Support levels

Resistance levels

Support distance

Resistance distance

**Evaluation Metrics:**

Mean Absolute Percentage Error (MAPE)

Root Mean Squared Error (RMSE)

Mean Absolute Error (MAE)

Accuracy (based on MAPE)

**🧠 Why GRU?**

GRUs are well-suited for time-series forecasting because they effectively capture long-term dependencies while being less computationally intensive than LSTMs. This makes them a strong choice for cryptocurrency price prediction where both speed and accuracy matter.

**📊 Methodology**

Data Collection & Preprocessing

Price data of EPX/USD is studied and scaled.

Sliding window technique applied for sequence modeling.

**Feature Engineering**

Computation of support and resistance levels.

Calculation of distances from support and resistance zones.

**Modeling**

GRU-based recurrent neural network is trained on sequential data.

**Evaluation**

Performance measured using MAPE, RMSE, and MAE.

Accuracy derived from MAPE values.

**📈 Results**

The GRU model achieved competitive performance with low error rates (MAPE, RMSE, MAE).

Accuracy was computed using MAPE, ensuring a meaningful interpretation of model reliability in real-world scenarios.

**🚀 Future Work**

Testing additional models such as LSTMs and Transformers.

Incorporating more advanced technical indicators.

Extending predictions to multi-step forecasting.

**🤝 Contributions**

Contributions, suggestions, and improvements are welcome!

**📬 Contact**

If you’d like to connect or collaborate, feel free to reach out via LinkedIn
 or open an issue in this repository.
