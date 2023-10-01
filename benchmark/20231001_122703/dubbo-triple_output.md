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
# Warmup Iteration   1: 2.139 ops/ms
# Warmup Iteration   2: 5.198 ops/ms
# Warmup Iteration   3: 8.398 ops/ms
Iteration   1: 9.098 ops/ms
Iteration   2: 8.924 ops/ms
Iteration   3: 8.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.930 ±(99.9%) 3.010 ops/ms [Average]
  (min, avg, max) = (8.768, 8.930, 9.098), stdev = 0.165
  CI (99.9%): [5.920, 11.940] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.173 ops/ms
# Warmup Iteration   2: 8.760 ops/ms
# Warmup Iteration   3: 9.206 ops/ms
Iteration   1: 9.482 ops/ms
Iteration   2: 9.585 ops/ms
Iteration   3: 9.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.527 ±(99.9%) 0.959 ops/ms [Average]
  (min, avg, max) = (9.482, 9.527, 9.585), stdev = 0.053
  CI (99.9%): [8.568, 10.485] (assumes normal distribution)


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
# Warmup Iteration   1: 2.932 ops/ms
# Warmup Iteration   2: 8.345 ops/ms
# Warmup Iteration   3: 8.843 ops/ms
Iteration   1: 9.115 ops/ms
Iteration   2: 9.321 ops/ms
Iteration   3: 9.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.153 ±(99.9%) 2.780 ops/ms [Average]
  (min, avg, max) = (9.023, 9.153, 9.321), stdev = 0.152
  CI (99.9%): [6.373, 11.933] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.921 ops/ms
# Warmup Iteration   2: 7.274 ops/ms
# Warmup Iteration   3: 7.624 ops/ms
Iteration   1: 7.684 ops/ms
Iteration   2: 7.534 ops/ms
Iteration   3: 7.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.624 ±(99.9%) 1.442 ops/ms [Average]
  (min, avg, max) = (7.534, 7.624, 7.684), stdev = 0.079
  CI (99.9%): [6.182, 9.066] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.759 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.004 ms/op
Iteration   1: 3.559 ±(99.9%) 0.008 ms/op
Iteration   2: 3.503 ±(99.9%) 0.004 ms/op
Iteration   3: 3.507 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.523 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (3.503, 3.523, 3.559), stdev = 0.031
  CI (99.9%): [2.957, 4.089] (assumes normal distribution)


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
# Warmup Iteration   1: 8.288 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.006 ms/op
Iteration   1: 3.441 ±(99.9%) 0.006 ms/op
Iteration   2: 3.357 ±(99.9%) 0.005 ms/op
Iteration   3: 3.304 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.367 ±(99.9%) 1.259 ms/op [Average]
  (min, avg, max) = (3.304, 3.367, 3.441), stdev = 0.069
  CI (99.9%): [2.108, 4.626] (assumes normal distribution)


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
# Warmup Iteration   1: 9.098 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.006 ms/op
Iteration   1: 3.475 ±(99.9%) 0.005 ms/op
Iteration   2: 3.453 ±(99.9%) 0.005 ms/op
Iteration   3: 3.646 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.524 ±(99.9%) 1.925 ms/op [Average]
  (min, avg, max) = (3.453, 3.524, 3.646), stdev = 0.106
  CI (99.9%): [1.600, 5.449] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.286 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.006 ms/op
Iteration   1: 4.233 ±(99.9%) 0.006 ms/op
Iteration   2: 4.197 ±(99.9%) 0.010 ms/op
Iteration   3: 4.062 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.164 ±(99.9%) 1.645 ms/op [Average]
  (min, avg, max) = (4.062, 4.164, 4.233), stdev = 0.090
  CI (99.9%): [2.519, 5.809] (assumes normal distribution)


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
# Warmup Iteration   1: 9.115 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.889 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.012 ms/op
Iteration   1: 3.625 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  20.578 ms/op
                 createUser·p0.9999: 23.888 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   2: 3.412 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  22.456 ms/op
                 createUser·p0.9999: 24.650 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 3.513 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 26.456 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273063
  mean =      3.515 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8660 
    [ 2.500,  5.000) = 256348 
    [ 5.000,  7.500) = 6582 
    [ 7.500, 10.000) = 807 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     25.352 ms/op
     p(99.9990) =     27.403 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 7.809 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.010 ms/op
Iteration   1: 3.397 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  13.969 ms/op
                 existUser·p0.9999: 23.546 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   2: 3.405 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   6.818 ms/op
                 existUser·p0.999:  22.120 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.548 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.344 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   7.471 ms/op
                 existUser·p0.999:  19.818 ms/op
                 existUser·p0.9999: 27.165 ms/op
                 existUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278369
  mean =      3.448 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6372 
    [ 2.500,  5.000) = 263290 
    [ 5.000,  7.500) = 6850 
    [ 7.500, 10.000) = 1109 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      0.344 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     28.366 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 8.945 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.012 ms/op
Iteration   1: 3.636 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   6.961 ms/op
                 getUser·p0.999:  10.437 ms/op
                 getUser·p0.9999: 22.813 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   2: 3.502 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.342 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  21.660 ms/op
                 getUser·p0.9999: 24.408 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   3: 3.553 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  18.383 ms/op
                 getUser·p0.9999: 26.608 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269327
  mean =      3.563 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4291 
    [ 2.500,  5.000) = 253242 
    [ 5.000,  7.500) = 10245 
    [ 7.500, 10.000) = 846 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     18.165 ms/op
     p(99.9900) =     25.435 ms/op
     p(99.9990) =     28.104 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 10.293 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.248 ±(99.9%) 0.014 ms/op
Iteration   1: 4.176 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  21.510 ms/op
                 listUser·p0.9999: 24.762 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   2: 4.236 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 17.709 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 4.198 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  15.383 ms/op
                 listUser·p0.9999: 23.671 ms/op
                 listUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228224
  mean =      4.203 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 215641 
    [ 5.000,  7.500) = 8982 
    [ 7.500, 10.000) = 2570 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 318 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     16.824 ms/op
     p(99.9900) =     23.730 ms/op
     p(99.9990) =     25.026 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.930 ± 3.010  ops/ms
ClientPb.existUser                       thrpt       3   9.527 ± 0.959  ops/ms
ClientPb.getUser                         thrpt       3   9.153 ± 2.780  ops/ms
ClientPb.listUser                        thrpt       3   7.624 ± 1.442  ops/ms
ClientPb.createUser                       avgt       3   3.523 ± 0.566   ms/op
ClientPb.existUser                        avgt       3   3.367 ± 1.259   ms/op
ClientPb.getUser                          avgt       3   3.524 ± 1.925   ms/op
ClientPb.listUser                         avgt       3   4.164 ± 1.645   ms/op
ClientPb.createUser                     sample  273063   3.515 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.898           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.333           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.352           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.525           ms/op
ClientPb.existUser                      sample  278369   3.448 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.344           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.881           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.005           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.542           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.836           ms/op
ClientPb.getUser                        sample  269327   3.563 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.342           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.165           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.435           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.377           ms/op
ClientPb.listUser                       sample  228224   4.203 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.128           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.043           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.063           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.069           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.824           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.730           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.035           ms/op
