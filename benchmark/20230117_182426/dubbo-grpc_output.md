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
# Warmup Iteration   1: 4.662 ops/ms
# Warmup Iteration   2: 9.310 ops/ms
# Warmup Iteration   3: 10.599 ops/ms
Iteration   1: 9.998 ops/ms
Iteration   2: 10.233 ops/ms
Iteration   3: 10.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.122 ±(99.9%) 2.150 ops/ms [Average]
  (min, avg, max) = (9.998, 10.122, 10.233), stdev = 0.118
  CI (99.9%): [7.972, 12.271] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.986 ops/ms
# Warmup Iteration   2: 10.278 ops/ms
# Warmup Iteration   3: 10.632 ops/ms
Iteration   1: 10.630 ops/ms
Iteration   2: 10.359 ops/ms
Iteration   3: 10.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.616 ±(99.9%) 4.561 ops/ms [Average]
  (min, avg, max) = (10.359, 10.616, 10.858), stdev = 0.250
  CI (99.9%): [6.055, 15.177] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.368 ops/ms
# Warmup Iteration   2: 10.192 ops/ms
# Warmup Iteration   3: 10.046 ops/ms
Iteration   1: 10.292 ops/ms
Iteration   2: 10.221 ops/ms
Iteration   3: 10.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.278 ±(99.9%) 0.936 ops/ms [Average]
  (min, avg, max) = (10.221, 10.278, 10.321), stdev = 0.051
  CI (99.9%): [9.342, 11.214] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.200 ops/ms
# Warmup Iteration   2: 7.612 ops/ms
# Warmup Iteration   3: 8.025 ops/ms
Iteration   1: 8.038 ops/ms
Iteration   2: 8.002 ops/ms
Iteration   3: 7.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.917 ±(99.9%) 3.274 ops/ms [Average]
  (min, avg, max) = (7.711, 7.917, 8.038), stdev = 0.179
  CI (99.9%): [4.643, 11.191] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.120 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.002 ms/op
Iteration   1: 3.150 ±(99.9%) 0.002 ms/op
Iteration   2: 3.204 ±(99.9%) 0.003 ms/op
Iteration   3: 3.110 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.155 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (3.110, 3.155, 3.204), stdev = 0.047
  CI (99.9%): [2.297, 4.013] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.883 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.003 ms/op
Iteration   1: 3.018 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
Iteration   3: 2.968 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.983 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (2.962, 2.983, 3.018), stdev = 0.031
  CI (99.9%): [2.421, 3.545] (assumes normal distribution)


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.002 ms/op
Iteration   1: 3.081 ±(99.9%) 0.002 ms/op
Iteration   2: 3.033 ±(99.9%) 0.002 ms/op
Iteration   3: 3.091 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.068 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (3.033, 3.068, 3.091), stdev = 0.031
  CI (99.9%): [2.502, 3.634] (assumes normal distribution)


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
# Warmup Iteration   1: 4.574 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.025 ms/op
Iteration   1: 4.127 ±(99.9%) 0.021 ms/op
Iteration   2: 3.874 ±(99.9%) 0.010 ms/op
Iteration   3: 3.943 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.981 ±(99.9%) 2.385 ms/op [Average]
  (min, avg, max) = (3.874, 3.981, 4.127), stdev = 0.131
  CI (99.9%): [1.596, 6.367] (assumes normal distribution)


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.885 ms/op
                 createUser·p0.9999: 15.679 ms/op
                 createUser·p1.00:   16.138 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.442 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  5.851 ms/op
                 createUser·p0.9999: 16.320 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.218 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  6.857 ms/op
                 createUser·p0.9999: 20.311 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314350
  mean =      3.054 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20584 
    [ 2.500,  5.000) = 292958 
    [ 5.000,  7.500) = 573 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.218 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.627 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.111 ms/op
                 existUser·p0.9999: 13.279 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  5.979 ms/op
                 existUser·p0.9999: 15.065 ms/op
                 existUser·p1.00:   15.598 ms/op

Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.231 ms/op
                 existUser·p0.9999: 19.233 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315834
  mean =      3.039 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2296 
    [ 1.250,  2.500) = 34814 
    [ 2.500,  3.750) = 251708 
    [ 3.750,  5.000) = 26415 
    [ 5.000,  6.250) = 313 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      6.128 ms/op
     p(99.9900) =     17.905 ms/op
     p(99.9990) =     19.618 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.006 ms/op
Iteration   1: 3.191 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.274 ms/op
                 getUser·p0.9999: 12.139 ms/op
                 getUser·p1.00:   12.648 ms/op

Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  9.093 ms/op
                 getUser·p0.9999: 13.230 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 3.146 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.745 ms/op
                 getUser·p0.9999: 15.428 ms/op
                 getUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304912
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 974 
    [ 1.250,  2.500) = 20692 
    [ 2.500,  3.750) = 247209 
    [ 3.750,  5.000) = 35055 
    [ 5.000,  6.250) = 464 
    [ 6.250,  7.500) = 194 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.712 ms/op
     p(99.9900) =     14.067 ms/op
     p(99.9990) =     15.695 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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
# Warmup Iteration   1: 5.434 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.011 ms/op
Iteration   1: 4.148 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.984 ms/op
                 listUser·p0.999:  12.423 ms/op
                 listUser·p0.9999: 19.384 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 4.041 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  12.648 ms/op
                 listUser·p0.9999: 16.598 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   3: 4.023 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  16.448 ms/op
                 listUser·p0.9999: 18.125 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235923
  mean =      4.070 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4193 
    [ 2.500,  5.000) = 194123 
    [ 5.000,  7.500) = 36345 
    [ 7.500, 10.000) = 867 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     13.996 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     23.293 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.122 ± 2.150  ops/ms
ClientGrpc.existUser                       thrpt       3  10.616 ± 4.561  ops/ms
ClientGrpc.getUser                         thrpt       3  10.278 ± 0.936  ops/ms
ClientGrpc.listUser                        thrpt       3   7.917 ± 3.274  ops/ms
ClientGrpc.createUser                       avgt       3   3.155 ± 0.858   ms/op
ClientGrpc.existUser                        avgt       3   2.983 ± 0.562   ms/op
ClientGrpc.getUser                          avgt       3   3.068 ± 0.566   ms/op
ClientGrpc.listUser                         avgt       3   3.981 ± 2.385   ms/op
ClientGrpc.createUser                     sample  314350   3.054 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.218           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.627           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.448           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.742           ms/op
ClientGrpc.existUser                      sample  315834   3.039 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.634           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.128           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.905           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  304912   3.147 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.601           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.026           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.712           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.067           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.778           ms/op
ClientGrpc.listUser                       sample  235923   4.070 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.968           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.996           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.940           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.396           ms/op
