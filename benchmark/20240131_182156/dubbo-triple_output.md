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
# Warmup Iteration   1: 4.511 ops/ms
# Warmup Iteration   2: 12.143 ops/ms
# Warmup Iteration   3: 11.873 ops/ms
Iteration   1: 12.321 ops/ms
Iteration   2: 12.420 ops/ms
Iteration   3: 12.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.377 ±(99.9%) 0.934 ops/ms [Average]
  (min, avg, max) = (12.321, 12.377, 12.420), stdev = 0.051
  CI (99.9%): [11.444, 13.311] (assumes normal distribution)


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
# Warmup Iteration   1: 7.787 ops/ms
# Warmup Iteration   2: 12.688 ops/ms
# Warmup Iteration   3: 12.663 ops/ms
Iteration   1: 12.629 ops/ms
Iteration   2: 12.767 ops/ms
Iteration   3: 12.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.698 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (12.629, 12.698, 12.767), stdev = 0.069
  CI (99.9%): [11.431, 13.966] (assumes normal distribution)


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
# Warmup Iteration   1: 7.667 ops/ms
# Warmup Iteration   2: 12.255 ops/ms
# Warmup Iteration   3: 12.377 ops/ms
Iteration   1: 12.665 ops/ms
Iteration   2: 12.489 ops/ms
Iteration   3: 12.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.541 ±(99.9%) 1.966 ops/ms [Average]
  (min, avg, max) = (12.469, 12.541, 12.665), stdev = 0.108
  CI (99.9%): [10.576, 14.507] (assumes normal distribution)


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
# Warmup Iteration   1: 6.371 ops/ms
# Warmup Iteration   2: 10.228 ops/ms
# Warmup Iteration   3: 10.398 ops/ms
Iteration   1: 10.479 ops/ms
Iteration   2: 10.418 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.456 ±(99.9%) 0.611 ops/ms [Average]
  (min, avg, max) = (10.418, 10.456, 10.479), stdev = 0.033
  CI (99.9%): [9.845, 11.067] (assumes normal distribution)


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.682 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.591 ±(99.9%) 0.004 ms/op
Iteration   1: 2.637 ±(99.9%) 0.004 ms/op
Iteration   2: 2.601 ±(99.9%) 0.005 ms/op
Iteration   3: 2.576 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.605 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (2.576, 2.605, 2.637), stdev = 0.030
  CI (99.9%): [2.054, 3.155] (assumes normal distribution)


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.003 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.511 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (2.508, 2.511, 2.515), stdev = 0.004
  CI (99.9%): [2.443, 2.579] (assumes normal distribution)


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
# Warmup Iteration   1: 4.282 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.004 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
Iteration   3: 2.558 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.547 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.531, 2.547, 2.558), stdev = 0.014
  CI (99.9%): [2.293, 2.801] (assumes normal distribution)


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
# Warmup Iteration   1: 4.924 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.006 ms/op
Iteration   1: 3.099 ±(99.9%) 0.005 ms/op
Iteration   2: 3.106 ±(99.9%) 0.004 ms/op
Iteration   3: 3.089 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.098 ±(99.9%) 0.154 ms/op [Average]
  (min, avg, max) = (3.089, 3.098, 3.106), stdev = 0.008
  CI (99.9%): [2.944, 3.252] (assumes normal distribution)


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.733 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.006 ms/op
Iteration   1: 2.581 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.747 ms/op
                 createUser·p0.9999: 14.543 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  10.306 ms/op
                 createUser·p0.9999: 12.812 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   3: 2.574 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 11.338 ms/op
                 createUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373206
  mean =      2.570 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 178662 
    [ 2.500,  3.750) = 190881 
    [ 3.750,  5.000) = 2858 
    [ 5.000,  6.250) = 291 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      9.211 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.672 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.502 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.477 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.667 ms/op
                 existUser·p0.999:  11.358 ms/op
                 existUser·p0.9999: 14.491 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.615 ms/op
                 existUser·p0.999:  9.159 ms/op
                 existUser·p0.9999: 13.667 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  8.249 ms/op
                 existUser·p0.9999: 11.889 ms/op
                 existUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382554
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 188168 
    [ 2.500,  3.750) = 190603 
    [ 3.750,  5.000) = 2611 
    [ 5.000,  6.250) = 509 
    [ 6.250,  7.500) = 136 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     14.831 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.589 ±(99.9%) 0.006 ms/op
Iteration   1: 2.589 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.355 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  11.911 ms/op
                 getUser·p0.9999: 14.461 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  10.068 ms/op
                 getUser·p0.9999: 14.238 ms/op
                 getUser·p1.00:   16.548 ms/op

Iteration   3: 2.598 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   2.638 ms/op
                 getUser·p0.90:   3.174 ms/op
                 getUser·p0.95:   3.342 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  10.288 ms/op
                 getUser·p0.9999: 12.021 ms/op
                 getUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 371088
  mean =      2.585 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 176119 
    [ 2.500,  3.750) = 187410 
    [ 3.750,  5.000) = 6345 
    [ 5.000,  6.250) = 695 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.334 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =     10.140 ms/op
     p(99.9900) =     14.103 ms/op
     p(99.9990) =     15.366 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.009 ms/op
Iteration   1: 3.106 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.382 ms/op
                 listUser·p1.00:   11.829 ms/op

Iteration   2: 3.119 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.964 ms/op
                 listUser·p0.999:  10.256 ms/op
                 listUser·p0.9999: 14.332 ms/op
                 listUser·p1.00:   14.926 ms/op

Iteration   3: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  10.060 ms/op
                 listUser·p0.9999: 11.970 ms/op
                 listUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309813
  mean =      3.096 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 75558 
    [ 2.500,  3.750) = 189411 
    [ 3.750,  5.000) = 36410 
    [ 5.000,  6.250) = 6655 
    [ 6.250,  7.500) = 962 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 233 
    [10.000, 11.250) = 195 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     10.046 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     14.641 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.377 ± 0.934  ops/ms
ClientPb.existUser                       thrpt       3  12.698 ± 1.268  ops/ms
ClientPb.getUser                         thrpt       3  12.541 ± 1.966  ops/ms
ClientPb.listUser                        thrpt       3  10.456 ± 0.611  ops/ms
ClientPb.createUser                       avgt       3   2.605 ± 0.550   ms/op
ClientPb.existUser                        avgt       3   2.511 ± 0.068   ms/op
ClientPb.getUser                          avgt       3   2.547 ± 0.254   ms/op
ClientPb.listUser                         avgt       3   3.098 ± 0.154   ms/op
ClientPb.createUser                     sample  373206   2.570 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.779           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.211           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.877           ms/op
ClientPb.existUser                      sample  382554   2.508 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.477           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.060           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.992           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.155           ms/op
ClientPb.getUser                        sample  371088   2.585 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.753           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.609           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.140           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.103           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.548           ms/op
ClientPb.listUser                       sample  309813   3.096 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.795           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.751           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.046           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.500           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.926           ms/op
