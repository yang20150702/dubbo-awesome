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
# Warmup Iteration   1: 4.075 ops/ms
# Warmup Iteration   2: 9.351 ops/ms
# Warmup Iteration   3: 10.192 ops/ms
Iteration   1: 10.914 ops/ms
Iteration   2: 10.635 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.719 ±(99.9%) 3.089 ops/ms [Average]
  (min, avg, max) = (10.608, 10.719, 10.914), stdev = 0.169
  CI (99.9%): [7.630, 13.808] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.511 ops/ms
# Warmup Iteration   2: 10.704 ops/ms
# Warmup Iteration   3: 11.026 ops/ms
Iteration   1: 11.131 ops/ms
Iteration   2: 11.015 ops/ms
Iteration   3: 11.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.075 ±(99.9%) 1.063 ops/ms [Average]
  (min, avg, max) = (11.015, 11.075, 11.131), stdev = 0.058
  CI (99.9%): [10.012, 12.138] (assumes normal distribution)


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
# Warmup Iteration   1: 7.058 ops/ms
# Warmup Iteration   2: 10.388 ops/ms
# Warmup Iteration   3: 10.758 ops/ms
Iteration   1: 10.443 ops/ms
Iteration   2: 10.755 ops/ms
Iteration   3: 10.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.678 ±(99.9%) 3.774 ops/ms [Average]
  (min, avg, max) = (10.443, 10.678, 10.835), stdev = 0.207
  CI (99.9%): [6.903, 14.452] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.700 ops/ms
# Warmup Iteration   2: 8.034 ops/ms
# Warmup Iteration   3: 8.279 ops/ms
Iteration   1: 8.141 ops/ms
Iteration   2: 7.994 ops/ms
Iteration   3: 8.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.094 ±(99.9%) 1.583 ops/ms [Average]
  (min, avg, max) = (7.994, 8.094, 8.146), stdev = 0.087
  CI (99.9%): [6.510, 9.677] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.002 ms/op
Iteration   1: 2.982 ±(99.9%) 0.004 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 3.037 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.015 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (2.982, 3.015, 3.037), stdev = 0.029
  CI (99.9%): [2.482, 3.548] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.858 ±(99.9%) 0.003 ms/op
Iteration   1: 2.866 ±(99.9%) 0.002 ms/op
Iteration   2: 2.845 ±(99.9%) 0.002 ms/op
Iteration   3: 2.752 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.821 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (2.752, 2.821, 2.866), stdev = 0.061
  CI (99.9%): [1.709, 3.933] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 2.937 ±(99.9%) 0.003 ms/op
Iteration   2: 3.000 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.975 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (2.937, 2.975, 3.000), stdev = 0.033
  CI (99.9%): [2.369, 3.580] (assumes normal distribution)


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
# Warmup Iteration   1: 5.016 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.014 ms/op
Iteration   1: 3.909 ±(99.9%) 0.037 ms/op
Iteration   2: 3.892 ±(99.9%) 0.032 ms/op
Iteration   3: 3.912 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.904 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.892, 3.904, 3.912), stdev = 0.010
  CI (99.9%): [3.716, 4.093] (assumes normal distribution)


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.005 ms/op
Iteration   1: 2.951 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.546 ms/op
                 createUser·p0.9999: 12.618 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   2: 3.003 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.359 ms/op
                 createUser·p0.9999: 14.648 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   3: 2.962 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.457 ms/op
                 createUser·p0.99:   4.051 ms/op
                 createUser·p0.999:  7.233 ms/op
                 createUser·p0.9999: 18.678 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323098
  mean =      2.971 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 548 
    [ 1.250,  2.500) = 23513 
    [ 2.500,  3.750) = 289297 
    [ 3.750,  5.000) = 8459 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.290 ms/op
     p(99.9900) =     17.590 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 3.997 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.871 ±(99.9%) 0.005 ms/op
Iteration   1: 2.897 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.498 ms/op
                 existUser·p0.9999: 11.829 ms/op
                 existUser·p1.00:   12.009 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.512 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  8.414 ms/op
                 existUser·p0.9999: 15.516 ms/op
                 existUser·p1.00:   15.909 ms/op

Iteration   3: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   3.990 ms/op
                 existUser·p0.999:  8.151 ms/op
                 existUser·p0.9999: 16.464 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331005
  mean =      2.900 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1642 
    [ 1.250,  2.500) = 38591 
    [ 2.500,  3.750) = 281616 
    [ 3.750,  5.000) = 8109 
    [ 5.000,  6.250) = 471 
    [ 6.250,  7.500) = 226 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.512 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     16.217 ms/op
     p(99.9990) =     16.597 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
Iteration   1: 2.979 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  6.881 ms/op
                 getUser·p0.9999: 17.703 ms/op
                 getUser·p1.00:   18.219 ms/op

Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.049 ms/op
                 getUser·p0.9999: 15.922 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.761 ms/op
                 getUser·p0.9999: 18.823 ms/op
                 getUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319320
  mean =      3.004 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 748 
    [ 1.250,  2.500) = 29856 
    [ 2.500,  3.750) = 271851 
    [ 3.750,  5.000) = 15353 
    [ 5.000,  6.250) = 982 
    [ 6.250,  7.500) = 289 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      6.857 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     19.261 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 5.827 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.010 ms/op
Iteration   1: 3.921 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.140 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 3.932 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.801 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 20.503 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 3.918 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 17.263 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244862
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3219 
    [ 2.500,  5.000) = 221897 
    [ 5.000,  7.500) = 18422 
    [ 7.500, 10.000) = 757 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.537 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.719 ± 3.089  ops/ms
ClientGrpc.existUser                       thrpt       3  11.075 ± 1.063  ops/ms
ClientGrpc.getUser                         thrpt       3  10.678 ± 3.774  ops/ms
ClientGrpc.listUser                        thrpt       3   8.094 ± 1.583  ops/ms
ClientGrpc.createUser                       avgt       3   3.015 ± 0.533   ms/op
ClientGrpc.existUser                        avgt       3   2.821 ± 1.112   ms/op
ClientGrpc.getUser                          avgt       3   2.975 ± 0.606   ms/op
ClientGrpc.listUser                         avgt       3   3.904 ± 0.189   ms/op
ClientGrpc.createUser                     sample  323098   2.971 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.556           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.379           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.290           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.590           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.907           ms/op
ClientGrpc.existUser                      sample  331005   2.900 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.512           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.799           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.217           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.334           ms/op
ClientGrpc.getUser                        sample  319320   3.004 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.696           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.857           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.564           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.366           ms/op
ClientGrpc.listUser                       sample  244862   3.924 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.762           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.537           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.678           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.168           ms/op
