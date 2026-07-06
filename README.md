# genai-llm-social-welfare-note
LLM 기반 사회복지 강의 교안 학습노트 자동화 프롬프트 설계 프로젝트
## 목차

1. [LLM 모델 비교·선정 보고서](./01_model_comparison.md)
2. [시스템 설계 문서](./02_system_design.md)
3. [실행 로그](./03_execution_log.md)

## 프로젝트 개요

본 프로젝트는 사회복지 강의 교안을 입력하면 LLM이 복습 및 시험 대비용 학습노트를 자동 생성하도록 프롬프트 시스템을 설계한 과제이다.

주요 검증 내용은 다음과 같다.

- Gemini 3 Flash, Claude Haiku 4.5, GPT-5.5 비교
- 최종 모델 Claude Haiku 4.5 선정
- 사회복지 강의 교안 기반 학습노트 자동화 시스템 설계
- 10턴 이상 실제 대화 로그 기반 문맥 유지 및 환각 검증

## 파일 구성

| 파일명 | 내용 |
|---|---|
| README.md | 프로젝트 소개 및 목차 |
| 01_model_comparison.md | LLM 모델 비교·선정 보고서 |
| 02_system_design.md | 시스템 설계 문서 |
| 03_execution_log.md | 실행 로그 및 환각 검증 기록 |
