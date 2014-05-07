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
| Show     | 774       | 1022    | 998    | 1103     | 807  | 2736  | 0.00% | 30.1/min   |
| New      | 26        | 772     | 719    | 832      | 661  | 1187  | 0.00% | 1.1/min    |
| Create   | 26        | 1461    | 1399   | 1737     | 1276 | 1934  | 0.00% | 1.1/min    |
| Update   | 26	       | 1778	 | 1762	  | 1837	 | 1676	| 2305	| 0.00% | 1.1/min    |
| Edit	   | 6	       | 1014	 | 1062	  | 1085	 | 745	| 1102	| 0.00% | 17.4/hour  |
| TOTAL	   | 858	   | 1050	 | 1000	  | 1160	 | 661	| 2736	| 0.00% | 33.3/min   |












