# 미로탐색(DFS)
7 * 7 격자판 미로를 탈출하는 경로의 가지수를 출력하는 프로그램을 작성하세요. 출발점은 격자의 (1 ,1) 좌표이고, 탈출 도착점은 (7, 7)좌표이다. 격잪나의 1은 벽이고, 0은 통로이다. 격자판의 움직임은 상하좌우로만 움직인다. 미로가 다음과 같다면<br>
<table>
    <tr>
        <td>출발</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
    </tr>
    <tr>
        <td>0</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0</td>
    </tr>
    <tr>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
    </tr>
    <tr>
        <td>1</td>
        <td>1</td>
        <td>0</td>
        <td>1</td>
        <td>0</td>
        <td>1</td>
        <td>1</td>
    </tr>
    <tr>
        <td>1</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
    </tr>
    <tr>
        <td>1</td>
        <td>1</td>
        <td>0</td>
        <td>1</td>
        <td>1</td>
        <td>0</td>
        <td>0</td>
    </tr>
    <tr>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>도착</td>
    </tr>
</table>
<br>
위의 지도에서 출발점에서 도착점까지 갈 수 있는 방법의 수는 8가지이다.<br>
<br>
■ 입력설명<br>
7 * 7 격자판의 정보가 주어집니다.<br>
<br>
■ 입력예제 1<br>
0 0 0 0 0 0 0<br>
0 1 1 1 1 1 0<br>
0 0 0 1 0 0 0<br>
1 1 0 1 0 1 1<br>
1 1 0 0 0 0 1<br>
1 1 0 1 1 0 0<br>
1 0 0 0 0 0 0<br>
<br>
■ 출력예제 1<br>
8
