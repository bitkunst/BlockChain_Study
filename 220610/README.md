# 블록 연결

새로운 블록을 만들 때 필요한 데이터
<br>
이전 블록의 정보 + 데이터
<br>
<br>

# POW

작업증명.
<br>
hash -> 16진수
<br>
hex-to-binary -> 16진수를 2진수로,,
<br>
2진수로 변환된 값에서 앞에 0이 몇개 붙었는가를 찾는게 POW.
<br>
블록 속성으로 들어가는 nonce 값을 바꿔가면서 알맞는 해시값을 찾는다.
<br>
<br>

# 난이도

블록이 생성되는 평균 시간을 구한다.
<br>
ex) 평균적으로 블록을 생성할 때 10분 정도 걸리게끔 하고 싶다. 그리고 평균시간을 구하는 블록 개수를 10개로 하겠다.
<br>
<br>

# 작업 순서

목적은 마이닝 구현

1. 체인 구현
2. 난이도 구현
3. 마이닝 구현