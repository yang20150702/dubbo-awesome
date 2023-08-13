# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.401 ops/ms
# Warmup Iteration   2: 9.427 ops/ms
# Warmup Iteration   3: 10.090 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.480 ops/ms
Iteration   3: 10.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.571 ±(99.9%) 1.677 ops/ms [Average]
  (min, avg, max) = (10.480, 10.571, 10.664), stdev = 0.092
  CI (99.9%): [8.895, 12.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.761 ops/ms
# Warmup Iteration   2: 10.715 ops/ms
# Warmup Iteration   3: 11.211 ops/ms
Iteration   1: 11.081 ops/ms
Iteration   2: 11.088 ops/ms
Iteration   3: 11.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.126 ±(99.9%) 1.323 ops/ms [Average]
  (min, avg, max) = (11.081, 11.126, 11.210), stdev = 0.073
  CI (99.9%): [9.804, 12.449] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.191 ops/ms
# Warmup Iteration   2: 10.165 ops/ms
# Warmup Iteration   3: 10.516 ops/ms
Iteration   1: 10.659 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 10.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.660 ±(99.9%) 1.491 ops/ms [Average]
  (min, avg, max) = (10.578, 10.660, 10.741), stdev = 0.082
  CI (99.9%): [9.168, 12.151] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.870 ops/ms
# Warmup Iteration   2: 7.742 ops/ms
# Warmup Iteration   3: 8.204 ops/ms
Iteration   1: 8.216 ops/ms
Iteration   2: 8.216 ops/ms
Iteration   3: 8.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.185 ±(99.9%) 0.977 ops/ms [Average]
  (min, avg, max) = (8.123, 8.185, 8.216), stdev = 0.054
  CI (99.9%): [7.208, 9.162] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.116 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.003 ms/op
Iteration   1: 2.989 ±(99.9%) 0.003 ms/op
Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.020 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (2.989, 3.020, 3.040), stdev = 0.027
  CI (99.9%): [2.521, 3.518] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.851 ±(99.9%) 0.003 ms/op
Iteration   1: 2.915 ±(99.9%) 0.004 ms/op
Iteration   2: 2.871 ±(99.9%) 0.004 ms/op
Iteration   3: 2.898 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.895 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.871, 2.895, 2.915), stdev = 0.022
  CI (99.9%): [2.491, 3.299] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.015 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
Iteration   1: 3.013 ±(99.9%) 0.003 ms/op
Iteration   2: 2.967 ±(99.9%) 0.002 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.003 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (2.967, 3.003, 3.028), stdev = 0.032
  CI (99.9%): [2.425, 3.580] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.012 ms/op
Iteration   1: 3.906 ±(99.9%) 0.009 ms/op
Iteration   2: 3.861 ±(99.9%) 0.033 ms/op
Iteration   3: 3.892 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.887 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (3.861, 3.887, 3.906), stdev = 0.023
  CI (99.9%): [3.464, 4.309] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.109 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.336 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  8.314 ms/op
                 createUser·p0.9999: 16.621 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.796 ms/op
                 createUser·p0.9999: 24.334 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.426 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.545 ms/op
                 createUser·p0.9999: 15.791 ms/op
                 createUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314853
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23711 
    [ 2.500,  5.000) = 289200 
    [ 5.000,  7.500) = 1508 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.318 ms/op
     p(99.9900) =     22.250 ms/op
     p(99.9990) =     24.347 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.847 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.006 ms/op
Iteration   1: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  8.116 ms/op
                 existUser·p0.9999: 13.223 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.875 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.558 ms/op
                 existUser·p0.999:  7.551 ms/op
                 existUser·p0.9999: 12.382 ms/op
                 existUser·p1.00:   12.648 ms/op

Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.145 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329471
  mean =      2.913 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2303 
    [ 1.250,  2.500) = 33018 
    [ 2.500,  3.750) = 280335 
    [ 3.750,  5.000) = 12212 
    [ 5.000,  6.250) = 794 
    [ 6.250,  7.500) = 403 
    [ 7.500,  8.750) = 199 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.549 ms/op
     p(99.9000) =      7.791 ms/op
     p(99.9900) =     15.234 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  9.697 ms/op
                 getUser·p0.9999: 27.459 ms/op
                 getUser·p1.00:   33.817 ms/op

Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.798 ms/op
                 getUser·p0.9999: 14.834 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   3: 3.000 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  9.352 ms/op
                 getUser·p0.9999: 24.576 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317066
  mean =      3.027 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25283 
    [ 2.500,  5.000) = 289473 
    [ 5.000,  7.500) = 1672 
    [ 7.500, 10.000) = 358 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      9.420 ms/op
     p(99.9900) =     25.596 ms/op
     p(99.9990) =     28.295 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.253 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.011 ms/op
Iteration   1: 3.920 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  13.098 ms/op
                 listUser·p0.9999: 18.498 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 3.930 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.451 ms/op
                 listUser·p0.9999: 16.927 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.939 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.740 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  15.000 ms/op
                 listUser·p0.9999: 27.558 ms/op
                 listUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244440
  mean =      3.930 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4715 
    [ 2.500,  5.000) = 218929 
    [ 5.000,  7.500) = 19151 
    [ 7.500, 10.000) = 1039 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     27.136 ms/op
     p(99.9990) =     29.087 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.571 ± 1.677  ops/ms
ClientGrpc.existUser                       thrpt       3  11.126 ± 1.323  ops/ms
ClientGrpc.getUser                         thrpt       3  10.660 ± 1.491  ops/ms
ClientGrpc.listUser                        thrpt       3   8.185 ± 0.977  ops/ms
ClientGrpc.createUser                       avgt       3   3.020 ± 0.498   ms/op
ClientGrpc.existUser                        avgt       3   2.895 ± 0.404   ms/op
ClientGrpc.getUser                          avgt       3   3.003 ± 0.577   ms/op
ClientGrpc.listUser                         avgt       3   3.887 ± 0.422   ms/op
ClientGrpc.createUser                     sample  314853   3.051 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.336           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.318           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.250           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.347           ms/op
ClientGrpc.existUser                      sample  329471   2.913 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.495           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.549           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.791           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.234           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.727           ms/op
ClientGrpc.getUser                        sample  317066   3.027 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.626           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.420           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.596           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.817           ms/op
ClientGrpc.listUser                       sample  244440   3.930 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.740           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.877           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.136           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.327           ms/op
