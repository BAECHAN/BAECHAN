<body align="center">


# 소개
  ## *다양한 사람들이 편하게 사용할 수 있는 프로그램을 만들기 위해 팀원들과 토론하는 개발자*
  <br>

  ### **Front End Engineer**

  <br>

  ## 방향성
  
  ### ● 누가 읽어도 이해하기 쉽고 유지보수력을 높이기 위해 가독성 좋은 코드를 작성하려는 개발자입니다.
  ### ● 지인들과 개발에 대한 의견을 나누며 다양한 의견을 듣는 것을 좋아하며 피드백을 받고 고민하는 개발자입니다.
  ### ● 웹사이트를 어려워하시는 저희 부모님과 같이 아들한테 안물어봐도 쉽게 사용하실 수 있는 사이트를 만들고 싶어하는 개발자입니다.
  ### ● 레고와 같이 프로젝트를 작은 단위로부터 쌓아올려 완성도 있는 프로젝트를 만들고 싶어하는 개발자입니다.
  ### ● 다른 사이트들을 돌아다니며 프로젝트에 도입해보는걸 좋아하는 개발자입니다.

  <br>
  
  ## 이직하려는 이유

  저는 입사하기 전까지도 웹 개발을 모르는 상태에서 시작하였었고 솔직하게 신입 때까지는 돌아가기 위한 코드를 먼저 작성해왔었습니다.  
  이전 직장에서는 백엔드 위주의 Full Stack 개발자로 성장하고 싶었으나  
  MPA 환경에서 작업하면서 아래의 클라이언트 관련 문제들에 대해 고민을 하며 시도하던 왔었고  
  오프라인 스터디팀에서 React를 처음 공부하면서 지금껏 고민해왔던 부분들을 이미 다른 개발자들도 고민을 해왔고  
  저와 같은 고민을 했던 사람들이 사용하는 SPA 구조를 활용한 개발자가 되고 싶다는 생각이 들었으며  
  프론트엔드를 할 때가 더 즐겁게 개발을 하고있는 제 모습을 보며 Fronted 개발자로 집중하고 싶어 이직을 결심하였습니다.  
  
  ### Q. 받아온 서버데이터를 클라이언트에서 재활용하기 위한 공간을 만들 수 있을 것인가?  
    
  => input type hidden으로 숨겨서 사용하거나 / HTML Element의 data set 속성을 사용하거나 / 함수로 분리하여 변수로 관리하거나  
  등의 여러 방법은 많았지만 관리하기가 쉽지 않았고 가독성도 떨어지는 상황에서  
  Spring의 VO처럼 getter setter를 만들어서 시도해보거나 하였다.  
  
  ### Q. Function의 재사용은 많이 언급하는데 Element의 재사용은 찾아보기 어려운데 이를 위한 해결방법은?  
    
  => 파일을 따로 분리하여 JSP의 include 지시어로 함수를 실행해 동적으로 Element를 생성하는 방식을 사용했지만  
  이 경우 상품목록에서 더 보기와 같이 상품이 추가되어도 기존의 상품목록 Element들에 대한 이벤트 핸들러를 다시 부착해주거나  
  이벤트위임을 이용하여 상위요소에 이벤트 핸들러를 부착하여 하위요소에도 이벤트가 실행될 수 있도록 처리하였다.  
  또는 이벤트 핸들러를 부착하는 방법으로 Web API인 Mutation Observer를 사용하여  
  DOM트리가 추가됨을 감지하여 이벤트 처리하는 등으로도 처리하였다.  
  
<br>

***
# 프로필
  ### 이름 : 배찬
  ### 생년월일 : 1994-03-15
  ### 연락처 : 010-4294-1966
  ### 지역 : 서울
  ### Github : https://github.com/BAECHAN
  ### Github_ToyProject : https://github.com/BAECHAN/lego_front
  ### Github_ToyProject_진행과정 : https://github.com/BAECHAN/lego_front/blob/main/HISTORY.md
  ### ToyProject_서버 : https://port-0-lego-front-nx562olfs8ljco.sel3.cloudtype.app/

<br>

***
# 기술 스택

<div>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white">&nbsp; 
  <p>
    Element들의 구조와 역할을 이해하며, 각 Element에 대한 속성을 활용할 줄 알고 있습니다.<br>
    다른 사이트의 디자인을 따라 레이아웃을 그릴 수 있으며, 시각장애인분들을 위해 웹접근성을 준수하며 HTML을 작성하려고 합니다.
  </p>
</div>
<div>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>&nbsp;
  <p>
    CSS 속성을 이해하고 사용하며,  이에 따라 width,height,margin,padding을 설정가능하며<br>
    레이아웃을 위해 float나 postion, flex 정도 사용할 수 있습니다. 또한 간단한 transition이나 animation을 사용할 수 있습니다.<br>
    grid의 경우 jquery 기반의 라이브러리나 실습 정도는 해보았지만 잘 다루지는 못합니다.
  </p>
