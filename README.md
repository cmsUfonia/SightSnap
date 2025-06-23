# SightSnap
Overview of SightSnap
```mermaid
graph TD
    A[Surgery] --> B[3 Weeks Post-Op Dora Call];
    B --> C[6 Weeks Post-Op SMS from Ufonia requesting photo of prescription];
    C --> D[Patient takes photo and sends to Ufonia];
    D --> E[Ufonia converts Photo to Data];
    E --> F[12 Weeks Post-Op PROMS Dora Call];

    %% Styling for the SightSnap core process nodes (B, C, D)
    style B fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px; %% Light Cyan box, green border
    style C fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px;
    style D fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px;
