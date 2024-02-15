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
# Warmup Iteration   1: 4.998 ops/ms
# Warmup Iteration   2: 12.220 ops/ms
# Warmup Iteration   3: 12.429 ops/ms
Iteration   1: 12.749 ops/ms
Iteration   2: 12.899 ops/ms
Iteration   3: 12.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.838 ±(99.9%) 1.440 ops/ms [Average]
  (min, avg, max) = (12.749, 12.838, 12.899), stdev = 0.079
  CI (99.9%): [11.398, 14.278] (assumes normal distribution)


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
# Warmup Iteration   1: 7.935 ops/ms
# Warmup Iteration   2: 12.751 ops/ms
# Warmup Iteration   3: 12.820 ops/ms
Iteration   1: 12.857 ops/ms
Iteration   2: 12.944 ops/ms
Iteration   3: 12.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.892 ±(99.9%) 0.830 ops/ms [Average]
  (min, avg, max) = (12.857, 12.892, 12.944), stdev = 0.046
  CI (99.9%): [12.062, 13.723] (assumes normal distribution)


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
# Warmup Iteration   1: 8.136 ops/ms
# Warmup Iteration   2: 12.602 ops/ms
# Warmup Iteration   3: 12.737 ops/ms
Iteration   1: 12.802 ops/ms
Iteration   2: 12.861 ops/ms
Iteration   3: 12.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.830 ±(99.9%) 0.549 ops/ms [Average]
  (min, avg, max) = (12.802, 12.830, 12.861), stdev = 0.030
  CI (99.9%): [12.281, 13.378] (assumes normal distribution)


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
# Warmup Iteration   1: 6.791 ops/ms
# Warmup Iteration   2: 10.546 ops/ms
# Warmup Iteration   3: 10.660 ops/ms
Iteration   1: 10.779 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.751 ±(99.9%) 0.958 ops/ms [Average]
  (min, avg, max) = (10.691, 10.751, 10.784), stdev = 0.052
  CI (99.9%): [9.794, 11.709] (assumes normal distribution)


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.565 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.545 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.532, 2.545, 2.565), stdev = 0.017
  CI (99.9%): [2.226, 2.864] (assumes normal distribution)


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.003 ms/op
Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.446 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (2.433, 2.446, 2.453), stdev = 0.011
  CI (99.9%): [2.245, 2.647] (assumes normal distribution)


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.003 ms/op
Iteration   1: 2.470 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.003 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (2.470, 2.478, 2.486), stdev = 0.008
  CI (99.9%): [2.332, 2.624] (assumes normal distribution)


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
# Warmup Iteration   1: 4.736 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.004 ms/op
Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
Iteration   3: 2.966 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.029 ms/op [Average]
  (min, avg, max) = (2.963, 2.964, 2.966), stdev = 0.002
  CI (99.9%): [2.935, 2.993] (assumes normal distribution)


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
# Warmup Iteration   1: 4.257 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  10.974 ms/op
                 createUser·p0.9999: 14.147 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  10.224 ms/op
                 createUser·p0.9999: 12.536 ms/op
                 createUser·p1.00:   12.747 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   4.036 ms/op
                 createUser·p0.999:  8.307 ms/op
                 createUser·p0.9999: 10.074 ms/op
                 createUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384179
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 185202 
    [ 2.500,  3.750) = 194812 
    [ 3.750,  5.000) = 3173 
    [ 5.000,  6.250) = 404 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.727 ms/op
     p(99.9900) =     12.747 ms/op
     p(99.9990) =     15.455 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.012 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  5.674 ms/op
                 existUser·p0.9999: 13.910 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  6.252 ms/op
                 existUser·p0.9999: 13.517 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  7.790 ms/op
                 existUser·p0.9999: 11.469 ms/op
                 existUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391592
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 193980 
    [ 2.500,  3.750) = 194837 
    [ 3.750,  5.000) = 2069 
    [ 5.000,  6.250) = 239 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 134 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =      7.332 ms/op
     p(99.9900) =     13.645 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  10.554 ms/op
                 getUser·p0.9999: 13.500 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.356 ms/op
                 getUser·p0.999:  10.327 ms/op
                 getUser·p0.9999: 20.236 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  7.353 ms/op
                 getUser·p0.9999: 10.979 ms/op
                 getUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384100
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190768 
    [ 2.500,  5.000) = 192319 
    [ 5.000,  7.500) = 574 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      9.319 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     21.085 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 4.610 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 2.953 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  8.958 ms/op
                 listUser·p0.9999: 10.784 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   2: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  8.801 ms/op
                 listUser·p0.9999: 10.722 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 10.866 ms/op
                 listUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324263
  mean =      2.958 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 98836 
    [ 2.500,  3.750) = 189322 
    [ 3.750,  5.000) = 29718 
    [ 5.000,  6.250) = 5092 
    [ 6.250,  7.500) = 483 
    [ 7.500,  8.750) = 312 
    [ 8.750, 10.000) = 235 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.467 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     10.790 ms/op
     p(99.9990) =     11.903 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.838 ± 1.440  ops/ms
ClientPb.existUser                       thrpt       3  12.892 ± 0.830  ops/ms
ClientPb.getUser                         thrpt       3  12.830 ± 0.549  ops/ms
ClientPb.listUser                        thrpt       3  10.751 ± 0.958  ops/ms
ClientPb.createUser                       avgt       3   2.545 ± 0.319   ms/op
ClientPb.existUser                        avgt       3   2.446 ± 0.201   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.146   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.029   ms/op
ClientPb.createUser                     sample  384179   2.496 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.612           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.727           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.747           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.252           ms/op
ClientPb.existUser                      sample  391592   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.946           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.332           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.645           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.418           ms/op
ClientPb.getUser                        sample  384100   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.783           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.319           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.648           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.398           ms/op
ClientPb.listUser                       sample  324263   2.958 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.766           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.467           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.864           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.790           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.533           ms/op
