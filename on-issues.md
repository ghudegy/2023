# ` ` 이슈 처리 계획

` `는 지문, 데이터 수정 및 재채점 요청 등을 문제마다 다음과 같은 기준으로 처리합니다. 

| # | 제목 | 출제자 | 지문 수정 | 데이터 수정/보완 | 스페셜 저지 수정 | 재채점 |
|---|------|--------|:--------:|:----------:|:--------------:|:-----:|
| [27907](https://www.acmicpc.net/problem/27907) | The primes contain arbitrarily long arithmetic progressions | cozyyg | ✅ | ❌ | ✅ | ✅ |
| [27906](https://www.acmicpc.net/problem/27906) | 모자 퍼즐 | jh05013, cozyyg | ✅ | ✅ | ⬜️ | ✅ |
| [27905](https://www.acmicpc.net/problem/27905) | Bækj00n Online RPG | kipa00 | 🤔 | ❌ | ⬜️ | ❌ |
| [27904](https://www.acmicpc.net/problem/27904) | 키파-틱택토 | kipa00 | ✅ | ✅ | ✅ | ✅ |
| [27903](https://www.acmicpc.net/problem/27903) | 인생 | havana723 | ✅ | ⬜️ | ✅ | ✅ |
| [27902](https://www.acmicpc.net/problem/27902) | CVE: Life is Way Too Short | jh05013 | 🤔 | 🤔 | ⬜️ | ✅ |
| [27901](https://www.acmicpc.net/problem/27901) | 사면수와 삼현수 | jh05013 | 🤔 | ✅ | ⬜️ | ✅ |
| [27900](https://www.acmicpc.net/problem/27900) | 4차 산업 혁명 2 | cozyyg | ✅ | ❌ | ✅ | ✅ |
| [☕](https://www.acmicpc.net/problem/12346) | Proprietary Problem | shiftpsh | ✅ | ⬜️ | ✅ | ✅ |

* ✅: 수정 요청이 있거나 수정이 필요한 상황이 있을 경우 검토 후 수정 진행.
* 🤔: 특정 종류의 수정 요청에 대해서만 검토 후 수정 진행. (사유 후술)
* ❌: 요청이 들어오더라도 차후 수정 계획이 없음. (사유 후술)
* ⬜️: 해당 사항 없음.

## 세부 사항

### [27907](https://www.acmicpc.net/problem/27907). The primes contain arbitrarily long arithmetic progressions

- 데이터
  - 가능한 모든 데이터가 채점 데이터로 들어오므로 추가할 데이터가 없습니다.

### [27905](https://www.acmicpc.net/problem/27905). Bækj00n Online RPG

- 지문
  - 전반적으로 지문이 매우 불명확하게 쓰여 있는 것은 의도되었습니다.
    - 입력 설명의 변수별 최대 제한이 없는 것은 의도되었습니다.
    - 출력 설명의 복사-붙여넣기해야 하는 지문은 의도되었습니다.
    - 지문 내의 트리비아 및 농담은 의도되었습니다.
  - 지문 내에 논리적인 오류가 있는 경우, 검토 후 수정을 진행합니다.
- 데이터
  - 문제의 의도대로라면 데이터의 개수가 많을 필요가 없으며 애초에 입력 데이터의 정의가 불분명하므로, 데이터 추가는 진행하지 않습니다.
  - 혹시 추후 입력 데이터가 틀렸음이 확인되더라도, 문제를 푸는 데에는 큰 지장이 없으므로 데이터 수정 역시 진행하지 않습니다.
- 스페셜 저지
  - 해당 사항이 없습니다.
- 재채점
  - 스페셜 저지가 없고, 데이터를 추가/삭제/변경하지 않으므로 재채점을 할 이유가 없습니다.

### [27904](https://www.acmicpc.net/problem/27904). 키파-틱택토

- 지문
  - 승리 조건이 영상의 형태로 주어지는 것은 의도되었습니다.
  - 다른 지문 요청은 환영합니다.
- 데이터
  - 서브태스크 5의 경우 데이터를 추가하지 않습니다. (서브태스크 4의 결과에서 자동으로 채점됩니다.)
  - 이외의 서브태스크의 경우 데이터 추가를 환영합니다.
- 스페셜 저지
  - 다음 조건을 모두 만족하면 "맞았습니다!!"를 내고, 이외의 경우 "틀렸습니다"를 내야 합니다.
    - 출력의 줄 수와 정답의 줄 수는 같습니다. 출력의 줄을 `out`이라 할 때 대응하는 정답의 줄을 `ans`라 하겠습니다.
    - `out`은 `KIPA WINS`, `HAVANA WINS`, `KIPA DECLARES A WIN`, `HAVANA DECLARES A WIN` 중 하나여야 합니다.
    - 서브태스크 1의 경우, `out.split()[0] == ans.split()[0]`이어야 합니다.
    - 서브태스크 3의 경우, `out.split()[1] == ans.split()[1]`이고 \[`out.split()[0] == ans.split()[0]`이거나 `ans.split()[1] == 'WINS'`\]여야 합니다.
    - 나머지 서브태스크의 경우, `out == ans`여야 합니다.
  - 이렇게 동작하지 않음이 확인될 경우 수정을 진행합니다.
- 재채점
  - 데이터가 추가/변경/삭제되거나, 스페셜 저지가 변경될 경우 재채점을 진행합니다.

### [27903](https://www.acmicpc.net/problem/27903). 인생

- 데이터
  - 이 문제는 데이터가 없습니다.

### [27902](https://www.acmicpc.net/problem/27902). CVE: Life is Way Too Short

- 지문
  - 구대기의 메시지를 포함하여 지문 구성은 모두 의도되었습니다.
  - 사소한 오타는 수정 가능합니다.
- 데이터
  - 특정 조건에서 출력을 하지 않아야 하는 점은 의도되었습니다.

### [27900](https://www.acmicpc.net/problem/27900). 4차 산업 혁명 2

- 데이터
  - 지문에 테스트 케이스가 10개라고 명시되어 있으므로, 데이터 수정 및 추가 요청은 받지 않습니다.

### [☕](https://www.acmicpc.net/problem/12346). Proprietary Problem

- 데이터
  - 이 문제는 데이터가 없습니다.
