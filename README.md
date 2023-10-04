# Membershipmanagement
## 회원관리 
![image](https://github.com/seokhyun06/Membershipmanagement/assets/122009563/579b9355-f7db-47ed-a8e1-7ec066f5746b)

## 회원가입
![image](https://github.com/seokhyun06/Membershipmanagement/assets/122009563/3d8a51bd-a26c-4f59-a5d2-c15ce919d50d)

```java
    // 빈칸 여부 확인
		// 아이디 중복 확인
		// 비번과 암호 확인이 일치 하는지 확인
		// 학번이 범위 안에 있는지 확인
		// ==> 위의 4가지를 확인한 결과를 저장할 변수 선언(boolean형)
		
		Boolean checkEmpty = false;
		Boolean checkId= false;
		Boolean checkPw = false;
		Boolean checkNum = false;
		
		checkEmpty = ischeckEmpty();
		checkId = ischeckId();
		checkPw = ischeckPw();
		checkNum = ischeckNum();
		
```
4개의 각각 메소드를 만들어 4개의 조건이 모두 만족하면 회원가입이 완료된다.

## 로그인 성공
![image](https://github.com/seokhyun06/Membershipmanagement/assets/122009563/4c347332-5484-4f3f-b5d5-bff698c3fb10)

로그인이 성공되면 로그인 성공 창이 뜨고 로그인 버튼에서 로그아웃 버튼으로 바뀐다.

## 회원정보 수정화면
![image](https://github.com/seokhyun06/Membershipmanagement/assets/122009563/f49d0c5f-4e8c-4583-9532-b13d5c5eba41)

회원정보수정버튼을 누르면 회원정보 화면 창이 뜬다.

사용자가 수정하고 싶은 곳을 수정하고 회원 정보 수정하기 버튼을 누르면 알림창이 뜬다.

확인을 누르면 수정하고 취소를 누르면 수정이 취소된다.

## 관리자 로그인 성공
![image](https://github.com/seokhyun06/Membershipmanagement/assets/122009563/46bf2335-271e-45d0-b536-a3f52e8992f2)

## 로그아웃
![image](https://github.com/seokhyun06/Membershipmanagement/assets/122009563/4bacf8d1-8a55-4123-bbd4-354e2869b644)
