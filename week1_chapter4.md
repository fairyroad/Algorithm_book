인트로
<hr>

    -알고리즘은 명료하고 모호하지 않아야 함
    -알고리즘에서 평가기준은 시간과 공간인데 두가지를 모두 잡는 것은 어려움



4.1_알고리즘의 수행시간 측정
<hr>
    
    1.반복문의 시간이 알고리즘의 시간이 됨 -> 함수의 입력같은건 1번만 실행되는 거여서 전체를 놓고 봤을 때는 미미한 차이를 줌(컴퓨터에 따라 시간이 달라짐)
    2.같은 for문이어도 상수값은 버림 ex)코드 4.2처럼 N + 100에서 N값이 무한히 커지면 100은 엄청 미미하기 때문


4.2~4.4_선형시간 및 선형시간이하, 지수시간 알고리즘
<hr>

    1.선형시간 = O(n)
    2.선형시간이하 ex.binary search ( 정렬하는과정은 내가 원하는 것을 찾는과정과는 별개의 알고리즘이므로 알고리즘!!)