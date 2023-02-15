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
# Warmup Iteration   1: 4.637 ops/ms
# Warmup Iteration   2: 9.557 ops/ms
# Warmup Iteration   3: 10.258 ops/ms
Iteration   1: 10.411 ops/ms
Iteration   2: 10.356 ops/ms
Iteration   3: 10.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.380 ±(99.9%) 0.515 ops/ms [Average]
  (min, avg, max) = (10.356, 10.380, 10.411), stdev = 0.028
  CI (99.9%): [9.865, 10.895] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.833 ops/ms
# Warmup Iteration   2: 11.018 ops/ms
# Warmup Iteration   3: 10.672 ops/ms
Iteration   1: 10.525 ops/ms
Iteration   2: 11.120 ops/ms
Iteration   3: 10.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.783 ±(99.9%) 5.561 ops/ms [Average]
  (min, avg, max) = (10.525, 10.783, 11.120), stdev = 0.305
  CI (99.9%): [5.222, 16.344] (assumes normal distribution)


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
# Warmup Iteration   1: 7.839 ops/ms
# Warmup Iteration   2: 10.239 ops/ms
# Warmup Iteration   3: 10.277 ops/ms
Iteration   1: 10.313 ops/ms
Iteration   2: 10.121 ops/ms
Iteration   3: 10.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.165 ±(99.9%) 2.407 ops/ms [Average]
  (min, avg, max) = (10.061, 10.165, 10.313), stdev = 0.132
  CI (99.9%): [7.759, 12.572] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.093 ops/ms
# Warmup Iteration   2: 7.647 ops/ms
# Warmup Iteration   3: 7.966 ops/ms
Iteration   1: 8.209 ops/ms
Iteration   2: 7.775 ops/ms
Iteration   3: 7.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.934 ±(99.9%) 4.369 ops/ms [Average]
  (min, avg, max) = (7.775, 7.934, 8.209), stdev = 0.239
  CI (99.9%): [3.565, 12.303] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.003 ms/op
Iteration   1: 3.095 ±(99.9%) 0.008 ms/op
Iteration   2: 3.161 ±(99.9%) 0.002 ms/op
Iteration   3: 3.075 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.111 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (3.075, 3.111, 3.161), stdev = 0.045
  CI (99.9%): [2.290, 3.931] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.003 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 2.954 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.997 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (2.954, 2.997, 3.047), stdev = 0.047
  CI (99.9%): [2.144, 3.850] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.002 ms/op
Iteration   1: 3.033 ±(99.9%) 0.003 ms/op
Iteration   2: 3.045 ±(99.9%) 0.002 ms/op
Iteration   3: 3.020 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.033 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (3.020, 3.033, 3.045), stdev = 0.013
  CI (99.9%): [2.803, 3.262] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.028 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.029 ms/op
Iteration   1: 3.891 ±(99.9%) 0.024 ms/op
Iteration   2: 4.051 ±(99.9%) 0.028 ms/op
Iteration   3: 4.024 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.989 ±(99.9%) 1.562 ms/op [Average]
  (min, avg, max) = (3.891, 3.989, 4.051), stdev = 0.086
  CI (99.9%): [2.427, 5.551] (assumes normal distribution)


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 3.131 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.011 ms/op
                 createUser·p0.9999: 11.757 ms/op
                 createUser·p1.00:   12.059 ms/op

Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.467 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.076 ms/op
                 createUser·p0.9999: 18.995 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.386 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  13.856 ms/op
                 createUser·p0.9999: 21.643 ms/op
                 createUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310512
  mean =      3.092 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22840 
    [ 2.500,  5.000) = 286824 
    [ 5.000,  7.500) = 531 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.386 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.590 ms/op
     p(99.9900) =     20.870 ms/op
     p(99.9990) =     21.823 ms/op
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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
Iteration   1: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.111 ms/op
                 existUser·p0.9999: 12.437 ms/op
                 existUser·p1.00:   12.583 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.785 ms/op
                 existUser·p0.9999: 13.129 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  6.281 ms/op
                 existUser·p0.9999: 14.876 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326157
  mean =      2.945 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2456 
    [ 1.250,  2.500) = 43327 
    [ 2.500,  3.750) = 264567 
    [ 3.750,  5.000) = 14878 
    [ 5.000,  6.250) = 593 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.308 ms/op
     p(99.9900) =     14.037 ms/op
     p(99.9990) =     16.658 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
Iteration   1: 3.101 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  8.004 ms/op
                 getUser·p0.9999: 22.458 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.406 ms/op
                 getUser·p0.9999: 19.202 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.716 ms/op
                 getUser·p0.9999: 16.256 ms/op
                 getUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312143
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22444 
    [ 2.500,  5.000) = 288668 
    [ 5.000,  7.500) = 721 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.495 ms/op
     p(99.9900) =     21.540 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 5.518 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.013 ms/op
Iteration   1: 4.083 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 15.620 ms/op
                 listUser·p1.00:   16.646 ms/op

Iteration   2: 4.011 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.896 ms/op
                 listUser·p0.9999: 24.281 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   3: 3.893 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.682 ms/op
                 listUser·p0.999:  15.727 ms/op
                 listUser·p0.9999: 26.313 ms/op
                 listUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240352
  mean =      3.994 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4202 
    [ 2.500,  5.000) = 210441 
    [ 5.000,  7.500) = 24426 
    [ 7.500, 10.000) = 895 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     25.817 ms/op
     p(99.9990) =     27.764 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.380 ± 0.515  ops/ms
ClientGrpc.existUser                       thrpt       3  10.783 ± 5.561  ops/ms
ClientGrpc.getUser                         thrpt       3  10.165 ± 2.407  ops/ms
ClientGrpc.listUser                        thrpt       3   7.934 ± 4.369  ops/ms
ClientGrpc.createUser                       avgt       3   3.111 ± 0.821   ms/op
ClientGrpc.existUser                        avgt       3   2.997 ± 0.853   ms/op
ClientGrpc.getUser                          avgt       3   3.033 ± 0.230   ms/op
ClientGrpc.listUser                         avgt       3   3.989 ± 1.562   ms/op
ClientGrpc.createUser                     sample  310512   3.092 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.386           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.590           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.870           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.086           ms/op
ClientGrpc.existUser                      sample  326157   2.945 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.636           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.308           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.037           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.777           ms/op
ClientGrpc.getUser                        sample  312143   3.075 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.589           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.495           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.540           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.741           ms/op
ClientGrpc.listUser                       sample  240352   3.994 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.889           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.943           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.817           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.574           ms/op
