
### 4. State Diagram

```mermaid
stateDiagram
    [*] --> Active
    Active --> Inactive : Deactivate
    Inactive --> Active : Activate
    Active --> [*]
    Inactive --> [*]
