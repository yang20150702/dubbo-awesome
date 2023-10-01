# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.013 ops/ms
# Warmup Iteration   2: 4.772 ops/ms
# Warmup Iteration   3: 8.349 ops/ms
Iteration   1: 8.820 ops/ms
Iteration   2: 9.105 ops/ms
Iteration   3: 9.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.031 ±(99.9%) 3.394 ops/ms [Average]
  (min, avg, max) = (8.820, 9.031, 9.169), stdev = 0.186
  CI (99.9%): [5.637, 12.426] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.020 ops/ms
# Warmup Iteration   2: 8.752 ops/ms
# Warmup Iteration   3: 9.256 ops/ms
Iteration   1: 9.388 ops/ms
Iteration   2: 9.412 ops/ms
Iteration   3: 9.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.426 ±(99.9%) 0.850 ops/ms [Average]
  (min, avg, max) = (9.388, 9.426, 9.478), stdev = 0.047
  CI (99.9%): [8.576, 10.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.554 ops/ms
# Warmup Iteration   2: 7.887 ops/ms
# Warmup Iteration   3: 8.977 ops/ms
Iteration   1: 8.794 ops/ms
Iteration   2: 9.077 ops/ms
Iteration   3: 9.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.019 ±(99.9%) 3.702 ops/ms [Average]
  (min, avg, max) = (8.794, 9.019, 9.187), stdev = 0.203
  CI (99.9%): [5.317, 12.721] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.781 ops/ms
# Warmup Iteration   2: 7.229 ops/ms
# Warmup Iteration   3: 7.370 ops/ms
Iteration   1: 7.459 ops/ms
Iteration   2: 7.671 ops/ms
Iteration   3: 7.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.638 ±(99.9%) 2.994 ops/ms [Average]
  (min, avg, max) = (7.459, 7.638, 7.782), stdev = 0.164
  CI (99.9%): [4.644, 10.632] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.045 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.006 ms/op
Iteration   1: 3.573 ±(99.9%) 0.007 ms/op
Iteration   2: 3.538 ±(99.9%) 0.003 ms/op
Iteration   3: 3.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.536 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (3.499, 3.536, 3.573), stdev = 0.037
  CI (99.9%): [2.859, 4.214] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.107 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.003 ms/op
Iteration   1: 3.227 ±(99.9%) 0.003 ms/op
Iteration   2: 3.372 ±(99.9%) 0.007 ms/op
Iteration   3: 3.295 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.298 ±(99.9%) 1.327 ms/op [Average]
  (min, avg, max) = (3.227, 3.298, 3.372), stdev = 0.073
  CI (99.9%): [1.971, 4.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.506 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.002 ms/op
Iteration   1: 3.402 ±(99.9%) 0.003 ms/op
Iteration   2: 3.519 ±(99.9%) 0.002 ms/op
Iteration   3: 3.396 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.439 ±(99.9%) 1.258 ms/op [Average]
  (min, avg, max) = (3.396, 3.439, 3.519), stdev = 0.069
  CI (99.9%): [2.182, 4.697] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.060 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.398 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.004 ms/op
Iteration   1: 4.044 ±(99.9%) 0.012 ms/op
Iteration   2: 4.017 ±(99.9%) 0.006 ms/op
Iteration   3: 4.092 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.051 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (4.017, 4.051, 4.092), stdev = 0.038
  CI (99.9%): [3.355, 4.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.336 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.013 ms/op
Iteration   1: 3.457 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  22.430 ms/op
                 createUser·p0.9999: 24.470 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   2: 3.515 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  13.140 ms/op
                 createUser·p0.9999: 26.106 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   3: 3.517 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.913 ms/op
                 createUser·p0.999:  19.958 ms/op
                 createUser·p0.9999: 37.552 ms/op
                 createUser·p1.00:   39.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274408
  mean =      3.496 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4456 
    [ 2.500,  5.000) = 265063 
    [ 5.000,  7.500) = 3889 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 142 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     20.630 ms/op
     p(99.9900) =     34.574 ms/op
     p(99.9990) =     39.471 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.381 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.009 ms/op
Iteration   1: 3.369 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  22.106 ms/op
                 existUser·p0.9999: 24.264 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   2: 3.454 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.304 ms/op
                 existUser·p0.999:  22.429 ms/op
                 existUser·p0.9999: 25.784 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 3.389 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 26.739 ms/op
                 existUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282315
  mean =      3.404 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10574 
    [ 2.500,  5.000) = 266727 
    [ 5.000,  7.500) = 3991 
    [ 7.500, 10.000) = 617 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 181 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     15.052 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     27.531 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.266 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.008 ms/op
Iteration   1: 3.596 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  19.596 ms/op
                 getUser·p0.9999: 21.860 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   2: 3.659 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  20.674 ms/op
                 getUser·p0.9999: 23.252 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   3: 3.518 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.441 ms/op
                 getUser·p0.999:  20.796 ms/op
                 getUser·p0.9999: 25.130 ms/op
                 getUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267202
  mean =      3.590 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3617 
    [ 2.500,  5.000) = 254114 
    [ 5.000,  7.500) = 7278 
    [ 7.500, 10.000) = 1430 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 169 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     24.487 ms/op
     p(99.9990) =     25.832 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.374 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.469 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.014 ms/op
Iteration   1: 4.166 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  18.718 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 4.181 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  16.455 ms/op
                 listUser·p0.9999: 18.525 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 4.239 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   4.141 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  15.705 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228867
  mean =      4.195 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 219772 
    [ 5.000,  7.500) = 7117 
    [ 7.500, 10.000) = 1118 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     16.618 ms/op
     p(99.9900) =     23.171 ms/op
     p(99.9990) =     24.201 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.031 ± 3.394  ops/ms
ClientPb.existUser                       thrpt       3   9.426 ± 0.850  ops/ms
ClientPb.getUser                         thrpt       3   9.019 ± 3.702  ops/ms
ClientPb.listUser                        thrpt       3   7.638 ± 2.994  ops/ms
ClientPb.createUser                       avgt       3   3.536 ± 0.678   ms/op
ClientPb.existUser                        avgt       3   3.298 ± 1.327   ms/op
ClientPb.getUser                          avgt       3   3.439 ± 1.258   ms/op
ClientPb.listUser                         avgt       3   4.051 ± 0.695   ms/op
ClientPb.createUser                     sample  274408   3.496 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.155           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.630           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.574           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.846           ms/op
ClientPb.existUser                      sample  282315   3.404 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.004           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.052           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.985           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.017           ms/op
ClientPb.getUser                        sample  267202   3.590 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.063           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.307           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.021           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.487           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.066           ms/op
ClientPb.listUser                       sample  228867   4.195 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.037           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.618           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.171           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.773           ms/op
