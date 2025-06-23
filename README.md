# SightSnap
Overview of SightSnap
``mermaid
graph TD
    A[Surgery] --> B[3 Weeks Post-Op Dora Call]
    linkStyle 0 stroke:#0000FF, stroke-width: 2px;
    B --> C[6 Weeks Post-Op SMS from Ufonia requesting photo of prescription]
    linkStyle 1 stroke:#0000FF, stroke-width: 2px;
    C --> D[Patient takes photo and sends to Ufonia]
    linkStyle 2 stroke:#0000FF, stroke-width: 2px;
    D --> E[Ufonia converts Photo to Data]
    linkStyle 3 stroke:#0000FF, stroke-width: 2px;
    E --> F[12 Weeks Post-Op PROMS Dora Call]
