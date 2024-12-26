# Riemann Sum = 구분구적법

**구분구적법**을 사용하여 함수의 적분을 시각화하여 수학 생기부를 채우려는 프로젝트(🔥🔥🔥🔥)입니다. `main.py` 파일은 주어진 함수 `f(x) = x^2`에 대해 구분구적법을 적용하여 적분 값을 계산하고, 이를 그래프로 나타냅니다.

## 알고리즘

1. 선언된 함수 `f(x) = x^2` 을 `numpy` 의  `linspace` 함수를 이용하여 x=10 까지 계산합니다.
2. 한국어 지원을 위해, 폰트를 변경해 주고 계산한 함숫값을 `matplotlib` 라이브러리로 그립니다.
3.  `numpy` 의  `linspace` 함수로 미리 계산된 포인트들에 맞춰 직사각형을 그립니다.
4. 직사각형 중간에 그 직사각형의 넓이가 표시됩니다.
5. 위 작업을 계속 반복하여 x=10 까지 직사각형을 그리고 넓이들을 전부 더합니다.
6. 적분 상수를 제외하여 부정적분한 함수 `F(x) = (1/3)*x^3`에 x=10 값을 대입하여 실제 적분 값을 구합니다.
7. 더한 넓이와 실제 적분 값을 출력하여 두 값을 비교할 수 있게 합니다.

## 요구 사항

- Python 3.x
- `matplotlib` 라이브러리
- `numpy` 라이브러리

## 라이브러리 설치 방법

```bash
pip install matplotlib numpy
```

### AI랑 노션으로 마크다운 하니까 겁내 좋다
