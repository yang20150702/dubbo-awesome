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
# Warmup Iteration   1: 4.413 ops/ms
# Warmup Iteration   2: 9.136 ops/ms
# Warmup Iteration   3: 10.176 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.612 ops/ms
Iteration   3: 10.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.557 ±(99.9%) 1.763 ops/ms [Average]
  (min, avg, max) = (10.445, 10.557, 10.614), stdev = 0.097
  CI (99.9%): [8.794, 12.320] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.305 ops/ms
# Warmup Iteration   2: 10.614 ops/ms
# Warmup Iteration   3: 11.010 ops/ms
Iteration   1: 11.138 ops/ms
Iteration   2: 10.989 ops/ms
Iteration   3: 11.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.141 ±(99.9%) 2.817 ops/ms [Average]
  (min, avg, max) = (10.989, 11.141, 11.298), stdev = 0.154
  CI (99.9%): [8.325, 13.958] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.346 ops/ms
# Warmup Iteration   2: 10.211 ops/ms
# Warmup Iteration   3: 10.683 ops/ms
Iteration   1: 10.576 ops/ms
Iteration   2: 10.695 ops/ms
Iteration   3: 10.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.591 ±(99.9%) 1.787 ops/ms [Average]
  (min, avg, max) = (10.501, 10.591, 10.695), stdev = 0.098
  CI (99.9%): [8.803, 12.378] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.824 ops/ms
# Warmup Iteration   2: 7.629 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 8.162 ops/ms
Iteration   2: 8.307 ops/ms
Iteration   3: 8.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.266 ±(99.9%) 1.643 ops/ms [Average]
  (min, avg, max) = (8.162, 8.266, 8.328), stdev = 0.090
  CI (99.9%): [6.622, 9.909] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.004 ms/op
Iteration   1: 3.009 ±(99.9%) 0.005 ms/op
Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.021 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (2.995, 3.021, 3.059), stdev = 0.034
  CI (99.9%): [2.403, 3.639] (assumes normal distribution)


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.891 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.877 ±(99.9%) 0.004 ms/op
Iteration   1: 2.838 ±(99.9%) 0.005 ms/op
Iteration   2: 2.829 ±(99.9%) 0.004 ms/op
Iteration   3: 2.887 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.851 ±(99.9%) 0.573 ms/op [Average]
  (min, avg, max) = (2.829, 2.851, 2.887), stdev = 0.031
  CI (99.9%): [2.279, 3.424] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.002 ms/op
Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.012 ±(99.9%) 0.020 ms/op [Average]
  (min, avg, max) = (3.011, 3.012, 3.013), stdev = 0.001
  CI (99.9%): [2.992, 3.031] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.021 ms/op
Iteration   1: 3.974 ±(99.9%) 0.026 ms/op
Iteration   2: 3.965 ±(99.9%) 0.008 ms/op
Iteration   3: 3.983 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.974 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (3.965, 3.974, 3.983), stdev = 0.009
  CI (99.9%): [3.810, 4.138] (assumes normal distribution)


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 2.937 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  7.536 ms/op
                 createUser·p0.9999: 12.013 ms/op
                 createUser·p1.00:   12.190 ms/op

Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  9.507 ms/op
                 createUser·p0.9999: 17.596 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.409 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  7.323 ms/op
                 createUser·p0.9999: 19.704 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320395
  mean =      2.996 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2571 
    [ 1.250,  2.500) = 30123 
    [ 2.500,  3.750) = 269517 
    [ 3.750,  5.000) = 16019 
    [ 5.000,  6.250) = 1337 
    [ 6.250,  7.500) = 404 
    [ 7.500,  8.750) = 143 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.409 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =      7.922 ms/op
     p(99.9900) =     19.430 ms/op
     p(99.9990) =     19.844 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
Iteration   1: 2.840 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.239 ms/op
                 existUser·p0.9999: 21.774 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 2.839 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.084 ms/op
                 existUser·p0.9999: 12.624 ms/op
                 existUser·p1.00:   12.829 ms/op

Iteration   3: 2.926 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  8.815 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334437
  mean =      2.868 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42785 
    [ 2.500,  5.000) = 290410 
    [ 5.000,  7.500) = 994 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.094 ms/op
     p(99.9900) =     22.188 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.577 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  11.256 ms/op
                 getUser·p0.9999: 23.200 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.238 ms/op
                 getUser·p0.9999: 20.790 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.275 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.644 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  7.766 ms/op
                 getUser·p0.9999: 24.751 ms/op
                 getUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317566
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25095 
    [ 2.500,  5.000) = 290414 
    [ 5.000,  7.500) = 1619 
    [ 7.500, 10.000) = 178 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.275 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      7.860 ms/op
     p(99.9900) =     23.879 ms/op
     p(99.9990) =     25.207 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.010 ms/op
Iteration   1: 3.943 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 15.723 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   2: 4.015 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  15.978 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 3.938 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  15.381 ms/op
                 listUser·p0.9999: 17.593 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242074
  mean =      3.965 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4034 
    [ 2.500,  5.000) = 214180 
    [ 5.000,  7.500) = 22254 
    [ 7.500, 10.000) = 1055 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 212 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     14.923 ms/op
     p(99.9900) =     17.321 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.557 ± 1.763  ops/ms
ClientGrpc.existUser                       thrpt       3  11.141 ± 2.817  ops/ms
ClientGrpc.getUser                         thrpt       3  10.591 ± 1.787  ops/ms
ClientGrpc.listUser                        thrpt       3   8.266 ± 1.643  ops/ms
ClientGrpc.createUser                       avgt       3   3.021 ± 0.618   ms/op
ClientGrpc.existUser                        avgt       3   2.851 ± 0.573   ms/op
ClientGrpc.getUser                          avgt       3   3.012 ± 0.020   ms/op
ClientGrpc.listUser                         avgt       3   3.974 ± 0.164   ms/op
ClientGrpc.createUser                     sample  320395   2.996 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.409           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.922           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.430           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.890           ms/op
ClientGrpc.existUser                      sample  334437   2.868 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.611           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.094           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.188           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.183           ms/op
ClientGrpc.getUser                        sample  317566   3.023 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.275           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.860           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.879           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.952           ms/op
ClientGrpc.listUser                       sample  242074   3.965 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.065           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.923           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.321           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.513           ms/op
