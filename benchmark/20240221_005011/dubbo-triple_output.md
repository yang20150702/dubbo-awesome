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
# Warmup Iteration   1: 5.200 ops/ms
# Warmup Iteration   2: 11.917 ops/ms
# Warmup Iteration   3: 12.079 ops/ms
Iteration   1: 12.349 ops/ms
Iteration   2: 12.402 ops/ms
Iteration   3: 12.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.406 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (12.349, 12.406, 12.468), stdev = 0.060
  CI (99.9%): [11.312, 13.500] (assumes normal distribution)


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
# Warmup Iteration   1: 8.212 ops/ms
# Warmup Iteration   2: 12.971 ops/ms
# Warmup Iteration   3: 12.900 ops/ms
Iteration   1: 12.977 ops/ms
Iteration   2: 13.056 ops/ms
Iteration   3: 12.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.002 ±(99.9%) 0.851 ops/ms [Average]
  (min, avg, max) = (12.973, 13.002, 13.056), stdev = 0.047
  CI (99.9%): [12.151, 13.854] (assumes normal distribution)


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
# Warmup Iteration   1: 7.710 ops/ms
# Warmup Iteration   2: 12.555 ops/ms
# Warmup Iteration   3: 12.749 ops/ms
Iteration   1: 12.794 ops/ms
Iteration   2: 12.764 ops/ms
Iteration   3: 13.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.876 ±(99.9%) 3.067 ops/ms [Average]
  (min, avg, max) = (12.764, 12.876, 13.069), stdev = 0.168
  CI (99.9%): [9.809, 15.943] (assumes normal distribution)


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
# Warmup Iteration   1: 6.665 ops/ms
# Warmup Iteration   2: 10.190 ops/ms
# Warmup Iteration   3: 10.438 ops/ms
Iteration   1: 10.444 ops/ms
Iteration   2: 10.383 ops/ms
Iteration   3: 10.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.458 ±(99.9%) 1.522 ops/ms [Average]
  (min, avg, max) = (10.383, 10.458, 10.548), stdev = 0.083
  CI (99.9%): [8.936, 11.980] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.673 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.004 ms/op
Iteration   1: 2.576 ±(99.9%) 0.004 ms/op
Iteration   2: 2.565 ±(99.9%) 0.004 ms/op
Iteration   3: 2.568 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.570 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.565, 2.570, 2.576), stdev = 0.005
  CI (99.9%): [2.470, 2.669] (assumes normal distribution)


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.541 ±(99.9%) 0.004 ms/op
Iteration   2: 2.514 ±(99.9%) 0.003 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.527 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.514, 2.527, 2.541), stdev = 0.014
  CI (99.9%): [2.280, 2.773] (assumes normal distribution)


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.532 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
Iteration   3: 2.536 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.535 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (2.532, 2.535, 2.538), stdev = 0.003
  CI (99.9%): [2.476, 2.594] (assumes normal distribution)


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 2.996 ±(99.9%) 0.006 ms/op
Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
Iteration   3: 2.982 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.989 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (2.982, 2.989, 2.996), stdev = 0.007
  CI (99.9%): [2.864, 3.114] (assumes normal distribution)


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
Iteration   1: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  11.368 ms/op
                 createUser·p0.9999: 13.327 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  9.491 ms/op
                 createUser·p0.9999: 12.448 ms/op
                 createUser·p1.00:   12.698 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  8.520 ms/op
                 createUser·p0.9999: 10.797 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379080
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 182905 
    [ 2.500,  3.750) = 192045 
    [ 3.750,  5.000) = 2991 
    [ 5.000,  6.250) = 597 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     13.063 ms/op
     p(99.9990) =     16.850 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  5.838 ms/op
                 existUser·p0.9999: 14.174 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  7.481 ms/op
                 existUser·p0.9999: 12.970 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.705 ms/op
                 existUser·p0.999:  5.325 ms/op
                 existUser·p0.9999: 11.583 ms/op
                 existUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388427
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 189279 
    [ 2.500,  3.750) = 195906 
    [ 3.750,  5.000) = 2518 
    [ 5.000,  6.250) = 304 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      6.090 ms/op
     p(99.9900) =     13.522 ms/op
     p(99.9990) =     14.551 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.006 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  6.123 ms/op
                 getUser·p0.9999: 13.337 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.006 ms/op
                 getUser·p0.999:  6.346 ms/op
                 getUser·p0.9999: 12.543 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  7.848 ms/op
                 getUser·p0.9999: 11.532 ms/op
                 getUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383929
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 190312 
    [ 2.500,  3.750) = 188774 
    [ 3.750,  5.000) = 3856 
    [ 5.000,  6.250) = 496 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     13.549 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 4.951 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.009 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  8.585 ms/op
                 listUser·p0.9999: 10.774 ms/op
                 listUser·p1.00:   11.059 ms/op

Iteration   2: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.527 ms/op
                 listUser·p0.9999: 11.345 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.417 ms/op
                 listUser·p0.9999: 12.416 ms/op
                 listUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314869
  mean =      3.046 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 85243 
    [ 2.500,  3.750) = 188382 
    [ 3.750,  5.000) = 33988 
    [ 5.000,  6.250) = 5734 
    [ 6.250,  7.500) = 771 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 211 
    [10.000, 11.250) = 151 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     11.485 ms/op
     p(99.9990) =     12.712 ms/op
     p(99.9999) =     13.140 ms/op
    p(100.0000) =     13.140 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.406 ± 1.094  ops/ms
ClientPb.existUser                       thrpt       3  13.002 ± 0.851  ops/ms
ClientPb.getUser                         thrpt       3  12.876 ± 3.067  ops/ms
ClientPb.listUser                        thrpt       3  10.458 ± 1.522  ops/ms
ClientPb.createUser                       avgt       3   2.570 ± 0.100   ms/op
ClientPb.existUser                        avgt       3   2.527 ± 0.247   ms/op
ClientPb.getUser                          avgt       3   2.535 ± 0.059   ms/op
ClientPb.listUser                         avgt       3   2.989 ± 0.125   ms/op
ClientPb.createUser                     sample  379080   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.611           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.552           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.063           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.039           ms/op
ClientPb.existUser                      sample  388427   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.857           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.090           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.522           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.204           ms/op
ClientPb.getUser                        sample  383929   2.498 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.878           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.750           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.976           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.123           ms/op
ClientPb.listUser                       sample  314869   3.046 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.899           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.485           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.140           ms/op
