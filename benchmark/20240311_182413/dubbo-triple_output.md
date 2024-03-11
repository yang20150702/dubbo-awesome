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
# Warmup Iteration   1: 4.684 ops/ms
# Warmup Iteration   2: 11.901 ops/ms
# Warmup Iteration   3: 12.358 ops/ms
Iteration   1: 12.557 ops/ms
Iteration   2: 12.610 ops/ms
Iteration   3: 12.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.624 ±(99.9%) 1.386 ops/ms [Average]
  (min, avg, max) = (12.557, 12.624, 12.707), stdev = 0.076
  CI (99.9%): [11.239, 14.010] (assumes normal distribution)


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
# Warmup Iteration   1: 8.176 ops/ms
# Warmup Iteration   2: 13.108 ops/ms
# Warmup Iteration   3: 13.201 ops/ms
Iteration   1: 13.167 ops/ms
Iteration   2: 13.136 ops/ms
Iteration   3: 13.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.133 ±(99.9%) 0.638 ops/ms [Average]
  (min, avg, max) = (13.097, 13.133, 13.167), stdev = 0.035
  CI (99.9%): [12.495, 13.771] (assumes normal distribution)


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
# Warmup Iteration   1: 7.308 ops/ms
# Warmup Iteration   2: 12.367 ops/ms
# Warmup Iteration   3: 12.710 ops/ms
Iteration   1: 12.865 ops/ms
Iteration   2: 12.712 ops/ms
Iteration   3: 12.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.811 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (12.712, 12.811, 12.865), stdev = 0.086
  CI (99.9%): [11.251, 14.371] (assumes normal distribution)


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
# Warmup Iteration   1: 6.611 ops/ms
# Warmup Iteration   2: 10.405 ops/ms
# Warmup Iteration   3: 10.555 ops/ms
Iteration   1: 10.488 ops/ms
Iteration   2: 10.464 ops/ms
Iteration   3: 10.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.507 ±(99.9%) 0.998 ops/ms [Average]
  (min, avg, max) = (10.464, 10.507, 10.568), stdev = 0.055
  CI (99.9%): [9.508, 11.505] (assumes normal distribution)


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.004 ms/op
Iteration   1: 2.565 ±(99.9%) 0.004 ms/op
Iteration   2: 2.531 ±(99.9%) 0.003 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (2.523, 2.540, 2.565), stdev = 0.022
  CI (99.9%): [2.135, 2.945] (assumes normal distribution)


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.004 ms/op
Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.445 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (2.440, 2.445, 2.452), stdev = 0.006
  CI (99.9%): [2.336, 2.554] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.305 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
Iteration   3: 2.502 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (2.490, 2.495, 2.502), stdev = 0.006
  CI (99.9%): [2.379, 2.610] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.761 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
Iteration   1: 3.057 ±(99.9%) 0.007 ms/op
Iteration   2: 3.063 ±(99.9%) 0.005 ms/op
Iteration   3: 3.068 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.063 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (3.057, 3.063, 3.068), stdev = 0.006
  CI (99.9%): [2.960, 3.166] (assumes normal distribution)


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
# Warmup Iteration   1: 4.257 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  11.633 ms/op
                 createUser·p0.9999: 14.032 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.514 ms/op
                 createUser·p0.999:  6.433 ms/op
                 createUser·p0.9999: 12.349 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  9.145 ms/op
                 createUser·p0.9999: 11.880 ms/op
                 createUser·p1.00:   15.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383519
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 183788 
    [ 2.500,  3.750) = 195994 
    [ 3.750,  5.000) = 2915 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     13.526 ms/op
     p(99.9990) =     14.229 ms/op
     p(99.9999) =     15.843 ms/op
    p(100.0000) =     15.843 ms/op


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
# Warmup Iteration   1: 3.691 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  6.060 ms/op
                 existUser·p0.9999: 13.976 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  6.388 ms/op
                 existUser·p0.9999: 13.271 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   3: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  5.643 ms/op
                 existUser·p0.9999: 12.088 ms/op
                 existUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396330
  mean =      2.420 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 203434 
    [ 2.500,  3.750) = 189051 
    [ 3.750,  5.000) = 3064 
    [ 5.000,  6.250) = 322 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      6.010 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.206 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  11.626 ms/op
                 getUser·p0.9999: 13.357 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.342 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  9.987 ms/op
                 getUser·p0.9999: 12.769 ms/op
                 getUser·p1.00:   13.337 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  8.470 ms/op
                 getUser·p0.9999: 11.038 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379191
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 185033 
    [ 2.500,  3.750) = 188231 
    [ 3.750,  5.000) = 5132 
    [ 5.000,  6.250) = 334 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.985 ms/op
     p(99.9000) =      9.074 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     13.753 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 4.952 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.009 ms/op
Iteration   1: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  8.857 ms/op
                 listUser·p0.9999: 10.571 ms/op
                 listUser·p1.00:   11.158 ms/op

Iteration   2: 3.075 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 12.930 ms/op
                 listUser·p1.00:   14.254 ms/op

Iteration   3: 3.105 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.978 ms/op
                 listUser·p0.9999: 11.448 ms/op
                 listUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311406
  mean =      3.080 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 78739 
    [ 2.500,  3.750) = 187546 
    [ 3.750,  5.000) = 37286 
    [ 5.000,  6.250) = 6349 
    [ 6.250,  7.500) = 698 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     12.368 ms/op
     p(99.9990) =     13.574 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.624 ± 1.386  ops/ms
ClientPb.existUser                       thrpt       3  13.133 ± 0.638  ops/ms
ClientPb.getUser                         thrpt       3  12.811 ± 1.560  ops/ms
ClientPb.listUser                        thrpt       3  10.507 ± 0.998  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.405   ms/op
ClientPb.existUser                        avgt       3   2.445 ± 0.109   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.116   ms/op
ClientPb.listUser                         avgt       3   3.063 ± 0.103   ms/op
ClientPb.createUser                     sample  383519   2.501 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.783           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.191           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.526           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.843           ms/op
ClientPb.existUser                      sample  396330   2.420 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.818           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.458           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.010           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.337           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  379191   2.529 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.864           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.074           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.058           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.057           ms/op
ClientPb.listUser                       sample  311406   3.080 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.786           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.368           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.254           ms/op
