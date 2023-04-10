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
# Warmup Iteration   1: 4.437 ops/ms
# Warmup Iteration   2: 9.408 ops/ms
# Warmup Iteration   3: 10.032 ops/ms
Iteration   1: 10.661 ops/ms
Iteration   2: 10.962 ops/ms
Iteration   3: 10.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.736 ±(99.9%) 3.639 ops/ms [Average]
  (min, avg, max) = (10.585, 10.736, 10.962), stdev = 0.199
  CI (99.9%): [7.098, 14.375] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.642 ops/ms
# Warmup Iteration   2: 10.684 ops/ms
# Warmup Iteration   3: 11.063 ops/ms
Iteration   1: 11.345 ops/ms
Iteration   2: 11.294 ops/ms
Iteration   3: 11.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.332 ±(99.9%) 0.608 ops/ms [Average]
  (min, avg, max) = (11.294, 11.332, 11.357), stdev = 0.033
  CI (99.9%): [10.723, 11.940] (assumes normal distribution)


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
# Warmup Iteration   1: 6.705 ops/ms
# Warmup Iteration   2: 10.111 ops/ms
# Warmup Iteration   3: 10.692 ops/ms
Iteration   1: 10.549 ops/ms
Iteration   2: 10.613 ops/ms
Iteration   3: 10.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.522 ±(99.9%) 1.955 ops/ms [Average]
  (min, avg, max) = (10.404, 10.522, 10.613), stdev = 0.107
  CI (99.9%): [8.567, 12.477] (assumes normal distribution)


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
# Warmup Iteration   1: 5.483 ops/ms
# Warmup Iteration   2: 7.977 ops/ms
# Warmup Iteration   3: 8.168 ops/ms
Iteration   1: 8.169 ops/ms
Iteration   2: 8.199 ops/ms
Iteration   3: 8.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.169 ±(99.9%) 0.549 ops/ms [Average]
  (min, avg, max) = (8.139, 8.169, 8.199), stdev = 0.030
  CI (99.9%): [7.620, 8.718] (assumes normal distribution)


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
# Warmup Iteration   1: 4.350 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.003 ms/op
Iteration   1: 3.044 ±(99.9%) 0.002 ms/op
Iteration   2: 2.922 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.976 ±(99.9%) 1.136 ms/op [Average]
  (min, avg, max) = (2.922, 2.976, 3.044), stdev = 0.062
  CI (99.9%): [1.841, 4.112] (assumes normal distribution)


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.852 ±(99.9%) 0.002 ms/op
Iteration   1: 2.865 ±(99.9%) 0.003 ms/op
Iteration   2: 2.853 ±(99.9%) 0.002 ms/op
Iteration   3: 2.844 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.854 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (2.844, 2.854, 2.865), stdev = 0.011
  CI (99.9%): [2.662, 3.045] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.004 ms/op
Iteration   1: 2.978 ±(99.9%) 0.004 ms/op
Iteration   2: 2.972 ±(99.9%) 0.004 ms/op
Iteration   3: 2.946 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.965 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (2.946, 2.965, 2.978), stdev = 0.017
  CI (99.9%): [2.661, 3.270] (assumes normal distribution)


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
# Warmup Iteration   1: 4.924 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.010 ms/op
Iteration   1: 3.856 ±(99.9%) 0.008 ms/op
Iteration   2: 3.876 ±(99.9%) 0.058 ms/op
Iteration   3: 3.841 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.858 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (3.841, 3.858, 3.876), stdev = 0.018
  CI (99.9%): [3.531, 4.184] (assumes normal distribution)


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.767 ms/op
                 createUser·p0.9999: 13.359 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   2: 2.855 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   2.892 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.112 ms/op
                 createUser·p0.999:  7.278 ms/op
                 createUser·p0.9999: 15.234 ms/op
                 createUser·p1.00:   15.401 ms/op

Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  9.023 ms/op
                 createUser·p0.9999: 16.672 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325573
  mean =      2.948 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1351 
    [ 1.250,  2.500) = 41425 
    [ 2.500,  3.750) = 265125 
    [ 3.750,  5.000) = 16380 
    [ 5.000,  6.250) = 615 
    [ 6.250,  7.500) = 275 
    [ 7.500,  8.750) = 139 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.126 ms/op
     p(99.9900) =     15.317 ms/op
     p(99.9990) =     16.892 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.877 ±(99.9%) 0.006 ms/op
Iteration   1: 2.871 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  6.384 ms/op
                 existUser·p0.9999: 12.744 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   2: 2.834 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  5.361 ms/op
                 existUser·p0.9999: 13.447 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   3: 2.869 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.005 ms/op
                 existUser·p0.999:  8.112 ms/op
                 existUser·p0.9999: 17.653 ms/op
                 existUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335885
  mean =      2.858 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1204 
    [ 1.250,  2.500) = 46880 
    [ 2.500,  3.750) = 281657 
    [ 3.750,  5.000) = 5525 
    [ 5.000,  6.250) = 229 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      6.570 ms/op
     p(99.9900) =     15.785 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.930 ms/op
                 getUser·p0.9999: 12.705 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.193 ms/op
                 getUser·p0.9999: 14.979 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.479 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321169
  mean =      2.989 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 745 
    [ 1.250,  2.500) = 30690 
    [ 2.500,  3.750) = 276223 
    [ 3.750,  5.000) = 11964 
    [ 5.000,  6.250) = 965 
    [ 6.250,  7.500) = 320 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.193 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 5.324 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.010 ms/op
Iteration   1: 3.930 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.391 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 3.909 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  13.763 ms/op
                 listUser·p0.9999: 15.329 ms/op
                 listUser·p1.00:   16.253 ms/op

Iteration   3: 3.764 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  18.100 ms/op
                 listUser·p0.9999: 25.821 ms/op
                 listUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248473
  mean =      3.866 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2788 
    [ 2.500,  5.000) = 226424 
    [ 5.000,  7.500) = 18153 
    [ 7.500, 10.000) = 682 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     14.050 ms/op
     p(99.9900) =     24.946 ms/op
     p(99.9990) =     25.986 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.736 ± 3.639  ops/ms
ClientGrpc.existUser                       thrpt       3  11.332 ± 0.608  ops/ms
ClientGrpc.getUser                         thrpt       3  10.522 ± 1.955  ops/ms
ClientGrpc.listUser                        thrpt       3   8.169 ± 0.549  ops/ms
ClientGrpc.createUser                       avgt       3   2.976 ± 1.136   ms/op
ClientGrpc.existUser                        avgt       3   2.854 ± 0.192   ms/op
ClientGrpc.getUser                          avgt       3   2.965 ± 0.304   ms/op
ClientGrpc.listUser                         avgt       3   3.858 ± 0.327   ms/op
ClientGrpc.createUser                     sample  325573   2.948 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.677           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.933           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.126           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.317           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.039           ms/op
ClientGrpc.existUser                      sample  335885   2.858 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.573           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.297           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.570           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.785           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.088           ms/op
ClientGrpc.getUser                        sample  321169   2.989 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.579           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.193           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.007           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.612           ms/op
ClientGrpc.listUser                       sample  248473   3.866 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.073           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.050           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.946           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.475           ms/op
