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
# Warmup Iteration   1: 2.487 ops/ms
# Warmup Iteration   2: 6.446 ops/ms
# Warmup Iteration   3: 9.330 ops/ms
Iteration   1: 9.342 ops/ms
Iteration   2: 9.839 ops/ms
Iteration   3: 10.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.785 ±(99.9%) 7.635 ops/ms [Average]
  (min, avg, max) = (9.342, 9.785, 10.174), stdev = 0.418
  CI (99.9%): [2.150, 17.419] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.353 ops/ms
# Warmup Iteration   2: 8.675 ops/ms
# Warmup Iteration   3: 10.235 ops/ms
Iteration   1: 10.505 ops/ms
Iteration   2: 10.015 ops/ms
Iteration   3: 10.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.277 ±(99.9%) 4.493 ops/ms [Average]
  (min, avg, max) = (10.015, 10.277, 10.505), stdev = 0.246
  CI (99.9%): [5.784, 14.770] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ops/ms
# Warmup Iteration   2: 8.644 ops/ms
# Warmup Iteration   3: 9.348 ops/ms
Iteration   1: 9.688 ops/ms
Iteration   2: 10.311 ops/ms
Iteration   3: 10.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.063 ±(99.9%) 6.017 ops/ms [Average]
  (min, avg, max) = (9.688, 10.063, 10.311), stdev = 0.330
  CI (99.9%): [4.046, 16.079] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.231 ops/ms
# Warmup Iteration   2: 8.141 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 8.655 ops/ms
Iteration   2: 8.527 ops/ms
Iteration   3: 8.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.550 ±(99.9%) 1.732 ops/ms [Average]
  (min, avg, max) = (8.470, 8.550, 8.655), stdev = 0.095
  CI (99.9%): [6.819, 10.282] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.685 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.006 ms/op
Iteration   1: 3.175 ±(99.9%) 0.004 ms/op
Iteration   2: 3.139 ±(99.9%) 0.009 ms/op
Iteration   3: 3.124 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.146 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.124, 3.146, 3.175), stdev = 0.026
  CI (99.9%): [2.671, 3.621] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.117 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.004 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
Iteration   3: 3.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.063 ±(99.9%) 1.101 ms/op [Average]
  (min, avg, max) = (3.002, 3.063, 3.123), stdev = 0.060
  CI (99.9%): [1.962, 4.164] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.365 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.003 ms/op
Iteration   1: 3.182 ±(99.9%) 0.006 ms/op
Iteration   2: 3.383 ±(99.9%) 0.003 ms/op
Iteration   3: 3.189 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.251 ±(99.9%) 2.074 ms/op [Average]
  (min, avg, max) = (3.182, 3.251, 3.383), stdev = 0.114
  CI (99.9%): [1.177, 5.325] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.001 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.623 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.006 ms/op
Iteration   1: 3.700 ±(99.9%) 0.012 ms/op
Iteration   2: 3.827 ±(99.9%) 0.008 ms/op
Iteration   3: 3.747 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.758 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (3.700, 3.758, 3.827), stdev = 0.064
  CI (99.9%): [2.590, 4.925] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.922 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.008 ms/op
Iteration   1: 3.157 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  17.826 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  12.583 ms/op
                 createUser·p0.9999: 22.410 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.241 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.966 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  15.555 ms/op
                 createUser·p0.9999: 18.556 ms/op
                 createUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300468
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22325 
    [ 2.500,  5.000) = 272779 
    [ 5.000,  7.500) = 4329 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     21.527 ms/op
     p(99.9990) =     22.937 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 6.920 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.008 ms/op
Iteration   1: 3.214 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  9.939 ms/op
                 existUser·p0.9999: 21.531 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   2: 3.062 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  15.104 ms/op
                 existUser·p0.9999: 25.854 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  8.634 ms/op
                 existUser·p0.9999: 23.578 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306365
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19719 
    [ 2.500,  5.000) = 281154 
    [ 5.000,  7.500) = 4735 
    [ 7.500, 10.000) = 384 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     24.787 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 7.227 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.011 ms/op
Iteration   1: 3.239 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  12.190 ms/op
                 getUser·p0.9999: 21.139 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   2: 3.288 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  10.453 ms/op
                 getUser·p0.9999: 22.539 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 3.277 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  14.942 ms/op
                 getUser·p0.9999: 22.381 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293459
  mean =      3.268 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13032 
    [ 2.500,  5.000) = 274042 
    [ 5.000,  7.500) = 5306 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     14.673 ms/op
     p(99.9900) =     22.205 ms/op
     p(99.9990) =     23.905 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 9.139 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.012 ms/op
Iteration   1: 3.827 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 18.175 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   2: 3.791 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.090 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.725 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.196 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  11.633 ms/op
                 listUser·p0.9999: 13.606 ms/op
                 listUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253746
  mean =      3.780 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 56 
    [ 2.500,  3.750) = 161514 
    [ 3.750,  5.000) = 84237 
    [ 5.000,  6.250) = 2720 
    [ 6.250,  7.500) = 3371 
    [ 7.500,  8.750) = 745 
    [ 8.750, 10.000) = 383 
    [10.000, 11.250) = 240 
    [11.250, 12.500) = 169 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 134 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     17.617 ms/op
     p(99.9990) =     18.605 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.785 ± 7.635  ops/ms
ClientPb.existUser                       thrpt       3  10.277 ± 4.493  ops/ms
ClientPb.getUser                         thrpt       3  10.063 ± 6.017  ops/ms
ClientPb.listUser                        thrpt       3   8.550 ± 1.732  ops/ms
ClientPb.createUser                       avgt       3   3.146 ± 0.475   ms/op
ClientPb.existUser                        avgt       3   3.063 ± 1.101   ms/op
ClientPb.getUser                          avgt       3   3.251 ± 2.074   ms/op
ClientPb.listUser                         avgt       3   3.758 ± 1.168   ms/op
ClientPb.createUser                     sample  300468   3.192 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.664           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.531           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.958           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.527           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.364           ms/op
ClientPb.existUser                      sample  306365   3.132 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.978           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.485           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.787           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.378           ms/op
ClientPb.getUser                        sample  293459   3.268 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.130           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.906           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.673           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.205           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.347           ms/op
ClientPb.listUser                       sample  253746   3.780 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.087           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.517           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.617           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.842           ms/op
