# Asl-Flutter-App
ASL Flutter App is a real-time ASL recognition system using Flutter, MediaPipe, and a TensorFlow Conv1D model. It extracts 21 hand landmarks (63 features), sends them to a Python backend, and predicts letters using a trained CNN model. It smooths outputs, forms text with space/delete gestures, and can speak results via flutter_tts.
