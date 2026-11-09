# 신경쇠약 - GitHub Pages 업로드용

## 업로드 방법
1. 이 ZIP 파일을 압축 해제합니다.
2. GitHub에서 게임 저장소(repository)를 엽니다.
3. `Add file` → `Upload files`를 선택합니다.
4. 압축 해제한 폴더 안의 **`index.html`과 `assets` 폴더**를 함께 업로드합니다.
   - `신경쇠약_GitHub` 폴더 자체를 한 단계 더 중첩해서 올리지 마세요.
   - 저장소 첫 화면에 `index.html`과 `assets`가 나란히 보여야 합니다.
5. `Commit changes`를 누릅니다.
6. 저장소의 `Settings` → `Pages`에서 기존과 같이 배포 브랜치와 폴더(`/root`)를 선택하고 저장합니다.
7. 배포가 끝나면 GitHub Pages 주소에서 게임을 확인합니다.

## 폴더 구성
- `index.html`: 게임 본체
- `assets/images/`: 게임 UI, 배경, 카드 이미지, 스테이지 사진
- `assets/audio/`: 배경음악
- `assets/fonts/`: 게임 폰트

## 참고
- 이미지, 폰트, 음악을 HTML 내부의 Base64 데이터에서 별도 파일로 분리했습니다.
- HTML의 파일 경로를 새 `assets` 폴더 구조에 맞게 변경했습니다.
- 기존 게임 코드와 화면/게임 설정은 유지하는 것을 목표로 했으며, 브라우저별 최종 동작은 GitHub Pages에 올린 뒤 확인해 주세요.
- 기존 저장소를 교체하는 경우, 기존 파일을 바로 삭제하기 전에 새 버전을 먼저 업로드하고 정상 작동을 확인하는 것을 권장합니다.
