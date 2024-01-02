# Geomin

# SpringBoot Project
* 바둑 교육 사이트 구현
![image](https://github.com/kimyongbinn/Geomin/assets/42797251/c209b00b-87d0-491d-8844-c2660f887033)
## 📌 담당 기술 구현 - 김용빈

**학습그룹 가입신청 / 학습자료 / 매출 조회**
- 학습그룹 가입신청
  - MyBatis ( DB SELECT, INTSERT )
  - JavaScript 
- 학습자료
  - JPA ( DB SELECT, INSERT, UPDATE, DELETE )
  - MyBatis ( DB SELECT )
  - JavaScript
  - MultipartFile
- 매출 조회
  - JPA ( DB SELECT )
  - JavaScript
  - Chart.js
  

SESSION 이용하여 로그인 / 로그아웃 구현
ID 기억하기 : 로그인 시 ID 정보 COOKIE 저장
비밀번호 찾기 -> 변경

이메일, 핸드폰 번호 인증후 회원정보 찾기. 문자전송 API 와 이메일전송 객체 사용
가입된 회원만 인증번호전송, 랜덤인증번호 와 입력인증번호 일치 시 비밀번호 변경 페이지 이동
INTERCEPTOR

로그인 필요한 페이지 접근 시 로그인 페이지로 이동 처리 ( 일반 회원 / 관리자 구분)
관리자 페이지 일반 회원이 접근 시 접근제한 페이지로 이동 처리
로그인 페이지 이동 시 이전 URL 저장 -> 로그인 후 해당 URL 이동 처리
독후감

목록 > 전체 독후감, 로그인 회원 해당 독후감 페이징 처리
독후감 등록 > 팝업 처리, 등록 된 책 상품 선택 후 상세내용 및 다중파일 업로드 구현
수정, 삭제 > 자신이 올린 독후감 상세 페이지에서 수정,삭제 가능 (작성한 회원만 button 볼 수 있게 처리)
좋아요 > 한 게시물 - 회원 당 한번만 가능 ( 재클릭 시 좋아요 비활성화 )
마이페이지

내 포인트 > 포인트 적립 및 차감 관련 목록 조회
장바구니 > 장바구니에 담은 상품 목록 조회 / 상품 없을 시 상품목록으로 이동 버튼 활성화
찜목록 > 찜한 상품 목록 조회 / 상품 없을 시 상품목록으로 이동 버튼 활성화
중고판매 현황 > 중고상품 판매 현황 목록 조회

## ERD
![image](https://github.com/kimyongbinn/Geomin/assets/42797251/cba72c5a-ab23-476c-86f4-a4b19b673199)


## 📰 UI
* 학습그룹 가입신청
![image](https://github.com/kimyongbinn/Geomin/assets/42797251/cd634e34-284d-44dc-9255-e3e056eb052f)
![image](https://github.com/kimyongbinn/Geomin/assets/42797251/1825172e-d846-43e5-93f4-0a5e65494479)

* 학습자료
  ![image](https://github.com/kimyongbinn/Geomin/assets/42797251/291d0c25-c113-4ad5-86ef-50b97a831917)
  > 목록
  ![image](https://github.com/kimyongbinn/Geomin/assets/42797251/e1667c6f-a365-490b-b3ed-93c03949d9ce)
  > 등록
  ![image](https://github.com/kimyongbinn/Geomin/assets/42797251/39aed6ca-9ca0-4b2d-bd78-1d6d56413185)
  > 상세
  ![image](https://github.com/kimyongbinn/Geomin/assets/42797251/30292c76-2851-4010-8323-1156729d6397)

* 매출 조회
  ![image](https://github.com/kimyongbinn/Geomin/assets/42797251/a283eb88-b148-4614-8d89-97dea2ce3470)
  ![image](https://github.com/kimyongbinn/Geomin/assets/42797251/11adc2a4-19d5-4616-9d95-06a4d6d9387a)



# ⏰ 개발 기간
- 2023.12.01 ~ 2023.12.29


# 🖥️ 개발 환경
- Java 11.0.12
- STS 2.7.17
- Oracle 11.2.0.2.0
- JDBC 8
