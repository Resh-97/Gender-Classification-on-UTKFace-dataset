# Gender Classification on UTKFace dataset
 The objective of this project is to classify each face based  on  gender  using  CNNs  on  Tensorflow  2.x  and  then,  use OpenCV & Haar Cascade File to check the gender in real-time.

### **Dataset Description**
- **UTKFace dataset** is a large-scale face dataset with long age span (range from 0 to 116 years old).
- **Total Images**: The dataset consists of over 20,000 Face Images 
- **Dataset URL**: https://susanqq.github.io/UTKFace/
- The images cover large variation in pose, facial expression, illumination, occlusion, resolution, etc. This dataset could be used on a variety of tasks, e.g., face detection, age estimation, gender detection, age progression/regression, landmark localization, etc.

- I will be using **Aligned & Cropped Faces** Dataset from the UTKFace Dataset

### **Labels**

The labels of each face image is embedded in the file name, formated like **age_gender_race_[date&time].jpg**

    [age] is an integer from 0 to 116, indicating the age
    [gender] is either 0 (male) or 1 (female)
    [race] is an integer from 0 to 4, denoting White, Black, Asian, Indian, and Others (like Hispanic, Latino, Middle Eastern).
    [date&time] is in the format of yyyymmddHHMMSSFFF, showing the date and time an image was collected to UTKFace



**Tasks Performed**:

- Prepare the dataset for the model
- Develop CNN model for recognizing the gender
- Fit the basic CNN model
- Save the model & load the saved weight to test the model
- Predict the gender of the uploaded image
- Use OpenCV and Haar Cascade File to check the gender in real time

**Model Evaluation**:
- I was able to achieve a **test accuracy of approx 90%**
![Output 1](/images/output.PNG)
