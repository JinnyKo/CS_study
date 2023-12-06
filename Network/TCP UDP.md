## TCP/IP 

<details> <summary>Q1.TCP 와 UDP 차이를 설명하시오.</summary>
- (차이가 메우 극명함 TCP: 1:1 과외, UDP: 학교 수업)

 TCP는 신뢰할 수 있는 연결형 프로토콜 입니다. 그렇기 때문에 데이터 송수신의 순서를 보장하고, 잘 못 전송된 데이터가 있을 경우 재전송을 통해서 데이터를 수정할 수 있고, 패킷이 손실되지 않도록 보장 합니다. (데이터가 올바르게 전송되었는지 확인하기 위해 연결을 설정하고, 유지합니다.) 그리고 *혼잡제어 알고리즘 이나 *흐름제어 알고리즘 같이 여러 신뢰성을 보장하기위한 매커니즘을 제공합니다.
UDP는 비연결 프로토콜 입니다. 연결을 설정하지않고, 데이터의 순서를 보장하지 않으며 손상된 데이터를 감지하거나 수정하지 않습니다. 또한 패킷이 손실될 수 있습니다. 하지만 이런 TCP에 비해서 비용이 없기 때문에 상대적으로 빠른 장점이 있습니다.

  ** 혼잡 제어(Congestion control): 네트워크내에서 패킷의 대기 지연이 너무 높아지게 되어 트래픽이 붕괴되지 않도록 패킷의 흐름을 제어하는 트래픽 제어, 목적: 네트워크 오버플로우,데이터 손실 방지 ex) AIMD,Slow Start 
  
  ** 흐름 제어: 네트워크내의 원활한 흐름을 위해 송,수신측 사이에 전송되는 패킷의 양, 속도 규제 
  
  ** 교착 상태 (Dead Lock): 예측 못한 다운, 둘 이상의 프로세스들이 자원을 점유한 상태에서 서로 다른 프로세스가 점유하고 있는 자원을 요구히며 무한정 기다리는 현상
</details>