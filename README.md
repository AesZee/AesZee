<div align="center">

# Hi, I'm Aes Lee

### Robotics simulation, spatial interfaces, and human-centered systems
### 로보틱스 시뮬레이션, 공간 인터페이스, 사람 중심 시스템을 만듭니다

[![GitHub](https://img.shields.io/badge/GitHub-AesZee-181717?style=flat-square&logo=github)](https://github.com/AesZee)
[![Unity](https://img.shields.io/badge/Unity-2022.3-000000?style=flat-square&logo=unity)](https://unity.com/)
[![ROS 2](https://img.shields.io/badge/ROS%202-Humble-22314E?style=flat-square&logo=ros)](https://docs.ros.org/en/humble/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

I build systems where robots, simulations, AR interfaces, and people meet. My recent work focuses on realistic robot simulation with ROS 2 and Isaac Sim, and spatial information delivery through AR/WebXR interfaces. I value collaborative development: turning feedback, supervision, testing notes, and shared iteration into working technical systems.

로봇, 시뮬레이션, AR 인터페이스, 사람이 만나는 지점을 다룹니다. 최근에는 ROS 2와 Isaac Sim 기반의 현실적인 로봇 시뮬레이션, 그리고 AR/WebXR을 활용한 공간 정보 전달 인터페이스에 집중하고 있습니다. 피드백, 지도, 테스트 기록, 반복적인 협업 과정을 실제로 동작하는 기술 시스템으로 연결하는 개발 방식을 중요하게 생각합니다.

Currently exploring:

- Robot simulation pipelines with Isaac Sim, TurtleBot4, ROS 2 Humble, SLAM, Nav2, and sensor integration
- AR and WebXR interfaces for infrastructure inspection and layered information delivery
- Human-machine interaction patterns for physical and simulated robotics systems
- Collaborative workflows that combine implementation, testing, documentation, and review

현재 관심 분야:

- Isaac Sim, TurtleBot4, ROS 2 Humble, SLAM, Nav2, 센서 통합을 활용한 로봇 시뮬레이션 파이프라인
- 인프라 점검과 계층적 정보 전달을 위한 AR/WebXR 인터페이스
- 실제 로봇과 시뮬레이션 로봇을 위한 인간-기계 상호작용 패턴
- 구현, 테스트, 문서화, 리뷰가 함께 움직이는 협업 개발 방식

## Featured Projects
## 대표 프로젝트

### [isaac4.5_turtlebot4](https://github.com/AesZee/isaac4.5_turtlebot4)

TurtleBot4 simulation project built around Isaac Sim 4.5 and ROS 2 Humble.

Isaac Sim 4.5와 ROS 2 Humble을 기반으로 한 TurtleBot4 시뮬레이션 프로젝트입니다.

Collaboration context:

- Developed through iterative implementation, testing, and documentation cycles
- Public contribution history includes work from `AesZee` and `claude`
- Emphasis on reproducible verification so future collaborators can validate robotics behavior quickly

협업 맥락:

- 구현, 테스트, 문서화가 반복되는 방식으로 개발
- 공개 contributor 기록 기준 `AesZee`와 `claude`의 작업이 포함됨
- 이후 협업자가 로봇 동작을 빠르게 검증할 수 있도록 재현 가능한 verification 흐름을 중점적으로 구성

Highlights:

- Integrated TurtleBot4 simulation with ROS 2 topic contracts for `/cmd_vel`, `/odom`, `/tf`, `/scan`, OAK-D RGB/depth, and point clouds
- Added OAK-D style RGB, depth, point cloud, and spatial detection flows for sim-to-hardware parity
- Built lidar, SLAM, mapping, and Nav2 verification gates to catch regressions
- Implemented an Isaac Sim GUI HMI extension with light ring, battery status, dock/undock controls, teleop nudges, and E-STOP behavior
- Created scripted mapping and acceptance checks for repeatable robotics validation

주요 작업:

- `/cmd_vel`, `/odom`, `/tf`, `/scan`, OAK-D RGB/depth, point cloud 등 ROS 2 토픽 계약에 맞춘 TurtleBot4 시뮬레이션 통합
- 실제 하드웨어와 유사한 흐름을 만들기 위한 OAK-D RGB, depth, point cloud, spatial detection 구성
- lidar, SLAM, mapping, Nav2 기능이 깨지지 않도록 검증 게이트 구축
- light ring, battery status, dock/undock, teleop, E-STOP을 포함한 Isaac Sim GUI HMI 확장 구현
- 반복 가능한 로보틱스 검증을 위한 scripted mapping 및 acceptance check 작성

Tech: `Python`, `ROS 2 Humble`, `Isaac Sim 4.5`, `TurtleBot4`, `SLAM`, `Nav2`, `Shell`, `CMake`

기술 스택: `Python`, `ROS 2 Humble`, `Isaac Sim 4.5`, `TurtleBot4`, `SLAM`, `Nav2`, `Shell`, `CMake`

### [AR-GUI_BridgeInspectionInformationDelivery](https://github.com/AesZee/AR-GUI_BridgeInspectionInformationDelivery)

Bachelor's graduation project in Creative Technology at the University of Twente: an AR-based graphical user interface prototype for bridge inspection workflows.

University of Twente Creative Technology 학사 졸업 프로젝트로, 교량 점검 업무를 위한 AR 기반 그래픽 사용자 인터페이스 프로토타입입니다.

Collaboration context:

- Created as an academic graduation project under supervision at the University of Twente
- Developed around infrastructure inspection workflows, with feedback and review shaping the interaction design
- Project documentation credits supervision by Dr. D.V. Le Viet Duc

협업 맥락:

- University of Twente에서 진행한 학사 졸업 프로젝트로 제작
- 인프라 점검 업무 흐름을 중심으로 피드백과 리뷰를 반영하며 인터랙션 설계를 발전시킴
- 프로젝트 문서에는 Dr. D.V. Le Viet Duc 지도교수의 supervision이 명시되어 있음

Highlights:

- Designed a WebXR AR-GUI for hierarchical, spatial information delivery
- Built with Unity 2022.3 LTS, URP, Needle Engine, JavaScript, HTML, and CSS
- Structured interactive inspection content through trigger-based UI states and level-of-detail views
- Deployed a browser-accessible AR prototype for mobile testing

주요 작업:

- 계층적이고 공간적인 정보 전달을 위한 WebXR AR-GUI 설계
- Unity 2022.3 LTS, URP, Needle Engine, JavaScript, HTML, CSS 기반 구현
- trigger 기반 UI 상태와 level-of-detail view를 활용한 인터랙티브 점검 콘텐츠 구성
- 모바일 테스트가 가능한 브라우저 기반 AR 프로토타입 배포

Tech: `Unity`, `Needle Engine`, `WebXR`, `JavaScript`, `HTML`, `CSS`

기술 스택: `Unity`, `Needle Engine`, `WebXR`, `JavaScript`, `HTML`, `CSS`

## Toolbox
## 기술 도구

<p>
  <img src="https://skillicons.dev/icons?i=python,js,html,css,unity,ros,github" alt="Tech stack icons" />
</p>

```text
Robotics      ROS 2, Isaac Sim, TurtleBot4, SLAM, Nav2, sensor simulation
AR / XR       Unity, Needle Engine, WebXR, spatial UI prototyping
Languages    Python, JavaScript, HTML, CSS, Shell, CMake
Focus         Simulation fidelity, HMI, inspection workflows, practical validation
```

## GitHub Snapshot
## GitHub 한눈에 보기

<div align="center">

![AesZee's GitHub stats](https://github-readme-stats.vercel.app/api?username=AesZee&show_icons=true&theme=tokyonight&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AesZee&layout=compact&theme=tokyonight&hide_border=true)

</div>

## Let's Connect
## 연락 및 관심사

I'm interested in robotics, AR interfaces, human-centered technology, and tools that make complex physical systems easier to understand and operate.

로보틱스, AR 인터페이스, 사람 중심 기술, 그리고 복잡한 물리 시스템을 더 쉽게 이해하고 조작할 수 있게 만드는 도구에 관심이 있습니다.

You can find my work here on GitHub: [github.com/AesZee](https://github.com/AesZee)

제 작업은 GitHub에서 확인할 수 있습니다: [github.com/AesZee](https://github.com/AesZee)
