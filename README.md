# data-science-study

studying data-science with python, R

------------------------------
### 주요 패키지
 * IDE 도구
 - Jupyter, PyCharm
 
  * 데이터 가공/ 조작
 - pandas 
 
 * 행렬/ 배열/ 선형대수/ 통계
 - NumPy, SciPy
 
 * 시각화
 - matplotlib
 - Seaborn
 
 * 머신러닝
 - Scikit-learn

 * 기타
 - 딥러닝 : TensorFlow, Keras, Pytorch 
 - Web Application : Django, Flask

--------------------------------------------

### 과정
 

1. 주제 정하기

2. 데이터 수집 : File, DBMS, API, WEB

3. 데이터 가공 :pyhon, R, xls

4. 모델링 :

	-Stats. : Knowledge,

	-ML : Algorithm(Scikit-learn)

	4.1) supervised : feature(Attribute) - label(target)

			분류(Classification), 회귀(Regression)

	4.2) non-super clustering

	4.3) 강화학습

5. 평가

	-hold out validation

	-cross-validation

6. 레포트, 제출 

-----------------------------------

### 참고 사이트
- colab https://colab.research.google.com/

------------------------------------------

### tip

* countplot - 하나의 값을 그린다. 데이터가 범주형일 때 (x축이나 y축 이용)
* 그 외에 데이터가 연속형일 때 (barplot, distplot, boxplot, pointplot, scatterplot)

-------------------------------------

### folium install
!conda install -c conda-forge folium
pip install folium -( anacomda cmd에서 관리자형으로 열어서 )
import folium

--------------------------------------

### selenium install 
1) `Chrome version 확인` :

![Chrome_versionpng.png](attachment:Chrome_versionpng.png)



2) `Webdriver 사이트 접속 및 Download` :

https://chromedriver.chromium.org/downloads

![Webdriver_download.JPG](attachment:Webdriver_download.JPG)


3) `다양한 browser 위한 Webdriver` :

https://selenium-python.readthedocs.io/api.html

exe파일 실행하지말고 해당 폴더로 복사하기 

-> !pip install selenium 

--------------------------

### 글자가 깨질 때
matplotlib.rc('font', family='Malgun Gothic') # for Windows


---------------------------

### Machine Learning
1) Supervised
	-> feature(문제, 함수)와 label(답)로 구성된 data 
	-> feature를 fit하여 label을 predict
		* classification(분류) : 범주형 데이터
		* regression(회귀) : 연속형 데이터 
2) Non(Un)-Supervised
	-> feature(문제, 함수)로 구성된 data 
	-> 수학에 근거한 알고리즘
3) Reinforce (강화학습)

---------------------------
### prophet 설치

conda install -c conda-forge prophet

----------------

### prophet 참고 사이트
- https://facebook.github.io/prophet/docs/quick_start.html 

- https://www.kaggle.com/robikscube/time-series-forecasting-with-prophet/notebook 

