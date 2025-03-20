graph LR;
    User -->|Fills Form| HTML[HTML Form]
    HTML -->|Triggers JavaScript| JS[JavaScript]
    JS -->|Sends Data via Fetch API| AppsScript[Google Apps Script]
    AppsScript -->|Processes Data| GoogleSheet[Google Sheets]
    GoogleSheet -->|Stores Data| Database[Database]
