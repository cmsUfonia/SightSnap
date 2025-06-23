# SightSnap
Overview of SightSnap
```mermaid
graph TD
    A[Surgery] --> B[3 Weeks Post-Op Dora Call];

    subgraph "SightSnap Process"
        C[6 Weeks Post-Op SMS from Ufonia requesting photo of prescription]
        D[Patient takes photo and sends to Ufonia]
        E[Ufonia converts Photo to Data]

        C --> D
        D --> E
    end

    B --> C;
    E --> F[12 Weeks Post-Op PROMS Dora Call];

    style C fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px;
    style D fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px;
    style E fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px;
