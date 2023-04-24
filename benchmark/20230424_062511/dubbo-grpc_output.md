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
# Warmup Iteration   1: 4.215 ops/ms
# Warmup Iteration   2: 9.412 ops/ms
# Warmup Iteration   3: 10.145 ops/ms
Iteration   1: 10.506 ops/ms
Iteration   2: 10.624 ops/ms
Iteration   3: 10.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.589 ±(99.9%) 1.305 ops/ms [Average]
  (min, avg, max) = (10.506, 10.589, 10.635), stdev = 0.072
  CI (99.9%): [9.284, 11.894] (assumes normal distribution)


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
# Warmup Iteration   1: 7.534 ops/ms
# Warmup Iteration   2: 10.710 ops/ms
# Warmup Iteration   3: 11.113 ops/ms
Iteration   1: 11.152 ops/ms
Iteration   2: 10.878 ops/ms
Iteration   3: 11.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.072 ±(99.9%) 3.074 ops/ms [Average]
  (min, avg, max) = (10.878, 11.072, 11.185), stdev = 0.168
  CI (99.9%): [7.998, 14.146] (assumes normal distribution)


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
# Warmup Iteration   1: 7.488 ops/ms
# Warmup Iteration   2: 10.218 ops/ms
# Warmup Iteration   3: 10.571 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.594 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (10.530, 10.594, 10.691), stdev = 0.086
  CI (99.9%): [9.033, 12.154] (assumes normal distribution)


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
# Warmup Iteration   1: 5.608 ops/ms
# Warmup Iteration   2: 7.943 ops/ms
# Warmup Iteration   3: 8.072 ops/ms
Iteration   1: 8.114 ops/ms
Iteration   2: 8.196 ops/ms
Iteration   3: 8.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.241 ±(99.9%) 2.830 ops/ms [Average]
  (min, avg, max) = (8.114, 8.241, 8.414), stdev = 0.155
  CI (99.9%): [5.412, 11.071] (assumes normal distribution)


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
# Warmup Iteration   1: 4.457 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.003 ms/op
Iteration   1: 2.938 ±(99.9%) 0.004 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 3.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.992 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (2.938, 2.992, 3.020), stdev = 0.047
  CI (99.9%): [2.137, 3.847] (assumes normal distribution)


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
# Warmup Iteration   1: 4.147 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.958 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.785 ±(99.9%) 0.004 ms/op
Iteration   1: 2.849 ±(99.9%) 0.002 ms/op
Iteration   2: 2.872 ±(99.9%) 0.002 ms/op
Iteration   3: 2.892 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.871 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (2.849, 2.871, 2.892), stdev = 0.022
  CI (99.9%): [2.471, 3.271] (assumes normal distribution)


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
# Warmup Iteration   1: 4.352 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.003 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
Iteration   3: 3.041 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.022 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (2.990, 3.022, 3.041), stdev = 0.028
  CI (99.9%): [2.515, 3.528] (assumes normal distribution)


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
# Warmup Iteration   1: 5.187 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.027 ms/op
Iteration   1: 3.884 ±(99.9%) 0.009 ms/op
Iteration   2: 3.828 ±(99.9%) 0.008 ms/op
Iteration   3: 3.966 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.893 ±(99.9%) 1.272 ms/op [Average]
  (min, avg, max) = (3.828, 3.893, 3.966), stdev = 0.070
  CI (99.9%): [2.620, 5.165] (assumes normal distribution)


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.672 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 15.244 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  9.829 ms/op
                 createUser·p0.9999: 17.288 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318173
  mean =      3.014 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25261 
    [ 2.500,  5.000) = 291320 
    [ 5.000,  7.500) = 1091 
    [ 7.500, 10.000) = 201 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     21.222 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.006 ms/op
Iteration   1: 2.876 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.492 ms/op
                 existUser·p0.999:  7.306 ms/op
                 existUser·p0.9999: 20.050 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   2: 2.893 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.430 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   3.918 ms/op
                 existUser·p0.999:  5.464 ms/op
                 existUser·p0.9999: 31.785 ms/op
                 existUser·p1.00:   32.014 ms/op

Iteration   3: 2.904 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.287 ms/op
                 existUser·p0.9999: 26.607 ms/op
                 existUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332049
  mean =      2.891 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39662 
    [ 2.500,  5.000) = 291218 
    [ 5.000,  7.500) = 955 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.430 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.849 ms/op
     p(99.9900) =     27.158 ms/op
     p(99.9990) =     31.873 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  8.444 ms/op
                 getUser·p0.9999: 12.255 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.469 ms/op
                 getUser·p0.9999: 17.940 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  9.142 ms/op
                 getUser·p0.9999: 16.374 ms/op
                 getUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317922
  mean =      3.020 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 533 
    [ 1.250,  2.500) = 19811 
    [ 2.500,  3.750) = 281973 
    [ 3.750,  5.000) = 14481 
    [ 5.000,  6.250) = 548 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.200 ms/op
     p(99.9900) =     17.060 ms/op
     p(99.9990) =     18.082 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 5.293 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.012 ms/op
Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  12.771 ms/op
                 listUser·p0.9999: 16.037 ms/op
                 listUser·p1.00:   16.335 ms/op

Iteration   2: 3.854 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  16.141 ms/op
                 listUser·p0.9999: 18.878 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   3: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.721 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  16.314 ms/op
                 listUser·p0.9999: 22.010 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247545
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3630 
    [ 2.500,  5.000) = 223476 
    [ 5.000,  7.500) = 19233 
    [ 7.500, 10.000) = 727 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     20.562 ms/op
     p(99.9990) =     22.415 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.589 ± 1.305  ops/ms
ClientGrpc.existUser                       thrpt       3  11.072 ± 3.074  ops/ms
ClientGrpc.getUser                         thrpt       3  10.594 ± 1.560  ops/ms
ClientGrpc.listUser                        thrpt       3   8.241 ± 2.830  ops/ms
ClientGrpc.createUser                       avgt       3   2.992 ± 0.855   ms/op
ClientGrpc.existUser                        avgt       3   2.871 ± 0.400   ms/op
ClientGrpc.getUser                          avgt       3   3.022 ± 0.507   ms/op
ClientGrpc.listUser                         avgt       3   3.893 ± 1.272   ms/op
ClientGrpc.createUser                     sample  318173   3.014 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.555           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.650           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.629           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.741           ms/op
ClientGrpc.existUser                      sample  332049   2.891 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.430           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.849           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.158           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.014           ms/op
ClientGrpc.getUser                        sample  317922   3.020 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.714           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.200           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.060           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.121           ms/op
ClientGrpc.listUser                       sample  247545   3.877 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.721           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.746           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.562           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
