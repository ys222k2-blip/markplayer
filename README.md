# &lt;mark&gt;

가사를 따라가며 듣는 웹 음악 플레이어. 휴대폰에 있는 음악 파일과 LRC·SRT 가사를 불러와, 지금 부르는 줄을 네모 상자가 따라갑니다.

**바로 쓰기:** https://ys222k2-blip.github.io/markplayer/

설치도 서버도 필요 없는 HTML 파일 하나(`index.html`)입니다. 고른 파일은 기기 밖으로 나가지 않고 브라우저 안에서만 재생됩니다.

## 기능

- 폴더 통째로 추가하기(iOS 18.4 이상) 또는 파일 여러 개 고르기
- 곡과 이름이 같은 `.lrc` · `.srt` · `.vtt` 가사를 자동으로 연결 (`곡.ko.srt`처럼 뒤에 붙은 이름도 찾음)
- 가사 줄을 누르면 그 위치로 이동, 손으로 넘겨 보다가 놓으면 현재 줄로 복귀
- 곡마다 가사 싱크 조절, 글자 크기·정렬·글꼴 설정
- 전체재생 · 전체반복 · 셔플 · 한곡반복 · 한곡재생, 재생 속도, 수면 타이머
- 잠금 화면 조작, 드래그로 순서 바꾸기, 지난번 목록과 위치 이어 듣기
- 곡을 넣기 전에 써 볼 수 있는 예시 곡이 들어 있음

## 아이폰에서 앱처럼 쓰기

Safari로 위 주소를 열고 공유 버튼 → **홈 화면에 추가**를 누르면 전체 화면 앱처럼 열립니다.

## GitHub Pages로 배포하기

이 저장소는 빌드 과정이 없어 `index.html`을 그대로 서비스합니다.

1. 저장소의 **Settings → Pages**로 이동
2. **Build and deployment → Source**를 `Deploy from a branch`로 선택
3. **Branch**에서 `index.html`이 있는 브랜치와 `/ (root)`를 고르고 **Save**
4. 1~2분 뒤 `https://ys222k2-blip.github.io/markplayer/`에서 열림

`.nojekyll` 파일은 GitHub Pages가 Jekyll 변환 없이 파일을 그대로 올리게 합니다.
