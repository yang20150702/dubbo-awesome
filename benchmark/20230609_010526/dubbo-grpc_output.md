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
# Warmup Iteration   1: 3.480 ops/ms
# Warmup Iteration   2: 6.886 ops/ms
# Warmup Iteration   3: 7.804 ops/ms
Iteration   1: 8.151 ops/ms
Iteration   2: 8.320 ops/ms
Iteration   3: 8.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.265 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (8.151, 8.265, 8.323), stdev = 0.099
  CI (99.9%): [6.466, 10.064] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.204 ops/ms
# Warmup Iteration   2: 8.170 ops/ms
# Warmup Iteration   3: 8.460 ops/ms
Iteration   1: 8.960 ops/ms
Iteration   2: 9.165 ops/ms
Iteration   3: 8.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.021 ±(99.9%) 2.286 ops/ms [Average]
  (min, avg, max) = (8.937, 9.021, 9.165), stdev = 0.125
  CI (99.9%): [6.734, 11.307] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.729 ops/ms
# Warmup Iteration   2: 7.892 ops/ms
# Warmup Iteration   3: 8.096 ops/ms
Iteration   1: 8.419 ops/ms
Iteration   2: 8.704 ops/ms
Iteration   3: 8.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.516 ±(99.9%) 2.972 ops/ms [Average]
  (min, avg, max) = (8.419, 8.516, 8.704), stdev = 0.163
  CI (99.9%): [5.544, 11.488] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.522 ops/ms
# Warmup Iteration   2: 6.080 ops/ms
# Warmup Iteration   3: 6.558 ops/ms
Iteration   1: 6.498 ops/ms
Iteration   2: 6.775 ops/ms
Iteration   3: 6.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.591 ±(99.9%) 2.904 ops/ms [Average]
  (min, avg, max) = (6.498, 6.591, 6.775), stdev = 0.159
  CI (99.9%): [3.686, 9.495] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.145 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.011 ms/op
Iteration   1: 3.722 ±(99.9%) 0.004 ms/op
Iteration   2: 3.785 ±(99.9%) 0.003 ms/op
Iteration   3: 3.695 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.734 ±(99.9%) 0.841 ms/op [Average]
  (min, avg, max) = (3.695, 3.734, 3.785), stdev = 0.046
  CI (99.9%): [2.893, 4.575] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.783 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.003 ms/op
Iteration   1: 3.684 ±(99.9%) 0.004 ms/op
Iteration   2: 3.777 ±(99.9%) 0.004 ms/op
Iteration   3: 3.555 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.672 ±(99.9%) 2.034 ms/op [Average]
  (min, avg, max) = (3.555, 3.672, 3.777), stdev = 0.111
  CI (99.9%): [1.638, 5.705] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.189 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.007 ms/op
Iteration   1: 3.716 ±(99.9%) 0.003 ms/op
Iteration   2: 3.797 ±(99.9%) 0.003 ms/op
Iteration   3: 3.917 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.810 ±(99.9%) 1.847 ms/op [Average]
  (min, avg, max) = (3.716, 3.810, 3.917), stdev = 0.101
  CI (99.9%): [1.963, 5.657] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.994 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.204 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.011 ms/op
Iteration   1: 4.963 ±(99.9%) 0.017 ms/op
Iteration   2: 4.961 ±(99.9%) 0.008 ms/op
Iteration   3: 4.952 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.959 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (4.952, 4.959, 4.963), stdev = 0.006
  CI (99.9%): [4.854, 5.064] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.012 ms/op
Iteration   1: 4.005 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   7.455 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 14.516 ms/op
                 createUser·p1.00:   16.581 ms/op

Iteration   2: 3.853 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  12.688 ms/op
                 createUser·p0.9999: 30.216 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   3: 3.928 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  18.105 ms/op
                 createUser·p0.9999: 23.223 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244349
  mean =      3.927 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4467 
    [ 2.500,  5.000) = 221257 
    [ 5.000,  7.500) = 16648 
    [ 7.500, 10.000) = 1590 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     11.648 ms/op
     p(99.9900) =     24.791 ms/op
     p(99.9990) =     30.427 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.955 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.709 ±(99.9%) 0.011 ms/op
Iteration   1: 3.596 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  10.109 ms/op
                 existUser·p0.9999: 27.791 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   2: 3.557 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  10.436 ms/op
                 existUser·p0.9999: 19.759 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   3: 3.617 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  14.428 ms/op
                 existUser·p0.9999: 20.354 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267337
  mean =      3.590 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10839 
    [ 2.500,  5.000) = 245691 
    [ 5.000,  7.500) = 9267 
    [ 7.500, 10.000) = 1127 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     11.906 ms/op
     p(99.9900) =     27.272 ms/op
     p(99.9990) =     27.929 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.462 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.010 ms/op
Iteration   1: 3.813 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   6.909 ms/op
                 getUser·p0.999:  9.947 ms/op
                 getUser·p0.9999: 16.908 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 3.829 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  11.714 ms/op
                 getUser·p0.9999: 18.416 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   3: 3.814 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  10.306 ms/op
                 getUser·p0.9999: 18.914 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251348
  mean =      3.819 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9624 
    [ 2.500,  5.000) = 224863 
    [ 5.000,  7.500) = 15207 
    [ 7.500, 10.000) = 1340 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      6.869 ms/op
     p(99.9000) =     10.420 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     20.089 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 6.570 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.078 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.999 ±(99.9%) 0.020 ms/op
Iteration   1: 4.977 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.266 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  15.002 ms/op
                 listUser·p0.9999: 17.811 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   2: 4.768 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   7.201 ms/op
                 listUser·p0.99:   9.571 ms/op
                 listUser·p0.999:  19.087 ms/op
                 listUser·p0.9999: 20.906 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 4.883 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.176 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  20.349 ms/op
                 listUser·p0.9999: 23.767 ms/op
                 listUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197116
  mean =      4.874 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 351 
    [ 2.500,  5.000) = 135802 
    [ 5.000,  7.500) = 53213 
    [ 7.500, 10.000) = 6424 
    [10.000, 12.500) = 768 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      6.365 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =      9.339 ms/op
     p(99.9000) =     17.724 ms/op
     p(99.9900) =     23.163 ms/op
     p(99.9990) =     24.092 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.265 ± 1.799  ops/ms
ClientGrpc.existUser                       thrpt       3   9.021 ± 2.286  ops/ms
ClientGrpc.getUser                         thrpt       3   8.516 ± 2.972  ops/ms
ClientGrpc.listUser                        thrpt       3   6.591 ± 2.904  ops/ms
ClientGrpc.createUser                       avgt       3   3.734 ± 0.841   ms/op
ClientGrpc.existUser                        avgt       3   3.672 ± 2.034   ms/op
ClientGrpc.getUser                          avgt       3   3.810 ± 1.847   ms/op
ClientGrpc.listUser                         avgt       3   4.959 ± 0.105   ms/op
ClientGrpc.createUser                     sample  244349   3.927 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.753           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.341           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.184           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.648           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.791           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.540           ms/op
ClientGrpc.existUser                      sample  267337   3.590 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.894           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.833           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.578           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.906           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.272           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.017           ms/op
ClientGrpc.getUser                        sample  251348   3.819 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.949           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.226           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.869           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.420           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.416           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.906           ms/op
ClientGrpc.listUser                       sample  197116   4.874 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.834           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.365           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.339           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.724           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.163           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.347           ms/op
