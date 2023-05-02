# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.506 ops/ms
# Warmup Iteration   2: 6.652 ops/ms
# Warmup Iteration   3: 8.996 ops/ms
Iteration   1: 9.895 ops/ms
Iteration   2: 9.697 ops/ms
Iteration   3: 9.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.722 ±(99.9%) 2.957 ops/ms [Average]
  (min, avg, max) = (9.574, 9.722, 9.895), stdev = 0.162
  CI (99.9%): [6.764, 12.679] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ops/ms
# Warmup Iteration   2: 9.407 ops/ms
# Warmup Iteration   3: 10.133 ops/ms
Iteration   1: 9.991 ops/ms
Iteration   2: 10.456 ops/ms
Iteration   3: 10.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.295 ±(99.9%) 4.815 ops/ms [Average]
  (min, avg, max) = (9.991, 10.295, 10.456), stdev = 0.264
  CI (99.9%): [5.480, 15.111] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.469 ops/ms
# Warmup Iteration   2: 8.589 ops/ms
# Warmup Iteration   3: 9.341 ops/ms
Iteration   1: 10.408 ops/ms
Iteration   2: 10.402 ops/ms
Iteration   3: 10.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.323 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (10.160, 10.323, 10.408), stdev = 0.142
  CI (99.9%): [7.741, 12.905] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.399 ops/ms
# Warmup Iteration   2: 7.909 ops/ms
# Warmup Iteration   3: 8.203 ops/ms
Iteration   1: 8.780 ops/ms
Iteration   2: 8.678 ops/ms
Iteration   3: 8.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.598 ±(99.9%) 4.240 ops/ms [Average]
  (min, avg, max) = (8.336, 8.598, 8.780), stdev = 0.232
  CI (99.9%): [4.358, 12.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.651 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.005 ms/op
Iteration   1: 3.260 ±(99.9%) 0.004 ms/op
Iteration   2: 3.172 ±(99.9%) 0.009 ms/op
Iteration   3: 3.092 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.174 ±(99.9%) 1.537 ms/op [Average]
  (min, avg, max) = (3.092, 3.174, 3.260), stdev = 0.084
  CI (99.9%): [1.637, 4.712] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.932 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.002 ms/op
Iteration   1: 3.160 ±(99.9%) 0.007 ms/op
Iteration   2: 3.215 ±(99.9%) 0.005 ms/op
Iteration   3: 3.132 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.169 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (3.132, 3.169, 3.215), stdev = 0.042
  CI (99.9%): [2.404, 3.934] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.316 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.005 ms/op
Iteration   1: 3.308 ±(99.9%) 0.008 ms/op
Iteration   2: 3.220 ±(99.9%) 0.004 ms/op
Iteration   3: 3.147 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.225 ±(99.9%) 1.469 ms/op [Average]
  (min, avg, max) = (3.147, 3.225, 3.308), stdev = 0.080
  CI (99.9%): [1.757, 4.694] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.484 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.008 ms/op
Iteration   1: 3.904 ±(99.9%) 0.006 ms/op
Iteration   2: 3.667 ±(99.9%) 0.010 ms/op
Iteration   3: 3.791 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.787 ±(99.9%) 2.163 ms/op [Average]
  (min, avg, max) = (3.667, 3.787, 3.904), stdev = 0.119
  CI (99.9%): [1.624, 5.950] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.932 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
Iteration   1: 3.162 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.322 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   6.174 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 27.620 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.159 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  12.509 ms/op
                 createUser·p0.9999: 22.370 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 3.314 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  13.135 ms/op
                 createUser·p0.9999: 19.446 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295406
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22510 
    [ 2.500,  5.000) = 265261 
    [ 5.000,  7.500) = 6724 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     16.649 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.921 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.835 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.191 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 27.424 ms/op
                 existUser·p1.00:   28.312 ms/op

Iteration   2: 3.138 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  13.751 ms/op
                 existUser·p0.9999: 22.074 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.091 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  14.642 ms/op
                 existUser·p0.9999: 21.878 ms/op
                 existUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305372
  mean =      3.140 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19685 
    [ 2.500,  5.000) = 278828 
    [ 5.000,  7.500) = 6029 
    [ 7.500, 10.000) = 436 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     14.255 ms/op
     p(99.9900) =     26.197 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.897 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.010 ms/op
Iteration   1: 3.231 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  17.170 ms/op
                 getUser·p0.9999: 25.333 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  9.814 ms/op
                 getUser·p0.9999: 23.460 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   3: 3.176 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.585 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  15.401 ms/op
                 getUser·p0.9999: 22.379 ms/op
                 getUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300183
  mean =      3.195 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13871 
    [ 2.500,  5.000) = 278174 
    [ 5.000,  7.500) = 6968 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     15.345 ms/op
     p(99.9900) =     24.477 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.630 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.555 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.012 ms/op
Iteration   1: 3.868 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 20.644 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   2: 3.906 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   3: 3.929 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  14.421 ms/op
                 listUser·p0.9999: 16.774 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246057
  mean =      3.901 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 234692 
    [ 5.000,  7.500) = 8827 
    [ 7.500, 10.000) = 1850 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     14.892 ms/op
     p(99.9900) =     22.492 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.722 ± 2.957  ops/ms
ClientPb.existUser                       thrpt       3  10.295 ± 4.815  ops/ms
ClientPb.getUser                         thrpt       3  10.323 ± 2.582  ops/ms
ClientPb.listUser                        thrpt       3   8.598 ± 4.240  ops/ms
ClientPb.createUser                       avgt       3   3.174 ± 1.537   ms/op
ClientPb.existUser                        avgt       3   3.169 ± 0.765   ms/op
ClientPb.getUser                          avgt       3   3.225 ± 1.469   ms/op
ClientPb.listUser                         avgt       3   3.787 ± 2.163   ms/op
ClientPb.createUser                     sample  295406   3.248 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.149           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.649           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.345           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.115           ms/op
ClientPb.existUser                      sample  305372   3.140 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.506           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.255           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.197           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.312           ms/op
ClientPb.getUser                        sample  300183   3.195 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.888           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.345           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.477           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.821           ms/op
ClientPb.listUser                       sample  246057   3.901 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.288           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.512           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.892           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.492           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.986           ms/op
