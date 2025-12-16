# **반응속도 테스트 (Reaction Speed Test)**

사용자의 반응 속도를 측정하는 간단한 웹 게임입니다. 화면의 색이 바뀌는 순간을 얼마나 빠르게 클릭할 수 있는지 확인할 수 있습니다.

# 프로젝트 개요

프로젝트명: 반응속도 테스트 (Reaction Speed Test)
목적: 사용자가 화면의 색 변화를 클릭하여 반응 속도를 확인하고, 기록을 저장해 자신의 최고 기록을 갱신할 수 있도록 함

# 주요 기능

시작 버튼을 눌러 테스트 시작

2~5초 사이 랜덤 시간 후 화면 색이 초록색으로 바뀜

색이 바뀌는 순간 클릭 → 반응 속도(ms) 측정

색이 바뀌기 전에 클릭하면 "너무 빨랐습니다!" 경고


# 화면 흐름

## 준비 상태: "곧 색이 바뀝니다..." (빨간색 배경)

<img width="897" height="630" alt="image" src="https://github.com/user-attachments/assets/194f975b-fc92-4dad-9fdb-fe1baf30bd2d" />

## 클릭 대기 상태: "지금 클릭!" (초록색 배경)

<img width="900" height="637" alt="image" src="https://github.com/user-attachments/assets/ee69c7a0-f707-43ae-8b96-1d53e676aca1" />


## 결과 화면: 반응속도의 평균과 최고 기록 표시

<img width="901" height="634" alt="image" src="https://github.com/user-attachments/assets/21330489-382a-46a6-b105-189a7be16767" />



# 실행 방법

저장소를 클론하거나 index.html 파일을 다운로드

크롬이나 엣지 브라우저로 열기

"시작" 버튼을 눌러 게임 시작


# 향후 개선

모바일 터치 대응

결과 더 정확하게 측정할 수 있도록 개선

온라인 랭킹 기능 추가 (Firebase/Supabase 연동)

테스트 결과에 따른 결과에 대한 평가 출력

# 데모버전
https://honey0085.github.io/web_programing/
