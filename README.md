# opentawi-assets

[Open Tawi in Seoul](https://opentawi.com) — 조선풍 서울 산책 게임의 공개 데이터·모델 파일이에요.
이 저장소는 게임이 서울에서 빠르게 파일을 받기 위해 [jsDelivr](https://www.jsdelivr.com/) 공개 CDN으로 서비스돼요. 파일은 게임 저장소에서 자동으로 복사되며, 사이트는 항상 특정 커밋에 고정된 주소를 써요.

Public data and 3D model files of **Open Tawi in Seoul**, a free browser walking game set in a Joseon-styled Seoul. The game serves these files through the jsDelivr CDN (pinned to one commit); they are mirrored automatically from the game's repository.

## 내용 · Contents

| 경로 · path | 내용 · what |
|---|---|
| `seoul-play/geodata/` | 동네별 도로·건물·지하철역·명소·건물 이름 (OpenStreetMap에서 추출, 게임용으로 가공). Roads, buildings, stations, landmarks and building names per neighbourhood, derived from OpenStreetMap. |
| `seoul-play/places/` | 동네별 가게 위치 (OpenStreetMap). Shop positions per neighbourhood, from OpenStreetMap. |
| `seoul-play/meshy/` | 게임 캐릭터·악당·주민 3D 모델 (glTF binary, meshopt). The game's 3D character models. |

## 라이선스 · License

- `geodata/`, `places/`: © OpenStreetMap contributors, [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/). 건물 모양은 조선풍으로 다시 그렸어요.
- `meshy/`: © Open Tawi. 게임 안에서 보는 용도로 공개해요. 다른 곳에 쓰려면 먼저 문의해 주세요 (opentawi@gmail.com). Published so the game can load them; all other uses need permission.
