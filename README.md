## 안녕하세요, 이은정입니다 👋

임베디드부터 AI 비전까지 단계적으로 공부하고 있습니다.  
2026년 1월 C 언어로 시작해 현재 Python 기반 컴퓨터 비전 프로젝트를 진행 중입니다.

<br>

## 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Frameworks & Tools**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111111?style=for-the-badge&logo=yolo&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

<br>

## 📌 Projects

### 🔴 영유아 수면 안전 모니터링 시스템
> `Python` `YOLOv8n` `OpenCV` `Arduino` — 2026.05

수면 중 아기의 자세를 실시간으로 감지해 위험 상황을 알리는 시스템.  
카메라 영상에서 정면 / 측면 / 후면 3가지 자세를 분류하고,  
후면 자세가 일정 시간 지속되면 아두이노 LED로 경보를 출력한다.  
YOLOv8n을 커스텀 데이터셋으로 직접 학습했으며, Google Colab GPU를 활용해 학습을 진행했다.

[![Repo](https://img.shields.io/badge/GitHub-바로가기-181717?style=flat-square&logo=github)](https://github.com/2eunjeong2/baby-safety-monitor)

---

### ☕ Spring Boot 웹 서비스 학습
> `Java 17` `Spring Boot 3.2` `JPA` `H2` — 2026.05

『스프링 부트와 AWS로 혼자 구현하는 웹 서비스』 교재를 따라 실습한 백엔드 학습 프로젝트.  
TDD 방식으로 REST API와 JPA 기반 CRUD를 구현했으며,  
MockMvc 단위 테스트, Lombok, DTO 패턴, @EnableJpaAuditing 등을 실습했다.

[![Repo](https://img.shields.io/badge/GitHub-바로가기-181717?style=flat-square&logo=github)](https://github.com/2eunjeong2/freelec-springboot2-webservice-2026)

---

### 👁 OpenCV 영상처리 실습
> `Python` `OpenCV` — 2026.04

10일 과정으로 OpenCV 기초부터 응용까지 단계적으로 학습한 저장소.  
색상 공간 변환, ROI 설정, 컨투어 감지 등 영상처리 핵심 개념을 실습했다.  
이후 baby-safety-monitor 프로젝트의 기반이 된 학습 과정이다.

[![Repo](https://img.shields.io/badge/GitHub-바로가기-181717?style=flat-square&logo=github)](https://github.com/2eunjeong2/OpenCV_practice)

---

### 🤖 ROS 로봇 운영 시스템
> `ROS Noetic` `Ubuntu 20.04` `CMake` — 2026.03

ROS 환경 구축부터 실제 로봇 제어까지 단계적으로 학습한 프로젝트.  
토픽 · 메시지 · 퍼블리셔/서브스크라이버 구조를 이해하고,  
Turtlesim, Gazebo 시뮬레이션과 벽 추종 알고리즘을 직접 구현했다.

[![Repo](https://img.shields.io/badge/GitHub-바로가기-181717?style=flat-square&logo=github)](https://github.com/2eunjeong2/ROS_programming)

---

### 🌐 IoT 서버 개발
> `Python` `Flask` `HTML` `JavaScript` — 2026.02

Flask 기반 웹 서버를 구축하고 센서 데이터를 수집·관리하는 IoT 실습 프로젝트.  
사용자 인증 시스템과 온습도 센서 데이터 수집 API를 구현했으며,  
센서 → 서버 → 웹 대시보드로 이어지는 전체 흐름을 직접 구성했다.

[![Repo](https://img.shields.io/badge/GitHub-바로가기-181717?style=flat-square&logo=github)](https://github.com/2eunjeong2/IoT_Study)

---

### ⚡ Arduino 임베디드 실습
> `C++` `Arduino Uno` — 2026.02

Arduino를 이용해 하드웨어 제어 전반을 단계적으로 학습한 저장소.  
LED, 모터, 초음파 센서, 온습도 센서 제어부터 WiFi TCP 통신, HTTP 요청, 웹 서버 구축까지 실습했다.

[![Repo](https://img.shields.io/badge/GitHub-바로가기-181717?style=flat-square&logo=github)](https://github.com/2eunjeong2/Arduino_study_YH)

---

### 📚 기초 학습
> 2026.01 ~ 2026.03

| 저장소 | 내용 |
|---|---|
| [C 언어 기초](https://github.com/2eunjeong2/hellotest) | 학습 시작점 — 기본 문법과 미니 프로젝트 실습 |
| [Linux 기초](https://github.com/2eunjeong2/linux_test) | 리눅스 명령어 및 Shell 스크립트 기초 학습 |
| [알고리즘 실습](https://github.com/2eunjeong2/Argorithm_practice) | 수업 기반 Python 알고리즘 문제 풀이 |

<br>

## 📬 Contact

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:qwert45640@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=netlify&logoColor=white)](https://leeeunjeong-portpolio.netlify.app/)
