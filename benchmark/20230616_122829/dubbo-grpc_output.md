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
# Warmup Iteration   1: 4.197 ops/ms
# Warmup Iteration   2: 8.673 ops/ms
# Warmup Iteration   3: 9.996 ops/ms
Iteration   1: 10.377 ops/ms
Iteration   2: 10.595 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.558 ±(99.9%) 3.024 ops/ms [Average]
  (min, avg, max) = (10.377, 10.558, 10.702), stdev = 0.166
  CI (99.9%): [7.534, 13.582] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.833 ops/ms
# Warmup Iteration   2: 10.725 ops/ms
# Warmup Iteration   3: 11.206 ops/ms
Iteration   1: 11.103 ops/ms
Iteration   2: 11.116 ops/ms
Iteration   3: 11.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.137 ±(99.9%) 0.878 ops/ms [Average]
  (min, avg, max) = (11.103, 11.137, 11.192), stdev = 0.048
  CI (99.9%): [10.259, 12.015] (assumes normal distribution)


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
# Warmup Iteration   1: 7.269 ops/ms
# Warmup Iteration   2: 10.302 ops/ms
# Warmup Iteration   3: 10.602 ops/ms
Iteration   1: 10.683 ops/ms
Iteration   2: 10.792 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.724 ±(99.9%) 1.083 ops/ms [Average]
  (min, avg, max) = (10.683, 10.724, 10.792), stdev = 0.059
  CI (99.9%): [9.641, 11.807] (assumes normal distribution)


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
# Warmup Iteration   1: 5.948 ops/ms
# Warmup Iteration   2: 7.587 ops/ms
# Warmup Iteration   3: 8.238 ops/ms
Iteration   1: 8.284 ops/ms
Iteration   2: 8.182 ops/ms
Iteration   3: 8.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.254 ±(99.9%) 1.141 ops/ms [Average]
  (min, avg, max) = (8.182, 8.254, 8.296), stdev = 0.063
  CI (99.9%): [7.113, 9.395] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.166 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.002 ms/op
Iteration   1: 3.038 ±(99.9%) 0.010 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 3.031 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.030 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (3.020, 3.030, 3.038), stdev = 0.009
  CI (99.9%): [2.864, 3.196] (assumes normal distribution)


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.876 ±(99.9%) 0.002 ms/op
Iteration   1: 2.896 ±(99.9%) 0.002 ms/op
Iteration   2: 2.898 ±(99.9%) 0.002 ms/op
Iteration   3: 2.834 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.876 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (2.834, 2.876, 2.898), stdev = 0.036
  CI (99.9%): [2.214, 3.539] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.002 ms/op
Iteration   1: 2.974 ±(99.9%) 0.002 ms/op
Iteration   2: 2.965 ±(99.9%) 0.003 ms/op
Iteration   3: 2.975 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.971 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (2.965, 2.971, 2.975), stdev = 0.006
  CI (99.9%): [2.866, 3.077] (assumes normal distribution)


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
# Warmup Iteration   1: 5.568 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.032 ms/op
Iteration   1: 3.889 ±(99.9%) 0.020 ms/op
Iteration   2: 3.940 ±(99.9%) 0.024 ms/op
Iteration   3: 3.883 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.904 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.883, 3.904, 3.940), stdev = 0.031
  CI (99.9%): [3.334, 4.473] (assumes normal distribution)


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 2.972 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.531 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  7.676 ms/op
                 createUser·p0.9999: 14.507 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.800 ms/op
                 createUser·p0.9999: 14.483 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   3: 3.076 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  12.059 ms/op
                 createUser·p0.9999: 29.884 ms/op
                 createUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319591
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27434 
    [ 2.500,  5.000) = 290897 
    [ 5.000,  7.500) = 726 
    [ 7.500, 10.000) = 229 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      9.509 ms/op
     p(99.9900) =     29.263 ms/op
     p(99.9990) =     30.075 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.005 ms/op
Iteration   1: 2.922 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.179 ms/op
                 existUser·p0.999:  6.864 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   12.567 ms/op

Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.626 ms/op
                 existUser·p0.9999: 14.358 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   3: 2.928 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.558 ms/op
                 existUser·p0.9999: 17.203 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327009
  mean =      2.937 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 934 
    [ 1.250,  2.500) = 33570 
    [ 2.500,  3.750) = 282674 
    [ 3.750,  5.000) = 8847 
    [ 5.000,  6.250) = 461 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.996 ms/op
     p(99.9900) =     15.460 ms/op
     p(99.9990) =     17.489 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  7.639 ms/op
                 getUser·p0.9999: 13.426 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.284 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.016 ms/op
                 getUser·p0.9999: 14.128 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.865 ms/op
                 getUser·p0.9999: 17.334 ms/op
                 getUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319640
  mean =      3.001 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 564 
    [ 1.250,  2.500) = 27726 
    [ 2.500,  3.750) = 274954 
    [ 3.750,  5.000) = 15035 
    [ 5.000,  6.250) = 808 
    [ 6.250,  7.500) = 295 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.284 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.187 ms/op
     p(99.9900) =     16.712 ms/op
     p(99.9990) =     17.682 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 5.341 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
Iteration   1: 3.878 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.673 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.755 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   2: 3.924 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 26.401 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   3: 3.969 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244482
  mean =      3.923 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4016 
    [ 2.500,  5.000) = 218396 
    [ 5.000,  7.500) = 20625 
    [ 7.500, 10.000) = 943 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     15.843 ms/op
     p(99.9900) =     25.806 ms/op
     p(99.9990) =     27.034 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.558 ± 3.024  ops/ms
ClientGrpc.existUser                       thrpt       3  11.137 ± 0.878  ops/ms
ClientGrpc.getUser                         thrpt       3  10.724 ± 1.083  ops/ms
ClientGrpc.listUser                        thrpt       3   8.254 ± 1.141  ops/ms
ClientGrpc.createUser                       avgt       3   3.030 ± 0.166   ms/op
ClientGrpc.existUser                        avgt       3   2.876 ± 0.662   ms/op
ClientGrpc.getUser                          avgt       3   2.971 ± 0.105   ms/op
ClientGrpc.listUser                         avgt       3   3.904 ± 0.569   ms/op
ClientGrpc.createUser                     sample  319591   3.005 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.765           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.509           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.263           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.212           ms/op
ClientGrpc.existUser                      sample  327009   2.937 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.712           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.996           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.460           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.662           ms/op
ClientGrpc.getUser                        sample  319640   3.001 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.284           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.187           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.712           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.826           ms/op
ClientGrpc.listUser                       sample  244482   3.923 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.978           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.843           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.806           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.165           ms/op
