# Indian Food Classifier

A Flask web app that classifies uploaded food photos into 20 Indian food categories using a deep learning model (EfficientNetB0).

## How it works
- User uploads an image via the web UI
- - A Keras model (models/food_classifier_model.keras) trained on 20 Indian food classes predicts the category
  - - Includes both PyTorch and TensorFlow training notebooks for the model
   
    - ## Tech stack
    - Python, TensorFlow/Keras (inference), PyTorch (alt. training), Flask, EfficientNetB0
   
    - ## Run locally
    - pip install -r requirements.txt
    - python app.py
   
    - ## Files
    - - model_training/ - training notebooks (PyTorch and TensorFlow versions)
      - - app.py - Flask inference server
        - - templates/, static/ - web UI
          - 
