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
# Warmup Iteration   1: 3.909 ops/ms
# Warmup Iteration   2: 8.896 ops/ms
# Warmup Iteration   3: 9.786 ops/ms
Iteration   1: 10.196 ops/ms
Iteration   2: 10.012 ops/ms
Iteration   3: 9.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.992 ±(99.9%) 3.907 ops/ms [Average]
  (min, avg, max) = (9.769, 9.992, 10.196), stdev = 0.214
  CI (99.9%): [6.085, 13.899] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.538 ops/ms
# Warmup Iteration   2: 10.491 ops/ms
# Warmup Iteration   3: 10.402 ops/ms
Iteration   1: 10.547 ops/ms
Iteration   2: 10.356 ops/ms
Iteration   3: 10.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.508 ±(99.9%) 2.498 ops/ms [Average]
  (min, avg, max) = (10.356, 10.508, 10.622), stdev = 0.137
  CI (99.9%): [8.010, 13.007] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.471 ops/ms
# Warmup Iteration   2: 9.874 ops/ms
# Warmup Iteration   3: 10.163 ops/ms
Iteration   1: 9.966 ops/ms
Iteration   2: 10.089 ops/ms
Iteration   3: 9.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.956 ±(99.9%) 2.516 ops/ms [Average]
  (min, avg, max) = (9.814, 9.956, 10.089), stdev = 0.138
  CI (99.9%): [7.441, 12.472] (assumes normal distribution)


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
# Warmup Iteration   1: 5.502 ops/ms
# Warmup Iteration   2: 7.458 ops/ms
# Warmup Iteration   3: 7.620 ops/ms
Iteration   1: 7.741 ops/ms
Iteration   2: 7.667 ops/ms
Iteration   3: 7.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.705 ±(99.9%) 0.671 ops/ms [Average]
  (min, avg, max) = (7.667, 7.705, 7.741), stdev = 0.037
  CI (99.9%): [7.033, 8.376] (assumes normal distribution)


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
# Warmup Iteration   1: 4.459 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.003 ms/op
Iteration   1: 3.170 ±(99.9%) 0.005 ms/op
Iteration   2: 3.240 ±(99.9%) 0.002 ms/op
Iteration   3: 3.260 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.223 ±(99.9%) 0.868 ms/op [Average]
  (min, avg, max) = (3.170, 3.223, 3.260), stdev = 0.048
  CI (99.9%): [2.355, 4.092] (assumes normal distribution)


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.002 ms/op
Iteration   1: 3.118 ±(99.9%) 0.002 ms/op
Iteration   2: 3.103 ±(99.9%) 0.001 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.093 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.058, 3.093, 3.118), stdev = 0.031
  CI (99.9%): [2.522, 3.664] (assumes normal distribution)


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
# Warmup Iteration   1: 4.333 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.002 ms/op
Iteration   1: 3.323 ±(99.9%) 0.002 ms/op
Iteration   2: 3.271 ±(99.9%) 0.002 ms/op
Iteration   3: 3.206 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.267 ±(99.9%) 1.073 ms/op [Average]
  (min, avg, max) = (3.206, 3.267, 3.323), stdev = 0.059
  CI (99.9%): [2.193, 4.340] (assumes normal distribution)


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
# Warmup Iteration   1: 5.800 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.008 ms/op
Iteration   1: 4.129 ±(99.9%) 0.031 ms/op
Iteration   2: 4.172 ±(99.9%) 0.020 ms/op
Iteration   3: 4.211 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.171 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (4.129, 4.171, 4.211), stdev = 0.041
  CI (99.9%): [3.425, 4.917] (assumes normal distribution)


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
# Warmup Iteration   1: 4.626 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.007 ms/op
Iteration   1: 3.255 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  8.134 ms/op
                 createUser·p0.9999: 13.978 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   2: 3.233 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  11.438 ms/op
                 createUser·p0.9999: 15.574 ms/op
                 createUser·p1.00:   16.056 ms/op

Iteration   3: 3.276 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.310 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.739 ms/op
                 createUser·p0.9999: 27.107 ms/op
                 createUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294799
  mean =      3.255 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18021 
    [ 2.500,  5.000) = 275209 
    [ 5.000,  7.500) = 1093 
    [ 7.500, 10.000) = 181 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =     10.030 ms/op
     p(99.9900) =     26.395 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.559 ms/op
                 existUser·p0.9999: 13.019 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.989 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  8.127 ms/op
                 existUser·p0.9999: 15.794 ms/op
                 existUser·p1.00:   16.269 ms/op

Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.571 ms/op
                 existUser·p0.9999: 25.068 ms/op
                 existUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316599
  mean =      3.032 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39817 
    [ 2.500,  5.000) = 275862 
    [ 5.000,  7.500) = 622 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.376 ms/op
     p(99.9900) =     24.434 ms/op
     p(99.9990) =     25.876 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 4.514 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.007 ms/op
Iteration   1: 3.219 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  7.799 ms/op
                 getUser·p0.9999: 14.751 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   2: 3.287 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.532 ms/op
                 getUser·p0.9999: 16.156 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   3: 3.237 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.236 ms/op
                 getUser·p0.9999: 17.079 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 295559
  mean =      3.247 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 453 
    [ 1.250,  2.500) = 16362 
    [ 2.500,  3.750) = 225048 
    [ 3.750,  5.000) = 52439 
    [ 5.000,  6.250) = 637 
    [ 6.250,  7.500) = 309 
    [ 7.500,  8.750) = 97 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 66 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     16.218 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 5.866 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.012 ms/op
Iteration   1: 4.263 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 25.068 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 4.156 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  13.960 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 4.213 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  19.826 ms/op
                 listUser·p0.9999: 31.038 ms/op
                 listUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 227916
  mean =      4.210 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1029 
    [ 2.500,  5.000) = 195592 
    [ 5.000,  7.500) = 29499 
    [ 7.500, 10.000) = 1248 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.843 ms/op
     p(99.9900) =     29.643 ms/op
     p(99.9990) =     32.586 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.992 ± 3.907  ops/ms
ClientGrpc.existUser                       thrpt       3  10.508 ± 2.498  ops/ms
ClientGrpc.getUser                         thrpt       3   9.956 ± 2.516  ops/ms
ClientGrpc.listUser                        thrpt       3   7.705 ± 0.671  ops/ms
ClientGrpc.createUser                       avgt       3   3.223 ± 0.868   ms/op
ClientGrpc.existUser                        avgt       3   3.093 ± 0.571   ms/op
ClientGrpc.getUser                          avgt       3   3.267 ± 1.073   ms/op
ClientGrpc.listUser                         avgt       3   4.171 ± 0.746   ms/op
ClientGrpc.createUser                     sample  294799   3.255 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.310           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.219           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.170           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.030           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.395           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.361           ms/op
ClientGrpc.existUser                      sample  316599   3.032 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.627           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.376           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.434           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.214           ms/op
ClientGrpc.getUser                        sample  295559   3.247 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.794           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.228           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.129           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.594           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.218           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.531           ms/op
ClientGrpc.listUser                       sample  227916   4.210 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.196           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.030           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.843           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.643           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.899           ms/op
