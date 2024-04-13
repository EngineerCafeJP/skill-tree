```mermaid
flowchart TD
    A[BAT]
    B{BAT file}
    C[PowerShell]
    D{PS file}
    E{BAT+PS script}
    F[shell]
    G{shell script}

    A --> B
    C --> D
    A --> E
    D --> E

    F --> G
```
