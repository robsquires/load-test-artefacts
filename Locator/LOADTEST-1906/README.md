#### No cache results

* lts_020 and lts_021 will not exceed a throughput of around 80RPS, indicating that these queries cannot handle a larger
  load and a no-cache header.

| Test     | Requests  | Average | Median | 90% Line | Min  | Max   | Error | Throughput  |
| -------- | --------- | ------- | ------ | -------- | ---  | ---   | ----- | ----------- |
| lts_020  | 56340     | 12187   | 12241  | 13362    | 80   | 19383 | 0.03% | 80.9/sec    |
| lts_021  | 49877     | 12143   | 12733  | 13553    | 67   | 18138 | 0.00% | 77.7/sec    |
| lts_025  | 83520     | 76      | 92     | 115      | 115  | 1965  | 2.09% | 201.9/sec   |
| lts_025  | 138757    | 93      | 97     | 121      | 7    | 6943  | 2.10% | 301.2/sec  |


#### Cache results 
| Test     | Requests  | Average | Median | 90% Line | Min | Max    | Error | Throughput |
| -------- | --------- | ------- | ------ | -------- | --- | ---   | ----- | ----------- |






 	
