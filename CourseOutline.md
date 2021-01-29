# CourseOutline

## Deep Learning Object Detection With Video

## Chapter 1 - Introduction to Face Detection with OpenCV

### **Lesson 1.1 - Laying the groundwork for detecting faces with deep learning**

- Learner will be able to: Create a command-line interface to allow for the import of a deep learning model and image for face detection.
- Some functions introduced/used: `argparse.ArgumentParser()`, `cv2.dnn.readNetFromCaffe()`.

### **Lesson 1.2 - Preparing an image for face detection**

- Learner will be able to: Prepare an input blob for face detection with a static image using OpenCV.
- Some functions introduced/used `cv2.imread()` , `cv2.dnn.blobFromImage().`

### **Lesson 1.3 - Doing face detection on an image**

- Learner will be able to: Write a loop that calculates predictions above a defined confidence level and draws an image overlay over the detection.
- Some functions introduced/used: `cv2.retangle()` , `cv2.imshow()`.

## Chapter 2 - Detecting Faces in Video

### **Lesson 2.1 -  Preparing a video for face detection**

- Learner will be able to: Prepare a video file or webcam feed for use in facial object detection
- Some functions introduced/used: `FileVideoStream()` , `imshow()`.

### **Lesson 2.2 - Looping over the frames in the video**

- Learner will be able to: Use a loop to grab frames from the video.
- Some functions introduced/used: `read()` , `blobFromImage()` .

### **Lesson 2.3 - Running the facial recognition on a video**

- Learner will be able to: Write a loop that calculates predictions above a defined confidence level and draws an image overlay on the video.
- Some functions introduced/used: `cv2.retangle()` , `cv2.imshow()`.

## Chapter 3 - Adding a New Model for Object Detection

### **Lesson 3.1 - Object detection vs Object classification**

- Learner will be able to: Distinguish between the concepts of classification and detection for video
- Some concepts introduced: bounding box list, class labels

### **Lesson 3.2 - Importing a trained model for detecting objects**

- Learner will be able to: Create a command-line interface to allow for the import of a deep learning model for object detection.
- Some functions introduced/used: `add_argument()`

### **Lesson 3.3 - Listing the objects to be detected**

- Learner will be able to: Reproduce the list of objects the model was trained on.
- Some concepts introduced: `Classes` list containing a list of objects.

## Chapter 4 - Detecting Objects in Video

### **Lesson 4.1 - Define different colors to identify each of the objects from `Classes` list**

- Learner will be able to: Create labels of differing colors to use to on the bounding boxes identifying the objects.
- Some functions introduced/used: `np.random.uniform()`

### **Lesson 4.2 - Loop over the video frames and adding differently colored bounding boxes around objects**

- Learner will be able to: Construct a loop that attaches a colored bounding box to detections over a defined confidence level.
- Some functions introduced/used: `cv2.rectangle()`

### **Lesson 4.3 - Ignoring objects from the trained model**

- Learner will be able to: Modify the detection to loop to ignore certain objects from the model.
- Some concepts introduced/used: A `set` containing values to ignore
