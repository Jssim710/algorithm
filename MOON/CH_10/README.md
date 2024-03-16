# 10 그래프

## 10-6 최단 경로
- 단일 시작점 최단 경로
  - Dijkstra : 음의 가중치를 허용하지 않는 경우
    - Heap을 이용하면 $O(E\log V)$
    - Heap을 이용하지 않으면 $O(E \cdot V)$
  - Bellman-Ford : 음의 가중치를 허용하는 경우
    - $O(E \cdot V)$
- 모든 쌍 최단 경로
  - Floyd-Warshall
    - $\Theta(n^4)$
