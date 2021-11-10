# springMVC1
[백엔드 웹 개발 공부](https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81-mvc-1/dashboard) <- 강의 링크

유료강의라 노트에 모든 내용을 공개하진 않을 예정.
코드는 [master](https://github.com/lucie-y/springMVC1/tree/master) 브랜치에!

SECTION 1 ) 웹 애플리케이션 이해 [NOTE](https://lucie-ko.notion.site/SECTION-1-b936f3e7c95042dda72fca52e1176c90)
- 웹 서버, 웹 애플리케이션 서버
- 서블릿
- 동시 요청 - 멀티 쓰레드
- HTML, HTTP API, CSR, SSR
- 자바 백엔드 웹 기술 역사

SECTION 2 ) 서블릿 [NOTE](https://lucie-ko.notion.site/SECTION-2-747fd83c457640bcb5cf0d77b33d3e1d)
- 프로젝트 생성
- Hello 서블릿
- HttpServletRequest 
- HTTP 요청 데이터 - GET 쿼리 파라미터, POST HTML Form, API 메시지 바디 (단순 텍스트, JSON)
- HttpServletResponse
- HTTP 응답 데이터 - 단순 텍스트, HTML, API JSON

SECTION 3) 서블릿, JSP 그리고 MVC 패턴 [NOTE](https://lucie-ko.notion.site/SECTION-3-JSP-MVC-5b4af0b91bf242dd825e5994cbc4b0ec)
- 회원 관리 웹 애플리케이션 요구사항
- 서블릿으로 회원 관리 웹 애플리케이션 만들기
- JSP로 회원 관리 웹 애플리케이션 만들기
- MVC 패턴 - 개요, 적용, 한계

SECTION 4) MVC 프레임워크 만들기 [NOTE](https://lucie-ko.notion.site/SECTION-4-MVC-56d03048563643fbb82fe62446337065)
- 프론트 컨트롤러 도입 - v1
- View 분리 - v2
- Model 추가 - v3
- 단순하고 실용적인 컨트롤러 - v4
- 유연한 컨트롤러1 - v5
- 유연한 컨트롤러2 - v5

SECTION 5) 스프링 MVC - 구조 이해 [NOTE](https://lucie-ko.notion.site/SECTION-5-MVC-19d5a14c8c52461d95502f25ee60403c)
- 스프링 MVC 전체 구조
- 핸들러 매핑과 핸들러 어댑터
- 뷰 리졸버
- 스프링 MVC - 시작하기
- 스프링 MVC - 컨트롤러 통합
- 스프링 MVC - 실용적인 방식

SECTION 6) 스프링 MVC - 기본 기능 [NOTE](https://lucie-ko.notion.site/SECTION-6-MVC-d79c81630edc475dbf0becab5dccab17)
- [프로젝트 생성](https://github.com/lucie-y/springMVC-welcome)
- 로깅 간단히 알아보기
- 요청 매핑
- 요청 매핑 - API 예시
- HTTP 요청 - 기본, 헤더 조회
- HTTP 요청 파라미터 - 쿼리 파라미터, HTML Form
- HTTP 요청 파라미터 - @RequestParam
- HTTP 요청 파라미터 - @ModelAttribute
- HTTP 요청 메시지 - 단순 텍스트
- HTTP 요청 메시지 - JSON
- 응답 - 정적 리소스, 뷰 템플릿
- HTTP 응답 - HTTP API, 메시지 바디에 직접 입력
- HTTP 메시지 컨버터
- 요청 매핑 헨들러 어뎁터 구조
