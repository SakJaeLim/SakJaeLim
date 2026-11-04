# 임석제 / Seokje Lim

공공기관의 정보화 전략과 데이터 활용을 다루는 IT 컨설턴트입니다. 현장에서 마주친 문제를 바탕으로, AI의 실행 과정과 결과를 사람이 확인할 수 있는 도구를 만들고 있습니다.

ISP와 ISMP, 공공데이터 개방과 활용체계 수립 업무를 해왔으며, 현재 aSSIST AI융합공학 박사과정에서 연구하고 있습니다. 기업 AI 교육과 실습 지원, AI 활용 경진대회 평가, 산업수요형 PBL 과정기획위원회 활동에도 참여했습니다.

I work on public-sector information strategy and data use, and build tools that make AI actions and results easier to review. I am pursuing a PhD in AI Convergence Engineering at aSSIST. My work also includes corporate AI training, AI competition judging, and industry-oriented PBL curriculum planning.

## Selected work

### [Ontology Review](https://github.com/SakJaeLim/ontology-review)

데이터의 설명이 바뀌면 이전 검토 결과도 다시 확인해야 합니다. NVIDIA Auto Ontology 형식의 데이터 사전을 가져와 Microsoft Ontology Playground 편집기에서 설명을 수정하고, 보존된 원문과 비교해 검토하는 로컬 작업 공간을 개발했습니다. 승인 뒤 내용을 다시 수정하면 기존 이력은 남고 현재 내용은 재검토 대상으로 바뀝니다.

A local workspace for importing NVIDIA Auto Ontology dictionaries, editing descriptions in Microsoft Ontology Playground, and reviewing changes against the preserved source. Later edits require a new review while keeping earlier decisions in history.

[![Ontology Review comparing the original and edited definition](https://raw.githubusercontent.com/SakJaeLim/ontology-review/b5b1d8ecfdb015385c2b0aa07bc171e2fba775dc/assets/standalone-review.png)](https://github.com/SakJaeLim/ontology-review/blob/main/CONNECTION.md)

[실행 안내 / Run locally](https://github.com/SakJaeLim/ontology-review/blob/main/CONNECTION.md)  
[실제 화면으로 구성한 20초 시연 / Captured-state walkthrough](https://github.com/SakJaeLim/ontology-review/blob/main/assets/connection-walkthrough.mp4)

<sub>The review engine and workbench are maintained in this independent project. The visual editor comes from <a href="https://github.com/microsoft/Ontology-Playground">Microsoft Ontology Playground</a>; the dictionary format comes from <a href="https://github.com/NVIDIA/auto-ontology">NVIDIA Auto Ontology</a>. <a href="https://github.com/SakJaeLim/ontology-review/blob/main/PROVENANCE.md">Contribution map and development history</a>.</sub>

### [TrustFlow MCP](https://github.com/SakJaeLim/trustflow-mcp-data-agent)

팀 프로젝트로 개발한 데이터 에이전트입니다. 조회 계획을 실행 전에 검사하고, 결과에 근거와 감사기록을 연결합니다. 공개 데모에서는 가상 데이터로 정상 조회, 조회 범위 보정, 민감정보 승인 대기, 삭제 요청 차단을 재현할 수 있습니다.

A team project that checks data query plans before execution and connects results to evidence and audit records. The public demo uses synthetic data to demonstrate query limits, approval requirements, blocked deletion, and audit tamper detection.

[공개 데모 / Public demo](https://github.com/SakJaeLim/trustflow-mcp-data-agent/blob/main/docs/PUBLIC_DEMO.md)  
TypeScript, PostgreSQL, pgvector, MCP

### [PaperOps](https://github.com/SakJaeLim/paperops)

연구자료의 출처와 근거를 정리하고, 원고에서 추가 확인이 필요한 주장과 수치를 찾는 도구입니다. 원고 변경은 미리 확인한 뒤 적용하며, 근거의 검증 완료 상태는 사람이 명시적으로 확인한 경우에만 기록합니다.

Organizes research evidence, flags claims and numbers for review, and previews manuscript changes before applying them. Evidence verification requires an explicit human attestation.

[공개 데모 / Public demo](https://github.com/SakJaeLim/paperops/blob/main/docs/PUBLIC_DEMO.md)  
Python, SQLite

## Other work

- [filename-rescue](https://github.com/SakJaeLim/filename-rescue): 깨진 한글 파일명을 미리 확인하고 복구하는 Windows 도구. A Windows utility for previewing and repairing decomposed Korean filenames.
- [PortSLM](https://huggingface.co/AICPADSLIM/PortSLM-Qwen2.5-VL-3B-v2): 항만 분야에 맞춰 Qwen2.5-VL-3B를 파인튜닝한 팀 프로젝트. A team project adapting a vision-language model to the port domain.

## Contact

[LinkedIn](https://www.linkedin.com/in/seok-jae-l-772836b5/)  
[Hugging Face](https://huggingface.co/AICPADSLIM)  
[lim.aicpa.ds@stud.assist.ac.kr](mailto:lim.aicpa.ds@stud.assist.ac.kr)

<sub>Projects use AI-assisted development. Each repository documents what is implemented, how to reproduce it, and its current limits.</sub>
