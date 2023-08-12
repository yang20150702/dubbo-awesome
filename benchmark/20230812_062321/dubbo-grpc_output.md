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
# Warmup Iteration   1: 4.641 ops/ms
# Warmup Iteration   2: 8.979 ops/ms
# Warmup Iteration   3: 10.405 ops/ms
Iteration   1: 10.889 ops/ms
Iteration   2: 10.789 ops/ms
Iteration   3: 10.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.784 ±(99.9%) 1.956 ops/ms [Average]
  (min, avg, max) = (10.675, 10.784, 10.889), stdev = 0.107
  CI (99.9%): [8.829, 12.740] (assumes normal distribution)


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
# Warmup Iteration   1: 7.937 ops/ms
# Warmup Iteration   2: 10.906 ops/ms
# Warmup Iteration   3: 11.185 ops/ms
Iteration   1: 11.209 ops/ms
Iteration   2: 11.291 ops/ms
Iteration   3: 10.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.135 ±(99.9%) 3.696 ops/ms [Average]
  (min, avg, max) = (10.906, 11.135, 11.291), stdev = 0.203
  CI (99.9%): [7.440, 14.831] (assumes normal distribution)


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
# Warmup Iteration   1: 7.964 ops/ms
# Warmup Iteration   2: 10.573 ops/ms
# Warmup Iteration   3: 10.740 ops/ms
Iteration   1: 11.026 ops/ms
Iteration   2: 10.645 ops/ms
Iteration   3: 10.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.872 ±(99.9%) 3.671 ops/ms [Average]
  (min, avg, max) = (10.645, 10.872, 11.026), stdev = 0.201
  CI (99.9%): [7.201, 14.543] (assumes normal distribution)


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
# Warmup Iteration   1: 5.762 ops/ms
# Warmup Iteration   2: 8.118 ops/ms
# Warmup Iteration   3: 8.181 ops/ms
Iteration   1: 8.155 ops/ms
Iteration   2: 8.109 ops/ms
Iteration   3: 8.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.125 ±(99.9%) 0.475 ops/ms [Average]
  (min, avg, max) = (8.109, 8.125, 8.155), stdev = 0.026
  CI (99.9%): [7.650, 8.599] (assumes normal distribution)


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.004 ms/op
Iteration   1: 2.989 ±(99.9%) 0.002 ms/op
Iteration   2: 2.958 ±(99.9%) 0.004 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.982 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (2.958, 2.982, 2.998), stdev = 0.021
  CI (99.9%): [2.598, 3.366] (assumes normal distribution)


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.944 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.003 ms/op
Iteration   1: 2.828 ±(99.9%) 0.002 ms/op
Iteration   2: 2.804 ±(99.9%) 0.003 ms/op
Iteration   3: 2.844 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.825 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (2.804, 2.825, 2.844), stdev = 0.020
  CI (99.9%): [2.459, 3.191] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.003 ms/op
Iteration   1: 2.994 ±(99.9%) 0.002 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 2.946 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.978 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (2.946, 2.978, 2.994), stdev = 0.028
  CI (99.9%): [2.476, 3.481] (assumes normal distribution)


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
# Warmup Iteration   1: 4.959 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.012 ms/op
Iteration   1: 3.921 ±(99.9%) 0.018 ms/op
Iteration   2: 3.903 ±(99.9%) 0.034 ms/op
Iteration   3: 3.940 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.903, 3.922, 3.940), stdev = 0.019
  CI (99.9%): [3.583, 4.260] (assumes normal distribution)


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
# Warmup Iteration   1: 4.154 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.279 ms/op
                 createUser·p0.9999: 12.255 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  8.160 ms/op
                 createUser·p0.9999: 15.945 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  14.582 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320468
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2306 
    [ 1.250,  2.500) = 24940 
    [ 2.500,  3.750) = 275669 
    [ 3.750,  5.000) = 15725 
    [ 5.000,  6.250) = 795 
    [ 6.250,  7.500) = 576 
    [ 7.500,  8.750) = 175 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 75 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     16.052 ms/op
     p(99.9990) =     17.425 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  8.256 ms/op
                 existUser·p0.9999: 13.174 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   2: 2.854 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 12.940 ms/op
                 existUser·p1.00:   13.238 ms/op

Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.463 ms/op
                 existUser·p0.9999: 14.365 ms/op
                 existUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330564
  mean =      2.904 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3328 
    [ 1.250,  2.500) = 45709 
    [ 2.500,  3.750) = 264129 
    [ 3.750,  5.000) = 15463 
    [ 5.000,  6.250) = 1014 
    [ 6.250,  7.500) = 433 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.130 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     14.631 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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
# Warmup Iteration   1: 3.969 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 2.992 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.010 ms/op
                 getUser·p0.9999: 11.724 ms/op
                 getUser·p1.00:   11.928 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.559 ms/op
                 getUser·p0.9999: 19.181 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.603 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.282 ms/op
                 getUser·p0.9999: 14.414 ms/op
                 getUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319652
  mean =      3.003 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1555 
    [ 1.250,  2.500) = 21739 
    [ 2.500,  3.750) = 280301 
    [ 3.750,  5.000) = 14539 
    [ 5.000,  6.250) = 781 
    [ 6.250,  7.500) = 317 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.061 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     19.556 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 5.099 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.011 ms/op
Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  12.831 ms/op
                 listUser·p0.9999: 19.193 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 3.916 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.694 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.585 ms/op
                 listUser·p0.9999: 22.571 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 3.935 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  17.387 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244396
  mean =      3.926 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4037 
    [ 2.500,  5.000) = 216781 
    [ 5.000,  7.500) = 21999 
    [ 7.500, 10.000) = 1049 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     14.461 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     23.120 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.784 ± 1.956  ops/ms
ClientGrpc.existUser                       thrpt       3  11.135 ± 3.696  ops/ms
ClientGrpc.getUser                         thrpt       3  10.872 ± 3.671  ops/ms
ClientGrpc.listUser                        thrpt       3   8.125 ± 0.475  ops/ms
ClientGrpc.createUser                       avgt       3   2.982 ± 0.384   ms/op
ClientGrpc.existUser                        avgt       3   2.825 ± 0.366   ms/op
ClientGrpc.getUser                          avgt       3   2.978 ± 0.502   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 0.338   ms/op
ClientGrpc.createUser                     sample  320468   2.998 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.588           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.405           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.052           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.957           ms/op
ClientGrpc.existUser                      sample  330564   2.904 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.676           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.130           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.173           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.090           ms/op
ClientGrpc.getUser                        sample  319652   3.003 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.603           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.061           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.416           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.694           ms/op
ClientGrpc.listUser                       sample  244396   3.926 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.694           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.461           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.413           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.527           ms/op
