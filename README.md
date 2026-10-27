# NFC 이미지 + 음악 페이지

화면에 이미지만 보이고, **한 번 탭하면 음악 재생 / 한 번 더 탭하면 정지**되는 페이지입니다.

## 파일 구성
- `index.html` : 페이지 본체
- `image.jpg` : 표시되는 이미지
- `song.mp3` : 재생되는 노래

## GitHub Pages로 배포
1. GitHub에서 새 저장소(Repository) 생성 (Public)
2. 이 폴더의 파일 4개를 모두 업로드 (Add file → Upload files)
3. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save
4. 1~2분 뒤 `https://<아이디>.github.io/<저장소이름>/` 주소 생성

## NFC 태그에 쓰기
NFC Tools 같은 앱에서 **쓰기 → 레코드 추가 → URL/URI** 선택 후 위 주소를 입력하고 태그에 쓰면 됩니다.
