실행 시 나타나는 창의 미리보기 스크린샷을 이 폴더에 넣습니다.

[파일 이름 규칙]
  프로젝트 폴더 경로의 슬래시(/, \)를 모두 __ 로 바꾸고 .png 를 붙입니다.

[예시]
  DATA_SHEET/PMC                 -> shots\DATA_SHEET__PMC.png
  DATA_SHEET/SAFETY_VALV_SIZING  -> shots\DATA_SHEET__SAFETY_VALV_SIZING.png
  DATA_SHEET/LINE_LIST           -> shots\DATA_SHEET__LINE_LIST.png
  HRSG                           -> shots\HRSG.png
  ACEUTIL                        -> shots\ACEUTIL.png
  ISO_AUTO_EDIT/ISO_AUTO_EDIT_FOR_E3D -> shots\ISO_AUTO_EDIT__ISO_AUTO_EDIT_FOR_E3D.png

[동작]
  - VIEW ONLY 모드에서 카드를 열면, 위 이름의 이미지가 있으면 모달 위쪽에 자동 표시됩니다.
  - 이미지를 클릭하면 새 탭에서 크게 볼 수 있습니다.
  - 해당 이미지가 없으면 아무것도 안 뜨고 기존처럼 파일 목록만 보입니다.

[캡처 방법]
  실제 도구를 실행(런처.bat)해서 창이 뜨면, 그 창을 캡처(Alt+PrintScreen 등)해서
  위 규칙의 이름으로 PNG 저장하면 됩니다.

[GitHub(웹/폰)에도 보이게 하려면]
  이 shots 폴더와 PNG 들을 ace-launcher 저장소에도 함께 올려야 합니다.
  (publish 시 index.html 뿐 아니라 shots 폴더도 함께 복사/푸시 필요)
