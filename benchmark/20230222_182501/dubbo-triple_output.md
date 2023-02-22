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
# Warmup Iteration   1: 2.494 ops/ms
# Warmup Iteration   2: 5.571 ops/ms
# Warmup Iteration   3: 9.577 ops/ms
Iteration   1: 10.060 ops/ms
Iteration   2: 10.043 ops/ms
Iteration   3: 10.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.062 ±(99.9%) 0.372 ops/ms [Average]
  (min, avg, max) = (10.043, 10.062, 10.084), stdev = 0.020
  CI (99.9%): [9.690, 10.434] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ops/ms
# Warmup Iteration   2: 9.483 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 10.408 ops/ms
Iteration   2: 9.991 ops/ms
Iteration   3: 10.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.134 ±(99.9%) 4.337 ops/ms [Average]
  (min, avg, max) = (9.991, 10.134, 10.408), stdev = 0.238
  CI (99.9%): [5.797, 14.471] (assumes normal distribution)


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
# Warmup Iteration   1: 3.815 ops/ms
# Warmup Iteration   2: 9.172 ops/ms
# Warmup Iteration   3: 9.924 ops/ms
Iteration   1: 10.191 ops/ms
Iteration   2: 10.261 ops/ms
Iteration   3: 10.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.191 ±(99.9%) 1.284 ops/ms [Average]
  (min, avg, max) = (10.120, 10.191, 10.261), stdev = 0.070
  CI (99.9%): [8.907, 11.474] (assumes normal distribution)


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
# Warmup Iteration   1: 3.552 ops/ms
# Warmup Iteration   2: 7.865 ops/ms
# Warmup Iteration   3: 8.419 ops/ms
Iteration   1: 8.360 ops/ms
Iteration   2: 8.705 ops/ms
Iteration   3: 8.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.590 ±(99.9%) 3.632 ops/ms [Average]
  (min, avg, max) = (8.360, 8.590, 8.705), stdev = 0.199
  CI (99.9%): [4.957, 12.222] (assumes normal distribution)


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
# Warmup Iteration   1: 8.245 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.005 ms/op
Iteration   1: 3.250 ±(99.9%) 0.003 ms/op
Iteration   2: 3.092 ±(99.9%) 0.003 ms/op
Iteration   3: 3.070 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.137 ±(99.9%) 1.788 ms/op [Average]
  (min, avg, max) = (3.070, 3.137, 3.250), stdev = 0.098
  CI (99.9%): [1.349, 4.926] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.208 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.005 ms/op
Iteration   1: 3.036 ±(99.9%) 0.007 ms/op
Iteration   2: 3.003 ±(99.9%) 0.004 ms/op
Iteration   3: 3.055 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.031 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (3.003, 3.031, 3.055), stdev = 0.026
  CI (99.9%): [2.551, 3.512] (assumes normal distribution)


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
# Warmup Iteration   1: 7.959 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.003 ms/op
Iteration   1: 3.307 ±(99.9%) 0.003 ms/op
Iteration   2: 3.328 ±(99.9%) 0.004 ms/op
Iteration   3: 3.121 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.252 ±(99.9%) 2.073 ms/op [Average]
  (min, avg, max) = (3.121, 3.252, 3.328), stdev = 0.114
  CI (99.9%): [1.179, 5.325] (assumes normal distribution)


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
# Warmup Iteration   1: 9.058 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.271 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.006 ms/op
Iteration   1: 3.743 ±(99.9%) 0.007 ms/op
Iteration   2: 3.688 ±(99.9%) 0.008 ms/op
Iteration   3: 3.692 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.708 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (3.688, 3.708, 3.743), stdev = 0.031
  CI (99.9%): [3.147, 4.268] (assumes normal distribution)


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
# Warmup Iteration   1: 7.270 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.010 ms/op
Iteration   1: 3.114 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.571 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  19.346 ms/op
                 createUser·p0.9999: 21.094 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  10.694 ms/op
                 createUser·p0.9999: 22.865 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   3: 3.296 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  14.385 ms/op
                 createUser·p0.9999: 19.092 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301800
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14706 
    [ 2.500,  5.000) = 282157 
    [ 5.000,  7.500) = 3994 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     21.916 ms/op
     p(99.9990) =     24.018 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 7.141 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.008 ms/op
Iteration   1: 3.204 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   6.146 ms/op
                 existUser·p0.999:  9.535 ms/op
                 existUser·p0.9999: 23.987 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   2: 3.095 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  12.648 ms/op
                 existUser·p0.9999: 24.685 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.315 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  12.567 ms/op
                 existUser·p0.9999: 20.628 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308216
  mean =      3.114 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25311 
    [ 2.500,  5.000) = 277524 
    [ 5.000,  7.500) = 4708 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.315 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     23.926 ms/op
     p(99.9990) =     25.130 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 8.496 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.010 ms/op
Iteration   1: 3.272 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   21.103 ms/op

Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.301 ms/op
                 getUser·p0.95:   3.502 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  19.551 ms/op
                 getUser·p0.9999: 21.285 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   3: 3.239 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  12.441 ms/op
                 getUser·p0.9999: 26.509 ms/op
                 getUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300775
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12834 
    [ 2.500,  5.000) = 280909 
    [ 5.000,  7.500) = 6031 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     14.471 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     26.770 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 8.801 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.011 ms/op
Iteration   1: 3.714 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  13.697 ms/op
                 listUser·p0.9999: 22.491 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   2: 3.772 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 15.139 ms/op
                 listUser·p1.00:   15.434 ms/op

Iteration   3: 3.732 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 15.434 ms/op
                 listUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256581
  mean =      3.739 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 248541 
    [ 5.000,  7.500) = 5923 
    [ 7.500, 10.000) = 1332 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 322 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     20.786 ms/op
     p(99.9990) =     24.265 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.062 ± 0.372  ops/ms
ClientPb.existUser                       thrpt       3  10.134 ± 4.337  ops/ms
ClientPb.getUser                         thrpt       3  10.191 ± 1.284  ops/ms
ClientPb.listUser                        thrpt       3   8.590 ± 3.632  ops/ms
ClientPb.createUser                       avgt       3   3.137 ± 1.788   ms/op
ClientPb.existUser                        avgt       3   3.031 ± 0.480   ms/op
ClientPb.getUser                          avgt       3   3.252 ± 2.073   ms/op
ClientPb.listUser                         avgt       3   3.708 ± 0.560   ms/op
ClientPb.createUser                     sample  301800   3.176 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.931           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.467           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.916           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.052           ms/op
ClientPb.existUser                      sample  308216   3.114 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.315           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.567           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.926           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.395           ms/op
ClientPb.getUser                        sample  300775   3.189 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.167           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.471           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.969           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.558           ms/op
ClientPb.listUser                       sample  256581   3.739 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.397           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.451           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.786           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.035           ms/op
