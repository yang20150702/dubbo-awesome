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
# Warmup Iteration   1: 4.688 ops/ms
# Warmup Iteration   2: 9.065 ops/ms
# Warmup Iteration   3: 10.347 ops/ms
Iteration   1: 10.738 ops/ms
Iteration   2: 10.555 ops/ms
Iteration   3: 10.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.655 ±(99.9%) 1.688 ops/ms [Average]
  (min, avg, max) = (10.555, 10.655, 10.738), stdev = 0.093
  CI (99.9%): [8.967, 12.343] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.888 ops/ms
# Warmup Iteration   2: 10.684 ops/ms
# Warmup Iteration   3: 11.068 ops/ms
Iteration   1: 11.004 ops/ms
Iteration   2: 11.248 ops/ms
Iteration   3: 10.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.077 ±(99.9%) 2.710 ops/ms [Average]
  (min, avg, max) = (10.979, 11.077, 11.248), stdev = 0.149
  CI (99.9%): [8.368, 13.787] (assumes normal distribution)


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
# Warmup Iteration   1: 7.065 ops/ms
# Warmup Iteration   2: 10.159 ops/ms
# Warmup Iteration   3: 10.461 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.676 ops/ms
Iteration   3: 10.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.656 ±(99.9%) 0.725 ops/ms [Average]
  (min, avg, max) = (10.610, 10.656, 10.682), stdev = 0.040
  CI (99.9%): [9.931, 11.381] (assumes normal distribution)


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
# Warmup Iteration   1: 5.358 ops/ms
# Warmup Iteration   2: 7.914 ops/ms
# Warmup Iteration   3: 7.926 ops/ms
Iteration   1: 7.946 ops/ms
Iteration   2: 8.027 ops/ms
Iteration   3: 7.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.982 ±(99.9%) 0.744 ops/ms [Average]
  (min, avg, max) = (7.946, 7.982, 8.027), stdev = 0.041
  CI (99.9%): [7.239, 8.726] (assumes normal distribution)


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.004 ms/op
Iteration   1: 2.982 ±(99.9%) 0.003 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.026 ±(99.9%) 0.790 ms/op [Average]
  (min, avg, max) = (2.982, 3.026, 3.068), stdev = 0.043
  CI (99.9%): [2.236, 3.815] (assumes normal distribution)


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.003 ms/op
Iteration   1: 3.008 ±(99.9%) 0.003 ms/op
Iteration   2: 3.001 ±(99.9%) 0.005 ms/op
Iteration   3: 3.161 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.056 ±(99.9%) 1.651 ms/op [Average]
  (min, avg, max) = (3.001, 3.056, 3.161), stdev = 0.090
  CI (99.9%): [1.406, 4.707] (assumes normal distribution)


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.002 ms/op
Iteration   1: 2.986 ±(99.9%) 0.003 ms/op
Iteration   2: 2.955 ±(99.9%) 0.003 ms/op
Iteration   3: 2.907 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.949 ±(99.9%) 0.732 ms/op [Average]
  (min, avg, max) = (2.907, 2.949, 2.986), stdev = 0.040
  CI (99.9%): [2.217, 3.681] (assumes normal distribution)


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
# Warmup Iteration   1: 5.073 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.014 ms/op
Iteration   1: 3.862 ±(99.9%) 0.014 ms/op
Iteration   2: 3.907 ±(99.9%) 0.014 ms/op
Iteration   3: 3.835 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.868 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (3.835, 3.868, 3.907), stdev = 0.036
  CI (99.9%): [3.207, 4.529] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.909 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.607 ms/op
                 createUser·p0.50:   2.879 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  6.940 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   18.383 ms/op

Iteration   2: 2.958 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  7.422 ms/op
                 createUser·p0.9999: 23.331 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  10.486 ms/op
                 createUser·p0.9999: 25.730 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325949
  mean =      2.946 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36634 
    [ 2.500,  5.000) = 288196 
    [ 5.000,  7.500) = 801 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =     23.627 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 3.506 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.837 ±(99.9%) 0.006 ms/op
Iteration   1: 2.798 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.472 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.342 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  6.205 ms/op
                 existUser·p0.9999: 12.339 ms/op
                 existUser·p1.00:   12.599 ms/op

Iteration   2: 2.899 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  5.311 ms/op
                 existUser·p0.9999: 12.484 ms/op
                 existUser·p1.00:   12.763 ms/op

Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.987 ms/op
                 existUser·p0.9999: 14.296 ms/op
                 existUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336024
  mean =      2.856 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3644 
    [ 1.250,  2.500) = 47844 
    [ 2.500,  3.750) = 275007 
    [ 3.750,  5.000) = 8517 
    [ 5.000,  6.250) = 505 
    [ 6.250,  7.500) = 227 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.135 ms/op
     p(99.9900) =     13.874 ms/op
     p(99.9990) =     16.062 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
Iteration   1: 2.966 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.729 ms/op
                 getUser·p0.9999: 18.331 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.282 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  6.305 ms/op
                 getUser·p0.9999: 13.919 ms/op
                 getUser·p1.00:   15.942 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.505 ms/op
                 getUser·p0.9999: 14.947 ms/op
                 getUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319605
  mean =      3.004 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24937 
    [ 2.500,  5.000) = 293481 
    [ 5.000,  7.500) = 872 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.474 ms/op
     p(99.9900) =     17.697 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 4.829 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.010 ms/op
Iteration   1: 3.860 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  12.386 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 3.817 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.485 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.555 ms/op
                 listUser·p0.9999: 17.767 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 3.903 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.637 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 21.592 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249060
  mean =      3.860 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3577 
    [ 2.500,  5.000) = 226771 
    [ 5.000,  7.500) = 17635 
    [ 7.500, 10.000) = 624 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     19.694 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.655 ± 1.688  ops/ms
ClientGrpc.existUser                       thrpt       3  11.077 ± 2.710  ops/ms
ClientGrpc.getUser                         thrpt       3  10.656 ± 0.725  ops/ms
ClientGrpc.listUser                        thrpt       3   7.982 ± 0.744  ops/ms
ClientGrpc.createUser                       avgt       3   3.026 ± 0.790   ms/op
ClientGrpc.existUser                        avgt       3   3.056 ± 1.651   ms/op
ClientGrpc.getUser                          avgt       3   2.949 ± 0.732   ms/op
ClientGrpc.listUser                         avgt       3   3.868 ± 0.661   ms/op
ClientGrpc.createUser                     sample  325949   2.946 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.607           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.933           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.438           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.627           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.083           ms/op
ClientGrpc.existUser                      sample  336024   2.856 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.472           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.135           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.874           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.269           ms/op
ClientGrpc.getUser                        sample  319605   3.004 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.282           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.474           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.697           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.185           ms/op
ClientGrpc.listUser                       sample  249060   3.860 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.485           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.025           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.694           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.758           ms/op
