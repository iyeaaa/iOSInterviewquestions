# Delegate Pattern

Delegate는 위임자라는 뜻을 지닌다.<br>

일을 '위임시키는 클래스'와 위임받는 '위임자 클래스들'로 이루어진다.<br>
위임시키는 클래스는 위임자 클래스에게 명령을 내리는 역할을 수행하고,<br>
위임자 클래스들은 동일한 일(Protocol에서 채택한 일)을 기존에 일을 하던 방식에서 확장되어 일을 처리한다.

Delegate Pattern으로 코드를 작성해서 객체간의 결합도를 낮추고, 캡슐화시켜서 코드의 재사용성과 유지보수를 쉽게한다<br><br><br>


# Delegate Pattern 을 활용하는 경우

각 버튼을 눌렀을 때 같은 함수를 호출하지만 서로 다르게 처리하는 경우에<br>
해당 함수가 구현된 프로토콜을 각 버튼이 채택해서,<br>
Delegate Pattern으로 위임자가 동작을 처리하는 방식으로 코드를 작성할 수 있다.
