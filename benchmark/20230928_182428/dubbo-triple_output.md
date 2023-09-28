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
# Warmup Iteration   1: 1.979 ops/ms
# Warmup Iteration   2: 4.840 ops/ms
# Warmup Iteration   3: 8.333 ops/ms
Iteration   1: 8.989 ops/ms
Iteration   2: 9.237 ops/ms
Iteration   3: 9.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.099 ±(99.9%) 2.304 ops/ms [Average]
  (min, avg, max) = (8.989, 9.099, 9.237), stdev = 0.126
  CI (99.9%): [6.796, 11.403] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.913 ops/ms
# Warmup Iteration   2: 8.575 ops/ms
# Warmup Iteration   3: 9.059 ops/ms
Iteration   1: 9.498 ops/ms
Iteration   2: 9.349 ops/ms
Iteration   3: 9.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.414 ±(99.9%) 1.402 ops/ms [Average]
  (min, avg, max) = (9.349, 9.414, 9.498), stdev = 0.077
  CI (99.9%): [8.011, 10.816] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.299 ops/ms
# Warmup Iteration   2: 7.736 ops/ms
# Warmup Iteration   3: 9.088 ops/ms
Iteration   1: 8.900 ops/ms
Iteration   2: 9.125 ops/ms
Iteration   3: 8.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.998 ±(99.9%) 2.104 ops/ms [Average]
  (min, avg, max) = (8.900, 8.998, 9.125), stdev = 0.115
  CI (99.9%): [6.895, 11.102] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.705 ops/ms
# Warmup Iteration   2: 6.455 ops/ms
# Warmup Iteration   3: 7.294 ops/ms
Iteration   1: 7.288 ops/ms
Iteration   2: 7.916 ops/ms
Iteration   3: 7.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.588 ±(99.9%) 5.747 ops/ms [Average]
  (min, avg, max) = (7.288, 7.588, 7.916), stdev = 0.315
  CI (99.9%): [1.841, 13.335] (assumes normal distribution)


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
# Warmup Iteration   1: 11.855 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.006 ms/op
Iteration   1: 3.602 ±(99.9%) 0.006 ms/op
Iteration   2: 3.597 ±(99.9%) 0.007 ms/op
Iteration   3: 3.615 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.605 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (3.597, 3.605, 3.615), stdev = 0.009
  CI (99.9%): [3.441, 3.768] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.016 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.004 ms/op
Iteration   1: 3.383 ±(99.9%) 0.005 ms/op
Iteration   2: 3.467 ±(99.9%) 0.004 ms/op
Iteration   3: 3.406 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.419 ±(99.9%) 0.797 ms/op [Average]
  (min, avg, max) = (3.383, 3.419, 3.467), stdev = 0.044
  CI (99.9%): [2.622, 4.216] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.364 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.673 ±(99.9%) 0.005 ms/op
Iteration   1: 3.636 ±(99.9%) 0.004 ms/op
Iteration   2: 3.658 ±(99.9%) 0.002 ms/op
Iteration   3: 3.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.601 ±(99.9%) 1.447 ms/op [Average]
  (min, avg, max) = (3.511, 3.601, 3.658), stdev = 0.079
  CI (99.9%): [2.154, 5.048] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.524 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.822 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.007 ms/op
Iteration   1: 4.267 ±(99.9%) 0.007 ms/op
Iteration   2: 4.288 ±(99.9%) 0.005 ms/op
Iteration   3: 4.196 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.250 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (4.196, 4.250, 4.288), stdev = 0.049
  CI (99.9%): [3.364, 5.137] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.567 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.016 ms/op
Iteration   1: 3.599 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  22.774 ms/op
                 createUser·p0.9999: 25.497 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   2: 3.515 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.386 ms/op
                 createUser·p0.999:  24.409 ms/op
                 createUser·p0.9999: 30.847 ms/op
                 createUser·p1.00:   31.621 ms/op

