# Prefix Sum (누적 합)

[메인으로 돌아가기](https://github.com/tony9402/baekjoon)

풀어보면 좋을 문제는 추천 문제에 체크(:heavy_check_mark:) 해놨습니다.

추천 문제 아닌 나머지는 나머지를 난이도 섞었습니다.

누적합은 단순히 이 알고리즘만 사용하는 문제보다 누적합과 다른 알고리즘을 섞어 쓰는 경우가 많습니다.

<br>

***❗️❗️꼭 문제를 순서대로 안풀어도 됩니다.❗️❗️***

[백준 문제집](https://www.acmicpc.net/workbook/view/7274)


|순번|추천 문제|문제 번호|문제 이름|난이도|풀이 링크|
|:--:|:--:|:--:|:--:|:--:|:--:|
|000|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/2167" target="_blank">2167</a>|<a href="https://www.acmicpc.net/problem/2167" target="_blank">2차원 배열의 합</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/6.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/2167" target="_blank">바로 가기</a>|
|001|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/14929" target="_blank">14929</a>|<a href="https://www.acmicpc.net/problem/14929" target="_blank">귀찮아 (SIB)</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/14929" target="_blank">바로 가기</a>|
|002|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/20438" target="_blank">20438</a>|<a href="https://www.acmicpc.net/problem/20438" target="_blank">출석체크</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/20438" target="_blank">바로 가기</a>|
|003|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/11660" target="_blank">11660</a>|<a href="https://www.acmicpc.net/problem/11660" target="_blank">구간 합 구하기 5</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/11660" target="_blank">바로 가기</a>|
|004|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/21318" target="_blank">21318</a>|<a href="https://www.acmicpc.net/problem/21318" target="_blank">피아노 체조</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/21318" target="_blank">바로 가기</a>|
|005|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/1749" target="_blank">1749</a>|<a href="https://www.acmicpc.net/problem/1749" target="_blank">점수따먹기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/1749" target="_blank">바로 가기</a>|
|006|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/2015" target="_blank">2015</a>|<a href="https://www.acmicpc.net/problem/2015" target="_blank">수들의 합 4</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/2015" target="_blank">바로 가기</a>|
|007|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/10986" target="_blank">10986</a>|<a href="https://www.acmicpc.net/problem/10986" target="_blank">나머지 합</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/10986" target="_blank">바로 가기</a>|
|008|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/20440" target="_blank">20440</a>|<a href="https://www.acmicpc.net/problem/20440" target="_blank">🎵니가 싫어 싫어 너무 싫어 싫어 오지 마 내게 찝쩍대지마🎵 - 1</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/20440" target="_blank">바로 가기</a>|
|009|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/21757" target="_blank">21757</a>|<a href="https://www.acmicpc.net/problem/21757" target="_blank">나누기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/14.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/21757" target="_blank">바로 가기</a>|
|010|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/20543" target="_blank">20543</a>|<a href="https://www.acmicpc.net/problem/20543" target="_blank">폭탄 던지는 태영이</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/16.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/20543" target="_blank">바로 가기</a>|
|011||<a href="https://www.acmicpc.net/problem/20116" target="_blank">20116</a>|<a href="https://www.acmicpc.net/problem/20116" target="_blank">상자의 균형</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>||
|012||<a href="https://www.acmicpc.net/problem/11659" target="_blank">11659</a>|<a href="https://www.acmicpc.net/problem/11659" target="_blank">구간 합 구하기 4</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/11659" target="_blank">바로 가기</a>|
|013||<a href="https://www.acmicpc.net/problem/17390" target="_blank">17390</a>|<a href="https://www.acmicpc.net/problem/17390" target="_blank">이건 꼭 풀어야 해!</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>||
|014||<a href="https://www.acmicpc.net/problem/11441" target="_blank">11441</a>|<a href="https://www.acmicpc.net/problem/11441" target="_blank">합 구하기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/11441" target="_blank">바로 가기</a>|
|015||<a href="https://www.acmicpc.net/problem/17123" target="_blank">17123</a>|<a href="https://www.acmicpc.net/problem/17123" target="_blank">배열 놀이</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/>||
|016||<a href="https://www.acmicpc.net/problem/16139" target="_blank">16139</a>|<a href="https://www.acmicpc.net/problem/16139" target="_blank">인간-컴퓨터 상호작용</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/>||
|017||<a href="https://www.acmicpc.net/problem/16507" target="_blank">16507</a>|<a href="https://www.acmicpc.net/problem/16507" target="_blank">어두운 건 무서워</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/>||
|018||<a href="https://www.acmicpc.net/problem/5549" target="_blank">5549</a>|<a href="https://www.acmicpc.net/problem/5549" target="_blank">행성 탐사</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>||
|019||<a href="https://www.acmicpc.net/problem/20002" target="_blank">20002</a>|<a href="https://www.acmicpc.net/problem/20002" target="_blank">사과나무</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>||
|020||<a href="https://www.acmicpc.net/problem/10427" target="_blank">10427</a>|<a href="https://www.acmicpc.net/problem/10427" target="_blank">빚</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>||
|021||<a href="https://www.acmicpc.net/problem/19951" target="_blank">19951</a>|<a href="https://www.acmicpc.net/problem/19951" target="_blank">태상이의 훈련소 생활</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>||
|022||<a href="https://www.acmicpc.net/problem/18866" target="_blank">18866</a>|<a href="https://www.acmicpc.net/problem/18866" target="_blank">젊은 날의 생이여</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>||
|023||<a href="https://www.acmicpc.net/problem/20159" target="_blank">20159</a>|<a href="https://www.acmicpc.net/problem/20159" target="_blank">동작 그만. 밑장 빼기냐?</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>||
|024||<a href="https://www.acmicpc.net/problem/10713" target="_blank">10713</a>|<a href="https://www.acmicpc.net/problem/10713" target="_blank">기차 여행</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>||
|025||<a href="https://www.acmicpc.net/problem/2900" target="_blank">2900</a>|<a href="https://www.acmicpc.net/problem/2900" target="_blank">프로그램</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/>||
|026||<a href="https://www.acmicpc.net/problem/16971" target="_blank">16971</a>|<a href="https://www.acmicpc.net/problem/16971" target="_blank">배열 B의 값</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/>|<a href="https://github.com/tony9402/algorithm-solutions/tree/main/solutions/baekjoon/16971" target="_blank">바로 가기</a>|
|027||<a href="https://www.acmicpc.net/problem/3673" target="_blank">3673</a>|<a href="https://www.acmicpc.net/problem/3673" target="_blank">나눌 수 있는 부분 수열</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/>||
|028||<a href="https://www.acmicpc.net/problem/2571" target="_blank">2571</a>|<a href="https://www.acmicpc.net/problem/2571" target="_blank">색종이 - 3</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/>||
|029||<a href="https://www.acmicpc.net/problem/5875" target="_blank">5875</a>|<a href="https://www.acmicpc.net/problem/5875" target="_blank">오타</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/14.svg"/>||
|030||<a href="https://www.acmicpc.net/problem/19566" target="_blank">19566</a>|<a href="https://www.acmicpc.net/problem/19566" target="_blank">수열의 구간 평균</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/14.svg"/>||
|031||<a href="https://www.acmicpc.net/problem/14476" target="_blank">14476</a>|<a href="https://www.acmicpc.net/problem/14476" target="_blank">최대공약수 하나 빼기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/14.svg"/>||