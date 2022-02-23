```mermaid
flowchart LR
home -->|set_site| home

hypotheses -->|def_ready| hypotheses 
hypotheses -->|questions| hypotheses 
hypotheses -->|set_phase| hypotheses 
hypotheses -->|new| hypothesis  
hypotheses -->|edit| hypothesis 
hypothesis -->|autosave| hypothesis  
hypothesis -->|done/delete| hypotheses
```
