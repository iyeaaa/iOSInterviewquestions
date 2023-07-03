# Struct, Class, Enum의 차이를 설명하시오

|    |struct|clsss|enum|
|:----:|:------:|:-----:|:----:|
|메모리 저장 영역|Stack|Heap|Stack|
|호출방식|call by Value|call by Reference|call by Value|
|상속|불가능|가능|불가능|
|AnyObject로 캐스팅|불가능|가능|불가능|
|initializer|있음|있음|없음|

<br><br>
+) <br><br>
- struct : Stack 영역에 저장되기 때문에, 일반적으로 Class보다 더 나은성능을 보인다.
- enum   : An enumeration defines a common type for a group of related values and enables you to work with those values in a type-safe way within your code.
- class  : 상속이 가능하기에 struct, enum보다 다형성 구현에 더 자유롭다.
- class  : 힙 영역에 저장되는 메모리 해제를 위해 ARC 기법을 사용한다.
- class  : 실행 시 컴파일러가 클래스 인스턴스의 타입을 미리 파악하고 검사할 수 있다.
- class  : 인스턴스가 소멸되며 호출되는 deinit에 원하는 구문을 등록할 수 있다.
