# EchoTalk 오늘의 레슨 피드

[EchoTalk](https://github.com/kth161091-ui/echo-talk) 앱의 "오늘의 레슨" 데이터 저장소.

- `feed.json` — 앱이 읽는 레슨 목록 (최신순)
- `lessons/*.json` — 레슨 정의 (문장·타임스탬프·스트리밍 URL). 오디오 파일은 호스팅하지 않으며, 앱이 archive.org 등 원 소스에서 직접 스트리밍한다
- `state.json`, `cache/` — 일일 생성 파이프라인의 작업 상태 (레슨 생성 도구: echo-talk 저장소의 `tool/generate_daily_lesson.dart`)

## 콘텐츠 원칙

이 저장소에는 **퍼블릭 도메인 또는 상업적 이용이 허용된 CC 라이선스 콘텐츠의 메타데이터만** 등록한다.
저작권물(미드, 상업 영화, 유료 콘텐츠)은 어떤 형태로도 등록하지 않는다.
각 레슨의 `source` 필드에 출처와 라이선스 근거를 명시한다.
