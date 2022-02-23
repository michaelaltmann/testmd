```mermaid
flowchart LR
home -->|set_site| home

hypotheses -->|def_ready| hypotheses 
hypotheses -->|questions| hypotheses 
hypotheses -->|set_phase| hypotheses 
hypotheses -->|new| hypothesis  
hypotheses -->|edit| hypothesis 
hypothesis -->|autosave| hypothesis  
hypothesis -->|done delete| hypotheses

select_final_hypotheses -->|autosave|  select_final_hypothese

recommendations -->|def_ready| recommendations 
recommendations -->|questions| recommendations 
recommendations -->|new| recommendation 
recommendations -->|edit| recommendation  
recommendation -->|autosave| recommendation 
recommendation -->|done delete|  recommendations
```
