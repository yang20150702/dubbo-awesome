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
# Warmup Iteration   1: 4.545 ops/ms
# Warmup Iteration   2: 9.089 ops/ms
# Warmup Iteration   3: 9.943 ops/ms
Iteration   1: 10.334 ops/ms
Iteration   2: 10.574 ops/ms
Iteration   3: 10.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.398 ±(99.9%) 2.814 ops/ms [Average]
  (min, avg, max) = (10.286, 10.398, 10.574), stdev = 0.154
  CI (99.9%): [7.584, 13.213] (assumes normal distribution)


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
# Warmup Iteration   1: 7.753 ops/ms
# Warmup Iteration   2: 10.595 ops/ms
# Warmup Iteration   3: 10.986 ops/ms
Iteration   1: 10.897 ops/ms
Iteration   2: 11.114 ops/ms
Iteration   3: 10.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.938 ±(99.9%) 2.913 ops/ms [Average]
  (min, avg, max) = (10.802, 10.938, 11.114), stdev = 0.160
  CI (99.9%): [8.025, 13.851] (assumes normal distribution)


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
# Warmup Iteration   1: 7.329 ops/ms
# Warmup Iteration   2: 10.345 ops/ms
# Warmup Iteration   3: 10.510 ops/ms
Iteration   1: 10.627 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.565 ±(99.9%) 1.248 ops/ms [Average]
  (min, avg, max) = (10.492, 10.565, 10.627), stdev = 0.068
  CI (99.9%): [9.316, 11.813] (assumes normal distribution)


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
# Warmup Iteration   1: 5.606 ops/ms
# Warmup Iteration   2: 8.049 ops/ms
# Warmup Iteration   3: 8.103 ops/ms
Iteration   1: 8.116 ops/ms
Iteration   2: 8.116 ops/ms
Iteration   3: 8.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.146 ±(99.9%) 0.932 ops/ms [Average]
  (min, avg, max) = (8.116, 8.146, 8.205), stdev = 0.051
  CI (99.9%): [7.213, 9.078] (assumes normal distribution)


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.003 ms/op
Iteration   1: 3.010 ±(99.9%) 0.010 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 3.008 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.022 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (3.008, 3.022, 3.047), stdev = 0.022
  CI (99.9%): [2.628, 3.415] (assumes normal distribution)


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.003 ms/op
Iteration   1: 2.922 ±(99.9%) 0.002 ms/op
Iteration   2: 2.922 ±(99.9%) 0.001 ms/op
Iteration   3: 2.947 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.930 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (2.922, 2.930, 2.947), stdev = 0.015
  CI (99.9%): [2.661, 3.200] (assumes normal distribution)


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
# Warmup Iteration   1: 4.057 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.003 ms/op
Iteration   1: 3.003 ±(99.9%) 0.005 ms/op
Iteration   2: 2.929 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.980 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (2.929, 2.980, 3.006), stdev = 0.044
  CI (99.9%): [2.181, 3.778] (assumes normal distribution)


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
# Warmup Iteration   1: 5.261 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.015 ms/op
Iteration   1: 3.840 ±(99.9%) 0.034 ms/op
Iteration   2: 3.839 ±(99.9%) 0.019 ms/op
Iteration   3: 3.847 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.842 ±(99.9%) 0.078 ms/op [Average]
  (min, avg, max) = (3.839, 3.842, 3.847), stdev = 0.004
  CI (99.9%): [3.764, 3.921] (assumes normal distribution)


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.046 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  10.812 ms/op
                 createUser·p0.9999: 16.810 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.408 ms/op
                 createUser·p0.999:  9.172 ms/op
                 createUser·p0.9999: 15.948 ms/op
                 createUser·p1.00:   16.187 ms/op

Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.685 ms/op
                 createUser·p0.9999: 18.688 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318090
  mean =      3.017 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1681 
    [ 1.250,  2.500) = 17997 
    [ 2.500,  3.750) = 285157 
    [ 3.750,  5.000) = 11678 
    [ 5.000,  6.250) = 808 
    [ 6.250,  7.500) = 236 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 74 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.878 ms/op
     p(99.9900) =     17.838 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.007 ms/op
Iteration   1: 2.978 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  5.938 ms/op
                 existUser·p0.9999: 12.395 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   2: 2.918 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  8.024 ms/op
                 existUser·p0.9999: 19.760 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  9.559 ms/op
                 existUser·p0.9999: 15.188 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325250
  mean =      2.950 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37233 
    [ 2.500,  5.000) = 286579 
    [ 5.000,  7.500) = 1103 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.569 ms/op
     p(99.9900) =     18.030 ms/op
     p(99.9990) =     20.046 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.493 ms/op
                 getUser·p0.999:  6.625 ms/op
                 getUser·p0.9999: 16.663 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.818 ms/op
                 getUser·p0.9999: 13.150 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.431 ms/op
                 getUser·p0.9999: 18.166 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317239
  mean =      3.026 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1410 
    [ 1.250,  2.500) = 21369 
    [ 2.500,  3.750) = 280188 
    [ 3.750,  5.000) = 13175 
    [ 5.000,  6.250) = 667 
    [ 6.250,  7.500) = 183 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      6.683 ms/op
     p(99.9900) =     16.630 ms/op
     p(99.9990) =     18.568 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.885 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.010 ms/op
Iteration   1: 3.862 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.306 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.517 ms/op
                 listUser·p0.9999: 13.770 ms/op
                 listUser·p1.00:   16.417 ms/op

Iteration   2: 3.881 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.509 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  19.615 ms/op
                 listUser·p0.9999: 26.625 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   3: 3.922 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  12.956 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246838
  mean =      3.888 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4343 
    [ 2.500,  5.000) = 222555 
    [ 5.000,  7.500) = 18836 
    [ 7.500, 10.000) = 563 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     26.774 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.398 ± 2.814  ops/ms
ClientGrpc.existUser                       thrpt       3  10.938 ± 2.913  ops/ms
ClientGrpc.getUser                         thrpt       3  10.565 ± 1.248  ops/ms
ClientGrpc.listUser                        thrpt       3   8.146 ± 0.932  ops/ms
ClientGrpc.createUser                       avgt       3   3.022 ± 0.393   ms/op
ClientGrpc.existUser                        avgt       3   2.930 ± 0.269   ms/op
ClientGrpc.getUser                          avgt       3   2.980 ± 0.799   ms/op
ClientGrpc.listUser                         avgt       3   3.842 ± 0.078   ms/op
ClientGrpc.createUser                     sample  318090   3.017 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.631           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.878           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.838           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.973           ms/op
ClientGrpc.existUser                      sample  325250   2.950 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.724           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.569           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.030           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.152           ms/op
ClientGrpc.getUser                        sample  317239   3.026 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.770           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.683           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.630           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.711           ms/op
ClientGrpc.listUser                       sample  246838   3.888 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.821           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.238           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.395           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.591           ms/op
