## 📅 2022/05/12

<br/>

### 🏹 주간 목표

- [ ] 이력서 지원
- [ ] stock 토이 프로젝트 데이터 파싱하기
- [ ] MySQL 스터디 이번주 분량 학습
- [ ] 스프링 원리 학습 및 정리
- [ ] queryDSL 학습


<br/>

### 일일 체크리스트(어제 정한 목표)

- [x] 스프링 학습
- [x] MySQL 읽기

<br/>

### 💯 오늘 한 일

- 스프링 학습
- MySQL 읽기
- queryDSL 설정 및 흐름 파악하기
- 운영체제 공부 훑어보기

<br/>

### 📈 내일 할 일

- 스프링 학습
- MySQL 격리레벨 테스트

<br/>

### 🧐 간단 회고

- 스프링 원리를 이해하기 위해서는 객체 지향의 원리를 잘 파악해야한다.
    - 역할과 구현을 분리, 다형성 및 인터페이스 활용, OCP, DIP 같은 원칙을 준수 했는가?
    - 결국 좋은 객체 지향 설계를 위한 5가지 원칙을 어떻게 구성했는가가 중요하다.
    
- IoC, DI, 컨테이너
    - 스프링은 좋은 객체 지향 설계를 돕기 위해 만들어진 프레임워크이다.
    - 프로그램의 제어 흐름을 외부에서 관리하기 -> IoC
    - 외부에서 실제 구현객체를 생성하고 클라이언트에 전달해서 의존관계가 연결됨 -> DI
    - 객체를 생성하고 관리하며 의존관계를 연결해주는 존재 -> 컨테이너
    
- 자바와 스프링의 차이
    - 자바 코드로 모든것을 구현한다면 제어, 객체 관리 등을 직접해야한다면
    - 스프링은 컨테이너에 객체를 빈으로 등록하고 객체를 사용할때는 스프링 빈에서 찾아 사용하도록 변경하는 것이다.
    

- MySQL 스터디 질문에 대한 답을 찾기 위해 다시 읽어보았다.
    - row 단위로 락이 걸렸을때 (Read-Uncommitted 레벨이라면 안걸릴거 같지만..) 격리 레벨상관없이 다른 클라이언트에서 조회시 변경된 사항이 조회 안되는것이 아닐까 라는 생각이 들었다.
    