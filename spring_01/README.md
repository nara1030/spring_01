## 목차
1. [환경설정](#환경설정)
2. [프로젝트 설정](#프로젝트-설정)
3. [요구사항](#요구사항)
4. .

## 환경설정
* OS: Windows 10
* IDE: Eclipse
* Framework: Spring(Spring Legacy Project > Simple Spring Web Maven)  
	```txt
	<properties>
		<!-- Generic properties -->
		<java.version>1.6</java.version>
		<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
		<project.reporting.outputEncoding>UTF-8</project.reporting.outputEncoding>
		
		<!-- Web -->
		<jsp.version>2.2</jsp.version>
		<jstl.version>1.2</jstl.version>
		<servlet.version>2.5</servlet.version>
		
		<!-- Spring -->
		<spring-framework.version>3.2.3.RELEASE</spring-framework.version>

		<!-- Hibernate / JPA -->
		<hibernate.version>4.2.1.Final</hibernate.version>

		<!-- Logging -->
		<logback.version>1.0.13</logback.version>
		<slf4j.version>1.7.5</slf4j.version>

		<!-- Test -->
		<junit.version>4.11</junit.version>
	</properties>
	```
* .
* .

##### [목차로 이동](#목차)

## 프로젝트 설정
* 기본
	* [ ] 인코딩: UTF-8
	* [ ] [버전 업데이트 - Maven](https://woopi1087.tistory.com/30)
	* [ ] 폴더 구조
	* [ ] 로거 설정
* `web.xml`
	* [ ] [세션 시간 설정 - `session-config`](https://bluesmile-dev.tistory.com/7)
	* [ ] [보안 설정 - `login-config`](https://keichee.tistory.com/333)
	* [ ] [에러 페이지 설정](https://devks.tistory.com/40)
* .
	* [ ] 테이블-클래스 매핑 컨벤션
	* [ ] Dispatcher-Servlet 분기
	* [ ] .

##### [목차로 이동](#목차)

## 요구사항
* [로그인 관련](https://velog.io/@ette9844/Spring-HandlerInterceptor-%EB%A5%BC-%ED%99%9C%EC%9A%A9%ED%95%9C-%EB%A1%9C%EA%B7%B8%EC%9D%B8-%EC%B2%98%EB%A6%AC)
	* [ ] 로그인 유지
	* [ ] 특정 경로 이동시 로그인 체크(ex. 쓰기)
	* [ ] 자동로그인
	* [ ] 본인 작성글 수정/삭제 버튼 노출
	* [ ] 본인 작성댓글 수정/삭제 버튼 노출
* [ ] 사용자별 메뉴 노출

##### [목차로 이동](#목차)
