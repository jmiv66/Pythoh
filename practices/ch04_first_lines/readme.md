# 코드의 첫 번째 줄에 대한 연습

## 개요

이 섹션에서는 동영상에서 배운 개념을 연습할 수 있는 기회가 주어집니다. 먼저, 여러분이 유념해야 할 핵심 개념들을 검토해보십시오. 그런 다음 아래의 연습문제를 살펴보십시오.

기억하십시오, 이것들은 여러분의 이익을 위한 것입니다. 만약 여러분이 특정한 연습이 가치가 없다고 발견되거나 너무 오랫동안 걸려있다면, 그것들을 건너뛰어도 좋습니다.

## 핵심개념

### REPL

REPL은 Read-Evaluation-Print-Loop의 약자로 터미널 / 명령 프롬프트에 `python` 을 입력할 때 얻을 수 있는 대화형 환경입니다. 맥os와 리눅스에서는 `python3`을 입력하여 REPL을 시작한다는 것을 기억하십시오.

### 변수 및 값

변수는 우리가 변경될 수 있거나 직접 쓰기에 복잡한 데이터를 참조하기 위해 사용하는 이름입니다. 값은 현재 해당 변수에 할당된 데이터입니다. 우리는 이것을 탐구하기 위해 [pythontutor.com](http://pythontutor.com) 를 이용했습니다.

예:

```python
x = 7
y = 11
z = x + 2*y 
name = 'Sarah'
```

### 기본 제공 라이브러리 사용

파이썬은 많은 라이브러리를 포함합니다. ([hundreds!](https://docs.python.org/3/library/)) `sys`같은 라이브러리 중 하나를 사용하려면 파이썬에게 로드하고 싶다고 말해야합니다. 이것은 `import` 키워드로 합니다.

예:

```python
import sys
print(f"파이썬의 현재 버전은 {sys.version_info}")
```

### 사용자로부터 입력을 가져오는 것

사용자로부터 입력을 받는 것은 `input` 함수로 이루어 집니다.

Example:

```python
name = input("이름이 뭐예요? ")
print(f"Hello {name}")
```

#### 데이터 변환

연산(수학 및 문자열 연결 등)에는 올바른 데이터 유형이 필요합니다.

데이터는 유형명(int,float 등)을 사용하여 숫자형으로 변환한다. 여기 몇 가지 예가 있습니다.

```python
text = '7.2'
number       = float(text) # value = 7.2
whole_number = int(number) # value = 7
```

## 연습

이제 여러분 차례입니다. 여기 연습할 몇가지 문제가 있습니다.

1. 파이썬 REPL을 실행하고 Python 3.6 이상인지 확인하십시오.
2. 정수인 변수를 만들어 그 변수의 제곱과 큐브를 계산합니다.(즉, x^2 와 x^3, 하지만 필요한 파이썬 코드는 아닙니다.)
3. 사용자 이름과 나이를 물어봅니다. 그들에게 여러분이 그들보다 몇 살 더 먹었는지 알려주는 코드를 작성하십시오. ( 지금은 젊음을 위한 음수가 괜찮습니다.)
4. 내장된 라이브러리 `datetime` 과 `datetime.datetime.now()` 함수를 사용하여 현재 연도를 결정하고 f-문자열을 사용하여 REPL에 출력합니다.
5. 이러한 코드 세트 중 하나를 취하여 [pythontutor.com](http://pythontutor.com/visualize.html#mode=edit) 로 시각화합니다.
