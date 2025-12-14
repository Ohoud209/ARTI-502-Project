# ARTI-502-Project
Proactive Stress Forecasting from Multi-Sensor Wearable Data Using Attention-Based Deep Learning.

This project is aimed at proactive predicting stress based on wearing multimodal sensor content. Contrary to traditional methods of stress detection, which label stress on-the-fly, in this work, the task is redefined as a short-time-forecasting problem, implying the prediction of the stress events several minutes before they occur. The research applies physiological measurements on the wrist in WESAD data, i.e. accelerator, blood volume pulse (BVP), electrodermal activity (EDA), and skin temperature.

Two standard baseline architectures (LSTM and CNN) are used in the modeling pipeline and a proposed hybrid CNN-BiLSTM-Attention model. Convolutional layers capture local temporal information, recurrent layers capture sequential networks, and an attention mechanism identifies the most informative time intervals to predict. Forecasting horizons of 0, 60, 120 and 180 seconds are also evaluated via the project in order to determine the model capacity in predicting the occurrence of stress.

The accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices, and attention visualizations are used in evaluating performance. The findings confirm the high detection rates and high performance of the proposed hybrid model in predicting the short-term future stress, which makes it potentially applicable to proactive stress monitoring.
