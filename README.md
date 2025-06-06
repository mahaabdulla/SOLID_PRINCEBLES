# 🧱 SOLID Principles Practice Project

🧩 What Are the SOLID Principles?

    S - Single Responsibility Principle (SRP)
    Every class should have only one reason to change.

    O - Open/Closed Principle (OCP)
    Code should be open for extension but closed for modification.

    L - Liskov Substitution Principle (LSP)
    Objects of subclasses should be replaceable with objects of the superclass without breaking the system.

    I - Interface Segregation Principle (ISP)
    Classes should not be forced to implement interfaces they do not use.

    D - Dependency Inversion Principle (DIP)
    Classes should depend on abstractions, not on concrete implementations
## 🔧 How the Principles Were Applied

### ✅ Example 1: SRP  
The `UserManager` class is only responsible for managing users, while the `Logger` class handles logging.

### ✅ Example 2: OCP  
We created a `PaymentMethod` interface that can be extended for different payment types without modifying the core code.

### ✅ Example 3: LSP  
Classes like `CreditCardPayment` and `PaypalPayment` inherit from `PaymentMethod` and can be used interchangeably.
### ✅ Example 4: ISP  
We split large interfaces into smaller, more specific ones tailored to particular use cases.

### ✅ Example 5: DIP  
We use `abstract class` or `interface` to reduce coupling between classes and rely on abstractions.


