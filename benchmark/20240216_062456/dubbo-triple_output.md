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
# Warmup Iteration   1: 4.989 ops/ms
# Warmup Iteration   2: 11.972 ops/ms
# Warmup Iteration   3: 12.263 ops/ms
Iteration   1: 12.742 ops/ms
Iteration   2: 12.680 ops/ms
Iteration   3: 12.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.733 ±(99.9%) 0.909 ops/ms [Average]
  (min, avg, max) = (12.680, 12.733, 12.778), stdev = 0.050
  CI (99.9%): [11.824, 13.643] (assumes normal distribution)


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
# Warmup Iteration   1: 8.254 ops/ms
# Warmup Iteration   2: 12.863 ops/ms
# Warmup Iteration   3: 13.009 ops/ms
Iteration   1: 13.134 ops/ms
Iteration   2: 13.089 ops/ms
Iteration   3: 12.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.074 ±(99.9%) 1.261 ops/ms [Average]
  (min, avg, max) = (12.998, 13.074, 13.134), stdev = 0.069
  CI (99.9%): [11.813, 14.334] (assumes normal distribution)


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
# Warmup Iteration   1: 7.733 ops/ms
# Warmup Iteration   2: 12.478 ops/ms
# Warmup Iteration   3: 12.746 ops/ms
Iteration   1: 12.956 ops/ms
Iteration   2: 12.788 ops/ms
Iteration   3: 12.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.874 ±(99.9%) 1.532 ops/ms [Average]
  (min, avg, max) = (12.788, 12.874, 12.956), stdev = 0.084
  CI (99.9%): [11.342, 14.406] (assumes normal distribution)


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
# Warmup Iteration   1: 6.896 ops/ms
# Warmup Iteration   2: 10.576 ops/ms
# Warmup Iteration   3: 10.674 ops/ms
Iteration   1: 10.764 ops/ms
Iteration   2: 10.740 ops/ms
Iteration   3: 10.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.743 ±(99.9%) 0.363 ops/ms [Average]
  (min, avg, max) = (10.724, 10.743, 10.764), stdev = 0.020
  CI (99.9%): [10.380, 11.106] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.003 ms/op
Iteration   1: 2.543 ±(99.9%) 0.003 ms/op
Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
Iteration   3: 2.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.537 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (2.533, 2.537, 2.543), stdev = 0.006
  CI (99.9%): [2.432, 2.642] (assumes normal distribution)


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
Iteration   1: 2.426 ±(99.9%) 0.004 ms/op
Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
Iteration   3: 2.433 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.430 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (2.426, 2.430, 2.433), stdev = 0.004
  CI (99.9%): [2.358, 2.503] (assumes normal distribution)


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.053 ms/op [Average]
  (min, avg, max) = (2.494, 2.497, 2.499), stdev = 0.003
  CI (99.9%): [2.444, 2.549] (assumes normal distribution)


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
# Warmup Iteration   1: 4.640 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.004 ms/op
Iteration   2: 3.050 ±(99.9%) 0.005 ms/op
Iteration   3: 2.991 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.019 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (2.991, 3.019, 3.050), stdev = 0.030
  CI (99.9%): [2.478, 3.560] (assumes normal distribution)


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
# Warmup Iteration   1: 4.342 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  11.377 ms/op
                 createUser·p0.9999: 13.560 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.551 ms/op
                 createUser·p0.999:  9.025 ms/op
                 createUser·p0.9999: 12.095 ms/op
                 createUser·p1.00:   12.386 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  9.362 ms/op
                 createUser·p0.9999: 12.973 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381988
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 185725 
    [ 2.500,  3.750) = 192616 
    [ 3.750,  5.000) = 2882 
    [ 5.000,  6.250) = 304 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     15.897 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.908 ms/op
                 existUser·p0.999:  5.677 ms/op
                 existUser·p0.9999: 12.928 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 14.336 ms/op
                 existUser·p1.00:   15.925 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.953 ms/op
                 existUser·p0.999:  7.273 ms/op
                 existUser·p0.9999: 10.879 ms/op
                 existUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390257
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 194244 
    [ 2.500,  3.750) = 191675 
    [ 3.750,  5.000) = 3414 
    [ 5.000,  6.250) = 445 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      7.012 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.933 ms/op
     p(99.9999) =     15.925 ms/op
    p(100.0000) =     15.925 ms/op


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.604 ms/op
                 getUser·p0.999:  5.593 ms/op
                 getUser·p0.9999: 13.978 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.935 ms/op
                 getUser·p0.999:  7.144 ms/op
                 getUser·p0.9999: 12.354 ms/op
                 getUser·p1.00:   12.714 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  8.998 ms/op
                 getUser·p0.9999: 11.394 ms/op
                 getUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384265
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 191614 
    [ 2.500,  3.750) = 188514 
    [ 3.750,  5.000) = 3024 
    [ 5.000,  6.250) = 657 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      6.482 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.177 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 4.776 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.009 ms/op
Iteration   1: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 11.860 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   2: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.675 ms/op
                 listUser·p0.9999: 11.393 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.709 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.605 ms/op
                 listUser·p0.9999: 13.482 ms/op
                 listUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319012
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 95160 
    [ 2.500,  3.750) = 186099 
    [ 3.750,  5.000) = 29967 
    [ 5.000,  6.250) = 6118 
    [ 6.250,  7.500) = 853 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     12.129 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.733 ± 0.909  ops/ms
ClientPb.existUser                       thrpt       3  13.074 ± 1.261  ops/ms
ClientPb.getUser                         thrpt       3  12.874 ± 1.532  ops/ms
ClientPb.listUser                        thrpt       3  10.743 ± 0.363  ops/ms
ClientPb.createUser                       avgt       3   2.537 ± 0.105   ms/op
ClientPb.existUser                        avgt       3   2.430 ± 0.072   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.053   ms/op
ClientPb.listUser                         avgt       3   3.019 ± 0.541   ms/op
ClientPb.createUser                     sample  381988   2.510 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.984           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.333           ms/op
ClientPb.existUser                      sample  390257   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.803           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.012           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.189           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.925           ms/op
ClientPb.getUser                        sample  384265   2.496 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.835           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.482           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.582           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.942           ms/op
ClientPb.listUser                       sample  319012   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.709           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.129           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.369           ms/op
