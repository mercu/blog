# SLO/SLI/SLA의 기본 정의

**SLA (Service Level Agreement)**
- 서비스 제공자와 고객 간의 공식적인 계약
- 서비스 수준에 대한 법적 약속
- 위반 시 보상이나 벌금 조항 포함
- 예: "월 99.9% 가용성 보장, 위반시 크레딧 제공"

**SLO (Service Level Objective)**
- 서비스 품질에 대한 내부 목표치
- SLA보다 더 엄격한 기준 설정
- 예: "월 99.95% 가용성 목표" (SLA가 99.9%인 경우)
- 오류 예산(Error Budget) 계산의 기준

**SLI (Service Level Indicator)**
- 서비스 수준을 측정하는 실제 메트릭
- SLO 달성 여부를 판단하는 정량적 지표
- 예:
  - 가용성 = 성공적인 요청 수 / 전체 요청 수
  - 지연시간 = 요청의 95퍼센타일 응답시간
