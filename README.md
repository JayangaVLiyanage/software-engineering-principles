# software-engineering-principles
Most Useful Software engineering principles
 
## 1. SOLID Principles

- SOLID is a group of object-oriented design principles
- Ech letter in the acronym “SOLID” represents one of the principles
- When applied together, these principles help developers create code that is more maintainable, understandable, and flexible software. 

### ![This is an image](images/s_letter_red_alphabet_letters_icon.svg)ingle Responsibility Principle (SRP)

- Every function, class, module, or service should have a single clearly defined responsibility
- In other words, A class, function, module should have one and only one reason to change.

### ![This is an image](images/o_letter_red_alphabet_letters_icon.svg)pen-Closed Principle (OCP)

- Software entities like class, modules, functions, etc.; should be able to extend a class behavior without modifying it
- This principle separates the existing code from modified mode to provide better stability, maintainability and minimizes the changes in the code

### ![This is an image](images/l_letter_red_alphabet_letters_icon.svg)iskov Substitution Principle (LSP)

- This principle ensures that any class that is the child of a parent class should be usable in place of its parent without any unexpected behavior
- In other words, the objects of your subclass should behave in the same way as the objects of your superclass

### ![This is an image](images/i_letter_red_alphabet_letters_icon.svg)nterface Segregation Principle (ISP)

- This principle states that a client should never be forced to depend on methods it does not use
- Here the main goal is to focus on avoiding fat interface and give preference to many small client-specific interfaces
- Split large interfaces into more specific ones that are focused on a specific set of functionalities so that the clients can choose to depend only on the functionalities they need

### ![This is an image](images/d_letter_red_alphabet_letters_icon.svg)ependency Inversion Principle (DIP)

- This principle tries to avoid tight coupling between software modules
- It states that High-level modules should not depend on low-level modules, but only on their abstractions
- In simple words, It suggests that you should use interfaces instead of concrete implementations wherever possible
