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
# Warmup Iteration   1: 4.693 ops/ms
# Warmup Iteration   2: 12.129 ops/ms
# Warmup Iteration   3: 12.366 ops/ms
Iteration   1: 12.862 ops/ms
Iteration   2: 12.894 ops/ms
Iteration   3: 12.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.892 ±(99.9%) 0.553 ops/ms [Average]
  (min, avg, max) = (12.862, 12.892, 12.922), stdev = 0.030
  CI (99.9%): [12.340, 13.445] (assumes normal distribution)


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
# Warmup Iteration   1: 8.716 ops/ms
# Warmup Iteration   2: 13.177 ops/ms
# Warmup Iteration   3: 13.176 ops/ms
Iteration   1: 13.365 ops/ms
Iteration   2: 13.076 ops/ms
Iteration   3: 13.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.181 ±(99.9%) 2.913 ops/ms [Average]
  (min, avg, max) = (13.076, 13.181, 13.365), stdev = 0.160
  CI (99.9%): [10.268, 16.094] (assumes normal distribution)


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
# Warmup Iteration   1: 7.875 ops/ms
# Warmup Iteration   2: 12.591 ops/ms
# Warmup Iteration   3: 13.050 ops/ms
Iteration   1: 13.096 ops/ms
Iteration   2: 13.066 ops/ms
Iteration   3: 13.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.079 ±(99.9%) 0.276 ops/ms [Average]
  (min, avg, max) = (13.066, 13.079, 13.096), stdev = 0.015
  CI (99.9%): [12.803, 13.355] (assumes normal distribution)


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
# Warmup Iteration   1: 6.751 ops/ms
# Warmup Iteration   2: 10.848 ops/ms
# Warmup Iteration   3: 10.906 ops/ms
Iteration   1: 10.915 ops/ms
Iteration   2: 10.849 ops/ms
Iteration   3: 10.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.868 ±(99.9%) 0.741 ops/ms [Average]
  (min, avg, max) = (10.840, 10.868, 10.915), stdev = 0.041
  CI (99.9%): [10.127, 11.609] (assumes normal distribution)


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.003 ms/op
Iteration   1: 2.533 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
Iteration   3: 2.468 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.491 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (2.468, 2.491, 2.533), stdev = 0.037
  CI (99.9%): [1.824, 3.158] (assumes normal distribution)


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.401 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.410 ±(99.9%) 0.004 ms/op
Iteration   1: 2.409 ±(99.9%) 0.004 ms/op
Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
Iteration   3: 2.404 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.408 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.404, 2.408, 2.412), stdev = 0.004
  CI (99.9%): [2.334, 2.482] (assumes normal distribution)


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.003 ms/op
Iteration   3: 2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.479, 2.490, 2.502), stdev = 0.012
  CI (99.9%): [2.278, 2.703] (assumes normal distribution)


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
# Warmup Iteration   1: 4.664 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.005 ms/op
Iteration   1: 2.952 ±(99.9%) 0.005 ms/op
Iteration   2: 2.951 ±(99.9%) 0.005 ms/op
Iteration   3: 2.935 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.946 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.935, 2.946, 2.952), stdev = 0.009
  CI (99.9%): [2.780, 3.112] (assumes normal distribution)


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  9.759 ms/op
                 createUser·p0.9999: 13.831 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  6.452 ms/op
                 createUser·p0.9999: 11.993 ms/op
                 createUser·p1.00:   12.747 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  7.043 ms/op
                 createUser·p0.9999: 10.780 ms/op
                 createUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388540
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 190944 
    [ 2.500,  3.750) = 193745 
    [ 3.750,  5.000) = 3075 
    [ 5.000,  6.250) = 315 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      7.077 ms/op
     p(99.9900) =     13.257 ms/op
     p(99.9990) =     14.060 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.476 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.415 ±(99.9%) 0.005 ms/op
Iteration   1: 2.407 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   2.431 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  5.678 ms/op
                 existUser·p0.9999: 14.041 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.389 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  8.016 ms/op
                 existUser·p0.9999: 12.763 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  7.302 ms/op
                 existUser·p0.9999: 11.645 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399056
  mean =      2.403 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 204639 
    [ 2.500,  3.750) = 191136 
    [ 3.750,  5.000) = 2518 
    [ 5.000,  6.250) = 275 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      7.397 ms/op
     p(99.9900) =     13.355 ms/op
     p(99.9990) =     14.714 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.692 ms/op
                 getUser·p0.999:  7.567 ms/op
                 getUser·p0.9999: 13.655 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  7.252 ms/op
                 getUser·p0.9999: 12.156 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   2.429 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.039 ms/op
                 getUser·p0.99:   3.449 ms/op
                 getUser·p0.999:  8.816 ms/op
                 getUser·p0.9999: 11.233 ms/op
                 getUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 393772
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 198166 
    [ 2.500,  3.750) = 192399 
    [ 3.750,  5.000) = 2397 
    [ 5.000,  6.250) = 273 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      8.044 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     13.976 ms/op
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
# Warmup Iteration   1: 4.777 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.008 ms/op
Iteration   1: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.780 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.070 ms/op
                 listUser·p0.9999: 10.882 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   2: 2.945 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  9.166 ms/op
                 listUser·p0.9999: 10.970 ms/op
                 listUser·p1.00:   11.518 ms/op

Iteration   3: 2.967 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.690 ms/op
                 listUser·p0.9999: 11.616 ms/op
                 listUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324554
  mean =      2.955 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 101686 
    [ 2.500,  3.750) = 187420 
    [ 3.750,  5.000) = 29109 
    [ 5.000,  6.250) = 4933 
    [ 6.250,  7.500) = 586 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 250 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.403 ms/op
     p(99.9990) =     12.510 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.892 ± 0.553  ops/ms
ClientPb.existUser                       thrpt       3  13.181 ± 2.913  ops/ms
ClientPb.getUser                         thrpt       3  13.079 ± 0.276  ops/ms
ClientPb.listUser                        thrpt       3  10.868 ± 0.741  ops/ms
ClientPb.createUser                       avgt       3   2.491 ± 0.667   ms/op
ClientPb.existUser                        avgt       3   2.408 ± 0.074   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.213   ms/op
ClientPb.listUser                         avgt       3   2.946 ± 0.166   ms/op
ClientPb.createUser                     sample  388540   2.469 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.741           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.531           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.077           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.257           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.598           ms/op
ClientPb.existUser                      sample  399056   2.403 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.794           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.458           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.397           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.355           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.008           ms/op
ClientPb.getUser                        sample  393772   2.436 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.863           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.044           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.960           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  324554   2.955 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.768           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.403           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.648           ms/op
