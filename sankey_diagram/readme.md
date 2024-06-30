# Data Flow Diagram Example

This is an example of a Data Flow Diagram (DFD) created using Mermaid.

```mermaid
graph TD;
    A[User] -->|Login Request| B[Auth Service];
    B -->|Auth Response| A;
    B -->|Fetch User Data| C[Database];
    C -->|User Data| B;
    A -->|Upload File| D[File Server];
    D -->|File Stored Confirmation| A;
