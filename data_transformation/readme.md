```mermaid
graph TD;
    A[Raw Data] --> B[Clean Data];
    B --> C[Transform Stage 1];
    C --> D[Transform Stage 2];
    D --> E[Enriched Data];
    E --> F[Load to Database];
    F --> G[Database];