</div>
<div>
  <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=white"/>&nbsp; 
  <p>
    기본적인 javascript 문법들을 숙지하고 있으며 라이브러리 없이 Vanilla JS로 DOM을 조작하거나 이벤트핸들링이 가능합니다.<br>
    XHR, fetch, axios 등으로 비동기 처리를 할 수 있으며, ES5뿐만 아니라 ES6 이상의 주요 문법들도 다루고 있습니다.</br>
    some이나 reduce등의 고차함수를 활용하여 로직을 구현할 줄 알고있습니다.
  </p>
</div>
<div>
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/>
  <p>
    Vanilla Javascript로 구현한 로직을 jQuery로 전환할 줄 알며, 역으로도 가능합니다.<br>
    또한 일부 테이블이나 차트 관련된 jQuery 라이브러리들을 사용해본 적이 있으며 Ajax를 사용하여 비동기 요청을 다룰 수 있습니다.
  </p>
</div>

<br>

<div>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/ReactQuery-FF4154?style=flat-square&logo=ReactQuery&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=Redux&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/Recoil-3578E5?style=flat-square&logo=Recoil&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/NextJS-000000?style=flat-square&logo=Next.js&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/Typescript-2962FF?style=flat-square&logo=typescript&logoColor=white"/>&nbsp; 
</div>

<div>
  <img src="https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=Sass&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/StyledComponents-DB7093?style=flat-square&logo=StyledComponents&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/FontAwesome-528DD7?style=flat-square&logo=FontAwesome&logoColor=white"/>&nbsp;
</div>

<div>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=Github&logoColor=white"/>&nbsp;
</div>

<br />

***
# 경력
  ### 회사명 : 미소테크(주)
  ### 재직기간 : 2020-03 ~ 2022-12 ( 2년 10개월 )
  ### 직급 : 사원
  ### 업무 : 논문/특허/학술지 관련 혹은 기업 재무 데이터 관련 통계 SI / SM
  ### 포지션 : Full Stack Engineer
  ### 프로젝트 업무 관련
  ### DB설계 후 서버를 통해 클라이언트로 API를 전달하여 데이터 통계 및 시각화 하여 화면에 보여주는 업무를 주로 진행하였습니다. 


<br>

***
# 프로젝트
<table align="center">
  <thead>
    <th>기간</th>
    <th>프로젝트 이름</th>
    <th>프로젝트 설명</th>
    <th>프로젝트 타입</th>
    <th>프로젝트 기술스택</th>
    <th>개인/사업</th>
  </thead>
  <tbody>
    <tr>
      <td>2020-03 ~ 2020-12</td>
      <td>NDSL</td>
      <td>국내 학술지 논문 검색</td>
      <td>SM</td>
      <td>Java / Spring / Oracle / jQuery / HTML5 / CSS3 / Javascript</td>
      <td>미소테크</td>
    </tr>
    <tr>
      <td>2021-01 ~ 2022-12</td>
      <td>RndPie</td>
      <td>국가연구개발 투자분석 시스템</td>
      <td>SI/SM</td>
      <td>Java / Spring / Oracle / jQuery / HTML5 / CSS3 / Javascript</td>
      <td>미소테크</td>
    </tr>
    <tr>
      <td>2021-09 ~ 2022-12</td>
      <td>중개연구플랫폼</td>
      <td>국가연구개발 중개연구분야 분석</td>
      <td>SI/SM</td>
      <td>Java / Spring / Oracle / jQuery / HTML5 / CSS3 / Javascript</td>
      <td>미소테크</td>
    </tr>
    <tr>
      <td>2021-12 ~ 2022-12</td>
      <td>한국과학기술한림원</td>
      <td>과학기술석학 디지털 아카이브 플랫폼 개발</td>
      <td>SI/SM</td>
      <td>Java / Spring / Mysql / jQuery / HTML5 / CSS3 / Javascript</td>
      <td>미소테크</td>
    </tr>
    <tr>
      <td>2022-10 ~ </td>
      <td>토이프로젝트-레고사이트</td>
      <td>포트폴리오 제출용 개인프로젝트</td>
      <td>포트폴리오</td>
      <td>React / Next.js / React-query / Recoil / Typescript / Java / Spring Boot / MariaDB</td>
      <td>개인</td>
    </tr>
  </tbody>
</table>
<br>

***
# 학교
  ### 학력 : 서울 환일고등학교 졸업
  ### 최종학력 : 명지대학교 학사졸업
  ### 재학기간 : 2013-03 ~ 2020-02
  ### 전공 : 정보통신공학과
<br>

***
# 자격증
  ### 자격증 : 정보처리기사 
  ### 취득기간 : 2019-12

</body>
