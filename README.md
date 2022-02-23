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

select_final_hypotheses -->|autosave| select_final_hypotheses

recommendations -->|def_ready| recommendations 
recommendations -->|questions| recommendations 
recommendations -->|new| recommendation 
recommendations -->|edit| recommendation  
recommendation -->|autosave| recommendation 
recommendation -->|done/delete| recommendations

plan -->|set_phase| plan 
plan -->|prioritize| plan 
plan -->|save| plan 

plan -->|edit| recommendation_plan  

recommendation_plan -->|new/edit| milestone  
milestone -->|autosave| milestone  
milestone -->|done/delete| recommendation_plan  

recommendation_plan -->|new| risk 
risk -->|autosave| risk  
risk -->|done/delete| recommendation_plan  

risks -->|edit| risk  


export_csv -->|download| export_csv 
reports -->|new| report 
report -->|submit| reports 
```

