# American-Sign-Language-Detection
## American Sign Language Detection and Translation Sign to Text
## Winner of Hack for Humanity | 2025 (https://devpost.com/software/american-sign-language-detection-8h3eo2?ref_content=my-projects-tab&ref_feature=my_projects)
 https://devpost.com/software/american-sign-language-detection-8h3eo2?ref_content=my-projects-tab&ref_feature=my_projects
Small project I worked on with the intention of expanding it to a fully developed application.
This project is based on the video by Computer Vision Engineer, I highly suggest everyone to watch the video at least once to get a simple and clear understanding of the code.

[![Watch the video](https://img.youtube.com/vi/MJCSjXepaAM/maxresdefault.jpg)](https://youtu.be/MJCSjXepaAM)

### ⚠️NOTE: Two models and pickle files have been given, model.p and data.pickle have been trained by a small dataset of 30mb which includes numbers while the model2.p and data2.pickle have been trained using a large dataset of 1gb+ which includes special signs like delete, nothing and space.

<h1>⭐TLDR:</h1>

* The data gets loaded and the landmarks of the hand symbol are stored in a picke file
* The model is trained using 80% of the pickle file and tested with the remaining 20%
* The main function occurs in inference_classifier.py where you map the alphanumerics with a number for the model to classify.


<h2>💻 Built with:</h2>

Technologies used in the project:

*   Pickle.py
*   MediaPipe
*   cv2
*   sklearn
*   numpy
*   Dataset used from Kaggle
