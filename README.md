# 📂 Portfolio
인프라/시스템 가시성(Observability) 및 자원 메트릭 수집 전문 개발자 포트폴리오  
— Go 기반 Collector·Agent 개발, Redfish/IPMI/SNMP 모의 환경 구축, Docker/K8s 배포 자동화 경험

---

## 👤 소개
- 역할: **수집·에이전트·통합** 영역 특화 백엔드 개발자  
- 강점:
  - Go 기반 모듈형 Collector·Agent 아키텍처 설계
  - Redfish/IPMI/SNMP/K8s/NetApp 등 다양한 인프라 메트릭 수집
  - Docker/Kubernetes/Ansible을 통한 배포 및 운영 자동화
  - 멀티 환경(dev/stg/prd) 운영 경험
- 목표: **“실사용 가능한 메트릭 수집 플랫폼 + 운영 자동화”**를 구축하고 발전시키는 것

---

## 🛠️ 스킬 요약
- **언어/런타임**: Go(주력), Python(모의 서버/툴)
- **백엔드 프레임워크**: Gin(Golang), GORM(DB ORM)
- **인프라/배포**: Docker, docker-compose, Kubernetes, Ansible
- **프로토콜/도메인**: Redfish, IPMI, SNMP, NetApp API, Kubernetes API
- **데이터/운영**: RDBMS(MySQL/Postgres), 로그 관리, 환경 분리(dev/stg/prd)
- **CI/CD 경험**: GitHub Actions 기반 테스트/빌드/도커 이미지 배포

---

## 🚀 대표 프로젝트

### 1. baton-ao-collector (2025)
- **내용**: Collector + API 런타임 템플릿
- **스택**: Go(Gin, GORM), DB, 로깅
- **특징**:
  - 설정 → DB 연결 → Collector 실행 → REST API까지 원패스 부팅 구조
  - 향후 다양한 Collector(운영체제/K8s/NetApp) 적용 가능
- **실행 예시**:
  ```bash
  go run main.go
  curl http://localhost:8080/healthz

