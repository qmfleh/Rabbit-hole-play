# 토끼굴 레이드 — 플레이 빌드

들어가서 털고, 살아서 나와야 내 것이 되는 탈출 던전 게임 (Windows 64비트).

## 처음 받을 때
1. [**릴리스 페이지**](https://github.com/qmfleh/Rabbit-hole-play/releases/latest)에서 `RabbitHole.exe`와 `RabbitHole.pck` 두 파일을 받음
   (exe는 100MB가 넘어서 저장소가 아니라 릴리스에만 있음)
2. 두 파일을 **같은 폴더**에 두고 `RabbitHole.exe` 실행

## 업데이트할 때
- **자동**: 게임을 켜면 새 버전이 있는지 확인해서, 있으면 `RabbitHole.pck`를 받아 스스로 다시 켜짐 (인터넷 필요)
  - 플레이 중에 다 받으면 다음에 켤 때 적용
  - exe가 있는 폴더에 쓸 수 있어야 함 (`Program Files` 같은 곳 말고 바탕 화면·내 문서 등에 두기)
- 손으로: 새 `RabbitHole.pck`만 받아서 덮어써도 됨 (이 저장소의 `RabbitHole.pck`나 릴리스 페이지, 둘 다 같은 파일)
  - 자동 업데이트가 없는 옛 빌드(2026-11-09 전)는 한 번은 손으로 바꿔야 함
- exe는 고도 엔진(4.7.2) 그대로라 엔진 버전이 바뀔 때만 다시 받으면 됨 → `VERSION.txt`에 적어 둠

## 조작
- 은신처: 장비·창고·상인, 시드 넣고 "굴로 들어가기"
- 레이드: WASD 이동 · J/왼쪽 공격(가까운 적 자동 조준) · Space/오른쪽 스킬 · Shift 구르기 · E 줍기·상자·계단 · Q 물약 · I 가방 · Tab 타겟팅(고정한 적을 보며 이동)

## 저장
`%APPDATA%\Godot\app_userdata\토끼굴 레이드\save.txt` — 업데이트해도 그대로 남음
