# shoppingmall-web
쇼핑몰을 만들어보자

프로젝트 설정
-
https://start.spring.io/

+ Project
  + Build : Gradle
  + Language : Java
  + Spring Boot : 2.5.4
  + Dependencies : Spring Web, Thymeleaf, Lombok, Validation, H2 Database, Spring HATEOAS, Spring REST Docs, MyBatis Framework, MySQL Driver

목표
- 
1. 쇼핑몰 구현
2. AWS에 올리기
3. 도메인 등록해서 도메인 주소 적용

프로세스
-
1. 쇼핑몰 템플릿 구하기
    + https://themewagon.com/themes/free-responsive-bootstrap-4-html5-ecommerce-website-template-ashion/
2. 기능 정의
    + 구현할 기능 정의
        + 로그인 기능
        + 상품 화면
        + 상품 상세 화면
        + 장바구니 기능
        + 찜 기능    
3. DB 설계
    + 테이블 정의서 작성
    + MysqlWorkbench를 이용하여 DB 설계 및 ERD 작성
    <img src="https://user-images.githubusercontent.com/30275700/137919758-9e49326c-c208-45da-a74f-8861b9473b9c.png">
4. 개발
    + 테스트 주도 개발(TDD)

진행사항
-
+ 21/10/16
    + 쇼핑몰 템플릿을 스프링 프로젝트에 설정 완료
    + 테이블 정의서 및 ERD 작성중
+ 21/10/19
    + ERD 초안 작성 완료
