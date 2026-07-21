# rs-screener

코스피200 상대강도 대시보드 — 폰 브라우저에서 확인용.

- **페이지**: https://amid815.github.io/rs-screener/
- **브랜치 `main`**: 대시보드 정적 파일 (`index.html` · `app.js` · `style.css`)
- **브랜치 `data`**: `rs-latest.json`(최신 실행 결과) + `history/YYYYMMDD.json`

데이터는 배포 PC의 스크리너(`코스피200_상대강도`)가 평일 15:37 실행 끝에
`data` 브랜치로 직접 push한다. 대시보드는
`raw.githubusercontent.com/AMID815/rs-screener/data/rs-latest.json`을 fetch해 렌더링.

데이터 스키마·발행 방식은 스크리너 프로젝트의
`docs/web-data-contract.md` · `docs/웹대시보드_배포.md` 참고.
