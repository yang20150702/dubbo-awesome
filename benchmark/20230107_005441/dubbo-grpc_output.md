# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.917 ops/ms
# Warmup Iteration   2: 9.286 ops/ms
# Warmup Iteration   3: 10.248 ops/ms
Iteration   1: 10.252 ops/ms
Iteration   2: 9.840 ops/ms
Iteration   3: 10.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.108 ±(99.9%) 4.248 ops/ms [Average]
  (min, avg, max) = (9.840, 10.108, 10.252), stdev = 0.233
  CI (99.9%): [5.860, 14.357] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.500 ops/ms
# Warmup Iteration   2: 10.654 ops/ms
# Warmup Iteration   3: 10.949 ops/ms
Iteration   1: 11.168 ops/ms
Iteration   2: 11.107 ops/ms
Iteration   3: 11.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.123 ±(99.9%) 0.725 ops/ms [Average]
  (min, avg, max) = (11.094, 11.123, 11.168), stdev = 0.040
  CI (99.9%): [10.398, 11.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.832 ops/ms
# Warmup Iteration   2: 10.571 ops/ms
# Warmup Iteration   3: 10.464 ops/ms
Iteration   1: 10.502 ops/ms
Iteration   2: 10.771 ops/ms
Iteration   3: 10.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.553 ±(99.9%) 3.619 ops/ms [Average]
  (min, avg, max) = (10.384, 10.553, 10.771), stdev = 0.198
  CI (99.9%): [6.933, 14.172] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.453 ops/ms
# Warmup Iteration   2: 7.945 ops/ms
# Warmup Iteration   3: 7.900 ops/ms
Iteration   1: 8.037 ops/ms
Iteration   2: 8.157 ops/ms
Iteration   3: 8.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.110 ±(99.9%) 1.160 ops/ms [Average]
  (min, avg, max) = (8.037, 8.110, 8.157), stdev = 0.064
  CI (99.9%): [6.950, 9.269] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.209 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.003 ms/op
Iteration   1: 3.128 ±(99.9%) 0.002 ms/op
Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
Iteration   3: 3.129 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.115 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (3.088, 3.115, 3.129), stdev = 0.023
  CI (99.9%): [2.687, 3.543] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.880 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.003 ms/op
Iteration   1: 2.981 ±(99.9%) 0.002 ms/op
Iteration   2: 2.992 ±(99.9%) 0.002 ms/op
Iteration   3: 2.874 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.949 ±(99.9%) 1.189 ms/op [Average]
  (min, avg, max) = (2.874, 2.949, 2.992), stdev = 0.065
  CI (99.9%): [1.761, 4.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.003 ms/op
Iteration   1: 3.158 ±(99.9%) 0.004 ms/op
Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
Iteration   3: 3.039 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.084 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (3.039, 3.084, 3.158), stdev = 0.064
  CI (99.9%): [1.917, 4.252] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.223 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.018 ms/op
Iteration   1: 4.004 ±(99.9%) 0.016 ms/op
Iteration   2: 3.882 ±(99.9%) 0.015 ms/op
Iteration   3: 3.864 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.917 ±(99.9%) 1.387 ms/op [Average]
  (min, avg, max) = (3.864, 3.917, 4.004), stdev = 0.076
  CI (99.9%): [2.530, 5.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.231 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.370 ms/op
                 createUser·p0.999:  7.556 ms/op
                 createUser·p0.9999: 11.634 ms/op
                 createUser·p1.00:   13.238 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  9.333 ms/op
                 createUser·p0.9999: 19.653 ms/op
                 createUser·p1.00:   19.923 ms/op

Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  8.134 ms/op
                 createUser·p0.9999: 24.371 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309557
  mean =      3.102 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31068 
    [ 2.500,  5.000) = 277208 
    [ 5.000,  7.500) = 847 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.231 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      9.002 ms/op
     p(99.9900) =     23.660 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.698 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.408 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  5.360 ms/op
                 existUser·p0.9999: 10.801 ms/op
                 existUser·p1.00:   11.092 ms/op

Iteration   2: 2.930 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.691 ms/op
                 existUser·p0.9999: 21.466 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.008 ms/op
                 existUser·p0.999:  7.269 ms/op
                 existUser·p0.9999: 16.040 ms/op
                 existUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326276
  mean =      2.943 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52378 
    [ 2.500,  5.000) = 273169 
    [ 5.000,  7.500) = 508 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.080 ms/op
     p(99.9000) =      6.289 ms/op
     p(99.9900) =     17.762 ms/op
     p(99.9990) =     21.782 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.784 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.012 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.412 ms/op
                 getUser·p0.9999: 11.285 ms/op
                 getUser·p1.00:   11.928 ms/op

Iteration   2: 2.908 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.567 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 17.891 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.409 ms/op
                 getUser·p0.9999: 26.804 ms/op
                 getUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320831
  mean =      2.991 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34905 
    [ 2.500,  5.000) = 284897 
    [ 5.000,  7.500) = 713 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.463 ms/op
     p(99.9900) =     25.784 ms/op
     p(99.9990) =     28.443 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.639 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.011 ms/op
Iteration   1: 4.143 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.406 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  13.074 ms/op
                 listUser·p0.9999: 18.130 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   2: 4.004 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  12.157 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 3.994 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237197
  mean =      4.046 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4272 
    [ 2.500,  5.000) = 197466 
    [ 5.000,  7.500) = 34178 
    [ 7.500, 10.000) = 758 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.103 ms/op
     p(99.9900) =     20.120 ms/op
     p(99.9990) =     21.292 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.108 ± 4.248  ops/ms
ClientGrpc.existUser                       thrpt       3  11.123 ± 0.725  ops/ms
ClientGrpc.getUser                         thrpt       3  10.553 ± 3.619  ops/ms
ClientGrpc.listUser                        thrpt       3   8.110 ± 1.160  ops/ms
ClientGrpc.createUser                       avgt       3   3.115 ± 0.428   ms/op
ClientGrpc.existUser                        avgt       3   2.949 ± 1.189   ms/op
ClientGrpc.getUser                          avgt       3   3.084 ± 1.168   ms/op
ClientGrpc.listUser                         avgt       3   3.917 ± 1.387   ms/op
ClientGrpc.createUser                     sample  309557   3.102 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.231           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.002           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.660           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.707           ms/op
ClientGrpc.existUser                      sample  326276   2.943 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.408           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.080           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.289           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.762           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.922           ms/op
ClientGrpc.getUser                        sample  320831   2.991 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.567           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.463           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.784           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.475           ms/op
ClientGrpc.listUser                       sample  237197   4.046 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.406           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.103           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.120           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.529           ms/op
