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
# Warmup Iteration   1: 4.753 ops/ms
# Warmup Iteration   2: 9.522 ops/ms
# Warmup Iteration   3: 10.073 ops/ms
Iteration   1: 10.679 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.718 ±(99.9%) 2.122 ops/ms [Average]
  (min, avg, max) = (10.626, 10.718, 10.848), stdev = 0.116
  CI (99.9%): [8.596, 12.840] (assumes normal distribution)


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
# Warmup Iteration   1: 8.285 ops/ms
# Warmup Iteration   2: 10.902 ops/ms
# Warmup Iteration   3: 11.321 ops/ms
Iteration   1: 11.281 ops/ms
Iteration   2: 11.540 ops/ms
Iteration   3: 11.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.406 ±(99.9%) 2.359 ops/ms [Average]
  (min, avg, max) = (11.281, 11.406, 11.540), stdev = 0.129
  CI (99.9%): [9.047, 13.765] (assumes normal distribution)


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
# Warmup Iteration   1: 7.576 ops/ms
# Warmup Iteration   2: 10.614 ops/ms
# Warmup Iteration   3: 10.749 ops/ms
Iteration   1: 10.858 ops/ms
Iteration   2: 10.905 ops/ms
Iteration   3: 10.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.876 ±(99.9%) 0.466 ops/ms [Average]
  (min, avg, max) = (10.858, 10.876, 10.905), stdev = 0.026
  CI (99.9%): [10.410, 11.342] (assumes normal distribution)


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
# Warmup Iteration   1: 5.802 ops/ms
# Warmup Iteration   2: 8.154 ops/ms
# Warmup Iteration   3: 8.190 ops/ms
Iteration   1: 8.546 ops/ms
Iteration   2: 8.503 ops/ms
Iteration   3: 8.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.459 ±(99.9%) 2.112 ops/ms [Average]
  (min, avg, max) = (8.328, 8.459, 8.546), stdev = 0.116
  CI (99.9%): [6.347, 10.571] (assumes normal distribution)


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.003 ms/op
Iteration   1: 2.977 ±(99.9%) 0.002 ms/op
Iteration   2: 2.978 ±(99.9%) 0.003 ms/op
Iteration   3: 2.914 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.956 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (2.914, 2.956, 2.978), stdev = 0.037
  CI (99.9%): [2.286, 3.626] (assumes normal distribution)


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
# Warmup Iteration   1: 3.696 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.768 ±(99.9%) 0.003 ms/op
Iteration   1: 2.818 ±(99.9%) 0.002 ms/op
Iteration   2: 2.823 ±(99.9%) 0.003 ms/op
Iteration   3: 2.810 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.817 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.810, 2.817, 2.823), stdev = 0.007
  CI (99.9%): [2.697, 2.938] (assumes normal distribution)


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.002 ms/op
Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
Iteration   3: 2.975 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.970 ±(99.9%) 0.112 ms/op [Average]
  (min, avg, max) = (2.963, 2.970, 2.975), stdev = 0.006
  CI (99.9%): [2.858, 3.081] (assumes normal distribution)


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
# Warmup Iteration   1: 4.700 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.042 ms/op
Iteration   1: 3.903 ±(99.9%) 0.029 ms/op
Iteration   2: 3.887 ±(99.9%) 0.016 ms/op
Iteration   3: 3.901 ±(99.9%) 0.047 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.897 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (3.887, 3.897, 3.903), stdev = 0.008
  CI (99.9%): [3.744, 4.050] (assumes normal distribution)


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
# Warmup Iteration   1: 4.119 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.922 ms/op
                 createUser·p0.9999: 12.829 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.509 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  9.362 ms/op
                 createUser·p0.9999: 13.212 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 2.965 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.344 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  9.552 ms/op
                 createUser·p0.9999: 25.657 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320746
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27059 
    [ 2.500,  5.000) = 292265 
    [ 5.000,  7.500) = 968 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.344 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      9.097 ms/op
     p(99.9900) =     25.035 ms/op
     p(99.9990) =     26.161 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 3.561 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.900 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.858 ±(99.9%) 0.005 ms/op
Iteration   1: 2.810 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.180 ms/op
                 existUser·p0.999:  7.704 ms/op
                 existUser·p0.9999: 13.363 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   2: 2.820 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.412 ms/op
                 existUser·p0.9999: 20.228 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   3: 2.860 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.342 ms/op
                 existUser·p0.9999: 19.917 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 339122
  mean =      2.830 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58466 
    [ 2.500,  5.000) = 279799 
    [ 5.000,  7.500) = 544 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.339 ms/op
     p(99.9900) =     19.893 ms/op
     p(99.9990) =     20.454 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.048 ms/op
                 getUser·p0.9999: 17.873 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 2.944 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.537 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  6.736 ms/op
                 getUser·p0.9999: 13.197 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   3: 2.963 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  7.655 ms/op
                 getUser·p0.9999: 14.831 ms/op
                 getUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322324
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1221 
    [ 1.250,  2.500) = 16656 
    [ 2.500,  3.750) = 293098 
    [ 3.750,  5.000) = 10471 
    [ 5.000,  6.250) = 442 
    [ 6.250,  7.500) = 153 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =      7.163 ms/op
     p(99.9900) =     16.050 ms/op
     p(99.9990) =     18.081 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.967 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.764 ±(99.9%) 0.010 ms/op
Iteration   1: 3.779 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.715 ms/op
                 listUser·p0.999:  11.600 ms/op
                 listUser·p0.9999: 18.141 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 3.834 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 14.696 ms/op
                 listUser·p1.00:   15.204 ms/op

Iteration   3: 3.823 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.880 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251832
  mean =      3.812 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 6868 
    [ 2.500,  3.750) = 136414 
    [ 3.750,  5.000) = 87816 
    [ 5.000,  6.250) = 16323 
    [ 6.250,  7.500) = 3439 
    [ 7.500,  8.750) = 505 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 149 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     17.966 ms/op
     p(99.9990) =     19.143 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.718 ± 2.122  ops/ms
ClientGrpc.existUser                       thrpt       3  11.406 ± 2.359  ops/ms
ClientGrpc.getUser                         thrpt       3  10.876 ± 0.466  ops/ms
ClientGrpc.listUser                        thrpt       3   8.459 ± 2.112  ops/ms
ClientGrpc.createUser                       avgt       3   2.956 ± 0.670   ms/op
ClientGrpc.existUser                        avgt       3   2.817 ± 0.121   ms/op
ClientGrpc.getUser                          avgt       3   2.970 ± 0.112   ms/op
ClientGrpc.listUser                         avgt       3   3.897 ± 0.153   ms/op
ClientGrpc.createUser                     sample  320746   2.992 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.344           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.097           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.035           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.378           ms/op
ClientGrpc.existUser                      sample  339122   2.830 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.515           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.339           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.893           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.611           ms/op
ClientGrpc.getUser                        sample  322324   2.979 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.537           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.957           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.163           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.050           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.186           ms/op
ClientGrpc.listUser                       sample  251832   3.812 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.005           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.674           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.993           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.966           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.726           ms/op
