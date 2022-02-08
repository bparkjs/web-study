# web-study
백견불여일타 JSP&amp;Servlet 실습 코드

목차

1장. 서블릿과 JSP 개요

1.1 웹 프로그래밍이란?

1.2 웹 애플리케이션 개발 환경 구축하기 ? 프로그램 설치

JDK 설치하기
톰캣 설치하기
이클립스 설치하기

1.3 이클립스로 첫 웹 애플리케이션 작성하기

1.4 서블릿과 JSP의 기초 개념

서블릿
JSP

[직접해보세요] JDK, 톰캣, 이클립스 설치하기

2장.서블릿의 기초

2.1 서블릿 프로그램을 만들어보자

서블릿의 동작 원리
서블릿의 라이프 사이클

2.2 서블릿의 한글 처리와 데이터 통신

서블릿에서 응답시 한글 처리
get 방식과 post 방식
쿼리 스트링이란?
요청 객체(request)와 파라미터 관련 메소드(getParameter)
자바스크립트로 폼에 입력된 정보가 올바른지 판단하기
서블릿에서 요청시 한글 처리

2.3 기타 다양한 입력 양식

암호를 입력 받기 위한 암호 입력 상자
여러 줄 입력할 수 있는 글상자와 배타적 선택을 하는 라디오 버튼
체크박스와 request의 getParameterValues( )
목록 상자

[직접해보세요] Dynamic Web Project 만들고 서블릿 만들기

[직접해보세요] 서블릿의 라이프사이클 테스트

[직접해보세요] 한글 메시지를 출력하는 서블릿 만들기

[직접해보세요] get과 post 전송 방식의 폼과 서블릿 테스트

[직접해보세요] 텍스트 박스에 입력된 값 얻어오기

[직접해보세요] 유효성 체크하기

[직접해보세요] 입력 폼에서 한글 읽어오기

[직접해보세요] POST 방식으로 한글 읽기

[직접해보세요] 로그인 폼 만들기

[직접해보세요] 배타적 선택하기

[직접해보세요] 관심 분야 다중 선택하기

[직접해보세요] 작업과 관심 분야 선택하기

3장.JSP 기본 다루기

3.1 JSP로 시작하는 웹 프로그래밍

JSP와 HTML
서블릿과 JSP의 차이

3.2 JSP 기본 태그
JSP 스크립트 요소
주석문
지시자
include 지시자

[직접해보세요] Dynamic Web Project와 컨텍스트 패스

[직접해보세요] 두 수의 합을 출력하는 JSP

[직접해보세요] 변수값을 1 증가하여 출력하는 JSP

[직접해보세요] 선언문에 변수 선언과 메소드 정의하기

[직접해보세요] 선언문에 선언한 변수와 스크립트릿 변수의 성격 파악하기

[직접해보세요] 표현식의 사용 예

[직접해보세요] HTML 주석문과 JSP 주석문의 사용

[직접해보세요] 오늘 날짜 출력하기

[직접해보세요] 에러 발생 페이지와 에러 페이지 만들기

[직접해보세요] include 지시자 사용법 알아보기

4장.내장 객체와 액션 태그

4.1 JSP 내장 객체

out 내장 객체
request 내장 객체
response 내장 객체
application 내장 객체
내장 객체의 영역

4.2 액션 태그

'jsp:forward' 액션 태그
'jsp:param' 액션 태그
'jsp:include' 액션 태그

[직접해보세요] 브라우저와 웹 서버의 정보를 알아내는 JSP

[직접해보세요] 설문조사 폼 만들기

[직접해보세요] 페이지 강제 이동하기

[직접해보세요] 로그인 인증 처리하기

[직접해보세요] 성년만 입장 가능한 사이트 만들기

[직접해보세요] application의 실제 경로 알아보기

[직접해보세요] 내장 객체 영역 테스트

[직접해보세요] 페이지 이동

[직접해보세요] 조건에 따른 페이지 이동

[직접해보세요] 'jsp:include' 액션 태그를 활용한 모듈화

5장.쿠키와 세션

5.1 쿠키(cookie)

5.2 세션(session)

세션 사용하기
세션 관련 메소드
세션 제거하기
세션을 이용한 로그인 처리

[직접해보세요] 쿠키를 생성하는 JSP

