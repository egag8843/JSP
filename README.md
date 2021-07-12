# JSP

# Ch01. Hello JSP
  - JSP 환경설정 (Apache Tomcat 8.5 Server Setting)

# Ch02. JSP 클래스, 인클루드 지시자 실습
  	- include 지시자
		- 공통의 전역파일을 삽입하는 지시자
		- 일반적으로 UI 모듈, 공통전역 파일 변수를 삽입할 때 사용
		- 정적타임 삽입, 참고) include 태그는 동적타임에 삽입

# Ch03. JSP 내장객체 실습
  	- cookie
 	 	- 클라이언트와 서버간의 식별을 위해 사용하는 조각파일
	 	- 서버에서 쿠키를 생성하고 클라이언트로 전송
  	 	- 클라이언트는 전송된 쿠키를 보관, 해당 서버로 다시 요청할때 보관된 쿠키를 전송

# Ch04. JSP 액션태그 실습
     - forward 태그
		 - 서버 시스템 내에서 페이지 요청을 처리하는 pageContext 내장객체의 기능
		 - 최초 요청에 대한 주소가 반영
		 - jsp 액션태그로 기능 제공
     
     - usebean 태그
		 - 자바빈(form 입력필드, table 컬럼을 멤버로 갖는 객체)을 활용하기 위한 태그
		 - 전송 파라미터를 수신(getParameter)해서 자바빈 객체로 생성

# Ch05. JSP DB Connect

# Ch06. JSP Ajax 실습
	-AJAX
		 - 일반적인 HTTP통신과 다르게 부분적인 통신방식(비동기 통신)
		 - jQuery 라이브러리의 Ajax 함수를 이용하여 통신
		 - 통신결과 데이터로 주로 JSON을 다룬다.
		 
# Ch07. JSP JSTL 실습
	- JSTL : Java Standars Tag Library
	
# FarmStory, JBoard 실습
	- 기본 게시판 만들기 실습.
	- 로그인, 회원가입, 글쓰기, 수정, 댓글달기등의 기능 구현.
