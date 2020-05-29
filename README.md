# arduino-selfie-camera (ver.rear camera)  

This is a very simple example of a Arduino Selfie Camera - ver.rear camera  

Original Selfie Camera page  
https://github.com/moononournation/arduino-selfie-camera  

## ver.rear camera 변경 사항  

카메라 모듈이 후면으로 연결되어 원본 예제 실행 시 사진이 뒤집혀 출력되므로 해당 부분이 수정된 버전입니다.  
(※ 카메라 위치 변경 버전으로 화면 확인중 셀카 촬영은 불가능합니다)  

## TTGO - T-Camera Plus / Rear camear  

전면 사진  
<img src="https://raw.githubusercontent.com/eleparts/arduino-selfie-camera-rear-ver/master/img/TTGO-T-Camera-Plus-front.jpg" width="70%"></img>

후면 사진  
<img src="https://raw.githubusercontent.com/eleparts/arduino-selfie-camera-rear-ver/master/img/TTGO-T-Camera-Plus-back.jpg" width="70%"></img>

## Usage  

예제 설치 및 사용법 (eng)  
https://www.instructables.com/id/Arduino-Selfie-Camera/  

아두이노 IDE 설치 후 보드매니저를 통해 ESP32 시리즈를 추가해 줍니다.  
※ 참고 포스팅 : https://blog.naver.com/elepartsblog/221533983571
보드 URL : https://dl.espressif.com/dl/package_esp32_index.json 

그리고 "ESP32 Dev Board" 선택하고 PSRAM를 Enabled 후 업로드 해 주시면 됩니다.  
부팅(및 재부팅/Reset 버튼) 후 자동으로 3번 사진을 촬영하며, 자동으로 SD카드에 저장됩니다.  

촬영 이미지  
![Prototype](https://raw.githubusercontent.com/eleparts/arduino-selfie-camera-rear-ver/master/img/snap-rear-camera.jpg)  
