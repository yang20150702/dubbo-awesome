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
# Warmup Iteration   1: 2.091 ops/ms
# Warmup Iteration   2: 5.922 ops/ms
# Warmup Iteration   3: 8.770 ops/ms
Iteration   1: 9.478 ops/ms
Iteration   2: 9.562 ops/ms
Iteration   3: 9.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.451 ±(99.9%) 2.313 ops/ms [Average]
  (min, avg, max) = (9.313, 9.451, 9.562), stdev = 0.127
  CI (99.9%): [7.138, 11.764] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.200 ops/ms
# Warmup Iteration   2: 9.010 ops/ms
# Warmup Iteration   3: 9.815 ops/ms
Iteration   1: 10.143 ops/ms
Iteration   2: 9.860 ops/ms
Iteration   3: 9.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.867 ±(99.9%) 4.974 ops/ms [Average]
  (min, avg, max) = (9.598, 9.867, 10.143), stdev = 0.273
  CI (99.9%): [4.894, 14.841] (assumes normal distribution)


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
# Warmup Iteration   1: 3.567 ops/ms
# Warmup Iteration   2: 8.585 ops/ms
# Warmup Iteration   3: 9.156 ops/ms
Iteration   1: 9.541 ops/ms
Iteration   2: 9.630 ops/ms
Iteration   3: 9.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.532 ±(99.9%) 1.854 ops/ms [Average]
  (min, avg, max) = (9.427, 9.532, 9.630), stdev = 0.102
  CI (99.9%): [7.679, 11.386] (assumes normal distribution)


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
# Warmup Iteration   1: 3.015 ops/ms
# Warmup Iteration   2: 7.634 ops/ms
# Warmup Iteration   3: 8.062 ops/ms
Iteration   1: 8.138 ops/ms
Iteration   2: 8.020 ops/ms
Iteration   3: 8.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.142 ±(99.9%) 2.256 ops/ms [Average]
  (min, avg, max) = (8.020, 8.142, 8.268), stdev = 0.124
  CI (99.9%): [5.886, 10.398] (assumes normal distribution)


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
# Warmup Iteration   1: 8.368 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.004 ms/op
Iteration   1: 3.388 ±(99.9%) 0.005 ms/op
Iteration   2: 3.340 ±(99.9%) 0.004 ms/op
Iteration   3: 3.259 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.329 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (3.259, 3.329, 3.388), stdev = 0.065
  CI (99.9%): [2.135, 4.523] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.225 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.008 ms/op
Iteration   1: 3.187 ±(99.9%) 0.006 ms/op
Iteration   2: 3.284 ±(99.9%) 0.007 ms/op
Iteration   3: 3.201 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.224 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (3.187, 3.224, 3.284), stdev = 0.052
  CI (99.9%): [2.270, 4.178] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.228 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.007 ms/op
Iteration   1: 3.467 ±(99.9%) 0.009 ms/op
Iteration   2: 3.340 ±(99.9%) 0.009 ms/op
Iteration   3: 3.400 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.402 ±(99.9%) 1.156 ms/op [Average]
  (min, avg, max) = (3.340, 3.402, 3.467), stdev = 0.063
  CI (99.9%): [2.246, 4.558] (assumes normal distribution)


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
# Warmup Iteration   1: 9.425 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.008 ms/op
Iteration   1: 3.860 ±(99.9%) 0.014 ms/op
Iteration   2: 3.935 ±(99.9%) 0.008 ms/op
Iteration   3: 3.849 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.881 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.849, 3.881, 3.935), stdev = 0.047
  CI (99.9%): [3.025, 4.737] (assumes normal distribution)


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
# Warmup Iteration   1: 9.136 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.374 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
Iteration   1: 3.381 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  20.027 ms/op
                 createUser·p0.9999: 22.746 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   2: 3.333 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  21.923 ms/op
                 createUser·p0.9999: 30.782 ms/op
                 createUser·p1.00:   31.392 ms/op

Iteration   3: 3.397 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.706 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  16.122 ms/op
                 createUser·p0.9999: 25.611 ms/op
                 createUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284588
  mean =      3.370 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8528 
    [ 2.500,  5.000) = 271346 
    [ 5.000,  7.500) = 3860 
    [ 7.500, 10.000) = 372 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     16.171 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     31.155 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 7.883 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.009 ms/op
Iteration   1: 3.312 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  8.682 ms/op
                 existUser·p0.9999: 22.665 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   2: 3.241 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  17.367 ms/op
                 existUser·p0.9999: 25.105 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 3.349 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  19.333 ms/op
                 existUser·p0.9999: 26.326 ms/op
                 existUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290414
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15737 
    [ 2.500,  5.000) = 268059 
    [ 5.000,  7.500) = 5681 
    [ 7.500, 10.000) = 572 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.602 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     25.427 ms/op
     p(99.9990) =     30.971 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 8.421 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.008 ms/op
Iteration   1: 3.351 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  13.313 ms/op
                 getUser·p0.9999: 23.930 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   2: 3.297 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.610 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.550 ms/op
                 getUser·p0.999:  11.043 ms/op
                 getUser·p0.9999: 21.496 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   3: 3.482 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  16.663 ms/op
                 getUser·p0.9999: 25.854 ms/op
                 getUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284393
  mean =      3.375 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12535 
    [ 2.500,  5.000) = 263663 
    [ 5.000,  7.500) = 7130 
    [ 7.500, 10.000) = 742 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     13.320 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     26.268 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 9.293 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.013 ms/op
Iteration   1: 3.882 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  16.430 ms/op
                 listUser·p0.9999: 23.585 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   2: 3.912 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.177 ms/op
                 listUser·p0.999:  14.952 ms/op
                 listUser·p0.9999: 17.558 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.913 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.830 ms/op
                 listUser·p0.999:  14.565 ms/op
                 listUser·p0.9999: 20.999 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245974
  mean =      3.902 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 239483 
    [ 5.000,  7.500) = 4658 
    [ 7.500, 10.000) = 1076 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     14.992 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     23.959 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.451 ± 2.313  ops/ms
ClientPb.existUser                       thrpt       3   9.867 ± 4.974  ops/ms
ClientPb.getUser                         thrpt       3   9.532 ± 1.854  ops/ms
ClientPb.listUser                        thrpt       3   8.142 ± 2.256  ops/ms
ClientPb.createUser                       avgt       3   3.329 ± 1.194   ms/op
ClientPb.existUser                        avgt       3   3.224 ± 0.954   ms/op
ClientPb.getUser                          avgt       3   3.402 ± 1.156   ms/op
ClientPb.listUser                         avgt       3   3.881 ± 0.856   ms/op
ClientPb.createUser                     sample  284588   3.370 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.268           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.171           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.492           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.392           ms/op
ClientPb.existUser                      sample  290414   3.300 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.229           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.026           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.602           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.138           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.427           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.719           ms/op
ClientPb.getUser                        sample  284393   3.375 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.014           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.320           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.461           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.640           ms/op
ClientPb.listUser                       sample  245974   3.902 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.468           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.857           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.992           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.839           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.642           ms/op
