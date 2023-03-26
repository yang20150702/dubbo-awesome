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
# Warmup Iteration   1: 2.264 ops/ms
# Warmup Iteration   2: 5.796 ops/ms
# Warmup Iteration   3: 8.641 ops/ms
Iteration   1: 9.465 ops/ms
Iteration   2: 9.341 ops/ms
Iteration   3: 9.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.300 ±(99.9%) 3.449 ops/ms [Average]
  (min, avg, max) = (9.093, 9.300, 9.465), stdev = 0.189
  CI (99.9%): [5.850, 12.749] (assumes normal distribution)


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
# Warmup Iteration   1: 3.704 ops/ms
# Warmup Iteration   2: 8.662 ops/ms
# Warmup Iteration   3: 9.832 ops/ms
Iteration   1: 9.879 ops/ms
Iteration   2: 10.043 ops/ms
Iteration   3: 9.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.941 ±(99.9%) 1.617 ops/ms [Average]
  (min, avg, max) = (9.879, 9.941, 10.043), stdev = 0.089
  CI (99.9%): [8.325, 11.558] (assumes normal distribution)


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
# Warmup Iteration   1: 2.705 ops/ms
# Warmup Iteration   2: 8.260 ops/ms
# Warmup Iteration   3: 9.444 ops/ms
Iteration   1: 9.552 ops/ms
Iteration   2: 9.029 ops/ms
Iteration   3: 9.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.235 ±(99.9%) 5.081 ops/ms [Average]
  (min, avg, max) = (9.029, 9.235, 9.552), stdev = 0.278
  CI (99.9%): [4.154, 14.316] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.051 ops/ms
# Warmup Iteration   2: 7.332 ops/ms
# Warmup Iteration   3: 7.904 ops/ms
Iteration   1: 7.842 ops/ms
Iteration   2: 8.227 ops/ms
Iteration   3: 8.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.130 ±(99.9%) 4.644 ops/ms [Average]
  (min, avg, max) = (7.842, 8.130, 8.322), stdev = 0.255
  CI (99.9%): [3.486, 12.774] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.817 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.005 ms/op
Iteration   1: 3.345 ±(99.9%) 0.005 ms/op
Iteration   2: 3.458 ±(99.9%) 0.005 ms/op
Iteration   3: 3.415 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.406 ±(99.9%) 1.044 ms/op [Average]
  (min, avg, max) = (3.345, 3.406, 3.458), stdev = 0.057
  CI (99.9%): [2.362, 4.450] (assumes normal distribution)


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
# Warmup Iteration   1: 8.323 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.009 ms/op
Iteration   1: 3.394 ±(99.9%) 0.004 ms/op
Iteration   2: 3.239 ±(99.9%) 0.010 ms/op
Iteration   3: 3.217 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.283 ±(99.9%) 1.761 ms/op [Average]
  (min, avg, max) = (3.217, 3.283, 3.394), stdev = 0.097
  CI (99.9%): [1.523, 5.044] (assumes normal distribution)


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
# Warmup Iteration   1: 10.079 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.003 ms/op
Iteration   1: 3.478 ±(99.9%) 0.003 ms/op
Iteration   2: 3.381 ±(99.9%) 0.006 ms/op
Iteration   3: 3.376 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.412 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (3.376, 3.412, 3.478), stdev = 0.058
  CI (99.9%): [2.360, 4.463] (assumes normal distribution)


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
# Warmup Iteration   1: 9.962 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.382 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.005 ms/op
Iteration   1: 4.013 ±(99.9%) 0.009 ms/op
Iteration   2: 3.927 ±(99.9%) 0.011 ms/op
Iteration   3: 3.933 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.958 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (3.927, 3.958, 4.013), stdev = 0.048
  CI (99.9%): [3.079, 4.836] (assumes normal distribution)


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
# Warmup Iteration   1: 9.417 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.009 ms/op
Iteration   1: 3.517 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  19.566 ms/op
                 createUser·p0.9999: 30.537 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   2: 3.433 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  21.117 ms/op
                 createUser·p0.9999: 28.334 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 3.334 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.978 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 25.015 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280205
  mean =      3.426 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9047 
    [ 2.500,  5.000) = 263157 
    [ 5.000,  7.500) = 6915 
    [ 7.500, 10.000) = 656 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     17.634 ms/op
     p(99.9900) =     29.028 ms/op
     p(99.9990) =     31.234 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 8.809 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.460 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
Iteration   1: 3.201 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  10.732 ms/op
                 existUser·p0.9999: 21.234 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   2: 3.248 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.571 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  13.499 ms/op
                 existUser·p0.9999: 21.239 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   3: 3.427 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  16.073 ms/op
                 existUser·p0.9999: 25.253 ms/op
                 existUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291868
  mean =      3.289 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15070 
    [ 2.500,  5.000) = 269413 
    [ 5.000,  7.500) = 6531 
    [ 7.500, 10.000) = 453 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     13.404 ms/op
     p(99.9900) =     23.325 ms/op
     p(99.9990) =     25.594 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 10.100 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.010 ms/op
Iteration   1: 3.389 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.702 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.947 ms/op
                 getUser·p0.999:  19.801 ms/op
                 getUser·p0.9999: 22.942 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.314 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  17.826 ms/op
                 getUser·p0.9999: 23.715 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   3: 3.560 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  21.070 ms/op
                 getUser·p0.9999: 25.727 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280558
  mean =      3.418 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5039 
    [ 2.500,  5.000) = 267246 
    [ 5.000,  7.500) = 7080 
    [ 7.500, 10.000) = 773 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.475 ms/op
     p(99.9000) =     20.167 ms/op
     p(99.9900) =     24.738 ms/op
     p(99.9990) =     26.620 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 9.869 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.382 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.012 ms/op
Iteration   1: 4.029 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 23.496 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 4.004 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.446 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 3.994 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239486
  mean =      4.009 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 229683 
    [ 5.000,  7.500) = 7608 
    [ 7.500, 10.000) = 1382 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.896 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     15.426 ms/op
     p(99.9900) =     20.913 ms/op
     p(99.9990) =     23.843 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.300 ± 3.449  ops/ms
ClientPb.existUser                       thrpt       3   9.941 ± 1.617  ops/ms
ClientPb.getUser                         thrpt       3   9.235 ± 5.081  ops/ms
ClientPb.listUser                        thrpt       3   8.130 ± 4.644  ops/ms
ClientPb.createUser                       avgt       3   3.406 ± 1.044   ms/op
ClientPb.existUser                        avgt       3   3.283 ± 1.761   ms/op
ClientPb.getUser                          avgt       3   3.412 ± 1.052   ms/op
ClientPb.listUser                         avgt       3   3.958 ± 0.878   ms/op
ClientPb.createUser                     sample  280205   3.426 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.217           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.634           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.028           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.982           ms/op
ClientPb.existUser                      sample  291868   3.289 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.039           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.141           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.939           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.404           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.325           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.247           ms/op
ClientPb.getUser                        sample  280558   3.418 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.200           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.475           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.167           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.738           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.935           ms/op
ClientPb.listUser                       sample  239486   4.009 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.426           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.913           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.986           ms/op
