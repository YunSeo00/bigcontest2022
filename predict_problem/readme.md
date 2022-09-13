- predict_set_split.ipynb
  - 예측문제를 위한 데이터셋을 생성하는 코드
  - 코드를 돌리면 6개의 csv 파일이 저장됨.
  - 각 csv 파일에 대한 설명은 아래와 같음.
  - csv 파일 설명
    1. user_loan_train.csv : user_spec + loan_result 인 훈련데이터
    2. user_loan_val.csv : user_spec + loan_result인 검증데이터
    3. user_loan_test.csv : user_spec + loan_result인 테스트데이터
    4. predict_final_set.csv : user_spec + loan_result인 6월 데이터 (대회 문제)
    5. no_info_data_345.csv : loan_result인 345월 데이터
    6. predict_final_no_info.csv : loan_result인 6월 데이터 (대회 문제)

  - 비고
      application_id가 loan_result에는 있지만 user_spec에는 없는 데이터가 존재하여 a-d묶음과 e-f묶음으로 분리함.
