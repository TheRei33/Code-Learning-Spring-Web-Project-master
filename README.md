# Code-Learning-Spring-Web-Project-master
코드로 배우는 스프링 웹 프로젝트

Part 1 스프링 개발 환경 구축<br>

1장 개발을 위한 준비<br>
1.1 개발환경 설정<br>
1.2 스프링 프로젝트 생성<br>
1.3 Tomcat을 이용한 프로젝트 실행 확인<br>
1.4 Lombok 라이브러리 설치<br>
1.5 Java Configuration을 하는 경우<br>

2장 스프링의 특징과 의존성 주입<br>
2.1 스프링 프레임워크의 간략한 역사<br>
2.2 의존성 주입 테스트<br>
2.3 스프링이 동작하면서 생기는 일<br>
2.4 스프링 4.3 이후 단일 생성자의 묵시적 자동주입<br>

3장 스프링과 Oracle Database 연동<br>
3.1 오라클 설치<br>
3.2 SQL Developer 설치<br>
3.3 프로젝트의 JDBC 연결<br>
3.4 커넥션 풀 설정<br>

4장 MyBatis와 스프링 연동<br>
4.1 MyBatis<br>
4.2 스프링과의 연동 처리<br>
4.3 log4jdbc-log4j2 설정<br>

Part 2 스프링 MVC 설정<br>

5장 스프링 MVC의 기본 구조<br>
5.1 스프링 MVC 프로젝트의 내부 구조<br>
5.2 예제 프로젝트의 로딩 구조<br>
5.3 스프링 MVC의 기본 사상<br>
5.4 모델2와 스프링 MVC<br>

6장 스프링 MVC의 Controller<br>
6.1 @Controller, @RequestMapping<br>
6.2 @RequestMapping의 변화<br>
6.3 Controller의 파라미터 수집<br>
6.4 Model이라는 데이터 전달자<br>
6.5 Controller의 리턴 타입<br>
6.6 Controller의 Exception 처리<br>

Part 3 기본적인 웹 게시물 관리<br>

7장 스프링 MVC 프로젝트의 기본 구성<br>
7.1 각 영역의 Naming Convention(명명규칙)<br>
7.2 프로젝트를 위한 요구 사항<br>
7.3 예제 프로젝트 구성<br>
7.4 데이터베이스 관련 설정 및 테스트<br>
7.5 Java 설정을 이용하는 경우의 프로젝트 구성<br>

8장 영속/비즈니스 계층의 CRUD 구현<br>
8.1 영속 계층의 구현 준비<br>
8.2 영속 영역의 CRUD 구현<br>

9장 비즈니스 계층<br>
9.1 비지니스 계층의 설정<br>
9.2 비즈니스 계층의 구현과 테스트<br>

10장 프레젠테이션(웹) 계층의 CRUD 구현<br>
10.1 Controller의 작성<br>
10.2 BoardController의 작성<br>

11장 화면 처리<br>
11.1 목록 페이지 작업과 includes<br>
11.2 목록 화면 처리<br>
11.3 등록 입력 페이지와 등록 처리<br>
11.4 조회 페이지와 이동<br>
11.5 게시물의 수정/삭제 처리<br>

12장 오라클 데이터베이스 페이징 처리<br>
12.1 order by의 문제<br>
12.2 order by 보다는 인덱스<br>
12.3 인덱스를 이용하는 정렬<br>
12.4 ROWNUM과 인라인뷰<br>

13장 MyBatis와 스프링에서 페이징 처리<br>
13.1 MyBatis 처리와 테스트<br>
13.2 BoardController와 BoardService 수정<br>

14장 페이징 화면 처리<br>
14.1 페이징 처리할 때 필요한 정보들<br>
14.2 페이징 처리를 위한 클래스 설계<br>
14.3 JSP에서 페이지 번호 출력<br>
14.4 조회 페이지로 이동<br>
14.5 수정과 삭제 처리<br>
14.6 MyBatis에서 전체 데이터의 개수 처리<br>

15장 검색 처리<br>
15.1 검색 기능과 SQL<br>
15.2 MyBatis의 동적 SQL<br>
15.3 검색 조건 처리를 위한 Criteria의 변화<br>
15.4 화면에서 검색 조건 처리<br>

Part 4 REST 방식과 Ajax를 이용하는 댓글 처리<br>

16장 REST 방식으로 전환<br>
16.1 @RestController<br>
16.2 @RestController의 반환 타입<br>
16.3 @RestController에서 파라미터<br>
16.4 REST 전송 방식<br>
16.5 다양한 전송 방식<br>

17장 Ajax 댓글 처리<br>
17.1 프로젝트의 구성<br>
17.2 댓글 처리를 위한 영속 영역<br>
17.3 서비스 영역과 Controller 처리<br>
17.4 JavaScript 준비<br>
17.5 이벤트 처리와 HTML 처리<br>
17.6 댓글의 페이징 처리<br>
17.7 댓글 페이지의 화면 처리<br>

