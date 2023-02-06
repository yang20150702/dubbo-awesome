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
# Warmup Iteration   1: 2.765 ops/ms
# Warmup Iteration   2: 6.562 ops/ms
# Warmup Iteration   3: 9.004 ops/ms
Iteration   1: 9.592 ops/ms
Iteration   2: 10.350 ops/ms
Iteration   3: 10.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.073 ±(99.9%) 7.623 ops/ms [Average]
  (min, avg, max) = (9.592, 10.073, 10.350), stdev = 0.418
  CI (99.9%): [2.449, 17.696] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ops/ms
# Warmup Iteration   2: 9.879 ops/ms
# Warmup Iteration   3: 10.391 ops/ms
Iteration   1: 10.464 ops/ms
Iteration   2: 10.116 ops/ms
Iteration   3: 10.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.406 ±(99.9%) 4.828 ops/ms [Average]
  (min, avg, max) = (10.116, 10.406, 10.636), stdev = 0.265
  CI (99.9%): [5.577, 15.234] (assumes normal distribution)


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
# Warmup Iteration   1: 3.811 ops/ms
# Warmup Iteration   2: 9.254 ops/ms
# Warmup Iteration   3: 9.577 ops/ms
Iteration   1: 9.800 ops/ms
Iteration   2: 9.769 ops/ms
Iteration   3: 9.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.810 ±(99.9%) 0.856 ops/ms [Average]
  (min, avg, max) = (9.769, 9.810, 9.861), stdev = 0.047
  CI (99.9%): [8.954, 10.665] (assumes normal distribution)


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
# Warmup Iteration   1: 3.701 ops/ms
# Warmup Iteration   2: 7.399 ops/ms
# Warmup Iteration   3: 8.456 ops/ms
Iteration   1: 8.367 ops/ms
Iteration   2: 8.669 ops/ms
Iteration   3: 8.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.555 ±(99.9%) 2.989 ops/ms [Average]
  (min, avg, max) = (8.367, 8.555, 8.669), stdev = 0.164
  CI (99.9%): [5.566, 11.545] (assumes normal distribution)


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
# Warmup Iteration   1: 8.963 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.005 ms/op
Iteration   1: 3.236 ±(99.9%) 0.009 ms/op
Iteration   2: 3.114 ±(99.9%) 0.009 ms/op
Iteration   3: 3.212 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.187 ±(99.9%) 1.175 ms/op [Average]
  (min, avg, max) = (3.114, 3.187, 3.236), stdev = 0.064
  CI (99.9%): [2.013, 4.362] (assumes normal distribution)


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
# Warmup Iteration   1: 7.095 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
Iteration   1: 3.085 ±(99.9%) 0.007 ms/op
Iteration   2: 3.022 ±(99.9%) 0.002 ms/op
Iteration   3: 3.058 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.055 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (3.022, 3.055, 3.085), stdev = 0.032
  CI (99.9%): [2.479, 3.632] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.251 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.008 ms/op
Iteration   1: 3.036 ±(99.9%) 0.005 ms/op
Iteration   2: 3.329 ±(99.9%) 0.004 ms/op
Iteration   3: 3.246 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.204 ±(99.9%) 2.754 ms/op [Average]
  (min, avg, max) = (3.036, 3.204, 3.329), stdev = 0.151
  CI (99.9%): [0.450, 5.958] (assumes normal distribution)


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
# Warmup Iteration   1: 8.802 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.003 ms/op
Iteration   1: 3.657 ±(99.9%) 0.009 ms/op
Iteration   2: 3.642 ±(99.9%) 0.011 ms/op
Iteration   3: 3.645 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.648 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (3.642, 3.648, 3.657), stdev = 0.008
  CI (99.9%): [3.500, 3.796] (assumes normal distribution)


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
# Warmup Iteration   1: 8.159 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.010 ms/op
Iteration   1: 3.164 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  12.154 ms/op
                 createUser·p0.9999: 19.562 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 3.264 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  19.205 ms/op
                 createUser·p0.9999: 22.289 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.129 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  11.601 ms/op
                 createUser·p0.9999: 20.447 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301255
  mean =      3.185 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24414 
    [ 2.500,  5.000) = 271904 
    [ 5.000,  7.500) = 4122 
    [ 7.500, 10.000) = 339 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     21.393 ms/op
     p(99.9990) =     23.819 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 7.322 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.008 ms/op
Iteration   1: 3.013 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 20.054 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.440 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  17.760 ms/op
                 existUser·p0.9999: 22.593 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  8.676 ms/op
                 existUser·p0.9999: 20.069 ms/op
                 existUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316741
  mean =      3.028 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21446 
    [ 2.500,  5.000) = 290720 
    [ 5.000,  7.500) = 3987 
    [ 7.500, 10.000) = 258 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.232 ms/op
     p(95.0000) =      3.453 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     23.353 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 7.060 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.011 ms/op
Iteration   1: 3.243 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  16.685 ms/op
                 getUser·p0.9999: 18.682 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  13.330 ms/op
                 getUser·p0.9999: 21.742 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 19.460 ms/op
                 getUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297172
  mean =      3.228 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22412 
    [ 2.500,  5.000) = 266691 
    [ 5.000,  7.500) = 7163 
    [ 7.500, 10.000) = 519 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     15.622 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     22.154 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 8.691 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.012 ms/op
Iteration   1: 3.726 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.352 ms/op
                 listUser·p0.9999: 17.623 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   2: 3.723 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 17.793 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   3: 3.614 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.748 ms/op
                 listUser·p0.95:   4.002 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  11.813 ms/op
                 listUser·p0.9999: 15.417 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260158
  mean =      3.687 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 76 
    [ 2.500,  3.750) = 207930 
    [ 3.750,  5.000) = 46307 
    [ 5.000,  6.250) = 2434 
    [ 6.250,  7.500) = 1922 
    [ 7.500,  8.750) = 639 
    [ 8.750, 10.000) = 165 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 200 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 120 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 69 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     18.199 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.073 ± 7.623  ops/ms
ClientPb.existUser                       thrpt       3  10.406 ± 4.828  ops/ms
ClientPb.getUser                         thrpt       3   9.810 ± 0.856  ops/ms
ClientPb.listUser                        thrpt       3   8.555 ± 2.989  ops/ms
ClientPb.createUser                       avgt       3   3.187 ± 1.175   ms/op
ClientPb.existUser                        avgt       3   3.055 ± 0.576   ms/op
ClientPb.getUser                          avgt       3   3.204 ± 2.754   ms/op
ClientPb.listUser                         avgt       3   3.648 ± 0.148   ms/op
ClientPb.createUser                     sample  301255   3.185 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.313           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.473           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.401           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.393           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.281           ms/op
ClientPb.existUser                      sample  316741   3.028 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.173           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.889           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.495           ms/op
ClientPb.getUser                        sample  297172   3.228 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.812           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.622           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.349           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.381           ms/op
ClientPb.listUser                       sample  260158   3.687 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.079           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.170           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.529           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.812           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.727           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.317           ms/op
