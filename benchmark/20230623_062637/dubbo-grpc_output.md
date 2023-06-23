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
# Warmup Iteration   1: 2.333 ops/ms
# Warmup Iteration   2: 5.605 ops/ms
# Warmup Iteration   3: 7.189 ops/ms
Iteration   1: 7.526 ops/ms
Iteration   2: 7.534 ops/ms
Iteration   3: 7.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.488 ±(99.9%) 1.337 ops/ms [Average]
  (min, avg, max) = (7.404, 7.488, 7.534), stdev = 0.073
  CI (99.9%): [6.151, 8.825] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.008 ops/ms
# Warmup Iteration   2: 7.359 ops/ms
# Warmup Iteration   3: 8.131 ops/ms
Iteration   1: 7.926 ops/ms
Iteration   2: 7.832 ops/ms
Iteration   3: 8.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.004 ±(99.9%) 4.042 ops/ms [Average]
  (min, avg, max) = (7.832, 8.004, 8.254), stdev = 0.222
  CI (99.9%): [3.962, 12.047] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.522 ops/ms
# Warmup Iteration   2: 7.005 ops/ms
# Warmup Iteration   3: 7.509 ops/ms
Iteration   1: 7.645 ops/ms
Iteration   2: 7.834 ops/ms
Iteration   3: 7.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.794 ±(99.9%) 2.430 ops/ms [Average]
  (min, avg, max) = (7.645, 7.794, 7.902), stdev = 0.133
  CI (99.9%): [5.363, 10.224] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ops/ms
# Warmup Iteration   2: 5.503 ops/ms
# Warmup Iteration   3: 5.957 ops/ms
Iteration   1: 6.072 ops/ms
Iteration   2: 6.095 ops/ms
Iteration   3: 6.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.132 ±(99.9%) 1.542 ops/ms [Average]
  (min, avg, max) = (6.072, 6.132, 6.228), stdev = 0.085
  CI (99.9%): [4.590, 7.674] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.329 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.299 ±(99.9%) 0.016 ms/op
Iteration   1: 4.178 ±(99.9%) 0.003 ms/op
Iteration   2: 4.133 ±(99.9%) 0.002 ms/op
Iteration   3: 4.080 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.131 ±(99.9%) 0.891 ms/op [Average]
  (min, avg, max) = (4.080, 4.131, 4.178), stdev = 0.049
  CI (99.9%): [3.239, 5.022] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.773 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.002 ms/op
Iteration   1: 3.737 ±(99.9%) 0.005 ms/op
Iteration   2: 3.775 ±(99.9%) 0.003 ms/op
Iteration   3: 3.735 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.749 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (3.735, 3.749, 3.775), stdev = 0.023
  CI (99.9%): [3.335, 4.163] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.293 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.004 ms/op
Iteration   1: 4.255 ±(99.9%) 0.003 ms/op
Iteration   2: 4.144 ±(99.9%) 0.003 ms/op
Iteration   3: 4.088 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.163 ±(99.9%) 1.554 ms/op [Average]
  (min, avg, max) = (4.088, 4.163, 4.255), stdev = 0.085
  CI (99.9%): [2.609, 5.716] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.253 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.608 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.190 ±(99.9%) 0.016 ms/op
Iteration   1: 5.144 ±(99.9%) 0.010 ms/op
Iteration   2: 5.033 ±(99.9%) 0.012 ms/op
Iteration   3: 5.198 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.125 ±(99.9%) 1.532 ms/op [Average]
  (min, avg, max) = (5.033, 5.125, 5.198), stdev = 0.084
  CI (99.9%): [3.592, 6.657] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.135 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.584 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.011 ms/op
Iteration   1: 4.069 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.308 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  9.432 ms/op
                 createUser·p0.9999: 14.900 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   2: 4.118 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   4.051 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  10.720 ms/op
                 createUser·p0.9999: 17.800 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   3: 4.054 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  17.007 ms/op
                 createUser·p0.9999: 21.482 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 235281
  mean =      4.080 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4655 
    [ 2.500,  5.000) = 208409 
    [ 5.000,  7.500) = 21262 
    [ 7.500, 10.000) = 681 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     10.453 ms/op
     p(99.9900) =     20.018 ms/op
     p(99.9990) =     22.215 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.966 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.009 ms/op
Iteration   1: 3.951 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  12.288 ms/op
                 existUser·p0.9999: 26.813 ms/op
                 existUser·p1.00:   27.427 ms/op

Iteration   2: 3.857 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.030 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  9.748 ms/op
                 existUser·p0.9999: 17.620 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   3: 3.798 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   5.783 ms/op
                 existUser·p0.999:  10.306 ms/op
                 existUser·p0.9999: 18.874 ms/op
                 existUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 247886
  mean =      3.868 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8468 
    [ 2.500,  5.000) = 227291 
    [ 5.000,  7.500) = 10703 
    [ 7.500, 10.000) = 968 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     10.996 ms/op
     p(99.9900) =     26.057 ms/op
     p(99.9990) =     27.052 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.457 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.434 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.012 ms/op
Iteration   1: 4.097 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   4.022 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   7.646 ms/op
                 getUser·p0.999:  12.806 ms/op
                 getUser·p0.9999: 14.959 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   2: 4.038 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  10.235 ms/op
                 getUser·p0.9999: 18.221 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   3: 4.067 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  8.866 ms/op
                 getUser·p0.9999: 19.207 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235964
  mean =      4.067 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 8750 
    [ 2.500,  3.750) = 72070 
    [ 3.750,  5.000) = 131789 
    [ 5.000,  6.250) = 19496 
    [ 6.250,  7.500) = 2434 
    [ 7.500,  8.750) = 686 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     11.830 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 6.672 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.785 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.241 ±(99.9%) 0.016 ms/op
Iteration   1: 5.195 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   6.562 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  16.235 ms/op
                 listUser·p0.9999: 23.911 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   2: 5.121 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   6.349 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   9.250 ms/op
                 listUser·p0.999:  19.613 ms/op
                 listUser·p0.9999: 21.652 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   3: 5.247 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 32.375 ms/op
                 listUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184946
  mean =      5.187 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 92701 
    [ 5.000,  7.500) = 84133 
    [ 7.500, 10.000) = 7005 
    [10.000, 12.500) = 583 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.324 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     18.323 ms/op
     p(99.9900) =     25.838 ms/op
     p(99.9990) =     32.609 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.488 ± 1.337  ops/ms
ClientGrpc.existUser                       thrpt       3   8.004 ± 4.042  ops/ms
ClientGrpc.getUser                         thrpt       3   7.794 ± 2.430  ops/ms
ClientGrpc.listUser                        thrpt       3   6.132 ± 1.542  ops/ms
ClientGrpc.createUser                       avgt       3   4.131 ± 0.891   ms/op
ClientGrpc.existUser                        avgt       3   3.749 ± 0.414   ms/op
ClientGrpc.getUser                          avgt       3   4.163 ± 1.554   ms/op
ClientGrpc.listUser                         avgt       3   5.125 ± 1.532   ms/op
ClientGrpc.createUser                     sample  235281   4.080 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.010           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.973           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.316           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.453           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.018           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.348           ms/op
ClientGrpc.existUser                      sample  247886   3.868 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.793           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.989           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.382           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.996           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.057           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.427           ms/op
ClientGrpc.getUser                        sample  235964   4.067 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.783           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.997           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.407           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.758           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.830           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.055           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.661           ms/op
ClientGrpc.listUser                       sample  184946   5.187 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.788           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.480           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.324           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.159           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.323           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.838           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.637           ms/op
