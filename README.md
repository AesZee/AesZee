<div align="center">

# Hi, I'm Aes Lee

### Robotics, AI, XR, and human-centered systems
### 로보틱스, AI, XR, 사람 중심 시스템을 만듭니다

[![GitHub](https://img.shields.io/badge/GitHub-AesZee-181717?style=flat-square&logo=github)](https://github.com/AesZee)
[![ROS 2](https://img.shields.io/badge/ROS%202-Humble-22314E?style=flat-square&logo=ros)](https://docs.ros.org/en/humble/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Unity](https://img.shields.io/badge/Unity-2022.3-000000?style=flat-square&logo=unity)](https://unity.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

I build systems where robots, simulations, AI, AR interfaces, and people meet. My work spans ROS 2 robotics, Isaac Sim simulation, collaborative robot systems, perception pipelines, WebXR prototypes, and practical validation workflows.

로봇, 시뮬레이션, AI, AR 인터페이스, 사람이 만나는 지점을 다룹니다. ROS 2 로보틱스, Isaac Sim 시뮬레이션, 협동로봇 시스템, perception 파이프라인, WebXR 프로토타입, 실제 검증 흐름을 중심으로 작업하고 있습니다.

## What I Work On

- Robotics systems with ROS 2, Nav2, SLAM, AMR control, cobots, and sensor integration
- Simulation and validation with Isaac Sim, TurtleBot4, scripted tests, and repeatable acceptance checks
- AI/perception workflows using YOLO, camera-to-robot calibration, STT/TTS, and task orchestration
- XR and spatial interfaces with Unity, Needle Engine, WebXR, and AR-GUI prototypes
- Team-based development across implementation, documentation, testing, review, and integration

## 관심 분야

- ROS 2, Nav2, SLAM, AMR 제어, 협동로봇, 센서 통합 기반 로보틱스 시스템
- Isaac Sim, TurtleBot4, scripted test, acceptance check를 활용한 시뮬레이션 및 검증
- YOLO, 카메라-로봇 좌표 변환, STT/TTS, task orchestration 기반 AI/perception 워크플로우
- Unity, Needle Engine, WebXR, AR-GUI를 활용한 XR 및 공간 인터페이스
- 구현, 문서화, 테스트, 리뷰, 통합이 함께 움직이는 팀 기반 개발

## Owned Projects
## 개인 / 소유 레포 프로젝트

### [isaac4.5_turtlebot4](https://github.com/AesZee/isaac4.5_turtlebot4)

TurtleBot4 simulation project built around Isaac Sim 4.5 and ROS 2 Humble.

Isaac Sim 4.5와 ROS 2 Humble을 기반으로 한 TurtleBot4 시뮬레이션 프로젝트입니다.

Highlights:

- Integrated TurtleBot4 simulation with ROS 2 topic contracts for `/cmd_vel`, `/odom`, `/tf`, `/scan`, OAK-D RGB/depth, and point clouds
- Added OAK-D style RGB, depth, point cloud, and spatial detection flows for sim-to-hardware parity
- Built lidar, SLAM, mapping, and Nav2 verification gates to catch regressions
- Implemented an Isaac Sim GUI HMI extension with light ring, battery status, dock/undock, teleop, and E-STOP behavior

주요 작업:

- `/cmd_vel`, `/odom`, `/tf`, `/scan`, OAK-D RGB/depth, point cloud 등 ROS 2 토픽 계약에 맞춘 TurtleBot4 시뮬레이션 통합
- 실제 하드웨어와 유사한 흐름을 만들기 위한 OAK-D RGB, depth, point cloud, spatial detection 구성
- lidar, SLAM, mapping, Nav2 기능 검증을 위한 regression guard 구축
- light ring, battery status, dock/undock, teleop, E-STOP을 포함한 Isaac Sim GUI HMI 확장 구현

Tech: `Python`, `ROS 2 Humble`, `Isaac Sim 4.5`, `TurtleBot4`, `SLAM`, `Nav2`, `Shell`, `CMake`

### [AR-GUI_BridgeInspectionInformationDelivery](https://github.com/AesZee/AR-GUI_BridgeInspectionInformationDelivery)

Bachelor's graduation project in Creative Technology at the University of Twente: an AR-based graphical user interface prototype for bridge inspection workflows.

University of Twente Creative Technology 학사 졸업 프로젝트로, 교량 점검 업무를 위한 AR 기반 그래픽 사용자 인터페이스 프로토타입입니다.

Highlights:

- Designed a WebXR AR-GUI for hierarchical, spatial information delivery
- Built with Unity 2022.3 LTS, URP, Needle Engine, JavaScript, HTML, and CSS
- Structured interactive inspection content through trigger-based UI states and level-of-detail views
- Developed under academic supervision, with feedback and review shaping the interaction design

주요 작업:

- 계층적이고 공간적인 정보 전달을 위한 WebXR AR-GUI 설계
- Unity 2022.3 LTS, URP, Needle Engine, JavaScript, HTML, CSS 기반 구현
- trigger 기반 UI 상태와 level-of-detail view를 활용한 인터랙티브 점검 콘텐츠 구성
- 지도와 피드백을 바탕으로 인프라 점검 흐름에 맞는 인터랙션 설계 발전

Tech: `Unity`, `Needle Engine`, `WebXR`, `JavaScript`, `HTML`, `CSS`

## Contributed / Collaborative Projects
## 참여 / 협업 레포 프로젝트

These are public repositories where my GitHub contribution history shows commits, branches, pull requests, or collaborator activity.

아래는 공개 GitHub contribution 기록 기준으로 commit, branch, pull request, collaborator 활동이 확인되는 참여 레포입니다.

### [jinw00ch01/ROKEY7_SECOND_PROJECT](https://github.com/jinw00ch01/ROKEY7_SECOND_PROJECT)

Voice-driven cobot pick-and-place system combining a Doosan M0609 6-DOF cobot, OnRobot RG2 gripper, Intel RealSense camera, Arduino stepper conveyor, web UI, STT/TTS, database integration, and ROS 2 task orchestration.

Doosan M0609 6축 협동로봇, OnRobot RG2 그리퍼, Intel RealSense 카메라, Arduino stepper 컨베이어, 웹 UI, STT/TTS, DB 연동, ROS 2 task orchestration을 결합한 음성 기반 견과류 pick-and-place 시스템입니다.

Contribution focus:

- ROS 2 package integration and task flow documentation
- STT, DB, TTS, robot integration summaries and operational notes
- Work across robotics, perception, backend status syncing, and web UI integration

기여 내용:

- ROS 2 패키지 통합 및 task flow 문서화
- STT, DB, TTS, 로봇 연동
- Data Collecting & AI modeling
- Conveyor Belt Control
- 로보틱스, perception, backend 상태 동기화, 웹 UI 통합 흐름에 참여

Tech: `Python`, `TypeScript`, `ROS 2`, `YOLO`, `FastAPI/Supabase`, `Doosan M0609`, `RealSense`, `Arduino`

### [kjhung8-rgb/final_ws](https://github.com/kjhung8-rgb/final_ws)

ROS 2 workspace for a factory and industrial fire rescue robot project, including team-wide interfaces, coverage planning, Nav2 navigation, survivor perception, database bridge, and bringup packages.

공장 및 산업 화재 구조 로봇 프로젝트를 위한 ROS 2 workspace입니다. 팀 공통 인터페이스, coverage planning, Nav2 navigation, survivor perception, DB bridge, bringup 패키지를 포함합니다.

Contribution focus:

- ROS 2 workspace development and integration
- Navigation, perception event publishing, shared interfaces, and bringup structure
- Team-oriented robotics package organization

기여 내용:

- ROS 2 workspace 개발 및 통합
- navigation, perception event publishing, shared interface, bringup 구조 작업
- 팀 단위 로보틱스 패키지 구조화에 참여
- Computer Vision based Detection
- Extracting Coordinates from the detected objects 

Tech: `Python`, `ROS 2`, `Nav2`, `SLAM`, `ament_python`, `ament_cmake`, `Shell`, `CMake`

### [dev-kibeom/cobot3](https://github.com/dev-kibeom/cobot3)

ROS 2 smart factory FMS project using AMR movement, Doosan M0609 manipulator control, vision recognition, MQTT triggers, FastAPI central server, SQLite database, Isaac Sim assets, and dashboard components.

AMR 이동, Doosan M0609 매니퓰레이터 제어, 비전 인식, MQTT trigger, FastAPI 중앙 서버, SQLite DB, Isaac Sim asset, dashboard 구성 요소를 사용하는 ROS 2 기반 스마트 팩토리 FMS 프로젝트입니다.

Contribution focus:

- Collaborator activity, feature/fix branches, and pull request work
- URDF/path environment fixes and ROS 2 integration support
- Smart factory robotics workflow exploration

기여 내용:

- collaborator 활동, feature/fix branch, pull request 작업
- URDF/path 환경 수정 및 ROS 2 통합 지원
- Omniverse 에셋 환경
- Nucleus Server 관리 
- 스마트 팩토리 로보틱스 워크플로우 탐색

Tech: `Python`, `C++`, `ROS 2`, `Nav2`, `BehaviorTree.CPP`, `MQTT`, `FastAPI`, `SQLite`, `Isaac Sim`

### [MatArmndo/AI_Project_12](https://github.com/MatArmndo/AI_Project_12)

Public contribution history shows Python-based AI project work.

- 한자 8가지를 CNN을 기반으로 분류
- 실시간 분류에 따른, 다른 시각화 혹은 Gamified Interaction
  
Tech: `Python`, `AI`

## Toolbox
## 기술 도구

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,ts,js,html,css,bash,cmake" alt="Languages and build tools" />
  <br />
  <img src="https://skillicons.dev/icons?i=ros,unity,react,vite,fastapi,sqlite,supabase,firebase,docker,github,arduino" alt="Frameworks, platforms, and tools" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ROS%202-Humble-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS 2 Humble" />
  <img src="https://img.shields.io/badge/Nav2-Navigation-0B6E4F?style=flat-square" alt="Nav2" />
  <img src="https://img.shields.io/badge/SLAM-Mapping-4B5563?style=flat-square" alt="SLAM" />
  <img src="https://img.shields.io/badge/Isaac%20Sim-NVIDIA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Isaac Sim" />
  <img src="https://img.shields.io/badge/TurtleBot4-Robotics-0A66C2?style=flat-square" alt="TurtleBot4" />
  <img src="https://img.shields.io/badge/Doosan%20M0609-Cobot-1E40AF?style=flat-square" alt="Doosan M0609" />
  <img src="https://img.shields.io/badge/YOLO-Vision-111827?style=flat-square" alt="YOLO" />
  <img src="https://img.shields.io/badge/RealSense-Depth%20Camera-0071C5?style=flat-square&logo=intel&logoColor=white" alt="Intel RealSense" />
  <img src="https://img.shields.io/badge/OAK--D-RGB%2FDepth-5B21B6?style=flat-square" alt="OAK-D" />
  <img src="https://img.shields.io/badge/MQTT-Messaging-660066?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT" />
  <img src="https://img.shields.io/badge/Needle%20Engine-WebXR-2F855A?style=flat-square" alt="Needle Engine" />
  <img src="https://img.shields.io/badge/WebXR-Spatial%20Web-0F766E?style=flat-square" alt="WebXR" />
</p>

```text
Robotics      ROS 2, Nav2, SLAM, AMR, cobots, TurtleBot4, Doosan M0609
Simulation    Isaac Sim, robot validation, scripted testing
AI / Vision   YOLO, RealSense, OAK-D-style RGB/depth, perception pipelines
Backend       FastAPI, SQLite, Supabase, Firebase, MQTT
Frontend/XR   Unity, Needle Engine, WebXR, React/Vite, AR-GUI
Languages     Python, C++, TypeScript, JavaScript, HTML, CSS, Shell, CMake
```

## GitHub Snapshot
## GitHub 한눈에 보기

<div align="center">

![AesZee's GitHub stats](https://github-readme-stats.vercel.app/api?username=AesZee&show_icons=true&theme=tokyonight&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AesZee&layout=compact&theme=tokyonight&hide_border=true)

</div>

## Let's Connect
## 연락 및 관심사

I'm interested in robotics, AI, AR interfaces, human-centered technology, and tools that make complex physical systems easier to understand and operate.

로보틱스, AI, AR 인터페이스, 사람 중심 기술, 그리고 복잡한 물리 시스템을 더 쉽게 이해하고 조작할 수 있게 만드는 도구에 관심이 있습니다.

You can find my work here on GitHub: [github.com/AesZee](https://github.com/AesZee)

제 작업은 GitHub에서 확인할 수 있습니다: [github.com/AesZee](https://github.com/AesZee)
