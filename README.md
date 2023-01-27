# 빅콘테스트 2022 퓨처스 부문
### 🏆 본선 진출 🏆

- 팀명 : nan알아요
- 팀원 : 김희경, 이영아, 이지수, 최윤서
- 팀 노션 페이지 : [Notion ](https://www.notion.so/2022-bigcontest-8e644f75749041debe979cc497ccf2f7)
- 분석 보고서 : [분석 보고서 바로가기](https://github.com/YunSeo00/bigcontest2022/blob/main/final_result/nan%EC%95%8C%EC%95%84%EC%9A%94%ED%8C%80_%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B6%84%EC%84%9D%EB%A6%AC%EA%B7%B8_%ED%93%A8%EC%B2%98%EC%8A%A4%EB%B6%84%EC%95%BC_%EB%B6%84%EC%84%9D%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)

### 대회 소개
- [대회 공식 홈페이지](https://www.bigcontest.or.kr/)
- 대회 기간 : 2022.8.30 ~ 2022.10.14
- 분석 주제 : 앱 사용성 데이터를 통한 대출신청 예측 분석
- 분석 목표
    - 대출 신청 고객 예측 : 사용자의 대출 상품 조회 신청서 정보와 승인된 대출 상품 정보를 바탕으로 대출 신청 고객과 승인된 대출 상품을 예측.
    - 모델 기반 고객 군집 분석 : 사용자 사용 기록(log data)을 이용한 군집 결과를 바탕으로 어플 메인 화면 상단 배너에 노출될 서비스 메시지 제안.
- 제공 데이터
  - log_data : 사용자의 로그 데이터가 담긴 테이블.
  - user_spec : 사용자의 일반정보, 고용정보, 소득정보, 대출관련정보가 담긴 테이블.
  - loan_result : 사용자(user)의 대출상품(item)에 대한 신청 여부가 담긴 테이블.

### 주요 분석 과정

#### 결측치 처리
<img width="682" alt="스크린샷 2023-01-27 오후 7 41 18" src="https://user-images.githubusercontent.com/88306013/215067072-1b0c69a4-029d-45db-85d1-9783a77da959.png">


#### 파생변수 생성
<img width="681" alt="스크린샷 2023-01-27 오후 7 41 41" src="https://user-images.githubusercontent.com/88306013/215067138-8b10b202-ab67-4da9-8997-3bf8837cf1f5.png">
<img width="684" alt="스크린샷 2023-01-27 오후 7 41 51" src="https://user-images.githubusercontent.com/88306013/215067162-5dcaae48-8912-4a03-aad1-40431da2abe4.png">


#### 군집 및 시각화
<img width="684" alt="스크린샷 2023-01-27 오후 7 42 07" src="https://user-images.githubusercontent.com/88306013/215067211-fdd7d672-9ff8-44dc-aa03-b379c5cb09c5.png">


#### 더 자세한 분석 보러가기 -> [분석보고서 link](https://github.com/YunSeo00/bigcontest2022/blob/main/final_result/nan%EC%95%8C%EC%95%84%EC%9A%94%ED%8C%80_%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B6%84%EC%84%9D%EB%A6%AC%EA%B7%B8_%ED%93%A8%EC%B2%98%EC%8A%A4%EB%B6%84%EC%95%BC_%EB%B6%84%EC%84%9D%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)




