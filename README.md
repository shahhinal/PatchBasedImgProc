## Introduction
This is MATLAB implementation of paper: W. Kim, “Image Enhancement Using Patch-Based Principal Energy Analysis,” IEEE Access, vol. 6, pp. 72620–72628, 2018.vv for Cal Poly Pomona Univ. course cs5550 as final project.
This paper proposes enhancement technique that decomposes the intensity channel and uses patch based principal energy 
which is an illumination component at each pixel.The proposed method uses conventional orthogonal transform for solving illumination-reflectance decomposition
<br/>
Additional global and local contrast techniques are implemented and performance metrics are used to compare the results.<br/>
##### List of global contrast algorithms implemented: 
1. Adaptive Gamma Correction with Weighting Distribution (AGCWD)
2. Adaptive Logarithmic Mapping
3. Fuzzy Logic Histogram Based
4. By enhancing Saturation Channel
5. Brightness Preserving Bi-Histogram Equalization (BBHE)

##### List of local contrast algorithms implemented:<br/>
1. Adaptive Histogram Equalization (AHE)
2. Contrast Limited Adaptive Histogram Equalization (CLAHE)

##### Performance metrics Used for image enhancement quality:<br/>
1. Mean Square Error (MSE)
2. Peak Signal to Noise Ratio (PSNR)
3. C-PCQI

### GUI Screenshots:
1. Various options to edit parameters values and change algorithms
![image](https://user-images.githubusercontent.com/35668737/75580821-47994580-5a1d-11ea-9d4a-cd448922fdd0.png)
2. Input and Output image panels
![image](https://user-images.githubusercontent.com/35668737/75580954-78797a80-5a1d-11ea-9b0a-40525597f8bf.png)
3. Performance score and Intermediate images 
![image](https://user-images.githubusercontent.com/35668737/75581003-91822b80-5a1d-11ea-9797-1af6a4d32b68.png)

### Implementation Results:
1. Output using different patch size
![image](https://user-images.githubusercontent.com/35668737/75581796-17eb3d00-5a1f-11ea-8e43-67c4dcb20f5d.png)
2. Output of using different global and local contrast algorithms
![image](https://user-images.githubusercontent.com/35668737/75581836-29344980-5a1f-11ea-98b1-172127ac75f7.png)
![image](https://user-images.githubusercontent.com/35668737/75581864-3a7d5600-5a1f-11ea-8a7d-28dfb2b4dbad.png)


### References:
1. W. Kim, “Image Enhancement Using Patch-Based Principal Energy Analysis,” IEEE Access, vol. 6, pp. 72620–72628, 2018.vv
2. S.-C. Huang, F.-C. Cheng, and Y.-S. Chiu, “Efficient Contrast Enhancement Using Adaptive Gamma Correction with Weighting Distribution,” IEEE Transactions on Image Processing, vol. 22, no. 3, pp. 1032–1041, 2013.
3. Kaur, Taranbir and Ravneet Kaur Sidhu. “Performance Evaluation of Fuzzy and Histogram Based Color Image Enhancement.” (2015)
4. J. L. Lisani, “Adaptive Local Image Enhancement Based on Logarithmic Mappings,” 2018 25th IEEE International Conference on Image Processing (ICIP), 2018.
5. Y.-T. Kim, “Contrast enhancement using brightness preserving bi-histogram equalization,” IEEE Transactions on Consumer Electronics, vol. 43, no. 1, pp. 1–8, 1997.
6. S. Wang, K. Ma, H. Yeganeh, Z. Wang, and W. Lin, “A Patch-Structure Representation Method for Quality Assessment of Contrast Changed Images,” IEEE Signal Processing Letters, vol. 22, no. 12, pp. 2387–2390, 2015.
Page 14 of 14
7. K. Gu, D. Tao, J.-F. Qiao, and W. Lin, “Learning a No-Reference Quality Assessment Model of Enhanced Images with Big Data,” IEEE Transactions on Neural Networks and Learning Systems, vol. 29, no. 4, pp. 1301–1313, 2018.
8. Pradeep, A. Gnana, and M. Gnanapriya. “A NOVEL CONTRAST ENHANCEMENT ALGORITHM USING HSV COLOR SPACE.” IJITR.


