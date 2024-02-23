# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.158 ops/ms
# Warmup Iteration   2: 12.162 ops/ms
# Warmup Iteration   3: 12.063 ops/ms
Iteration   1: 12.449 ops/ms
Iteration   2: 12.333 ops/ms
Iteration   3: 12.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.420 ±(99.9%) 1.388 ops/ms [Average]
  (min, avg, max) = (12.333, 12.420, 12.477), stdev = 0.076
  CI (99.9%): [11.032, 13.808] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.820 ops/ms
# Warmup Iteration   2: 12.886 ops/ms
# Warmup Iteration   3: 12.777 ops/ms
Iteration   1: 13.045 ops/ms
Iteration   2: 12.947 ops/ms
Iteration   3: 12.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.965 ±(99.9%) 1.339 ops/ms [Average]
  (min, avg, max) = (12.902, 12.965, 13.045), stdev = 0.073
  CI (99.9%): [11.625, 14.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.580 ops/ms
# Warmup Iteration   2: 12.364 ops/ms
# Warmup Iteration   3: 12.519 ops/ms
Iteration   1: 12.655 ops/ms
Iteration   2: 12.430 ops/ms
Iteration   3: 12.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.585 ±(99.9%) 2.456 ops/ms [Average]
  (min, avg, max) = (12.430, 12.585, 12.670), stdev = 0.135
  CI (99.9%): [10.129, 15.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.474 ops/ms
# Warmup Iteration   2: 10.228 ops/ms
# Warmup Iteration   3: 10.486 ops/ms
Iteration   1: 10.501 ops/ms
Iteration   2: 10.554 ops/ms
Iteration   3: 10.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.533 ±(99.9%) 0.515 ops/ms [Average]
  (min, avg, max) = (10.501, 10.533, 10.554), stdev = 0.028
  CI (99.9%): [10.018, 11.048] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.986 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.003 ms/op
Iteration   1: 2.575 ±(99.9%) 0.005 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (2.534, 2.549, 2.575), stdev = 0.023
  CI (99.9%): [2.132, 2.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.003 ms/op
Iteration   1: 2.472 ±(99.9%) 0.003 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (2.472, 2.478, 2.485), stdev = 0.007
  CI (99.9%): [2.359, 2.598] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.137 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.004 ms/op
Iteration   1: 2.549 ±(99.9%) 0.004 ms/op
Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
Iteration   3: 2.575 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.556 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (2.544, 2.556, 2.575), stdev = 0.017
  CI (99.9%): [2.253, 2.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 5.066 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.005 ms/op
Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
Iteration   3: 3.092 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.092 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (3.086, 3.092, 3.098), stdev = 0.006
  CI (99.9%): [2.977, 3.208] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.285 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.723 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.575 ±(99.9%) 0.006 ms/op
Iteration   1: 2.581 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   4.088 ms/op
                 createUser·p0.999:  12.026 ms/op
                 createUser·p0.9999: 14.045 ms/op
                 createUser·p1.00:   14.467 ms/op

Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  9.412 ms/op
                 createUser·p0.9999: 14.002 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   3: 2.580 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 10.895 ms/op
                 createUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372498
  mean =      2.575 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 177619 
    [ 2.500,  3.750) = 189677 
    [ 3.750,  5.000) = 4149 
    [ 5.000,  6.250) = 526 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     14.373 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.677 ms/op
                 existUser·p0.999:  7.560 ms/op
                 existUser·p0.9999: 13.990 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.902 ms/op
                 existUser·p0.999:  9.034 ms/op
                 existUser·p0.9999: 13.390 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 11.848 ms/op
                 existUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389172
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 194780 
    [ 2.500,  3.750) = 190473 
    [ 3.750,  5.000) = 2625 
    [ 5.000,  6.250) = 676 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     13.601 ms/op
     p(99.9990) =     14.534 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  11.118 ms/op
                 getUser·p0.9999: 13.735 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  9.483 ms/op
                 getUser·p0.9999: 14.342 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  9.471 ms/op
                 getUser·p0.9999: 12.315 ms/op
                 getUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378736
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 185115 
    [ 2.500,  3.750) = 189055 
    [ 3.750,  5.000) = 3705 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.602 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.751 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.009 ms/op
Iteration   1: 3.090 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.841 ms/op
                 listUser·p0.999:  9.945 ms/op
                 listUser·p0.9999: 12.463 ms/op
                 listUser·p1.00:   13.238 ms/op

Iteration   2: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.637 ms/op
                 listUser·p0.999:  9.526 ms/op
                 listUser·p0.9999: 11.686 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   3: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  10.109 ms/op
                 listUser·p0.9999: 13.829 ms/op
                 listUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312310
  mean =      3.071 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 79305 
    [ 2.500,  3.750) = 189969 
    [ 3.750,  5.000) = 35173 
    [ 5.000,  6.250) = 6210 
    [ 6.250,  7.500) = 822 
    [ 7.500,  8.750) = 182 
    [ 8.750, 10.000) = 294 
    [10.000, 11.250) = 162 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     12.444 ms/op
     p(99.9990) =     14.228 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.420 ± 1.388  ops/ms
ClientPb.existUser                       thrpt       3  12.965 ± 1.339  ops/ms
ClientPb.getUser                         thrpt       3  12.585 ± 2.456  ops/ms
ClientPb.listUser                        thrpt       3  10.533 ± 0.515  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.417   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.120   ms/op
ClientPb.getUser                          avgt       3   2.556 ± 0.303   ms/op
ClientPb.listUser                         avgt       3   3.092 ± 0.115   ms/op
ClientPb.createUser                     sample  372498   2.575 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.957           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.093           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.648           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.467           ms/op
ClientPb.existUser                      sample  389172   2.465 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.776           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.995           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.601           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.713           ms/op
ClientPb.getUser                        sample  378736   2.532 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.854           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.486           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.713           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.762           ms/op
ClientPb.listUser                       sample  312310   3.071 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.813           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.880           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.444           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.352           ms/op