Part 5 AOP와 트랜잭션<br>

18장 AOP라는 패러다임<br>
18.1 AOP 용어들<br>
18.2 AOP 실습<br>
18.3 AOP 설정<br>
18.4 AOP 테스트<br>
18.5 @Around와 ProceedingJoinPoint<br>

19장 스프링에서 트랜잭션 관리<br>
19.1 데이터베이스 설계와 트랜잭션<br>
19.2 트랜잭션 설정 실습<br>

20장 댓글과 댓글 수에 대한 처리<br>
20.1 프로젝트수정<br>

Part 6 파일 업로드 처리<br>

21장 파일 업로드 방식<br>
21.1 스프링의 첨부파일을 위한 설정<br>
21.2 〈form〉 방식의 파일 업로드<br>
21.3 Ajax를 이용하는 파일 업로드<br>

22장 파일 업로드 상세 처리<br>
22.1 파일의 확장자나 크기의 사전 처리<br>
22.2 섬네일 이미지 생성<br>
22.3 업로드된 파일의 데이터 반환<br>

23장 브라우저에서 섬네일 처리<br>
23.1 〈input type='file'〉의 초기화<br>
23.2 업로드된 이미지 처리<br>

24장 첨부파일의 다운로드 혹은 원본 보여주기<br>
24.1 첨부파일의 다운로드<br>
24.2 원본 이미지 보여주기<br>
24.3 첨부파일 삭제<br>

25장 프로젝트의 첨부파일 - 등록<br>
25.1 첨부파일 정보를 위한 준비<br>
25.2 등록을 위한 화면 처리<br>
25.3 BoardController, BoardService의 처리<br>

26장 게시물의 조회와 첨부파일<br>
26.1 BoardService와 BoardController 수정<br>
26.2 BoardController의 변경과 화면 처리<br>

27장 게시물의 삭제와 첨부파일<br>
27.1 첨부파일 삭제 처리<br>

28장 게시물의 수정과 첨부파일<br>
28.1 화면에서 첨부파일 수정<br>
28.2 서버측 게시물 수정과 첨부파일<br>

29장 잘못 업로드된 파일 삭제<br>
29.1 잘못 업로드된 파일의 정리<br>
29.2 Quartz 라이브러리 설정<br>
29.3 BoardAttachMapper 수정<br>
29.4 cron 설정과 삭제 처리<br>

Part 7 Spring Web Security를 이용한 로그인 처리<br>

30장 Spring Web Security 소개<br>
30.1 Spring Web Security의 설정<br>
30.2 시큐리티가 필요한 URI 설계<br>
30.3 인증(Authentication)과 권한부여(Authorization -인가)<br>

31장 로그인과 로그아웃 처리<br>
31.1 접근 제한 설정<br>
31.2 단순 로그인 처리<br>
31.3 커스텀 로그인 페이지<br>
31.4 CSRF(Cross-site request forgery) 공격과 토큰<br>
31.5 로그인 성공과 AuthenticationSuccessHandler<br>
31.6 로그아웃의 처리와 LogoutSuccessHandler<br>

32장 JDBC를 이용하는 간편 인증/권한 처리<br>
32.1 JDBC를 이용하기 위한 테이블 설정<br>
32.2 기존의 테이블을 이용하는 경우<br>

33장 커스텀 UserDetailsService 활용<br>
33.1 회원 도메인, 회원 Mapper 설계<br>
33.2 CustomUserDetailsService 구성<br>

34장 스프링 시큐리티를 JSP에서 사용하기<br>
34.1 JSP에서 로그인한 사용자 정보 보여주기<br>
34.2 표현식을 이용하는 동적 화면 구성<br>

35장 자동 로그인(remember-me)<br>
35.1 데이터베이스를 이용하는 자동 로그인<br>

36장 Java 설정을 이용하는 경우의 스프링 시큐리티 설정<br>
36.1 Java 설정 추가 및 동작 확인<br>
36.2 로그인 페이지 관련 설정<br>
36.3 로그아웃 처리<br>
36.4 PasswordEncoder 지정<br>
36.5 JDBC를 이용하는 Java 설정<br>
36.6 커스텀 UserDetailsService 설정<br>
36.7 자동 로그인 설정(remember-me)<br>

37장 어노테이션을 이용하는 스프링 시큐리티 설정<br>

38장 기존 프로젝트에 스프링 시큐리티 접목하기<br>
38.1 로그인 페이지 처리<br>
38.2 게시물 작성 시 스프링 시큐리티 처리<br>
38.3 게시물 조회와 로그인 처리<br>
38.4 게시물의 수정/삭제<br>
38.5 Ajax와 스프링 시큐리티 처리<br>

39장 로그아웃 처리<br>
39.1 로그아웃 페이지<br>
39.2 로그인 후 '/board/list'로 이동하기<br>
