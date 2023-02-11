# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.707 ops/ms
# Warmup Iteration   2: 6.410 ops/ms
# Warmup Iteration   3: 9.380 ops/ms
Iteration   1: 9.569 ops/ms
Iteration   2: 10.164 ops/ms
Iteration   3: 10.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.950 ±(99.9%) 6.039 ops/ms [Average]
  (min, avg, max) = (9.569, 9.950, 10.164), stdev = 0.331
  CI (99.9%): [3.911, 15.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.505 ops/ms
# Warmup Iteration   2: 9.455 ops/ms
# Warmup Iteration   3: 10.281 ops/ms
Iteration   1: 10.133 ops/ms
Iteration   2: 10.197 ops/ms
Iteration   3: 10.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.216 ±(99.9%) 1.706 ops/ms [Average]
  (min, avg, max) = (10.133, 10.216, 10.318), stdev = 0.094
  CI (99.9%): [8.510, 11.922] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.314 ops/ms
# Warmup Iteration   2: 9.077 ops/ms
# Warmup Iteration   3: 10.118 ops/ms
Iteration   1: 9.908 ops/ms
Iteration   2: 9.823 ops/ms
Iteration   3: 9.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.779 ±(99.9%) 2.845 ops/ms [Average]
  (min, avg, max) = (9.606, 9.779, 9.908), stdev = 0.156
  CI (99.9%): [6.935, 12.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.255 ops/ms
# Warmup Iteration   2: 7.689 ops/ms
# Warmup Iteration   3: 8.406 ops/ms
Iteration   1: 8.575 ops/ms
Iteration   2: 8.708 ops/ms
Iteration   3: 8.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.729 ±(99.9%) 3.024 ops/ms [Average]
  (min, avg, max) = (8.575, 8.729, 8.904), stdev = 0.166
  CI (99.9%): [5.705, 11.753] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.693 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.007 ms/op
Iteration   1: 3.065 ±(99.9%) 0.007 ms/op
Iteration   2: 3.172 ±(99.9%) 0.005 ms/op
Iteration   3: 3.138 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.125 ±(99.9%) 0.999 ms/op [Average]
  (min, avg, max) = (3.065, 3.125, 3.172), stdev = 0.055
  CI (99.9%): [2.126, 4.124] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.798 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.460 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
Iteration   2: 3.061 ±(99.9%) 0.009 ms/op
Iteration   3: 3.029 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.035 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (3.016, 3.035, 3.061), stdev = 0.023
  CI (99.9%): [2.616, 3.455] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.611 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.408 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.004 ms/op
Iteration   1: 3.182 ±(99.9%) 0.004 ms/op
Iteration   2: 3.065 ±(99.9%) 0.004 ms/op
Iteration   3: 3.052 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.100 ±(99.9%) 1.310 ms/op [Average]
  (min, avg, max) = (3.052, 3.100, 3.182), stdev = 0.072
  CI (99.9%): [1.790, 4.410] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.293 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.005 ms/op
Iteration   1: 3.817 ±(99.9%) 0.006 ms/op
Iteration   2: 3.768 ±(99.9%) 0.006 ms/op
Iteration   3: 3.749 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.778 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (3.749, 3.778, 3.817), stdev = 0.035
  CI (99.9%): [3.142, 4.413] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.250 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.009 ms/op
Iteration   1: 3.148 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  15.352 ms/op
                 createUser·p0.9999: 21.261 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   2: 3.353 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.239 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  18.373 ms/op
                 createUser·p0.9999: 24.019 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   3: 3.260 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  17.727 ms/op
                 createUser·p0.9999: 35.062 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295401
  mean =      3.252 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12561 
    [ 2.500,  5.000) = 275407 
    [ 5.000,  7.500) = 6464 
    [ 7.500, 10.000) = 448 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     17.485 ms/op
     p(99.9900) =     25.148 ms/op
     p(99.9990) =     35.130 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.237 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 22.118 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   2: 3.017 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  12.927 ms/op
                 existUser·p0.9999: 18.986 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  8.239 ms/op
                 existUser·p0.9999: 21.098 ms/op
                 existUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313523
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14725 
    [ 2.500,  5.000) = 293941 
    [ 5.000,  7.500) = 4123 
    [ 7.500, 10.000) = 332 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     12.501 ms/op
     p(99.9900) =     21.189 ms/op
     p(99.9990) =     22.802 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.675 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.396 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.009 ms/op
Iteration   1: 3.223 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.485 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  17.383 ms/op
                 getUser·p0.9999: 19.898 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   2: 3.117 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  10.666 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.274 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  13.238 ms/op
                 getUser·p0.9999: 17.840 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303805
  mean =      3.159 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14271 
    [ 2.500,  5.000) = 281202 
    [ 5.000,  7.500) = 7498 
    [ 7.500, 10.000) = 375 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 186 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.274 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     15.407 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     20.638 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.177 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.010 ms/op
Iteration   1: 3.740 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.364 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 20.421 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 3.755 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  12.632 ms/op
                 listUser·p0.9999: 14.803 ms/op
                 listUser·p1.00:   15.958 ms/op

Iteration   3: 3.787 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  13.420 ms/op
                 listUser·p0.9999: 15.344 ms/op
                 listUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255183
  mean =      3.761 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 246972 
    [ 5.000,  7.500) = 5990 
    [ 7.500, 10.000) = 1475 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 301 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.161 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     18.953 ms/op
     p(99.9990) =     21.132 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.950 ± 6.039  ops/ms
ClientPb.existUser                       thrpt       3  10.216 ± 1.706  ops/ms
ClientPb.getUser                         thrpt       3   9.779 ± 2.845  ops/ms
ClientPb.listUser                        thrpt       3   8.729 ± 3.024  ops/ms
ClientPb.createUser                       avgt       3   3.125 ± 0.999   ms/op
ClientPb.existUser                        avgt       3   3.035 ± 0.419   ms/op
ClientPb.getUser                          avgt       3   3.100 ± 1.310   ms/op
ClientPb.listUser                         avgt       3   3.778 ± 0.635   ms/op
ClientPb.createUser                     sample  295401   3.252 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.969           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.485           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.148           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.193           ms/op
ClientPb.existUser                      sample  313523   3.059 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.133           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.501           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.189           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.265           ms/op
ClientPb.getUser                        sample  303805   3.159 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.274           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.531           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.210           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.407           ms/op
ClientPb.getUser:getUser·p0.9999        sample          19.431           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.709           ms/op
ClientPb.listUser                       sample  255183   3.761 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.364           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.161           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.730           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.953           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.217           ms/op
