FULLSTACK OPEN COURSE 30/08/2024

```mermaid
flowchart TD
    A{Client} -->|GET https://studies.cs.helsinki.fi/exampleapp/notes| B[(Server)]
    B -->|notes.html| C{Client}
    C -->|GET https://studies.cs.helsinki.fi/exampleapp/main.css| D[(Server)]
    D -->|main.css| E{Client}
    E -->|GET https://studies.cs.helsinki.fi/exampleapp/main.js| F[(Server)]
    F -->|main.js| G{Client}
    G -->|GET https://studies.cs.helsinki.fi/exampleapp/data.json| H[(Server)]
    H --> |data.json| I{Client}
    I --> |executes callback function that renders the notes| I
```
