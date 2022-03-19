# flutter-kduBus-app

플러터를 이용하여 만든 학교 셔틀버스 어플입니다.
교내 무료로 운영되는 셔틀버스를 타고 다니면서
3학년 2학기에 처음으로 만들게 되었던 어플리케이션입니다.


2020년도 말에 완성된 프로젝트로 현재 버전과는 조금 다를 수 있습니다.
(2021 초에 버전 수정하였으나 문제 있을 수 있습니다!)

- 자료 중 어플리케이션 설명 PPT 자료도 포함 되어있습니다.
------------------------------------------------------------------------------------
<br><br>


## 개발 동기


타 대학의 셔틀버스는 티켓을 구매하는 등 미리 신청을 받는 방식으로 운영됨과 달리
저희 학교 셔틀버스는 따로 티켓이 없이 선착순으로 탑승하고 인원이 채워지면 출발하는 시스템이었습니다.
9시 반 차가 4대 준비되어있다면, 특정 시간(9시 50분 등)까지 기다리지 않고 순차적으로 채워 출발하는 방식으로
인원이 많은 날에는 시간에 맞추어 오더라도 버스를 이용하지 못하거나,
인원이 적어 이용할 수 있는 날에도 직접 정류장까지 가보기 전에는 알 수 없기 때문에
이러한 불편함을 해소하고자 만들게 된 프로젝트입니다.
<br><br>
## 프로젝트 설명


QR코드를 이용하여 그 날 그 날 버스 탑승인원을 체크하여,
멀리에서도 오늘의 잔여 좌석을 확인할 수 있고,

매일 운영 대수가 달라지는 만큼 관리자 계정을 따로 개설하여 운영되는 버스를 체크하여
학생 화면에는 운영되는 버스만 표시될 수 있도록 하는 어플리케이션입니다.
<br><br>

## 구현 기능

#### 1. 로그인


회원 가입 후 이메일 인증 후에 계정을 사용할 수 있습니다.


<img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%EB%A1%9C%EA%B7%B8%EC%9D%B81.png" width=30%> <img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%EB%A1%9C%EA%B7%B8%EC%9D%B82.png" width=30%> <img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%EB%A1%9C%EA%B7%B8%EC%9D%B83.png" width=30%>






#### 2. 학생 탭


학생은 회원가입 후 학번 등록을 완료해야 본인의 QR 기능(학번으로 QR 생성)을 사용할 수 있으며,
등록된 계정 중 일치하는 학번이 없는 경우에만 등록이 가능합니다. (닉네임 변경 가능)
또한 QR을 통해 찍힌 탑승인원과 시간대별 운행 중인 버스의 상태를 확인할 수 있습니다.

<img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%ED%95%99%EB%B2%88%20%EC%9D%B4%EB%A6%84%20%EC%9E%85%EB%A0%A5.png" width=30%> <img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%ED%95%99%EC%83%9D1.png" width=30%> <img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%ED%95%99%EC%83%9D2.png" width=30%>


<img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%ED%95%99%EC%83%9D3.png" width=30%> <img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%ED%95%99%EC%83%9D4.png" width=30%>






#### 3. 관리자 탭


관리자 탭에서는 운행 중인 버스를 관리할 수 있습니다.
요일별/시간별로 운행되는 버스 수가 다르기 때문에 '운행 중단' 시 학생들에게는 해당 호차가 표시되지 않습니다
QR스캐너를 통해서 해당 호차 탑승인원을 체크할 수 있습니다
탑승하는 학생들의 QR을 스캔하여 인원을 집계합니다.


<img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%EA%B4%80%EB%A6%AC%EC%9E%901.png" width=30%> <img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%EA%B4%80%EB%A6%AC%EC%9E%902.png" width=30%> <img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%EA%B4%80%EB%A6%AC%EC%9E%903.png" width=30%>


<img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%EA%B4%80%EB%A6%AC%EC%9E%904.png" width=30%> <img src="https://github.com/mingulee-only/flutter-kduBus-app/blob/main/%EA%B4%80%EB%A6%AC%EC%9E%905.png" width=30%>











