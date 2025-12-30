# RNN Sequence Prediction Assignment

## 1. Project Overview
This assignment focuses on the practical application of **Recurrent Neural Networks (RNNs)** to time-series forecasting. The goal is to build a model that can learn temporal dependencies in a sequence and predict future values accurately.

## 2. Technical Requirements
- **Language**: Python 3.x
- **Core Library**: Keras / TensorFlow
- **Layer Requirement**: Use only `SimpleRNN` for the recurrent component.
- **Dataset**: A simple numeric sequence (e.g., Sine Wave, Fibonacci, or custom time-series).

## 3. Implementation Workflow
1.  **Data Preparation**: Generate or load a sequential dataset.
2.  **Preprocessing**: Use a sliding window approach to format data into (samples, time_steps, features).
3.  **Model Build**: Construct a Sequential model using `SimpleRNN`.
4.  **Training**: Optimize using MSE loss and monitor convergence.
5.  **Validation**: Test the model on unseen data and visualize the predictions.

## 4. Evaluation Criteria
- Successful implementation of the `SimpleRNN` architecture.
- Clear visualization of the predicted vs. actual values.
- Documentation of the training process and results.

## 5. Submission Checklist
- [ ] Completed Jupyter Notebook (`.ipynb`).
- [ ] Technical explanations for each phase of implementation.
- [ ] (Optional) Professional research report in LaTeX/PDF format.