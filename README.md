# planes

## Data flow
Make a graph that shows data going:
- From the user to ingest01 or ingest02
- From ingest01 and ingest02 to hub
- From ingest01 and ingest02 to mlat
- From mlat to hub
- From hub to planes

## Data flow
```
user -> ingest01 -> hub -> planes
user -> ingest02 -> hub -> planes
ingest01 -> mlat -> hub -> planes
ingest02 -> mlat -> hub -> planes
# infra
