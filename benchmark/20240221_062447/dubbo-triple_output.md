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
# Warmup Iteration   1: 4.484 ops/ms
# Warmup Iteration   2: 11.665 ops/ms
# Warmup Iteration   3: 12.021 ops/ms
Iteration   1: 12.383 ops/ms
Iteration   2: 12.334 ops/ms
Iteration   3: 12.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.360 ±(99.9%) 0.451 ops/ms [Average]
  (min, avg, max) = (12.334, 12.360, 12.383), stdev = 0.025
  CI (99.9%): [11.908, 12.811] (assumes normal distribution)


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
# Warmup Iteration   1: 7.731 ops/ms
# Warmup Iteration   2: 12.927 ops/ms
# Warmup Iteration   3: 13.037 ops/ms
Iteration   1: 13.083 ops/ms
Iteration   2: 13.169 ops/ms
Iteration   3: 12.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.081 ±(99.9%) 1.637 ops/ms [Average]
  (min, avg, max) = (12.990, 13.081, 13.169), stdev = 0.090
  CI (99.9%): [11.443, 14.718] (assumes normal distribution)


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
# Warmup Iteration   1: 7.897 ops/ms
# Warmup Iteration   2: 12.430 ops/ms
# Warmup Iteration   3: 12.642 ops/ms
Iteration   1: 12.610 ops/ms
Iteration   2: 12.672 ops/ms
Iteration   3: 12.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.598 ±(99.9%) 1.457 ops/ms [Average]
  (min, avg, max) = (12.513, 12.598, 12.672), stdev = 0.080
  CI (99.9%): [11.141, 14.055] (assumes normal distribution)


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
# Warmup Iteration   1: 6.932 ops/ms
# Warmup Iteration   2: 10.514 ops/ms
# Warmup Iteration   3: 10.468 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.541 ops/ms
Iteration   3: 10.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.583 ±(99.9%) 0.862 ops/ms [Average]
  (min, avg, max) = (10.541, 10.583, 10.634), stdev = 0.047
  CI (99.9%): [9.720, 11.445] (assumes normal distribution)


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
# Warmup Iteration   1: 4.325 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.596 ±(99.9%) 0.004 ms/op
Iteration   1: 2.631 ±(99.9%) 0.005 ms/op
Iteration   2: 2.593 ±(99.9%) 0.003 ms/op
Iteration   3: 2.563 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.596 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (2.563, 2.596, 2.631), stdev = 0.034
  CI (99.9%): [1.970, 3.222] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.743 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.003 ms/op
Iteration   3: 2.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.511 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.508, 2.511, 2.516), stdev = 0.005
  CI (99.9%): [2.424, 2.597] (assumes normal distribution)


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.004 ms/op
Iteration   1: 2.525 ±(99.9%) 0.004 ms/op
Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
Iteration   3: 2.570 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.546 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (2.525, 2.546, 2.570), stdev = 0.022
  CI (99.9%): [2.136, 2.956] (assumes normal distribution)


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
# Warmup Iteration   1: 4.796 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.005 ms/op
Iteration   1: 3.021 ±(99.9%) 0.005 ms/op
Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
Iteration   3: 3.015 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (3.015, 3.021, 3.027), stdev = 0.006
  CI (99.9%): [2.913, 3.129] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  11.403 ms/op
                 createUser·p0.9999: 13.683 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.931 ms/op
                 createUser·p0.999:  8.805 ms/op
                 createUser·p0.9999: 11.868 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  8.962 ms/op
                 createUser·p0.9999: 10.295 ms/op
                 createUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380077
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 182623 
    [ 2.500,  3.750) = 192571 
    [ 3.750,  5.000) = 3801 
    [ 5.000,  6.250) = 506 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 134 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     14.132 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  7.256 ms/op
                 existUser·p0.9999: 14.222 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.825 ms/op
                 existUser·p0.9999: 13.372 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  9.026 ms/op
                 existUser·p0.9999: 11.634 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386630
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 190325 
    [ 2.500,  3.750) = 193235 
    [ 3.750,  5.000) = 2241 
    [ 5.000,  6.250) = 419 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      6.087 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.363 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.839 ms/op
                 getUser·p0.999:  11.060 ms/op
                 getUser·p0.9999: 14.729 ms/op
                 getUser·p1.00:   15.565 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  5.671 ms/op
                 getUser·p0.9999: 12.931 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  7.996 ms/op
                 getUser·p0.9999: 13.103 ms/op
                 getUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384051
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 189932 
    [ 2.500,  3.750) = 190380 
    [ 3.750,  5.000) = 2886 
    [ 5.000,  6.250) = 406 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 136 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      6.454 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     15.453 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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
# Warmup Iteration   1: 4.984 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.009 ms/op
Iteration   1: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 11.451 ms/op
                 listUser·p1.00:   12.386 ms/op

Iteration   2: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.929 ms/op
                 listUser·p0.9999: 11.327 ms/op
                 listUser·p1.00:   11.502 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 11.433 ms/op
                 listUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317681
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 91018 
    [ 2.500,  3.750) = 187143 
    [ 3.750,  5.000) = 32563 
    [ 5.000,  6.250) = 5571 
    [ 6.250,  7.500) = 594 
    [ 7.500,  8.750) = 169 
    [ 8.750, 10.000) = 245 
    [10.000, 11.250) = 197 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.688 ms/op
     p(99.9900) =     11.374 ms/op
     p(99.9990) =     11.779 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.360 ± 0.451  ops/ms
ClientPb.existUser                       thrpt       3  13.081 ± 1.637  ops/ms
ClientPb.getUser                         thrpt       3  12.598 ± 1.457  ops/ms
ClientPb.listUser                        thrpt       3  10.583 ± 0.862  ops/ms
ClientPb.createUser                       avgt       3   2.596 ± 0.626   ms/op
ClientPb.existUser                        avgt       3   2.511 ± 0.087   ms/op
ClientPb.getUser                          avgt       3   2.546 ± 0.410   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.108   ms/op
ClientPb.createUser                     sample  380077   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.671           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.962           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.271           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.713           ms/op
ClientPb.existUser                      sample  386630   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.737           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.087           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.418           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.451           ms/op
ClientPb.getUser                        sample  384051   2.498 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.653           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.454           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.484           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.565           ms/op
ClientPb.listUser                       sample  317681   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.919           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.688           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.374           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.386           ms/op
