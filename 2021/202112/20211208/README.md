## 📅 2021/12/08

<br/>

### 🏹 주간 목표

- [ ] 클린코드를 위한 TDD with Java 13기 로또 완료
- [ ] 클린코드를 위한 TDD with Java 13기 사다리 타기 step1 진행

<br/>

### 일일 체크리스트(어제 정한 목표)

- [x] 로또 과제 step 3 리뷰 반영

- [x] 리뷰 요청

<br/>

### 💯 오늘 한 일

- 로또 과제 step 3 진행
  - 리뷰 반영
- 리뷰 요청

<br/>

### 📈 내일 할 일
  
- 로또 과제 step 3 리뷰 반영 및 요청 (있다면)
- step 4 진행 (리뷰 없다면)


<br/>

### 🧐 간단 회고


- 로또 step 3 리뷰
  - 보너스를 Lotto 클래스에 위치한 것이 부적절하다는 리뷰를 받았다. -> 뭐 그럴수 있다고 생각한다.
  - 코드 컨벤션 -> 생성자가 정적 팩토리 메서드 앞에 작성하는 것이 정석이다!!!
  - 로또를 생성하는 부분을 디자인 패턴 중 생성 패턴을 사용해서 구현해라 -> 정적 팩토리 메서드를 사용해서 구현해야하는지 의문이다....!! -> 질문을 남겨보자
  - LottoNumber 클래스 제거 -> 로또 숫자를 일급 컬렉션으로서 로또 숫자 6개의 원소로 사용하길 바랬던것 같지만 불필요 클래스라 제거하기로 결정
  - Stream findFirst, findAny [참고링크](https://codechacha.com/ko/java8-stream-difference-findany-findfirst/)
  - 2등에 대한 테스트 코드가 누락되었다. 반영하자
  
  
  
