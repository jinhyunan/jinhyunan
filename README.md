# Jinhyun An — Industrial AI / Data Engineering

> 13 years designing power-plant systems on EPC mega-projects — now building
> the AI/data systems that make construction projects measurable.
>
> 발전플랜트 EPC 13년(사우디·방글라데시·베트남 복합화력 시스템 설계, 벤더
> 기술평가, 현장 엔지니어링) 위에, 지난 2년간 LLM 에이전트 런타임과 엔지니어링
> 계산의 AI 도구화를 직접 설계·구현해 왔습니다.

**Principle: tools over tokens** — 숫자는 결정론적 코드가 계산하고, LLM은
근거를 연결하고 설명합니다. 오류 허용치가 낮은 산업 도메인에서 신뢰할 수 있는
AI의 유일한 형태라고 믿습니다.

## Projects

| | |
|---|---|
| **[permit-delay-risk-chicago](https://github.com/jinhyunan/permit-delay-risk-chicago)** 🏗️ | Flagship. 시카고 건축허가 22.7만 건으로 "착공 전 readiness 마찰"을 예측 — DuckDB 적재 → 누수차단 피처(테스트로 강제) → LightGBM + SHAP → 결정론적 도구 기반 진단 에이전트 → 리스크 카드. 시간분할 검증과 정직한 부정적 결과 보고 포함 |
| **[ccpptools-mcp](https://github.com/jinhyunan/ccpptools-mcp)** ⚙️ | 복합화력발전소 배관/펌프 계산을 검증 가능한 Python + MCP 도구로 재구성. Excel cell-replay 테스트로 원 계산서와 결과를 고정 (ASME · Crane TP-410) |
| **[watt-agent](https://github.com/jinhyunan/watt-agent)** 🤖 | 외부 패키지 설치가 불가능한 폐쇄망을 위한 stdlib-only LLM 에이전트 런타임 — tool-calling 루프, 서브에이전트, 컨텍스트 압축, 문서생성 파이프라인 |
| **[lane-departure-warning-rebuild](https://github.com/jinhyunan/lane-departure-warning-rebuild)** 🛣️ | 2013 학부논문 차선이탈경보 알고리즘을 PDF 부록 코드에서 복원하고 근거 기반으로 현대화 — golden-frame 평가, 제어상태 분리, 게이트 뒤의 ML. [4패널 비교 프레젠테이션](https://jinhyun-an.dev/ldw/) |

**Portfolio site**: [jinhyun-an.dev](https://jinhyun-an.dev) · **Contact**: jinhyun.an.ai@gmail.com
