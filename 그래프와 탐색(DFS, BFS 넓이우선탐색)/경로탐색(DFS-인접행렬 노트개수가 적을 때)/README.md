# 경로 탐색(인접행렬)
방향그래프가 주어지면 1번 정점에서 N번 정점으로 가는 모든 경로의 가지 수를 출력하는 프로그램을 작성하세요. 아래 그래프에서 1번 정점에서 5번 정점으로 가는 가지수는<br>
1 2 3 4 5<br>
1 2 5<br>
1 3 4 2 5<br>
1 3 4 5<br>
1 4 2 5<br>
1 4 5<br>
총 6 가지입니다.<br>
<br>
■ 입력설명<br>
첫째 줄에는 정점의 수 N(1<=N<=20)와 간선의 수 M가 주어진다. 그 다음부터 M줄에 걸쳐 연결정보가 주어진다.<br>
<br>
■ 출력설명<br>
총 가지수를 출력한다.<br>
<br>
■ 입력예제 1<br>
5 9<br>
1 2<br>
1 3<br>
1 4<br>
2 1<br>
2 3<br>
2 5<br>
3 4<br>
4 2<br>
4 5<br>
<br>
■ 출력예제 1<br>
6