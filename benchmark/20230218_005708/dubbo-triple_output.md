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
# Warmup Iteration   1: 2.160 ops/ms
# Warmup Iteration   2: 5.602 ops/ms
# Warmup Iteration   3: 8.570 ops/ms
Iteration   1: 9.168 ops/ms
Iteration   2: 9.411 ops/ms
Iteration   3: 9.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.302 ±(99.9%) 2.252 ops/ms [Average]
  (min, avg, max) = (9.168, 9.302, 9.411), stdev = 0.123
  CI (99.9%): [7.050, 11.553] (assumes normal distribution)


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
# Warmup Iteration   1: 2.664 ops/ms
# Warmup Iteration   2: 8.661 ops/ms
# Warmup Iteration   3: 9.362 ops/ms
Iteration   1: 9.871 ops/ms
Iteration   2: 9.864 ops/ms
Iteration   3: 9.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.892 ±(99.9%) 0.761 ops/ms [Average]
  (min, avg, max) = (9.864, 9.892, 9.940), stdev = 0.042
  CI (99.9%): [9.131, 10.652] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.851 ops/ms
# Warmup Iteration   2: 8.661 ops/ms
# Warmup Iteration   3: 9.095 ops/ms
Iteration   1: 9.421 ops/ms
Iteration   2: 9.479 ops/ms
Iteration   3: 9.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.533 ±(99.9%) 2.696 ops/ms [Average]
  (min, avg, max) = (9.421, 9.533, 9.701), stdev = 0.148
  CI (99.9%): [6.838, 12.229] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.460 ops/ms
# Warmup Iteration   2: 7.141 ops/ms
# Warmup Iteration   3: 7.817 ops/ms
Iteration   1: 7.970 ops/ms
Iteration   2: 7.727 ops/ms
Iteration   3: 8.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.959 ±(99.9%) 4.153 ops/ms [Average]
  (min, avg, max) = (7.727, 7.959, 8.182), stdev = 0.228
  CI (99.9%): [3.806, 12.113] (assumes normal distribution)


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
# Warmup Iteration   1: 9.506 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.006 ms/op
Iteration   1: 3.402 ±(99.9%) 0.012 ms/op
Iteration   2: 3.356 ±(99.9%) 0.005 ms/op
Iteration   3: 3.301 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.353 ±(99.9%) 0.918 ms/op [Average]
  (min, avg, max) = (3.301, 3.353, 3.402), stdev = 0.050
  CI (99.9%): [2.435, 4.271] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.605 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.006 ms/op
Iteration   1: 3.297 ±(99.9%) 0.008 ms/op
Iteration   2: 3.222 ±(99.9%) 0.005 ms/op
Iteration   3: 3.221 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.247 ±(99.9%) 0.797 ms/op [Average]
  (min, avg, max) = (3.221, 3.247, 3.297), stdev = 0.044
  CI (99.9%): [2.449, 4.044] (assumes normal distribution)


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
# Warmup Iteration   1: 8.494 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.006 ms/op
Iteration   1: 3.352 ±(99.9%) 0.010 ms/op
Iteration   2: 3.389 ±(99.9%) 0.004 ms/op
Iteration   3: 3.356 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.366 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (3.352, 3.366, 3.389), stdev = 0.020
  CI (99.9%): [2.996, 3.735] (assumes normal distribution)


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
# Warmup Iteration   1: 11.367 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.010 ms/op
Iteration   1: 3.873 ±(99.9%) 0.009 ms/op
Iteration   2: 3.972 ±(99.9%) 0.010 ms/op
Iteration   3: 3.921 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.922 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (3.873, 3.922, 3.972), stdev = 0.050
  CI (99.9%): [3.018, 4.826] (assumes normal distribution)


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
# Warmup Iteration   1: 9.638 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.009 ms/op
Iteration   1: 3.380 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  20.106 ms/op
                 createUser·p0.9999: 23.765 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 3.372 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.597 ms/op
                 createUser·p0.999:  22.819 ms/op
                 createUser·p0.9999: 26.510 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   3: 3.284 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  18.874 ms/op
                 createUser·p0.9999: 29.385 ms/op
                 createUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286932
  mean =      3.344 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10766 
    [ 2.500,  5.000) = 270182 
    [ 5.000,  7.500) = 5066 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     18.879 ms/op
     p(99.9900) =     28.180 ms/op
     p(99.9990) =     29.873 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 8.212 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.009 ms/op
Iteration   1: 3.388 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  19.887 ms/op
                 existUser·p0.9999: 28.723 ms/op
                 existUser·p1.00:   29.164 ms/op

Iteration   2: 3.294 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   6.003 ms/op
                 existUser·p0.999:  12.091 ms/op
                 existUser·p0.9999: 24.978 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   3: 3.281 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  11.601 ms/op
                 existUser·p0.9999: 28.050 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289214
  mean =      3.320 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19931 
    [ 2.500,  5.000) = 261752 
    [ 5.000,  7.500) = 6627 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     28.249 ms/op
     p(99.9990) =     29.102 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 10.373 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.010 ms/op
Iteration   1: 3.459 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  20.168 ms/op
                 getUser·p0.9999: 24.207 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.441 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  21.501 ms/op
                 getUser·p0.9999: 27.182 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   3: 3.402 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  25.199 ms/op
                 getUser·p0.9999: 30.330 ms/op
                 getUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279437
  mean =      3.434 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13338 
    [ 2.500,  5.000) = 258759 
    [ 5.000,  7.500) = 6237 
    [ 7.500, 10.000) = 608 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     20.711 ms/op
     p(99.9900) =     29.173 ms/op
     p(99.9990) =     30.907 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 10.633 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.013 ms/op
Iteration   1: 3.998 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.604 ms/op
                 listUser·p0.999:  22.181 ms/op
                 listUser·p0.9999: 34.996 ms/op
                 listUser·p1.00:   35.389 ms/op

Iteration   2: 3.979 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 17.202 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 3.873 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  15.548 ms/op
                 listUser·p0.9999: 17.383 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243012
  mean =      3.949 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 234125 
    [ 5.000,  7.500) = 6711 
    [ 7.500, 10.000) = 1255 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 218 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     33.914 ms/op
     p(99.9990) =     35.230 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.302 ± 2.252  ops/ms
ClientPb.existUser                       thrpt       3   9.892 ± 0.761  ops/ms
ClientPb.getUser                         thrpt       3   9.533 ± 2.696  ops/ms
ClientPb.listUser                        thrpt       3   7.959 ± 4.153  ops/ms
ClientPb.createUser                       avgt       3   3.353 ± 0.918   ms/op
ClientPb.existUser                        avgt       3   3.247 ± 0.797   ms/op
ClientPb.getUser                          avgt       3   3.366 ± 0.369   ms/op
ClientPb.listUser                         avgt       3   3.922 ± 0.904   ms/op
ClientPb.createUser                     sample  286932   3.344 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.149           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.882           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.879           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.180           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.048           ms/op
ClientPb.existUser                      sample  289214   3.320 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.290           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.091           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.249           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.164           ms/op
ClientPb.getUser                        sample  279437   3.434 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.419           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.711           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.173           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.326           ms/op
ClientPb.listUser                       sample  243012   3.949 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.665           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.450           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.914           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.389           ms/op
