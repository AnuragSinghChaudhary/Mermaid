
### 3. Class Diagram

```mermaid
classDiagram
    class Animal {
        +String species
        +int age
        +void eat()
        +void sleep()
    }
    class Dog {
        +String breed
        +void bark()
    }
    Animal <|-- Dog
