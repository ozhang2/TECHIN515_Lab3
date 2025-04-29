# TECHIN515 Lab 3: ESP32 Sorting Hat

## Discussion
1. Play with your sorting hat. Are all 10 questions important to create the sorting hat? If you were to remove some questions to improve user experience, which questions would you remove and justify your answer.
- Not all ten questions are essential for sorting. I would drop question 6 (mystery book) and question 7 (pet choice) because they contribute little useful information to the decision. Those topics tend to introduce noise without improving the house prediction. Removing them makes the quiz faster and keeps the results just as reliable.

2. If you were to improve the sorting hat, what technical improvements would you make?
- Model Improvements
  - I would tune the tree’s max depth and minimum leaf samples to avoid overfitting and speed up inference. I’d also apply pruning or quantization to shrink the model and reduce memory use.
- Hardware Upgrades
  - Adding a heart-rate sensor captures stress levels and an accelerometer tracks how quickly users press buttons. These extra signals provide behavioral context that can enhance the sorting accuracy.
- Algorithm Choice
  - A decision tree still handles mixed quiz and sensor data well and offers fast, explainable predictions on low-power devices. If I needed better accuracy with more complex feature interactions, I’d switch to a small random forest for its improved stability while keeping resource needs moderate.
