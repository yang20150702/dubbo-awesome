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
# Warmup Iteration   1: 3.992 ops/ms
# Warmup Iteration   2: 8.969 ops/ms
# Warmup Iteration   3: 10.021 ops/ms
Iteration   1: 10.518 ops/ms
Iteration   2: 10.273 ops/ms
Iteration   3: 10.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.322 ±(99.9%) 3.205 ops/ms [Average]
  (min, avg, max) = (10.177, 10.322, 10.518), stdev = 0.176
  CI (99.9%): [7.118, 13.527] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.117 ops/ms
# Warmup Iteration   2: 10.427 ops/ms
# Warmup Iteration   3: 10.977 ops/ms
Iteration   1: 10.975 ops/ms
Iteration   2: 11.007 ops/ms
Iteration   3: 10.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.964 ±(99.9%) 0.918 ops/ms [Average]
  (min, avg, max) = (10.909, 10.964, 11.007), stdev = 0.050
  CI (99.9%): [10.046, 11.882] (assumes normal distribution)


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
# Warmup Iteration   1: 6.638 ops/ms
# Warmup Iteration   2: 10.002 ops/ms
# Warmup Iteration   3: 10.406 ops/ms
Iteration   1: 10.364 ops/ms
Iteration   2: 10.467 ops/ms
Iteration   3: 10.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.448 ±(99.9%) 1.386 ops/ms [Average]
  (min, avg, max) = (10.364, 10.448, 10.513), stdev = 0.076
  CI (99.9%): [9.062, 11.835] (assumes normal distribution)


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
# Warmup Iteration   1: 5.284 ops/ms
# Warmup Iteration   2: 7.686 ops/ms
# Warmup Iteration   3: 8.071 ops/ms
Iteration   1: 7.819 ops/ms
Iteration   2: 7.886 ops/ms
Iteration   3: 7.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.890 ±(99.9%) 1.352 ops/ms [Average]
  (min, avg, max) = (7.819, 7.890, 7.967), stdev = 0.074
  CI (99.9%): [6.538, 9.243] (assumes normal distribution)


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
# Warmup Iteration   1: 4.460 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.002 ms/op
Iteration   1: 3.068 ±(99.9%) 0.004 ms/op
Iteration   2: 3.086 ±(99.9%) 0.003 ms/op
Iteration   3: 3.048 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.067 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (3.048, 3.067, 3.086), stdev = 0.019
  CI (99.9%): [2.725, 3.409] (assumes normal distribution)


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
# Warmup Iteration   1: 4.185 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.003 ms/op
Iteration   1: 3.037 ±(99.9%) 0.002 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 2.968 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.001 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (2.968, 3.001, 3.037), stdev = 0.035
  CI (99.9%): [2.366, 3.636] (assumes normal distribution)


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.004 ms/op
Iteration   1: 3.070 ±(99.9%) 0.003 ms/op
Iteration   2: 3.079 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.052 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.007, 3.052, 3.079), stdev = 0.039
  CI (99.9%): [2.339, 3.766] (assumes normal distribution)


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
# Warmup Iteration   1: 5.080 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.013 ms/op
Iteration   1: 3.968 ±(99.9%) 0.008 ms/op
Iteration   2: 3.937 ±(99.9%) 0.013 ms/op
Iteration   3: 3.894 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.933 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (3.894, 3.933, 3.968), stdev = 0.037
  CI (99.9%): [3.252, 4.614] (assumes normal distribution)


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.982 ms/op
                 createUser·p0.9999: 14.615 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  6.735 ms/op
                 createUser·p0.9999: 21.346 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.416 ms/op
                 createUser·p0.9999: 24.582 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313676
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25255 
    [ 2.500,  5.000) = 286795 
    [ 5.000,  7.500) = 1219 
    [ 7.500, 10.000) = 176 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.197 ms/op
     p(99.9900) =     23.286 ms/op
     p(99.9990) =     25.234 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.315 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.005 ms/op
Iteration   1: 2.971 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.925 ms/op
                 existUser·p0.9999: 14.242 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 2.941 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.889 ms/op
                 existUser·p0.9999: 14.436 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  9.799 ms/op
                 existUser·p0.9999: 15.827 ms/op
                 existUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324334
  mean =      2.959 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 372 
    [ 1.250,  2.500) = 30924 
    [ 2.500,  3.750) = 282558 
    [ 3.750,  5.000) = 9315 
    [ 5.000,  6.250) = 524 
    [ 6.250,  7.500) = 321 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 126 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      7.471 ms/op
     p(99.9900) =     15.459 ms/op
     p(99.9990) =     16.253 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


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
# Warmup Iteration   1: 4.551 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.006 ms/op
Iteration   1: 3.097 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.744 ms/op
                 getUser·p0.999:  7.959 ms/op
                 getUser·p0.9999: 12.856 ms/op
                 getUser·p1.00:   13.124 ms/op

Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.282 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  7.051 ms/op
                 getUser·p0.9999: 13.954 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   3: 3.170 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.407 ms/op
                 getUser·p0.9999: 19.792 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307733
  mean =      3.122 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14904 
    [ 2.500,  5.000) = 290965 
    [ 5.000,  7.500) = 1565 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      7.449 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 5.947 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.011 ms/op
Iteration   1: 4.020 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.186 ms/op
                 listUser·p0.999:  14.925 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   2: 4.064 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  13.746 ms/op
                 listUser·p0.9999: 16.714 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 4.093 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 20.361 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236616
  mean =      4.059 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1954 
    [ 2.500,  5.000) = 210395 
    [ 5.000,  7.500) = 22638 
    [ 7.500, 10.000) = 1163 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.260 ms/op
     p(99.9900) =     20.360 ms/op
     p(99.9990) =     20.861 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.322 ± 3.205  ops/ms
ClientGrpc.existUser                       thrpt       3  10.964 ± 0.918  ops/ms
ClientGrpc.getUser                         thrpt       3  10.448 ± 1.386  ops/ms
ClientGrpc.listUser                        thrpt       3   7.890 ± 1.352  ops/ms
ClientGrpc.createUser                       avgt       3   3.067 ± 0.342   ms/op
ClientGrpc.existUser                        avgt       3   3.001 ± 0.635   ms/op
ClientGrpc.getUser                          avgt       3   3.052 ± 0.713   ms/op
ClientGrpc.listUser                         avgt       3   3.933 ± 0.681   ms/op
ClientGrpc.createUser                     sample  313676   3.059 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.197           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.286           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.592           ms/op
ClientGrpc.existUser                      sample  324334   2.959 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.853           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.471           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.459           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.613           ms/op
ClientGrpc.getUser                        sample  307733   3.122 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.282           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.449           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.202           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.447           ms/op
ClientGrpc.listUser                       sample  236616   4.059 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.041           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.260           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.360           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.004           ms/op
