## 📅 2022/05/14

<br/>

### 🏹 주간 목표

- [ ] 이력서 지원
- [ ] stock 토이 프로젝트 데이터 파싱하기
- [x] MySQL 스터디 이번주 분량 학습
- [x] 스프링 원리 학습 및 정리
- [x] queryDSL 학습


<br/>

### 일일 체크리스트(어제 정한 목표)

- [ ] 스프링 학습
- [x] MySQL 격리레벨 테스트

<br/>

### 💯 오늘 한 일

- MySQL 격리레벨 테스트

<br/>

### 📈 내일 할 일

- 스프링 학습
- stock 토이프로젝트
- MySQL 테스트

<br/>

### 🧐 간단 회고

- Mysql 격리 레벨 테스트를 진행했다.
  - 각 격리레벨 별로 update 한 데이터를 읽었을때 결과를 확인하는 테스트를 수행했으며
  - Read Uncommitted 인 유저가 레벨로 조회시 row lock 이 걸려있는 데이터를 읽었을때 과거 데이터가 나올것인가를 추가적으로 테스트했다.
  - 질문에 답을 하기 위해 내일 row lock 을 좀더 장기적으로 할 수 있는 방법이 있는지, 없다면 uncommitted 레벨에서 읽었을때 undo log 에서 과연 절대 안읽는지를 좀더 확인해봐야 할 것 같다.
  
