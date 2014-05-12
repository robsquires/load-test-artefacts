#### Search

Both Search-query and Cloudview tests were run at various loads (throughput) with the data files provided.

Note: Time in milliseconds

| Test            | Requests  | Average | Median |  90% Line | Min  | Max   | Error | Throughput |
| --------        | --------- | ------- | ------ | -------- | ---  | ---    | ----- | ---------- |
| Search-query    | 37678     | 125     | 123    |  200     | 2    | 2273   | 0.00% | 99.3/sec   |
| Search-query    | 30693     | 124     | 124    |  217     | 2    | 1759   | 0.00% | 147.3/sec  |
| Search-query    | 37287     | 155     | 148    |  243     | 3    | 1226   | 0.00% | 157.4/sec  |
| Search-query    | 42862     | 127     | 126    |  232     | 2    | 1183   | 0.00% | 177.0/sec  |
| Search-query    | 41479     | 137     | 135    |  244     | 2    | 1456   | 0.00% | 185.9/sec  |
| Search-query    | 92628     | 262     | 136    |  426     | 2    | 5848   | 0.00% | 218/4/sec  |



##### Conclusion

* Search-query: The desired 300ms average response rate is within a throughput of 220/sec,
although the 90% line breaks the threshold at around 200/sec. The application
server will not accept requests above 220/sec.
