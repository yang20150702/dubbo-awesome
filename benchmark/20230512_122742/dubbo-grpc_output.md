# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.032 ops/ms
# Warmup Iteration   2: 8.705 ops/ms
# Warmup Iteration   3: 9.890 ops/ms
Iteration   1: 10.354 ops/ms
Iteration   2: 10.543 ops/ms
Iteration   3: 10.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.369 ±(99.9%) 3.046 ops/ms [Average]
  (min, avg, max) = (10.210, 10.369, 10.543), stdev = 0.167
  CI (99.9%): [7.323, 13.415] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.245 ops/ms
# Warmup Iteration   2: 10.638 ops/ms
# Warmup Iteration   3: 10.877 ops/ms
Iteration   1: 10.902 ops/ms
Iteration   2: 10.797 ops/ms
Iteration   3: 10.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.832 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (10.796, 10.832, 10.902), stdev = 0.061
  CI (99.9%): [9.716, 11.947] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.279 ops/ms
# Warmup Iteration   2: 9.903 ops/ms
# Warmup Iteration   3: 10.377 ops/ms
Iteration   1: 10.374 ops/ms
Iteration   2: 10.359 ops/ms
Iteration   3: 10.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.361 ±(99.9%) 0.234 ops/ms [Average]
  (min, avg, max) = (10.349, 10.361, 10.374), stdev = 0.013
  CI (99.9%): [10.126, 10.595] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.329 ops/ms
# Warmup Iteration   2: 7.526 ops/ms
# Warmup Iteration   3: 7.820 ops/ms
Iteration   1: 7.843 ops/ms
Iteration   2: 7.840 ops/ms
Iteration   3: 7.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.867 ±(99.9%) 0.805 ops/ms [Average]
  (min, avg, max) = (7.840, 7.867, 7.918), stdev = 0.044
  CI (99.9%): [7.062, 8.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.390 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.145 ±(99.9%) 0.003 ms/op
Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
Iteration   3: 3.140 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.121 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (3.077, 3.121, 3.145), stdev = 0.038
  CI (99.9%): [2.427, 3.815] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.019 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.003 ms/op
Iteration   1: 2.936 ±(99.9%) 0.004 ms/op
Iteration   2: 2.952 ±(99.9%) 0.002 ms/op
Iteration   3: 2.944 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.944 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (2.936, 2.944, 2.952), stdev = 0.008
  CI (99.9%): [2.802, 3.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.319 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.088 ±(99.9%) 0.002 ms/op
Iteration   2: 3.053 ±(99.9%) 0.003 ms/op
Iteration   3: 3.083 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.074 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (3.053, 3.074, 3.088), stdev = 0.019
  CI (99.9%): [2.730, 3.418] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.899 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.007 ms/op
Iteration   1: 4.070 ±(99.9%) 0.009 ms/op
Iteration   2: 4.042 ±(99.9%) 0.017 ms/op
Iteration   3: 4.084 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.065 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (4.042, 4.065, 4.084), stdev = 0.021
  CI (99.9%): [3.679, 4.452] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.262 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.084 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.357 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  9.246 ms/op
                 createUser·p0.9999: 12.980 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.351 ms/op
                 createUser·p0.9999: 15.175 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  7.617 ms/op
                 createUser·p0.9999: 30.015 ms/op
                 createUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311901
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19667 
    [ 2.500,  5.000) = 290630 
    [ 5.000,  7.500) = 1229 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      8.366 ms/op
     p(99.9900) =     28.284 ms/op
     p(99.9990) =     30.048 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.264 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 2.934 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.832 ms/op
                 existUser·p0.9999: 12.899 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 2.942 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.351 ms/op
                 existUser·p0.9999: 14.604 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   3: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.389 ms/op
                 existUser·p0.9999: 15.434 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327745
  mean =      2.927 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 873 
    [ 1.250,  2.500) = 35775 
    [ 2.500,  3.750) = 280228 
    [ 3.750,  5.000) = 9815 
    [ 5.000,  6.250) = 639 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 134 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.014 ms/op
     p(99.9900) =     14.828 ms/op
     p(99.9990) =     16.910 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.636 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.676 ms/op
                 getUser·p0.9999: 12.543 ms/op
                 getUser·p1.00:   12.714 ms/op

Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.768 ms/op
                 getUser·p0.9999: 15.164 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.947 ms/op
                 getUser·p0.9999: 17.651 ms/op
                 getUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312678
  mean =      3.068 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 957 
    [ 1.250,  2.500) = 14217 
    [ 2.500,  3.750) = 281118 
    [ 3.750,  5.000) = 14640 
    [ 5.000,  6.250) = 1074 
    [ 6.250,  7.500) = 277 
    [ 7.500,  8.750) = 126 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.957 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     18.997 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.415 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.280 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.012 ms/op
Iteration   1: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.672 ms/op
                 listUser·p0.9999: 15.368 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   2: 4.054 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 17.698 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   3: 3.992 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  17.013 ms/op
                 listUser·p0.9999: 32.670 ms/op
                 listUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237910
  mean =      4.038 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2779 
    [ 2.500,  5.000) = 209541 
    [ 5.000,  7.500) = 24132 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     31.661 ms/op
     p(99.9990) =     33.595 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.369 ± 3.046  ops/ms
ClientGrpc.existUser                       thrpt       3  10.832 ± 1.116  ops/ms
ClientGrpc.getUser                         thrpt       3  10.361 ± 0.234  ops/ms
ClientGrpc.listUser                        thrpt       3   7.867 ± 0.805  ops/ms
ClientGrpc.createUser                       avgt       3   3.121 ± 0.694   ms/op
ClientGrpc.existUser                        avgt       3   2.944 ± 0.142   ms/op
ClientGrpc.getUser                          avgt       3   3.074 ± 0.344   ms/op
ClientGrpc.listUser                         avgt       3   4.065 ± 0.386   ms/op
ClientGrpc.createUser                     sample  311901   3.079 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.357           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.366           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.284           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.081           ms/op
ClientGrpc.existUser                      sample  327745   2.927 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.678           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.014           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.828           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.367           ms/op
ClientGrpc.getUser                        sample  312678   3.068 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.629           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.957           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.007           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.104           ms/op
ClientGrpc.listUser                       sample  237910   4.038 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.795           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.795           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.661           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.686           ms/op
