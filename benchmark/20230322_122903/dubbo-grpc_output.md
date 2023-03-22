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
# Warmup Iteration   1: 4.668 ops/ms
# Warmup Iteration   2: 9.131 ops/ms
# Warmup Iteration   3: 10.130 ops/ms
Iteration   1: 10.757 ops/ms
Iteration   2: 10.771 ops/ms
Iteration   3: 10.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.813 ±(99.9%) 1.555 ops/ms [Average]
  (min, avg, max) = (10.757, 10.813, 10.911), stdev = 0.085
  CI (99.9%): [9.258, 12.369] (assumes normal distribution)


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
# Warmup Iteration   1: 7.450 ops/ms
# Warmup Iteration   2: 10.935 ops/ms
# Warmup Iteration   3: 11.984 ops/ms
Iteration   1: 11.279 ops/ms
Iteration   2: 11.390 ops/ms
Iteration   3: 11.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.367 ±(99.9%) 1.438 ops/ms [Average]
  (min, avg, max) = (11.279, 11.367, 11.431), stdev = 0.079
  CI (99.9%): [9.929, 12.804] (assumes normal distribution)


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
# Warmup Iteration   1: 7.503 ops/ms
# Warmup Iteration   2: 10.409 ops/ms
# Warmup Iteration   3: 10.701 ops/ms
Iteration   1: 10.694 ops/ms
Iteration   2: 10.754 ops/ms
Iteration   3: 11.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.822 ±(99.9%) 3.146 ops/ms [Average]
  (min, avg, max) = (10.694, 10.822, 11.018), stdev = 0.172
  CI (99.9%): [7.676, 13.968] (assumes normal distribution)


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
# Warmup Iteration   1: 6.727 ops/ms
# Warmup Iteration   2: 7.871 ops/ms
# Warmup Iteration   3: 8.207 ops/ms
Iteration   1: 8.183 ops/ms
Iteration   2: 8.210 ops/ms
Iteration   3: 8.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.192 ±(99.9%) 0.279 ops/ms [Average]
  (min, avg, max) = (8.183, 8.192, 8.210), stdev = 0.015
  CI (99.9%): [7.913, 8.471] (assumes normal distribution)


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
# Warmup Iteration   1: 4.178 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.003 ms/op
Iteration   1: 2.948 ±(99.9%) 0.002 ms/op
Iteration   2: 2.967 ±(99.9%) 0.004 ms/op
Iteration   3: 2.975 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.963 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.948, 2.963, 2.975), stdev = 0.014
  CI (99.9%): [2.709, 3.217] (assumes normal distribution)


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
# Warmup Iteration   1: 3.615 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 2.925 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.849 ±(99.9%) 0.002 ms/op
Iteration   1: 2.881 ±(99.9%) 0.003 ms/op
Iteration   2: 2.823 ±(99.9%) 0.004 ms/op
Iteration   3: 2.837 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.847 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (2.823, 2.847, 2.881), stdev = 0.030
  CI (99.9%): [2.294, 3.399] (assumes normal distribution)


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.002 ms/op
Iteration   1: 2.977 ±(99.9%) 0.003 ms/op
Iteration   2: 2.956 ±(99.9%) 0.002 ms/op
Iteration   3: 2.941 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.958 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (2.941, 2.958, 2.977), stdev = 0.018
  CI (99.9%): [2.626, 3.290] (assumes normal distribution)


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
# Warmup Iteration   1: 4.447 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.008 ms/op
Iteration   1: 3.904 ±(99.9%) 0.009 ms/op
Iteration   2: 3.802 ±(99.9%) 0.009 ms/op
Iteration   3: 3.722 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.809 ±(99.9%) 1.665 ms/op [Average]
  (min, avg, max) = (3.722, 3.809, 3.904), stdev = 0.091
  CI (99.9%): [2.144, 5.474] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
Iteration   1: 2.943 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.851 ms/op
                 createUser·p0.9999: 11.174 ms/op
                 createUser·p1.00:   11.354 ms/op

Iteration   2: 2.955 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.676 ms/op
                 createUser·p0.9999: 12.802 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  10.494 ms/op
                 createUser·p0.9999: 14.569 ms/op
                 createUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324913
  mean =      2.953 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1495 
    [ 1.250,  2.500) = 24146 
    [ 2.500,  3.750) = 287748 
    [ 3.750,  5.000) = 10372 
    [ 5.000,  6.250) = 676 
    [ 6.250,  7.500) = 174 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.177 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     15.487 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.958 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.883 ±(99.9%) 0.005 ms/op
Iteration   1: 2.856 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.610 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.210 ms/op
                 existUser·p0.9999: 16.266 ms/op
                 existUser·p1.00:   16.466 ms/op

Iteration   2: 2.818 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.178 ms/op
                 existUser·p0.95:   3.334 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 13.587 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.804 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  12.742 ms/op
                 existUser·p0.9999: 14.587 ms/op
                 existUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 339839
  mean =      2.826 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3985 
    [ 1.250,  2.500) = 47468 
    [ 2.500,  3.750) = 279860 
    [ 3.750,  5.000) = 7487 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 142 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.240 ms/op
     p(95.0000) =      3.457 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     15.925 ms/op
     p(99.9990) =     16.427 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.565 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  6.547 ms/op
                 getUser·p0.9999: 12.440 ms/op
                 getUser·p1.00:   12.567 ms/op

Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.513 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.249 ms/op
                 getUser·p0.9999: 13.030 ms/op
                 getUser·p1.00:   13.238 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.467 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.356 ms/op
                 getUser·p0.9999: 15.712 ms/op
                 getUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322611
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1499 
    [ 1.250,  2.500) = 24096 
    [ 2.500,  3.750) = 284515 
    [ 3.750,  5.000) = 11557 
    [ 5.000,  6.250) = 523 
    [ 6.250,  7.500) = 164 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.835 ms/op
     p(99.9900) =     15.421 ms/op
     p(99.9990) =     15.778 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.011 ms/op
Iteration   1: 3.801 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  12.433 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 3.888 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.510 ms/op
                 listUser·p0.9999: 28.599 ms/op
                 listUser·p1.00:   29.000 ms/op

Iteration   3: 3.854 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  14.318 ms/op
                 listUser·p0.9999: 27.495 ms/op
                 listUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249666
  mean =      3.847 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5646 
    [ 2.500,  5.000) = 222677 
    [ 5.000,  7.500) = 20274 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     27.266 ms/op
     p(99.9990) =     28.902 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.813 ± 1.555  ops/ms
ClientGrpc.existUser                       thrpt       3  11.367 ± 1.438  ops/ms
ClientGrpc.getUser                         thrpt       3  10.822 ± 3.146  ops/ms
ClientGrpc.listUser                        thrpt       3   8.192 ± 0.279  ops/ms
ClientGrpc.createUser                       avgt       3   2.963 ± 0.254   ms/op
ClientGrpc.existUser                        avgt       3   2.847 ± 0.552   ms/op
ClientGrpc.getUser                          avgt       3   2.958 ± 0.332   ms/op
ClientGrpc.listUser                         avgt       3   3.809 ± 1.665   ms/op
ClientGrpc.createUser                     sample  324913   2.953 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.599           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.387           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.177           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          13.582           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.778           ms/op
ClientGrpc.existUser                      sample  339839   2.826 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.579           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.240           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.405           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.925           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.646           ms/op
ClientGrpc.getUser                        sample  322611   2.973 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.513           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.449           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.835           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.421           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.958           ms/op
ClientGrpc.listUser                       sample  249666   3.847 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.948           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.222           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.266           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.000           ms/op
