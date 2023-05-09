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
# Warmup Iteration   1: 4.741 ops/ms
# Warmup Iteration   2: 9.217 ops/ms
# Warmup Iteration   3: 10.126 ops/ms
Iteration   1: 10.848 ops/ms
Iteration   2: 10.895 ops/ms
Iteration   3: 10.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.882 ±(99.9%) 0.542 ops/ms [Average]
  (min, avg, max) = (10.848, 10.882, 10.903), stdev = 0.030
  CI (99.9%): [10.341, 11.424] (assumes normal distribution)


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
# Warmup Iteration   1: 8.012 ops/ms
# Warmup Iteration   2: 10.846 ops/ms
# Warmup Iteration   3: 11.351 ops/ms
Iteration   1: 11.150 ops/ms
Iteration   2: 11.241 ops/ms
Iteration   3: 11.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.182 ±(99.9%) 0.929 ops/ms [Average]
  (min, avg, max) = (11.150, 11.182, 11.241), stdev = 0.051
  CI (99.9%): [10.253, 12.111] (assumes normal distribution)


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
# Warmup Iteration   1: 7.750 ops/ms
# Warmup Iteration   2: 10.419 ops/ms
# Warmup Iteration   3: 10.825 ops/ms
Iteration   1: 10.903 ops/ms
Iteration   2: 10.808 ops/ms
Iteration   3: 10.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.882 ±(99.9%) 1.218 ops/ms [Average]
  (min, avg, max) = (10.808, 10.882, 10.936), stdev = 0.067
  CI (99.9%): [9.664, 12.100] (assumes normal distribution)


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
# Warmup Iteration   1: 5.853 ops/ms
# Warmup Iteration   2: 8.140 ops/ms
# Warmup Iteration   3: 8.330 ops/ms
Iteration   1: 8.150 ops/ms
Iteration   2: 8.552 ops/ms
Iteration   3: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.410 ±(99.9%) 4.116 ops/ms [Average]
  (min, avg, max) = (8.150, 8.410, 8.552), stdev = 0.226
  CI (99.9%): [4.294, 12.527] (assumes normal distribution)


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.002 ms/op
Iteration   1: 2.936 ±(99.9%) 0.002 ms/op
Iteration   2: 2.937 ±(99.9%) 0.002 ms/op
Iteration   3: 2.989 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.954 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (2.936, 2.954, 2.989), stdev = 0.030
  CI (99.9%): [2.400, 3.508] (assumes normal distribution)


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.895 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.003 ms/op
Iteration   1: 2.831 ±(99.9%) 0.003 ms/op
Iteration   2: 2.858 ±(99.9%) 0.002 ms/op
Iteration   3: 2.852 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.847 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.831, 2.847, 2.858), stdev = 0.014
  CI (99.9%): [2.588, 3.106] (assumes normal distribution)


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.002 ms/op
Iteration   1: 3.006 ±(99.9%) 0.002 ms/op
Iteration   2: 2.969 ±(99.9%) 0.002 ms/op
Iteration   3: 2.954 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.977 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (2.954, 2.977, 3.006), stdev = 0.027
  CI (99.9%): [2.488, 3.466] (assumes normal distribution)


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
# Warmup Iteration   1: 5.110 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.011 ms/op
Iteration   1: 3.823 ±(99.9%) 0.011 ms/op
Iteration   2: 3.845 ±(99.9%) 0.021 ms/op
Iteration   3: 3.823 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.831 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (3.823, 3.831, 3.845), stdev = 0.013
  CI (99.9%): [3.603, 4.059] (assumes normal distribution)


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.007 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  9.030 ms/op
                 createUser·p0.9999: 11.562 ms/op
                 createUser·p1.00:   11.928 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  9.658 ms/op
                 createUser·p0.9999: 20.261 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.243 ms/op
                 createUser·p0.9999: 19.616 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319447
  mean =      3.003 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30022 
    [ 2.500,  5.000) = 287811 
    [ 5.000,  7.500) = 1200 
    [ 7.500, 10.000) = 202 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.865 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     20.467 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.896 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.006 ms/op
Iteration   1: 2.843 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.356 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  8.347 ms/op
                 existUser·p0.9999: 14.021 ms/op
                 existUser·p1.00:   16.040 ms/op

Iteration   2: 2.850 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.617 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  9.734 ms/op
                 existUser·p0.9999: 13.706 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.916 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  7.414 ms/op
                 existUser·p0.9999: 14.452 ms/op
                 existUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334513
  mean =      2.869 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2645 
    [ 1.250,  2.500) = 45759 
    [ 2.500,  3.750) = 276781 
    [ 3.750,  5.000) = 8385 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 175 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.188 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     14.691 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
Iteration   1: 2.956 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.124 ms/op
                 getUser·p0.9999: 13.733 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.760 ms/op
                 getUser·p0.9999: 12.665 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.475 ms/op
                 getUser·p0.9999: 15.155 ms/op
                 getUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322293
  mean =      2.977 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2393 
    [ 1.250,  2.500) = 31531 
    [ 2.500,  3.750) = 269576 
    [ 3.750,  5.000) = 17675 
    [ 5.000,  6.250) = 682 
    [ 6.250,  7.500) = 193 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.909 ms/op
     p(99.9900) =     14.431 ms/op
     p(99.9990) =     16.468 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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
# Warmup Iteration   1: 5.159 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.011 ms/op
Iteration   1: 3.878 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  11.813 ms/op
                 listUser·p0.9999: 19.471 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 3.846 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.298 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  12.983 ms/op
                 listUser·p0.9999: 17.946 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  14.663 ms/op
                 listUser·p0.9999: 21.168 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248938
  mean =      3.859 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5633 
    [ 2.500,  5.000) = 222314 
    [ 5.000,  7.500) = 20049 
    [ 7.500, 10.000) = 544 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     13.320 ms/op
     p(99.9900) =     20.844 ms/op
     p(99.9990) =     21.906 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.882 ± 0.542  ops/ms
ClientGrpc.existUser                       thrpt       3  11.182 ± 0.929  ops/ms
ClientGrpc.getUser                         thrpt       3  10.882 ± 1.218  ops/ms
ClientGrpc.listUser                        thrpt       3   8.410 ± 4.116  ops/ms
ClientGrpc.createUser                       avgt       3   2.954 ± 0.554   ms/op
ClientGrpc.existUser                        avgt       3   2.847 ± 0.259   ms/op
ClientGrpc.getUser                          avgt       3   2.977 ± 0.489   ms/op
ClientGrpc.listUser                         avgt       3   3.831 ± 0.228   ms/op
ClientGrpc.createUser                     sample  319447   3.003 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.546           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.865           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.825           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.578           ms/op
ClientGrpc.existUser                      sample  334513   2.869 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.356           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.188           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.008           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.040           ms/op
ClientGrpc.getUser                        sample  322293   2.977 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.909           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.431           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.581           ms/op
ClientGrpc.listUser                       sample  248938   3.859 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.298           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.562           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.320           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.844           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.987           ms/op
