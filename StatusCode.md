## 상태 코드


| Status | Description | example |
| --- | --- | --- |
| 200 | OK: 요청이 성공적으로 처리됨 | GET, POST, PATCH |
| 201 | Created: 리소스가 성공적으로 생성됨 | POST |
| 204 | No Content: 요청이 성공했지만 응답할 데이터가 없음 | DELETE |
| 400 | Bad Request: 잘못된 요청, 서버가 요청을 이해할 수 없음 | POST |
| 401 | Unauthorized: 인증이 필요하거나 인증 정보가 유효하지 않음 | 
| 403 | Forbidden: 접근 권한이 없어서 요청이 거부됨 |
| 404 | Not Found: 요청한 리소스를 찾을 수 없음 | POST, PATCH, DELETE |
| 422 | Unprocessable Entity: 요청이 처리되지 않음 (유효성 검사 실패 등) | PATCH |
| 500 | Internal Server Error: 서버에서 알 수 없는 오류 발생 |