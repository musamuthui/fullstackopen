```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/new_note_spa 
    activate server
    server-->>browser: 201 Created [{"content": "single page does not reload the whole page", "date": "2025-08-15"}]
    deactivate server


```
