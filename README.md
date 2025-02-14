# Fortify
## Fotify 란?
#### Fortify는 애플리케이션 보안 테스트(AST) 솔루션입니다. 소스 코드 분석 및 보안 취약점 검출을 목적으로 사용되며, 정적 및 동적 분석을 지원합니다. Fortify on Deamnd Trial버전을 사용하여 SAST 정적 코드 분석을 진행해 보겠습니다.
- ### Fortify를 활용한 동적 분석 (DAST, Dynamic Application Security Testing)
  #### 기존 웹 보안 학습을 위한 Spring Boot 코드를 통한 검사 실시 예시.
  ![image](https://github.com/user-attachments/assets/4d2971a5-4eaf-452d-a5ff-b820eaa81c2d)
  ![image](https://github.com/user-attachments/assets/0e6d3b0a-f16b-4856-9290-6cfc7355af69)
  #### 취약점에 대한 코멘트 작성 후
  ![코멘트](https://github.com/user-attachments/assets/dadcde1b-f957-476e-9f5a-d241c68c6306)
  #### 보고서 템플릿 지정 후 출력
  ![리포트 유형](https://github.com/user-attachments/assets/155b5c59-e528-41f5-870b-f3c9ce20e9eb)
  ```
  FISMA Compliance
  미국 연방 정보 보안 관리법(FISMA) 기준에 따른 보안 규정 준수 여부를 평가하는 보고서

  PCI DSS Compliance (버전별 2.0~4.0, SSF 1.2 포함)
  **PCI DSS(Payment Card Industry Data Security Standard)**는 카드 결제 시스템 보안을 위한 표준
  버전별로 보안 요구사항이 다르며, 각 버전에 맞는 준수 여부를 확인하는 리포트

  STIG Compliance (4.11, 5.1, 5.2, 5.3)
  **STIG(Security Technical Implementation Guide)**는 미국 국방부(DoD)에서 정의한 보안 가이드라인
  버전별 보안 정책을 준수하는지 평가

  Hybrid Comprehensive
  정적 & 동적 분석 결과를 종합하여 전체적인 보안 상태를 평가

  Hybrid Issue Detail
  발견된 보안 문제(취약점)에 대한 세부 정보를 제공

  Hybrid Summary
  하이브리드 분석 결과를 요약하여 제공하는 보고서

  Static Analysis Trace
  취약점이 발견된 코드 실행 경로(Trace)를 상세하게 보여주는 리포트
  어떤 입력값이 보안 문제를 유발했는지 추적 가능

  Static Comprehensive
  정적 분석 결과를 포괄적으로 제공하는 보고서
  코드의 전체 보안 상태를 평가

  Static Issue Detail
  정적 분석에서 발견된 보안 문제를 개별적으로 상세하게 제공

  Static Summary
  정적 분석 결과를 요약하여 제공하는 보고서
  전반적인 취약점 개수 및 심각도 등을 포함
  ```


