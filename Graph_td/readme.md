```mermaid
graph TD;
    A[Start] --> B{Is it?};
    B -->|Yes| C[Do something];
    C --> D[Finish];
    B -->|No| E[Do something else];
    E --> D[Finish];
