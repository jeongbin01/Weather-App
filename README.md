# 날씨 앱 만들기

사용자가 원하는 도시의 현재 날씨를 확인할 수 있는 간단한 웹 애플리케이션입니다.

## 프로젝트 개요
사용자가 특정 도시의 날씨 정보를 쉽게 조회할 수 있도록 하는 웹 애플리케이션입니다.<br>사용자는 도시 이름을 입력하면, 해당 도시의 현재 날씨, 기온, 습도, 풍속 등을 확인할 수 있습니다.<br>

## 개발 서버

로컬 환경에서 `index.html` 파일을 열려면 다음 경로를 사용하세요:
- **경로**: `C:/Users/bin14/project/Weather app/index.html`
- **파일 열기**: 파일 탐색기에서 해당 경로로 이동하여 `index.html` 파일을 더블 클릭하거나, 브라우저에서 파일을 열어 확인할 수 있습니다.



## 주요 기능
- **도시 검색**: 사용자가 입력한 도시의 현재 날씨 정보를 조회할 수 있습니다.
- **실시간 날씨 정보**: 현재 기온, 습도, 풍속 등을 실시간으로 확인할 수 있습니다.
- **시각적 피드백**: 날씨 상태에 따라 아이콘과 배경 이미지가 변경됩니다.
- **에러 처리**: 유효하지 않은 도시 이름을 입력할 경우, 에러 메시지를 표시합니다.

## 사용 방법
1. 웹 브라우저에서 `index.html` 파일을 엽니다.
2. 검색 창에 원하는 도시 이름을 입력하고 '검색' 버튼을 클릭합니다.
3. 해당 도시의 현재 날씨 정보가 화면에 표시됩니다.

## 기술 스택
- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## 향후 계획
- 다양한 난이도 모드 추가
- 리더보드 기능 구현
- 모바일 호환성 개선

## 리뷰 포인트

### 코드 구조 및 가독성
- 코드가 구조적으로 잘 짜여져 있는지
- 함수와 메서드가 명확하게 정의되어 있는지
- 주석 및 코드 설명이 충분한지

### 기능 구현의 완성도
- 주요 기능(도시 검색, 실시간 날씨 정보, 시각적 피드백, 에러 처리)이 제대로 동작하는지
- 날씨 정보가 정확하게 표시되는지

### 확장성 및 유지보수성
- 코드가 쉽게 확장 가능하게 작성되어 있는지
- 향후 계획된 기능들을 추가하기 위해 필요한 변경이 쉽게 적용될 수 있는지

### 사용자 경험(UX)
- 사용자가 프로그램을 쉽게 사용할 수 있도록 인터페이스가 구성되어 있는지
- 오류 메시지 및 사용자 피드백이 명확하게 전달되는지

## 부족한 점

### 보안
- 현재 프로젝트는 보안 이슈가 상대적으로 적지만, 사용자의 데이터 저장 및 관리 방안을 고려해야 할 수 있음.

### 다중 사용자 지원
- 현재는 단일 사용자만을 지원하며, 다중 사용자 지원이 필요함.

### 거래 내역 기록
- 검색 이력이나 사용자의 활동 기록을 저장하는 기능이 없음.

### 데이터베이스 연동
- 현재는 파일 기반의 데이터 저장 방식을 사용하고 있으며, 데이터베이스 연동을 통해 데이터 관리의 효율성을 높일 필요가 있음.

### 그래픽 사용자 인터페이스(GUI)
- 현재는 기본적인 GUI만 제공되고 있으며, 사용자 경험을 향상시킬 수 있는 추가적인 디자인 개선이 필요함.

## 히스토리
- **v1.0**: 기본 기능 구현 (도시 검색, 실시간 날씨 정보, 시각적 피드백, 에러 처리)
- **v1.1**: 점수 시스템 개선 및 버그 수정
- **v1.2**: 사용자 인터페이스 개선 및 색상 조정 기능 추가

## 원하는 목적성
- 사용자가 손쉽게 원하는 도시의 날씨 정보를 조회할 수 있는 간단한 웹 애플리케이션 제공
- 향후 다양한 기능 추가를 통해 실용적이고 확장 가능한 애플리케이션으로 발전
- 모바일 호환성을 개선하여 다양한 기기에서 애플리케이션을 사용할 수 있도록 함
