
# 🌍 클릭땅 (ClickLand) - 세계지도 땅따먹기

전 세계 실제 지도 위에서 **1m × 1m** 단위의 구역을 클릭하여 점령하는 **실시간 멀티플레이 웹 미니게임**입니다.

---

## ✨ 주요 기능

- **실시간 멀티플레이 동기화**: Firebase Realtime Database를 통해 전 세계 플레이어들의 땅 점령 및 공성전 현황이 실시간으로 반영됩니다.
- **1m × 1m 정밀 그리드 시스템**: 위도에 따른 실제 거리(`1m × 1m`)를 프론트엔드 수학 공식으로 계산하여 지도 위에 격자를 렌더링합니다.
- **점령전 & 공성전 규칙**:
  - 🏳️ **주인 없는 빈 땅**: **50번 클릭** 달성 시 내 영토로 점령
  - ⚔️ **다른 플레이어의 땅**: 방어력 2배가 적용되어 **100번 클릭** 달성 시 영토 강탈
- **전 세계 자유 이동 & 위성/일반 지도 전환**: 전 세계 도시/장소 검색, GPS 내 위치 이동, 고해상도 위성지도 및 일반 도로 지도를 자유롭게 전환할 수 있습니다.
- **실시간 영토 TOP 5 랭킹**: 현재 가장 많은 영토를 보유한 상위 5명의 플레이어와 총 점령 칸 수를 실시간으로 확인할 수 있습니다.

---

## 🛠️ 사용 기술 (Tech Stack)

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript (ES Modules)
- **Map Engine**: Leaflet.js (Esri World Imagery / Google Road Tiles / Nominatim Geocoding)
- **Backend / Realtime DB**: Firebase Realtime Database v11
- **Hosting**: GitHub Pages

---

## 🚀 플레이 방법

1. 접속 후 사용할 **정복자 닉네임**과 **영토 색상**을 선택합니다.
2. 지도를 **줌 레벨 18 이상**으로 확대하면 `1m × 1m` 격자가 나타납니다.
3. 원하는 칸을 클릭하고 목표 횟수(**50회** 또는 **100회**)만큼 빠르게 클릭하여 `[닉네임]의 땅!`으로 등록하세요!
Map Engine: Leaflet.js (Esri World Imagery / Google Road Tiles / Nominatim Geocoding)

Backend / Realtime DB: Firebase Realtime Database v11

Hosting: GitHub Pages
