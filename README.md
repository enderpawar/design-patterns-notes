# Design Pattern 정리 노트

Spring 백엔드 개발 관점에서 정리한 디자인 패턴 학습 노트입니다.
아래는 각 패턴별 참고 다이어그램(UML/시퀀스) 이미지와 원문 소스 링크이며,
전체 학습 내용은 [본문](#본문)에 그대로 실려 있습니다.

이미지·소스는 [iluwatar/java-design-patterns](https://github.com/iluwatar/java-design-patterns) (MIT License) 저장소를 참고했습니다.

## 참고 링크

### 생성 패턴 (Creational)

| 패턴 | 참고 다이어그램 | 참고 소스 |
|---|---|---|
| Singleton | ![Singleton](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/singleton/etc/singleton.urm.png) | [singleton](https://github.com/iluwatar/java-design-patterns/tree/master/singleton) |
| Factory Method | ![Factory Method](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/factory-method/etc/factory-method.urm.png) | [factory-method](https://github.com/iluwatar/java-design-patterns/tree/master/factory-method) |
| Abstract Factory | ![Abstract Factory](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/abstract-factory/etc/abstract-factory.urm.png) | [abstract-factory](https://github.com/iluwatar/java-design-patterns/tree/master/abstract-factory) |
| Builder | ![Builder](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/builder/etc/builder.urm.png) | [builder](https://github.com/iluwatar/java-design-patterns/tree/master/builder) |
| Prototype | ![Prototype](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/prototype/etc/prototype.urm.png) | [prototype](https://github.com/iluwatar/java-design-patterns/tree/master/prototype) |

### 구조 패턴 (Structural)

| 패턴 | 참고 다이어그램 | 참고 소스 |
|---|---|---|
| Adapter | ![Adapter](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/adapter/etc/adapter.urm.png) | [adapter](https://github.com/iluwatar/java-design-patterns/tree/master/adapter) |
| Decorator | ![Decorator](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/decorator/etc/decorator.urm.png) | [decorator](https://github.com/iluwatar/java-design-patterns/tree/master/decorator) |
| Facade | ![Facade](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/facade/etc/facade.urm.png) | [facade](https://github.com/iluwatar/java-design-patterns/tree/master/facade) |
| Proxy | ![Proxy](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/proxy/etc/proxy.urm.png) | [proxy](https://github.com/iluwatar/java-design-patterns/tree/master/proxy) |
| Composite | ![Composite](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/composite/etc/composite.urm.png) | [composite](https://github.com/iluwatar/java-design-patterns/tree/master/composite) |
| Bridge | ![Bridge](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/bridge/etc/bridge.urm.png) | [bridge](https://github.com/iluwatar/java-design-patterns/tree/master/bridge) |
| Flyweight | ![Flyweight](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/flyweight/etc/flyweight.urm.png) | [flyweight](https://github.com/iluwatar/java-design-patterns/tree/master/flyweight) |

### 행위 패턴 (Behavioral)

| 패턴 | 참고 다이어그램 | 참고 소스 |
|---|---|---|
| Strategy | ![Strategy](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/strategy/etc/strategy_urm.png) | [strategy](https://github.com/iluwatar/java-design-patterns/tree/master/strategy) |
| Observer | ![Observer](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/observer/etc/observer.png) | [observer](https://github.com/iluwatar/java-design-patterns/tree/master/observer) |
| Template Method | ![Template Method](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/template-method/etc/template_method_urm.png) | [template-method](https://github.com/iluwatar/java-design-patterns/tree/master/template-method) |
| Command | ![Command](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/command/etc/command.png) | [command](https://github.com/iluwatar/java-design-patterns/tree/master/command) |
| State | ![State](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/state/etc/state_urm.png) | [state](https://github.com/iluwatar/java-design-patterns/tree/master/state) |
| Iterator | ![Iterator](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/iterator/etc/iterator.png) | [iterator](https://github.com/iluwatar/java-design-patterns/tree/master/iterator) |
| Mediator | ![Mediator](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/mediator/etc/mediator.png) | [mediator](https://github.com/iluwatar/java-design-patterns/tree/master/mediator) |
| Chain of Responsibility | ![Chain of Responsibility](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/chain-of-responsibility/etc/chain-of-responsibility.urm.png) | [chain-of-responsibility](https://github.com/iluwatar/java-design-patterns/tree/master/chain-of-responsibility) |

### GoF 외 — 백엔드/Spring에서 자주 쓰는 개념

| 개념 | 참고 다이어그램 | 참고 소스 |
|---|---|---|
| Repository | ![Repository](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/repository/etc/repository.png) | [repository](https://github.com/iluwatar/java-design-patterns/tree/master/repository) |
| Dependency Injection | ![Dependency Injection](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/dependency-injection/etc/dependency-injection.png) | [dependency-injection](https://github.com/iluwatar/java-design-patterns/tree/master/dependency-injection) |
| MVC | ![MVC](https://raw.githubusercontent.com/iluwatar/java-design-patterns/master/model-view-controller/etc/model-view-controller.png) | [model-view-controller](https://github.com/iluwatar/java-design-patterns/tree/master/model-view-controller) |
| AOP | (Proxy 다이어그램 참고 — Spring AOP는 Proxy 기반으로 동작) | [Spring Framework Reference — AOP](https://docs.spring.io/spring-framework/reference/core/aop.html) |

---

## 본문

# 1. 디자인 패턴이란?

## 1) 개념

디자인 패턴(Design Pattern)은 소프트웨어 설계에서 반복해서 등장하는 문제를 해결하기 위한 대표적인 설계 방법이다.

특정 코드를 그대로 복사해서 사용하는 것이 아니라, 객체 간의 역할과 책임을 어떻게 나눌지에 대한 구조적인 해결책에 가깝다.

예를 들어 다음과 같은 문제들이 있다.

```text
조건문이 계속 늘어난다.
객체 생성 코드가 여러 곳에 흩어져 있다.
공통 기능이 여러 클래스에 반복된다.
객체 간 결합도가 너무 높다.
특정 구현체를 바꾸기가 어렵다.
```

디자인 패턴은 이런 문제들을 조금 더 유지보수하기 좋은 구조로 바꾸는 데 사용한다.

---

# 2. GoF 디자인 패턴

## 1) GoF란?

GoF는 Gang of Four의 약자로, 디자인 패턴을 체계적으로 정리한 네 명의 저자를 의미한다.

GoF 디자인 패턴은 총 23개이며 크게 세 종류로 나뉜다.

```text
생성 패턴
→ 객체를 어떻게 생성할 것인가

구조 패턴
→ 객체들을 어떻게 연결할 것인가

행위 패턴
→ 객체들이 어떻게 역할을 나누고 협력할 것인가
```

---

## 2) 생성 패턴

대표적으로 다음과 같은 패턴이 있다.

```text
Singleton
Factory Method
Abstract Factory
Builder
Prototype
```

생성 패턴의 핵심은 객체 생성 과정을 직접 처리하지 않고 적절한 방식으로 분리하는 것이다.

---

## 3) 구조 패턴

대표적으로 다음과 같은 패턴이 있다.

```text
Adapter
Decorator
Facade
Proxy
Composite
Bridge
Flyweight
```

객체와 객체를 어떤 방식으로 조합할지를 다룬다.

---

## 4) 행위 패턴

대표적으로 다음과 같은 패턴이 있다.

```text
Strategy
Observer
Template Method
Command
State
Iterator
Mediator
Chain of Responsibility
```

객체 간 역할 분담과 동작 방식을 정의한다.

---

# 3. Strategy Pattern

## 1) 개념

Strategy Pattern은 특정 기능을 수행하는 방법이 여러 개 존재할 때 각각의 알고리즘을 별도의 객체로 분리하는 패턴이다.

예를 들어 결제 시스템을 생각해볼 수 있다.

```text
결제

카드 결제
계좌이체
카카오페이
네이버페이
```

이를 단순한 조건문으로 작성하면 다음과 같은 구조가 된다.

```java
public void pay(String type) {

    if (type.equals("CARD")) {
        // 카드 결제
    } else if (type.equals("KAKAO")) {
        // 카카오페이
    } else if (type.equals("NAVER")) {
        // 네이버페이
    }
}
```

결제 방식이 추가될수록 조건문이 계속 증가한다.

Strategy Pattern에서는 각각의 결제 방식을 분리한다.

```java
public interface PaymentStrategy {

    void pay();
}
```

```java
public class CardPayment implements PaymentStrategy {

    @Override
    public void pay() {
        System.out.println("카드 결제");
    }
}
```

```java
public class KakaoPayment implements PaymentStrategy {

    @Override
    public void pay() {
        System.out.println("카카오페이 결제");
    }
}
```

사용하는 쪽에서는 구체적인 결제 방법을 알 필요가 없다.

```java
public class PaymentService {

    private final PaymentStrategy paymentStrategy;

    public PaymentService(PaymentStrategy paymentStrategy) {
        this.paymentStrategy = paymentStrategy;
    }

    public void pay() {
        paymentStrategy.pay();
    }
}
```

---

## 2) 핵심 구조

```text
Context
   ↓
Strategy Interface
   ↓
┌──────────┬──────────┬──────────┐
Card       Kakao      Naver
Strategy   Strategy   Strategy
```

---

## 3) 장점

새로운 기능이 추가되어도 기존 코드를 크게 수정하지 않아도 된다.

```text
기존

Card
Kakao

추가

Toss
```

새로운 `TossPayment` 클래스만 추가하면 된다.

OCP(Open Closed Principle)와 연결되는 대표적인 패턴이다.

---

## 4) 사용하는 상황

다음과 같은 경우에 자주 사용한다.

```text
결제 방식
할인 정책
배송 정책
로그인 방식
파일 저장 방식
알림 전송 방식
검색 알고리즘
정렬 알고리즘
```

---

## 5) Spring에서의 활용

Spring에서는 인터페이스와 여러 구현체를 함께 사용하는 구조가 많기 때문에 Strategy Pattern을 쉽게 볼 수 있다.

```java
public interface NotificationService {

    void send();
}
```

```java
@Component
public class EmailNotificationService
        implements NotificationService {

    public void send() {
        // 이메일
    }
}
```

```java
@Component
public class SmsNotificationService
        implements NotificationService {

    public void send() {
        // SMS
    }
}
```

Spring의 Dependency Injection과 함께 사용하면 구현체를 쉽게 교체할 수 있다.

---

# 4. Singleton Pattern

## 1) 개념

Singleton Pattern은 특정 클래스의 객체가 프로그램 전체에서 하나만 존재하도록 만드는 패턴이다.

```text
Application

        Singleton Object
          ↑     ↑     ↑
Service A      B      C
```

여러 곳에서 동일한 객체를 공유한다.

---

## 2) 기본 구현

```java
public class Singleton {

    private static final Singleton instance
            = new Singleton();

    private Singleton() {
    }

    public static Singleton getInstance() {
        return instance;
    }
}
```

생성자를 `private`으로 만들어 외부에서 객체를 생성하지 못하도록 한다.

```java
new Singleton();
```

위 코드는 사용할 수 없다.

대신 다음과 같이 접근한다.

```java
Singleton instance = Singleton.getInstance();
```

---

## 3) Spring과 Singleton

Spring Bean의 기본 Scope는 Singleton이다.

```java
@Service
public class UserService {

}
```

Spring은 일반적으로 `UserService` 객체를 하나 생성한 뒤 여러 요청에서 공유한다.

```text
Request 1 ─┐
Request 2 ─┼→ UserService
Request 3 ─┘
```

---

## 4) 주의점

Singleton 객체에는 사용자별 상태를 저장하지 않는 것이 좋다.

```java
@Service
public class UserService {

    private String currentUser;
}
```

여러 요청이 하나의 객체를 공유하기 때문에 문제가 발생할 수 있다.

따라서 일반적인 Spring Service는 상태를 가지지 않는 Stateless 구조로 작성한다.

```java
@Service
public class UserService {

    public User findUser(Long userId) {
        ...
    }
}
```

---

# 5. Factory Pattern

## 1) 개념

Factory Pattern은 객체 생성 책임을 별도의 객체나 메서드에 맡기는 패턴이다.

객체를 사용하는 쪽에서 직접 `new`를 호출하지 않도록 한다.

기존 구조는 다음과 같다.

```java
if (type.equals("CARD")) {
    Payment payment = new CardPayment();
} else if (type.equals("KAKAO")) {
    Payment payment = new KakaoPayment();
}
```

객체 생성 코드가 비즈니스 로직과 섞인다.

Factory를 사용하면 생성 책임을 분리할 수 있다.

```java
public class PaymentFactory {

    public Payment create(String type) {

        if (type.equals("CARD")) {
            return new CardPayment();
        }

        if (type.equals("KAKAO")) {
            return new KakaoPayment();
        }

        throw new IllegalArgumentException();
    }
}
```

사용하는 쪽에서는 다음과 같이 사용한다.

```java
Payment payment =
        paymentFactory.create("CARD");

payment.pay();
```

---

## 2) 구조

```text
Client
  ↓
Factory
  ↓
객체 생성

CardPayment
KakaoPayment
NaverPayment
```

---

## 3) 장점

객체 생성 방식이 변경되어도 사용하는 코드를 크게 수정할 필요가 없다.

생성 과정이 복잡할수록 효과가 크다.

---

## 4) 사용하는 상황

```text
조건에 따라 다른 객체를 생성할 때

객체 생성 과정이 복잡할 때

생성 코드를 한 곳에서 관리하고 싶을 때

클라이언트가 구체적인 구현 클래스를 몰라도 되게 하고 싶을 때
```

---

# 6. Builder Pattern

## 1) 개념

Builder Pattern은 객체에 많은 값을 넣어 생성해야 할 때 객체 생성을 읽기 쉽게 만드는 패턴이다.

예를 들어 생성자가 다음과 같다고 하자.

```java
User user = new User(
    "jinwoo",
    24,
    "test@test.com",
    "Seoul",
    "Backend Developer"
);
```

파라미터가 많아질수록 각 값이 무엇을 의미하는지 파악하기 어렵다.

Builder를 사용하면 다음처럼 작성할 수 있다.

```java
User user = User.builder()
        .name("jinwoo")
        .age(24)
        .email("test@test.com")
        .address("Seoul")
        .job("Backend Developer")
        .build();
```

---

## 2) 장점

각 값의 의미를 명확하게 알 수 있다.

```java
.age(24)
.email("test@test.com")
```

또한 선택적인 값이 존재하는 객체를 만들 때 편리하다.

---

## 3) Lombok

Java에서는 Lombok의 `@Builder`를 많이 사용한다.

```java
@Builder
public class User {

    private String name;
    private int age;
    private String email;
}
```

다음과 같이 객체를 만들 수 있다.

```java
User user = User.builder()
        .name("jinwoo")
        .age(24)
        .email("test@test.com")
        .build();
```

---

## 4) 주의점

Builder를 무조건 사용해야 하는 것은 아니다.

필드가 두세 개 정도밖에 없다면 일반 생성자가 더 단순할 수 있다.

```java
new User(name, age);
```

Builder는 필드가 많거나 선택적인 값이 많을 때 사용하는 것이 좋다.

---

# 7. Proxy Pattern

## 1) 개념

Proxy Pattern은 실제 객체 앞에 대리 객체를 두는 패턴이다.

```text
Client

 ↓

Proxy

 ↓

Real Object
```

클라이언트는 실제 객체를 직접 호출하는 것처럼 보이지만 실제로는 Proxy를 거쳐서 호출된다.

---

## 2) 사용 목적

Proxy를 사용하면 실제 비즈니스 로직을 수정하지 않고 추가 기능을 넣을 수 있다.

예를 들어 다음과 같은 기능이 있다.

```text
Logging

Transaction

Authorization

Caching

Execution Time Measurement
```

---

## 3) 예시

실제 서비스가 있다고 하자.

```java
public class OrderService {

    public void order() {
        System.out.println("주문 처리");
    }
}
```

Proxy를 만들 수 있다.

```java
public class OrderServiceProxy {

    private final OrderService orderService;

    public void order() {

        System.out.println("Transaction Start");

        orderService.order();

        System.out.println("Transaction Commit");
    }
}
```

호출 구조는 다음과 같다.

```text
Controller

 ↓

OrderServiceProxy

 ↓

OrderService
```

---

## 4) Spring AOP와 Proxy

Spring AOP는 Proxy를 기반으로 동작한다.

대표적인 예가 `@Transactional`이다.

```java
@Transactional
public void order() {

    ...
}
```

개발자가 직접 다음 코드를 작성하지 않아도 된다.

```java
transaction.start();

order();

transaction.commit();
```

Spring이 Proxy를 통해 트랜잭션 로직을 추가한다.

```text
Controller

 ↓

Proxy

 ↓

Transaction Start

 ↓

OrderService

 ↓

Transaction Commit
```

---

# 8. Template Method Pattern

## 1) 개념

Template Method Pattern은 전체 처리 과정의 구조를 상위 클래스에서 정하고 일부 단계만 하위 클래스가 구현하도록 하는 패턴이다.

예를 들어 게임 실행 과정이 있다고 하자.

```text
게임 시작

↓

게임 진행

↓

게임 종료
```

전체 흐름은 동일하지만 게임 진행 방식만 달라질 수 있다.

```java
public abstract class Game {

    public final void play() {

        start();

        run();

        end();
    }

    void start() {
        System.out.println("게임 시작");
    }

    abstract void run();

    void end() {
        System.out.println("게임 종료");
    }
}
```

각 게임은 `run()`만 구현한다.

```java
public class SoccerGame extends Game {

    @Override
    void run() {
        System.out.println("축구 진행");
    }
}
```

---

## 2) 핵심 구조

```text
Template

start()
run()
end()

↓

일부 단계만 구현

Game A
Game B
Game C
```

---

## 3) 사용하는 상황

전체 처리 흐름은 동일하지만 특정 단계만 다른 경우 사용한다.

```text
파일 처리
데이터 파싱
게임 실행
요청 처리
DB 작업
```

---

# 9. Observer Pattern

## 1) 개념

Observer Pattern은 특정 객체에서 이벤트가 발생하면 다른 객체들에게 이를 알려주는 구조다.

```text
Subject

 ↓ Event

Observer A
Observer B
Observer C
```

예를 들어 회원가입이 완료되면 여러 작업이 실행될 수 있다.

```text
회원가입

↓

이메일 발송

↓

쿠폰 지급

↓

로그 기록
```

회원가입 코드에서 모든 작업을 직접 호출하면 결합도가 높아진다.

```java
public void signup() {

    createUser();

    emailService.send();

    couponService.issue();

    logService.write();
}
```

Observer 구조를 사용하면 회원가입은 이벤트만 발생시킨다.

```text
UserCreatedEvent

 ├ EmailListener
 ├ CouponListener
 └ LogListener
```

---

## 2) Spring Event

Spring에서는 다음과 같이 이벤트를 발생시킬 수 있다.

```java
applicationEventPublisher.publishEvent(
    new UserCreatedEvent(user)
);
```

이벤트를 받는 Listener를 만들 수 있다.

```java
@EventListener
public void handle(UserCreatedEvent event) {

    emailService.send(event.getUser());
}
```

---

## 3) 장점

이벤트 발생 객체와 처리 객체의 결합도를 낮출 수 있다.

```text
UserService

EmailService를 몰라도 됨
CouponService를 몰라도 됨
LogService를 몰라도 됨
```

---

## 4) 사용하는 상황

```text
회원가입 완료

주문 완료

결제 완료

파일 업로드 완료

알림 전송

도메인 이벤트
```

---

# 10. Adapter Pattern

## 1) 개념

Adapter Pattern은 서로 호환되지 않는 인터페이스를 연결해주는 패턴이다.

쉽게 말하면 실제 어댑터와 비슷하다.

```text
220V 콘센트

↓

Adapter

↓

110V 전자제품
```

소프트웨어에서도 외부 시스템의 인터페이스가 현재 프로그램에서 원하는 형태와 다를 때 사용한다.

---

## 2) 예시

우리 서비스에서는 다음 인터페이스를 사용한다고 하자.

```java
public interface Payment {

    void pay(int money);
}
```

그런데 외부 결제 API가 다음과 같은 구조를 가진다.

```java
public class ExternalPayment {

    public void requestPayment(long amount) {

    }
}
```

Adapter를 만들 수 있다.

```java
public class PaymentAdapter
        implements Payment {

    private final ExternalPayment externalPayment;

    @Override
    public void pay(int money) {

        externalPayment.requestPayment(money);
    }
}
```

우리 시스템에서는 외부 API의 구조를 몰라도 된다.

```text
Service

 ↓

Payment

 ↓

PaymentAdapter

 ↓

External Payment API
```

---

## 3) 사용하는 상황

외부 API나 라이브러리를 기존 코드에 연결할 때 많이 사용한다.

```text
외부 결제 API

외부 SMS API

외부 Storage API

Legacy System

Third Party Library
```

---

# 11. Facade Pattern

## 1) 개념

Facade Pattern은 복잡한 여러 시스템을 하나의 단순한 인터페이스로 감싸는 패턴이다.

예를 들어 주문 하나를 처리하기 위해 다음 서비스가 필요할 수 있다.

```text
OrderService

PaymentService

InventoryService

DeliveryService

PointService
```

Controller가 모든 서비스를 직접 호출하면 복잡해진다.

```java
paymentService.pay();

inventoryService.decrease();

deliveryService.create();

pointService.save();
```

Facade를 만들면 다음처럼 단순하게 만들 수 있다.

```java
orderFacade.order();
```

내부적으로 여러 서비스를 호출한다.

```text
Controller

 ↓

OrderFacade

 ├ PaymentService
 ├ InventoryService
 ├ DeliveryService
 └ PointService
```

---

## 2) 사용하는 상황

복잡한 서브 시스템을 단순한 API로 제공하고 싶을 때 사용한다.

---

# 12. Decorator Pattern

## 1) 개념

Decorator Pattern은 기존 객체를 수정하지 않고 기능을 추가하는 패턴이다.

기존 객체를 다른 객체로 감싸는 방식이다.

```text
Object

↓

Decorator

↓

Decorator

↓

Decorator
```

---

## 2) 예시

기본 커피가 있다고 하자.

```java
public interface Coffee {

    int cost();
}
```

```java
public class BasicCoffee implements Coffee {

    public int cost() {
        return 3000;
    }
}
```

우유를 추가하는 Decorator를 만들 수 있다.

```java
public class MilkDecorator
        implements Coffee {

    private final Coffee coffee;

    public MilkDecorator(Coffee coffee) {
        this.coffee = coffee;
    }

    public int cost() {
        return coffee.cost() + 500;
    }
}
```

```java
Coffee coffee =
    new MilkDecorator(
        new BasicCoffee()
    );
```

기존 객체를 수정하지 않고 기능을 추가할 수 있다.

---

# 13. State Pattern

## 1) 개념

State Pattern은 객체의 상태에 따라 행동이 달라질 때 상태 자체를 객체로 분리하는 패턴이다.

예를 들어 주문 상태가 있다고 하자.

```text
ORDERED

PAID

DELIVERING

COMPLETED

CANCELLED
```

일반적인 방식으로 작성하면 조건문이 많아질 수 있다.

```java
if (state == ORDERED) {

} else if (state == PAID) {

} else if (state == DELIVERING) {

}
```

State Pattern에서는 상태별 행동을 별도 객체로 분리할 수 있다.

---

## 2) 사용하는 상황

상태에 따라 행동이 크게 달라지는 시스템에서 유용하다.

```text
주문 상태

결제 상태

게임 캐릭터 상태

문서 승인 상태

배송 상태
```

---

# 14. Command Pattern

## 1) 개념

Command Pattern은 요청 자체를 객체로 만드는 패턴이다.

```text
Client

 ↓

Command

 ↓

Receiver
```

예를 들어 버튼을 누르는 동작 자체를 Command 객체로 만들 수 있다.

```java
public interface Command {

    void execute();
}
```

```java
public class SaveCommand
        implements Command {

    public void execute() {

        System.out.println("저장");
    }
}
```

---

## 2) 장점

요청을 객체로 다룰 수 있기 때문에 다음과 같은 기능을 구현하기 좋다.

```text
Undo

Redo

작업 Queue

작업 기록

재실행
```

---

# 15. Repository Pattern

## 1) 개념

Repository Pattern은 데이터 접근 로직을 비즈니스 로직에서 분리하는 패턴이다.

GoF 디자인 패턴은 아니지만 백엔드 개발에서 매우 자주 사용한다.

일반적인 Spring 구조는 다음과 같다.

```text
Controller

 ↓

Service

 ↓

Repository

 ↓

Database
```

---

## 2) 예시

```java
public interface UserRepository {

    User findById(Long id);

    void save(User user);
}
```

Service는 DB 접근 방법을 알 필요가 없다.

```java
@Service
public class UserService {

    private final UserRepository userRepository;

    public User findUser(Long id) {

        return userRepository.findById(id);
    }
}
```

---

## 3) 장점

비즈니스 로직과 데이터 접근 로직을 분리할 수 있다.

DB 구현이 변경되어도 Service 코드에 미치는 영향을 줄일 수 있다.

---

# 16. Dependency Injection

## 1) 개념

Dependency Injection은 객체가 필요한 의존 객체를 직접 생성하지 않고 외부에서 전달받는 방식이다.

GoF 패턴은 아니지만 Spring을 이해하려면 반드시 알아야 하는 개념이다.

직접 생성하는 경우는 다음과 같다.

```java
public class OrderService {

    private final OrderRepository repository
        = new OrderRepository();
}
```

`OrderService`가 `OrderRepository`의 생성까지 책임지고 있다.

DI를 사용하면 다음과 같이 바뀐다.

```java
public class OrderService {

    private final OrderRepository repository;

    public OrderService(
        OrderRepository repository
    ) {
        this.repository = repository;
    }
}
```

객체 생성은 외부에서 담당한다.

---

## 2) Spring DI

Spring에서는 Bean을 생성하고 필요한 객체에 자동으로 주입해준다.

```java
@Service
public class OrderService {

    private final OrderRepository repository;

    public OrderService(
        OrderRepository repository
    ) {
        this.repository = repository;
    }
}
```

---

## 3) Strategy Pattern과의 관계

DI와 Strategy Pattern은 함께 사용되는 경우가 많다.

```text
PaymentStrategy
      ↑
      │
CardPayment
KakaoPayment
TossPayment
```

필요한 구현체를 외부에서 주입한다.

---

# 17. MVC Pattern

## 1) 개념

MVC는 Model, View, Controller로 역할을 분리하는 패턴이다.

```text
Model
→ 데이터와 비즈니스 상태

View
→ 화면

Controller
→ 요청 처리
```

Spring MVC에서는 다음과 같은 흐름을 볼 수 있다.

```text
Client

 ↓

Controller

 ↓

Service

 ↓

Repository

 ↓

Database
```

---

## 2) Controller

HTTP 요청을 받는다.

```java
@RestController
public class UserController {

    @GetMapping("/users/{id}")
    public UserResponse getUser(
        @PathVariable Long id
    ) {

        ...
    }
}
```

Controller는 HTTP 요청과 응답을 처리하는 역할에 집중한다.

---

## 3) Service

비즈니스 로직을 처리한다.

```java
@Service
public class UserService {

    public User findUser(Long id) {

        ...
    }
}
```

---

## 4) Repository

데이터 접근을 담당한다.

```java
@Repository
public interface UserRepository {

}
```

---

# 18. AOP와 디자인 패턴

## 1) AOP

AOP는 Aspect Oriented Programming의 약자로 관점 지향 프로그래밍이라고 한다.

여러 클래스에서 반복되는 공통 관심사를 비즈니스 로직과 분리하는 방식이다.

대표적인 공통 관심사는 다음과 같다.

```text
Logging

Transaction

Authorization

Performance Measurement

Exception Handling
```

---

## 2) Aspect

Aspect는 여러 객체에 공통적으로 적용되는 기능을 모아둔 모듈이다.

```java
@Aspect
@Component
public class LoggingAspect {

    @Before(
        "execution(* com.example.service..*(..))"
    )
    public void logging() {

        System.out.println("method start");
    }
}
```

Aspect는 일반적으로 다음 개념과 함께 이해하면 된다.

```text
Aspect

=

Pointcut
+
Advice
```

---

## 3) Pointcut

Pointcut은 Advice가 적용될 위치를 의미한다.

```java
execution(* com.example.service..*(..))
```

예를 들어 Service 패키지의 메서드에 적용하도록 설정할 수 있다.

---

## 4) Advice

Advice는 실제로 실행할 공통 로직이다.

```java
@Before(...)
public void logging() {

    System.out.println("실행");
}
```

대표적으로 다음 종류가 있다.

```text
@Before

@After

@AfterReturning

@AfterThrowing

@Around
```

---

## 5) AOP와 Proxy

Spring AOP는 Proxy를 사용해서 구현된다.

```text
Controller

 ↓

Proxy

 ↓

Service
```

Proxy가 Service 호출 전후에 공통 기능을 실행한다.

---

# 19. 디자인 패턴 간 관계

실제 개발에서는 하나의 패턴만 단독으로 사용하는 경우보다 여러 패턴이 함께 사용되는 경우가 많다.

예를 들어 다음 구조가 있다.

```text
Controller

 ↓

Service

 ↓

PaymentStrategy

 ↓

CardPayment
KakaoPayment
TossPayment
```

여기에는 여러 개념이 동시에 들어간다.

```text
Strategy
→ 결제 방법을 구현체로 분리

DI
→ 필요한 Strategy를 주입

Singleton
→ Spring Bean을 하나 생성해서 공유

Proxy
→ @Transactional이나 AOP 적용

Factory
→ Bean 생성 및 관리
```

Spring Framework 자체가 여러 디자인 패턴을 조합해서 만들어진 프레임워크라고 볼 수 있다.

---

# 20. 자주 사용하는 패턴 우선순위

Spring 백엔드 개발을 기준으로 보면 모든 디자인 패턴을 같은 수준으로 공부할 필요는 없다.

먼저 익혀두면 좋은 순서는 다음과 같다.

```text
1. Strategy

2. Dependency Injection

3. Singleton

4. Proxy

5. Factory

6. Builder

7. Repository

8. Observer

9. Template Method

10. Adapter

11. Facade
```

특히 다음 네 가지는 Spring 코드를 읽을 때 매우 자주 등장한다.

```text
Strategy

Dependency Injection

Proxy

Repository
```

---

# 21. 패턴을 사용할 때 주의할 점

## 1) 패턴을 억지로 적용하지 않는다

디자인 패턴을 공부한 직후에는 간단한 코드에도 패턴을 적용하고 싶어질 수 있다.

예를 들어 다음 코드가 있다고 하자.

```java
if (type.equals("A")) {

} else {

}
```

조건이 두 개밖에 없고 앞으로 늘어날 가능성도 없다면 Strategy Pattern까지 적용할 필요가 없을 수 있다.

오히려 클래스만 늘어나 코드 구조가 복잡해질 수 있다.

---

## 2) 패턴 이름보다 문제를 먼저 본다

개발하면서

```text
이건 Strategy Pattern을 써야겠다.
```

라고 시작하는 것보다는

```text
조건문이 너무 많다.

구현체를 쉽게 교체하고 싶다.

객체 생성 책임을 분리하고 싶다.

공통 기능을 비즈니스 로직에서 분리하고 싶다.
```

와 같이 문제를 먼저 발견하는 것이 중요하다.

그다음 적절한 디자인 패턴을 선택하면 된다.

---

# 22. 상황별로 떠올릴 패턴

개발하면서 다음과 같이 연결해서 기억하면 편하다.

```text
if-else가 계속 늘어난다
→ Strategy

객체 생성 코드가 복잡하다
→ Factory

생성자 파라미터가 너무 많다
→ Builder

객체 하나를 공유해야 한다
→ Singleton

기존 객체 앞뒤에 기능을 추가하고 싶다
→ Proxy

기존 객체를 감싸 기능을 추가하고 싶다
→ Decorator

외부 API 인터페이스가 우리 코드와 맞지 않는다
→ Adapter

복잡한 여러 서비스를 하나로 감싸고 싶다
→ Facade

특정 이벤트가 발생했을 때 여러 기능을 실행하고 싶다
→ Observer

상태에 따라 행동이 달라진다
→ State

전체 처리 흐름은 같고 일부 과정만 다르다
→ Template Method

DB 접근 코드를 분리하고 싶다
→ Repository

구현체를 쉽게 교체하고 싶다
→ Strategy + DI

로깅이나 트랜잭션 같은 공통 기능을 분리하고 싶다
→ Proxy + AOP
```

---

# 23. Spring에서 자주 보이는 패턴

Spring 코드를 기준으로 연결하면 다음과 같이 정리할 수 있다.

```text
Spring Bean
→ Singleton

인터페이스 + 구현체
→ Strategy

@Autowired / 생성자 주입
→ Dependency Injection

@Transactional
→ Proxy + AOP

Spring Data JPA
→ Repository

ApplicationEventPublisher
→ Observer

JdbcTemplate
→ Template 계열

Bean 생성
→ Factory

외부 API Wrapper
→ Adapter

DTO / Entity 생성
→ Builder
```

Spring을 공부하면서 패턴을 따로 외우기보다는 실제 코드에서 어떤 구조로 사용되는지 같이 보는 것이 가장 이해하기 쉽다.
