# Monocular SLAM

## 개요
- 단안 카메라를 이용하여 3D 맵을 생성하여 ROS2의 NAV2와 연동하여 주행을 목표로 하는 프로젝트

## 개발 환경
### 운영체제
- Ubuntu 22.04 ARM64
### ROS 버전
- ROS2 Humble
### C++ 버전
- C++17

### 라이브러리
- OpenCV
- Eigen
- Sophus
- Gazebo

## 진행 예정 단계
- [ ] 개발 환경 구축하기
    - [ ] 개발 환경 설치 스크립트 작성하기        
        - [ ] ROS2 설치
        - [ ] 라이브러리 설치
        - [ ] Turtlebot3 및 AWS Small Warehouse 모델 기반 Gazebo 환경 구현
- [ ] Monocular Visual SLAM 구현에 필요한 이론 학습하기
- [ ] Monocular Visual SLAM을 구현해보기
	- [ ]  Localizer를 KISS-ICP로 변경하기
- [ ] 구현한 Monocular Visual SLAM을 이용하여 맵 만들기
	- [ ] 맵 생성 및 저장
- [ ] 만든 맵으로 NAV2에서 주행해보기
	- [ ] Localizer를 KISS-ICP로 변경하기
