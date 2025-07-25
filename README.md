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
 video: https://youtu.be/MfG0RaNTlVY
