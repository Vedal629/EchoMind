# KakaoPersona  
카카오톡 대화 내보내기(txt)를 기반으로 **자신의 대화 성향을 분석하고 빅파이브 성격 지표를 탐색적으로 추정**하는 프로젝트입니다.  
무료 AI API (Hugging Face Inference API + Google Perspective API)를 활용합니다.

---

## 🚀 기능
- 카카오톡 대화 내보내기(txt) 파싱
- 본인 이름 입력 → 자신의 발화만 자동 추출
- 무료 AI API로 감성 분석(긍/부정/중립), 독성 점수 계산
- 어휘 다양성/자기지시어/확신·불확실 표현 등 스타일 지표 계산
- 빅파이브(Big Five: OCEAN) 성격 특성 탐색적 추정
- 결과를 **Markdown, JSON, CSV** 리포트로 저장

---