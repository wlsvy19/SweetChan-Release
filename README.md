# SweetChan

Shift를 누른 채 파일을 끌면 커서 둘레에 원형 메뉴가 뜨고, 원하는 칸에 놓으면 그 형식으로 바꿔 주는 프로그램입니다.
바뀐 파일은 원본 옆에 새로 생기고, 원본은 그대로 남습니다. 모든 변환은 내 컴퓨터 안에서 끝나며 파일을 어디로도 보내지 않습니다.

## 내려받기

| 운영체제 | 파일 |
|---|---|
| 윈도우 10·11 (64비트) | [installSweetChan.exe](https://github.com/wlsvy19/SweetChan-Release/releases/latest/download/installSweetChan.exe) |
| macOS | [installSweetChan.dmg](https://github.com/wlsvy19/SweetChan-Release/releases/latest/download/installSweetChan.dmg) |

지난 판과 바뀐 날짜는 [릴리스](https://github.com/wlsvy19/SweetChan-Release/releases)에서 볼 수 있습니다. 내려받은 파일이 맞는지는 `SHA256SUMS.txt`의 체크섬과 견주어 확인할 수 있습니다.

## 설치

**윈도우**

1. `installSweetChan.exe`를 실행합니다. 관리자 권한 없이 내 계정에만 설치됩니다.
2. "Windows의 PC 보호" 창이 뜨면 **추가 정보 → 실행**을 누릅니다. 유료 서명 인증서를 쓰지 않아서 처음에 이 경고가 뜹니다.
3. 설치가 끝나면 바로 실행되고, 작업 표시줄 오른쪽 알림 영역에 아이콘이 생깁니다.

**macOS**

1. `installSweetChan.dmg`를 열고 `SweetChan`을 `Applications` 폴더로 끌어 놓습니다.
2. 처음 열 때 "확인되지 않은 개발자" 경고가 뜨면 **시스템 설정 → 개인정보 보호 및 보안**으로 가서 SweetChan 옆의 **그래도 열기**를 누릅니다. 애플 유료 인증을 받지 않아서 처음 한 번 이렇게 해야 합니다.
3. 실행되면 화면 위쪽 메뉴 막대에 아이콘이 생깁니다.

## 쓰는 법

1. 탐색기(맥은 Finder)에서 **Shift를 누른 채** 파일을 클릭하고 끌기 시작합니다.
2. 커서 둘레에 원형 메뉴가 뜨면 바꾸고 싶은 형식의 칸 위로 가져갑니다.
3. 놓으면 원본 옆에 새 파일이 생깁니다. 가운데나 메뉴 밖에 놓거나, Shift를 떼거나, Esc를 누르면 취소됩니다.

## 바꿀 수 있는 형식

| 끌어온 파일 | 바꿀 수 있는 형식 |
|---|---|
| md | Word · 한글 · txt |
| Word (.docx) | md · 한글 · txt |
| 한글 (.hwpx, .hwp) | md · Word · txt |
| txt | md · Word · 한글 |

한글 문서는 `.hwpx`로 만듭니다. 다른 형식은 차례로 늘어날 예정입니다.

## 그 밖에

- 컴퓨터를 켤 때 자동으로 실행하려면 아이콘의 메뉴에서 **로그인할 때 자동 실행**을 켭니다.
- 끄려면 아이콘의 메뉴에서 **종료**를 누릅니다.
