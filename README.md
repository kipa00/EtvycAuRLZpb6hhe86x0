(필요한 경우 대회 전반에 대한 이야기)

# А. le français

*최고 득점자: rubix (1분, 2147483647점)*

(여기에 에디토리얼 입력)

# Ꭺ. No Description 2

*최고 득점자: rubix (1분, 2147483647점)*

**실패는 성공의 어머니다. 일단 문제에 아무 제출이나 해보자.** 정상적인 실행이 되는 코드는 대개 `틀렸습니다` 를 받게 된다. 이 때 소스 코드를 눌러 보면 코드 위에 "다섯 개의 조각을 모아 문제를 완성하자!" 라는 문구를 확인할 수 있다. 다섯 개의 조각이 채점 결과에 대응될 것을 유추할 수 있으며, 특정 채점 결과를 강제할 수 있는 소스 코드를 제출하면 문제에 대한 정보를 얻을 수 있다. 컴파일 에러, 런타임 에러, 시간 초과, 출력 초과, 메모리 초과를 내는 코드를 만드는 것은 어렵지 않으니 각자 해보도록 하자. 모든 정보를 얻었음에도 문제를 못 풀고 있다면, q가 없음에 주의하자.

# ᗅ. 와 쿼리

*최고 득점자: rubix (1분, 2147483647점)*

(여기에 에디토리얼 입력)

# ꓮ. 두 천재들의 대결

*최고 득점자: rubix (1분, 2147483647점)*

