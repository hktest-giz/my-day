# MY DAY · Pink Grape

사용자가 확정한 MY DAY 디자인과 기능을 담은 GitHub Pages용 웹앱입니다.

## 업로드 파일

압축을 푼 뒤 이 폴더 안의 모든 파일과 `icons` 폴더를 GitHub 저장소 최상위(root)에 업로드하세요. `index.html`이 최상위에 있어야 합니다.

## GitHub Pages 배포

1. GitHub 저장소에서 **Add file → Upload files**를 선택합니다.
2. `index.html`, `manifest.json`, `service-worker.js`, `README.md`, `.nojekyll`과 `icons` 폴더를 업로드합니다.
3. **Commit changes**를 누릅니다.
4. **Settings → Pages → Deploy from a branch**에서 `main`과 `/(root)`를 선택하고 저장합니다.
5. Pages 주소가 생성되면 Safari에서 열고 공유 메뉴의 **홈 화면에 추가**를 선택합니다.

## 포함 기능

- 딸기우유 핑크 테마 `#FFD1DC` 및 사용자 참고 이미지 스타일의 흰색 포도 아이콘
- 오늘 할 일, 예상 소요시간, 긴급 할 일, 남은 시간 헤드라인
- 마감 이틀 전부터 당일까지 긴급 표시
- 매일 반복 항목의 녹색 `매일` 표시 및 날짜 변경 시 완료 체크 초기화
- 할 일 체크와 취소선, 100% 달성 시 딸기와 새로운 계획 만들기 버튼
- 자동 배분 / 매일 반복, 시간 직접 입력 및 10분 단위 조절
- 모바일 터치와 PC 마우스 드래그로 할 일 순서 변경
- 기상 시간과 목표 수면시간 설정, 10분 단위 조절, 7시간일 때 녹색 권장 표시
- 취침 준비 30분을 고려한 `취침 전까지` / `기상까지` 카운트다운

## 저장 방식

할 일과 설정은 현재 브라우저의 localStorage에 저장됩니다. 기기 간 자동 동기화는 포함되어 있지 않습니다.
