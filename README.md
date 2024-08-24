# System Architecture Playground

회사 업무를 위해 그때그때 찾아서 적용했던 기술들을  
처음부터 하나씩 정리하며 다시 구축해본다.

---

- [ ] Building K8s System
- [ ] Logging with Spring Webflux
- [ ] CI/CD
- [ ] Building APM
- [ ] OpenTracing
- [ ] Building Logging System
- [ ] Building Monitoring System
- [ ] CDC

---

### 1. Building K8s System

전체 시스템의 기반인 k8s 를 세팅한다.   
네트워크 플러그인을 고민하고 적용하여 외부 요청을 받을 수 있도록 세팅한다.

### 2. Logging with Webflux

단순한 Spring Webflux 를 만들고 Request, Response, Webclient 와 내부 로직 log 처리를 진행해본다.

### 3. CI/CD

Jenkins, github actions, Argo CD 등 CI/CD 를 비교 및 적용해본다.

### 4. Building APM

Pinpoint 또는 다른 대안이 될 수 있는 APM 도구를 찾아서 비교하고 적용해본다.

### 5. OpenTracing

Zipkin 과 같은 openTracing 도구를 찾아보고 비교한 뒤 적용해본다.   
기존 만들었던 Spring Webflux 프로젝트 외에 기본적인 다른 프로젝트도 생성하고 테스트 해본다.

### 6. Building Logging System

ELK 또는 Grafana Loki 를 비교해보고 적용해본다.   
단순 학습용이므로 비용문제가 없으니 둘다 적용해본다.

### 7. Building Monitoring System

기본적으로 알고 있는 prometheus + grafana 조합으로 구축해본다.   
혹시 다른 기술 스택이 있는지도 고려해본다.

### 8. CDC

가장 단순한 방식인 스케줄러를 이용한 CDC 는 하지 않고  
kafka connect, debezium 을 활용해보고 mysql 의 trigger 를 이용한 방식도 고려해본다.  