# ` ` 에디토리얼 

## 들어가기 전에 

대회 이름에 대한 좋은 아이디어가 없어서 대회 이름에 공백 하나만 넣었습니다. 이렇게 했더니 [12906번 문제](https://www.acmicpc.net/problem/12096)처럼 **대회 목록에서 대회 링크를 클릭할 수 없게 되었습니다.** 따라서 대회를 참가하기 위해서는 개발자 도구 등을 통해 대회 링크를 찾거나, BOJ 대회 링크 형식인 `https://www.acmicpc.net/contest/view/` 뒤에 대회 번호인 965를 입력하여 진입해야 했습니다. 대회 진입부터 어려웠기 때문에, 참가자의 편의를 위해 대회 홍보글에 대회 링크를 걸어두었습니다. 

* 문제 출처를 클릭하는 것도 어렵게 되었습니다... 
* 문제 번호 역시 좋은 아이디어가 없어서 문제에 할당할 BOJ 번호를 그대로 문제 번호로 사용했습니다. 문제 배점도 문제 번호와 같도록 했습니다. 이로 인해 문제별 배점의 차이가 약간 있었습니다. 
* 문제 **번호의** 순서는 문제를 정할 당시에 등록했던 순서로, 난이도와 큰 관련이 없습니다. 다만 더 많은 사람들이 solved.ac 배경과 뱃지를 얻을 수 있도록, 쉽게 부분 점수를 받을 수 있는 문제를 맨 앞에 배치하기로 하여, 대회 문제 순서는 문제 **번호의 역순**으로 정했습니다. 

## 27907번. The primes contain arbitrarily long arithmetic progressions
_출제자: cozyyg,_
_최고 득점자: - (0분, 27907점)_

## 27906번. 모자 퍼즐
_출제자: jh05013, cozyyg,_
_최고 득점자: - (0분, 27906점)_

## 27905번. Bækj00n Online RPG
_출제자: kipa00,_
_최고 득점자: - (0분, 27905점)_

## 27904번. 키파-틱택토
_출제자: kipa00,_
_최고 득점자: - (0분, 27904점)_

## 27903번. 인생
_출제자: havana723,_
_최고 득점자: - (0분, 27903점)_

## 27902번. CVE: Life is Way Too Short
_출제자: jh05013,_
_최고 득점자: - (0분, 27902점)_

> Bigint's really feel like a neat computer science toy most of the time. We've got them, but what actually uses integers larger than 64 or 128 bits?

2020년에 1,000,000 자리 이상의 정수를 파싱하면 제곱 시간 알고리즘으로 인해 매우 오래 걸린다는 점이 보안 결함 목록(CVE)에 등록되었다. 그로부터 4년 후인 2022년, 파이썬이 긴급 패치되면서 4,300 자리보다 긴 정수를 파싱하려고 하면 오류를 내게 되었고, 이는 당시 큰 파장과 논란을 불러일으켰다.

이 제한을 해제하려면 `sys.set_int_max_str_digits()`을 사용해야 한다.

제목과 지문에 언급된 `CVE`, `4300`, `하위 호환성` 등의 키워드는 모두 이 사태에 대한 레퍼런스이다. 출제자도 과거에 몇 번 언급한 내용이기 때문에, 형평성을 위해 예제 2로부터 무언가 문제가 있음을 유추하게 하고, 관련 정보를 쉽게 찾을 수 있도록 지문을 작성하였다.

BOJ에서는 (이 문제를 제외하고) 이 제한을 기본적으로 해제하기 때문에, 큰 수 A+B 등의 문제에 재채점이 진행되면서 대부분의 코드가 런타임 에러로 바뀌게 되는 일은 볼 수 없게 되었다.

관련 링크:

- [CVE-2020-10735](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-10735)
- [cpython issue #95778: CVE-2020-10735: Prevent DoS by large int<->str conversions](https://github.com/python/cpython/issues/95778)
- [Python doc: Integer string conversion length limitation](https://docs.python.org/3.10/library/stdtypes.html#int-max-str-digits)
- [Int/str conversions broken in latest Python bugfix releases](https://discuss.python.org/t/int-str-conversions-broken-in-latest-python-bugfix-releases/18889)
- [sympy issue #24033: int/str conversions broken by latest CPython bugfix releases](https://github.com/sympy/sympy/issues/24033)
- [A Python security fix breaks (some) bignums](https://lwn.net/Articles/907572/)
- [cpython issue #96834: FAQ for CVE-2020-10735](https://github.com/python/cpython/issues/96834)

## 27901번. 사면수와 삼현수
_출제자: jh05013,_
_최고 득점자: - (0분, 27901점)_

## 27900번. 4차 산업 혁명 2
_출제자: cozyyg,_
_최고 득점자: - (0분, 27900점)_
