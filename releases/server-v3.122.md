# JSON 프롬프트 설명·예시 표기 통일

기존 임상 추정 규칙은 유지하고 설명에서 텍스트 섹션 구분선/대괄호 TAG 지시를 제거했습니다. 모든 설명을 JSON 필드 및 name/value 객체 표기로 통일했습니다. JSON 예시 3개도 유지합니다.

PROMPT_JSON_V1.txt 전체를 config!B2에 값으로 붙여넣기 → Android 설정에서 프롬프트 가져오기 → 앱에 저장. PC/APK/Code.gs/Editor.html 변경 및 재배포 불필요. 기존 전송 작업의 고정 프롬프트는 바뀌지 않습니다.

검증: 기존 구분선/태그 지시 제거 확인, JSON 예시 파싱 및 서버 HXJSON1 검증. 실제 Gemini 호출은 하지 않았습니다.
