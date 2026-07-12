# webtoon

Claude Code 웹툰 제작 파이프라인으로 만든 웹툰 릴리스 저장소입니다.

## 작품 목록

- **최약체의 귀환** — 시즌1 · EP01~EP05

## 보기

GitHub Pages: https://hslim11.github.io/webtoon/

로컬에서 보려면 `docs/` 디렉토리를 정적 서버로 띄우세요.

```bash
python3 -m http.server 8080 -d docs/
open http://localhost:8080
```

## 구조

```
docs/
  index.html              # 작품 목록 랜딩 페이지
  최약체의 귀환/
    EP01/ ~ EP05/
      index.html           # 세로 스크롤 뷰어(패널 in-image 베이크)
      cover.png             # 표지(첫 패널 썸네일)
      panels/                # 패널 PNG
      qa_report.md           # 품질 검수 보고서
      RELEASE_NOTES.md       # 사인오프·회차 요약·다음 화 시드
```
