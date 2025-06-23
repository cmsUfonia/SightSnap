# SightSnap
Overview of SightSnap
```mermaid
graph TD
    A[Surgery] --> B[3 Weeks Post-Op Dora Call];
    B --> C[6 Weeks Post-Op SMS from Ufonia requesting photo of prescription];
    C --> D[Patient takes photo and sends to Ufonia];
    D --> E[Ufonia converts Photo to Data];
    E --> F[12 Weeks Post-Op PROMS Dora Call];

    %% Styling for the SightSnap process links (B to C, C to D, D to E)
    linkStyle 1 stroke:#0000FF,stroke-width:2px; %% Link from B to C
    linkStyle 2 stroke:#0000FF,stroke-width:2px; %% Link from C to D
    linkStyle 3 stroke:#0000FF,stroke-width:2px; %% Link from D to E
