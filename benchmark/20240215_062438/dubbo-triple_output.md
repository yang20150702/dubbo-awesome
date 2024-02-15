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
# Warmup Iteration   1: 4.446 ops/ms
# Warmup Iteration   2: 12.091 ops/ms
# Warmup Iteration   3: 12.420 ops/ms
Iteration   1: 12.676 ops/ms
Iteration   2: 12.671 ops/ms
Iteration   3: 12.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.717 ±(99.9%) 1.364 ops/ms [Average]
  (min, avg, max) = (12.671, 12.717, 12.803), stdev = 0.075
  CI (99.9%): [11.353, 14.081] (assumes normal distribution)


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
# Warmup Iteration   1: 7.590 ops/ms
# Warmup Iteration   2: 13.342 ops/ms
# Warmup Iteration   3: 13.148 ops/ms
Iteration   1: 13.164 ops/ms
Iteration   2: 13.254 ops/ms
Iteration   3: 13.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.155 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (13.047, 13.155, 13.254), stdev = 0.104
  CI (99.9%): [11.259, 15.051] (assumes normal distribution)


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
# Warmup Iteration   1: 7.458 ops/ms
# Warmup Iteration   2: 12.389 ops/ms
# Warmup Iteration   3: 12.691 ops/ms
Iteration   1: 12.689 ops/ms
Iteration   2: 12.836 ops/ms
Iteration   3: 12.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.693 ±(99.9%) 2.563 ops/ms [Average]
  (min, avg, max) = (12.555, 12.693, 12.836), stdev = 0.141
  CI (99.9%): [10.130, 15.256] (assumes normal distribution)


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
# Warmup Iteration   1: 6.331 ops/ms
# Warmup Iteration   2: 10.402 ops/ms
# Warmup Iteration   3: 10.508 ops/ms
Iteration   1: 10.624 ops/ms
Iteration   2: 10.593 ops/ms
Iteration   3: 10.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.591 ±(99.9%) 0.635 ops/ms [Average]
  (min, avg, max) = (10.555, 10.591, 10.624), stdev = 0.035
  CI (99.9%): [9.956, 11.226] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.003 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
Iteration   3: 2.531 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.506 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (2.488, 2.506, 2.531), stdev = 0.022
  CI (99.9%): [2.105, 2.907] (assumes normal distribution)


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.004 ms/op
Iteration   1: 2.450 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.434 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.434, 2.443, 2.450), stdev = 0.008
  CI (99.9%): [2.291, 2.595] (assumes normal distribution)


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
# Warmup Iteration   1: 3.946 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
Iteration   3: 2.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.480 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.469, 2.480, 2.493), stdev = 0.012
  CI (99.9%): [2.260, 2.700] (assumes normal distribution)


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
# Warmup Iteration   1: 4.803 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
Iteration   2: 2.978 ±(99.9%) 0.007 ms/op
Iteration   3: 2.954 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.972 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (2.954, 2.972, 2.983), stdev = 0.015
  CI (99.9%): [2.691, 3.252] (assumes normal distribution)


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  10.927 ms/op
                 createUser·p0.9999: 13.609 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  10.004 ms/op
                 createUser·p0.9999: 12.636 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 11.813 ms/op
                 createUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381153
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 183657 
    [ 2.500,  3.750) = 193426 
    [ 3.750,  5.000) = 3045 
    [ 5.000,  6.250) = 500 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      8.714 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.192 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
Iteration   1: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  5.700 ms/op
                 existUser·p0.9999: 13.778 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.707 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  6.061 ms/op
                 existUser·p0.9999: 13.157 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.701 ms/op
                 existUser·p0.999:  7.175 ms/op
                 existUser·p0.9999: 12.272 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389868
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 192001 
    [ 2.500,  3.750) = 194886 
    [ 3.750,  5.000) = 2179 
    [ 5.000,  6.250) = 365 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      6.384 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.015 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.006 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  6.661 ms/op
                 getUser·p0.9999: 13.860 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 12.324 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  6.748 ms/op
                 getUser·p0.9999: 10.309 ms/op
                 getUser·p1.00:   10.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387116
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 194120 
    [ 2.500,  3.750) = 188990 
    [ 3.750,  5.000) = 3021 
    [ 5.000,  6.250) = 441 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      6.875 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     14.260 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.009 ms/op
Iteration   1: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 12.261 ms/op
                 listUser·p1.00:   12.796 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.786 ms/op
                 listUser·p0.9999: 12.655 ms/op
                 listUser·p1.00:   13.533 ms/op

Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.738 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.738 ms/op
                 listUser·p0.9999: 10.131 ms/op
                 listUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318766
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 91221 
    [ 2.500,  3.750) = 189186 
    [ 3.750,  5.000) = 30951 
    [ 5.000,  6.250) = 5903 
    [ 6.250,  7.500) = 686 
    [ 7.500,  8.750) = 299 
    [ 8.750, 10.000) = 220 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     12.241 ms/op
     p(99.9990) =     13.461 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.717 ± 1.364  ops/ms
ClientPb.existUser                       thrpt       3  13.155 ± 1.896  ops/ms
ClientPb.getUser                         thrpt       3  12.693 ± 2.563  ops/ms
ClientPb.listUser                        thrpt       3  10.591 ± 0.635  ops/ms
ClientPb.createUser                       avgt       3   2.506 ± 0.401   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.152   ms/op
ClientPb.getUser                          avgt       3   2.480 ± 0.220   ms/op
ClientPb.listUser                         avgt       3   2.972 ± 0.280   ms/op
ClientPb.createUser                     sample  381153   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.848           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.714           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  389868   2.460 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.707           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.384           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  387116   2.477 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.959           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.875           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.222           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  318766   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.738           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.077           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.241           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.533           ms/op
