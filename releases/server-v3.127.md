# 정리기 1 서버 v3.127

Apps Script 편집기에서 시트 직접 전송을 설정할 수 있도록 실행 함수 `enableDirectHxWrites`를 추가했습니다. PC 앱은 v3.126을 사용합니다.

1. 기존 정리기 1 Apps Script 프로젝트의 통합 Code.gs를 ZIP의 Code.gs로 교체하고 저장합니다.
2. 편집기 상단 함수 목록에서 `enableDirectHxWrites`를 선택하고 실행합니다. 권한 요청이 뜨면 승인합니다. 연결된 스프레드시트에 HxSubmit 탭이 생기면 설정 완료입니다.
3. 배포 관리에서 기존 웹앱을 새 버전으로 업데이트합니다. 직접 전송을 처음 사용하는 PC는 트레이 Google Sheets 연결에서 쓰기 권한을 승인합니다.
