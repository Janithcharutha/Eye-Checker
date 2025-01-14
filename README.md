#Eye Checker App 👁️

A Flutter application powered by TensorFlow Lite that detects and identifies potential eye problems using image classification.

Features ✨
    -📷 Image Capture: Take a photo directly from your device's camera for analysis.

    -🖼️ Gallery Selection: Pick an existing image from your gallery to identify potential issues.

    -🤖 AI-Powered Analysis: Leverages TensorFlow Lite for accurate and fast eye problem detection.

    -📊 Confidence Scores: Displays the model's confidence level for the detected condition.

    -🌟 User-Friendly Interface: Intuitive UI for smooth user experience.

##How It Works 🛠️

Model Integration

The app uses a pre-trained TensorFlow Lite model (model_unquant.tflite) and associated labels (labels.txt) for eye problem identification.

Image Processing:

    -Captures or selects an image.
    -Runs the image through the TensorFlow Lite model for classification.
    -Displays the detected label and confidence score.

Results:
    -Shows the identified condition with an accuracy percentage.
 
 
