## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:

 # FEATURE ENCODING
 
 <img width="680" height="695" alt="image" src="https://github.com/user-attachments/assets/a9591317-1b22-4aed-b686-d5da416d2c1a" />

 # ORIGINAL ENCODER

 <img width="797" height="483" alt="image" src="https://github.com/user-attachments/assets/b7d103b4-75e5-477b-b52d-12d9091c51fa" />

<img width="690" height="565" alt="image" src="https://github.com/user-attachments/assets/b6224d8a-6d83-4387-bb47-43a4bf1463ba" />

# LABEL ENCODER

<img width="721" height="698" alt="image" src="https://github.com/user-attachments/assets/abbb4a50-2b89-4941-a919-fd1bc1326ed7" />

# ONEHOT ENCODER

<img width="653" height="715" alt="image" src="https://github.com/user-attachments/assets/f3774b18-9f80-4126-918c-a25cffc4ba95" />

<img width="791" height="461" alt="image" src="https://github.com/user-attachments/assets/cec0fbba-13f3-4979-ab84-c1b41edad3f5" />

<img width="810" height="397" alt="image" src="https://github.com/user-attachments/assets/f7f42d06-dbf7-4c0a-a2fb-b9423e36a633" />

<img width="720" height="568" alt="image" src="https://github.com/user-attachments/assets/04ed0464-b50b-4060-9e18-076f6752964e" />

# BINARY ENCODER

<img width="797" height="637" alt="image" src="https://github.com/user-attachments/assets/bd4e5ced-3a2a-4ba7-9804-f1e806c2c761" />

# TARGET ENCODER

<img width="742" height="567" alt="image" src="https://github.com/user-attachments/assets/ad151f79-34e8-4082-83e3-30afb4d267b7" />

# FEATURE TRANSFORMATION

<img width="793" height="691" alt="image" src="https://github.com/user-attachments/assets/529c5f48-3b4d-4c85-b351-9e4e083c53cc" />

<img width="602" height="285" alt="image" src="https://github.com/user-attachments/assets/a084c685-6e74-4c16-b258-d66708cf9b03" />

<img width="638" height="562" alt="image" src="https://github.com/user-attachments/assets/fce5b773-dfd4-4bb7-ae51-0f6d084912f6" />

<img width="630" height="562" alt="image" src="https://github.com/user-attachments/assets/382ad341-1b1a-47e9-a7e2-66143c9680f6" />

<img width="628" height="567" alt="image" src="https://github.com/user-attachments/assets/1a711243-be06-4386-9c0a-c4941d7ae7ae" />

<img width="662" height="562" alt="image" src="https://github.com/user-attachments/assets/e28e7e29-d5a1-4fe7-9d31-e8ee92b321db" />

<img width="795" height="611" alt="image" src="https://github.com/user-attachments/assets/e718d343-e841-42c4-b798-4f0b4aac8944" />

<img width="695" height="323" alt="image" src="https://github.com/user-attachments/assets/f395b9ee-ad3d-484a-a3f9-9f90449a105e" />

<img width="796" height="425" alt="image" src="https://github.com/user-attachments/assets/50a941d1-1c72-4976-b906-1a4c8dee5a12" />

# QUANTILE TRANSFORMER

<img width="792" height="731" alt="image" src="https://github.com/user-attachments/assets/6d0b2d3e-8efc-4881-83a2-55fbe502af77" />

<img width="782" height="692" alt="image" src="https://github.com/user-attachments/assets/79dc8d66-78c1-44b5-b94d-30a3d2bd387e" />

<img width="778" height="555" alt="image" src="https://github.com/user-attachments/assets/80cdac91-ef66-4adc-ae64-1a238c64d86a" />

<img width="783" height="563" alt="image" src="https://github.com/user-attachments/assets/43f2cac7-3b6a-44a5-a2af-7cfba376b6ea" />

# RESULT:
      
Thus the program to read the given data and perform Feature Encoding and Transformation process and save the data to a file is successfully completed.
       
