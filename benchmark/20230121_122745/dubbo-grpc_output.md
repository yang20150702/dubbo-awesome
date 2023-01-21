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
# Warmup Iteration   1: 4.640 ops/ms
# Warmup Iteration   2: 9.451 ops/ms
# Warmup Iteration   3: 10.162 ops/ms
Iteration   1: 10.160 ops/ms
Iteration   2: 10.278 ops/ms
Iteration   3: 10.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.289 ±(99.9%) 2.469 ops/ms [Average]
  (min, avg, max) = (10.160, 10.289, 10.430), stdev = 0.135
  CI (99.9%): [7.820, 12.759] (assumes normal distribution)


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
# Warmup Iteration   1: 7.926 ops/ms
# Warmup Iteration   2: 10.512 ops/ms
# Warmup Iteration   3: 10.677 ops/ms
Iteration   1: 10.741 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.766 ±(99.9%) 3.306 ops/ms [Average]
  (min, avg, max) = (10.599, 10.766, 10.959), stdev = 0.181
  CI (99.9%): [7.460, 14.073] (assumes normal distribution)


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
# Warmup Iteration   1: 7.632 ops/ms
# Warmup Iteration   2: 10.410 ops/ms
# Warmup Iteration   3: 10.437 ops/ms
Iteration   1: 10.398 ops/ms
Iteration   2: 10.416 ops/ms
Iteration   3: 10.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.392 ±(99.9%) 0.518 ops/ms [Average]
  (min, avg, max) = (10.361, 10.392, 10.416), stdev = 0.028
  CI (99.9%): [9.874, 10.910] (assumes normal distribution)


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
# Warmup Iteration   1: 5.697 ops/ms
# Warmup Iteration   2: 7.743 ops/ms
# Warmup Iteration   3: 7.988 ops/ms
Iteration   1: 7.779 ops/ms
Iteration   2: 8.193 ops/ms
Iteration   3: 7.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.964 ±(99.9%) 3.836 ops/ms [Average]
  (min, avg, max) = (7.779, 7.964, 8.193), stdev = 0.210
  CI (99.9%): [4.128, 11.800] (assumes normal distribution)


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.005 ms/op
Iteration   1: 3.094 ±(99.9%) 0.002 ms/op
Iteration   2: 3.135 ±(99.9%) 0.001 ms/op
Iteration   3: 3.174 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.134 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (3.094, 3.134, 3.174), stdev = 0.040
  CI (99.9%): [2.409, 3.860] (assumes normal distribution)


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.002 ms/op
Iteration   1: 3.010 ±(99.9%) 0.003 ms/op
Iteration   2: 2.937 ±(99.9%) 0.003 ms/op
Iteration   3: 2.946 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.964 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (2.937, 2.964, 3.010), stdev = 0.040
  CI (99.9%): [2.236, 3.693] (assumes normal distribution)


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
# Warmup Iteration   1: 3.641 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.002 ms/op
Iteration   1: 3.134 ±(99.9%) 0.002 ms/op
Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
Iteration   3: 3.051 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 0.761 ms/op [Average]
  (min, avg, max) = (3.051, 3.091, 3.134), stdev = 0.042
  CI (99.9%): [2.330, 3.852] (assumes normal distribution)


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
# Warmup Iteration   1: 4.797 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.011 ms/op
Iteration   1: 4.052 ±(99.9%) 0.019 ms/op
Iteration   2: 3.985 ±(99.9%) 0.008 ms/op
Iteration   3: 4.006 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.014 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (3.985, 4.014, 4.052), stdev = 0.034
  CI (99.9%): [3.395, 4.634] (assumes normal distribution)


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.007 ms/op
Iteration   1: 3.039 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  7.137 ms/op
                 createUser·p0.9999: 11.926 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.408 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  10.268 ms/op
                 createUser·p0.9999: 13.195 ms/op
                 createUser·p1.00:   15.335 ms/op

Iteration   3: 3.156 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.205 ms/op
                 createUser·p0.9999: 53.412 ms/op
                 createUser·p1.00:   54.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309751
  mean =      3.102 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 308801 
    [ 5.000, 10.000) = 713 
    [10.000, 15.000) = 189 
    [15.000, 20.000) = 16 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     51.355 ms/op
     p(99.9990) =     53.733 ms/op
     p(99.9999) =     54.002 ms/op
    p(100.0000) =     54.002 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.473 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  5.913 ms/op
                 existUser·p0.9999: 16.225 ms/op
                 existUser·p1.00:   16.663 ms/op

Iteration   2: 2.916 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  9.967 ms/op
                 existUser·p0.9999: 13.730 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  5.601 ms/op
                 existUser·p0.9999: 14.217 ms/op
                 existUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321736
  mean =      2.984 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2954 
    [ 1.250,  2.500) = 42159 
    [ 2.500,  3.750) = 253748 
    [ 3.750,  5.000) = 21992 
    [ 5.000,  6.250) = 400 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 87 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.481 ms/op
     p(99.9900) =     13.792 ms/op
     p(99.9990) =     16.554 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 4.140 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.089 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.630 ms/op
                 getUser·p0.9999: 14.394 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.604 ms/op
                 getUser·p0.9999: 16.772 ms/op
                 getUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312752
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25848 
    [ 2.500,  5.000) = 285982 
    [ 5.000,  7.500) = 652 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.900 ms/op
     p(99.9900) =     21.347 ms/op
     p(99.9990) =     22.470 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 5.322 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.012 ms/op
Iteration   1: 4.037 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  13.239 ms/op
                 listUser·p0.9999: 19.139 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   2: 4.004 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.765 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  18.191 ms/op
                 listUser·p0.9999: 23.397 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   3: 4.226 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234879
  mean =      4.087 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5534 
    [ 2.500,  5.000) = 188223 
    [ 5.000,  7.500) = 39772 
    [ 7.500, 10.000) = 979 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.407 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     26.693 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.289 ± 2.469  ops/ms
ClientGrpc.existUser                       thrpt       3  10.766 ± 3.306  ops/ms
ClientGrpc.getUser                         thrpt       3  10.392 ± 0.518  ops/ms
ClientGrpc.listUser                        thrpt       3   7.964 ± 3.836  ops/ms
ClientGrpc.createUser                       avgt       3   3.134 ± 0.725   ms/op
ClientGrpc.existUser                        avgt       3   2.964 ± 0.728   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 0.761   ms/op
ClientGrpc.listUser                         avgt       3   4.014 ± 0.619   ms/op
ClientGrpc.createUser                     sample  309751   3.102 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.408           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          51.355           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          54.002           ms/op
ClientGrpc.existUser                      sample  321736   2.984 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.473           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.481           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.792           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.663           ms/op
ClientGrpc.getUser                        sample  312752   3.071 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.726           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.900           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.347           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.577           ms/op
ClientGrpc.listUser                       sample  234879   4.087 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.765           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.317           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.407           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.315           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.903           ms/op
