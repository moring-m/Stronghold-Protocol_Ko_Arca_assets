# Stronghold Protocol 한국어판 리소스

게임 저장소: https://github.com/moring-m/Stronghold-Protocol_Ko_Arca

`public/`은 게임 리소스 경로를 그대로 보존합니다. 게임에서는 변경되지 않는 커밋 SHA로 고정한 URL을 사용합니다.

- `inventory.json`: 서버 제공 리소스의 경로·크기·SHA-256
- `language-inventory.json`: 언어팩 파일 검증 정보
- `browser-resources.json`: 기존 미러를 포함한 리소스 목록
- `metadata/costume-supplement.json`: 기존 공식 이펙트를 보존하는 스킨 추가분
- `metadata/costume-report.json`: 추출 및 연결 수량

Arknights 게임 리소스의 권리는 Hypergryph / Yostar 등 해당 권리자에게 있습니다. 비공식 팬 프로젝트의 리소스 저장소입니다.

## 중국 클라이언트 추가 추출분

기존 게임 오퍼레이터의 스킨 19종에 대한 FX 연결과 파일만 추가했다. 이 수는 중국 서버 전용 신규 스킨 수가 아니다. 게임에 없는 오퍼레이터용 240종은 이번 저장소 업데이트에 포함하지 않는다.

- 기존 스킨 260종을 보존하며, 총 279종의 연결 정보를 보관한다.
- 마운틴 `marthe#13`은 목적지 이펙트 참조 2개를 확인하지 못해 보류한다. 기존 마운틴 스킨은 유지한다.
- 추가 이펙트 357개, 투사체 정의 20개, 텍스처 312개, 메시 92개. 신규 페이로드 1,069개/28,852,382바이트.
- `metadata/cn-costume-approved-report.json`에 승인 범위를 기록한다.
- 게임 저장소의 고정 참조 커밋을 갱신해야 이후 배포에 반영된다. 이 저장소 업데이트만으로 운영 게임이 변경되지는 않는다.
