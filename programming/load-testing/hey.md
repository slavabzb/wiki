# Hey

[https://github.com/rakyll/hey](https://github.com/rakyll/hey)

An easy to use load testing tool which generates beautiful reports.

```
Summary:
  Total:    1200.0304 secs
  Slowest:    2.0342 secs
  Fastest:    0.0071 secs
  Average:    0.0241 secs
  Requests/sec:    624.5817

  Total data:    90345174 bytes
  Size/request:    120 bytes

Response time histogram:
  0.007 [1]    |
  0.210 [743065]    |■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
  0.413 [3479]    |
  0.615 [119]    |
  0.818 [27]    |
  1.021 [24]    |
  1.223 [23]    |
  1.426 [3]    |
  1.629 [0]    |
  1.831 [5]    |
  2.034 [1]    |


Latency distribution:
  10% in 0.0121 secs
  25% in 0.0142 secs
  50% in 0.0179 secs
  75% in 0.0246 secs
  90% in 0.0378 secs
  95% in 0.0530 secs
  99% in 0.1300 secs

Details (average, fastest, slowest):
  DNS+dialup:    0.0000 secs, 0.0071 secs, 2.0342 secs
  DNS-lookup:    0.0000 secs, 0.0000 secs, 0.3912 secs
  req write:    0.0000 secs, 0.0000 secs, 0.0486 secs
  resp wait:    0.0239 secs, 0.0070 secs, 2.0338 secs
  resp read:    0.0001 secs, 0.0000 secs, 0.0370 secs

Status code distribution:
  [200]    646439 responses
  [502]    100308 responses
```
