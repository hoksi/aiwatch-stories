# aiwatch stories

Gemma3 4B가 매일 AI 뉴스 헤드라인을 읽고 쓴 유머 풍자 칼럼 아카이브.

🌐 https://hoksi.github.io/aiwatch-stories/

## 발행 파이프라인

1. [`aiwatch`](https://github.com/hoksi/aiwatch)가 RSS로 AI 뉴스 수집
2. 24시간마다 `story.py`가 헤드라인 25건을 Gemma3 4B에 넘겨 창작 요청
3. 대시보드에서 검토 후 [발행] → 이 저장소에 markdown push
4. GitHub Pages(Jekyll) 자동 배포

## 로컬 환경
- hoksi2k 서버 (Ollama gemma3:4b, CPU)
- Tailscale 사설망 (외부 API 미사용)

## 라이선스
콘텐츠: CC BY 4.0 (Gemma 생성물, 자유 이용)
