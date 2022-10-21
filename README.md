# Image-Denoising-With-CDDAE
Convolutional Dual-Decoder AutoEncoder를 사용한 의료영상 잡음제거

"의료영상에서 Convolutional Dual-Decoder AutoEncoder 모형을 이용한 잡음제거"

[한국데이터정보과학회 10/11 게재허가]

<제안모형>

![image](https://user-images.githubusercontent.com/71765587/197094039-4e8187bd-f129-4e1b-8776-6f45da1ed473.png)

<Noise 종류>

![image](https://user-images.githubusercontent.com/71765587/197094238-87b2cd8d-0e11-4426-a71c-26b2a255a0a0.png)
![image](https://user-images.githubusercontent.com/71765587/197094334-08e37d6c-0f4d-4c86-a5bd-685cf47b7575.png)

<Loss Graph>
1. MRI Dataset

![image](https://user-images.githubusercontent.com/71765587/197094423-0fee5532-f4de-4c7c-b5c7-3e1027b5fcb9.png)

2. Chest CT Dataset

![image](https://user-images.githubusercontent.com/71765587/197094677-859e7bb5-05ac-423c-9bf1-8e8c65d76d91.png)


<실험결과>

1. 정성적인 비교
  
![image](https://user-images.githubusercontent.com/71765587/197094796-0fcc7afd-b4e7-4b95-bb1f-2260e645d4e7.png)
![image](https://user-images.githubusercontent.com/71765587/197094858-3e3138cc-8b50-46f4-be41-4d3de3d86a49.png)

2. 정량적인 비교

A. Gaussian Noise
  
![image](https://user-images.githubusercontent.com/71765587/197094932-28083058-87f6-4ea2-99b3-aa0ecc47b441.png)

B. Impulse Noise
  
![image](https://user-images.githubusercontent.com/71765587/197095003-40ee9453-144b-4d14-9e66-4e475afde081.png)

C. Speckle Noise
  
![image](https://user-images.githubusercontent.com/71765587/197095044-12fa0741-b3a4-48f3-b171-3d9dff06e78f.png)
