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
# Warmup Iteration   1: 4.869 ops/ms
# Warmup Iteration   2: 9.515 ops/ms
# Warmup Iteration   3: 10.295 ops/ms
Iteration   1: 10.838 ops/ms
Iteration   2: 10.733 ops/ms
Iteration   3: 10.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.808 ±(99.9%) 1.198 ops/ms [Average]
  (min, avg, max) = (10.733, 10.808, 10.854), stdev = 0.066
  CI (99.9%): [9.610, 12.007] (assumes normal distribution)


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
# Warmup Iteration   1: 8.917 ops/ms
# Warmup Iteration   2: 10.926 ops/ms
# Warmup Iteration   3: 11.256 ops/ms
Iteration   1: 11.140 ops/ms
Iteration   2: 11.228 ops/ms
Iteration   3: 11.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.261 ±(99.9%) 2.569 ops/ms [Average]
  (min, avg, max) = (11.140, 11.261, 11.416), stdev = 0.141
  CI (99.9%): [8.692, 13.831] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.974 ops/ms
# Warmup Iteration   2: 10.532 ops/ms
# Warmup Iteration   3: 10.861 ops/ms
Iteration   1: 10.717 ops/ms
Iteration   2: 10.894 ops/ms
Iteration   3: 10.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.809 ±(99.9%) 1.625 ops/ms [Average]
  (min, avg, max) = (10.717, 10.809, 10.894), stdev = 0.089
  CI (99.9%): [9.184, 12.435] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.953 ops/ms
# Warmup Iteration   2: 8.198 ops/ms
# Warmup Iteration   3: 8.408 ops/ms
Iteration   1: 8.306 ops/ms
Iteration   2: 8.262 ops/ms
Iteration   3: 8.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.330 ±(99.9%) 1.500 ops/ms [Average]
  (min, avg, max) = (8.262, 8.330, 8.422), stdev = 0.082
  CI (99.9%): [6.830, 9.831] (assumes normal distribution)


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.002 ms/op
Iteration   1: 2.909 ±(99.9%) 0.003 ms/op
Iteration   2: 2.940 ±(99.9%) 0.002 ms/op
Iteration   3: 2.926 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.925 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.909, 2.925, 2.940), stdev = 0.015
  CI (99.9%): [2.644, 3.207] (assumes normal distribution)


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.939 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 2.812 ±(99.9%) 0.003 ms/op
Iteration   1: 2.720 ±(99.9%) 0.004 ms/op
Iteration   2: 2.846 ±(99.9%) 0.004 ms/op
Iteration   3: 2.823 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.796 ±(99.9%) 1.222 ms/op [Average]
  (min, avg, max) = (2.720, 2.796, 2.846), stdev = 0.067
  CI (99.9%): [1.574, 4.018] (assumes normal distribution)


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.004 ms/op
Iteration   1: 2.937 ±(99.9%) 0.003 ms/op
Iteration   2: 2.933 ±(99.9%) 0.003 ms/op
Iteration   3: 2.897 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.923 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (2.897, 2.923, 2.937), stdev = 0.022
  CI (99.9%): [2.521, 3.324] (assumes normal distribution)


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.038 ms/op
Iteration   1: 3.878 ±(99.9%) 0.029 ms/op
Iteration   2: 3.889 ±(99.9%) 0.017 ms/op
Iteration   3: 3.868 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.878 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (3.868, 3.878, 3.889), stdev = 0.011
  CI (99.9%): [3.687, 4.070] (assumes normal distribution)


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
Iteration   1: 2.946 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.031 ms/op
                 createUser·p0.9999: 12.557 ms/op
                 createUser·p1.00:   12.911 ms/op

Iteration   2: 2.975 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  6.832 ms/op
                 createUser·p0.9999: 22.618 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 2.979 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 25.707 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323637
  mean =      2.966 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36068 
    [ 2.500,  5.000) = 285911 
    [ 5.000,  7.500) = 1354 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.330 ms/op
     p(99.9900) =     24.156 ms/op
     p(99.9990) =     25.970 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.883 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.824 ±(99.9%) 0.006 ms/op
Iteration   1: 2.877 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.152 ms/op
                 existUser·p0.9999: 17.629 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 2.836 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 14.118 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   3: 2.819 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.168 ms/op
                 existUser·p0.9999: 14.625 ms/op
                 existUser·p1.00:   15.024 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337393
  mean =      2.844 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3704 
    [ 1.250,  2.500) = 47246 
    [ 2.500,  3.750) = 278194 
    [ 3.750,  5.000) = 7171 
    [ 5.000,  6.250) = 572 
    [ 6.250,  7.500) = 133 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.932 ms/op
     p(99.9900) =     14.988 ms/op
     p(99.9990) =     17.834 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.532 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.774 ms/op
                 getUser·p0.9999: 19.735 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.147 ms/op
                 getUser·p0.999:  6.226 ms/op
                 getUser·p0.9999: 19.413 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   3: 2.915 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.391 ms/op
                 getUser·p0.9999: 16.401 ms/op
                 getUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325006
  mean =      2.953 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2669 
    [ 1.250,  2.500) = 32149 
    [ 2.500,  3.750) = 275046 
    [ 3.750,  5.000) = 14012 
    [ 5.000,  6.250) = 634 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.873 ms/op
     p(99.9900) =     19.382 ms/op
     p(99.9990) =     19.915 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 4.999 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.010 ms/op
Iteration   1: 3.836 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  11.804 ms/op
                 listUser·p0.9999: 13.976 ms/op
                 listUser·p1.00:   14.254 ms/op

Iteration   2: 3.846 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  12.843 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 3.949 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 16.703 ms/op
                 listUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247654
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6004 
    [ 2.500,  5.000) = 218528 
    [ 5.000,  7.500) = 21935 
    [ 7.500, 10.000) = 785 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     21.045 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.808 ± 1.198  ops/ms
ClientGrpc.existUser                       thrpt       3  11.261 ± 2.569  ops/ms
ClientGrpc.getUser                         thrpt       3  10.809 ± 1.625  ops/ms
ClientGrpc.listUser                        thrpt       3   8.330 ± 1.500  ops/ms
ClientGrpc.createUser                       avgt       3   2.925 ± 0.281   ms/op
ClientGrpc.existUser                        avgt       3   2.796 ± 1.222   ms/op
ClientGrpc.getUser                          avgt       3   2.923 ± 0.402   ms/op
ClientGrpc.listUser                         avgt       3   3.878 ± 0.192   ms/op
ClientGrpc.createUser                     sample  323637   2.966 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.546           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.937           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.330           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.156           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.051           ms/op
ClientGrpc.existUser                      sample  337393   2.844 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.602           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.932           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.988           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  325006   2.953 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.532           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.957           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.873           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.382           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.988           ms/op
ClientGrpc.listUser                       sample  247654   3.877 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.840           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.723           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.845           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.045           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.675           ms/op
