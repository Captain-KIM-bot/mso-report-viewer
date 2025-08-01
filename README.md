# MSO 리포트 뷰어

## 이 리포지토리 구조
- `index.html`: UI 및 iframe 로딩 스크립트
- `data.js`: 병원/지점/연월별 Google Sheets URL 관리
- `style.css`: 반응형 UI 스타일

## URL 업데이트 방법
1. `data.js`에서 병원 > 지점 > 연월 블록을 찾습니다.
2. 원하는 연월에 `"YYYY": "구글 시트 pubhtml URL"` 형식으로 URL을 추가하세요.
3. GitHub에 커밋하고 푸시하면 자동 반영됩니다.
