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
# Warmup Iteration   1: 4.735 ops/ms
# Warmup Iteration   2: 9.390 ops/ms
# Warmup Iteration   3: 9.999 ops/ms
Iteration   1: 10.175 ops/ms
Iteration   2: 10.354 ops/ms
Iteration   3: 10.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.272 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (10.175, 10.272, 10.354), stdev = 0.091
  CI (99.9%): [8.620, 11.925] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.827 ops/ms
# Warmup Iteration   2: 10.797 ops/ms
# Warmup Iteration   3: 10.726 ops/ms
Iteration   1: 10.975 ops/ms
Iteration   2: 11.030 ops/ms
Iteration   3: 11.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.011 ±(99.9%) 0.563 ops/ms [Average]
  (min, avg, max) = (10.975, 11.011, 11.030), stdev = 0.031
  CI (99.9%): [10.447, 11.574] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.476 ops/ms
# Warmup Iteration   2: 10.046 ops/ms
# Warmup Iteration   3: 10.282 ops/ms
Iteration   1: 10.449 ops/ms
Iteration   2: 10.351 ops/ms
Iteration   3: 10.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.320 ±(99.9%) 2.668 ops/ms [Average]
  (min, avg, max) = (10.161, 10.320, 10.449), stdev = 0.146
  CI (99.9%): [7.652, 12.988] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.956 ops/ms
# Warmup Iteration   2: 8.332 ops/ms
# Warmup Iteration   3: 8.524 ops/ms
Iteration   1: 8.542 ops/ms
Iteration   2: 8.631 ops/ms
Iteration   3: 8.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.583 ±(99.9%) 0.822 ops/ms [Average]
  (min, avg, max) = (8.542, 8.583, 8.631), stdev = 0.045
  CI (99.9%): [7.760, 9.405] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.074 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.003 ms/op
Iteration   1: 3.140 ±(99.9%) 0.001 ms/op
Iteration   2: 3.081 ±(99.9%) 0.003 ms/op
Iteration   3: 3.033 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.085 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.033, 3.085, 3.140), stdev = 0.053
  CI (99.9%): [2.109, 4.061] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.003 ms/op
Iteration   1: 2.951 ±(99.9%) 0.002 ms/op
Iteration   2: 2.959 ±(99.9%) 0.003 ms/op
Iteration   3: 2.898 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.936 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (2.898, 2.936, 2.959), stdev = 0.033
  CI (99.9%): [2.335, 3.537] (assumes normal distribution)


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.002 ms/op
Iteration   1: 3.166 ±(99.9%) 0.003 ms/op
Iteration   2: 3.089 ±(99.9%) 0.002 ms/op
Iteration   3: 3.082 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.112 ±(99.9%) 0.846 ms/op [Average]
  (min, avg, max) = (3.082, 3.112, 3.166), stdev = 0.046
  CI (99.9%): [2.266, 3.959] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.589 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.044 ms/op
Iteration   1: 3.850 ±(99.9%) 0.048 ms/op
Iteration   2: 3.837 ±(99.9%) 0.016 ms/op
Iteration   3: 3.856 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.848 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (3.837, 3.848, 3.856), stdev = 0.010
  CI (99.9%): [3.672, 4.023] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.825 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
Iteration   1: 3.085 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  7.801 ms/op
                 createUser·p0.9999: 11.272 ms/op
                 createUser·p1.00:   11.387 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.623 ms/op
                 createUser·p0.9999: 13.280 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   3: 3.182 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  10.174 ms/op
                 createUser·p0.9999: 26.542 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309018
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14305 
    [ 2.500,  5.000) = 292722 
    [ 5.000,  7.500) = 1450 
    [ 7.500, 10.000) = 297 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     24.972 ms/op
     p(99.9990) =     26.575 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 2.931 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  7.423 ms/op
                 existUser·p0.9999: 15.128 ms/op
                 existUser·p1.00:   15.843 ms/op

Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 13.907 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.044 ms/op
                 existUser·p0.9999: 16.128 ms/op
                 existUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324903
  mean =      2.957 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2159 
    [ 1.250,  2.500) = 26825 
    [ 2.500,  3.750) = 284503 
    [ 3.750,  5.000) = 10061 
    [ 5.000,  6.250) = 724 
    [ 6.250,  7.500) = 270 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.643 ms/op
     p(99.9900) =     15.737 ms/op
     p(99.9990) =     16.478 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
Iteration   1: 3.147 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.922 ms/op
                 getUser·p0.9999: 16.695 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.136 ms/op
                 getUser·p0.9999: 15.818 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  9.765 ms/op
                 getUser·p0.9999: 19.750 ms/op
                 getUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310960
  mean =      3.089 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9703 
    [ 2.500,  5.000) = 299937 
    [ 5.000,  7.500) = 985 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.742 ms/op
     p(99.9900) =     17.921 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 4.856 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.009 ms/op
Iteration   1: 3.875 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  12.819 ms/op
                 listUser·p0.9999: 15.511 ms/op
                 listUser·p1.00:   16.105 ms/op

Iteration   2: 3.842 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  12.730 ms/op
                 listUser·p0.9999: 15.106 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   3: 3.841 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  12.825 ms/op
                 listUser·p0.9999: 19.672 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249181
  mean =      3.853 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3569 
    [ 2.500,  5.000) = 230821 
    [ 5.000,  7.500) = 13937 
    [ 7.500, 10.000) = 435 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     20.022 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.272 ± 1.652  ops/ms
ClientGrpc.existUser                       thrpt       3  11.011 ± 0.563  ops/ms
ClientGrpc.getUser                         thrpt       3  10.320 ± 2.668  ops/ms
ClientGrpc.listUser                        thrpt       3   8.583 ± 0.822  ops/ms
ClientGrpc.createUser                       avgt       3   3.085 ± 0.976   ms/op
ClientGrpc.existUser                        avgt       3   2.936 ± 0.601   ms/op
ClientGrpc.getUser                          avgt       3   3.112 ± 0.846   ms/op
ClientGrpc.listUser                         avgt       3   3.848 ± 0.175   ms/op
ClientGrpc.createUser                     sample  309018   3.105 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.679           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.765           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.972           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.575           ms/op
ClientGrpc.existUser                      sample  324903   2.957 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.691           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.643           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.737           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.630           ms/op
ClientGrpc.getUser                        sample  310960   3.089 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.646           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.742           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.921           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.185           ms/op
ClientGrpc.listUser                       sample  249181   3.853 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.995           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.375           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.496           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.763           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.777           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.120           ms/op
