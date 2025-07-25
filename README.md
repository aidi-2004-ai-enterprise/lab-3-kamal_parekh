# lab-3-kamal_parekh

A simple machine learning API built with **FastAPI** that predicts the species of a penguin based on physical measurements. The prediction is powered by an XGBoost classifier, and all key events are logged using Python’s built-in `logging` module.


- Predicts penguin species (`Adelie`, `Chinstrap`, or `Gentoo`) from bill and body metrics
- Cleanly structured input validation using `Pydantic` models and `Enum` classes
- One-hot encoding of categorical variables (`sex` and `island`)
- Robust logging of:
  - API startup
  - Model loading
  - Incoming prediction requests
  - Prediction results and failures
 video: 
  https://dconline-my.sharepoint.com/:v:/r/personal/kamalashwinbhai_parekh_dcmail_ca/Documents/Recordings/Meeting%20with%20Kamal%20ashwinbhai%20Parekh-20250724_183448-Meeting%20Recording.mp4?csf=1&web=1&e=GGbvXj&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