[직접해보세요] 생성된 모든 쿠키를 얻어와 출력하기

[직접해보세요] id 쿠키 삭제하기

[직접해보세요] 세션에 값 설정하기

[직접해보세요] 세션에 설정한 모든 값 얻어오기

[직접해보세요] 세션 객체의 메소드 사용하기

[직접해보세요] 세션에 저장된 특정 객체 삭제하기

[직접해보세요] 설정된 모든 세션 제거하기

[직접해보세요] 회원 인증을 위해 아이디와 비밀번호를 입력받는 폼

[직접해보세요] 회원 인증 처리하기

[직접해보세요] 로그인 인증 받은 회원에게 제공되는 JSP

[직접해보세요] 인증된 사용자의 인증을 무효화하는 JSP

6장.자바 빈과 액션 태그

6.1 자바 빈과의 첫 데이트

6.2 자바 빈 클래스 만들기

6.3 자바 빈 관련 액션 태그

자바 빈 객체를 생성하는 'jsp:useBean' 액션 태그
자바 빈에서 정보를 얻어오는 'jsp:getProperty' 액션 태그
자바 빈에 정보를 새롭게 설정하는 'jsp:setProperty' 액션 태그

6.4 자바 빈으로 회원 정보 처리하기

[직접해보세요] 첫 자바 빈 만들기

[직접해보세요] 자바 빈 객체 생성하기(useBean 액션 태그)

[직접해보세요] 자바 빈 프로퍼티 값 얻기와 변경하기

[직접해보세요] 폼 양식에 입력한 내용을 자바 빈으로 처리하기


7장.표현 언어와 JSTL

7.1 표현 언어로 표현 단순화하기

7.2 표현 언어로 요청 파라미터 처리하기

7.3 표현 언어로 내장 객체 접근하기

7.4 JSTL

JSTL 라이브러리를 사용하는 이유
JSTL 라이브러리

7.5 JSTL core 태그

'c:set'과 'c:remove' 태그
흐름을 제어하는 태그
'c:import', 'c:redirect', 'c:url' 태그 사용하기
'c:out'과 'c:catch' 태그 사용하기

7.6 JSTL fmt 태그

숫자 날짜 형식 지정 관련 태그
로케일 지정을 위한 태그

[직접해보세요] 표현 언어로 간단한 메시지를 출력하는 JSP 페이지

[직접해보세요] 표현 언어에서 사용 가능한 데이터

[직접해보세요] 표현 언어의 연산자 사용하기

[직접해보세요] 로그인 폼 만들기

[직접해보세요] EL로 형 변환ㅎ 없이 두 수를 입력받아 합을 구하기

[직접해보세요] 서블릿 클래스에서 두 수에 대한 합을 구해 JSP에서 출력하기

[직접해보세요] 표현 언어의 내장 객체를 명시적으로 사용하기

[직접해보세요] 자바 빈 클래스 만들기

[직접해보세요] 표현 언어로 자바 빈 객체 속성 값 얻어오기

[직접해보세요] JSTL 다운로드 받아 설치하기

[직접해보세요] 'c:out 태그로 간단한 메시지를 출력하는 JSP 페이지

[직접해보세요] 'c:set' 태그로 변수에 값 저장하기

[직접해보세요] 색상 선택하기

[직접해보세요] 과일 선택하기

[직접해보세요] 아이디 중복 체크를 위한 JSP

[직접해보세요] 영화 제목을 저장한 배열을 'c:forEach' 태그의 varStatus 속성을 사용하여
인덱스와 반복 횟수 출력하기

[직접해보세요] first, last 프로퍼티 사용하기

[직접해보세요] begin, end 속성 사용하기

[직접해보세요] 관심 분야 다중 선택하기

[직접해보세요] 'c:import' 사용하기

[직접해보세요] 'c:url' 사용하기

[직접해보세요] 'c:redirect' 사용하기

[직접해보세요] 출력과 예외 처리를 지원하는 태그 사용하기

[직접해보세요] 날짜 형식 지정하기

[직접해보세요] 타임 존 설정하기

[직접해보세요] 로케일 지정하기

[직접해보세요] 입력 폼에서 한글 깨지지 않고 읽어오기

[직접해보세요] 요청 파라미터의 캐릭터 인코딩 지정하기

