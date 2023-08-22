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
# Warmup Iteration   1: 4.592 ops/ms
# Warmup Iteration   2: 9.258 ops/ms
# Warmup Iteration   3: 9.982 ops/ms
Iteration   1: 10.582 ops/ms
Iteration   2: 10.509 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.540 ±(99.9%) 0.682 ops/ms [Average]
  (min, avg, max) = (10.509, 10.540, 10.582), stdev = 0.037
  CI (99.9%): [9.858, 11.222] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.056 ops/ms
# Warmup Iteration   2: 10.957 ops/ms
# Warmup Iteration   3: 11.150 ops/ms
Iteration   1: 11.223 ops/ms
Iteration   2: 11.211 ops/ms
Iteration   3: 11.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.232 ±(99.9%) 0.490 ops/ms [Average]
  (min, avg, max) = (11.211, 11.232, 11.263), stdev = 0.027
  CI (99.9%): [10.742, 11.722] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.342 ops/ms
# Warmup Iteration   2: 10.137 ops/ms
# Warmup Iteration   3: 10.699 ops/ms
Iteration   1: 10.712 ops/ms
Iteration   2: 10.738 ops/ms
Iteration   3: 10.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.733 ±(99.9%) 0.331 ops/ms [Average]
  (min, avg, max) = (10.712, 10.733, 10.748), stdev = 0.018
  CI (99.9%): [10.402, 11.064] (assumes normal distribution)


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
# Warmup Iteration   1: 5.420 ops/ms
# Warmup Iteration   2: 8.055 ops/ms
# Warmup Iteration   3: 8.177 ops/ms
Iteration   1: 8.245 ops/ms
Iteration   2: 8.349 ops/ms
Iteration   3: 8.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.301 ±(99.9%) 0.959 ops/ms [Average]
  (min, avg, max) = (8.245, 8.301, 8.349), stdev = 0.053
  CI (99.9%): [7.342, 9.261] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.003 ms/op
Iteration   1: 3.060 ±(99.9%) 0.003 ms/op
Iteration   2: 2.977 ±(99.9%) 0.002 ms/op
Iteration   3: 2.942 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.993 ±(99.9%) 1.101 ms/op [Average]
  (min, avg, max) = (2.942, 2.993, 3.060), stdev = 0.060
  CI (99.9%): [1.892, 4.094] (assumes normal distribution)


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.873 ±(99.9%) 0.003 ms/op
Iteration   1: 2.847 ±(99.9%) 0.003 ms/op
Iteration   2: 2.853 ±(99.9%) 0.005 ms/op
Iteration   3: 2.833 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.844 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.833, 2.844, 2.853), stdev = 0.010
  CI (99.9%): [2.657, 3.031] (assumes normal distribution)


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.003 ms/op
Iteration   1: 2.998 ±(99.9%) 0.002 ms/op
Iteration   2: 2.949 ±(99.9%) 0.003 ms/op
Iteration   3: 2.963 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.970 ±(99.9%) 0.466 ms/op [Average]
  (min, avg, max) = (2.949, 2.970, 2.998), stdev = 0.026
  CI (99.9%): [2.504, 3.436] (assumes normal distribution)


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
# Warmup Iteration   1: 4.784 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.026 ms/op
Iteration   1: 3.807 ±(99.9%) 0.017 ms/op
Iteration   2: 3.757 ±(99.9%) 0.004 ms/op
Iteration   3: 3.855 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.806 ±(99.9%) 0.888 ms/op [Average]
  (min, avg, max) = (3.757, 3.806, 3.855), stdev = 0.049
  CI (99.9%): [2.919, 4.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.876 ms/op
                 createUser·p0.9999: 13.148 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.584 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.407 ms/op
                 createUser·p0.9999: 13.105 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   3: 3.003 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.316 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.793 ms/op
                 createUser·p0.999:  8.241 ms/op
                 createUser·p0.9999: 15.424 ms/op
                 createUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319601
  mean =      3.002 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2257 
    [ 1.250,  2.500) = 27227 
    [ 2.500,  3.750) = 273540 
    [ 3.750,  5.000) = 14542 
    [ 5.000,  6.250) = 993 
    [ 6.250,  7.500) = 624 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.316 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     15.801 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 3.374 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.006 ms/op
Iteration   1: 2.935 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.542 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.676 ms/op
                 existUser·p0.9999: 14.324 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   2: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  8.110 ms/op
                 existUser·p0.9999: 17.963 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   3: 2.931 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.530 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 26.381 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327148
  mean =      2.933 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39686 
    [ 2.500,  5.000) = 285665 
    [ 5.000,  7.500) = 1229 
    [ 7.500, 10.000) = 306 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.616 ms/op
     p(99.9900) =     21.183 ms/op
     p(99.9990) =     26.623 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 3.565 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.115 ms/op
                 getUser·p0.9999: 14.005 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 3.005 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.298 ms/op
                 getUser·p0.9999: 25.428 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.594 ms/op
                 getUser·p0.9999: 23.921 ms/op
                 getUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317625
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22956 
    [ 2.500,  5.000) = 292985 
    [ 5.000,  7.500) = 1337 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     26.340 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 4.730 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.010 ms/op
Iteration   1: 3.810 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.491 ms/op
                 listUser·p0.99:   6.965 ms/op
                 listUser·p0.999:  13.074 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 3.835 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 3.848 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 21.727 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250621
  mean =      3.831 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5873 
    [ 2.500,  5.000) = 225244 
    [ 5.000,  7.500) = 18043 
    [ 7.500, 10.000) = 941 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 204 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.847 ms/op
     p(99.9000) =     15.614 ms/op
     p(99.9900) =     20.085 ms/op
     p(99.9990) =     22.298 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.540 ± 0.682  ops/ms
ClientGrpc.existUser                       thrpt       3  11.232 ± 0.490  ops/ms
ClientGrpc.getUser                         thrpt       3  10.733 ± 0.331  ops/ms
ClientGrpc.listUser                        thrpt       3   8.301 ± 0.959  ops/ms
ClientGrpc.createUser                       avgt       3   2.993 ± 1.101   ms/op
ClientGrpc.existUser                        avgt       3   2.844 ± 0.187   ms/op
ClientGrpc.getUser                          avgt       3   2.970 ± 0.466   ms/op
ClientGrpc.listUser                         avgt       3   3.806 ± 0.888   ms/op
ClientGrpc.createUser                     sample  319601   3.002 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.316           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.815           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          13.976           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.876           ms/op
ClientGrpc.existUser                      sample  327148   2.933 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.530           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.616           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.183           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.001           ms/op
ClientGrpc.getUser                        sample  317625   3.023 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.584           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.594           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.838           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.378           ms/op
ClientGrpc.listUser                       sample  250621   3.831 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.785           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.847           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.614           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.085           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.315           ms/op
