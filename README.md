# 임청수 | Embedded & Robotics Software Portfolio

ROS2, 임베디드 제어, 자율주행 로봇을 중심으로 하드웨어와 소프트웨어를 연결하는 프로젝트를 개발했습니다. 센서 데이터 수집부터 모터 제어, 로봇 통신, 인공지능 비전, 웹 모니터링까지 전체 시스템 흐름을 직접 구현하고 검증한 경험을 정리했습니다.

## Portfolio

[포트폴리오 PDF 보기](./portfolio.pdf)

## Featured Projects

### 1. ROS2 기반 코봇 자율주행 시스템

[프로젝트 저장소](https://github.com/koonie404/ros2-cobot-autonomous-navigation)

- Raspberry Pi 4와 ESP32-S3를 Serial micro-ROS로 연동
- LD14P LiDAR 데이터 파싱 및 `LaserScan` 토픽 발행
- SLAM Toolbox를 이용한 실내 지도 생성
- AMCL·Nav2 기반 목표 지점 자율주행 구현
- 엔코더·IMU 기반 Odometry와 TF, URDF RobotModel 구성

`ROS2 Humble` `micro-ROS` `Nav2` `SLAM Toolbox` `C++` `ESP32-S3` `Raspberry Pi`

### 2. Smart Grip Car v1.1

[프로젝트 저장소](https://github.com/koonie404/Smart-Grip-Car-Ver1.1)

- STM32 기반 모터·센서·그립 장치 제어
- Raspberry Pi와 Flask를 이용한 웹 UI 원격 제어
- TACO 기반 18개 폐기물 클래스로 YOLOv8s 모델 학습
- 객체 탐지 결과와 임베디드 제어 시스템 연동 구조 구현

`STM32` `Raspberry Pi` `Flask` `YOLOv8` `C` `Python` `Computer Vision`

### 3. Smart Food Inventory System

[프로젝트 저장소](https://github.com/koonie404/Smart-Food-Inventory-System)

- YOLOv8 객체 탐지와 HSV 색상 분석을 결합한 식품 상태 인식
- 실시간 영상 기반 재고·배식 상태 모니터링
- 인식 결과를 활용한 운영 상태 시각화 구조 구현

`YOLOv8` `OpenCV` `HSV` `Python` `Real-time Monitoring`

## Core Skills

| 분야 | 기술 |
| --- | --- |
| Embedded | STM32, ESP32-S3, C/C++, UART, I2C, SPI, PWM, Encoder, Motor Control |
| Robotics | ROS2 Humble, micro-ROS, Nav2, SLAM Toolbox, TF2, URDF/Xacro, RViz2 |
| AI & Vision | Python, YOLOv8, OpenCV, HSV Image Analysis |
| Web & SBC | Raspberry Pi, Flask, Linux |
| Hardware | 회로·PCB 설계, 센서 연동, 3D 프린팅 부품 적용 |

## Development Focus

- 하드웨어와 상위 애플리케이션 사이의 안정적인 데이터 흐름 설계
- 센서·구동부 문제를 실제 측정과 시연을 통해 검증
- 통신, 제어, 인식, 시각화를 하나의 동작 가능한 시스템으로 통합
