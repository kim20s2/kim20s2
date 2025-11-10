# 👋 안녕하세요, 임베디드 개발자입니다!

🏅 Intel Edge AI Academy 8기
  
🚗 최근에는 ~ 개발했어요.  
💡 다양한 임베디드 프로젝트를 직접 설계하고 구현하며 경험을 쌓고 있습니다.  

---
🎓 현재 구직 중

🔧 Tech stack: C/C++, Python, Embedded Linux, Firmware, BSP, MariaDB, LaspberryPi + Hailo8(AI Accelerator), Pi Camera Module V3, Jetson Nano, Arduino, STM32, FreeRTOS, OpenVINO, intelGeti, Deep Learning, OpenCV, Gstreamer, ROS

📫 How to reach me: [kim24k2qq@gmail.com](mailto:kim24k2qq@gmail.com)   

## 🚀 주요 프로젝트

- 🏗️ **[프로젝트 2](https://github.com/kim20s2/Project2)**:

- 🤖 **[AI 모의 면접 평가 시스템](https://github.com/kim20s2/Project1)**:
  Jetson Nano(또는 Raspberry Pi 5 + Hailo-8) 기반 AI 카메라로 면접자의 얼굴 표정(긍정·중립·부정)과 자세(좋음·보통·나쁨), 다리 떨림을 실시간 추론하고 화면에 HUD로 표시. OpenCV와 TensorRT/HailoRT로 경량화해 저사양에서도 동작하며, Flask REST 서버와 웹 UI를 통해 카메라 ON/OFF·녹화 시작/종료·결과 다운로드를 제어. 세션 동안 MP4/WAV와 XML 메타데이터를 저장하고, 종료 후 표정 비율·자세 점수·이벤트 타임라인을 기반으로 생성된 자동 분석 리포트를 클라이언트에게 제공. USB/RealSense/RTSP 등 다양한 카메라를 지원하고, 베이스라인 캘리브레이션(b)→녹화 트리거(t) 워크플로로 일관된 비교가 가능해 면접 피드백에 바로 활용 가능.

- 🏠 **[IoT 스마트홈 시스템](https://github.com/kim20s2/MiniProject2)**:  
  Cortex-M4 기반 STM32F 보드와 PIR·플레임·진동·가스 센서 등을 활용하여 화재, 가스 누출, 지진 등을 감지하는 알람 시스템을 구축.
  NTP 서버와 기상청 API를 통해 현재 시간을 동기화하고 날씨 정보를 받아오며, 온습도 센서(DHT11)를 연동하여 실내 온도 자동 조절 및 자동 환기 기능을 구현.
  
- 🕒 **[디지털 원격 제어 시계](https://github.com/kim20s2/MiniProject1)**:  
  Cortex-M4 기반 STM32F 보드에 LCD1602, DS1302 RTC 모듈, IR 수신기 및 리모컨, WiFi 모듈 등을 결합하여 디지털 원격 제어 시계를 제작.
  리모컨으로 시간을 설정하고, WiFi를 통해 NTP 서버와 동기화하여 정확한 시간을 유지할 수 있으며, 알람 기능도 함께 제공.


---

## 🛠 기술 스택

🧱 Core Languages & Essentials : 
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

🧠 Edge AI / ML : 
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![OpenVINO](https://img.shields.io/badge/OpenVINO-632CA6?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-4285F4?style=flat-square&logo=google&logoColor=white)
![Ultralytics%20YOLO](https://img.shields.io/badge/Ultralytics%20YOLO-0A66C2?style=flat-square&logo=ultralytics&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Intel Geti](https://img.shields.io/badge/Intel%20Geti-0071C5?style=flat-square&logo=intel&logoColor=white)

🎥 Vision I/O & Streaming : 
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![GStreamer](https://img.shields.io/badge/GStreamer-FF6F00?style=flat-square&logo=gstreamer&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![RTSP](https://img.shields.io/badge/RTSP-232F3E?style=flat-square)
![V4L2](https://img.shields.io/badge/V4L2-5E5E5E?style=flat-square)
![Intel%20RealSense](https://img.shields.io/badge/Intel%20RealSense-0071C5?style=flat-square&logo=intel&logoColor=white)

🟩 NVIDIA Jetson & 🟨 Hailo : 
![Jetson%20Nano](https://img.shields.io/badge/Jetson%20Nano-76B900?style=flat-square&logo=nvidia&logoColor=white)
![JetPack](https://img.shields.io/badge/JetPack-76B900?style=flat-square&logo=nvidia&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![cuDNN](https://img.shields.io/badge/cuDNN-76B900?style=flat-square&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![HailoRT](https://img.shields.io/badge/HailoRT-FF3366?style=flat-square)
![TAPPAS](https://img.shields.io/badge/TAPPAS-FF3366?style=flat-square)
![DFC](https://img.shields.io/badge/DFC-FF3366?style=flat-square)
![HEF](https://img.shields.io/badge/HEF-FF3366?style=flat-square)

🔧 Embedded / RTOS & HW I/O : 
![Linux%20Embedded](https://img.shields.io/badge/Linux_Embedded-000000?style=flat-square&logo=linux&logoColor=white)
![BSP](https://img.shields.io/badge/BSP-007ACC?style=flat-square)
![ARM](https://img.shields.io/badge/ARM-0091BD?style=flat-square)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square)
![STM32CubeMX/HAL](https://img.shields.io/badge/STM32CubeMX/HAL-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-2C3E50?style=flat-square)
![Keil%20uVision](https://img.shields.io/badge/Keil%20uVision-0091BD?style=flat-square&logo=arm&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![Firmware](https://img.shields.io/badge/Firmware-555555?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-444444?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-444444?style=flat-square)
![UART](https://img.shields.io/badge/UART-444444?style=flat-square)
![PWM](https://img.shields.io/badge/PWM-444444?style=flat-square)
![GPIO](https://img.shields.io/badge/GPIO-444444?style=flat-square)

🌐 Backend / Data : 
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![REST%20API](https://img.shields.io/badge/REST%20API-4A90E2?style=flat-square)
![JSON](https://img.shields.io/badge/JSON-333333?style=flat-square&logo=json&logoColor=white)
![XML](https://img.shields.io/badge/XML-8A2BE2?style=flat-square)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![NTP](https://img.shields.io/badge/NTP-1E90FF?style=flat-square)

🖥 OS / Tools & Docs : 
![Linux%20(Ubuntu)](https://img.shields.io/badge/Linux%20(Ubuntu)-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnu-bash&logoColor=white)
![Microsoft%20Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=flat-square&logo=microsoft-office&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-22314E?style=flat-square)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=qt&logoColor=white)
![GitHub%20Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)
![Mermaid](https://img.shields.io/badge/Mermaid-1F8ACB?style=flat-square)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)

---

## 📊 GitHub Stats

![Your GitHub Stats](https://github-readme-stats.vercel.app/api?username=kim20s2&show_icons=true&theme=tokyonight)

📫 궁금한 점이 있다면 언제든지 연락 주세요!
