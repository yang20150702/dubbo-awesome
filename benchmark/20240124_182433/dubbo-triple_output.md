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
# Warmup Iteration   1: 4.600 ops/ms
# Warmup Iteration   2: 11.889 ops/ms
# Warmup Iteration   3: 12.099 ops/ms
Iteration   1: 12.412 ops/ms
Iteration   2: 12.342 ops/ms
Iteration   3: 12.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.411 ±(99.9%) 1.237 ops/ms [Average]
  (min, avg, max) = (12.342, 12.411, 12.478), stdev = 0.068
  CI (99.9%): [11.174, 13.648] (assumes normal distribution)


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
# Warmup Iteration   1: 7.834 ops/ms
# Warmup Iteration   2: 12.835 ops/ms
# Warmup Iteration   3: 12.836 ops/ms
Iteration   1: 12.767 ops/ms
Iteration   2: 13.005 ops/ms
Iteration   3: 12.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.905 ±(99.9%) 2.254 ops/ms [Average]
  (min, avg, max) = (12.767, 12.905, 13.005), stdev = 0.124
  CI (99.9%): [10.651, 15.159] (assumes normal distribution)


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
# Warmup Iteration   1: 7.702 ops/ms
# Warmup Iteration   2: 12.432 ops/ms
# Warmup Iteration   3: 12.317 ops/ms
Iteration   1: 12.705 ops/ms
Iteration   2: 12.559 ops/ms
Iteration   3: 12.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.580 ±(99.9%) 2.118 ops/ms [Average]
  (min, avg, max) = (12.476, 12.580, 12.705), stdev = 0.116
  CI (99.9%): [10.462, 14.697] (assumes normal distribution)


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
# Warmup Iteration   1: 6.609 ops/ms
# Warmup Iteration   2: 10.266 ops/ms
# Warmup Iteration   3: 10.463 ops/ms
Iteration   1: 10.433 ops/ms
Iteration   2: 10.471 ops/ms
Iteration   3: 10.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.439 ±(99.9%) 0.534 ops/ms [Average]
  (min, avg, max) = (10.414, 10.439, 10.471), stdev = 0.029
  CI (99.9%): [9.905, 10.973] (assumes normal distribution)


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.524 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.522 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (2.509, 2.522, 2.535), stdev = 0.013
  CI (99.9%): [2.291, 2.754] (assumes normal distribution)


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
# Warmup Iteration   1: 3.846 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.486 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (2.467, 2.486, 2.498), stdev = 0.017
  CI (99.9%): [2.178, 2.795] (assumes normal distribution)


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.004 ms/op
Iteration   1: 2.553 ±(99.9%) 0.004 ms/op
Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
Iteration   3: 2.586 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.561 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (2.544, 2.561, 2.586), stdev = 0.022
  CI (99.9%): [2.161, 2.961] (assumes normal distribution)


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
Iteration   1: 3.044 ±(99.9%) 0.007 ms/op
Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
Iteration   3: 3.049 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.054 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (3.044, 3.054, 3.070), stdev = 0.013
  CI (99.9%): [2.808, 3.300] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.691 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.582 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  11.238 ms/op
                 createUser·p0.9999: 15.073 ms/op
                 createUser·p1.00:   15.499 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 12.983 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   3: 2.546 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.209 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  9.028 ms/op
                 createUser·p0.9999: 12.199 ms/op
                 createUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377020
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 180403 
    [ 2.500,  3.750) = 192600 
    [ 3.750,  5.000) = 3157 
    [ 5.000,  6.250) = 364 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 146 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     13.997 ms/op
     p(99.9990) =     15.325 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


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
# Warmup Iteration   1: 3.650 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  5.783 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  5.652 ms/op
                 existUser·p0.9999: 13.042 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.004 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  8.096 ms/op
                 existUser·p0.9999: 12.028 ms/op
                 existUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389318
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 190163 
    [ 2.500,  3.750) = 196082 
    [ 3.750,  5.000) = 2284 
    [ 5.000,  6.250) = 351 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     13.076 ms/op
     p(99.9990) =     13.526 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.006 ms/op
Iteration   1: 2.573 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.981 ms/op
                 getUser·p0.999:  11.132 ms/op
                 getUser·p0.9999: 14.057 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 2.597 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.342 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  9.976 ms/op
                 getUser·p0.9999: 18.536 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  8.415 ms/op
                 getUser·p0.9999: 11.780 ms/op
                 getUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 372800
  mean =      2.573 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 178945 
    [ 2.500,  3.750) = 187297 
    [ 3.750,  5.000) = 5079 
    [ 5.000,  6.250) = 898 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      9.146 ms/op
     p(99.9900) =     14.139 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 4.778 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.009 ms/op
Iteration   1: 3.106 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.591 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.697 ms/op
                 listUser·p0.999:  10.372 ms/op
                 listUser·p0.9999: 13.402 ms/op
                 listUser·p1.00:   13.828 ms/op

Iteration   2: 3.102 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.008 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  9.960 ms/op
                 listUser·p0.9999: 12.422 ms/op
                 listUser·p1.00:   13.156 ms/op

Iteration   3: 3.095 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.684 ms/op
                 listUser·p0.9999: 10.917 ms/op
                 listUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309320
  mean =      3.101 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 76754 
    [ 2.500,  3.750) = 187433 
    [ 3.750,  5.000) = 36802 
    [ 5.000,  6.250) = 6751 
    [ 6.250,  7.500) = 795 
    [ 7.500,  8.750) = 160 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 190 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     12.765 ms/op
     p(99.9990) =     13.716 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.411 ± 1.237  ops/ms
ClientPb.existUser                       thrpt       3  12.905 ± 2.254  ops/ms
ClientPb.getUser                         thrpt       3  12.580 ± 2.118  ops/ms
ClientPb.listUser                        thrpt       3  10.439 ± 0.534  ops/ms
ClientPb.createUser                       avgt       3   2.522 ± 0.232   ms/op
ClientPb.existUser                        avgt       3   2.486 ± 0.308   ms/op
ClientPb.getUser                          avgt       3   2.561 ± 0.400   ms/op
ClientPb.listUser                         avgt       3   3.054 ± 0.246   ms/op
ClientPb.createUser                     sample  377020   2.544 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.805           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.044           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.997           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.499           ms/op
ClientPb.existUser                      sample  389318   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.910           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.652           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.076           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.025           ms/op
ClientPb.getUser                        sample  372800   2.573 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.913           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.601           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.146           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.139           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.628           ms/op
ClientPb.listUser                       sample  309320   3.101 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.591           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.043           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.945           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.765           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.828           ms/op
