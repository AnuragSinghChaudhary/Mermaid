```mermaid
sequenceDiagram
    participant User
    participant RawData
    participant CleanData
    participant Transform1
    participant Transform2
    participant EnrichedData
    participant Database

    User->>RawData: Provide Raw Data
    RawData-->>CleanData: Clean Data
    CleanData-->>Transform1: Transform Stage 1
    Transform1-->>Transform2: Transform Stage 2
    Transform2-->>EnrichedData: Enriched Data
    EnrichedData-->>Database: Load Data
    Database-->>User: Data Available
