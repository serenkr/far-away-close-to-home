# Far Away, Close to Home · 나를 만든 사람들의 지도

문화기술론 HW2 · Generative AI × Me (2026년 10월)

나를 만든 40명의 사람을 두 개의 지도로 그린 작업입니다.

- **실제 거리:** 서울을 중심에 둔 정거방위도법 지도. 중심에서 멀수록 실제로 먼 사람입니다.
- **내가 느끼는 거리:** 같은 방향, 다른 거리. 동심원은 내가 직접 정한 거리 1–20입니다.
- **집의 좌표:** 가깝게 느끼는 사람일수록 무겁게 쳐서 구한 무게중심. 2026년 10월 기준 57.1°N 178.0°E, 베링해입니다.

## 파일

- `index.html`: 앱 전체가 들어 있는 파일 하나. 휴대폰, 태블릿, 노트북에서 모두 열립니다.

## 사용한 것

- 구상: ChatGPT
- 시각화와 앱 코드: Claude
- 지도 그리기: [D3.js](https://d3js.org) (cdnjs에서 불러옴)
- 지형 데이터: [Natural Earth](https://www.naturalearthdata.com) 1:110m 육지 (world-atlas)
- 글꼴: Google Fonts의 IM Fell English, Gowun Batang

거리 숫자(1–20)는 모두 작가가 직접 정했습니다. 이름은 이니셜로만 표기했습니다.
