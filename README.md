# 백화점 고객의 성별 예측
1. 프로젝트 주제 및 목적
   - 백화점 구매 데이터를 분석하여 고객의 성별을 예측

2. 프로젝트 진행
   - 머신러닝 전공 팀프로젝트(2인)
   - 2020.10 ~ 2020.11

3. 프로젝트 설명
 
   ![image](https://github.com/user-attachments/assets/a12f465e-9745-484a-94aa-02cf9c42aac4)

   - 백화점 구매 데이터로부터 고객의 성별을 예측하는 분류 문제로 거래시각, 지점, 상품분류코드, 구매금액 피처를 이용해
     총 76개의 파생변수를 만들었다. 수치형 변수에 대해 이상치 처리, Standardization처리, 범주형 변수에 대해서는
     원핫인코딩을 하였고 Feature Selection 과정을 거쳐 최종적으로 280개의 피처를 사용했다.

     모델링은 BayesianOptimization으로
     KNN, MLP,LogisticRegression , RandomForest, GradientBoosting, ExtraTrees, XGBoost, LGBM, Catboost 등
     다양한 모델을 사용하여 튜닝을 하였고, 성능이 가장 좋게 나온 GradientBoosting, RandomForest 두 모델을
     SoftVoting 한 것을 최종 모델로 사용하였다. (박준영_2_Build_models-submit-2.ipynb)
     
4. 프로젝트 역할
    - 데이터 전처리 및 피처 엔지니어링
    - BayesianOptimization 하이퍼 파라미터 튜닝

5. 프로젝트 결과
    - 총 15팀 중 2위
      
   ![image](https://github.com/user-attachments/assets/e7144be7-e294-4e26-a204-c0898c4e0d03)

   
