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
# Warmup Iteration   1: 2.563 ops/ms
# Warmup Iteration   2: 5.948 ops/ms
# Warmup Iteration   3: 9.221 ops/ms
Iteration   1: 9.588 ops/ms
Iteration   2: 9.511 ops/ms
Iteration   3: 9.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.697 ±(99.9%) 4.693 ops/ms [Average]
  (min, avg, max) = (9.511, 9.697, 9.990), stdev = 0.257
  CI (99.9%): [5.003, 14.390] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.789 ops/ms
# Warmup Iteration   2: 8.707 ops/ms
# Warmup Iteration   3: 10.172 ops/ms
Iteration   1: 10.387 ops/ms
Iteration   2: 10.685 ops/ms
Iteration   3: 10.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.537 ±(99.9%) 2.716 ops/ms [Average]
  (min, avg, max) = (10.387, 10.537, 10.685), stdev = 0.149
  CI (99.9%): [7.821, 13.254] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.429 ops/ms
# Warmup Iteration   2: 9.333 ops/ms
# Warmup Iteration   3: 9.568 ops/ms
Iteration   1: 9.339 ops/ms
Iteration   2: 9.799 ops/ms
Iteration   3: 9.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.503 ±(99.9%) 4.688 ops/ms [Average]
  (min, avg, max) = (9.339, 9.503, 9.799), stdev = 0.257
  CI (99.9%): [4.814, 14.191] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.999 ops/ms
# Warmup Iteration   2: 7.821 ops/ms
# Warmup Iteration   3: 8.376 ops/ms
Iteration   1: 8.628 ops/ms
Iteration   2: 8.476 ops/ms
Iteration   3: 8.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.550 ±(99.9%) 1.388 ops/ms [Average]
  (min, avg, max) = (8.476, 8.550, 8.628), stdev = 0.076
  CI (99.9%): [7.161, 9.938] (assumes normal distribution)


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
# Warmup Iteration   1: 8.173 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.002 ms/op
Iteration   1: 3.151 ±(99.9%) 0.004 ms/op
Iteration   2: 3.198 ±(99.9%) 0.004 ms/op
Iteration   3: 3.272 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.207 ±(99.9%) 1.109 ms/op [Average]
  (min, avg, max) = (3.151, 3.207, 3.272), stdev = 0.061
  CI (99.9%): [2.098, 4.316] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.566 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.004 ms/op
Iteration   1: 3.020 ±(99.9%) 0.007 ms/op
Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
Iteration   3: 3.023 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.054 ±(99.9%) 1.015 ms/op [Average]
  (min, avg, max) = (3.020, 3.054, 3.118), stdev = 0.056
  CI (99.9%): [2.039, 4.069] (assumes normal distribution)


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
# Warmup Iteration   1: 7.553 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.004 ms/op
Iteration   1: 3.231 ±(99.9%) 0.003 ms/op
Iteration   2: 3.277 ±(99.9%) 0.004 ms/op
Iteration   3: 3.304 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.271 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (3.231, 3.271, 3.304), stdev = 0.037
  CI (99.9%): [2.598, 3.944] (assumes normal distribution)


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
# Warmup Iteration   1: 9.800 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.008 ms/op
Iteration   1: 3.781 ±(99.9%) 0.007 ms/op
Iteration   2: 3.824 ±(99.9%) 0.004 ms/op
Iteration   3: 3.739 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.781 ±(99.9%) 0.779 ms/op [Average]
  (min, avg, max) = (3.739, 3.781, 3.824), stdev = 0.043
  CI (99.9%): [3.002, 4.561] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.928 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
Iteration   1: 3.291 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  12.419 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   21.299 ms/op

Iteration   2: 3.155 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.453 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  12.599 ms/op
                 createUser·p0.9999: 22.634 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.481 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  15.925 ms/op
                 createUser·p0.9999: 23.632 ms/op
                 createUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296659
  mean =      3.236 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22213 
    [ 2.500,  5.000) = 269043 
    [ 5.000,  7.500) = 4525 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     22.621 ms/op
     p(99.9990) =     24.288 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.327 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
Iteration   1: 3.111 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.373 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   2: 3.256 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  11.754 ms/op
                 existUser·p0.9999: 21.010 ms/op
                 existUser·p1.00:   21.823 ms/op

Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  14.372 ms/op
                 existUser·p0.9999: 20.721 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305183
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14052 
    [ 2.500,  5.000) = 285553 
    [ 5.000,  7.500) = 4619 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     12.823 ms/op
     p(99.9900) =     20.266 ms/op
     p(99.9990) =     21.492 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 8.713 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.008 ms/op
Iteration   1: 3.233 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  16.204 ms/op
                 getUser·p0.9999: 20.975 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  11.140 ms/op
                 getUser·p0.9999: 23.076 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  8.233 ms/op
                 getUser·p0.9999: 22.082 ms/op
                 getUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297791
  mean =      3.221 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14848 
    [ 2.500,  5.000) = 275438 
    [ 5.000,  7.500) = 6712 
    [ 7.500, 10.000) = 407 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     15.188 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 9.261 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.012 ms/op
Iteration   1: 3.769 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.819 ms/op
                 listUser·p0.9999: 23.465 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   2: 3.739 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  12.730 ms/op
                 listUser·p0.9999: 14.320 ms/op
                 listUser·p1.00:   14.975 ms/op

Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  14.520 ms/op
                 listUser·p0.9999: 16.204 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253238
  mean =      3.790 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 245833 
    [ 5.000,  7.500) = 5001 
    [ 7.500, 10.000) = 1640 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.066 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     13.768 ms/op
     p(99.9900) =     22.796 ms/op
     p(99.9990) =     23.853 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.697 ± 4.693  ops/ms
ClientPb.existUser                       thrpt       3  10.537 ± 2.716  ops/ms
ClientPb.getUser                         thrpt       3   9.503 ± 4.688  ops/ms
ClientPb.listUser                        thrpt       3   8.550 ± 1.388  ops/ms
ClientPb.createUser                       avgt       3   3.207 ± 1.109   ms/op
ClientPb.existUser                        avgt       3   3.054 ± 1.015   ms/op
ClientPb.getUser                          avgt       3   3.271 ± 0.673   ms/op
ClientPb.listUser                         avgt       3   3.781 ± 0.779   ms/op
ClientPb.createUser                     sample  296659   3.236 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.257           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.543           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.538           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.532           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.621           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.510           ms/op
ClientPb.existUser                      sample  305183   3.145 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.350           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.823           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.266           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.823           ms/op
ClientPb.getUser                        sample  297791   3.221 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.075           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.149           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.882           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.188           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.479           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.790           ms/op
ClientPb.listUser                       sample  253238   3.790 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.066           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.116           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.768           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.796           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.953           ms/op
