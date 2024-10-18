Coffee Type Recommendation Model
Overview
- This project is a machine learning-based web app that recommends a coffee type based on user preferences. The app uses a pre-trained model to predict the ideal coffee type by taking various user inputs such as time of day, coffee strength, sweetness level, and more. The app is built using Python and Gradio to create an interactive user interface.

Features
- **User Inputs**: Users can select their preferences for time of day, coffee strength, sweetness level, milk type, coffee temperature, flavored coffee, caffeine tolerance, coffee bean, coffee size, and dietary preferences.
- **Machine Learning**: The app uses a pre-trained model (stored in best_model.pkl) to predict the ideal coffee type based on user input.
- **Label Encoding**: Predictions are decoded to return user-friendly coffee types using a pre-trained label encoder (stored in label_encoder.pkl).
- **Gradio Interface**: The app features an easy-to-use interface with dropdown menus for user input and a textbox displaying the recommended coffee type.
