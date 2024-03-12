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
# Warmup Iteration   1: 4.527 ops/ms
# Warmup Iteration   2: 12.084 ops/ms
# Warmup Iteration   3: 12.403 ops/ms
Iteration   1: 12.721 ops/ms
Iteration   2: 12.607 ops/ms
Iteration   3: 12.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.654 ±(99.9%) 1.083 ops/ms [Average]
  (min, avg, max) = (12.607, 12.654, 12.721), stdev = 0.059
  CI (99.9%): [11.571, 13.737] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.119 ops/ms
# Warmup Iteration   2: 13.233 ops/ms
# Warmup Iteration   3: 13.386 ops/ms
Iteration   1: 13.410 ops/ms
Iteration   2: 13.344 ops/ms
Iteration   3: 13.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.348 ±(99.9%) 1.103 ops/ms [Average]
  (min, avg, max) = (13.290, 13.348, 13.410), stdev = 0.060
  CI (99.9%): [12.244, 14.451] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.757 ops/ms
# Warmup Iteration   2: 12.866 ops/ms
# Warmup Iteration   3: 13.102 ops/ms
Iteration   1: 13.189 ops/ms
Iteration   2: 13.083 ops/ms
Iteration   3: 13.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.145 ±(99.9%) 1.009 ops/ms [Average]
  (min, avg, max) = (13.083, 13.145, 13.189), stdev = 0.055
  CI (99.9%): [12.136, 14.154] (assumes normal distribution)


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
# Warmup Iteration   1: 6.684 ops/ms
# Warmup Iteration   2: 10.681 ops/ms
# Warmup Iteration   3: 10.777 ops/ms
Iteration   1: 10.913 ops/ms
Iteration   2: 10.739 ops/ms
Iteration   3: 10.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.839 ±(99.9%) 1.640 ops/ms [Average]
  (min, avg, max) = (10.739, 10.839, 10.913), stdev = 0.090
  CI (99.9%): [9.199, 12.479] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.003 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.486 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (2.460, 2.486, 2.519), stdev = 0.030
  CI (99.9%): [1.929, 3.042] (assumes normal distribution)


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
# Warmup Iteration   1: 3.637 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.408 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.416 ±(99.9%) 0.004 ms/op
Iteration   1: 2.426 ±(99.9%) 0.004 ms/op
Iteration   2: 2.421 ±(99.9%) 0.004 ms/op
Iteration   3: 2.410 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.419 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.410, 2.419, 2.426), stdev = 0.008
  CI (99.9%): [2.267, 2.571] (assumes normal distribution)


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
# Warmup Iteration   1: 3.845 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.480 ±(99.9%) 0.004 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (2.457, 2.467, 2.480), stdev = 0.012
  CI (99.9%): [2.253, 2.681] (assumes normal distribution)


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
# Warmup Iteration   1: 4.786 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.005 ms/op
Iteration   1: 2.963 ±(99.9%) 0.004 ms/op
Iteration   2: 2.947 ±(99.9%) 0.006 ms/op
Iteration   3: 2.957 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.956 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (2.947, 2.956, 2.963), stdev = 0.008
  CI (99.9%): [2.801, 3.110] (assumes normal distribution)


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.006 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  6.914 ms/op
                 createUser·p0.9999: 13.697 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  5.874 ms/op
                 createUser·p0.9999: 12.812 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  8.432 ms/op
                 createUser·p0.9999: 11.125 ms/op
                 createUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 390032
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 195225 
    [ 2.500,  3.750) = 191090 
    [ 3.750,  5.000) = 2801 
    [ 5.000,  6.250) = 415 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.364 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     14.044 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.672 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.006 ms/op
Iteration   1: 2.387 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  6.377 ms/op
                 existUser·p0.9999: 14.582 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   2: 2.397 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  6.778 ms/op
                 existUser·p0.9999: 13.571 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.387 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  8.031 ms/op
                 existUser·p0.9999: 11.059 ms/op
                 existUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401190
  mean =      2.390 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 205841 
    [ 2.500,  3.750) = 192388 
    [ 3.750,  5.000) = 2265 
    [ 5.000,  6.250) = 213 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      7.887 ms/op
     p(99.9900) =     14.057 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.006 ms/op
Iteration   1: 2.415 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   2.933 ms/op
                 getUser·p0.95:   3.023 ms/op
                 getUser·p0.99:   3.437 ms/op
                 getUser·p0.999:  5.751 ms/op
                 getUser·p0.9999: 14.186 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.388 ms/op
                 getUser·p0.9999: 12.910 ms/op
                 getUser·p1.00:   13.353 ms/op

Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  6.508 ms/op
                 getUser·p0.9999: 11.455 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 394570
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 201312 
    [ 2.500,  3.750) = 189006 
    [ 3.750,  5.000) = 3145 
    [ 5.000,  6.250) = 620 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      6.298 ms/op
     p(99.9900) =     13.362 ms/op
     p(99.9990) =     14.340 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 4.731 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
Iteration   1: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  8.845 ms/op
                 listUser·p0.9999: 10.941 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   2: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 10.703 ms/op
                 listUser·p1.00:   11.551 ms/op

Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.820 ms/op
                 listUser·p0.9999: 10.939 ms/op
                 listUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319602
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 93552 
    [ 2.500,  3.750) = 187118 
    [ 3.750,  5.000) = 31653 
    [ 5.000,  6.250) = 5892 
    [ 6.250,  7.500) = 602 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     10.863 ms/op
     p(99.9990) =     11.928 ms/op
     p(99.9999) =     11.960 ms/op
    p(100.0000) =     11.960 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.654 ± 1.083  ops/ms
ClientPb.existUser                       thrpt       3  13.348 ± 1.103  ops/ms
ClientPb.getUser                         thrpt       3  13.145 ± 1.009  ops/ms
ClientPb.listUser                        thrpt       3  10.839 ± 1.640  ops/ms
ClientPb.createUser                       avgt       3   2.486 ± 0.556   ms/op
ClientPb.existUser                        avgt       3   2.419 ± 0.152   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.214   ms/op
ClientPb.listUser                         avgt       3   2.956 ± 0.155   ms/op
ClientPb.createUser                     sample  390032   2.459 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.738           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.499           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.364           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.173           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.189           ms/op
ClientPb.existUser                      sample  401190   2.390 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.741           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.904           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.887           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.057           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.434           ms/op
ClientPb.getUser                        sample  394570   2.431 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.691           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.454           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.298           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.362           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.631           ms/op
ClientPb.listUser                       sample  319602   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.912           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.028           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.863           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.960           ms/op
