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
# Warmup Iteration   1: 4.858 ops/ms
# Warmup Iteration   2: 12.127 ops/ms
# Warmup Iteration   3: 12.671 ops/ms
Iteration   1: 12.750 ops/ms
Iteration   2: 12.742 ops/ms
Iteration   3: 12.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.775 ±(99.9%) 0.906 ops/ms [Average]
  (min, avg, max) = (12.742, 12.775, 12.832), stdev = 0.050
  CI (99.9%): [11.869, 13.681] (assumes normal distribution)


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
# Warmup Iteration   1: 7.843 ops/ms
# Warmup Iteration   2: 13.176 ops/ms
# Warmup Iteration   3: 13.270 ops/ms
Iteration   1: 13.136 ops/ms
Iteration   2: 13.228 ops/ms
Iteration   3: 13.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.150 ±(99.9%) 1.311 ops/ms [Average]
  (min, avg, max) = (13.086, 13.150, 13.228), stdev = 0.072
  CI (99.9%): [11.839, 14.461] (assumes normal distribution)


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
# Warmup Iteration   1: 7.930 ops/ms
# Warmup Iteration   2: 12.632 ops/ms
# Warmup Iteration   3: 12.791 ops/ms
Iteration   1: 12.896 ops/ms
Iteration   2: 12.736 ops/ms
Iteration   3: 12.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.833 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (12.736, 12.833, 12.896), stdev = 0.086
  CI (99.9%): [11.273, 14.393] (assumes normal distribution)


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
# Warmup Iteration   1: 6.702 ops/ms
# Warmup Iteration   2: 10.507 ops/ms
# Warmup Iteration   3: 10.595 ops/ms
Iteration   1: 10.731 ops/ms
Iteration   2: 10.762 ops/ms
Iteration   3: 10.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.741 ±(99.9%) 0.334 ops/ms [Average]
  (min, avg, max) = (10.729, 10.741, 10.762), stdev = 0.018
  CI (99.9%): [10.407, 11.075] (assumes normal distribution)


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.003 ms/op
Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
Iteration   3: 2.567 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.527, 2.541, 2.567), stdev = 0.022
  CI (99.9%): [2.138, 2.945] (assumes normal distribution)


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
# Warmup Iteration   1: 3.629 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.003 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.422 ±(99.9%) 0.003 ms/op
Iteration   3: 2.417 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.428 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.417, 2.428, 2.445), stdev = 0.015
  CI (99.9%): [2.158, 2.698] (assumes normal distribution)


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.455 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.458 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (2.448, 2.458, 2.470), stdev = 0.011
  CI (99.9%): [2.249, 2.666] (assumes normal distribution)


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
Iteration   2: 3.040 ±(99.9%) 0.005 ms/op
Iteration   3: 3.044 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.039 ±(99.9%) 0.089 ms/op [Average]
  (min, avg, max) = (3.034, 3.039, 3.044), stdev = 0.005
  CI (99.9%): [2.950, 3.128] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.676 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  10.813 ms/op
                 createUser·p0.9999: 13.863 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  9.767 ms/op
                 createUser·p0.9999: 11.538 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  9.833 ms/op
                 createUser·p0.9999: 12.216 ms/op
                 createUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380966
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 183668 
    [ 2.500,  3.750) = 193245 
    [ 3.750,  5.000) = 2976 
    [ 5.000,  6.250) = 505 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      9.815 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     14.174 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  5.480 ms/op
                 existUser·p0.9999: 13.025 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  6.914 ms/op
                 existUser·p0.9999: 12.010 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  8.546 ms/op
                 existUser·p0.9999: 11.814 ms/op
                 existUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390011
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 192643 
    [ 2.500,  3.750) = 193998 
    [ 3.750,  5.000) = 2607 
    [ 5.000,  6.250) = 318 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      6.864 ms/op
     p(99.9900) =     12.304 ms/op
     p(99.9990) =     13.373 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  5.772 ms/op
                 getUser·p0.9999: 13.905 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   2: 2.557 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  9.322 ms/op
                 getUser·p0.9999: 12.951 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  8.454 ms/op
                 getUser·p0.9999: 11.531 ms/op
                 getUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377456
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 183751 
    [ 2.500,  3.750) = 188006 
    [ 3.750,  5.000) = 4503 
    [ 5.000,  6.250) = 668 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      7.750 ms/op
     p(99.9900) =     13.263 ms/op
     p(99.9990) =     14.114 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.851 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
Iteration   1: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 10.391 ms/op
                 listUser·p1.00:   11.076 ms/op

Iteration   2: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.378 ms/op
                 listUser·p0.9999: 12.713 ms/op
                 listUser·p1.00:   13.418 ms/op

Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.187 ms/op
                 listUser·p0.9999: 10.589 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322459
  mean =      2.974 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 96544 
    [ 2.500,  3.750) = 189442 
    [ 3.750,  5.000) = 29904 
    [ 5.000,  6.250) = 5118 
    [ 6.250,  7.500) = 601 
    [ 7.500,  8.750) = 301 
    [ 8.750, 10.000) = 303 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     11.903 ms/op
     p(99.9990) =     13.149 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.775 ± 0.906  ops/ms
ClientPb.existUser                       thrpt       3  13.150 ± 1.311  ops/ms
ClientPb.getUser                         thrpt       3  12.833 ± 1.560  ops/ms
ClientPb.listUser                        thrpt       3  10.741 ± 0.334  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.404   ms/op
ClientPb.existUser                        avgt       3   2.428 ± 0.270   ms/op
ClientPb.getUser                          avgt       3   2.458 ± 0.208   ms/op
ClientPb.listUser                         avgt       3   3.039 ± 0.089   ms/op
ClientPb.createUser                     sample  380966   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.974           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.124           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.336           ms/op
ClientPb.existUser                      sample  390011   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.879           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.864           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.304           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.090           ms/op
ClientPb.getUser                        sample  377456   2.541 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.852           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.750           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.263           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.893           ms/op
ClientPb.listUser                       sample  322459   2.974 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.011           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.903           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.418           ms/op
