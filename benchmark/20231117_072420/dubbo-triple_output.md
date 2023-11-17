# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.716 ops/ms
# Warmup Iteration   2: 11.844 ops/ms
# Warmup Iteration   3: 12.136 ops/ms
Iteration   1: 12.329 ops/ms
Iteration   2: 12.445 ops/ms
Iteration   3: 12.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.413 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (12.329, 12.413, 12.465), stdev = 0.073
  CI (99.9%): [11.080, 13.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.706 ops/ms
# Warmup Iteration   2: 12.730 ops/ms
# Warmup Iteration   3: 12.826 ops/ms
Iteration   1: 12.652 ops/ms
Iteration   2: 12.857 ops/ms
Iteration   3: 12.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.720 ±(99.9%) 2.160 ops/ms [Average]
  (min, avg, max) = (12.651, 12.720, 12.857), stdev = 0.118
  CI (99.9%): [10.560, 14.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.453 ops/ms
# Warmup Iteration   2: 12.264 ops/ms
# Warmup Iteration   3: 12.276 ops/ms
Iteration   1: 12.488 ops/ms
Iteration   2: 12.655 ops/ms
Iteration   3: 12.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.523 ±(99.9%) 2.161 ops/ms [Average]
  (min, avg, max) = (12.426, 12.523, 12.655), stdev = 0.118
  CI (99.9%): [10.363, 14.684] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.538 ops/ms
# Warmup Iteration   2: 10.155 ops/ms
# Warmup Iteration   3: 10.195 ops/ms
Iteration   1: 10.196 ops/ms
Iteration   2: 10.261 ops/ms
Iteration   3: 10.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.283 ±(99.9%) 1.830 ops/ms [Average]
  (min, avg, max) = (10.196, 10.283, 10.393), stdev = 0.100
  CI (99.9%): [8.453, 12.113] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.464 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.693 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.598 ±(99.9%) 0.005 ms/op
Iteration   1: 2.566 ±(99.9%) 0.004 ms/op
Iteration   2: 2.595 ±(99.9%) 0.003 ms/op
Iteration   3: 2.646 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.603 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (2.566, 2.603, 2.646), stdev = 0.041
  CI (99.9%): [1.862, 3.343] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.004 ms/op
Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.456 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (2.437, 2.456, 2.491), stdev = 0.030
  CI (99.9%): [1.906, 3.006] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.004 ms/op
Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
Iteration   3: 2.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.548 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (2.527, 2.548, 2.574), stdev = 0.024
  CI (99.9%): [2.113, 2.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.830 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (2.999, 3.007, 3.020), stdev = 0.011
  CI (99.9%): [2.803, 3.211] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.704 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.594 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.346 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  12.484 ms/op
                 createUser·p0.9999: 13.872 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  10.018 ms/op
                 createUser·p0.9999: 13.402 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   3: 2.573 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.094 ms/op
                 createUser·p0.999:  9.630 ms/op
                 createUser·p0.9999: 11.565 ms/op
                 createUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372064
  mean =      2.578 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 174459 
    [ 2.500,  3.750) = 190499 
    [ 3.750,  5.000) = 5834 
    [ 5.000,  6.250) = 654 
    [ 6.250,  7.500) = 116 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 135 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.305 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.272 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.696 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  8.220 ms/op
                 existUser·p0.9999: 14.227 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  6.021 ms/op
                 existUser·p0.9999: 13.404 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  8.585 ms/op
                 existUser·p0.9999: 12.144 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385525
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 188951 
    [ 2.500,  3.750) = 192355 
    [ 3.750,  5.000) = 3300 
    [ 5.000,  6.250) = 433 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      7.496 ms/op
     p(99.9900) =     13.744 ms/op
     p(99.9990) =     14.523 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.246 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
Iteration   1: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  12.482 ms/op
                 getUser·p0.9999: 13.919 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.795 ms/op
                 getUser·p0.999:  5.861 ms/op
                 getUser·p0.9999: 13.943 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   3: 2.575 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.747 ms/op
                 getUser·p0.9999: 11.626 ms/op
                 getUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377559
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 183375 
    [ 2.500,  3.750) = 188254 
    [ 3.750,  5.000) = 4673 
    [ 5.000,  6.250) = 748 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =      7.007 ms/op
     p(99.9900) =     13.799 ms/op
     p(99.9990) =     14.340 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.892 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.009 ms/op
Iteration   1: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.977 ms/op
                 listUser·p1.00:   13.287 ms/op

Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.921 ms/op
                 listUser·p0.9999: 12.309 ms/op
                 listUser·p1.00:   13.156 ms/op

Iteration   3: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.476 ms/op
                 listUser·p0.9999: 12.822 ms/op
                 listUser·p1.00:   13.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315294
  mean =      3.042 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 87497 
    [ 2.500,  3.750) = 187542 
    [ 3.750,  5.000) = 32634 
    [ 5.000,  6.250) = 6197 
    [ 6.250,  7.500) = 694 
    [ 7.500,  8.750) = 194 
    [ 8.750, 10.000) = 219 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     12.442 ms/op
     p(99.9990) =     13.301 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.413 ± 1.333  ops/ms
ClientPb.existUser                       thrpt       3  12.720 ± 2.160  ops/ms
ClientPb.getUser                         thrpt       3  12.523 ± 2.161  ops/ms
ClientPb.listUser                        thrpt       3  10.283 ± 1.830  ops/ms
ClientPb.createUser                       avgt       3   2.603 ± 0.740   ms/op
ClientPb.existUser                        avgt       3   2.456 ± 0.550   ms/op
ClientPb.getUser                          avgt       3   2.548 ± 0.435   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.204   ms/op
ClientPb.createUser                     sample  372064   2.578 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.846           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.781           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.582           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.942           ms/op
ClientPb.existUser                      sample  385525   2.487 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.834           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.496           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.744           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.664           ms/op
ClientPb.getUser                        sample  377559   2.540 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.712           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.007           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.799           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.385           ms/op
ClientPb.listUser                       sample  315294   3.042 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.442           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.681           ms/op
