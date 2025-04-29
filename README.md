# TECHIN515 Lab 3: ESP32 Sorting Hat

## Discussion

- Not all 10 are needed. I would drop Q6 (mystery book) and Q7 (pet choice). These two don’t help sorting much and speed up the quiz.

- Model Improvements
  - Tune tree depth or min samples to make it faster and more stable. Or use a random forest instead of one tree for better accuracy.
- Hardware Upgrades
  - Add a heart-rate sensor to track stress.
  - Add an accelerometer to measure button press speed.
- Algorithm Choice
  - For just quiz data, a decision tree is simple and fast. With heart-rate or motion data, use random forest because it handles mixed data and is more accurate.
