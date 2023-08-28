# 📚 MongoDB 스터디

### 모티브
+ **자유**, **함께** 그리고 **완주**

### 멤버
+ [김민수](https://github.com/minsoozz)
+ [김의빈](https://github.com/JoeCP17)
+ [이연재](https://github.com/yyy96)
+ [민율](https://github.com/minyul)

### 진행안
- 주차별 유동 스터디 방식
- 토론시, 공부하면서 느꼈던 중요사항 질문 2~3가지 준비
- 자유로운 대화를 존중하되, 가능한 한 근거를 중심으로하여 생산적인 대화를 진행합니다 

### 정리

|No. <img width=150/>|주제 <img width=300/>| 정리 자료 <img width=300/>|
|---|---|---|
|Week 01|사전 모임| - |
|Week 02|RDB, NoSQL 차이점| <a href="https://github.com/zunior-study/mongodb-study/blob/main/%EA%B9%80%EB%AF%BC%EC%88%98/2%EC%A3%BC%EC%B0%A8.md">[김민수]</a> <a href="https://github.com/zunior-study/mongodb-study/blob/main/%EC%9D%B4%EC%97%B0%EC%9E%AC/2%EC%A3%BC%EC%B0%A8.md">[이연재]</a>|
|Week 03|MongoDB 인덱스 특징| - |
<br>

## 질문 목록

### RDB, NoSQL 차이점 (2주차)
- 관계형 데이터베이스에서 NoSQL로 데이터 저장소를 변경할 때 고려해야 할 사항
- 문서 범위 검색(document range scan)을 할 때, 범위 내에 속한 문서 중 쓰기 작업(write operation)이 진행되고 있는 문서에는 쓰기 배타적 락(write exclusive lock)이 걸리면서 읽을 때 지연이 발생하는 경우 어떤 해결 방법이 있을 수 있을까?
- Redis 를 메인 스토리지로 사용하다가 가용량이 문제가 생겼을 경우 대처할 수 있는 방법들
- 채팅 시스템에서 적합한 데이터베이스는?
- 수직 확장, 수평 확장이 무엇인가요? 어떤 차이가 있나요? 왜 각 데이터베이스가 유리하다고 생각하시나요?
- 포털 서비스를 설계할 때 RDB, NoSQL 중 어떤 데이터베이스를 사용하시겠습니까? 그 이유는 무엇인가요?
- 왜 NoSQL이 주목받고 있는가요? NoSQL의 장점과 단점은 무엇인가요?
- NoSQL이 어떻게 높은 읽기/쓰기 처리량을 보장할 수 있나요?
