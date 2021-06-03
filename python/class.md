##### class

- 객체를 만들어내기 위한 설계도이다.
- 연관되어 있는 데이터 속성과 메소드의 집합이다.
- 클래스에는 데이터 속성, 메소드, 생성자, 소멸자 등이 포함된다



``` python
class Car:
    def __init__(self):
        self.color = 0xFF0000    #바다의 색
        self.wheel_size = 16     #바퀴의 색
        self.displacement = 2000 #엔진 배기량
        
    def forward(self): #전진
        pass
    def backword(self): #후진
        pass
    def turn_left(self): #좌회전
        pass
    def turn_right(self): #우회전
        pass    
```



##### object

- 소프트웨어 세계에 구현할 대상
- 클래스로 구현한 실체적 대상
- OOP의 관점에서 클래스의 타입으로 선언되었을때



##### instance

- 설계도를 바탕으로 세계에 구현된 구체적인 실체

- 소프트웨어에 실체화된 객체(메모리에 할당된 객체)

- OOP의 관점에서 객체가 메모리에 할당되어 실제 사용될 때

  