8장.데이터베이스와 JDBC

8.1 데이터베이스 개요 및 오라클 DB 환경 구축하기

오라클 다운로드와 설치

8.2 SQL

테이블을 생성하는 create table
테이블에 레코드를 추가하는 insert
데이터를 조회하는 select
저장된 데이터를 변경하는 update
테이블에 저장된 레코드를 삭제하는 delete

8.3 JDBC를 이용한 데이터 조작하기

데이터베이스와 연결하기
SELECT문과 Statement, ResultSet 클래스
데이터 저장과 PreparedStatement 클래스

[직접해보세요] 오라클 다운로드(Oracle Database 11g Express Edition)와 설치

[직접해보세요] 오라클 데이터베이스 관리 프로그램 접속하기

[직접해보세요] 사용자 생성하기

[직접해보세요] 회원 테이블 생성하기

[직접해보세요] JDBC 드라이버 연결하기

[직접해보세요] member 테이블에 데이터 추가하기

9장.데이터베이스를 이용한 회원 관리 시스템 구축하기

9.1 데이터베이스 커넥션 풀

9.2 데이터베이스를 연동한 회원 관리 시스템

사용자 관리 시스템의 전체 구조
회원 관리 member 테이블과 연동하는 DAO
로그인 인증 처리
회원 가입을 위한 프로그래밍
로그아웃 처리를 위한 프로그래밍
회원 정보 수정을 위한 프로그래밍

[직접해보세요] DBCP 설치하기

[직접해보세요] 이클립스에서 회원 정보를 저장하는 VO 클래스 만들기

[직접해보세요] 이클립스에서 회원 테이블을 액세스하는 DAO 클래스 만들기

[직접해보세요] 커넥션을 얻어오는 메소드

[직접해보세요] 회원 인증을 위해 아이디와 비밀번호를 입력 받는 폼

[직접해보세요] 회원 관리 웹 애플리케이션을 위한 자바스크립트 파일

[직접해보세요] 로그인 입력 폼을 위한 서블릿 클래스 만들기

[직접해보세요] 홈(프론트) 페이지

[직접해보세요] 회원 인증을 위한 메소드 추가하기

[직접해보세요] 회원 인증을 위한 서블릿 클래스 만들기

[직접해보세요] 회원 인증된 사용자에게 제공되는 JSP 페이지

[직접해보세요] 회원 정보 입력 폼을 위한 서블릿 클래스 만들기

[직접해보세요] 회원 가입을 위한 회원 정보를 입력 받는 폼

[직접해보세요] 중복 체크 페이지를 새로운 창으로 띄우기 위한 자바스크립트 함수

[직접해보세요] 아이디 중복 체크를 위한 메소드 추가하기

[직접해보세요] 아이디 중복 체크를 위한 서블릿 클래스 만들기

[직접해보세요] 아이디 중복 체크를 위한 JSP 페이지

[직접해보세요] 아이디 중복 체크 완료 처리를 위한 자바스크립트 함수

[직접해보세요] 회원 정보의 유효성을 체크하기 위한 자바스크립트 함수

[직접해보세요] 회원 정보를 DB에 추가하기 위한 메소드 추가하기

[직접해보세요] 회원 정보를 데이터베이스에 추가하는 서블릿

[직접해보세요] 인증된 사용자의 인증을 무효화하는 서블릿

[직접해보세요] 회원 정보 수정을 위한 폼으로 이동하는 처리를 하는 서블릿

[직접해보세요] 인증된 사용자에게 제공되는 회원 정보 수정 페이지

[직접해보세요] 회원 정보를 변경하기 위한 메소드 추가하기

[직접해보세요] 회원 정보 수정 처리 서블릿의 doPost( ) 메소드에 데이터베이스 처리를
위한 코드 추가


10장.파일 업로드

10.1 파일 업로드에 사용되는 COS 라이브러리

10.2 쇼핑몰 관리자 애플리케이션 작성-cos.jar 파일을 이용한

이미지 업로드
쇼핑몰 관리자 페이지 개요
데이터베이스 구축하기
프로젝트 환경 설정
상품 정보를 저장하기 위한 VO 클래스 정의
데이터베이스 처리를 위한 DAO 클래스
화면 디자인을 위한 스타일 시트 정의하기
상품 등록하기
상품 수정하기
상품 삭제하기

