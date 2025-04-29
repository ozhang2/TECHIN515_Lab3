# TECHIN515 Lab 3: ESP32 Sorting Hat

## Discussion
1. Play with your sorting hat. Are all 10 questions important to create the sorting hat? If you were to remove some questions to improve user experience, which questions would you remove and justify your answer.
- Not all 10 are needed. I would drop Q6 (mystery book) and Q7 (pet choice). These two don’t help sorting much and speed up the quiz.

2. If you were to improve the sorting hat, what technical improvements would you make?
- Model Improvements
  - Tune tree depth or min samples to make it faster and more stable. Or use a random forest instead of one tree for better accuracy.
- Hardware Upgrades
  - Add a heart-rate sensor to track stress.
  - Add an accelerometer to measure button press speed.
- Algorithm Choice
  - For just quiz data, a decision tree is simple and fast. With heart-rate or motion data, use random forest because it handles mixed data and is more accurate.