Iteration   3: 3.627 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.640 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  24.145 ms/op
                 createUser·p0.9999: 29.989 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268142
  mean =      3.580 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4521 
    [ 2.500,  5.000) = 254992 
    [ 5.000,  7.500) = 6522 
    [ 7.500, 10.000) = 1289 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     23.588 ms/op
     p(99.9900) =     29.983 ms/op
     p(99.9990) =     31.213 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.866 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.010 ms/op
Iteration   1: 3.459 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   6.685 ms/op
                 existUser·p0.999:  20.382 ms/op
                 existUser·p0.9999: 23.356 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   2: 3.446 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  14.060 ms/op
                 existUser·p0.9999: 35.848 ms/op
                 existUser·p1.00:   37.421 ms/op

Iteration   3: 3.554 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   7.438 ms/op
                 existUser·p0.999:  24.998 ms/op
                 existUser·p0.9999: 28.836 ms/op
                 existUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275338
  mean =      3.486 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5243 
    [ 2.500,  5.000) = 260920 
    [ 5.000,  7.500) = 7295 
    [ 7.500, 10.000) = 1157 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     15.996 ms/op
     p(99.9900) =     33.225 ms/op
     p(99.9990) =     36.534 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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
# Warmup Iteration   1: 9.217 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.010 ms/op
Iteration   1: 3.562 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.898 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  17.531 ms/op
                 getUser·p0.9999: 24.151 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.531 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  23.822 ms/op
                 getUser·p0.9999: 27.097 ms/op
                 getUser·p1.00:   31.326 ms/op

Iteration   3: 3.578 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.585 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  20.972 ms/op
                 getUser·p0.9999: 33.458 ms/op
                 getUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269796
  mean =      3.557 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4221 
    [ 2.500,  5.000) = 256392 
    [ 5.000,  7.500) = 6664 
    [ 7.500, 10.000) = 1727 
    [10.000, 12.500) = 352 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     30.151 ms/op
     p(99.9990) =     33.574 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.747 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.942 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.016 ms/op
Iteration   1: 4.260 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  23.200 ms/op
                 listUser·p0.9999: 33.750 ms/op
                 listUser·p1.00:   36.110 ms/op

Iteration   2: 4.239 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 24.147 ms/op
                 listUser·p1.00:   32.178 ms/op

Iteration   3: 4.196 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  16.803 ms/op
                 listUser·p0.9999: 49.414 ms/op
                 listUser·p1.00:   50.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226725
  mean =      4.231 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 212271 
    [ 5.000, 10.000) = 13212 
    [10.000, 15.000) = 818 
    [15.000, 20.000) = 221 
    [20.000, 25.000) = 132 
    [25.000, 30.000) = 24 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 6 
    [45.000, 50.000) = 22 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      8.282 ms/op
     p(99.9000) =     19.047 ms/op
     p(99.9900) =     46.639 ms/op
     p(99.9990) =     49.785 ms/op
     p(99.9999) =     50.266 ms/op
    p(100.0000) =     50.266 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.099 ± 2.304  ops/ms
ClientPb.existUser                       thrpt       3   9.414 ± 1.402  ops/ms
ClientPb.getUser                         thrpt       3   8.998 ± 2.104  ops/ms
ClientPb.listUser                        thrpt       3   7.588 ± 5.747  ops/ms
ClientPb.createUser                       avgt       3   3.605 ± 0.164   ms/op
ClientPb.existUser                        avgt       3   3.419 ± 0.797   ms/op
ClientPb.getUser                          avgt       3   3.601 ± 1.447   ms/op
ClientPb.listUser                         avgt       3   4.250 ± 0.887   ms/op
ClientPb.createUser                     sample  268142   3.580 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.325           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.209           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.588           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.983           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.621           ms/op
ClientPb.existUser                      sample  275338   3.486 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.518           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.996           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.225           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.421           ms/op
ClientPb.getUser                        sample  269796   3.557 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.427           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.406           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.907           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.151           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  226725   4.231 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.178           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.282           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.047           ms/op
ClientPb.listUser:listUser·p0.9999      sample          46.639           ms/op
ClientPb.listUser:listUser·p1.00        sample          50.266           ms/op
