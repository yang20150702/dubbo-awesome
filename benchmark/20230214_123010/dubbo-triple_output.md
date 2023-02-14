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
# Warmup Iteration   1: 2.441 ops/ms
# Warmup Iteration   2: 5.697 ops/ms
# Warmup Iteration   3: 9.132 ops/ms
Iteration   1: 9.725 ops/ms
Iteration   2: 9.525 ops/ms
Iteration   3: 9.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.719 ±(99.9%) 3.484 ops/ms [Average]
  (min, avg, max) = (9.525, 9.719, 9.907), stdev = 0.191
  CI (99.9%): [6.235, 13.203] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.151 ops/ms
# Warmup Iteration   2: 8.817 ops/ms
# Warmup Iteration   3: 9.954 ops/ms
Iteration   1: 10.287 ops/ms
Iteration   2: 9.946 ops/ms
Iteration   3: 10.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.087 ±(99.9%) 3.247 ops/ms [Average]
  (min, avg, max) = (9.946, 10.087, 10.287), stdev = 0.178
  CI (99.9%): [6.839, 13.334] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.241 ops/ms
# Warmup Iteration   2: 9.250 ops/ms
# Warmup Iteration   3: 9.459 ops/ms
Iteration   1: 9.756 ops/ms
Iteration   2: 9.980 ops/ms
Iteration   3: 9.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.881 ±(99.9%) 2.082 ops/ms [Average]
  (min, avg, max) = (9.756, 9.881, 9.980), stdev = 0.114
  CI (99.9%): [7.798, 11.963] (assumes normal distribution)


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
# Warmup Iteration   1: 3.397 ops/ms
# Warmup Iteration   2: 7.605 ops/ms
# Warmup Iteration   3: 8.302 ops/ms
Iteration   1: 8.386 ops/ms
Iteration   2: 8.262 ops/ms
Iteration   3: 8.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.413 ±(99.9%) 3.050 ops/ms [Average]
  (min, avg, max) = (8.262, 8.413, 8.593), stdev = 0.167
  CI (99.9%): [5.363, 11.463] (assumes normal distribution)


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
# Warmup Iteration   1: 9.647 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.005 ms/op
Iteration   1: 3.237 ±(99.9%) 0.004 ms/op
Iteration   2: 3.314 ±(99.9%) 0.003 ms/op
Iteration   3: 3.201 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.251 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.201, 3.251, 3.314), stdev = 0.058
  CI (99.9%): [2.197, 4.305] (assumes normal distribution)


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
# Warmup Iteration   1: 6.908 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.002 ms/op
Iteration   1: 3.120 ±(99.9%) 0.007 ms/op
Iteration   2: 3.023 ±(99.9%) 0.008 ms/op
Iteration   3: 3.035 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.060 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (3.023, 3.060, 3.120), stdev = 0.053
  CI (99.9%): [2.101, 4.018] (assumes normal distribution)


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
# Warmup Iteration   1: 8.082 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.444 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.006 ms/op
Iteration   1: 3.245 ±(99.9%) 0.003 ms/op
Iteration   2: 3.171 ±(99.9%) 0.006 ms/op
Iteration   3: 3.418 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.278 ±(99.9%) 2.311 ms/op [Average]
  (min, avg, max) = (3.171, 3.278, 3.418), stdev = 0.127
  CI (99.9%): [0.967, 5.590] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.844 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.005 ms/op
Iteration   1: 3.757 ±(99.9%) 0.010 ms/op
Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
Iteration   3: 3.894 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.798 ±(99.9%) 1.522 ms/op [Average]
  (min, avg, max) = (3.744, 3.798, 3.894), stdev = 0.083
  CI (99.9%): [2.276, 5.320] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.625 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.009 ms/op
Iteration   1: 3.295 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  20.869 ms/op
                 createUser·p0.9999: 25.077 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  9.883 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   3: 3.338 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  14.713 ms/op
                 createUser·p0.9999: 27.034 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292813
  mean =      3.277 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18961 
    [ 2.500,  5.000) = 267097 
    [ 5.000,  7.500) = 5698 
    [ 7.500, 10.000) = 593 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     16.518 ms/op
     p(99.9900) =     26.533 ms/op
     p(99.9990) =     27.497 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 7.337 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
Iteration   1: 3.236 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  13.999 ms/op
                 existUser·p0.9999: 19.767 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   2: 3.244 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  19.530 ms/op
                 existUser·p0.9999: 22.844 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   3: 3.110 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  16.351 ms/op
                 existUser·p0.9999: 28.883 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300208
  mean =      3.195 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16230 
    [ 2.500,  5.000) = 278125 
    [ 5.000,  7.500) = 4731 
    [ 7.500, 10.000) = 470 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     17.393 ms/op
     p(99.9900) =     27.391 ms/op
     p(99.9990) =     29.491 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 7.848 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.010 ms/op
Iteration   1: 3.258 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  16.208 ms/op
                 getUser·p0.9999: 47.514 ms/op
                 getUser·p1.00:   48.234 ms/op

Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  20.251 ms/op
                 getUser·p0.9999: 27.793 ms/op
                 getUser·p1.00:   29.426 ms/op

Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  14.671 ms/op
                 getUser·p0.9999: 21.006 ms/op
                 getUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300281
  mean =      3.193 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 293452 
    [ 5.000, 10.000) = 6391 
    [10.000, 15.000) = 116 
    [15.000, 20.000) = 117 
    [20.000, 25.000) = 141 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     16.379 ms/op
     p(99.9900) =     44.694 ms/op
     p(99.9990) =     47.776 ms/op
     p(99.9999) =     48.234 ms/op
    p(100.0000) =     48.234 ms/op


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
# Warmup Iteration   1: 9.151 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.011 ms/op
Iteration   1: 3.778 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.978 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.003 ms/op
                 listUser·p0.999:  18.138 ms/op
                 listUser·p0.9999: 21.549 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   2: 3.808 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  13.238 ms/op
                 listUser·p0.9999: 15.487 ms/op
                 listUser·p1.00:   15.876 ms/op

Iteration   3: 3.759 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253524
  mean =      3.781 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 243213 
    [ 5.000,  7.500) = 8437 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.978 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.827 ms/op
     p(99.9900) =     20.436 ms/op
     p(99.9990) =     27.304 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.719 ± 3.484  ops/ms
ClientPb.existUser                       thrpt       3  10.087 ± 3.247  ops/ms
ClientPb.getUser                         thrpt       3   9.881 ± 2.082  ops/ms
ClientPb.listUser                        thrpt       3   8.413 ± 3.050  ops/ms
ClientPb.createUser                       avgt       3   3.251 ± 1.054   ms/op
ClientPb.existUser                        avgt       3   3.060 ± 0.958   ms/op
ClientPb.getUser                          avgt       3   3.278 ± 2.311   ms/op
ClientPb.listUser                         avgt       3   3.798 ± 1.522   ms/op
ClientPb.createUser                     sample  292813   3.277 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.972           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.067           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.518           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.533           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.689           ms/op
ClientPb.existUser                      sample  300208   3.195 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.245           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.393           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.391           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.590           ms/op
ClientPb.getUser                        sample  300281   3.193 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.032           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.490           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.379           ms/op
ClientPb.getUser:getUser·p0.9999        sample          44.694           ms/op
ClientPb.getUser:getUser·p1.00          sample          48.234           ms/op
ClientPb.listUser                       sample  253524   3.781 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.978           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.827           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.436           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.623           ms/op
