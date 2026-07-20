# Data Flow

```mermaid
flowchart TD

Insert

↓

Async Insert

↓

Data Parts

↓

MergeTree

↓

Background Merge

↓

Compressed Parts

↓

Query Execution
```
