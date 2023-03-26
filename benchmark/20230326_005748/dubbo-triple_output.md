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
# Warmup Iteration   1: 2.645 ops/ms
# Warmup Iteration   2: 6.599 ops/ms
# Warmup Iteration   3: 9.323 ops/ms
Iteration   1: 10.167 ops/ms
Iteration   2: 10.149 ops/ms
Iteration   3: 10.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.137 ±(99.9%) 0.658 ops/ms [Average]
  (min, avg, max) = (10.097, 10.137, 10.167), stdev = 0.036
  CI (99.9%): [9.479, 10.796] (assumes normal distribution)


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
# Warmup Iteration   1: 3.531 ops/ms
# Warmup Iteration   2: 9.209 ops/ms
# Warmup Iteration   3: 10.407 ops/ms
Iteration   1: 9.967 ops/ms
Iteration   2: 10.021 ops/ms
Iteration   3: 10.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.114 ±(99.9%) 3.837 ops/ms [Average]
  (min, avg, max) = (9.967, 10.114, 10.355), stdev = 0.210
  CI (99.9%): [6.277, 13.952] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.298 ops/ms
# Warmup Iteration   2: 9.131 ops/ms
# Warmup Iteration   3: 9.743 ops/ms
Iteration   1: 10.240 ops/ms
Iteration   2: 10.154 ops/ms
Iteration   3: 10.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.288 ±(99.9%) 2.977 ops/ms [Average]
  (min, avg, max) = (10.154, 10.288, 10.469), stdev = 0.163
  CI (99.9%): [7.311, 13.265] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.676 ops/ms
# Warmup Iteration   2: 8.038 ops/ms
# Warmup Iteration   3: 8.578 ops/ms
Iteration   1: 8.583 ops/ms
Iteration   2: 8.802 ops/ms
Iteration   3: 8.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.782 ±(99.9%) 3.459 ops/ms [Average]
  (min, avg, max) = (8.583, 8.782, 8.960), stdev = 0.190
  CI (99.9%): [5.322, 12.241] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.542 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.007 ms/op
Iteration   1: 3.309 ±(99.9%) 0.005 ms/op
Iteration   2: 3.167 ±(99.9%) 0.002 ms/op
Iteration   3: 3.179 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.219 ±(99.9%) 1.439 ms/op [Average]
  (min, avg, max) = (3.167, 3.219, 3.309), stdev = 0.079
  CI (99.9%): [1.779, 4.658] (assumes normal distribution)


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
# Warmup Iteration   1: 6.906 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.005 ms/op
Iteration   1: 3.056 ±(99.9%) 0.004 ms/op
Iteration   2: 3.121 ±(99.9%) 0.004 ms/op
Iteration   3: 3.146 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.108 ±(99.9%) 0.849 ms/op [Average]
  (min, avg, max) = (3.056, 3.108, 3.146), stdev = 0.047
  CI (99.9%): [2.259, 3.957] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 6.915 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.383 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.004 ms/op
Iteration   1: 3.279 ±(99.9%) 0.002 ms/op
Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
Iteration   3: 3.220 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.193 ±(99.9%) 1.857 ms/op [Average]
  (min, avg, max) = (3.081, 3.193, 3.279), stdev = 0.102
  CI (99.9%): [1.336, 5.051] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.468 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.007 ms/op
Iteration   1: 3.714 ±(99.9%) 0.008 ms/op
Iteration   2: 3.704 ±(99.9%) 0.007 ms/op
Iteration   3: 3.715 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.711 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (3.704, 3.711, 3.715), stdev = 0.006
  CI (99.9%): [3.594, 3.827] (assumes normal distribution)


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
# Warmup Iteration   1: 7.789 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.009 ms/op
Iteration   1: 3.204 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.460 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  18.350 ms/op
                 createUser·p0.9999: 21.247 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  9.290 ms/op
                 createUser·p0.9999: 27.460 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 3.243 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  14.065 ms/op
                 createUser·p0.9999: 21.332 ms/op
                 createUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299599
  mean =      3.204 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20762 
    [ 2.500,  5.000) = 271739 
    [ 5.000,  7.500) = 6075 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     16.027 ms/op
     p(99.9900) =     26.053 ms/op
     p(99.9990) =     27.952 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.802 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.008 ms/op
Iteration   1: 3.028 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  11.146 ms/op
                 existUser·p0.9999: 21.496 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.314 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 19.242 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316668
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19485 
    [ 2.500,  5.000) = 293161 
    [ 5.000,  7.500) = 3293 
    [ 7.500, 10.000) = 311 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.232 ms/op
     p(95.0000) =      3.432 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =     11.867 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     23.828 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 8.524 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.010 ms/op
Iteration   1: 3.175 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  15.291 ms/op
                 getUser·p0.9999: 23.319 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.070 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.314 ms/op
                 getUser·p0.95:   3.518 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  12.891 ms/op
                 getUser·p0.9999: 24.975 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.265 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   5.910 ms/op
                 getUser·p0.999:  10.524 ms/op
                 getUser·p0.9999: 21.936 ms/op
                 getUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302587
  mean =      3.168 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13617 
    [ 2.500,  5.000) = 283476 
    [ 5.000,  7.500) = 4569 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     23.617 ms/op
     p(99.9990) =     25.360 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 8.169 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.010 ms/op
Iteration   1: 3.703 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  15.214 ms/op
                 listUser·p0.9999: 21.311 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   2: 3.669 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.564 ms/op
                 listUser·p0.999:  12.826 ms/op
                 listUser·p0.9999: 17.606 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.641 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.141 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  13.677 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 261307
  mean =      3.671 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 254924 
    [ 5.000,  7.500) = 4711 
    [ 7.500, 10.000) = 978 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     19.882 ms/op
     p(99.9990) =     22.000 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.137 ± 0.658  ops/ms
ClientPb.existUser                       thrpt       3  10.114 ± 3.837  ops/ms
ClientPb.getUser                         thrpt       3  10.288 ± 2.977  ops/ms
ClientPb.listUser                        thrpt       3   8.782 ± 3.459  ops/ms
ClientPb.createUser                       avgt       3   3.219 ± 1.439   ms/op
ClientPb.existUser                        avgt       3   3.108 ± 0.849   ms/op
ClientPb.getUser                          avgt       3   3.193 ± 1.857   ms/op
ClientPb.listUser                         avgt       3   3.711 ± 0.116   ms/op
ClientPb.createUser                     sample  299599   3.204 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.460           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.027           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.053           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.115           ms/op
ClientPb.existUser                      sample  316668   3.030 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.073           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.867           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.020           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.986           ms/op
ClientPb.getUser                        sample  302587   3.168 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.887           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.800           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.467           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.617           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.559           ms/op
ClientPb.listUser                       sample  261307   3.671 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.153           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.576           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.166           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.545           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.943           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.882           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.381           ms/op
