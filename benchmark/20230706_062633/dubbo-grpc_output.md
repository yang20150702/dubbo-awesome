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
# Warmup Iteration   1: 4.633 ops/ms
# Warmup Iteration   2: 9.453 ops/ms
# Warmup Iteration   3: 10.707 ops/ms
Iteration   1: 10.594 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.612 ±(99.9%) 1.710 ops/ms [Average]
  (min, avg, max) = (10.529, 10.612, 10.714), stdev = 0.094
  CI (99.9%): [8.902, 12.322] (assumes normal distribution)


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
# Warmup Iteration   1: 8.161 ops/ms
# Warmup Iteration   2: 10.611 ops/ms
# Warmup Iteration   3: 11.244 ops/ms
Iteration   1: 11.066 ops/ms
Iteration   2: 11.154 ops/ms
Iteration   3: 11.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.221 ±(99.9%) 3.617 ops/ms [Average]
  (min, avg, max) = (11.066, 11.221, 11.445), stdev = 0.198
  CI (99.9%): [7.604, 14.839] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.400 ops/ms
# Warmup Iteration   2: 10.405 ops/ms
# Warmup Iteration   3: 10.657 ops/ms
Iteration   1: 10.794 ops/ms
Iteration   2: 10.505 ops/ms
Iteration   3: 10.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.618 ±(99.9%) 2.819 ops/ms [Average]
  (min, avg, max) = (10.505, 10.618, 10.794), stdev = 0.155
  CI (99.9%): [7.799, 13.437] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.554 ops/ms
# Warmup Iteration   2: 7.908 ops/ms
# Warmup Iteration   3: 8.122 ops/ms
Iteration   1: 8.211 ops/ms
Iteration   2: 8.195 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.149 ±(99.9%) 1.728 ops/ms [Average]
  (min, avg, max) = (8.040, 8.149, 8.211), stdev = 0.095
  CI (99.9%): [6.420, 9.877] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.940 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.003 ms/op
Iteration   1: 2.973 ±(99.9%) 0.002 ms/op
Iteration   2: 2.997 ±(99.9%) 0.003 ms/op
Iteration   3: 2.967 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.979 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.967, 2.979, 2.997), stdev = 0.016
  CI (99.9%): [2.693, 3.265] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.923 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.835 ±(99.9%) 0.003 ms/op
Iteration   1: 2.823 ±(99.9%) 0.003 ms/op
Iteration   2: 2.835 ±(99.9%) 0.003 ms/op
Iteration   3: 2.877 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.845 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (2.823, 2.845, 2.877), stdev = 0.029
  CI (99.9%): [2.321, 3.369] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.082 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.002 ms/op
Iteration   2: 2.960 ±(99.9%) 0.002 ms/op
Iteration   3: 2.977 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.979 ±(99.9%) 0.373 ms/op [Average]
  (min, avg, max) = (2.960, 2.979, 3.000), stdev = 0.020
  CI (99.9%): [2.606, 3.352] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.127 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.020 ms/op
Iteration   1: 3.961 ±(99.9%) 0.046 ms/op
Iteration   2: 3.937 ±(99.9%) 0.010 ms/op
Iteration   3: 3.924 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.941 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.924, 3.941, 3.961), stdev = 0.019
  CI (99.9%): [3.603, 4.278] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.538 ms/op
                 createUser·p0.9999: 12.799 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   2: 3.001 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  7.070 ms/op
                 createUser·p0.9999: 12.523 ms/op
                 createUser·p1.00:   12.796 ms/op

Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 14.780 ms/op
                 createUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319083
  mean =      3.007 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 955 
    [ 1.250,  2.500) = 18856 
    [ 2.500,  3.750) = 286484 
    [ 3.750,  5.000) = 11606 
    [ 5.000,  6.250) = 629 
    [ 6.250,  7.500) = 204 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     14.418 ms/op
     p(99.9990) =     16.586 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.933 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.006 ms/op
Iteration   1: 2.868 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.376 ms/op
                 existUser·p0.9999: 16.378 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   2: 2.887 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  5.727 ms/op
                 existUser·p0.9999: 17.069 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   3: 2.660 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.399 ms/op
                 existUser·p0.50:   2.789 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  9.257 ms/op
                 existUser·p0.9999: 14.712 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 342843
  mean =      2.801 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7650 
    [ 1.250,  2.500) = 53899 
    [ 2.500,  3.750) = 270549 
    [ 3.750,  5.000) = 9510 
    [ 5.000,  6.250) = 743 
    [ 6.250,  7.500) = 199 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      6.907 ms/op
     p(99.9900) =     16.723 ms/op
     p(99.9990) =     17.503 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 4.093 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 2.954 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.404 ms/op
                 getUser·p0.9999: 12.714 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.557 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.777 ms/op
                 getUser·p0.9999: 13.279 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.271 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.716 ms/op
                 getUser·p0.9999: 17.219 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322092
  mean =      2.978 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1593 
    [ 1.250,  2.500) = 25173 
    [ 2.500,  3.750) = 279948 
    [ 3.750,  5.000) = 14281 
    [ 5.000,  6.250) = 604 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.271 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.823 ms/op
     p(99.9900) =     16.013 ms/op
     p(99.9990) =     17.491 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 4.869 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.010 ms/op
Iteration   1: 3.917 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   5.501 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  14.804 ms/op
                 listUser·p0.9999: 18.405 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 3.984 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.107 ms/op
                 listUser·p0.9999: 15.923 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   3: 3.996 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.401 ms/op
                 listUser·p0.9999: 21.952 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242298
  mean =      3.965 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5487 
    [ 2.500,  5.000) = 212396 
    [ 5.000,  7.500) = 22810 
    [ 7.500, 10.000) = 954 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 211 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.282 ms/op
     p(99.9900) =     20.178 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.612 ± 1.710  ops/ms
ClientGrpc.existUser                       thrpt       3  11.221 ± 3.617  ops/ms
ClientGrpc.getUser                         thrpt       3  10.618 ± 2.819  ops/ms
ClientGrpc.listUser                        thrpt       3   8.149 ± 1.728  ops/ms
ClientGrpc.createUser                       avgt       3   2.979 ± 0.286   ms/op
ClientGrpc.existUser                        avgt       3   2.845 ± 0.524   ms/op
ClientGrpc.getUser                          avgt       3   2.979 ± 0.373   ms/op
ClientGrpc.listUser                         avgt       3   3.941 ± 0.338   ms/op
ClientGrpc.createUser                     sample  319083   3.007 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.601           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.418           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.761           ms/op
ClientGrpc.existUser                      sample  342843   2.801 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.399           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.314           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.907           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.723           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.629           ms/op
ClientGrpc.getUser                        sample  322092   2.978 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.271           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.823           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.013           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.874           ms/op
ClientGrpc.listUser                       sample  242298   3.965 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.886           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.282           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.178           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
