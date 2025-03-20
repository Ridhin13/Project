```mermaid
graph LR
    A[User] --> B[Fills Form]
    B --> C[HTML Form]
    C --> D[Triggers JavaScript]
    D --> E[JavaScript]
    E --> F[Sends Data via Fetch API]
    F --> G[Google Apps Script]
    G --> H[Processes Data]
    H --> I[Google Sheets]
    I --> J[Stores Data]
    J --> K[Database]
