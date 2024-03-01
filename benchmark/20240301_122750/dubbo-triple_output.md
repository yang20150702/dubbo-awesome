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
# Warmup Iteration   1: 4.426 ops/ms
# Warmup Iteration   2: 12.198 ops/ms
# Warmup Iteration   3: 12.446 ops/ms
Iteration   1: 12.542 ops/ms
Iteration   2: 12.702 ops/ms
Iteration   3: 12.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.687 ±(99.9%) 2.516 ops/ms [Average]
  (min, avg, max) = (12.542, 12.687, 12.817), stdev = 0.138
  CI (99.9%): [10.171, 15.203] (assumes normal distribution)


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
# Warmup Iteration   1: 6.788 ops/ms
# Warmup Iteration   2: 13.285 ops/ms
# Warmup Iteration   3: 13.290 ops/ms
Iteration   1: 13.373 ops/ms
Iteration   2: 13.479 ops/ms
Iteration   3: 13.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.433 ±(99.9%) 0.991 ops/ms [Average]
  (min, avg, max) = (13.373, 13.433, 13.479), stdev = 0.054
  CI (99.9%): [12.442, 14.424] (assumes normal distribution)


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
# Warmup Iteration   1: 7.691 ops/ms
# Warmup Iteration   2: 12.612 ops/ms
# Warmup Iteration   3: 12.855 ops/ms
Iteration   1: 13.020 ops/ms
Iteration   2: 13.001 ops/ms
Iteration   3: 13.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.031 ±(99.9%) 0.666 ops/ms [Average]
  (min, avg, max) = (13.001, 13.031, 13.072), stdev = 0.037
  CI (99.9%): [12.365, 13.697] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.392 ops/ms
# Warmup Iteration   2: 10.734 ops/ms
# Warmup Iteration   3: 10.532 ops/ms
Iteration   1: 10.716 ops/ms
Iteration   2: 10.780 ops/ms
Iteration   3: 10.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.723 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (10.672, 10.723, 10.780), stdev = 0.054
  CI (99.9%): [9.737, 11.709] (assumes normal distribution)


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.003 ms/op
Iteration   1: 2.498 ±(99.9%) 0.003 ms/op
Iteration   2: 2.493 ±(99.9%) 0.003 ms/op
Iteration   3: 2.496 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.496 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (2.493, 2.496, 2.498), stdev = 0.003
  CI (99.9%): [2.448, 2.543] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.788 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.389 ±(99.9%) 0.004 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
Iteration   2: 2.392 ±(99.9%) 0.003 ms/op
Iteration   3: 2.389 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.401 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (2.389, 2.401, 2.423), stdev = 0.019
  CI (99.9%): [2.056, 2.746] (assumes normal distribution)


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.453 ±(99.9%) 0.003 ms/op
Iteration   3: 2.464 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.450 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (2.434, 2.450, 2.464), stdev = 0.015
  CI (99.9%): [2.173, 2.727] (assumes normal distribution)


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
# Warmup Iteration   1: 4.742 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
Iteration   1: 2.972 ±(99.9%) 0.006 ms/op
Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
Iteration   3: 2.972 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (2.959, 2.968, 2.972), stdev = 0.008
  CI (99.9%): [2.829, 3.107] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  10.305 ms/op
                 createUser·p0.9999: 14.437 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  9.478 ms/op
                 createUser·p0.9999: 13.042 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.006 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 12.176 ms/op
                 createUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384909
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 188230 
    [ 2.500,  3.750) = 191817 
    [ 3.750,  5.000) = 3824 
    [ 5.000,  6.250) = 467 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      9.048 ms/op
     p(99.9900) =     13.968 ms/op
     p(99.9990) =     14.744 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 3.877 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.402 ±(99.9%) 0.005 ms/op
