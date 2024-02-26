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
# Warmup Iteration   1: 4.397 ops/ms
# Warmup Iteration   2: 11.921 ops/ms
# Warmup Iteration   3: 12.327 ops/ms
Iteration   1: 12.501 ops/ms
Iteration   2: 12.395 ops/ms
Iteration   3: 12.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.513 ±(99.9%) 2.281 ops/ms [Average]
  (min, avg, max) = (12.395, 12.513, 12.644), stdev = 0.125
  CI (99.9%): [10.232, 14.794] (assumes normal distribution)


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
# Warmup Iteration   1: 7.758 ops/ms
# Warmup Iteration   2: 13.240 ops/ms
# Warmup Iteration   3: 13.258 ops/ms
Iteration   1: 13.121 ops/ms
Iteration   2: 13.300 ops/ms
Iteration   3: 13.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.225 ±(99.9%) 1.699 ops/ms [Average]
  (min, avg, max) = (13.121, 13.225, 13.300), stdev = 0.093
  CI (99.9%): [11.526, 14.924] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.684 ops/ms
# Warmup Iteration   2: 12.494 ops/ms
# Warmup Iteration   3: 12.674 ops/ms
Iteration   1: 12.552 ops/ms
Iteration   2: 12.768 ops/ms
Iteration   3: 12.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.653 ±(99.9%) 1.980 ops/ms [Average]
  (min, avg, max) = (12.552, 12.653, 12.768), stdev = 0.109
  CI (99.9%): [10.674, 14.633] (assumes normal distribution)


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
# Warmup Iteration   1: 6.661 ops/ms
# Warmup Iteration   2: 10.595 ops/ms
# Warmup Iteration   3: 10.770 ops/ms
Iteration   1: 10.832 ops/ms
Iteration   2: 10.735 ops/ms
Iteration   3: 10.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.808 ±(99.9%) 1.167 ops/ms [Average]
  (min, avg, max) = (10.735, 10.808, 10.856), stdev = 0.064
  CI (99.9%): [9.640, 11.975] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.851 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.512 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.504 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (2.497, 2.504, 2.512), stdev = 0.007
  CI (99.9%): [2.370, 2.638] (assumes normal distribution)


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.411 ±(99.9%) 0.004 ms/op
Iteration   1: 2.436 ±(99.9%) 0.004 ms/op
Iteration   2: 2.419 ±(99.9%) 0.003 ms/op
Iteration   3: 2.442 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.419, 2.432, 2.442), stdev = 0.012
  CI (99.9%): [2.212, 2.653] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.003 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.482 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (2.468, 2.482, 2.502), stdev = 0.018
  CI (99.9%): [2.153, 2.811] (assumes normal distribution)


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
# Warmup Iteration   1: 4.651 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 2.990 ±(99.9%) 0.005 ms/op
Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
Iteration   3: 3.014 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.995 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (2.982, 2.995, 3.014), stdev = 0.017
  CI (99.9%): [2.690, 3.301] (assumes normal distribution)


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
# Warmup Iteration   1: 4.276 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.714 ms/op
                 createUser·p0.999:  9.162 ms/op
                 createUser·p0.9999: 13.246 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.644 ms/op
                 createUser·p0.999:  8.273 ms/op
                 createUser·p0.9999: 12.456 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  8.071 ms/op
                 createUser·p0.9999: 9.994 ms/op
                 createUser·p1.00:   10.240 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385331
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 187288 
    [ 2.500,  3.750) = 194223 
    [ 3.750,  5.000) = 2843 
    [ 5.000,  6.250) = 420 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      8.066 ms/op
     p(99.9900) =     12.664 ms/op
     p(99.9990) =     13.742 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.697 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.436 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.281 ms/op
                 existUser·p0.999:  5.323 ms/op
                 existUser·p0.9999: 14.021 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  7.918 ms/op
                 existUser·p0.9999: 12.404 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  6.858 ms/op
                 existUser·p0.9999: 12.039 ms/op
                 existUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395230
  mean =      2.427 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 199518 
    [ 2.500,  3.750) = 192968 
    [ 3.750,  5.000) = 2044 
    [ 5.000,  6.250) = 233 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.523 ms/op
     p(99.9000) =      6.610 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.241 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 3.813 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  7.618 ms/op
                 getUser·p0.9999: 13.532 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  7.004 ms/op
                 getUser·p0.9999: 13.242 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.005 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  6.782 ms/op
                 getUser·p0.9999: 13.006 ms/op
                 getUser·p1.00:   14.139 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390148
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 196400 
    [ 2.500,  3.750) = 188973 
    [ 3.750,  5.000) = 3733 
    [ 5.000,  6.250) = 570 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      6.716 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 4.993 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.008 ms/op
Iteration   1: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.806 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 11.326 ms/op
                 listUser·p1.00:   11.469 ms/op

Iteration   2: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  10.387 ms/op
                 listUser·p0.9999: 13.158 ms/op
                 listUser·p1.00:   14.844 ms/op

Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.729 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  10.011 ms/op
                 listUser·p0.9999: 11.983 ms/op
                 listUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317368
  mean =      3.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 91519 
    [ 2.500,  3.750) = 185237 
    [ 3.750,  5.000) = 32705 
    [ 5.000,  6.250) = 6506 
    [ 6.250,  7.500) = 588 
    [ 7.500,  8.750) = 97 
    [ 8.750, 10.000) = 271 
    [10.000, 11.250) = 205 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.994 ms/op
     p(99.9900) =     12.219 ms/op
     p(99.9990) =     14.187 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.513 ± 2.281  ops/ms
ClientPb.existUser                       thrpt       3  13.225 ± 1.699  ops/ms
ClientPb.getUser                         thrpt       3  12.653 ± 1.980  ops/ms
ClientPb.listUser                        thrpt       3  10.808 ± 1.167  ops/ms
ClientPb.createUser                       avgt       3   2.504 ± 0.134   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.220   ms/op
ClientPb.getUser                          avgt       3   2.482 ± 0.329   ms/op
ClientPb.listUser                         avgt       3   2.995 ± 0.306   ms/op
ClientPb.createUser                     sample  385331   2.489 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.853           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.066           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.664           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  395230   2.427 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.765           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.610           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.582           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.467           ms/op
ClientPb.getUser                        sample  390148   2.458 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.777           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.716           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.435           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.352           ms/op
ClientPb.listUser                       sample  317368   3.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.729           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.994           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.219           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.844           ms/op
