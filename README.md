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

데스크 업무 환경에서 발생하는 **사용자의 자세·행동을 실시간으로 감지**하고, IoT 경고·제어와 연동.  
COCO-17 기반 데이터셋으로 학습된 YOLOv8n-pose 모델을 Jetson Nano 환경 내 최적화(기존 - DESKTOP환경 내 프로그램 운용)를 진행하여 앉은 환경 특화 인식을 확보.
허리 굽음, 다리 꼬기 등 사무실에서 빈번한 자세 문제를 검출 및 TCP 신호로 서버/GUI와 잘못된 동작을 기록하여 제공하는 사용자 친화적인 프로젝트.
**Flask 웹 스트리밍·TensorRT 최적화·IoT 서버 연동**까지 포함한 end-to-end AI+IoT 융합 프로젝트.

- **사용 기술**  
  `AI Deeprunning` `TCP/IP` `STM32` `PWM` `UART` `MariaDB` `RFID` `openCV` `u-boot`

---

### 📄 쓰윽캔 (Image Scanner)
**Repository**: https://github.com/hb1no/image-scanner-opencv.git  

OpenCV와 Qt 기반으 제작한 데스크톱 이미지 스캐너 애플리케이션.  
문서 이미지를 불러와 다각형/사각형 ROI를 지정하면, **전처리(그레이스케일, 적응형 이진화, 노이즈 제거, 각도 보정)를 거쳐 텍스트를 
추출·클립보드/파일로 변환**할 수 있으며, 간단한 후처리 기능(다국어 인식, 노이즈 제거, 왜곡 보정)도 제공.  
문서 디지털화, 시험 답안지 판독, 간단한 노트 기록 디지털화 등 **실생활 응용에 적합한 범용 OCR 툴**로 발전 가능성을 염두해두고 제작한 프로젝트.

- **사용 기술**  
  `OpenCV` `Qt` `Python` `OCR`

---

### 🚦 Walk-Wise (Pedestrian Classification AI Model)
**Repository**: https://github.com/hb1no/Walk-Wise.git  

Intel Geti로 수집·라벨링한 횡단보도 데이터에서 보행자의 행동을 걷기/달리기로 분류하는 이미지 분류 파이프라인. 
횡단보도 보행자의 행동을 **걷기 vs 달리기(Classification)** 로 분류 하는 것. 
교통 신호 체계와 연계해 **달리는 보행자 감지 → 신호 시간 조정/경고 알림**과 같은 응용을 목표로 제작한 AI모델.

- **사용 기술**  
  `Intel Geti` `Classification` `Computer Vision`

---

### 🏋️‍♂️ New_Workout_Plan (Home Training System)
**Repository**: https://github.com/hb1no/New_Workout_Plan.git  

YOLOv11 포즈 인식으로 **사용자의 관절 키포인트를 추적하고, 반복/자세 각도 규칙으로 운동 카운트·폼 교정**을 실시간 피드백하는 프로젝트. 
라즈베리 카메라+팬틸트 구동으로 피사체 추적을 유지하고, ESP32 리모콘(가속도/자이로)에서 동작 스윙·속도를 수집해 포즈 신뢰도를 보강하며, 
심박 워치 데이터(BPM)를 함께 취합하여 운동 중 생체 리듬 데이터와 같은 개인화 가이드를 제공하는 통합 홈 트레이닝 루프를 구성.


- **사용 기술**  
  `YOLOv11` `Pose Estimation` `Raspberry Pi Camera` `ESP32` `STM32` `Accelerometer` `Heart Rate Sensor` `IoT` `Embedded Systems`

---

## 💼 경력 (Experience)

- **QA 테스터 – (주)모디엠 (VCRM 파트)**  
  2022.08 ~ 2024.11 (2년 4개월)  
  소프트웨어 품질 보증 및 테스트 자동화, 결함 관리, 사용자 시나리오 기반 검증 담당.  

- **AI SW 과정 수료 – 대한상공회의소 [Intel]**  
  2025.04 ~ 2025.10 (7개월 / 900시간)  
  Intel Geti 플랫폼 기반 AI 모델 학습·배포, 딥러닝 프레임워크 활용, 임베디드 AI 응용 프로젝트 수행.  

---

## 📜 자격증 (Certifications)

- **자동차운전면허 1급**

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
