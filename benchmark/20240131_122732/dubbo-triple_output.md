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
# Warmup Iteration   1: 4.887 ops/ms
# Warmup Iteration   2: 12.033 ops/ms
# Warmup Iteration   3: 12.300 ops/ms
Iteration   1: 12.626 ops/ms
Iteration   2: 12.558 ops/ms
Iteration   3: 12.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.632 ±(99.9%) 1.421 ops/ms [Average]
  (min, avg, max) = (12.558, 12.632, 12.713), stdev = 0.078
  CI (99.9%): [11.211, 14.054] (assumes normal distribution)


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
# Warmup Iteration   1: 8.090 ops/ms
# Warmup Iteration   2: 12.976 ops/ms
# Warmup Iteration   3: 13.053 ops/ms
Iteration   1: 12.937 ops/ms
Iteration   2: 13.228 ops/ms
Iteration   3: 12.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.051 ±(99.9%) 2.837 ops/ms [Average]
  (min, avg, max) = (12.937, 13.051, 13.228), stdev = 0.156
  CI (99.9%): [10.214, 15.888] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.814 ops/ms
# Warmup Iteration   2: 12.662 ops/ms
# Warmup Iteration   3: 12.946 ops/ms
Iteration   1: 13.044 ops/ms
Iteration   2: 13.027 ops/ms
Iteration   3: 12.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.988 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (12.894, 12.988, 13.044), stdev = 0.082
  CI (99.9%): [11.493, 14.483] (assumes normal distribution)


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
# Warmup Iteration   1: 6.883 ops/ms
# Warmup Iteration   2: 10.675 ops/ms
# Warmup Iteration   3: 10.659 ops/ms
Iteration   1: 10.716 ops/ms
Iteration   2: 10.705 ops/ms
Iteration   3: 10.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.712 ±(99.9%) 0.119 ops/ms [Average]
  (min, avg, max) = (10.705, 10.712, 10.716), stdev = 0.006
  CI (99.9%): [10.594, 10.831] (assumes normal distribution)


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.538 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (2.500, 2.513, 2.538), stdev = 0.021
  CI (99.9%): [2.130, 2.896] (assumes normal distribution)


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
# Warmup Iteration   1: 3.715 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.412 ±(99.9%) 0.003 ms/op
Iteration   3: 2.414 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.420 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.412, 2.420, 2.434), stdev = 0.012
  CI (99.9%): [2.203, 2.637] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.004 ms/op
Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.373 ms/op [Average]
  (min, avg, max) = (2.462, 2.485, 2.499), stdev = 0.020
  CI (99.9%): [2.112, 2.858] (assumes normal distribution)


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
# Warmup Iteration   1: 4.675 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
Iteration   3: 3.028 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (3.028, 3.036, 3.044), stdev = 0.008
  CI (99.9%): [2.890, 3.183] (assumes normal distribution)


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
# Warmup Iteration   1: 4.186 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.721 ms/op
                 createUser·p0.999:  11.788 ms/op
                 createUser·p0.9999: 13.894 ms/op
                 createUser·p1.00:   15.073 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  9.198 ms/op
                 createUser·p0.9999: 11.886 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 10.966 ms/op
                 createUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382134
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 184104 
    [ 2.500,  3.750) = 194504 
    [ 3.750,  5.000) = 2801 
    [ 5.000,  6.250) = 231 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      8.943 ms/op
     p(99.9900) =     12.796 ms/op
     p(99.9990) =     14.136 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  7.659 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  7.765 ms/op
                 existUser·p0.9999: 12.302 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  8.044 ms/op
                 existUser·p0.9999: 11.993 ms/op
                 existUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393684
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 194595 
    [ 2.500,  3.750) = 196604 
    [ 3.750,  5.000) = 1682 
    [ 5.000,  6.250) = 260 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =      7.995 ms/op
     p(99.9900) =     13.929 ms/op
     p(99.9990) =     18.024 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 3.821 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  6.080 ms/op
                 getUser·p0.9999: 14.026 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.491 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   4.324 ms/op
                 getUser·p0.999:  9.383 ms/op
                 getUser·p0.9999: 12.152 ms/op
                 getUser·p1.00:   12.878 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  8.261 ms/op
                 getUser·p0.9999: 10.753 ms/op
                 getUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386076
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 192281 
    [ 2.500,  3.750) = 189080 
    [ 3.750,  5.000) = 3556 
    [ 5.000,  6.250) = 573 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      8.314 ms/op
     p(99.9900) =     13.245 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 4.862 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.008 ms/op
Iteration   1: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 11.165 ms/op
                 listUser·p1.00:   11.862 ms/op

Iteration   2: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.709 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.048 ms/op
                 listUser·p0.9999: 11.229 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.494 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.634 ms/op
                 listUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316226
  mean =      3.033 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 85948 
    [ 2.500,  3.750) = 190632 
    [ 3.750,  5.000) = 32631 
    [ 5.000,  6.250) = 5510 
    [ 6.250,  7.500) = 729 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 277 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     11.370 ms/op
     p(99.9990) =     12.119 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.632 ± 1.421  ops/ms
ClientPb.existUser                       thrpt       3  13.051 ± 2.837  ops/ms
ClientPb.getUser                         thrpt       3  12.988 ± 1.495  ops/ms
ClientPb.listUser                        thrpt       3  10.712 ± 0.119  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.383   ms/op
ClientPb.existUser                        avgt       3   2.420 ± 0.217   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.373   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.146   ms/op
ClientPb.createUser                     sample  382134   2.510 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.849           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.943           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.796           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.073           ms/op
ClientPb.existUser                      sample  393684   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.921           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.995           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.929           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.088           ms/op
ClientPb.getUser                        sample  386076   2.484 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.955           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.314           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.245           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.582           ms/op
ClientPb.listUser                       sample  316226   3.033 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.709           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.829           ms/op
