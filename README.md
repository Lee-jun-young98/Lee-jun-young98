# 이준영 · Junyoung Lee

**AI Engineer | LLM Agent · AI Platform · Computer Vision**

모델 개발부터 API 연동, 배포와 운영까지 이어지는 AI 서비스를 만듭니다.  
영상 인식 서비스와 Kubernetes 기반 AI 플랫폼을 개발해 왔고, 현재는 LLM Agent의 설계와 구현을 진행하고 있습니다.

## 실무에서 해온 일

- **Computer Vision** — 객체 탐지·분할, 실시간 영상 처리, 이미지 임베딩과 유사도 검색. 모델 개발부터 서비스 연동·배포·유지보수까지 경험했습니다.
- **AI Platform** — LLM·Embedding·Reranker의 학습·서빙 환경과 LoRA 학습·평가·모델 등록 파이프라인을 개발하고 GPU 인프라를 운영했습니다.
- **운영 안정성** — 학습 코드와 Kubernetes Job/Pod 상태를 함께 확인하는 상태 판정 로직을 구현하고, 서비스 로그와 사용자 피드백으로 검색·응답 흐름을 개선했습니다.

## 현재 만들고 있는 것

**LLM Agent · 설계 및 구현 진행 중**

사용자 요청을 Planning → Dispatch → Retrieval → Verify 단계로 연결하는 구조를 개발하고 있습니다.

- 서비스 시나리오 정의, 개발·검증용 데이터 생성, 아키텍처 설계 및 구현
- LangGraph·ReAct 기반 실행 흐름과 코드 검색·저장소 도구 연동
- 사용자 승인(HITL), 세션 상태 관리, 도구 반복 호출 한도 적용

## 공개 프로젝트와 기록

실무에서 다룬 주제를 개인 학습용 예제와 기술 노트로 정리합니다. 아래 저장소는 공개용 실습 프로젝트입니다.

| 프로젝트 | 다루는 내용 |
| --- | --- |
| [Agent RAG Evaluation Lab](https://github.com/Lee-jun-young98/agent-rag-evaluation-lab) | 코드 검색, 라우팅, 모의 PR 리뷰, 검색 평가를 작은 예제로 실습 |
| [Production AI Performance Lab](https://github.com/Lee-jun-young98/production-ai-performance-lab) | 합성 벤치마크로 RAG 지연 시간, 배칭, TTFT 분석 |
| [LLM SFT Training Lab](https://github.com/Lee-jun-young98/llm-sft-training-lab) | 경량 QA 예제로 전처리·학습·평가·결과 저장 흐름 학습 |

[기술 블로그 · 포트폴리오](https://lee-jun-young98.github.io) · [Agent 라이브러리 학습 노트](https://lee-jun-young98.github.io/libraries/)

## 관심과 학습 방향

Agent의 도구 사용과 검증, 안정적인 모델 서빙, 시각 인식을 실제 행동으로 연결하는 Embodied AI에 관심이 있습니다.  
로봇 학습과 VLA는 작은 실험을 통해 기초를 쌓는 단계입니다.

**주요 기술** · Python, PyTorch, FastAPI, Docker, Kubernetes, Airflow, vLLM, LangGraph, OpenCV
