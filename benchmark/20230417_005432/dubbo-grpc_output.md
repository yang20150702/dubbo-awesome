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
# Warmup Iteration   1: 5.185 ops/ms
# Warmup Iteration   2: 9.594 ops/ms
# Warmup Iteration   3: 10.479 ops/ms
Iteration   1: 10.937 ops/ms
Iteration   2: 10.960 ops/ms
Iteration   3: 10.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.952 ±(99.9%) 0.227 ops/ms [Average]
  (min, avg, max) = (10.937, 10.952, 10.960), stdev = 0.012
  CI (99.9%): [10.724, 11.179] (assumes normal distribution)


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
# Warmup Iteration   1: 7.847 ops/ms
# Warmup Iteration   2: 11.175 ops/ms
# Warmup Iteration   3: 11.183 ops/ms
Iteration   1: 11.375 ops/ms
Iteration   2: 11.371 ops/ms
Iteration   3: 11.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.359 ±(99.9%) 0.431 ops/ms [Average]
  (min, avg, max) = (11.332, 11.359, 11.375), stdev = 0.024
  CI (99.9%): [10.928, 11.790] (assumes normal distribution)


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
# Warmup Iteration   1: 7.815 ops/ms
# Warmup Iteration   2: 10.570 ops/ms
# Warmup Iteration   3: 10.783 ops/ms
Iteration   1: 11.020 ops/ms
Iteration   2: 10.967 ops/ms
Iteration   3: 10.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.954 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (10.875, 10.954, 11.020), stdev = 0.073
  CI (99.9%): [9.621, 12.287] (assumes normal distribution)


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
# Warmup Iteration   1: 6.905 ops/ms
# Warmup Iteration   2: 7.992 ops/ms
# Warmup Iteration   3: 8.359 ops/ms
Iteration   1: 8.597 ops/ms
Iteration   2: 8.364 ops/ms
Iteration   3: 8.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.473 ±(99.9%) 2.141 ops/ms [Average]
  (min, avg, max) = (8.364, 8.473, 8.597), stdev = 0.117
  CI (99.9%): [6.332, 10.613] (assumes normal distribution)


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.009 ms/op
Iteration   1: 2.968 ±(99.9%) 0.002 ms/op
Iteration   2: 2.976 ±(99.9%) 0.003 ms/op
Iteration   3: 2.987 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.977 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (2.968, 2.977, 2.987), stdev = 0.010
  CI (99.9%): [2.801, 3.153] (assumes normal distribution)


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
# Warmup Iteration   1: 3.358 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.811 ±(99.9%) 0.003 ms/op
Iteration   1: 2.803 ±(99.9%) 0.003 ms/op
Iteration   2: 2.857 ±(99.9%) 0.002 ms/op
Iteration   3: 2.788 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.816 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (2.788, 2.816, 2.857), stdev = 0.036
  CI (99.9%): [2.154, 3.478] (assumes normal distribution)


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.004 ms/op
Iteration   1: 2.930 ±(99.9%) 0.004 ms/op
Iteration   2: 2.975 ±(99.9%) 0.004 ms/op
Iteration   3: 2.949 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.952 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (2.930, 2.952, 2.975), stdev = 0.023
  CI (99.9%): [2.537, 3.366] (assumes normal distribution)


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
# Warmup Iteration   1: 4.697 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.017 ms/op
Iteration   1: 3.746 ±(99.9%) 0.018 ms/op
Iteration   2: 3.796 ±(99.9%) 0.010 ms/op
Iteration   3: 3.783 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.775 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (3.746, 3.775, 3.796), stdev = 0.026
  CI (99.9%): [3.304, 4.246] (assumes normal distribution)


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  5.977 ms/op
                 createUser·p0.9999: 23.077 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 2.946 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  10.231 ms/op
                 createUser·p0.9999: 13.257 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   3: 2.933 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.398 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  12.351 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325012
  mean =      2.953 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36945 
    [ 2.500,  5.000) = 286831 
    [ 5.000,  7.500) = 821 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     23.773 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.819 ±(99.9%) 0.006 ms/op
Iteration   1: 2.849 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.125 ms/op
                 existUser·p0.9999: 11.911 ms/op
                 existUser·p1.00:   12.206 ms/op

Iteration   2: 2.874 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  5.953 ms/op
                 existUser·p0.9999: 13.119 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  9.044 ms/op
                 existUser·p0.9999: 14.204 ms/op
                 existUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333775
  mean =      2.875 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2877 
    [ 1.250,  2.500) = 47385 
    [ 2.500,  3.750) = 274704 
    [ 3.750,  5.000) = 7657 
    [ 5.000,  6.250) = 793 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.341 ms/op
     p(99.9900) =     13.750 ms/op
     p(99.9990) =     14.467 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.709 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.237 ms/op
                 getUser·p0.9999: 17.802 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.832 ms/op
                 getUser·p0.9999: 20.742 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   3: 2.965 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  6.145 ms/op
                 getUser·p0.9999: 13.688 ms/op
                 getUser·p1.00:   15.057 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322252
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32787 
    [ 2.500,  5.000) = 288262 
    [ 5.000,  7.500) = 894 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.422 ms/op
     p(99.9900) =     19.811 ms/op
     p(99.9990) =     21.423 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 4.299 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.009 ms/op
Iteration   1: 3.856 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  11.497 ms/op
                 listUser·p0.9999: 18.406 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   2: 3.760 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   3: 3.836 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  13.583 ms/op
                 listUser·p0.9999: 23.024 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251564
  mean =      3.817 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5264 
    [ 2.500,  5.000) = 228220 
    [ 5.000,  7.500) = 17131 
    [ 7.500, 10.000) = 477 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     22.595 ms/op
     p(99.9990) =     23.281 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.952 ± 0.227  ops/ms
ClientGrpc.existUser                       thrpt       3  11.359 ± 0.431  ops/ms
ClientGrpc.getUser                         thrpt       3  10.954 ± 1.333  ops/ms
ClientGrpc.listUser                        thrpt       3   8.473 ± 2.141  ops/ms
ClientGrpc.createUser                       avgt       3   2.977 ± 0.176   ms/op
ClientGrpc.existUser                        avgt       3   2.816 ± 0.662   ms/op
ClientGrpc.getUser                          avgt       3   2.952 ± 0.414   ms/op
ClientGrpc.listUser                         avgt       3   3.775 ± 0.471   ms/op
ClientGrpc.createUser                     sample  325012   2.953 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.398           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.633           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.643           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.052           ms/op
ClientGrpc.existUser                      sample  333775   2.875 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.515           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.341           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.750           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.598           ms/op
ClientGrpc.getUser                        sample  322252   2.979 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.566           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.422           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.811           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.692           ms/op
ClientGrpc.listUser                       sample  251564   3.817 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.894           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.504           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.042           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.595           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.642           ms/op
