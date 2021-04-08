- Address Resolution Protocol의 약자로, OSI 7계층에서 네트워크 계층 주소와 데이터 링크 계층 주소 간의 변환을 담당하는 IP 프로토콜이다.
- IP 주소에 해당하는 물리적인 MAC 주소를 가져온다.
- ARP의 필요성은 다음과 같다.
- 네트워크의 동작 방식이 계층별로 나누어져 있기 때문에, 네트워크 계층에서는 IP 프로토콜을 통해 IP 주소를 매개로 하여 정보가 전송된다. 
- 이 때, 네트워크 계층에서 데이터 링크 계층으로의 정보 전달을 위해 MAC 주소가 필요하다.
- ARP의 동작 과정은 다음과 같다.
- 송신자는 MAC 주소를 얻기 위해 ARP 요청 패킷을 전송한다.
- 라우터와 호스트는 송신자가 전송한 ARP를 요청하고, 이에 해당되는 수신자가 IP 주소와 MAC 주소를 응답 패킷에 기록하여 전송한다.
- 송신자는 응답 메시지를 받고 MAC 주소를 알 수 있다.