## 📅 2021/12/25

<br/>

### 🏹 주간 목표

- [ ] 클린코드를 위한 TDD with Java 13기 사다리타기 완료
- [ ] 클린코드를 위한 TDD with Java 13기 볼링 step1 진행

<br/>

### 일일 체크리스트(어제 정한 목표)

- [x] 볼링 step 1 진행

<br/>

### 💯 오늘 한 일
  
- 볼링 step 1 진행

<br/>

### 📈 내일 할 일

- 사다리 4단계 피드백 수행


<br/>

### 🧐 간단 회고

- 볼링 step 1 질문 삭제하기 기능 리팩토링
    - TDD 핵심이라고도 할수 있는 볼링 1단계는 기존 레거시 코드인 서비스코드를 TDD 방식으로 리팩토링하는 것이다.
    - 서비스레이어의 기능을 도메인으로 넘기는 것이 포인트였다.
    - 힌트중 JPA 에서 데이터를 받아오는 List 를 일급컬렉션으로 만드는 과정이 있는데 @Embedded 어노테이션을 사용해야 가능했다.
    - 과제를 진행하다보니 서비스레이어를 우선 도메인으로 옮기고 테스트 코드를 수행하는 방식으로 했었다.
    - Mock 코드가 있었기에 단계수행이 수월했다. 내일 피드백이 어떻게 올지 궁금하다
    - 철저하게 TDD 방식으로 하려면 아직 갈길이 먼것 같다.
    

- @Embedded 임베디드 타입이란?
    - 기본타입 값만 매핑하는 방식으로 객체지향적인 코드가 어려울때 사용하는 JPA 타입이다.
    - 여러 기본타입을 하나의 객체로 묶어서 값을 매핑하는 방법으로 사용된다.


  