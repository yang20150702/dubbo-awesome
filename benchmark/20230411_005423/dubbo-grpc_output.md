# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.441 ops/ms
# Warmup Iteration   2: 8.944 ops/ms
# Warmup Iteration   3: 10.067 ops/ms
Iteration   1: 10.686 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.589 ±(99.9%) 2.136 ops/ms [Average]
  (min, avg, max) = (10.459, 10.589, 10.686), stdev = 0.117
  CI (99.9%): [8.453, 12.725] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.468 ops/ms
# Warmup Iteration   2: 10.544 ops/ms
# Warmup Iteration   3: 10.910 ops/ms
Iteration   1: 11.207 ops/ms
Iteration   2: 11.036 ops/ms
Iteration   3: 11.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.277 ±(99.9%) 5.170 ops/ms [Average]
  (min, avg, max) = (11.036, 11.277, 11.589), stdev = 0.283
  CI (99.9%): [6.108, 16.447] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.724 ops/ms
# Warmup Iteration   2: 10.245 ops/ms
# Warmup Iteration   3: 10.354 ops/ms
Iteration   1: 10.312 ops/ms
Iteration   2: 10.457 ops/ms
Iteration   3: 10.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.380 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (10.312, 10.380, 10.457), stdev = 0.073
  CI (99.9%): [9.051, 11.709] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.471 ops/ms
# Warmup Iteration   2: 7.521 ops/ms
# Warmup Iteration   3: 7.792 ops/ms
Iteration   1: 7.885 ops/ms
Iteration   2: 7.845 ops/ms
Iteration   3: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.905 ±(99.9%) 1.305 ops/ms [Average]
  (min, avg, max) = (7.845, 7.905, 7.984), stdev = 0.072
  CI (99.9%): [6.600, 9.210] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.704 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.002 ms/op
Iteration   1: 3.037 ±(99.9%) 0.003 ms/op
Iteration   2: 3.085 ±(99.9%) 0.001 ms/op
Iteration   3: 3.045 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.056 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.037, 3.056, 3.085), stdev = 0.026
  CI (99.9%): [2.581, 3.530] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.002 ms/op
Iteration   1: 2.937 ±(99.9%) 0.002 ms/op
Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
Iteration   3: 2.948 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.958 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (2.937, 2.958, 2.990), stdev = 0.028
  CI (99.9%): [2.448, 3.469] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.690 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.005 ms/op
Iteration   1: 3.134 ±(99.9%) 0.003 ms/op
Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
Iteration   3: 3.038 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.076 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.038, 3.076, 3.134), stdev = 0.051
  CI (99.9%): [2.137, 4.015] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.671 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.020 ms/op
Iteration   1: 4.055 ±(99.9%) 0.009 ms/op
Iteration   2: 4.091 ±(99.9%) 0.014 ms/op
Iteration   3: 4.064 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.070 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (4.055, 4.070, 4.091), stdev = 0.019
  CI (99.9%): [3.727, 4.413] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.295 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  9.716 ms/op
                 createUser·p0.9999: 13.220 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.860 ms/op
                 createUser·p0.9999: 21.835 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.127 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316913
  mean =      3.029 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20837 
    [ 2.500,  5.000) = 294735 
    [ 5.000,  7.500) = 926 
    [ 7.500, 10.000) = 204 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.267 ms/op
     p(99.9900) =     21.408 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.005 ms/op
Iteration   1: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  6.742 ms/op
                 existUser·p0.9999: 18.816 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   3: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   3.961 ms/op
                 existUser·p0.999:  6.467 ms/op
                 existUser·p0.9999: 17.855 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327341
  mean =      2.932 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32710 
    [ 2.500,  5.000) = 293506 
    [ 5.000,  7.500) = 833 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      7.075 ms/op
     p(99.9900) =     18.293 ms/op
     p(99.9990) =     19.750 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.209 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.049 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.348 ms/op
                 getUser·p0.9999: 13.296 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  9.518 ms/op
                 getUser·p0.9999: 17.465 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.635 ms/op
                 getUser·p0.9999: 27.740 ms/op
                 getUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314570
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19300 
    [ 2.500,  5.000) = 293373 
    [ 5.000,  7.500) = 1531 
    [ 7.500, 10.000) = 167 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     26.774 ms/op
     p(99.9990) =     28.368 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.935 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.349 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.012 ms/op
Iteration   1: 4.078 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 22.263 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 4.068 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.374 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  14.947 ms/op
                 listUser·p0.9999: 22.712 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 4.083 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  16.674 ms/op
                 listUser·p0.9999: 23.735 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235579
  mean =      4.077 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2013 
    [ 2.500,  5.000) = 208836 
    [ 5.000,  7.500) = 23308 
    [ 7.500, 10.000) = 996 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     15.768 ms/op
     p(99.9900) =     23.393 ms/op
     p(99.9990) =     25.807 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.589 ± 2.136  ops/ms
ClientGrpc.existUser                       thrpt       3  11.277 ± 5.170  ops/ms
ClientGrpc.getUser                         thrpt       3  10.380 ± 1.329  ops/ms
ClientGrpc.listUser                        thrpt       3   7.905 ± 1.305  ops/ms
ClientGrpc.createUser                       avgt       3   3.056 ± 0.475   ms/op
ClientGrpc.existUser                        avgt       3   2.958 ± 0.510   ms/op
ClientGrpc.getUser                          avgt       3   3.076 ± 0.939   ms/op
ClientGrpc.listUser                         avgt       3   4.070 ± 0.343   ms/op
ClientGrpc.createUser                     sample  316913   3.029 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.548           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.267           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.408           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.086           ms/op
ClientGrpc.existUser                      sample  327341   2.932 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.683           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.075           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.293           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.135           ms/op
ClientGrpc.getUser                        sample  314570   3.053 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.935           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.864           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.774           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.508           ms/op
ClientGrpc.listUser                       sample  235579   4.077 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.374           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.920           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.768           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.393           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.919           ms/op
