# API Service

| Category     | SLI | SLO                                                                                                         |
|--------------|-----|-------------------------------------------------------------------------------------------------------------|
| Availability |   Percentage of successful 2xx requests   | 99%                                                                                                         |
| Latency      |   90th percentile latency over a 10 min period  | 90% of requests below 100ms                                                                                 |
| Error Budget |  Percentage of failed requests < 20%  | Error budget is defined at 20%. This means that 20% of the requests can fail and still be within the budget |
| Throughput   |   total number of requests over a period of time  | 5 RPS indicates the application is functioning                                                              |
