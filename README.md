# SAP_CO_OP_TRACK_25_2
SAP ABAP 개발 교육 과정 실습 코드 모음

## 구조
- `src/edr` : 교육 내의 주차별 실습코드
  - 기본문법 및 데이터 타입
  - Internal Table 조작
  - Database 조작 (SELECT, INSERT, UPDATE, DELETE)
  - Screen Programming
  - ALV 리포트
  - Module Pool 개발
  - Class 및 Event 처리
 
- `src/mm` : MM의 AP프로세스, 전표를 다룬 프로젝트
  - 구매오더 기반 송장 / 입고 흐름
  - 회계전표 생성 및 취소 로직
  - 부분/전체 처리 시나리오

- `src/work` :
  - 환율 업데이트 (1) - 엑셀 업로드 기반 수동 환율 등록, 파일 F4 도움말, 템플릿 다운로드, 환율유형 M 고정
  - 환율 업데이트 (2) - 날짜 기준 환율 조회 및 PDF 다운로드
    
- `src/practice` :
  - PRACTICE001 : LOOP / AT FIRST·LAST·NEW·END 실습, 성적 집계 및 장학금 처리
  - PRACTICE002 : READ TABLE / COLLECT 실습, 학사경고 대상 판별 및 통계 출력
  - PRACTICE003 : 스크린 제어 실습, 주문/배송 라디오버튼 및 반품 체크 처리
  - PRACTICE004 : FUNCTION 실습, 사번 자리수 보정 후 데이터 INSERT
  - PRACTICE006 : 사원 월급 지급 프로그램, ALV 출력 및 월별 지급 UPDATE
  - PRACTICE007 : 사원 월급 지급(FS), 필드심볼 기반 월별 지급 처리
  - PRACTICE008 : CLASS ALV 기반 물품 내역 확인서
  - PRACTICE009 : SPLITTER 기반 사원정보 조회, 입력조건 검증
