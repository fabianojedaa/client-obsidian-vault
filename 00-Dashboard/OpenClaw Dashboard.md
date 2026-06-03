# OpenClaw Dashboard

## Active Tasks

```dataview
TABLE status, machine, updated
FROM "02-Tasks"
WHERE status != "Done"
SORT updated DESC
```

## Recent Daily Logs

```dataview
LIST
FROM "01-Daily-Logs"
SORT file.name DESC
LIMIT 20
```

## Mac Mini 1 Tasks

```dataview
TABLE status, updated
FROM "02-Tasks/Mac-Mini-1"
SORT updated DESC
```

## Mac Mini 2 Tasks

```dataview
TABLE status, updated
FROM "02-Tasks/Mac-Mini-2"
SORT updated DESC
```

## Mac Mini 3 Tasks

```dataview
TABLE status, updated
FROM "02-Tasks/Mac-Mini-3"
SORT updated DESC
```