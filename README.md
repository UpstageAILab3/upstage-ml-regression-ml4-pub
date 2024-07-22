[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/D1pZhJxu)
# House Price Prediction | 아파트 실거래가 예측

## Team

| ![안재영](https://avatars.githubusercontent.com/u/104719742?v=4) | ![박주연](https://avatars.githubusercontent.com/u/164493549?v=4) | ![이아윤](https://avatars.githubusercontent.com/u/118864266?v=4) | ![성명기](https://avatars.githubusercontent.com/u/104310191?v=4) | ![서혜교](https://avatars.githubusercontent.com/u/86095630?v=4) |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|            [안재영](https://github.com/AJY3124)             |          [박주연](https://github.com/Lucypothesis)               |            [이아윤](https://github.com/Laycode00)             |            [성명기](https://github.com/SUNGMYEONGGI)             |            [서혜교](https://github.com/andWHISKEY)             |
|   팀장  | 팀원 | 팀원 | 팀원 | 팀원 |

## 1. Competiton Info

### Overview

- House Price Prediction 경진대회는 주어진 데이터를 활용하여 서울의 아파트 실거래가를 효과적으로 예측하는 모델을 개발하는 대회입니다.

### Timeline

- 2024.07.08 ~ 2024.07.22

### Evaluation
<img src="https://t1.daumcdn.net/thumb/R720x0/?fname=http://t1.daumcdn.net/brunch/service/user/IgT/image/VPAtmQdjdJUh3KVXeTVw2_txvYI.png" title="RMSE"/>

- RMSE는 예측된 값과 실제 값 간의 평균편차를 측정합니다. 아파트 매매의 맥락에서는 회귀 모델이 실제 거래 가격의 차이를 얼마나 잘 잡아내는지 측정합니다. 

## 2. Components

### Directory
```bash
UPSTAGE-ML-REGRESSION-ML4
├── AYUN
│   ├── code
│   │   ├── 1data_merge_conveni.ipynb
│   │   ├── 2data_merge_food.ipynb
│   │   ├── 3data_merge_big.ipynb
│   │   ├── 4data_merge_movie.ipynb
│   │   ├── 5royal_floor.ipynb
│   │   └── 6all_merge.ipynb
│   └── royal_floor
│       └── royal_floor.ipynb
├── HYEGYO
│   └── Train_&_Test_dataset_code.ipynb
├── JAEYEONG
│   ├── 500m이내 버스정류장 개수.ipynb
│   ├── JY_작업파일.ipynb
│   ├── column_merge.ipynb
│   ├── 버스_지하철_통합.ipynb
│   ├── 지하철 정보 연동.ipynb
│   ├── 상관관계분석.ipynb
│   └── 위도경도작업.ipynb
├── JUYEON
│   ├── 240710_train데이터셋.ipynb
│   ├── 240716_test데이터셋.ipynb
│   └── 외부데이터
│       ├── 240712-파생변수추가.ipynb
│       ├── 서울시 학교 기본정보.csv
│       ├── 서울시 학원 교습소정보.csv
│       ├── 학급당+학생수(구별)_20240710103447.csv
│       ├── 서울시_학원_위도와경도.csv
│       ├── 서울시_중학교_위도와경도.csv
│       └── 서울시_초등학교_위도와경도.csv
├── MYEONGGI
│   ├── code
│   │   ├── EDA.ipynb
│   │   ├── HousePrice_EDA(None-Birth).ipynb
│   │   ├── HousePrice_EDA.ipynb
│   │   ├── baseline_code.ipynb
│   │   ├── houseprice_alldata.ipynb
│   │   ├── houseprice_predict(구단위).ipynb
│   │   ├── houseprice_predict(전용면적&강남여부).ipynb
│   │   ├── houseprice_predict(전용면적&고가저가)_실패.ipynb
│   │   ├── houseprice_predict(전용면적).ipynb
│   │   ├── irk_EDA.ipynb
│   │   ├── requirements.txt
│   │   └── voting.ipynb
│   └── data
│       └── IR_Korea(경제지표).csv
├── README.md
└── docs
    └── [패스트캠퍼스]House Price Prediction_4조.pptx
```

## 3. Data descrption

### Dataset overview

- 학습 데이터 (2007.01.01 ~ 2023.06.30) 1,118,822개 거래 데이터 52개 변수 (거래금액 포함)

- 평가 데이터 (2023.07.01 ~ 2023.09.26) 9,272개 거래 데이터 51개 변수 (거래금액 제외)

- 기초생활환경, 교육환경, 문화 및 상권, 합계출산율, 경제지표 등 외부 데이터

### EDA
<img src="https://github.com/SUNGMYEONGGI/image/blob/main/upml3_img1.png?raw=true" style="zoom:60%;" />

<img src="https://github.com/SUNGMYEONGGI/image/blob/main/upml3_img2.png?raw=true" style="zoom:60%;" />

<img src="https://github.com/SUNGMYEONGGI/image/blob/main/upml3_img3.png?raw=true" style="zoom:60%;" />

## 4. Modeling
<img src="https://github.com/SUNGMYEONGGI/image/blob/main/upml3_img6.png?raw=true" style="zoom:60%;" />

## 5. Result

### Leader Board
#### Public Leader Board
<img src="https://github.com/SUNGMYEONGGI/image/blob/main/upml3_img4.png?raw=true" title="Leader Board" style="zoom:60%;" />

#### Private Leader Board
<img src="https://github.com/SUNGMYEONGGI/image/blob/main/upml3_img5.png?raw=true" title="Leader Board" style="zoom:60%;" />

### Presentation
[발표자료](https://github.com/UpstageAILab3/upstage-ml-regression-ml4/blob/main/docs/House%20Price%20Prediction_4%EC%A1%B0.pdf)