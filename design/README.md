# 디자인 시안

화면을 바꾸기 전에 그려 본 시안. HTML을 브라우저로 열면 그대로 보이고, 같은 이름의 PNG는 그 화면을 찍은 것.

| 시안 | 내용 | 상태 |
| --- | --- | --- |
| [layout-bottom](layout-bottom.png) ([html](layout-bottom.html)) | 메뉴를 전부 아래로: 맨 아래 로고 + 탭, 그 위 재생 칸, 콘텐츠 바로 아래 탭별 버튼. 위에는 메뉴 없음 | 지금 쓰는 배치 |
| [layout-swap](layout-swap.png) ([html](layout-swap.html)) | 탭과 옵션 자리 바꾸기: 탭을 재생 칸 맨 아랫줄로, 재생 모드·속도·수면 타이머를 위 머리줄로. ③은 새 버전 알림과 로고 메뉴 | 백업 |
| [album-tab](album-tab.png) ([html](album-tab.html)) | 앨범 탭 첫 시안(표지 + 버튼, 탭 이름은 '작품'이던 때) | 반영됨 |

## 예전 배치로 돌아가기

- 탭이 위에 있던 마지막 판: main의 커밋 `c92f770` (앨범 탭: 저장소에 한글 제목이 있으면 먼저 보여주기). 그 판의 화면으로 돌리려면 `git checkout c92f770 -- index.html`
- layout-swap은 코드로 만든 적이 없는 시안이라, 돌아가려면 이 시안대로 새로 만든다.
