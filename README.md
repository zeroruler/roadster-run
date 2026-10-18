# Roadster Run

흰 스튜디오 도로를 달리며 사고 차량, 빌런 SUV, 타이어 더미, 트레일러를 점프와 킥플립으로 넘는 3D 장애물 게임입니다.
2026년 10월 공개된 신형 로드스터의 콜드가스 스러스터 점프·킥플립 시연을 모티브로 했습니다.

- 플레이: https://zeroruler.github.io/roadster-run/
- 조작: Space / ↑ / W 또는 화면 탭으로 점프, 공중에서 한 번 더 누르면 킥플립
- 터널: 10km 지점에서 첫 터널(1km)이 나오고, 그 뒤로는 가끔 나옵니다. 안에서는 화면이 어두워지고 바리케이드, 연기 나는 사고 차량, 점프하면 부딪히는 천장 표지판이 나옵니다. 로컬(localhost/파일)에서 열면 첫 터널이 500m에 나옵니다.

## 파일

- `index.html` — 게임 전체 (Three.js r128)
- `car.js` — 차 모델(GLB)을 base64로 담은 스크립트, 페이지가 비동기로 불러옵니다
- `car.glb` — 텍스처를 1024px로 줄인 차 모델 원본
- `suv.js` / `suv.glb` — 장애물용 SUV 모델 (같은 방식)
- `truck.js` / `truck.glb` — 킥플립으로 넘는 컨테이너 트럭 모델 (같은 방식)
- `flatbed.js` / `flatbed.glb`, `coil.js` / `coil.glb` — 코일을 싣고 지나가는 평판 트럭과 굴러오는 강철 코일 (같은 방식)
- `barricade.js` / `barricade.glb` — 터널 안 바리케이드 모델 (같은 방식)
