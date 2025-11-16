NEUROXAI is a project built to identify stroke patterns from MRI brain scans and clearly show why the model makes a particular prediction. Instead of just giving a “stroke / no-stroke” output, the system highlights the exact areas in the image that influenced the decision. This makes the results easier to understand and more reliable for practical use.
Problem Statement:In many medical imaging systems, models give predictions without showing how they reached that conclusion. This lack of clarity becomes a problem in stroke diagnosis, where understanding the reasoning is just as important as the result. Doctors need transparency, not just accuracy.
It uses two techniques—Saliency Maps and Integrated Gradients—to highlight the important regions in the MRI scan. These visual cues help users understand what the model focused on while making a decision.
Tech Stack:
-Python
-TensorFlow / Keras
-NumPy
-OpenCV
-Matplotlib
-Google Colab
