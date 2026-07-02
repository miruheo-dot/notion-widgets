# notion-widgets

Notion 대시보드에 임베드하는 커스텀 위젯 모음.

## gauge.html — 분기 진행률 게이지바

VOC 분석 대시보드(Notion)의 분기별 프로젝트 진행률 시각화.

- 임베드 URL: `https://miruheo-dot.github.io/notion-widgets/gauge.html`
- 값 변경: `values.json`의 `value`(0~100)를 수정하고 push하면 Notion에서 자동 반영
- URL 파라미터로도 가능: `gauge.html?labels=2분기,3분기,4분기&values=33,0,0`
