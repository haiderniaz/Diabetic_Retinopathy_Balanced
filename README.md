Diabetic Retinopathy Detection

Diabetic retinopathy is a diabetes-related complication that affects the eyes. It occurs when high levels of blood sugar damage the blood vessels in the retina, the light-sensitive tissue at the back of the eye. This damage can lead to vision impairment and even blindness if left untreated.

There are 5 Types Of Diabetic Retinopathy Stages

1 No_Dr
2 Mild
3 Moderate
4 Severe
5 Proliferative DR

Notations In Dataset -> {0: 'No_Dr', 1: 'Mild', 2: 'Moderate', 3: 'severe', 4: 'Proliferative DR'}

These images were taken and pre-processed/cleaned from original dataset that's present -> https://www.kaggle.com/datasets/tanlikesmath/diabetic-retinopathy-resized

Pre-Processing Involved
a) Balancing out all the 5 types of Images in each of the class.
b) Image Augmentation -> RandomRotation , RandomZoom , RandomContrast, GaussianBlur,Crop and many more.

Refer Below Github-Repo For More Details.

    https://github.com/Kushagratandon12/Diabetic_retinopathy/tree/main
