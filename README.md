# Dacon_Mnist: 글자에 숨겨진 숫자찾기 (08.23~)  
- __1주차__: [baseline코드](https://github.com/Jimin980921/Dacon_Mnist/blob/master/ver1_baseline.ipynb)기반 정확도 높이기(8.23~8.30) 
 > epoch수 늘리기=> 정확도: 약 75%  
   layer 한 층 쌓기=> 정확도: 약 60%
  <br>
  
  
 - __2주차__: [이미지 전처리](https://github.com/Jimin980921/Dacon_Mnist/blob/master/dacon_Transforming_data.ipynb)를 통해 정확도 높이기(8.31~09.06)  
>   - __원본__=> 정확도: 약 75%  
><img src="https://user-images.githubusercontent.com/57060127/92191308-65e56f80-ee9e-11ea-9e72-c337a8823b58.JPG" width=30%>  
<br>

  __특징점 강조__  
>   - __th=125__  
baseline코드=> 정확도: 약 24%   
layer추가코드=> 정확도:  약 31%  
><img src="https://user-images.githubusercontent.com/57060127/92191310-667e0600-ee9e-11ea-81b0-c1441ed28292.JPG" width=30%>  
<br>

>   - __th=200__   
baeline코드=> 정확도: 약 41%   
layer추가코드=> 정확도: 약 38%   
><img src="https://user-images.githubusercontent.com/57060127/92191306-64b44280-ee9e-11ea-94c5-1a75e8506442.JPG" width=30%>  
<br>

__데이터 증가__  
특징점 강조한 데이터, train을 한번에 학습  
> baseline코드=> 정확도: 약 68%  
layer추가코드=> 정확도: 약 70%  
<br>

- 3주차: 정확도 높이기  
*임계값을 작게잡아 너무 많은 특징점을 강조하는것이 정확도를 낮추는 요인임을 발견  
> 200이상 다양한 임계값으로 데이터 증가+ver2.=> 정확도: 75%  

> 200이상 다양한 임계값으로 데이터 증가+ver3.=> 이미지증가 데이터먼저 학습 후 train데이터 학습 =>80%   
                                                    train학습 후 이미지증가 데이터 학습=>75%  
  
> 200이상 다양한 임계값으로 데이터 증가+ver4. => 이미지증가 데이터먼저 학습 후 train데이터 학습 =>76%  
  layer가 깊다고 정확도가 높은 것은 아님.  


