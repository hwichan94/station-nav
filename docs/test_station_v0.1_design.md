# Test Station v0.1

## Purpose
STATION-NAV의 Occupancy Map / Nav2 / Semantic Costmap 실험용
가상 소형 도시철도 역사.

## Size
- 40m × 20m
- 단층 대합실층

## Spatial classification
- Free: 일반 통로, 대합실
- Blocked: 벽, 계단 개구부, 로봇 금지구역
- High Cost: 혼잡구역, 좁은 통로
- Conditional: 서비스구역, 특정 접근구역

## Future mapping
Occupancy Map:
- 벽
- 고정 장애물
- 계단 개구부
- 통행 불가능 영역

Semantic / Costmap:
- 혼잡구역
- 위험구역
- 조건부 접근
- 고비용 이동구역