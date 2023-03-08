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
# Warmup Iteration   1: 2.528 ops/ms
# Warmup Iteration   2: 5.929 ops/ms
# Warmup Iteration   3: 9.161 ops/ms
Iteration   1: 9.765 ops/ms
Iteration   2: 10.259 ops/ms
Iteration   3: 10.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.018 ±(99.9%) 4.513 ops/ms [Average]
  (min, avg, max) = (9.765, 10.018, 10.259), stdev = 0.247
  CI (99.9%): [5.505, 14.531] (assumes normal distribution)


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
# Warmup Iteration   1: 3.371 ops/ms
# Warmup Iteration   2: 9.764 ops/ms
# Warmup Iteration   3: 10.368 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.115 ops/ms
Iteration   3: 10.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.348 ±(99.9%) 4.588 ops/ms [Average]
  (min, avg, max) = (10.115, 10.348, 10.614), stdev = 0.252
  CI (99.9%): [5.759, 14.936] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.059 ops/ms
# Warmup Iteration   2: 9.351 ops/ms
# Warmup Iteration   3: 9.777 ops/ms
Iteration   1: 10.128 ops/ms
Iteration   2: 10.092 ops/ms
Iteration   3: 9.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.951 ±(99.9%) 5.046 ops/ms [Average]
  (min, avg, max) = (9.632, 9.951, 10.128), stdev = 0.277
  CI (99.9%): [4.905, 14.997] (assumes normal distribution)


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
# Warmup Iteration   1: 3.540 ops/ms
# Warmup Iteration   2: 7.537 ops/ms
# Warmup Iteration   3: 8.454 ops/ms
Iteration   1: 8.505 ops/ms
Iteration   2: 8.778 ops/ms
Iteration   3: 8.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.685 ±(99.9%) 2.840 ops/ms [Average]
  (min, avg, max) = (8.505, 8.685, 8.778), stdev = 0.156
  CI (99.9%): [5.845, 11.525] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.309 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.008 ms/op
Iteration   1: 3.151 ±(99.9%) 0.003 ms/op
Iteration   2: 3.286 ±(99.9%) 0.007 ms/op
Iteration   3: 3.195 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.211 ±(99.9%) 1.263 ms/op [Average]
  (min, avg, max) = (3.151, 3.211, 3.286), stdev = 0.069
  CI (99.9%): [1.948, 4.473] (assumes normal distribution)


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
# Warmup Iteration   1: 7.334 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.006 ms/op
Iteration   1: 3.040 ±(99.9%) 0.003 ms/op
Iteration   2: 3.092 ±(99.9%) 0.008 ms/op
Iteration   3: 3.061 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.064 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (3.040, 3.064, 3.092), stdev = 0.026
  CI (99.9%): [2.589, 3.540] (assumes normal distribution)


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
# Warmup Iteration   1: 7.076 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.394 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.002 ms/op
Iteration   1: 3.072 ±(99.9%) 0.004 ms/op
Iteration   2: 3.137 ±(99.9%) 0.003 ms/op
Iteration   3: 3.147 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.119 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (3.072, 3.119, 3.147), stdev = 0.041
  CI (99.9%): [2.375, 3.862] (assumes normal distribution)


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
# Warmup Iteration   1: 8.497 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.005 ms/op
Iteration   1: 3.575 ±(99.9%) 0.008 ms/op
Iteration   2: 3.712 ±(99.9%) 0.010 ms/op
Iteration   3: 3.694 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.660 ±(99.9%) 1.355 ms/op [Average]
  (min, avg, max) = (3.575, 3.660, 3.712), stdev = 0.074
  CI (99.9%): [2.305, 5.015] (assumes normal distribution)


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
# Warmup Iteration   1: 7.828 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.010 ms/op
Iteration   1: 3.251 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.957 ms/op
                 createUser·p0.999:  13.959 ms/op
                 createUser·p0.9999: 18.929 ms/op
                 createUser·p1.00:   21.398 ms/op

Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  12.599 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  17.498 ms/op
                 createUser·p0.9999: 21.677 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305655
  mean =      3.139 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23517 
    [ 2.500,  5.000) = 277614 
    [ 5.000,  7.500) = 3543 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     23.524 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 8.375 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.008 ms/op
Iteration   1: 3.475 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  15.564 ms/op
                 existUser·p0.9999: 22.276 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  12.093 ms/op
                 existUser·p0.9999: 22.971 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.251 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.441 ms/op
                 existUser·p0.999:  11.497 ms/op
                 existUser·p0.9999: 28.159 ms/op
                 existUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290185
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14396 
    [ 2.500,  5.000) = 268345 
    [ 5.000,  7.500) = 6497 
    [ 7.500, 10.000) = 539 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     13.039 ms/op
     p(99.9900) =     26.467 ms/op
     p(99.9990) =     28.914 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.693 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.010 ms/op
Iteration   1: 3.337 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  18.816 ms/op
                 getUser·p0.9999: 21.804 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   2: 3.281 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  10.472 ms/op
                 getUser·p0.9999: 27.370 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 3.358 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.839 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  20.740 ms/op
                 getUser·p0.9999: 24.101 ms/op
                 getUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288307
  mean =      3.325 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4158 
    [ 2.500,  5.000) = 276858 
    [ 5.000,  7.500) = 5874 
    [ 7.500, 10.000) = 903 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     27.857 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.748 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.896 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.013 ms/op
Iteration   1: 3.847 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  15.545 ms/op
                 listUser·p0.9999: 24.434 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   2: 3.994 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  14.532 ms/op
                 listUser·p0.9999: 15.221 ms/op
                 listUser·p1.00:   16.073 ms/op

Iteration   3: 3.793 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247551
  mean =      3.876 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 239352 
    [ 5.000,  7.500) = 6008 
    [ 7.500, 10.000) = 1476 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     23.781 ms/op
     p(99.9990) =     24.691 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.018 ± 4.513  ops/ms
ClientPb.existUser                       thrpt       3  10.348 ± 4.588  ops/ms
ClientPb.getUser                         thrpt       3   9.951 ± 5.046  ops/ms
ClientPb.listUser                        thrpt       3   8.685 ± 2.840  ops/ms
ClientPb.createUser                       avgt       3   3.211 ± 1.263   ms/op
ClientPb.existUser                        avgt       3   3.064 ± 0.476   ms/op
ClientPb.getUser                          avgt       3   3.119 ± 0.744   ms/op
ClientPb.listUser                         avgt       3   3.660 ± 1.355   ms/op
ClientPb.createUser                     sample  305655   3.139 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.057           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.465           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.531           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.889           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.084           ms/op
ClientPb.existUser                      sample  290185   3.305 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.841           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.054           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.039           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.467           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.983           ms/op
ClientPb.getUser                        sample  288307   3.325 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.487           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.809           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.542           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.017           ms/op
ClientPb.listUser                       sample  247551   3.876 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.556           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.764           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.781           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.002           ms/op
