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
# Warmup Iteration   1: 5.660 ops/ms
# Warmup Iteration   2: 12.300 ops/ms
# Warmup Iteration   3: 12.366 ops/ms
Iteration   1: 12.692 ops/ms
Iteration   2: 12.555 ops/ms
Iteration   3: 12.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.660 ±(99.9%) 1.704 ops/ms [Average]
  (min, avg, max) = (12.555, 12.660, 12.733), stdev = 0.093
  CI (99.9%): [10.957, 14.364] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.023 ops/ms
# Warmup Iteration   2: 13.012 ops/ms
# Warmup Iteration   3: 13.174 ops/ms
Iteration   1: 13.119 ops/ms
Iteration   2: 13.179 ops/ms
Iteration   3: 13.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.152 ±(99.9%) 0.554 ops/ms [Average]
  (min, avg, max) = (13.119, 13.152, 13.179), stdev = 0.030
  CI (99.9%): [12.598, 13.707] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.961 ops/ms
# Warmup Iteration   2: 12.393 ops/ms
# Warmup Iteration   3: 12.625 ops/ms
Iteration   1: 12.545 ops/ms
Iteration   2: 12.768 ops/ms
Iteration   3: 12.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.619 ±(99.9%) 2.347 ops/ms [Average]
  (min, avg, max) = (12.545, 12.619, 12.768), stdev = 0.129
  CI (99.9%): [10.272, 14.966] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.647 ops/ms
# Warmup Iteration   2: 10.214 ops/ms
# Warmup Iteration   3: 10.520 ops/ms
Iteration   1: 10.529 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.546 ±(99.9%) 0.270 ops/ms [Average]
  (min, avg, max) = (10.529, 10.546, 10.557), stdev = 0.015
  CI (99.9%): [10.277, 10.816] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.925 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.003 ms/op
Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (2.503, 2.534, 2.563), stdev = 0.030
  CI (99.9%): [1.988, 3.081] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.583 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.469 ±(99.9%) 0.094 ms/op [Average]
  (min, avg, max) = (2.465, 2.469, 2.475), stdev = 0.005
  CI (99.9%): [2.375, 2.564] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.928 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.412 ±(99.9%) 0.003 ms/op
Iteration   1: 2.419 ±(99.9%) 0.004 ms/op
Iteration   2: 2.398 ±(99.9%) 0.003 ms/op
Iteration   3: 2.408 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.408 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.398, 2.408, 2.419), stdev = 0.010
  CI (99.9%): [2.217, 2.599] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.603 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.005 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
Iteration   3: 3.038 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.037 ±(99.9%) 0.050 ms/op [Average]
  (min, avg, max) = (3.034, 3.037, 3.039), stdev = 0.003
  CI (99.9%): [2.986, 3.087] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.362 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.496 ms/op
                 createUser·p0.999:  10.963 ms/op
                 createUser·p0.9999: 13.533 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.490 ms/op
                 createUser·p0.999:  6.492 ms/op
                 createUser·p0.9999: 12.911 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  9.552 ms/op
                 createUser·p0.9999: 14.601 ms/op
                 createUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385489
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 187348 
    [ 2.500,  3.750) = 194963 
    [ 3.750,  5.000) = 2465 
    [ 5.000,  6.250) = 215 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      9.380 ms/op
     p(99.9900) =     13.627 ms/op
     p(99.9990) =     15.761 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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
# Warmup Iteration   1: 3.604 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.588 ms/op
                 existUser·p0.9999: 13.990 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  8.072 ms/op
                 existUser·p0.9999: 12.239 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  8.413 ms/op
                 existUser·p0.9999: 11.665 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392413
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 194710 
    [ 2.500,  3.750) = 194642 
    [ 3.750,  5.000) = 2133 
    [ 5.000,  6.250) = 367 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.575 ms/op
     p(99.9000) =      8.315 ms/op
     p(99.9900) =     13.251 ms/op
     p(99.9990) =     14.616 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  5.693 ms/op
                 getUser·p0.9999: 13.978 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.651 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.924 ms/op
                 getUser·p0.999:  9.053 ms/op
                 getUser·p0.9999: 13.686 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  8.028 ms/op
                 getUser·p0.9999: 10.897 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384825
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 189901 
    [ 2.500,  3.750) = 190063 
    [ 3.750,  5.000) = 3611 
    [ 5.000,  6.250) = 763 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      6.668 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     14.388 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 4.776 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.009 ms/op
Iteration   1: 3.054 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.841 ms/op
                 listUser·p0.999:  9.245 ms/op
                 listUser·p0.9999: 12.215 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   2: 3.094 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.817 ms/op
                 listUser·p0.9999: 11.977 ms/op
                 listUser·p1.00:   12.730 ms/op

Iteration   3: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.307 ms/op
                 listUser·p0.9999: 10.782 ms/op
                 listUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312484
  mean =      3.069 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 84035 
    [ 2.500,  3.750) = 185662 
    [ 3.750,  5.000) = 33819 
    [ 5.000,  6.250) = 7267 
    [ 6.250,  7.500) = 898 
    [ 7.500,  8.750) = 258 
    [ 8.750, 10.000) = 234 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     11.690 ms/op
     p(99.9990) =     12.564 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.660 ± 1.704  ops/ms
ClientPb.existUser                       thrpt       3  13.152 ± 0.554  ops/ms
ClientPb.getUser                         thrpt       3  12.619 ± 2.347  ops/ms
ClientPb.listUser                        thrpt       3  10.546 ± 0.270  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.546   ms/op
ClientPb.existUser                        avgt       3   2.469 ± 0.094   ms/op
ClientPb.getUser                          avgt       3   2.408 ± 0.191   ms/op
ClientPb.listUser                         avgt       3   3.037 ± 0.050   ms/op
ClientPb.createUser                     sample  385489   2.488 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.994           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.380           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.627           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.794           ms/op
ClientPb.existUser                      sample  392413   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.891           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.575           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.315           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.251           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.746           ms/op
ClientPb.getUser                        sample  384825   2.493 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.651           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.668           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.648           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.122           ms/op
ClientPb.listUser                       sample  312484   3.069 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.880           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.690           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.271           ms/op
