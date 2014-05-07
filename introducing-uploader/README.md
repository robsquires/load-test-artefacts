#### Peak Load

| Action               | Constant Timer    |
| ---------------------|-------------------|
| Show                 | 2 secs            |
| Edit                 | 5 mins            |
| Create               | 1 min             |
| Update               | 1 min             |
| New                  | 1 min             |


* Response times in ms

| Test     | Requests  | Average | Median | 90% Line | Min  | Max   | Error | Throughput | 
| -------- | --------- | ------- | ------ | -------- | ---  | ---   | ----- | ---------- |
| Show     | 613       | 1079    | 1042   | 1223     | 866  | 2680  | 0.00% | 19.5/min   |
| New      | 32        | 834     | 757    | 919      | 594  | 2014  | 0.00% | 1.0/min    |
| Create   | 32        | 1618    | 1508   | 1959     | 1325 | 2119  | 0.00% | 1.0/min    |
| Update   | 30        | 1968    | 1890   | 2243     | 1685 | 2506  | 0.00% | 1.0/min    |
| Edit     | 7         | 1269    | 1132   | 1396     | 1014 | 2016  | 0.00% | 13.9/hour  |
| Total    | 714       | 1132    | 1049   | 1475     | 594  | 2680  | 0.00% | 20.3/min   |
