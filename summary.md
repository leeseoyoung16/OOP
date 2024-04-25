```Object``` are created from ```classes```

- 객체는 클래스에서 만들어짐

```metohod``` : that can be invoked

- 메소드 : 호출할 수 있는 작업

  eg. makeVisible(), moveHorizontal()

  - method 명, parameter 타입 통틀어 ```signature```라고 함

    eg. void changeSize(int newDiameter) -> changeSize(int)

    
```state``` : set of values stored in th fields

- 속성 : 객체 필드에 저장된 값의 집합

```Instance``` : Any particular object will be an instance of some class

- 인스턴스 : 실체화 된 개념. 

```field``` : characterize an object

- 객체를 특성화 한 것

```
  public class TicketMachine
{
 private int price;
 private int balance;
 private int total;
 Further details omitted.
}
```

```constructor``` : initialize object by assigning inital values to their field

- 생성자 : 필드에 초기값을 할당하여 객체 초기화 함

```
public TicketMachine(int ticketCost)
{
 price = ticketCost;
 balance = 0;
 total = 0;
}
```

```Accessor method``` 

- 접근자 메서드 : 객체의 상태를 반환하거나 조회하는 메서드

```
public int getPrice()
{
 return price;
}
```


```Mutator method``` 

- 객체의 상태를 변경하는 메서드

```
public void setName(String newName) {
        name = newName;
    }
```

```local varables``` : method can inculde shorter-lived variables

- 지역 변수 : 메서드 내에서만 존재
  
```
public int refundBalance()
{
int amountToRefund; // local varables
amountToRefund = balance; 
balance = 0;
return amountToRefund;
}
```

```Abstraction``` : the ability to ignore details of parts to focus attetion on a higher level of a problem.

- 추상화 : 더 높은 수준의 문제에 집중하려고 세부 사항 무시

```Modularization``` : the process of dividing a whole into well-defined part

- 모듈화 : 전체를 나누는 것

  
