# Navigation 파라미터 튜닝

## 비용맵(costmap) 관련 주요 파라미터

| Parameter | 실험값 | 결과 |
|-----------|--------|------|
| `inflation_radius` | 0.2 | 장애물 회피에 실패 |
| 1.2 | 복도 중앙으로 주행 성공 |
| `cost_scaling_factor` | 3 → 6 → 10 | 장애물 회피 반응 예민도 증가 |

### 최종 설정 추천:
```yaml
inflation_radius: 1.2
cost_scaling_factor: 6.0
