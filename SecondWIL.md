# 다중 상속을 사용하지 않는 이유
1. 다이아몬드 문제

 한 클래스가 두 개 이상의 부모 클래스로부터 동일한 멤버를 상속받을 수 있음
 
 같은 이름의 멤버를 가지고 있을 때 어떤 부모 클래스의 멤버를 사용해야 하는지 모호해짐
 
2. 설계의 복잡성 문제

 다중 상속을 사용하면, 클래스간의 관계가 복잡해진다, 클래스가 다중 상속을 받을 경우
 
어떤 클래스로 부터 어떤 멤버를 상속받을지 걱정해야한다 

3. 이름 충돌과 충돌 해결의 어려움

다중 상속을 허용하면, 여러 부모 클래스로부터 상속 받은 멤버들이 이름을 충돌할 수 있다

충돌하는 멤버를 재정의해야 하거나, 명시적으로 부모 클래스를 지정해야 할 수 있다

4. 설계의 일관성과 단순성 유지

c#은 단일 상속을 통해 설계의 일관성과 단순성을 유지하고자 한다

단일 상속을 통해 클래스 간의 관계를 명확하게 만들고, 코드의 가독성과 이해도를 높일 수 있다

# 인터페이스를 사용하는 이유
1. 코드의 재사용성
2. 다중 상속 제공
3. 유연한 설계
## 인터페이스 특징
1. 인터페이스란 클래스가 구현해야 하는 멤버들을 정의하는 것이다
2. 클래스의 일종이 아니며, 클래스에 대한 제약 조건을 명시하는 것이다
3. 인터페이스는 다중 상속을 지원한다
