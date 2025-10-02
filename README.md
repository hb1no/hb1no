# profile
<div align="center">

#프로필 👨‍💻

임베디드 개발을 지향하는 이호빈입니다.  

<!-- 주요 스택 (배지) -->
  
[![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white)]()
[![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)]()
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)]()
[![STM32](https://img.shields.io/badge/STM32-03234B?logo=stmicroelectronics&logoColor=white)]()
[![Arduino](https://img.shields.io/badge/Arduino-00979D?logo=arduino&logoColor=white)]()
[![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?logo=raspberrypi&logoColor=white)]()
[![Jetson Nano](https://img.shields.io/badge/Jetson%20Nano-76B900?logo=nvidia&logoColor=white)]()
[![ROS](https://img.shields.io/badge/ROS-22314E?logo=ros&logoColor=white)]()
[![ESP32](https://img.shields.io/badge/ESP32-000000?logo=espressif&logoColor=white)]()
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)]()
[![MariaDB](https://img.shields.io/badge/MariaDB-003545?logo=mariadb&logoColor=white)]()
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)]()
[![u-boot](https://img.shields.io/badge/u--boot-333?logo=gnu&logoColor=white)]()
[![TCP/IP](https://img.shields.io/badge/TCP%2FIP-333333?logo=internet-computer&logoColor=white)]()

</div>

---

## 📂 주요 프로젝트

### 🏢 Office_IoT (Comprehensive IOT)
**Repository**: https://github.com/hb1no/Office_IoT  

사무실 환경에서 다양한 센서·액추에이터를 MCU 및 서버와 연동하여 **실시간 상태 모니터링과 제어**를 구현한 IoT 시스템.  
RFID, 조도·온습도 센서, PWM 기반 구동 장치 등을 통합해 출입 관리 및 환경 제어까지 가능하도록 설계.  
**펌웨어–네트워크–데이터베이스–서버** 전 구간을 직접 구현·연동. 

- **사용 기술**  
  `C` `TCP/IP` `STM32` `Arduino` `PWM` `UART` `MariaDB` `RFID`

---

### 🤖 꼰Desk (AI Smart Desk)
**Repository**: https://github.com/hb1no/Smart-Desk.git

OpenCV와 AI 모델을 활용해 **사용자의 자세·행동을 실시간으로 감지**하고, IoT 신호와 연동하여 경고·제어 기능을 제공하는 프로젝트.  
YOLO 기반 커스텀 모델과 Jetson Nano 최적화를 통해 허리 굽음, 다리 꼬기 등 사무실에서 빈번한 자세 문제를 검출.  
**Flask 웹 스트리밍·TensorRT 최적화·IoT 서버 연동**까지 포함한 end-to-end AI+IoT 융합 시스템.  

- **사용 기술**  
  `AI Deeprunning` `TCP/IP` `STM32` `PWM` `UART` `MariaDB` `RFID` `openCV` `u-boot`

---

### 📄 쓰윽캔 (Image Scanner)
**Repository**: https://github.com/hb1no/image-scanner-opencv.git  

OpenCV와 Qt 기반으로 제작한 **데스크톱 이미지 스캐너** 애플리케이션.  
이미지 파일을 불러와 특정 영역을 선택하면 OCR을 통해 텍스트를 추출·변환할 수 있으며, 간단한 후처리 기능도 제공.  
문서 디지털화, 시험 답안지 판독, 간단한 노트 기록 디지털화 등 **실생활 응용에 적합한 범용 OCR 툴**로 발전 가능.

- **사용 기술**  
  `OpenCV` `Qt` `Python` `OCR`

---

### 🚦 Walk-Wise (Pedestrian Classification AI Model)
**Repository**: https://github.com/hb1no/Walk-Wise.git  

Intel Geti를 활용해 횡단보도 보행자의 행동을 **걷기 vs 달리기(Classification)** 로 분류하는 AI 모델.  
교통 신호 체계와 연계해 **달리는 보행자 감지 → 신호 시간 조정/경고 알림**과 같은 응용을 목표.  
데이터셋 품질과 다양성 문제를 다루며, **실제 교통·안전 분야 적용 가능성**을 실험적으로 검증.  

- **사용 기술**  
  `Intel Geti` `Classification` `Computer Vision`

---

### 🏋️‍♂️ New_Workout_Plan (Home Training System)
**Repository**: https://github.com/hb1no/New_Workout_Plan.git  

YOLOv11 모델을 활용해 **트레이닝 자세(포즈)를 인식·교정**하는 기능을 중심으로 한 홈 트레이닝 시스템.  
라즈베리 카메라 기반 팬틸트 카메라로 사용자 동작을 추적하고, ESP32 + 가속도 센서 기반 리모콘으로 **Wii 스타일의 운동 인터랙션**을 제공.  
심박수 센서를 장착한 워치를 연동하여, **운동 자세·활동 강도·심박 데이터**를 통합 분석하는 개인 맞춤형 피트니스 환경을 구현.  

- **사용 기술**  
  `YOLOv11` `Pose Estimation` `Raspberry Pi Camera` `ESP32` `STM32` `Accelerometer` `Heart Rate Sensor` `IoT` `Embedded Systems`

---

## 🧰 보유 스택 (요약)

`C` `STM32` `Arduino` `ESP32` `Raspberry PI` `TCP/IP` `PWM` `UART` `MariaDB/MySQL` `RFID` `OpenCV` `u-boot`

> 하드웨어 드라이버/펌웨어부터 서버 연동, 네트워킹까지 전 구간을 직접 구현/통합하는 데 강점이 있습니다.

---

## 📫 Contact
- Email: **hobini77@naver.com**
- GitHub: **@hb1no**

<div align="center">

</div>
