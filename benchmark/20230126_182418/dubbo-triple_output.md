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
# Warmup Iteration   1: 2.562 ops/ms
# Warmup Iteration   2: 6.232 ops/ms
# Warmup Iteration   3: 9.335 ops/ms
Iteration   1: 9.678 ops/ms
Iteration   2: 10.101 ops/ms
Iteration   3: 10.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.958 ±(99.9%) 4.429 ops/ms [Average]
  (min, avg, max) = (9.678, 9.958, 10.101), stdev = 0.243
  CI (99.9%): [5.529, 14.387] (assumes normal distribution)


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
# Warmup Iteration   1: 3.687 ops/ms
# Warmup Iteration   2: 8.969 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 10.205 ops/ms
Iteration   2: 10.887 ops/ms
Iteration   3: 10.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.411 ±(99.9%) 7.541 ops/ms [Average]
  (min, avg, max) = (10.141, 10.411, 10.887), stdev = 0.413
  CI (99.9%): [2.870, 17.952] (assumes normal distribution)


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
# Warmup Iteration   1: 3.642 ops/ms
# Warmup Iteration   2: 9.018 ops/ms
# Warmup Iteration   3: 9.857 ops/ms
Iteration   1: 10.273 ops/ms
Iteration   2: 10.220 ops/ms
Iteration   3: 10.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.334 ±(99.9%) 2.783 ops/ms [Average]
  (min, avg, max) = (10.220, 10.334, 10.507), stdev = 0.153
  CI (99.9%): [7.551, 13.116] (assumes normal distribution)


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
# Warmup Iteration   1: 3.189 ops/ms
# Warmup Iteration   2: 7.811 ops/ms
# Warmup Iteration   3: 8.633 ops/ms
Iteration   1: 8.679 ops/ms
Iteration   2: 8.803 ops/ms
Iteration   3: 8.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.682 ±(99.9%) 2.192 ops/ms [Average]
  (min, avg, max) = (8.563, 8.682, 8.803), stdev = 0.120
  CI (99.9%): [6.489, 10.874] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.921 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.002 ms/op
Iteration   1: 3.116 ±(99.9%) 0.004 ms/op
Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
Iteration   3: 3.113 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.134 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.113, 3.134, 3.172), stdev = 0.033
  CI (99.9%): [2.533, 3.735] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.571 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.438 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.002 ms/op
Iteration   1: 3.051 ±(99.9%) 0.003 ms/op
Iteration   2: 3.051 ±(99.9%) 0.003 ms/op
Iteration   3: 3.115 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.073 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (3.051, 3.073, 3.115), stdev = 0.037
  CI (99.9%): [2.399, 3.746] (assumes normal distribution)


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
# Warmup Iteration   1: 6.953 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.005 ms/op
Iteration   1: 3.223 ±(99.9%) 0.006 ms/op
Iteration   2: 3.354 ±(99.9%) 0.004 ms/op
Iteration   3: 3.201 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.260 ±(99.9%) 1.512 ms/op [Average]
  (min, avg, max) = (3.201, 3.260, 3.354), stdev = 0.083
  CI (99.9%): [1.748, 4.771] (assumes normal distribution)


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
# Warmup Iteration   1: 8.917 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.006 ms/op
Iteration   1: 3.682 ±(99.9%) 0.007 ms/op
Iteration   2: 3.800 ±(99.9%) 0.006 ms/op
Iteration   3: 3.702 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.728 ±(99.9%) 1.151 ms/op [Average]
  (min, avg, max) = (3.682, 3.728, 3.800), stdev = 0.063
  CI (99.9%): [2.577, 4.879] (assumes normal distribution)


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
# Warmup Iteration   1: 8.421 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
Iteration   1: 3.306 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.230 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  13.497 ms/op
                 createUser·p0.9999: 23.931 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   2: 3.344 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  17.647 ms/op
                 createUser·p0.9999: 22.020 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   3: 3.128 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  10.256 ms/op
                 createUser·p0.9999: 18.907 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294573
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21321 
    [ 2.500,  5.000) = 267393 
    [ 5.000,  7.500) = 5049 
    [ 7.500, 10.000) = 468 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     11.815 ms/op
     p(99.9900) =     22.464 ms/op
     p(99.9990) =     24.385 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 6.423 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.008 ms/op
Iteration   1: 3.018 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.138 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  14.052 ms/op
                 existUser·p0.9999: 18.015 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 2.958 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.318 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.086 ms/op
                 existUser·p0.9999: 19.228 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  8.678 ms/op
                 existUser·p0.9999: 19.347 ms/op
                 existUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 319900
  mean =      2.999 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15033 
    [ 2.500,  5.000) = 301103 
    [ 5.000,  7.500) = 3129 
    [ 7.500, 10.000) = 282 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.195 ms/op
     p(95.0000) =      3.379 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     11.887 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     20.107 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 7.119 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.011 ms/op
Iteration   1: 3.164 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.412 ms/op
                 getUser·p0.999:  18.874 ms/op
                 getUser·p0.9999: 25.031 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   2: 3.150 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.485 ms/op
                 getUser·p0.999:  20.021 ms/op
                 getUser·p0.9999: 27.913 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   5.444 ms/op
                 getUser·p0.999:  10.240 ms/op
                 getUser·p0.9999: 22.717 ms/op
                 getUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304416
  mean =      3.152 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19788 
    [ 2.500,  5.000) = 279481 
    [ 5.000,  7.500) = 4253 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     16.148 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     28.703 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 8.685 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.011 ms/op
Iteration   1: 3.785 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  16.283 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 3.738 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.420 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  12.801 ms/op
                 listUser·p0.9999: 15.825 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.656 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.166 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  11.846 ms/op
                 listUser·p0.9999: 13.427 ms/op
                 listUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257725
  mean =      3.725 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 248599 
    [ 5.000,  7.500) = 7147 
    [ 7.500, 10.000) = 1325 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     20.508 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.958 ± 4.429  ops/ms
ClientPb.existUser                       thrpt       3  10.411 ± 7.541  ops/ms
ClientPb.getUser                         thrpt       3  10.334 ± 2.783  ops/ms
ClientPb.listUser                        thrpt       3   8.682 ± 2.192  ops/ms
ClientPb.createUser                       avgt       3   3.134 ± 0.601   ms/op
ClientPb.existUser                        avgt       3   3.073 ± 0.673   ms/op
ClientPb.getUser                          avgt       3   3.260 ± 1.512   ms/op
ClientPb.listUser                         avgt       3   3.728 ± 1.151   ms/op
ClientPb.createUser                     sample  294573   3.256 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.186           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.464           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.510           ms/op
ClientPb.existUser                      sample  319900   2.999 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.161           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.887           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.169           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.283           ms/op
ClientPb.getUser                        sample  304416   3.152 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.913           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.523           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.148           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.756           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.196           ms/op
ClientPb.listUser                       sample  257725   3.725 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.420           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.500           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.202           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.709           ms/op
