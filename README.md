# 이준영 · Junyoung Lee

**AI Engineer | AI Platform · Computer Vision · LLM Agent**

영상 인식 서비스와 AI 학습·서빙 플랫폼을 개발해 왔습니다. 모델 개발뿐 아니라 데이터 정리, API 연동, 배포 이후의 유지보수까지 맡아왔고, 현재는 LLM Agent의 설계와 구현을 진행하고 있습니다.

## AI 학습·서빙 플랫폼

- Kubernetes에서 LLM·Embedding·Reranker를 학습하고 서빙하는 환경을 개발·운영했습니다.
- Airflow로 LoRA 학습, 평가, 결과 저장, 모델 등록과 서빙을 연결하는 파이프라인을 구현했습니다.
- 학습 상태 파일과 Kubernetes Job/Pod 상태를 함께 확인해 성공·실패·진행 상태를 판정하는 로직을 구현했습니다. 학습 컨테이너와 사이드카의 상태를 구분해 완료 여부를 처리했습니다.
- RAG의 검색·리랭킹·응답 생성 흐름을 분석하고, 서비스 로그와 사용자 피드백을 바탕으로 검색과 응답을 개선했습니다.

## Computer Vision 서비스

**하수관로 결함 탐지**

데이터 정제, YOLO 기반 탐지와 후처리, FastAPI·Docker를 이용한 웹 서비스 연동·배포를 맡았습니다. 사용자에게 배포한 뒤 피드백 대응과 유지보수를 이어갔습니다.

**지능형 CCTV**

침입·배회 이벤트 탐지를 위해 데이터 라벨링·자동 라벨링과 YOLO·OpenCV 기반 영상 처리, FFmpeg 스트리밍 연계를 개발했습니다. 참여한 시스템은 KISA 지능형 CCTV 본 시험을 통과했습니다.

**이미지 검색·3D PoC**

DINOv2 이미지 임베딩과 Milvus를 연결한 유사 이미지 검색 파이프라인을 개발했습니다. 별도 PoC에서는 TRELLIS 기반 3D 복원과 GLIP·SAM을 이용한 파트 분할을 구현했습니다.

## LLM Agent · 설계 및 구현 진행 중

사용자 요청을 Planning → Dispatch → Retrieval → Verify 단계로 연결하는 기능을 개발하고 있습니다.

- 서비스 시나리오와 단계별 입출력을 정의하고, 개발·검증용 데이터를 생성하며 아키텍처를 설계·구현하고 있습니다.
- LangGraph·ReAct 기반 실행 흐름과 코드 검색·저장소 도구 연동을 구현했습니다. 사용자 승인(HITL), 세션 상태 관리, 도구 반복 호출 한도를 적용했습니다.

## 기술 기록

[기술 블로그](https://lee-jun-young98.github.io)에 개발 기록과 논문·라이브러리 학습 노트를 정리합니다.

**주요 기술** · Python, PyTorch, FastAPI, Docker, Kubernetes, Airflow, vLLM, LangGraph, OpenCV
