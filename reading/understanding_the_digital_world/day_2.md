# 2일 : 프로세서 속도와 심장 박동수

## 폰 노이만 아키텍처 (von Neumann architecture)

> **프로세서, 메모리(명령어 + 데이터 저장), 입력 장치, 출력 장치**<br>
> 가 있는 컴퓨터의 기본 구조. 1940년대부터 이어져오는 표준

<br>

**프로세서 (CPU, 이제는 프로세서라고 더 많이 불림)**<br>→ 산술 연산과 제어 기능을 제공

**주 기억 장치 (RAM), 보조 기억 장치 (디스크, 드라이브)**<br>→ 기억과 저장을 담당

**키보드, 마우스, 디스플레이**<br>→ 운영자와 상호작용을 함

<br>

## 프로세서

**컴퓨터의 두뇌**

- 산술 연산을 하고, 데이터를 여기저기로 옮기고, 다른 구성 요소의 작업을 제어함
- 엄청나게 빠른 속도로 연산을 함
- 기존 계산 결과를 바탕으로 다음에 수행할 연산을 결정함

<br>

**프로세서의 속도**

- 1초에 수행할 수 있는 연산이나 명령어의 개수로 측정
- 기본 연산 수행 단위 = 클록 (clock)
- 2.2GHz 프로세서라면 1초에 22억번(클록) 연산한다는 것

<br>

## 주 기억 장치 (primary memory)

프로세서가 **현재 작업중인 데이터** 뿐만 아니라,<br>
프로세서가 그 데이터로 무엇을 해야하는지 알려주는 **명령어까지** 저장이 됨

> **프로그램 내장식 컴퓨터 (stored-program computer)**<br>
> 메모리에 다른 명령어를 로드하여 프로세서가 다른 계산을 수행할 수 있음<br>
> → 컴퓨터가 하나의 기계로 다양한 일을 수행하는 **범용 장치**가 될 수 있는 이유

<br>

**Random Access Memory (임의 접근 메모리) 라고 불리는 이유는?**

프로세서가 주 기억 장치에 있는 정보에 접근할 때 저장된 위치와 무관하게 같은 속도로 접근할 수 있어서<br>
cf) 비디오 테이프 : 위치까지 감아야 함 (순차적 접근)