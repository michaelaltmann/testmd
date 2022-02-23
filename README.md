```mermaid
erDiagram
alembic_version {
   INT version_num PK
}
phase_ready_question {
    INTEGER id PK
    "VARCHAR(100)" created_by 
    "TIMESTAMP WITHOUT TIME ZONE" created_dt 
    "VARCHAR(1000)" modified_by 
    "TIMESTAMP WITHOUT TIME ZONE" modified_dt 
    INTEGER phase_id 
    "VARCHAR(65000)" description 
}
```

