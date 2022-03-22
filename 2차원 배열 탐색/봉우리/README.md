# 봉우리
지도 정보가 N*N 격자판에 주어집니다. 각 격자에는 그 지역의 높이가 쓰여있습니다. 각 격자판의 숫자 중 자신의 상하좌우 숫자보다 큰 숫자는 봉우리 지역입니다. 봉우리 지역이 몇 개 있는지 알아내는 프로그램을 작성하세요.<br>
격자의 가장자리는 0으로 초기화 되었다고 가정한다.<br>
만약 N=5 이고, 격자판의 숫자가 다음과 같다면 봉우리의 개수는 10개입니다.<br>
<table>
    <tr>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
    </tr>
    <tr>
        <td>0</td>
<<<<<<< HEAD
        <td style="background-color: gray;">5</td>
=======
        <td style="background-: gray;">5</td>
>>>>>>> a9e70e28f78b2a4533f9132514342cf920c27268
        <td>3</td>
        <td style="background-color: gray;">7</td>
        <td>2</td>
        <td style="background-color: gray;">3</td>
        <td>0</td>
    </tr>
<<<<<<< HEAD
    <tr>
        <td>0</td>
        <td>3</td>
        <td style="background-color: gray;">7</td>
        <td>1</td>
        <td style="background-color: gray;">6</td>
        <td>1</td>
        <td>0</td>
    </tr>
    <tr>
        <td>0</td>
        <td style="background-color: gray;">7</td>
        <td>2</td>
        <td>5</td>
        <td>3</td>
        <td style="background-color: gray;">4</td>
        <td>0</td>
    </tr>
    <tr>
        <td>0</td>
        <td>4</td>
        <td>3</td>
        <td style="background-color: gray;">6</td>
        <td>4</td>
        <td>1</td>
        <td>0</td>
    </tr>
    <tr>
        <td>0</td>
        <td>8</td>
        <td>7</td>
        <td>3</td>
        <td style="background-color: gray;">5</td>
        <td>2</td>
        <td>0</td>
    </tr>
</table>
■ 입력설명<br>
첫 줄에 자연수 N이 주어진다. (N<=N<=50)<br>
두 번째 줄부터 N줄에 걸쳐 각 줄에 N개의 자연수가 주어진다. 각 자연수는 100을 넘지 않는다.<br>
<br>
■ 출력설명<br>
봉우리의 개수를 출력하세요.<br>
<br>
■ 입력예제 1<br>
5<br>
5 3 7 2 3<br>
3 7 1 6 1<br>
7 2 5 3 4<br>
4 3 6 4 1<br>
8 7 3 5 2<br>
<br>
■ 출력예제 1<br>
10
