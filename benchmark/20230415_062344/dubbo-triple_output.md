# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.506 ops/ms
# Warmup Iteration   2: 6.559 ops/ms
# Warmup Iteration   3: 8.982 ops/ms
Iteration   1: 9.552 ops/ms
Iteration   2: 9.684 ops/ms
Iteration   3: 9.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.582 ±(99.9%) 1.647 ops/ms [Average]
  (min, avg, max) = (9.511, 9.582, 9.684), stdev = 0.090
  CI (99.9%): [7.936, 11.229] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.206 ops/ms
# Warmup Iteration   2: 8.739 ops/ms
# Warmup Iteration   3: 9.518 ops/ms
Iteration   1: 10.082 ops/ms
Iteration   2: 9.901 ops/ms
Iteration   3: 9.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.858 ±(99.9%) 4.534 ops/ms [Average]
  (min, avg, max) = (9.591, 9.858, 10.082), stdev = 0.249
  CI (99.9%): [5.324, 14.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.580 ops/ms
# Warmup Iteration   2: 8.921 ops/ms
# Warmup Iteration   3: 9.246 ops/ms
Iteration   1: 9.630 ops/ms
Iteration   2: 9.624 ops/ms
Iteration   3: 9.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.585 ±(99.9%) 1.350 ops/ms [Average]
  (min, avg, max) = (9.499, 9.585, 9.630), stdev = 0.074
  CI (99.9%): [8.234, 10.935] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.268 ops/ms
# Warmup Iteration   2: 7.205 ops/ms
# Warmup Iteration   3: 7.957 ops/ms
Iteration   1: 8.166 ops/ms
Iteration   2: 8.017 ops/ms
Iteration   3: 8.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.203 ±(99.9%) 3.760 ops/ms [Average]
  (min, avg, max) = (8.017, 8.203, 8.425), stdev = 0.206
  CI (99.9%): [4.442, 11.963] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.837 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.011 ms/op
Iteration   1: 3.461 ±(99.9%) 0.007 ms/op
Iteration   2: 3.410 ±(99.9%) 0.009 ms/op
Iteration   3: 3.347 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.406 ±(99.9%) 1.045 ms/op [Average]
  (min, avg, max) = (3.347, 3.406, 3.461), stdev = 0.057
  CI (99.9%): [2.361, 4.451] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.372 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.004 ms/op
Iteration   1: 3.241 ±(99.9%) 0.008 ms/op
Iteration   2: 3.251 ±(99.9%) 0.007 ms/op
Iteration   3: 3.307 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.266 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.241, 3.266, 3.307), stdev = 0.036
  CI (99.9%): [2.617, 3.916] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.477 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.003 ms/op
Iteration   1: 3.500 ±(99.9%) 0.005 ms/op
Iteration   2: 3.314 ±(99.9%) 0.008 ms/op
Iteration   3: 3.426 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.414 ±(99.9%) 1.708 ms/op [Average]
  (min, avg, max) = (3.314, 3.414, 3.500), stdev = 0.094
  CI (99.9%): [1.706, 5.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.559 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.007 ms/op
Iteration   1: 3.943 ±(99.9%) 0.008 ms/op
Iteration   2: 3.888 ±(99.9%) 0.012 ms/op
Iteration   3: 3.831 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.887 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (3.831, 3.887, 3.943), stdev = 0.056
  CI (99.9%): [2.867, 4.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.073 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.010 ms/op
Iteration   1: 3.353 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  19.628 ms/op
                 createUser·p0.9999: 23.101 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   2: 3.605 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   6.504 ms/op
                 createUser·p0.99:   7.463 ms/op
                 createUser·p0.999:  21.615 ms/op
                 createUser·p0.9999: 29.332 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   3: 3.355 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  19.923 ms/op
                 createUser·p0.9999: 25.705 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279485
  mean =      3.433 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2987 
    [ 2.500,  5.000) = 264922 
    [ 5.000,  7.500) = 9935 
    [ 7.500, 10.000) = 892 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     19.989 ms/op
     p(99.9900) =     27.702 ms/op
     p(99.9990) =     29.505 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.428 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.009 ms/op
Iteration   1: 3.368 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  9.537 ms/op
                 existUser·p0.9999: 21.955 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   2: 3.274 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  14.425 ms/op
                 existUser·p0.9999: 24.788 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   3: 3.287 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  11.697 ms/op
                 existUser·p0.9999: 30.592 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289974
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24505 
    [ 2.500,  5.000) = 259681 
    [ 5.000,  7.500) = 4973 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     11.013 ms/op
     p(99.9900) =     28.574 ms/op
     p(99.9990) =     31.264 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.994 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.011 ms/op
Iteration   1: 3.348 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  20.330 ms/op
                 getUser·p0.9999: 30.030 ms/op
                 getUser·p1.00:   30.638 ms/op

Iteration   2: 3.410 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  22.731 ms/op
                 getUser·p0.9999: 26.923 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   3: 3.369 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  17.765 ms/op
                 getUser·p0.9999: 25.510 ms/op
                 getUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284149
  mean =      3.376 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12743 
    [ 2.500,  5.000) = 266232 
    [ 5.000,  7.500) = 3993 
    [ 7.500, 10.000) = 696 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     18.242 ms/op
     p(99.9900) =     29.134 ms/op
     p(99.9990) =     30.359 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.349 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.012 ms/op
Iteration   1: 4.038 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  17.099 ms/op
                 listUser·p0.9999: 28.380 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   2: 3.984 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  14.729 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 3.965 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.077 ms/op
                 listUser·p0.999:  15.014 ms/op
                 listUser·p0.9999: 16.318 ms/op
                 listUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240212
  mean =      3.995 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 230766 
    [ 5.000,  7.500) = 6894 
    [ 7.500, 10.000) = 1612 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 218 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.593 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     28.692 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.582 ± 1.647  ops/ms
ClientPb.existUser                       thrpt       3   9.858 ± 4.534  ops/ms
ClientPb.getUser                         thrpt       3   9.585 ± 1.350  ops/ms
ClientPb.listUser                        thrpt       3   8.203 ± 3.760  ops/ms
ClientPb.createUser                       avgt       3   3.406 ± 1.045   ms/op
ClientPb.existUser                        avgt       3   3.266 ± 0.649   ms/op
ClientPb.getUser                          avgt       3   3.414 ± 1.708   ms/op
ClientPb.listUser                         avgt       3   3.887 ± 1.020   ms/op
ClientPb.createUser                     sample  279485   3.433 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.204           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.989           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.702           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.015           ms/op
ClientPb.existUser                      sample  289974   3.309 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.436           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.013           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.574           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  284149   3.376 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.910           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.242           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.134           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.638           ms/op
ClientPb.listUser                       sample  240212   3.995 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.843           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.593           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.368           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.623           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.229           ms/op
