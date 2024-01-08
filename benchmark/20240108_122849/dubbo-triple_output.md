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
# Warmup Iteration   1: 4.965 ops/ms
# Warmup Iteration   2: 11.904 ops/ms
# Warmup Iteration   3: 12.091 ops/ms
Iteration   1: 12.506 ops/ms
Iteration   2: 12.295 ops/ms
Iteration   3: 12.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.353 ±(99.9%) 2.443 ops/ms [Average]
  (min, avg, max) = (12.258, 12.353, 12.506), stdev = 0.134
  CI (99.9%): [9.910, 14.796] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.175 ops/ms
# Warmup Iteration   2: 13.054 ops/ms
# Warmup Iteration   3: 13.255 ops/ms
Iteration   1: 13.162 ops/ms
Iteration   2: 13.081 ops/ms
Iteration   3: 13.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.141 ±(99.9%) 0.967 ops/ms [Average]
  (min, avg, max) = (13.081, 13.141, 13.180), stdev = 0.053
  CI (99.9%): [12.174, 14.109] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.023 ops/ms
# Warmup Iteration   2: 12.836 ops/ms
# Warmup Iteration   3: 12.749 ops/ms
Iteration   1: 12.918 ops/ms
Iteration   2: 12.914 ops/ms
Iteration   3: 12.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.902 ±(99.9%) 0.436 ops/ms [Average]
  (min, avg, max) = (12.875, 12.902, 12.918), stdev = 0.024
  CI (99.9%): [12.466, 13.339] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.668 ops/ms
# Warmup Iteration   2: 10.620 ops/ms
# Warmup Iteration   3: 10.723 ops/ms
Iteration   1: 10.723 ops/ms
Iteration   2: 10.968 ops/ms
Iteration   3: 10.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.854 ±(99.9%) 2.251 ops/ms [Average]
  (min, avg, max) = (10.723, 10.854, 10.968), stdev = 0.123
  CI (99.9%): [8.603, 13.105] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.026 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.610 ±(99.9%) 0.004 ms/op
Iteration   2: 2.569 ±(99.9%) 0.003 ms/op
Iteration   3: 2.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.573 ±(99.9%) 0.637 ms/op [Average]
  (min, avg, max) = (2.540, 2.573, 2.610), stdev = 0.035
  CI (99.9%): [1.936, 3.210] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.628 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.406 ±(99.9%) 0.004 ms/op
Iteration   2: 2.418 ±(99.9%) 0.003 ms/op
Iteration   3: 2.435 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.419 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.406, 2.419, 2.435), stdev = 0.014
  CI (99.9%): [2.155, 2.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.003 ms/op
Iteration   3: 2.513 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.504 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.490, 2.504, 2.513), stdev = 0.012
  CI (99.9%): [2.283, 2.725] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.659 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
Iteration   3: 3.003 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.002 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (2.987, 3.002, 3.016), stdev = 0.015
  CI (99.9%): [2.735, 3.270] (assumes normal distribution)


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
# Warmup Iteration   1: 4.185 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  6.699 ms/op
                 createUser·p0.9999: 13.453 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.449 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 12.210 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 11.183 ms/op
                 createUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386058
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 187994 
    [ 2.500,  3.750) = 194678 
    [ 3.750,  5.000) = 2565 
    [ 5.000,  6.250) = 314 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 133 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     14.115 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  6.658 ms/op
                 existUser·p0.9999: 13.976 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  6.375 ms/op
                 existUser·p0.9999: 10.960 ms/op
                 existUser·p1.00:   12.108 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  7.899 ms/op
                 existUser·p0.9999: 13.401 ms/op
                 existUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391425
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 194481 
    [ 2.500,  3.750) = 194245 
    [ 3.750,  5.000) = 1960 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 134 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =      6.591 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  5.721 ms/op
                 getUser·p0.9999: 13.632 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   4.003 ms/op
                 getUser·p0.999:  8.569 ms/op
                 getUser·p0.9999: 12.125 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  5.597 ms/op
                 getUser·p0.9999: 10.535 ms/op
                 getUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388749
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 194688 
    [ 2.500,  3.750) = 189995 
    [ 3.750,  5.000) = 3029 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.217 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     13.790 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 4.871 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
Iteration   1: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.773 ms/op
                 listUser·p0.9999: 13.147 ms/op
                 listUser·p1.00:   14.287 ms/op

Iteration   2: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 10.902 ms/op
                 listUser·p1.00:   11.305 ms/op

Iteration   3: 3.048 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.589 ms/op
                 listUser·p0.9999: 12.501 ms/op
                 listUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316333
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 90202 
    [ 2.500,  3.750) = 184771 
    [ 3.750,  5.000) = 33631 
    [ 5.000,  6.250) = 6278 
    [ 6.250,  7.500) = 664 
    [ 7.500,  8.750) = 156 
    [ 8.750, 10.000) = 268 
    [10.000, 11.250) = 159 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     12.453 ms/op
     p(99.9990) =     13.916 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.353 ± 2.443  ops/ms
ClientPb.existUser                       thrpt       3  13.141 ± 0.967  ops/ms
ClientPb.getUser                         thrpt       3  12.902 ± 0.436  ops/ms
ClientPb.listUser                        thrpt       3  10.854 ± 2.251  ops/ms
ClientPb.createUser                       avgt       3   2.573 ± 0.637   ms/op
ClientPb.existUser                        avgt       3   2.419 ± 0.264   ms/op
ClientPb.getUser                          avgt       3   2.504 ± 0.221   ms/op
ClientPb.listUser                         avgt       3   3.002 ± 0.267   ms/op
ClientPb.createUser                     sample  386058   2.484 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.888           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.110           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.124           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.516           ms/op
ClientPb.existUser                      sample  391425   2.450 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.732           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.591           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.402           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.320           ms/op
ClientPb.getUser                        sample  388749   2.467 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.910           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.217           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.993           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.090           ms/op
ClientPb.listUser                       sample  316333   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.453           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.287           ms/op
