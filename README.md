# TacTileSegmentation
- 점자 보도블럭 segmentation model  

학습 방법  
--------------------
1. 노란색 박스를 segmentation하는 모델을 학습.  
2. 사전학습한 모델을 가지고 실제 점자보도블럭으로 전이학습.  
   - freeze layer set중 가장 좋은 성능을 보인 것으로 더 높은 epoch에서 학습.   

결과  
----------
### test image:   
![image](https://user-images.githubusercontent.com/66504341/142164495-2198f91e-7800-4ed4-a837-b61aae3e825e.png)   
### predict result:   
![image](https://user-images.githubusercontent.com/66504341/142164874-d28f3c91-44fe-47da-8255-b4f7248b3c7f.png)   
