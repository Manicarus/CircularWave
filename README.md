# Pygame을 이용한 2D 원형파 시뮬레이션

## 개발환경
- Python 2.7.12
- Pygame 1.9.2b6
- PyCharm Community Edition 2016.2
- OS X El Capitan 10.11.6

Pycharm은 Cross Platform IDE이기 때문에, 컴퓨터 운영체제는 그리 신경쓰지 않아도 된다.  
OS X의 경우 Homebrew Package Manager을 이용해서 설치하면 매우 간편하다.  
대다수가 사용할 위도우즈 운영체제의 개발환경 준비 과정은 추가바람.

## 스크린샷

![Screenshot](./Circular_Wave_Screenshot.tiff)

## 설명

객체지향적으로 프로그래밍한다. 마우스로 콘솔의 한 지점을 클릭하면, 그 지점을 중심으로 하는 원형파가 만들어진다. 각 원형파는 일정한 속도로 퍼져나간다.

## 소스코드

[Github - 2D Circular Wave Simulated with PyCharm](https://github.com/Manicarus/CircularWave/blob/master/main.py)

## 한 걸음 더 나아가기

1. 가속도의 개념을 도입해서 물결파가 점점 빨리 퍼져나가도록 만들어보자
2. 마우스 클릭을 하지 않아도 일정 시간마다 임의의 점에서 원형파가 만들어지도록 해보자.