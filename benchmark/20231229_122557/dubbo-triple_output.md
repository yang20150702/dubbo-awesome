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
# Warmup Iteration   1: 4.465 ops/ms
# Warmup Iteration   2: 12.007 ops/ms
# Warmup Iteration   3: 12.316 ops/ms
Iteration   1: 12.586 ops/ms
Iteration   2: 12.676 ops/ms
Iteration   3: 12.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.648 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (12.586, 12.648, 12.681), stdev = 0.053
  CI (99.9%): [11.678, 13.617] (assumes normal distribution)


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
# Warmup Iteration   1: 8.290 ops/ms
# Warmup Iteration   2: 12.938 ops/ms
# Warmup Iteration   3: 13.031 ops/ms
Iteration   1: 13.039 ops/ms
Iteration   2: 12.855 ops/ms
Iteration   3: 12.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.867 ±(99.9%) 3.053 ops/ms [Average]
  (min, avg, max) = (12.705, 12.867, 13.039), stdev = 0.167
  CI (99.9%): [9.814, 15.919] (assumes normal distribution)


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
# Warmup Iteration   1: 7.524 ops/ms
# Warmup Iteration   2: 12.452 ops/ms
# Warmup Iteration   3: 12.749 ops/ms
Iteration   1: 12.854 ops/ms
Iteration   2: 12.844 ops/ms
Iteration   3: 12.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.899 ±(99.9%) 1.585 ops/ms [Average]
  (min, avg, max) = (12.844, 12.899, 12.999), stdev = 0.087
  CI (99.9%): [11.314, 14.484] (assumes normal distribution)


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
# Warmup Iteration   1: 6.688 ops/ms
# Warmup Iteration   2: 10.419 ops/ms
# Warmup Iteration   3: 10.619 ops/ms
Iteration   1: 10.627 ops/ms
Iteration   2: 10.588 ops/ms
Iteration   3: 10.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.607 ±(99.9%) 0.361 ops/ms [Average]
  (min, avg, max) = (10.588, 10.607, 10.627), stdev = 0.020
  CI (99.9%): [10.246, 10.968] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.577 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
Iteration   3: 2.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.539 ±(99.9%) 0.637 ms/op [Average]
  (min, avg, max) = (2.509, 2.539, 2.577), stdev = 0.035
  CI (99.9%): [1.902, 3.175] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.456 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.477 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (2.456, 2.477, 2.508), stdev = 0.028
  CI (99.9%): [1.974, 2.980] (assumes normal distribution)


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.556 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.525 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (2.505, 2.525, 2.556), stdev = 0.027
  CI (99.9%): [2.035, 3.016] (assumes normal distribution)


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
# Warmup Iteration   1: 4.580 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.004 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
Iteration   2: 2.978 ±(99.9%) 0.004 ms/op
Iteration   3: 2.986 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (2.978, 2.987, 2.999), stdev = 0.010
  CI (99.9%): [2.796, 3.179] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.102 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.714 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.977 ms/op
                 createUser·p0.9999: 17.051 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  9.455 ms/op
                 createUser·p0.9999: 11.729 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.312 ms/op
                 createUser·p0.9999: 9.727 ms/op
                 createUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379910
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 183691 
    [ 2.500,  3.750) = 192577 
    [ 3.750,  5.000) = 2892 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.340 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     17.243 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 3.681 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  5.908 ms/op
                 existUser·p0.9999: 13.780 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  8.772 ms/op
                 existUser·p0.9999: 13.548 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  6.883 ms/op
                 existUser·p0.9999: 12.009 ms/op
                 existUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390628
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 194865 
    [ 2.500,  3.750) = 192401 
    [ 3.750,  5.000) = 2534 
    [ 5.000,  6.250) = 365 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =      8.122 ms/op
     p(99.9900) =     13.467 ms/op
     p(99.9990) =     13.918 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  11.311 ms/op
                 getUser·p0.9999: 13.909 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.322 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  5.690 ms/op
                 getUser·p0.9999: 15.398 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  7.995 ms/op
                 getUser·p0.9999: 11.427 ms/op
                 getUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380744
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 187117 
    [ 2.500,  3.750) = 188422 
    [ 3.750,  5.000) = 4335 
    [ 5.000,  6.250) = 422 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      6.038 ms/op
     p(99.9900) =     13.828 ms/op
     p(99.9990) =     15.797 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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
# Warmup Iteration   1: 4.847 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.009 ms/op
Iteration   1: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.683 ms/op
                 listUser·p0.999:  9.025 ms/op
                 listUser·p0.9999: 11.263 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   2: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.634 ms/op
                 listUser·p0.999:  9.988 ms/op
                 listUser·p0.9999: 13.088 ms/op
                 listUser·p1.00:   14.189 ms/op

Iteration   3: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.765 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 12.370 ms/op
                 listUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317666
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 90609 
    [ 2.500,  3.750) = 187684 
    [ 3.750,  5.000) = 31241 
    [ 5.000,  6.250) = 6482 
    [ 6.250,  7.500) = 854 
    [ 7.500,  8.750) = 274 
    [ 8.750, 10.000) = 187 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.213 ms/op
     p(99.9900) =     12.374 ms/op
     p(99.9990) =     13.584 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.648 ± 0.970  ops/ms
ClientPb.existUser                       thrpt       3  12.867 ± 3.053  ops/ms
ClientPb.getUser                         thrpt       3  12.899 ± 1.585  ops/ms
ClientPb.listUser                        thrpt       3  10.607 ± 0.361  ops/ms
ClientPb.createUser                       avgt       3   2.539 ± 0.637   ms/op
ClientPb.existUser                        avgt       3   2.477 ± 0.503   ms/op
ClientPb.getUser                          avgt       3   2.525 ± 0.491   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.192   ms/op
ClientPb.createUser                     sample  379910   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.803           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.340           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.746           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.957           ms/op
ClientPb.existUser                      sample  390628   2.455 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.854           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.122           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.467           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  380744   2.519 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.658           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.038           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.828           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.040           ms/op
ClientPb.listUser                       sample  317666   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.974           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.213           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.374           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.189           ms/op
