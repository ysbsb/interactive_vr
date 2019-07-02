# Interactive VR Game and Controller 

PART A: VR Game 제작
PART B: VR 게임과 연동하는 컨트롤러 장치 개발

## VR Game 제작
Catch Star

## Controller 개발
1. Software: Game과 Controller간 블루투스 Serial 통신
  * Game과 Controller간 블루트스 Serial 통신
  * 립모션 장치와 Unity 간의 Interface  
2. Hardware: Controller 장치 제작   

## Software  

### Arduino
블루투스 Serial 통신
단계 
* 기본: 게임 상에서 노트를 맞추었을 때, 아두이노 진동 모터 상에서 진동이 울린다.
* 콤보: 게임 상에서 콤보가 되었을 때, 진동의 세기를 더 크게 울린다.  

Code
* Arduino Script
* Unity Script

### LeapMotion  

* [립모션 리뷰](https://blog.naver.com/dev4unet/220647478393)
* [Leapmotion developer documentation](https://developer.leapmotion.com/documentation)
* [Leapmotion Android](https://developer.leapmotion.com/android#107)
* [Leapmotion Orion SDK](https://www.leapmotion.com/technology/)
* [Leapmotion in Unity Tutorials](https://www.youtube.com/playlist?list=PLnTTrMDXCsLpjeAYUXdgcpuGBWZSp7vyS)  

## Hardware

하드웨어 수량 확인하기  
- [ ] 립모션  
- [x] 아두이노 우노  
- [ ] 아두이노 나노 or 미니  
- [x] 블루투스 모듈 HC-06  
- [ ] 진동모터  
- [ ] 가속도센서  
- [ ] 전선  
- [ ] 브레드보드  
- [ ] PCB  

추가 테스트 하기 위한 장비
* LED
* 버튼
* DC모터 
