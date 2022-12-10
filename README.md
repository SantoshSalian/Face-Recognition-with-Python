## Face Recognition with Python API
#### Installation
First, clone or download this GitHub repository. Install required packages from requirements.txt

```
Predictive modeling using the k-nearest-neighbors (KNN) algorithm for face recognition.

When should I use this example?
This example is useful when you wish to recognize a large set of known people,
and make a prediction for an unknown person in a feasible computation time.

Algorithm Description:
The knn classifier is first trained on a set of labeled (known) faces and can then predict the person
in an unknown image by finding the k most similar faces (images with closet face-features under eucledian distance)
in its training set, and performing a majority vote (possibly weighted) on their label.

For example, if k=3, and the three closest face images to the given image in the training set are one image of Biden
and two images of Obama, The result would be 'Obama'.
* This implementation uses a weighted vote, such that the votes of closer-neighbors are weighted more heavily.
```

#### Quick Start
```
 setup and execute faceRec_api.py
 go to localhost "http://127.0.0.1:5001/"
 upload image from 'img' for testing
```


