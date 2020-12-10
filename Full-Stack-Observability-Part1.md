
# Full Stack Observability Workshop - Day 1

## How Does New Relic Work?
- TODO add Print slide 39

## Main Event Types

## NRQL Syntax

### NRQL Examples 1

### Aggregate Data - `average, max, min, count`
```
FROM Transaction SELECT count(*)
// Throughput for my application

FROM Transaction SELECT max(duration)
// Slowest transactions for my application
```

### Group Data - `FACET`
- `FACET` is like `group by` from SQL
```
FROM Transaction SELECT count(*) FACET appName
// Transactions grouped by different applications name

FROM Transaction SELECT count(*) FACET httpResponseCoded
// Transactions grouped by response codes
```

### Quering only part of the data - `WHERE`

### NRQL Examples 2

##
- TODO - Dashboards: 12 column layout and other features PRINT HERE


https://blog.newrelic.com/product-news/how-to-choose-apdex-t/

https://one.newrelic.com/launcher/dashboards.launcher?pane=eyJuZXJkbGV0SWQiOiJkYXNoYm9hcmRzLmRhc2hib2FyZCIsImVudGl0eUlkIjoiTVRBek9ESTROM3hXU1ZwOFJFRlRTRUpQUVZKRWZERTBOemN4TXpZIiwidXNlRGVmYXVsdFRpbWVSYW5nZSI6ZmFsc2UsImlzVGVtcGxhdGVFbXB0eSI6ZmFsc2V9&platform[$isFallbackTimeRange]=false


https://docs.newrelic.com/docs/understand-dependencies/distributed-tracing/get-started/introduction-distributed-tracing