[직접해보세요] 파일 전송 폼 만들기

[직접해보세요] 파일 업로드를 위한 서블릿

[직접해보세요] 한꺼번에 여러 파일을 업로드하기 위한 폼

[직접해보세요] 한꺼번에 여러 파일을 업로드하기 위한 서블릿

[직접해보세요] 이클립스에서 상품 정보를 저장하는 VO 클래스 작성

[직접해보세요] Connection 객체 얻기와 사용이 끝난 리소스 해제를 위한 클래스

[직접해보세요] 스타일 시트 파일

[직접해보세요] ProductDAO 클래스 정의하기

[직접해보세요] 상품 리스트를 위한 서블릿

[직접해보세요] 상품 리스트를 위한 JSP 페이지

[직접해보세요] 상품 등록을 위한 서블릿

[직접해보세요] 상품 등록 화면을 위한 JSP

[직접해보세요] ProductDAO 클래스에 상품 등록을 위한 메소드 추가하기

[직접해보세요] 폼 입력 정보의 유효성 체크를 위한 자바스크립트

[직접해보세요] ProductDAO 클래스에 상품 등록을 위한 메소드 추가하기

[직접해보세요] ProductDAO 클래스에 상품 정보 수정을 위한 메소드 추가하기

[직접해보세요] 상품 수정을 위한 서블릿

[직접해보세요] 상품 삭제를 위한 서블릿

[직접해보세요] 상품 삭제 화면을 위한 JSP 페이지

[직접해보세요] ProductDAO 클래스에 상품 삭제를 위한 메소드 추가하기


11장.MVC 패턴(모델2)을 사용한 게시판

11.1 모델2 기반의 MVC 패턴 개요

MVC 패턴의 컨트롤러 : 서블릿
MVC 패턴의 뷰: JSP
MVC 패턴의 모델

11.2 게시판-모델2 기반의 간단한 MVC 패턴 구현하기

[직접해보세요] 이클립스에서 게시글 정보를 저장하는 VO 클래스 만들기

[직접해보세요] Connection 객체 얻기와 사용이 끝난 리소스 해제를 위한 클래스 만들기

[직접해보세요] 게시글 테이블을 액세스하는 DAO 클래스 만들기

[직접해보세요] 폼 입력 정보의 유효성을 체크하는 자바스크립트

[직접해보세요] 화면 레이아웃을 위한 스타일 시트

[직접해보세요] MVC 패턴의 Controller 역할을 하는 서블릿 만들기

[직접해보세요] 모델을 동일한 방식으로 실행하기 위한 인터페이스

[직접해보세요] 커맨드(command) 패턴으로 작업 처리를 위한 명령 처리 클래스

[직접해보세요] BoardServlet 클래스에 코드 추가하기

[직접해보세요] 게시글 리스트를 위한 액션 클래스

[직접해보세요] 게시글 리스트를 위한 JSP 페이지

[직접해보세요] 커맨드 패턴으로 작업 처리를 위한 명령 처리 클래스 ActionFactory 수정

[직접해보세요] 게시글 등록을 위한 폼으로 이동하게 하는 액션 클래스

[직접해보세요] 게시글 등록 화면을 위한 JSP 페이지

[직접해보세요] 게시글을 데이터베이스에 추가하기 위한 액션 클래스

[직접해보세요] 게시글 상세 보기 페이로 이동하게 하는 액션 클래스

[직접해보세요] 게시글 상세 보기를 위한 JSP 페이지

[직접해보세요] 비밀번호 입력 화면으로 이동하게 하는 액션 클래스

[직접해보세요] 비밀번호 입력 화면을 위한 JSP 페이지

[직접해보세요] 게시글의 비밀번호 확인을 위한 액션 클래스

[직접해보세요] 게시글의 비밀번호가 일치할 경우 처리를 위한 JSP 페이지

[직접해보세요] 게시글 수정 화면으로 이동하게 하는 액션 클래스

[직접해보세요] 게시글 수정 화면을 위한 JSP 페이지

[직접해보세요] 게시글을 데이터베이스에 수정하기 위한 액션 클래스

[직접해보세요] 게시글 삭제를 위한 액션 클래스

