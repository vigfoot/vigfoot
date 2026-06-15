# 👨‍💻 HyeonSeok Ko (VIGFOOT)
### Backend & System Architect

과잉 엔지니어링(Over-Engineering)을 경계하고 비즈니스 스케일에 가장 부합하는 **실용적인 아키텍처(Pragmatic Architecture)**를 지향하는 백엔드 엔지니어입니다. 

데이터의 정합성(Data Integrity)과 실시간 관측성(Observability)을 시스템 설계의 핵심 원칙으로 삼으며, 데이터 로딩 병목 제어, 분산 환경에서의 비동기 처리 파이프라인 구축, 그리고 순수 알고리즘 기반의 성능 극대화에 강점이 있습니다.

---

### 🚀 Technical Core Values

* **Data Integrity & DB Optimization**: REPEATABLE READ 격리 수준 하의 범위 잠금(Gap Lock) 병목을 분석하여 READ COMMITTED 최적화 및 인덱스 정밀화를 통해 데드락 발생률 0% 달성 (TPS +200%).
* **Lightweight Asynchronous Architecture**: 무거운 분산 메시지 브로커(Kafka 등) 도입 없이, Spring 내부 스케줄러 기반의 인메모리 배치 버퍼 파이프라인 설계로 인프라 비용 $0 유지 및 무중단 적재 완수.
* **High-Throughput Deduplication**: AWS S3 비동기 적재 및 고유 Idempotency Key 검증 필터 설계를 통해 4,000+ 동시성 트래픽 하에서의 안전한 트랜잭션 중복 검증 완료.
* **Algorithm-Driven Performance**: 외부 GIS 엔진에 의존하지 않고, Pure Java 기반의 경량 Ray-Casting 알고리즘을 구현하여 실시간 지오펜싱(Geofencing) 진입 검증을 sub-millisecond 단위로 가속화.
* **AI-Augmented (Harness Engineering)**: LLM(Gemini, Claude)의 추론 엔진 도입 시, 시스템 안정성을 지키기 위해 AI의 결과물을 통제 및 검증 영역 내에 가두는 하네스(Harness) 아키텍처 구축.

---

### 🛠 Tech Stack

| Category | Skills |
| :--- | :--- |
| **Backend** | `Java 17`, `Spring Boot 3.x`, `Spring Web / MVC`, `JPA / Hibernate`, `MyBatis` |
| **Database & Cache** | `MySQL`, `MariaDB`, `Redis` |
| **Infra & DevOps** | `Linux (Ubuntu/CentOS)`, `AWS (EC2, S3)`, `Docker`, `Nginx`, `Cloudflare Tunnel`, `Git / GitHub` |

---

### 🔗 Contact & Links
* **Portfolio**: [vigfoot.com](https://vigfoot.com)
* **GitHub**: [github.com/vigfoot](https://github.com/vigfoot)