시즌 3, 시즌 4는 tvN에서 방영한 <더 지니어스> 시리즈의 시즌 3, 시즌 4를 뜻하며, 문제에서 J, O는 해당 프로그램의 출연자인 장동민, 오현민이다. 그리고 문제에서 설명하는 "이 게임"은 십이장기다. 규칙은 [이 영상](https://youtu.be/AvczH_VEo5I)의 앞부분에서 확인할 수 있다. 

채점 데이터가 주어졌기 때문에, 정답을 미리 구해놓고 하드코딩하는 방법으로 문제를 풀 수 있다. 입력 데이터를 첫 줄에 들어오는 정수로 구분할 수 있어 다음과 같은 형태의 코드를 만들면 된다. 

```python
ans = {6: "0+0+++", 32: "(answer for 1.in)", 29: "(answer for 2.in)", 73: "(answer for 3.in)"}
print('\n'.join(ans[int(input())]))
```

하지만 정답을 구하는 게 어렵다. 장기나 바둑, 체스만큼은 아니지만 가능한 게임 상태의 수가 생각보다 많기 때문에 직접 모든 경우를 따져 보는 것은 불가능에 가깝다.

## 정해

십이장기의 원형인 동물장기(Dobutsu shogi)를 설명하고 있는 [Wikipedia 문서](https://en.wikipedia.org/wiki/D%C5%8Dbutsu_sh%C5%8Dgi)를 확인해보면 Theoretical Result의 Reference로 달려 있는 링크를 확인할 수 있다. 코드를 다운로드받아 컴파일한 뒤, makeAllState와 makeWinLose를 실행하면 된다. 하지만 동물장기와 십이장기의 규칙이 완전히 동일하지는 않기 때문에 해당 규칙이 구현되어 있는 코드 부분을 수정한 뒤 실행해야 한다. 상대편 진영에 새로 말을 놓을 수 없다는 규칙을 추가하기 위해서 `dobutsu.h` 의 `nextMovesForBlack()` 함수 내에 있는 한 줄을 수정하면 된다. 프로그램이 메모리를 꽤 많이 사용한다는 점을 유의하자. 도달 가능한 게임 상태의 수는 총 177,941,677개이며, 출제자는 해당 코드를 실행하는 데 총 3.5시간 정도 걸렸다. 

데이터는 문제 본문에서 언급한 장동민과 오현민의 십이장기 대결을 그대로 가져왔다. 프로그램에 바로 적용할 수는 없지만 거의 모든 에디터에 있는 찾아 바꾸기 기능을 이용하면 된다.

## 기타

자신 있다면 직접 구현하여 풀어도 되지만, 추천하지 않는다. 이걸 구현할 시간과 노력 정도면 적절한 퀄리티의 학사 졸업 논문 한 편 정도를 만들 수 있다. 

온라인 상에서 장동민과 오현민의 십이장기 대국을 분석한 글을 많이 볼 수 있지만, 정확하게 분석한 글은 없는 것으로 보인다. (3.in의 마지막 부분에서 장동민은 큰 실수를 했는데, 거기서 오현민의 이기는 수를 지적하는 글도 찾아보기 어려웠다) 출제자는 두 사람의 대국에 대한 완벽 분석을 글로 쓸 의향이 있지만, 글로 쓰기 위해서는 비기는 수들의 반복 패턴이나 형세 판단에 대한 깊은 이해가 필요하기 때문에 열심히 연구를 하고 있다. 관심 있는 분들은 연락 바랍니다.

# Α. 팩토리얼

*최고 득점자: rubix (1분, 2147483647점)*

(여기에 에디토리얼 입력)

# Ａ. 댓글, 구독, 크리에이터와의 교류

*최고 득점자: rubix (1분, 2147483647점)*

(여기에 에디토리얼 입력)

# $A$. 하이퍼 배열 돌리기

*최고 득점자: rubix (1분, 2147483647점)*

(여기에 에디토리얼 입력)

# A. 진짜 최종 구데기컵 1 경품 당첨자

*최고 득점자: rubix (1분, 2147483647점)*

선택지의 개수를 보면 알 수 있지만, 같은 상 이름 / 경품 이름이 여러 번 쓰일 수 있음에 주의합시다. 문제를 풀기 위해 필요한 정보는 대부분 온라인에 공개되어 있기 때문에, 열심히 정보를 찾아보면 풀 수 있는 문제였습니다.

1. Marathon Edition 우승자
2. Marathon Edition 준우승자 및 ReguIar Edition 준우승자
3. ReguIar Edition 우승자 및 Speedrun Edition 우승자
4. Speedrun Edition 준우승자
5. 이 대회에 참가하지 않은 사람 중 2019년 대회 최고 등수
6. 모든 에디션에서 총점이 160억점에 가장 가까운 사람
7. 홀수와 짝수의 대결 문제의 오류를 발견한 사람
8. 4차 산업 혁명을 기계학습 없이 서브태스크 2까지만 푼 사람 중 추첨
9. 배중률교를 정해가 아닌 방법으로 푼 사람 중 추첨
10. Marathon Edition에서 Nonogram QR을 마지막으로 1점 이상 획득한 사람
11. 연속합 2147483647 첫 0점자
12. Beginning the Hunt 첫 만점자
13. 대회에 참여하였고 A+B (MC)에 제출하지 않은 사람 중 추첨

## 경품 당첨 기준과 당첨자 아이디 매칭하기
- 당첨자 아이디도 13개, 기준도 13개이므로 중복은 없습니다.
- 당첨자 아이디 중 cubelover님은 현재 BOJ 유저가 아닙니다. cubelover님은 BOJ를 탈퇴하면서 제출 기록이 함께 사라졌는데, 현재의 스코어보드와 당첨자 기준이 맞지 않기 때문에 cubelover님이 몇몇 에디션에서 순위권에 들었음을 알 수 있고, 경우를 따져 보면 2번에 해당하는 아이디가 cubelover여야만 모든 것이 맞아떨어집니다. 이렇게 1, 2, 3, 4번에 해당하는 당첨자 아이디를 결정할 수 있습니다.
- 5번에 해당하는 당첨자를 찾기 위해서는 진짜 구데기컵 2018의 스코어보드에 있는 유저들을 1등부터 한 명씩 진짜 최종 구데기컵 2의 스코어보드에서 찾아보면 됩니다.
- 6번에 해당하는 당첨자는 Marathon Edition의 스코어보드를 통해 확인할 수 있습니다.
- 예제는 믿어도 됩니다. 믿을 수 없다면 예제만 잘 출력하는 코드를 제출해 보시면 됩니다. 아무튼 7번에 해당하는 당첨자는 namnamseo님이 맞습니다.
- 추첨이 들어간 8, 9, 13번은 나중에 정하도록 하고, 10번에 해당하는 당첨자는 문제 제출 현황 페이지를 통해 확인할 수 있습니다.
- 11번에 해당하는 당첨자는 문제 제출 현황에서 채점 결과를 "틀렸습니다"로 놓고 검색해보면, 출제자인 16silver가 검수 중에 냈던 코드 하나와 대회 중 제출이 나옵니다.
- 12번에 해당하는 당첨자는 스코어보드 또는 문제 제출 현황에서 확인할 수 있습니다.
- 여기까지 정하고 나면 남는 아이디는 greimul, dotorya, pichulia뿐입니다. 이 중 배중률교를 푼 사람은 dotorya님뿐이며, 남은 두 사람 중 4차 산업 혁명을 서브태스크 2까지만 푼 사람은 pichulia님입니다. 그러므로 13번에 해당하는 당첨자는 greimul님으로 정해집니다. 모두 축하드립니다!

## 경품 당첨 기준과 상 이름 매칭하기
- 상 이름이 문제 정보와 관련이 있는 경우가 많습니다. 문제 내용을 많이 알면 알수록 빠르게 문제를 풀어낼 수 있습니다.
- 상 이름은 대부분의 경우 직관적으로 주어졌습니다. 별도의 설명이 필요 없는 상들은 간단하게만 짚고 넘어가겠습니다.
- QR 분해 상 = 10번
- QA 상 = 7번
- 결근상 = 5번
- You Need a Minecraft 상 = 13번
- "Ghudegy Cup looks too intense for me" 상 = 12번: looks too intense for me를 검색해보면 Roller Coaster Tycoon이 나옵니다. 문제 내용이 Roller Coaster Tycoon과 관련 있는 Beginning the Hunt에 걸려 있는 경품이었습니다.
- Re: 제로부터 시작하는 다이나믹 프로그래밍 상 = 11번: 제로는 11번 당첨 기준인 0점과 연관 있으며, 연속합 문제는 잘 알려진 다이나믹 프로그래밍 문제입니다.
- UPWF 위원회 특별상 = 8번: 문제 내용에 UPWF 위원회가 나온 4차 산업 혁명 문제에 걸려 있는 경품이었습니다.
- 직관주의자상 = 9번: 직관주의 / 직관 논리에서는 배중률을 부정합니다. 이는 9번 기준과 연관이 깊습니다.
- 남은 상 이름은 대상과 장려상, 남은 경품 당첨 기준은 1~4번과 6번입니다. 직접 제출해 보면서 상 이름을 확인할 수 있습니다. 이 부분에 한해서는 직관을 버리는 것이 좋습니다.

## 경품 당첨 기준과 경품 이름 매칭하기

