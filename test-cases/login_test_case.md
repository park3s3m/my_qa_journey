# 로그인 기능 테스트 시나리오

## 목적
로그인 기능의 정상 및 비정상 입력 케이스에 따른 시스템 반응을 확인하기 위한 테스트 시나리오입니다.  
QA 포트폴리오용으로 개인 실습 목적에 따라 작성되었습니다.

## 테스트 환경
- 디바이스: Galaxy S21 / Windows 10
- 플랫폼: 모바일 웹 / 크롬 브라우저
- 테스트 대상: 로그인 화면 (웹/앱 구조 유사)

## 테스트 케이스 목록

| 시나리오 ID | 테스트 항목 | 입력값 | 기대 결과 | 비고 |
|-------------|--------------|--------|------------|------|
| TC001 | ID/PW 정상 입력 | Valid ID / Valid PW | 메인 페이지 이동 | 정상 케이스 |
| TC002 | ID 미입력 | 공백 / Valid PW | "아이디를 입력해주세요" 메시지 | |
| TC003 | PW 미입력 | Valid ID / 공백 | "비밀번호를 입력해주세요" 메시지 | |
| TC004 | ID, PW 모두 누락 | 공백 / 공백 | 오류 메시지 모두 표시 | |
| TC005 | 틀린 ID/PW | Invalid ID / Invalid PW | "아이디 또는 비밀번호가 잘못되었습니다" | |
| TC006 | 특수문자 입력 | 특수문자 포함 | 오류 메시지 또는 제한 | UX 정책에 따라 |

## 확인 포인트
- 오류 메시지 출력 위치 및 시각적 구성
- 입력창 포커스 이동
- 로그인 성공 시 URL 또는 앱 화면 흐름

## 상태
- 개인 QA 실습 기준으로 작성된 항목이며, 실무 적용을 위한 참고 자료용


참고
나중에 회원가입, 비밀번호 찾기, 로그아웃, 2단계 인증 등도 같은 형식으로 확장 가능

이 파일은 문서화 능력 + 구조화된 사고력을 잘 보여줄 수 있는 핵심 포인트입니다

