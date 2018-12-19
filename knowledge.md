# Today I Learn

프레임워크 : 프로그램 기본 구조(spring, angular.js), 자동차 프레임 

라이브러리 : 프로그램 제작시 필요한 기능(Jquery, react), 자동차 바퀴

아키텍처: 프로그램 주요 구조 설계, 자동차 도면

플랫폼: 프로그램 실행 환경, 자동차 주행환경


# Today I Learn

npm 

Node Packeged Manager: Node.js로 만들어진 pakage(모듈)를 관리해주는 툴

Java의 Maven과 유사

필요한 라이브러리를 웹에서 검색할 필요없음


# Today I Learn

npm install -g create-react-app

create-react-app 디렉토리명

cd 디렉토리명

npm start || yarn start  //서버 켜짐

cd 디렉토리명 code . //디렉토리 vsc 열어짐


# Today I Learn

npm 모듈 설치 시 --save 붙이면 package.json에 자동 업데이트


# Today I Learn

브라우저 호환

Promise 중 es6-promise, bluebird 등이 있음


# Today I Learn

MVVM (Model View ViewModel) 패턴

v <-> vm <-> m

view(dom으로 화면 ) -> 가상dom(특정 로직을 수행) -> Model(서버 데이터를 JS객체 저장) -> 데이터바인딩(view에 모델의 데이터 동기화) -> view(사용자에게 보임)

페이스북 읽지 않은 메세지를 MVC로 하다가 복잡해져서 오류가 많이 발생하게 됨 그래서 MVVM 패턴으로 바꿈


# Today I Learn

noSQL=MongoDB


# Today I Learn

HTTP 상태코드(HTTP Response Status Code)

1XX: Informational

2XX: Success

3XX: Redirection

301(영구 이동): 요청한 페이지를 새 위치로 영구적으로 이동했다. GET 또는 HEAD 요청에 대한 응답으로 이 응답을 표시하면 요청자가 자동으로 새 위치로 전달된다./ (이전 URL) 정보를 (새로운 URL)에 승계

302(임시 이동): 현재 서버가 다른 위치의 페이지로 요청에 응답하고 있지만 요청자는 향후 요청 시 원래 위치를 계속 사용해야 한다.

4XX: client-error

5XX: server-error


# Today I Learn

javascript

undefined: 변수 선언은 되었지만, 값은 할당 받지 않은것 / 변수 자체 값 undefined

null: 변수 선언, 정의했지만, 값이 null인 것/ 객체


# Today I Learn

절대적인 크기를 정함

pt, px

상대적인 크기를 정함

rem : 최상위 요소의 크기의 배수

em: 바로 윗 상위 요소의 크기의 배수

# Today I Learn

RESTful API

REST API 규칙

1. URI는 정보의 자원을 표현

2. 자원에 대한 행위는 HTTP Method(GET, POST, PUT, DELETE 등)으로 표현

restful api 설명[https://poiemaweb.com/js-rest-api]


# Today I Learn

상태관리

-컴포넌트간 데이터 공유, 이벤트 처리를 관리하기 쉽게 구조화한것

-state: 컴포넌트간 공유될 데이터

-view: 데이터가 표현될 템플릿

-method: 사용자 입력에 반응할 메서드

예(vue-vuex, react-redux)

# Today I Learn

virtual dom

-실제 DOM의 조작을 최소화

-바뀐 부분만 업데이트

-훨신 효율적임
