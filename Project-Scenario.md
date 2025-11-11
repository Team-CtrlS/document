## Team 17 CtrlS
|항목|내용|
|---|---|
|프로젝트명|난독 아동의 소리 내어 읽기 개선을 위한, 음성 인식 기반 읽기 오류 패턴 분석과 맞춤형 동화책 생성을 활용한 학습 시스템|
|프로젝트 키워드|음성 인식 기반 읽기 오류 분석, 텍스트 적응형 생성, 맞춤형 동화책 & 피드백 학습 시스템|
|트랙|산학|
|프로젝트 멤버|정유진, 정윤아, 복지희|
|팀 지도교수|윤명국 교수님|
|무엇을 만들고자 하는가|아이의 관심사 키워드와 음성 입력을 기반으로 맞춤형 동화책 텍스트와 삽화를 생성한다.<br>낭독 과정에서는 발음 오류, 읽기 속도, 자주 틀리는 단어를 분석하여 개인 맞춤형 피드백을 제공한다.<br>또한 난독 아동에게 적합한 어휘 난이도 조절과 문장 구조 제어 기능을 갖춘 적응형 학습 알고리즘을 구현한다.<br>이를 통해 아이의 읽기 자신감과 학습 효율을 높이는 것을 목표로 한다.|
|고객|**김민서 (8세, 초등학교 2학년)**<br>- 특성: 난독증 진단을 받아 글자를 읽을 때 자주 틀리고 속도가 느려져 읽기에 대한 자신감이 떨어짐.<br>- 요구: 자신이 좋아하는 주제(동물, 모험 등)로 된 동화를 쉽게 읽고 싶고, 틀린 발음을 교정받고 싶음.<br><br>**박소영 (38세, 초등학교 교사)**<br>- 특성: 학급 내 난독 아동을 개별적으로 지도할 시간이 부족함.<br>- 요구: 아이의 읽기 오류 패턴과 학습 진행 상황을 시각적으로 확인할 수 있고, 자동으로 난이도가 조절된 읽기 자료를 제공받고 싶음.|
|Pain Point|- 난독 아동은 기존 교재로 학습할 때 읽기 속도 저하, 빈번한 오류, 낮은 자신감 문제를 겪음.<br>- 교사는 개별 피드백과 수준별 자료 제공에 많은 시간이 소요됨.<br>- 학부모는 아이의 읽기 수준과 학습 진척도를 객관적으로 확인하기 어려워, 가정에서 효과적인 지원이 힘듦.|
|사용할 소프트웨어 패키지의 명칭과 핵심기능/용도, 사용 시나리오|**[Frontend]** <br>Swift : 모바일 앱 UI/UX 개발, 동화책 뷰어 및 읽기 훈련 인터페이스 제공<br><br> **[Backend]** <br>Spring Boot : REST API 서버 구축, 사용자 관리·학습 데이터 저장<br>FastAPI : STT/LLM 모듈 연동, 적응형 알고리즘 처리<br><br> **[협업 툴]** <br>Git/GitHub : 소스 코드 버전 관리<br>Figma : UI 프로토타입 제작<br>Notion : 문서 및 일정 관리<br>Discord : 팀 커뮤니케이션<br><br> **[AI / API]** <br>Whisper : 아이의 낭독 음성 인식 및 전사<br>KoNLPy/형태소 분석기 : 한국어 문장 난이도 제어, 어휘 분석<br>Stable Diffusion API : 삽화 이미지 생성<br>TTS (Coqui TTS/Piper) : 동화 오디오북 기능 제공<br>LLM(OpenAI GPT 계열) : 아이 수준에 맞는 동화 문장 생성 및 질문 대화 제공<br>Adaptive Learning Engine(직접 구현) : 학습 데이터 기반 난이도 조절 및 피드백|
|사용할 소프트웨어 패키지의 명칭과 URL|Whisper: https://openai.com/index/whisper <br>KoNLPy: https://konlpy.org <br>Stable Diffusion: https://stability.ai <br>Coqui TTS: https://coqui.ai <br>OpenAI GPT: https://openai.com/ko-KR/index/openai-api/|
|팀 그라운드룰|[GitHub Ground Rule](https://github.com/Team-CtrlS/document/blob/main/GroudRule.md)|
|최종 수정일|2025-10-03|
