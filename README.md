# TurtleBot3 SLAM & Navigation 실습

본 프로젝트는 ROS 기반의 TurtleBot3 플랫폼을 사용하여 실시간 지도 작성(SLAM)과 자율주행(Navigation)을 실습한 결과를 정리한 포트폴리오입니다.
실내 복도 환경에서의 로봇 위치 인식, 맵 생성, 목표 지점 이동까지의 전체 과정을 직접 수행하며, 핵심 파라미터 실험과 성능 튜닝을 병행했습니다.

---

## 🧩 프로젝트 요약

- 대상 플랫폼: TurtleBot3 Waffle Pi
- 센서: LDS-01 LiDAR
- OS & ROS: Ubuntu 18.04 + ROS Melodic
- 실습 환경: Wi-Fi 기반 Remote PC ↔ SBC 통신
- 주요 기술:
  - `slam_gmapping`을 통한 SLAM
  - `move_base`를 통한 경로 탐색 및 자율주행
  - RViz를 활용한 시각화 및 제어
  - `.yaml` 파라미터 수정 실험

---

## 📁 디렉토리 구성

| 폴더 | 설명 |
|------|------|
| `slam/` | SLAM 관련 실행 명령어, 파라미터 실험 결과 및 지도 이미지 |
| `navigation/` | 자율주행 실행 명령어, 맵 튜닝, 경로 영상 |
| `docs/` | 최종 실습 보고서 PDF 원문 |

---

## 📷 결과 미리보기

### SLAM 지도 작성 결과
![SLAM 지도](slam/map_example.png)

### Navigation 경로 실행 시연
<img src="navigation/goal_set_example.gif" width="500"/>

---

## 🔗 관련 링크

- [TurtleBot3 매뉴얼](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/)
- [SLAM 문서 보기](./slam/README.md)
- [Navigation 문서 보기](./navigation/README.md)
