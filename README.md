# Noom

Zoom Clone using NodeJS, WebRTC and Websockets.
---
동일한 방 이름을 입력하면 1:1 화상통화가 가능한 실시간 웹서비스를 구현함.

<img width="100%" src="https://github.com/changwann/crave_week2/assets/122224659/d160a0e7-4cce-4305-a4c7-e614e3c8ae70"/>  
처음 페이지를 들어가면 방 이름을 칠 수 있는 칸과 함께 홈 메뉴가 뜬다. 이미 있는 방 이름을 치게 되면, 해당 방으로 접속을 하게 되고, 없는 방 이름을 치게 되면 자신이 방을 만드는 셈이 된다.

<img width="100%" src="https://github.com/changwann/crave_week2/assets/122224659/43922767-e714-4a27-9a10-9eb504f554ca"/>   
방에 입장할 경우, 카메라를 선택할 수 있는 선택창이 있고, 마이크와 카메라를 On/Off 할 수 있는 버튼을 구현했다.

<img width="100%" src="https://github.com/changwann/crave_week2/assets/122224659/b37949ef-acae-48d2-8117-ef7e145285ea"/>  
2명이 하나의 방에 있을 경우 WebRTC의 Peer To Peer 방식을 이용해 실시간으로 영상과 소리 정보를 송수신하며 정상적으로 영상통화를 할 수 있다.  

---
✔️ 피드백
- 1:多 서비스 구현 필요
- 사용자가 방을 나가는 버튼이 구현되어 있지 않고, 페이지 종료를 통해 방을 나갈 경우 카메라가 멈춘 상태로 유지되는 버그 발견
- 디자인에 신경을 쓰지 못함

🙂 배운 점
- HTTP와 Websocket의 차이점, socket.io, WebRTC 개념과 사용법을 익힘.
- pug를 이용해 html 코드를 깔끔하게 작성할 수 있게 됨.


https://nomadcoders.co/noom
