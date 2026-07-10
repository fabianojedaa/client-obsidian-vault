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

## Virtual Lending Mac Mini Tasks

```dataview
TABLE status, updated
FROM "02-Tasks/Virtual Lending Mac Mini"
SORT updated DESC
```

## Better Processor Tasks

```dataview
TABLE status, updated
FROM "02-Tasks/BetterProcessors"
SORT updated DESC
```

## VirtuaListing Tasks

```dataview
TABLE status, updated
FROM "02-Tasks/VirtuaListing"
SORT updated DESC
```