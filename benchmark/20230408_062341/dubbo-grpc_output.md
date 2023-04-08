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
# Warmup Iteration   1: 3.832 ops/ms
# Warmup Iteration   2: 8.601 ops/ms
# Warmup Iteration   3: 9.996 ops/ms
Iteration   1: 10.433 ops/ms
Iteration   2: 10.481 ops/ms
Iteration   3: 10.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.443 ±(99.9%) 0.622 ops/ms [Average]
  (min, avg, max) = (10.415, 10.443, 10.481), stdev = 0.034
  CI (99.9%): [9.821, 11.065] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.486 ops/ms
# Warmup Iteration   2: 10.452 ops/ms
# Warmup Iteration   3: 10.743 ops/ms
Iteration   1: 10.783 ops/ms
Iteration   2: 10.900 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.780 ±(99.9%) 2.201 ops/ms [Average]
  (min, avg, max) = (10.659, 10.780, 10.900), stdev = 0.121
  CI (99.9%): [8.580, 12.981] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.478 ops/ms
# Warmup Iteration   2: 9.538 ops/ms
# Warmup Iteration   3: 10.278 ops/ms
Iteration   1: 10.335 ops/ms
Iteration   2: 10.294 ops/ms
Iteration   3: 10.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.431 ±(99.9%) 3.691 ops/ms [Average]
  (min, avg, max) = (10.294, 10.431, 10.663), stdev = 0.202
  CI (99.9%): [6.740, 14.122] (assumes normal distribution)


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
# Warmup Iteration   1: 5.414 ops/ms
# Warmup Iteration   2: 7.561 ops/ms
# Warmup Iteration   3: 7.956 ops/ms
Iteration   1: 7.902 ops/ms
Iteration   2: 7.863 ops/ms
Iteration   3: 8.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.954 ±(99.9%) 2.286 ops/ms [Average]
  (min, avg, max) = (7.863, 7.954, 8.097), stdev = 0.125
  CI (99.9%): [5.668, 10.239] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.003 ms/op
Iteration   1: 3.147 ±(99.9%) 0.004 ms/op
Iteration   2: 3.132 ±(99.9%) 0.002 ms/op
Iteration   3: 3.121 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.134 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (3.121, 3.134, 3.147), stdev = 0.013
  CI (99.9%): [2.894, 3.373] (assumes normal distribution)


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.003 ms/op
Iteration   1: 2.980 ±(99.9%) 0.002 ms/op
Iteration   2: 2.974 ±(99.9%) 0.001 ms/op
Iteration   3: 2.971 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.975 ±(99.9%) 0.082 ms/op [Average]
  (min, avg, max) = (2.971, 2.975, 2.980), stdev = 0.004
  CI (99.9%): [2.893, 3.057] (assumes normal distribution)


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.003 ms/op
Iteration   1: 3.099 ±(99.9%) 0.003 ms/op
Iteration   2: 3.098 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.099 ±(99.9%) 0.035 ms/op [Average]
  (min, avg, max) = (3.098, 3.099, 3.102), stdev = 0.002
  CI (99.9%): [3.064, 3.135] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.723 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.012 ms/op
Iteration   1: 3.979 ±(99.9%) 0.007 ms/op
Iteration   2: 3.996 ±(99.9%) 0.011 ms/op
Iteration   3: 4.033 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.003 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.979, 4.003, 4.033), stdev = 0.028
  CI (99.9%): [3.492, 4.513] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.431 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.006 ms/op
Iteration   1: 3.129 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.776 ms/op
                 createUser·p0.9999: 13.054 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   2: 3.120 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.742 ms/op
                 createUser·p0.9999: 13.955 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.153 ms/op
                 createUser·p0.999:  8.984 ms/op
                 createUser·p0.9999: 23.003 ms/op
                 createUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308616
  mean =      3.112 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10697 
    [ 2.500,  5.000) = 296672 
    [ 5.000,  7.500) = 980 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.840 ms/op
     p(99.9900) =     22.090 ms/op
     p(99.9990) =     23.653 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.005 ms/op
Iteration   1: 2.894 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.305 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  6.410 ms/op
                 existUser·p0.9999: 12.321 ms/op
                 existUser·p1.00:   12.452 ms/op

Iteration   2: 2.924 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.485 ms/op
                 existUser·p0.9999: 13.783 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   3: 2.964 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.938 ms/op
                 existUser·p0.9999: 16.453 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327955
  mean =      2.927 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1643 
    [ 1.250,  2.500) = 23771 
    [ 2.500,  3.750) = 294847 
    [ 3.750,  5.000) = 6266 
    [ 5.000,  6.250) = 889 
    [ 6.250,  7.500) = 281 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.311 ms/op
     p(95.0000) =      3.502 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.865 ms/op
     p(99.9900) =     14.841 ms/op
     p(99.9990) =     16.904 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
Iteration   1: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.198 ms/op
                 getUser·p0.9999: 13.009 ms/op
                 getUser·p1.00:   13.206 ms/op

Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 22.261 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.142 ms/op
                 getUser·p0.9999: 16.604 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308661
  mean =      3.112 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12175 
    [ 2.500,  5.000) = 294762 
    [ 5.000,  7.500) = 1480 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.023 ms/op
     p(99.9900) =     21.111 ms/op
     p(99.9990) =     22.637 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 5.074 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.010 ms/op
Iteration   1: 3.992 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  14.262 ms/op
                 listUser·p0.9999: 22.279 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   2: 4.102 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.285 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 25.153 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 3.971 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.893 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238711
  mean =      4.021 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2831 
    [ 2.500,  5.000) = 211770 
    [ 5.000,  7.500) = 22511 
    [ 7.500, 10.000) = 1094 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     23.204 ms/op
     p(99.9990) =     25.534 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.443 ± 0.622  ops/ms
ClientGrpc.existUser                       thrpt       3  10.780 ± 2.201  ops/ms
ClientGrpc.getUser                         thrpt       3  10.431 ± 3.691  ops/ms
ClientGrpc.listUser                        thrpt       3   7.954 ± 2.286  ops/ms
ClientGrpc.createUser                       avgt       3   3.134 ± 0.240   ms/op
ClientGrpc.existUser                        avgt       3   2.975 ± 0.082   ms/op
ClientGrpc.getUser                          avgt       3   3.099 ± 0.035   ms/op
ClientGrpc.listUser                         avgt       3   4.003 ± 0.510   ms/op
ClientGrpc.createUser                     sample  308616   3.112 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.696           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.840           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.090           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.691           ms/op
ClientGrpc.existUser                      sample  327955   2.927 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.311           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.865           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.841           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.974           ms/op
ClientGrpc.getUser                        sample  308661   3.112 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.695           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.023           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.111           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.741           ms/op
ClientGrpc.listUser                       sample  238711   4.021 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.368           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.204           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
