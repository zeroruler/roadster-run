# Roadster Run

흰 스튜디오 도로를 달리며 사고 차량, 빌런 SUV, 타이어 더미, 트레일러를 점프와 킥플립으로 넘는 3D 장애물 게임입니다.
2026년 10월 공개된 신형 로드스터의 콜드가스 스러스터 점프·킥플립 시연을 모티브로 했습니다.

- 플레이: https://zeroruler.github.io/roadster-run/
- 조작: Space / ↑ / W 또는 화면 탭으로 점프, 공중에서 한 번 더 누르면 킥플립

## 파일

- `index.html` — 게임 전체 (Three.js r128)
- `car.js` — 차 모델(GLB)을 base64로 담은 스크립트, 페이지가 비동기로 불러옵니다
- `car.glb` — 텍스처를 1024px로 줄인 차 모델 원본
- `suv.js` / `suv.glb` — 장애물용 SUV 모델 (같은 방식)
- `truck.js` / `truck.glb` — 킥플립으로 넘는 컨테이너 트럭 모델 (같은 방식)
