# 생기부 나침반 — 깃허브(GitHub Pages) 1분 배포 가이드

이 폴더 안에 있는 파일들은 깃허브 웹 앱으로 즉시 동작하도록 완전히 빌드된 정적 웹 파일 모음입니다.
인터넷 브라우저만 있으면 스마트폰(아이폰/갤럭시), 태블릿(아이패드/갤럭시탭), 학교 PC 어디서든 즉시 접속할 수 있습니다.

---

### [초간단 3단계 배포 방법]

1. **깃허브 저장소(Repository) 만들기**
   - GitHub(https://github.com)에 로그인 후 우측 상단 `+` 버튼 -> `New repository` 클릭
   - Repository name 입력 (예: `compass` 또는 `school-record`)
   - `Public` 선택 후 아래 초록색 `Create repository` 클릭

2. **파일 드래그 앤 드롭 업로드**
   - 생성된 저장소 첫 화면 중간의 `uploading an existing file` 파란색 링크 클릭
   - 현재 이 폴더(`깃허브_배포용_생기부나침반`) 안에 있는 **모든 파일과 폴더**를 통째로 마우스로 끌어서(드래그) 깃허브 화면에 놓기
     - `assets` 폴더
     - `index.html`
     - `manual.html`
     - `app-icon.svg`
     - `404.html`
     - `.nojekyll`
   - 아래쪽 초록색 `Commit changes` 버튼 클릭

3. **무료 웹 주소(GitHub Pages) 켜기**
   - 저장소 상단 메뉴의 `Settings` (톱니바퀴) 클릭
   - 왼쪽 메뉴에서 `Pages` 클릭
   - `Build and deployment` 항목의 `Branch`를 `None`에서 `main` (또는 `master`)으로 변경하고 옆의 `/ (root)` 유지 후 `Save` 클릭
   - 1~2분 뒤 페이지 새로고침 시 상단에 생성된 웹 주소가 표시됩니다!
     (예: `https://선생님아이디.github.io/저장소이름/`)

이제 해당 주소를 스마트폰 홈 화면에 '홈 화면에 추가(PWA/웹앱)' 해두시면 앱처럼 언제 어디서나 바로 열어 쓰실 수 있습니다.
