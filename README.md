# ESSAY
Project: Drowsiness Detection using Deep Learning \
Stage 01: \
In the first phase, we took the input and used face landmark 468 to select two diagonal points to crop the two eyes image. Then, feed into the Xception model that predicts eye-opening and closing-eyes \
![image](https://user-images.githubusercontent.com/81805609/217510853-1e92dff4-e12d-4493-b3e1-8f2a35ded15a.png) 

Stage 02: \
In the second stage we create a queue with a length of five. Then we sum the queue if the sum is zero we will give the output as dangerous and warn the driver, otherwise if the sum is non-zero we will give the output as safe. \
![image](https://user-images.githubusercontent.com/81805609/217511183-e67266a1-3ce0-46e0-b4bc-ce801b60c792.png) 

Result: \
*Model predicts eye-opening and closing-eyes: \
![image](https://user-images.githubusercontent.com/81805609/217511553-d6f7cfc1-d802-4075-9dab-afc38f550d16.png) 
*Model Drowsiness Detection: \
![image](https://user-images.githubusercontent.com/81805609/217511841-ba1870c5-c512-4b91-a81c-99a650e90a51.png)





