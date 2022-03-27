## EasyHCI  
  메모리 오버클럭 후 안정성 테스트에 사용되는 "HCI Memtest" 프로그램을 한글화하고, 가장 편리하게 사용할 수 있도록 만든 런처입니다.  
  
  
## 테스트 방법  
  1. 프로그램을 실행하여 "테스트 시작" 버튼을 누릅니다.  
    
  <img src="https://user-images.githubusercontent.com/74810045/159885823-b1c0b38f-530d-448e-b92b-1a49247f4c6a.png"  width="470" height="290">  
    
    
    
  2. 목표치를 설정하고 기다립니다. 테스트 탭을 눌러 모니터링 화면을 볼 수 있습니다. 메모리 사용량이 95% 이상을 유지하고 있다면 끝입니다.  
     EasyHCI는 Memtest 최대 메모리 할당량 / CPU 쓰레드 수 / 여유 메모리 등을 자동 탐색하기 때문에 별도의 설정을 하지 않아도 됩니다.  
     부가적으로 자동 캡쳐, 소리 알림, 테스트 정보 기록, 메모리 정리 등의 다양한 기능들도 존재합니다.
    
  <img src="https://user-images.githubusercontent.com/74810045/159886082-3a8b84e8-1cce-461e-bdd0-82e333620239.png"  width="470" height="250">  
    
    
    
## 주의사항
  ● HCI Memtest가 절대적으로 가장 좋은 테스트 프로그램은 아닙니다. 각 프로그램마다 테스트 방법이 많이 다릅니다. TM5, Prime95 등 많은 프로그램을 함께 이용하시는걸 권장합니다. 또한, 자원 활용량이 많은 게임을 해보시는 것도 방법입니다.  
  ● 테스트는 장시간 안정적으로 통과했지만 실사용은 불가능한 경우가 있습니다. 보통은 램의 온도가 너무 높은 경우가 많습니다. 실제 게임을 하실 때에는 GPU의 열기가 위로 올라오므로, 램의 온도가 테스트 당시보다 더 상승합니다. 이를 감안하여, 높은 전압과 세팅의 오버클럭을 하신다면 꼭 램 스팟쿨링을 하시길 권장합니다.  
    
    
## 사용한 외부 라이브러리  
  ● [MaterialSkin](https://github.com/IgnaceMaes/MaterialSkin)
