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
# Warmup Iteration   1: 4.719 ops/ms
# Warmup Iteration   2: 9.398 ops/ms
# Warmup Iteration   3: 10.578 ops/ms
Iteration   1: 10.737 ops/ms
Iteration   2: 10.830 ops/ms
Iteration   3: 10.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.795 ±(99.9%) 0.921 ops/ms [Average]
  (min, avg, max) = (10.737, 10.795, 10.830), stdev = 0.050
  CI (99.9%): [9.874, 11.716] (assumes normal distribution)


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
# Warmup Iteration   1: 8.382 ops/ms
# Warmup Iteration   2: 11.388 ops/ms
# Warmup Iteration   3: 11.165 ops/ms
Iteration   1: 11.300 ops/ms
Iteration   2: 11.342 ops/ms
Iteration   3: 11.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.385 ±(99.9%) 2.072 ops/ms [Average]
  (min, avg, max) = (11.300, 11.385, 11.514), stdev = 0.114
  CI (99.9%): [9.313, 13.457] (assumes normal distribution)


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
# Warmup Iteration   1: 7.529 ops/ms
# Warmup Iteration   2: 10.471 ops/ms
# Warmup Iteration   3: 10.862 ops/ms
Iteration   1: 10.910 ops/ms
Iteration   2: 10.876 ops/ms
Iteration   3: 10.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.896 ±(99.9%) 0.322 ops/ms [Average]
  (min, avg, max) = (10.876, 10.896, 10.910), stdev = 0.018
  CI (99.9%): [10.574, 11.217] (assumes normal distribution)


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
# Warmup Iteration   1: 5.795 ops/ms
# Warmup Iteration   2: 8.089 ops/ms
# Warmup Iteration   3: 8.090 ops/ms
Iteration   1: 8.209 ops/ms
Iteration   2: 8.084 ops/ms
Iteration   3: 8.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.130 ±(99.9%) 1.259 ops/ms [Average]
  (min, avg, max) = (8.084, 8.130, 8.209), stdev = 0.069
  CI (99.9%): [6.871, 9.389] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.002 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 2.960 ±(99.9%) 0.002 ms/op
Iteration   3: 2.919 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.957 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (2.919, 2.957, 2.991), stdev = 0.036
  CI (99.9%): [2.294, 3.620] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.908 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.846 ±(99.9%) 0.004 ms/op
Iteration   1: 2.873 ±(99.9%) 0.002 ms/op
Iteration   2: 2.829 ±(99.9%) 0.002 ms/op
Iteration   3: 2.737 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.813 ±(99.9%) 1.268 ms/op [Average]
  (min, avg, max) = (2.737, 2.813, 2.873), stdev = 0.070
  CI (99.9%): [1.545, 4.081] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.002 ms/op
Iteration   1: 2.998 ±(99.9%) 0.003 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 2.996 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.996 ±(99.9%) 0.038 ms/op [Average]
  (min, avg, max) = (2.994, 2.996, 2.998), stdev = 0.002
  CI (99.9%): [2.958, 3.034] (assumes normal distribution)


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
# Warmup Iteration   1: 5.306 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.013 ms/op
Iteration   1: 3.875 ±(99.9%) 0.024 ms/op
Iteration   2: 3.881 ±(99.9%) 0.036 ms/op
Iteration   3: 3.866 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.874 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (3.866, 3.874, 3.881), stdev = 0.008
  CI (99.9%): [3.736, 4.011] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 2.964 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  5.964 ms/op
                 createUser·p0.9999: 19.078 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.417 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   3: 2.927 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.498 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.553 ms/op
                 createUser·p0.9999: 24.646 ms/op
                 createUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323617
  mean =      2.965 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26620 
    [ 2.500,  5.000) = 295867 
    [ 5.000,  7.500) = 806 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.528 ms/op
     p(99.9900) =     22.066 ms/op
     p(99.9990) =     24.961 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.826 ±(99.9%) 0.006 ms/op
Iteration   1: 2.870 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  5.612 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   2: 2.865 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  10.960 ms/op
                 existUser·p0.9999: 16.936 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   3: 2.860 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.787 ms/op
                 existUser·p0.9999: 27.093 ms/op
                 existUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334951
  mean =      2.865 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53568 
    [ 2.500,  5.000) = 280183 
    [ 5.000,  7.500) = 800 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     28.798 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.951 ±(99.9%) 0.004 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.322 ms/op
                 getUser·p0.95:   3.502 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  5.923 ms/op
                 getUser·p0.9999: 12.272 ms/op
                 getUser·p1.00:   12.534 ms/op

Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.262 ms/op
                 getUser·p0.9999: 12.730 ms/op
                 getUser·p1.00:   13.042 ms/op

Iteration   3: 2.978 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  6.286 ms/op
                 getUser·p0.9999: 15.598 ms/op
                 getUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323063
  mean =      2.971 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1551 
    [ 1.250,  2.500) = 23934 
    [ 2.500,  3.750) = 286040 
    [ 3.750,  5.000) = 10686 
    [ 5.000,  6.250) = 476 
    [ 6.250,  7.500) = 132 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.463 ms/op
     p(99.9900) =     14.954 ms/op
     p(99.9990) =     15.865 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 5.233 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.009 ms/op
Iteration   1: 3.876 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.861 ms/op
                 listUser·p0.999:  12.873 ms/op
                 listUser·p0.9999: 15.970 ms/op
                 listUser·p1.00:   16.744 ms/op

Iteration   2: 3.858 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.093 ms/op
                 listUser·p0.9999: 15.773 ms/op
                 listUser·p1.00:   16.073 ms/op

Iteration   3: 3.848 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.711 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  16.285 ms/op
                 listUser·p0.9999: 19.803 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248863
  mean =      3.861 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3809 
    [ 2.500,  5.000) = 225096 
    [ 5.000,  7.500) = 18739 
    [ 7.500, 10.000) = 806 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     19.242 ms/op
     p(99.9990) =     20.596 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.795 ± 0.921  ops/ms
ClientGrpc.existUser                       thrpt       3  11.385 ± 2.072  ops/ms
ClientGrpc.getUser                         thrpt       3  10.896 ± 0.322  ops/ms
ClientGrpc.listUser                        thrpt       3   8.130 ± 1.259  ops/ms
ClientGrpc.createUser                       avgt       3   2.957 ± 0.663   ms/op
ClientGrpc.existUser                        avgt       3   2.813 ± 1.268   ms/op
ClientGrpc.getUser                          avgt       3   2.996 ± 0.038   ms/op
ClientGrpc.listUser                         avgt       3   3.874 ± 0.138   ms/op
ClientGrpc.createUser                     sample  323617   2.965 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.635           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.400           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.528           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.066           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.068           ms/op
ClientGrpc.existUser                      sample  334951   2.865 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.590           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.306           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.629           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.000           ms/op
ClientGrpc.getUser                        sample  323063   2.971 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.582           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.449           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.463           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.954           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.007           ms/op
ClientGrpc.listUser                       sample  248863   3.861 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.711           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.173           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.242           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.742           ms/op
