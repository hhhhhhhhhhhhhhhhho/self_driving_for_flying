# self_driving_for_flying
Using sensor for autonomous driving and flying drone

프로젝트의 최종형태는 비행드론을 만드는 것이다. 하하!


## 1. Lane Detection
---
자율주행에 사용 가능 한 여러개의 센서가 있겠지만 카메라만 먼저 구현하도록 해보자. 개발과 동시에 정리를 할 예정이라. 자율주행에 막 입문을 하려는 사람들이 보면 좋을 것 같다. 

'The Camera Never Lies' 카메라는 거짓말을 하지 않는다. 

NVIDA 의 공식문서에 나와있는 말인데, 카메라는 시각에 관한 모든 정보를 준다. 하지만 안개나 물체간의 거리를 구할 때는 다른 센서와의 협업이 필요 할 것이다. 

내가 첫번째로 구현 할 것은 카메라의 시각정보 중 도로 차선을 실시간으로 검출하는것이다. 

인공지능은 활용되지 않고 단순히 Computer Vision 만 활용 된다. 