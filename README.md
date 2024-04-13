## 2024/04/13 - TextWebSocketHandler
#### HTTP 통신의 특징
1. 비연결성 (connectionless) : 연결을 맺고 요청을 하고 응답을 받으면 연결을 끊어버린다.
2. 무상태성 (stateless) : 서버가 클라이언트의 상태를 가지고 있지 않는다.
3. 단방향 통신이다.

HTTP 통신의 경우 채팅과 같은 실시간 통신에 적합하지 않다.

HTTP 통신으로 실시간 통신을 흉내낼 수는 있으나 완벽하지는 않다.

실시간 통신이 필요할 때 사용하는 통신을 소켓 통신이라고 한다.

HTTP 통신과 다르게 연결을 맺고, 바로 끊어버리는 게 아니라 계속 유지를 하기 때문에 실시간 통신에 적합하다.