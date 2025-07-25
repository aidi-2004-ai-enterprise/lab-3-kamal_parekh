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
  https://teams.microsoft.com/l/meetingrecap?driveId=b%21cTviwgf_ukmGwhIfHfE80lUBfI-gIt5CuUsf5PtIBeIr3ctvtR50R7XMaoNvU1hR&driveItemId=01DPU3463CWUSWGIZZ3FCZKD76MQM3E7MX&sitePath=https%3A%2F%2Fdconline-my.sharepoint.com%2F%3Av%3A%2Fg%2Fpersonal%2Fkamalashwinbhai_parekh_dcmail_ca%2FEWK1JWMjOdlFlQ_-ZBmyfZcBAgOdmvvJdiYKQ0IVwIjxeg&fileUrl=https%3A%2F%2Fdconline-my.sharepoint.com%2Fpersonal%2Fkamalashwinbhai_parekh_dcmail_ca%2FDocuments%2FRecordings%2FMeeting%2520with%2520Kamal%2520ashwinbhai%2520Parekh-20250724_183448-Meeting%2520Recording.mp4%3Fweb%3D1&threadId=19%3Ameeting_ZmZjYmM5NmQtYTY3Yi00NDYzLTk3OWYtZWYwZTJjZTc2YmI4%40thread.v2&organizerId=50ef077b-377e-4211-b008-cbb849ef4db3&tenantId=49bba7a4-424b-4070-a70e-886e9dd7caef&callId=4f4f81db-16a7-43ea-b358-5acbffb866e5&threadType=Meeting&meetingType=MeetNow&subType=RecapSharingLink_RecapCore
