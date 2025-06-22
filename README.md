# TurtleBot3 SLAM & Navigation 실습

본 프로젝트는 TurtleBot3 Waffle Pi와 ROS Melodic 환경에서 SLAM 및 자율주행(Navigation)을 실습한 결과를 정리한 포트폴리오입니다.

## 개요

- ROS 기반 실시간 지도 작성(SLAM)
- RViz에서의 위치 설정 및 경로 탐색(Navigation)
- 파라미터 튜닝을 통한 성능 향상 실험 포함

## 구성

| 폴더 | 내용 |
|------|------|
| `slam/` | Gmapping SLAM 실행 및 튜닝 실험 |
| `navigation/` | 자율주행 실행 및 경로 최적화 실험 |
| `docs/` | 최종 보고서 PDF 원문 |

## 주요 학습 내용

- ROS 패키지 구성 및 실행 명령 이해
- `map_update_interval`, `inflation_radius` 등 핵심 파라미터의 효과 분석
- 복도 환경에서 실시간 자율주행 테스트
- 시스템 bringup, 오류 해결, 노드 통신 구조 이해

## 결과 예시

### SLAM
![SLAM 지도 예시](slam/map_example.png)

### Navigation
<img src="navigation/goal_set_example.gif" width="500"/>

## 🔗 참고

- [TurtleBot3 매뉴얼](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/)
