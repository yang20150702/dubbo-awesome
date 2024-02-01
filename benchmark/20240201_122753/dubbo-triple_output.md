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
# Warmup Iteration   1: 5.195 ops/ms
# Warmup Iteration   2: 12.294 ops/ms
# Warmup Iteration   3: 12.566 ops/ms
Iteration   1: 12.772 ops/ms
Iteration   2: 12.897 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.829 ±(99.9%) 1.152 ops/ms [Average]
  (min, avg, max) = (12.772, 12.829, 12.897), stdev = 0.063
  CI (99.9%): [11.677, 13.981] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.503 ops/ms
# Warmup Iteration   2: 13.065 ops/ms
# Warmup Iteration   3: 13.224 ops/ms
Iteration   1: 13.176 ops/ms
Iteration   2: 13.202 ops/ms
Iteration   3: 13.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.159 ±(99.9%) 0.993 ops/ms [Average]
  (min, avg, max) = (13.098, 13.159, 13.202), stdev = 0.054
  CI (99.9%): [12.166, 14.151] (assumes normal distribution)


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
# Warmup Iteration   1: 7.780 ops/ms
# Warmup Iteration   2: 12.297 ops/ms
# Warmup Iteration   3: 12.809 ops/ms
Iteration   1: 12.775 ops/ms
Iteration   2: 12.844 ops/ms
Iteration   3: 12.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.810 ±(99.9%) 0.634 ops/ms [Average]
  (min, avg, max) = (12.775, 12.810, 12.844), stdev = 0.035
  CI (99.9%): [12.176, 13.444] (assumes normal distribution)


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
# Warmup Iteration   1: 6.944 ops/ms
# Warmup Iteration   2: 10.577 ops/ms
# Warmup Iteration   3: 10.746 ops/ms
Iteration   1: 10.797 ops/ms
Iteration   2: 10.684 ops/ms
Iteration   3: 10.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.739 ±(99.9%) 1.034 ops/ms [Average]
  (min, avg, max) = (10.684, 10.739, 10.797), stdev = 0.057
  CI (99.9%): [9.705, 11.773] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.520 ±(99.9%) 0.004 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.523 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (2.508, 2.523, 2.540), stdev = 0.016
  CI (99.9%): [2.223, 2.822] (assumes normal distribution)


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
# Warmup Iteration   1: 3.583 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.004 ms/op
Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
Iteration   3: 2.456 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.436, 2.448, 2.456), stdev = 0.010
  CI (99.9%): [2.262, 2.633] (assumes normal distribution)


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.003 ms/op
Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
Iteration   3: 2.478 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.070 ms/op [Average]
  (min, avg, max) = (2.474, 2.478, 2.482), stdev = 0.004
  CI (99.9%): [2.408, 2.548] (assumes normal distribution)


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
# Warmup Iteration   1: 4.549 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.004 ms/op
Iteration   1: 3.004 ±(99.9%) 0.007 ms/op
Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
Iteration   3: 3.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.009 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (2.996, 3.009, 3.027), stdev = 0.016
  CI (99.9%): [2.716, 3.302] (assumes normal distribution)


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.662 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.968 ms/op
                 createUser·p0.999:  11.518 ms/op
                 createUser·p0.9999: 13.051 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  7.647 ms/op
                 createUser·p0.9999: 12.208 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  8.442 ms/op
                 createUser·p0.9999: 10.322 ms/op
                 createUser·p1.00:   10.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383320
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 187011 
    [ 2.500,  3.750) = 191962 
    [ 3.750,  5.000) = 3221 
    [ 5.000,  6.250) = 551 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     12.621 ms/op
     p(99.9990) =     13.520 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


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
# Warmup Iteration   1: 3.700 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  5.431 ms/op
                 existUser·p0.9999: 13.285 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.520 ms/op
                 existUser·p0.999:  8.407 ms/op
                 existUser·p0.9999: 12.665 ms/op
                 existUser·p1.00:   13.058 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.619 ms/op
                 existUser·p0.999:  6.896 ms/op
                 existUser·p0.9999: 12.206 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390332
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 190663 
    [ 2.500,  3.750) = 197083 
    [ 3.750,  5.000) = 1928 
    [ 5.000,  6.250) = 205 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     12.796 ms/op
     p(99.9990) =     13.764 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.751 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  10.710 ms/op
                 getUser·p0.9999: 13.103 ms/op
                 getUser·p1.00:   13.435 ms/op

Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  9.160 ms/op
                 getUser·p0.9999: 14.238 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  6.331 ms/op
                 getUser·p0.9999: 11.372 ms/op
                 getUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383646
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 190345 
    [ 2.500,  3.750) = 188614 
    [ 3.750,  5.000) = 3667 
    [ 5.000,  6.250) = 532 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      7.912 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 4.691 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
Iteration   1: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.910 ms/op
                 listUser·p0.9999: 11.352 ms/op
                 listUser·p1.00:   11.731 ms/op

Iteration   2: 2.947 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.276 ms/op
                 listUser·p0.999:  9.429 ms/op
                 listUser·p0.9999: 10.710 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   3: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.845 ms/op
                 listUser·p0.9999: 11.442 ms/op
                 listUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323665
  mean =      2.963 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 99925 
    [ 2.500,  3.750) = 187585 
    [ 3.750,  5.000) = 30206 
    [ 5.000,  6.250) = 4694 
    [ 6.250,  7.500) = 430 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 286 
    [10.000, 11.250) = 151 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =      9.295 ms/op
     p(99.9900) =     11.309 ms/op
     p(99.9990) =     12.862 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.829 ± 1.152  ops/ms
ClientPb.existUser                       thrpt       3  13.159 ± 0.993  ops/ms
ClientPb.getUser                         thrpt       3  12.810 ± 0.634  ops/ms
ClientPb.listUser                        thrpt       3  10.739 ± 1.034  ops/ms
ClientPb.createUser                       avgt       3   2.523 ± 0.299   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.185   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.070   ms/op
ClientPb.listUser                         avgt       3   3.009 ± 0.293   ms/op
ClientPb.createUser                     sample  383320   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.933           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.224           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.621           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.730           ms/op
ClientPb.existUser                      sample  390332   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.841           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.389           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.796           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.090           ms/op
ClientPb.getUser                        sample  383646   2.500 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.629           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.912           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.189           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.402           ms/op
ClientPb.listUser                       sample  323665   2.963 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.818           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.415           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.295           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.309           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.976           ms/op
