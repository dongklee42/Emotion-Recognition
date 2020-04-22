# Meeting Log

> 팀프로젝트간 회의했던 내용 정리본

### 주요 목표 사항

1. 웹/앱 개발 완료
2. Open CV 스터디

## 주요 논의 사항

### 팀 프로젝트 진행사항

- 프로젝트 계획서 초안 ppt 작성(20.04.18~, 진행중)
- 이미지 슬라이싱, resize하여 감정 분류 모델 적용하는 코드 django로 구현(20.04.18~, 진행중)
- 실시간 캡처 이미지 다음 페이지로 redirect 하는 javascript 코드 서칭(20.04.17~, 진행중)

### 추가 고려해볼 사항

- 결과물 산출 후 웹 페이지 검증 방법, 기준
- 분류 모델 알고리즘 검증 방법, 기준
- 개발 목적 대한 논의 및 문서화(통계 포함)

### 일정 관련 사항

- 4/20(월)~4/24(금)

  1. django를 활용한 웹페이지 기본 틀 제작 완료

     (이하 구현할 주요 코드)

     - push 버튼=>웹캠 접근하는 코드(완료 20.04.13)
     - 웹캠 접근 및 실시간 촬영, 캡쳐 코드(완료 20.04.13)
     - 캡쳐한 이미지 resize하는 코드(완료 20.04.17)
     - 이미지 모델과 연결, 실행하는 코드(완료 20.04.17)
     - 감정 결과 웹페이지에 표시하는 코드
     - 감정 결과와 음악 실행 리스트 연결하는 코드
     - 음악 리스트 자동재생, 웹페이지 화면에 구현하는 코드
     - 한 곡이 끝나면 연속재생하는 코드

  2. 틈틈이 모델링 시험, 정확도 및 하이퍼파라미터 기록

## 기타사항

- 월, 금, 토, 일 : 화상 강의가 진행되는 기간 동안 팀 프로젝트 진행(금요일 역삼 멀티캠퍼스 강의실, CMAX 스터디룸)
- 화, 수, 목 : 개인 스케줄에 따름(공부, Kaggle, DACON, 시험/자격증 준비 등)
- 팀 프로젝트 진행 시간 **13:00PM~19:00PM**으로 변경(04/17(금)만 11:30AM~06:00PM)
- 04.19(일)은 오프라인 모임 없음
  - Atom + django 복습 및 javascript 공부할 것
  - 04.20(월)에 OpenCV 스터디 대신 전날 공부한 내용 각자 리뷰
- 프로젝트 계획서 수정 및 보완(1시간)