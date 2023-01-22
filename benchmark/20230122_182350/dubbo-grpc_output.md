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
# Warmup Iteration   1: 5.211 ops/ms
# Warmup Iteration   2: 9.750 ops/ms
# Warmup Iteration   3: 10.227 ops/ms
Iteration   1: 10.585 ops/ms
Iteration   2: 10.551 ops/ms
Iteration   3: 10.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.469 ±(99.9%) 3.150 ops/ms [Average]
  (min, avg, max) = (10.270, 10.469, 10.585), stdev = 0.173
  CI (99.9%): [7.319, 13.619] (assumes normal distribution)


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
# Warmup Iteration   1: 8.139 ops/ms
# Warmup Iteration   2: 10.656 ops/ms
# Warmup Iteration   3: 10.785 ops/ms
Iteration   1: 10.969 ops/ms
Iteration   2: 10.930 ops/ms
Iteration   3: 11.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.982 ±(99.9%) 1.081 ops/ms [Average]
  (min, avg, max) = (10.930, 10.982, 11.046), stdev = 0.059
  CI (99.9%): [9.900, 12.063] (assumes normal distribution)


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
# Warmup Iteration   1: 7.248 ops/ms
# Warmup Iteration   2: 10.275 ops/ms
# Warmup Iteration   3: 10.507 ops/ms
Iteration   1: 10.640 ops/ms
Iteration   2: 10.510 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.566 ±(99.9%) 1.217 ops/ms [Average]
  (min, avg, max) = (10.510, 10.566, 10.640), stdev = 0.067
  CI (99.9%): [9.350, 11.783] (assumes normal distribution)


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
# Warmup Iteration   1: 6.694 ops/ms
# Warmup Iteration   2: 7.744 ops/ms
# Warmup Iteration   3: 8.187 ops/ms
Iteration   1: 7.962 ops/ms
Iteration   2: 7.838 ops/ms
Iteration   3: 7.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.889 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (7.838, 7.889, 7.962), stdev = 0.065
  CI (99.9%): [6.712, 9.066] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.003 ms/op
Iteration   1: 3.139 ±(99.9%) 0.002 ms/op
Iteration   2: 3.145 ±(99.9%) 0.002 ms/op
Iteration   3: 3.161 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.148 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (3.139, 3.148, 3.161), stdev = 0.012
  CI (99.9%): [2.938, 3.359] (assumes normal distribution)


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
# Warmup Iteration   1: 3.588 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.003 ms/op
Iteration   1: 2.882 ±(99.9%) 0.003 ms/op
Iteration   2: 2.935 ±(99.9%) 0.002 ms/op
Iteration   3: 2.903 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (2.882, 2.907, 2.935), stdev = 0.027
  CI (99.9%): [2.417, 3.396] (assumes normal distribution)


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
# Warmup Iteration   1: 3.946 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.003 ms/op
Iteration   1: 2.982 ±(99.9%) 0.002 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.040 ±(99.9%) 0.959 ms/op [Average]
  (min, avg, max) = (2.982, 3.040, 3.084), stdev = 0.053
  CI (99.9%): [2.082, 3.999] (assumes normal distribution)


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.008 ms/op
Iteration   1: 3.895 ±(99.9%) 0.011 ms/op
Iteration   2: 3.824 ±(99.9%) 0.008 ms/op
Iteration   3: 3.915 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.878 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (3.824, 3.878, 3.915), stdev = 0.048
  CI (99.9%): [3.010, 4.747] (assumes normal distribution)


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
Iteration   1: 3.084 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.278 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  8.008 ms/op
                 createUser·p0.9999: 15.127 ms/op
                 createUser·p1.00:   15.401 ms/op

Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.124 ms/op
                 createUser·p0.9999: 15.581 ms/op
                 createUser·p1.00:   15.942 ms/op

Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.583 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  10.239 ms/op
                 createUser·p0.9999: 17.023 ms/op
                 createUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309172
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1276 
    [ 1.250,  2.500) = 26238 
    [ 2.500,  3.750) = 248909 
    [ 3.750,  5.000) = 31736 
    [ 5.000,  6.250) = 407 
    [ 6.250,  7.500) = 230 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 115 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.278 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.730 ms/op
     p(99.9900) =     15.765 ms/op
     p(99.9990) =     17.459 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.493 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  5.751 ms/op
                 existUser·p0.9999: 17.039 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 2.965 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  9.309 ms/op
                 existUser·p0.9999: 14.969 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.189 ms/op
                 existUser·p0.999:  6.999 ms/op
                 existUser·p0.9999: 16.056 ms/op
                 existUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324162
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2633 
    [ 1.250,  2.500) = 50610 
    [ 2.500,  3.750) = 246076 
    [ 3.750,  5.000) = 24029 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 143 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.100 ms/op
     p(99.9900) =     16.504 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 3.690 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.254 ms/op
                 getUser·p0.9999: 15.139 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  9.471 ms/op
                 getUser·p0.9999: 16.908 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.439 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  8.269 ms/op
                 getUser·p0.9999: 28.263 ms/op
                 getUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316331
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31148 
    [ 2.500,  5.000) = 284245 
    [ 5.000,  7.500) = 616 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     28.503 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 5.104 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.011 ms/op
Iteration   1: 4.026 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  13.075 ms/op
                 listUser·p0.9999: 15.424 ms/op
                 listUser·p1.00:   16.007 ms/op

Iteration   2: 3.997 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 4.007 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.748 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.756 ms/op
                 listUser·p0.999:  16.914 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239310
  mean =      4.010 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5667 
    [ 2.500,  5.000) = 200026 
    [ 5.000,  7.500) = 32401 
    [ 7.500, 10.000) = 818 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.626 ms/op
     p(99.9900) =     21.203 ms/op
     p(99.9990) =     22.060 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.469 ± 3.150  ops/ms
ClientGrpc.existUser                       thrpt       3  10.982 ± 1.081  ops/ms
ClientGrpc.getUser                         thrpt       3  10.566 ± 1.217  ops/ms
ClientGrpc.listUser                        thrpt       3   7.889 ± 1.177  ops/ms
ClientGrpc.createUser                       avgt       3   3.148 ± 0.211   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 0.489   ms/op
ClientGrpc.getUser                          avgt       3   3.040 ± 0.959   ms/op
ClientGrpc.listUser                         avgt       3   3.878 ± 0.869   ms/op
ClientGrpc.createUser                     sample  309172   3.104 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.278           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.730           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.765           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.564           ms/op
ClientGrpc.existUser                      sample  324162   2.961 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.554           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.854           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.100           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.504           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.269           ms/op
ClientGrpc.getUser                        sample  316331   3.033 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.439           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.864           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.919           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.098           ms/op
ClientGrpc.listUser                       sample  239310   4.010 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.748           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.626           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.203           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.184           ms/op