Iteration   1: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.439 ms/op
                 existUser·p0.9999: 14.004 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.430 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  6.491 ms/op
                 existUser·p0.9999: 99.968 ms/op
                 existUser·p1.00:   100.401 ms/op

Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.813 ms/op
                 existUser·p0.999:  5.923 ms/op
                 existUser·p0.9999: 11.502 ms/op
                 existUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395719
  mean =      2.423 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 395393 
    [ 10.000,  20.000) = 294 
    [ 20.000,  30.000) = 0 
    [ 30.000,  40.000) = 0 
    [ 40.000,  50.000) = 0 
    [ 50.000,  60.000) = 0 
    [ 60.000,  70.000) = 0 
    [ 70.000,  80.000) = 0 
    [ 80.000,  90.000) = 0 
    [ 90.000, 100.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      6.111 ms/op
     p(99.9900) =     14.497 ms/op
     p(99.9990) =    100.270 ms/op
     p(99.9999) =    100.401 ms/op
    p(100.0000) =    100.401 ms/op


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.509 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  11.911 ms/op
                 getUser·p0.9999: 15.434 ms/op
                 getUser·p1.00:   15.843 ms/op

Iteration   2: 2.584 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.416 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  10.933 ms/op
                 getUser·p0.9999: 18.031 ms/op
                 getUser·p1.00:   18.678 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  9.370 ms/op
                 getUser·p0.9999: 12.272 ms/op
                 getUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376466
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 183521 
    [ 2.500,  3.750) = 185947 
    [ 3.750,  5.000) = 5186 
    [ 5.000,  6.250) = 1082 
    [ 6.250,  7.500) = 196 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.289 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     15.407 ms/op
     p(99.9990) =     18.358 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.009 ms/op
Iteration   1: 2.964 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 12.016 ms/op
                 listUser·p1.00:   12.648 ms/op

Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.858 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.934 ms/op
                 listUser·p0.9999: 11.185 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   3: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.062 ms/op
                 listUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322603
  mean =      2.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 98847 
    [ 2.500,  3.750) = 185592 
    [ 3.750,  5.000) = 30185 
    [ 5.000,  6.250) = 6467 
    [ 6.250,  7.500) = 731 
    [ 7.500,  8.750) = 145 
    [ 8.750, 10.000) = 237 
    [10.000, 11.250) = 181 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.682 ms/op
     p(99.9990) =     12.563 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt    Score   Error   Units
ClientPb.createUser                      thrpt       3   12.687 ± 2.516  ops/ms
ClientPb.existUser                       thrpt       3   13.433 ± 0.991  ops/ms
ClientPb.getUser                         thrpt       3   13.031 ± 0.666  ops/ms
ClientPb.listUser                        thrpt       3   10.723 ± 0.986  ops/ms
ClientPb.createUser                       avgt       3    2.496 ± 0.048   ms/op
ClientPb.existUser                        avgt       3    2.401 ± 0.345   ms/op
ClientPb.getUser                          avgt       3    2.450 ± 0.277   ms/op
ClientPb.listUser                         avgt       3    2.968 ± 0.139   ms/op
ClientPb.createUser                     sample  384909    2.491 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample            0.727           ms/op
ClientPb.createUser:createUser·p0.50    sample            2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample            3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample            3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample            3.879           ms/op
ClientPb.createUser:createUser·p0.999   sample            9.048           ms/op
ClientPb.createUser:createUser·p0.9999  sample           13.968           ms/op
ClientPb.createUser:createUser·p1.00    sample           14.893           ms/op
ClientPb.existUser                      sample  395719    2.423 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample            0.964           ms/op
ClientPb.existUser:existUser·p0.50      sample            2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample            2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample            3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample            3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample            6.111           ms/op
ClientPb.existUser:existUser·p0.9999    sample           14.497           ms/op
ClientPb.existUser:existUser·p1.00      sample          100.401           ms/op
ClientPb.getUser                        sample  376466    2.548 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample            0.509           ms/op
ClientPb.getUser:getUser·p0.50          sample            2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample            3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample            3.289           ms/op
ClientPb.getUser:getUser·p0.99          sample            4.186           ms/op
ClientPb.getUser:getUser·p0.999         sample            9.880           ms/op
ClientPb.getUser:getUser·p0.9999        sample           15.407           ms/op
ClientPb.getUser:getUser·p1.00          sample           18.678           ms/op
ClientPb.listUser                       sample  322603    2.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample            0.858           ms/op
ClientPb.listUser:listUser·p0.50        sample            2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample            3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample            4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample            5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample            9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample           11.682           ms/op
ClientPb.listUser:listUser·p1.00        sample           12.648           ms/op
