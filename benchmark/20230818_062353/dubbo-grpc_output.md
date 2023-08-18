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
# Warmup Iteration   1: 3.832 ops/ms
# Warmup Iteration   2: 8.457 ops/ms
# Warmup Iteration   3: 9.776 ops/ms
Iteration   1: 10.142 ops/ms
Iteration   2: 10.263 ops/ms
Iteration   3: 10.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.296 ±(99.9%) 3.141 ops/ms [Average]
  (min, avg, max) = (10.142, 10.296, 10.482), stdev = 0.172
  CI (99.9%): [7.155, 13.436] (assumes normal distribution)


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
# Warmup Iteration   1: 7.063 ops/ms
# Warmup Iteration   2: 10.372 ops/ms
# Warmup Iteration   3: 10.907 ops/ms
Iteration   1: 10.925 ops/ms
Iteration   2: 10.943 ops/ms
Iteration   3: 10.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.879 ±(99.9%) 1.746 ops/ms [Average]
  (min, avg, max) = (10.769, 10.879, 10.943), stdev = 0.096
  CI (99.9%): [9.133, 12.625] (assumes normal distribution)


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
# Warmup Iteration   1: 6.582 ops/ms
# Warmup Iteration   2: 9.899 ops/ms
# Warmup Iteration   3: 10.307 ops/ms
Iteration   1: 10.382 ops/ms
Iteration   2: 10.350 ops/ms
Iteration   3: 10.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.362 ±(99.9%) 0.325 ops/ms [Average]
  (min, avg, max) = (10.350, 10.362, 10.382), stdev = 0.018
  CI (99.9%): [10.037, 10.687] (assumes normal distribution)


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
# Warmup Iteration   1: 5.916 ops/ms
# Warmup Iteration   2: 7.355 ops/ms
# Warmup Iteration   3: 7.594 ops/ms
Iteration   1: 7.820 ops/ms
Iteration   2: 7.700 ops/ms
Iteration   3: 7.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.749 ±(99.9%) 1.149 ops/ms [Average]
  (min, avg, max) = (7.700, 7.749, 7.820), stdev = 0.063
  CI (99.9%): [6.600, 8.898] (assumes normal distribution)


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
# Warmup Iteration   1: 4.516 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.003 ms/op
Iteration   1: 3.120 ±(99.9%) 0.005 ms/op
Iteration   2: 3.051 ±(99.9%) 0.003 ms/op
Iteration   3: 3.073 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.081 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.051, 3.081, 3.120), stdev = 0.035
  CI (99.9%): [2.436, 3.727] (assumes normal distribution)


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
# Warmup Iteration   1: 4.175 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.004 ms/op
Iteration   1: 2.833 ±(99.9%) 0.003 ms/op
Iteration   2: 2.978 ±(99.9%) 0.003 ms/op
Iteration   3: 2.969 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.927 ±(99.9%) 1.484 ms/op [Average]
  (min, avg, max) = (2.833, 2.927, 2.978), stdev = 0.081
  CI (99.9%): [1.443, 4.411] (assumes normal distribution)


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
# Warmup Iteration   1: 4.714 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.003 ms/op
Iteration   1: 3.122 ±(99.9%) 0.003 ms/op
Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
Iteration   3: 3.112 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.102 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (3.071, 3.102, 3.122), stdev = 0.027
  CI (99.9%): [2.603, 3.600] (assumes normal distribution)


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
# Warmup Iteration   1: 5.679 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.015 ms/op
Iteration   1: 4.055 ±(99.9%) 0.009 ms/op
Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
Iteration   3: 3.930 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.998 ±(99.9%) 1.156 ms/op [Average]
  (min, avg, max) = (3.930, 3.998, 4.055), stdev = 0.063
  CI (99.9%): [2.841, 5.154] (assumes normal distribution)


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.651 ms/op
                 createUser·p0.9999: 19.792 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  7.569 ms/op
                 createUser·p0.9999: 15.163 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  9.584 ms/op
                 createUser·p0.9999: 17.039 ms/op
                 createUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312941
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22291 
    [ 2.500,  5.000) = 288489 
    [ 5.000,  7.500) = 1672 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.699 ms/op
     p(99.9000) =      8.390 ms/op
     p(99.9900) =     18.583 ms/op
     p(99.9990) =     20.345 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 3.569 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
Iteration   1: 2.942 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.356 ms/op
                 existUser·p0.9999: 12.604 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  8.039 ms/op
                 existUser·p0.9999: 16.585 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.725 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327068
  mean =      2.936 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1398 
    [ 1.250,  2.500) = 30884 
    [ 2.500,  3.750) = 284669 
    [ 3.750,  5.000) = 8393 
    [ 5.000,  6.250) = 711 
    [ 6.250,  7.500) = 621 
    [ 7.500,  8.750) = 179 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     17.475 ms/op
     p(99.9990) =     18.103 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 4.291 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.849 ms/op
                 getUser·p0.999:  8.750 ms/op
                 getUser·p0.9999: 27.825 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  7.741 ms/op
                 getUser·p0.9999: 18.535 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  9.322 ms/op
                 getUser·p0.9999: 22.135 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310134
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17603 
    [ 2.500,  5.000) = 289945 
    [ 5.000,  7.500) = 1982 
    [ 7.500, 10.000) = 407 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      8.747 ms/op
     p(99.9900) =     27.228 ms/op
     p(99.9990) =     28.305 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 5.804 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.011 ms/op
Iteration   1: 4.076 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 18.065 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   2: 4.035 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.472 ms/op
                 listUser·p0.9999: 20.358 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.078 ms/op
                 listUser·p0.9999: 19.630 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237644
  mean =      4.040 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2599 
    [ 2.500,  5.000) = 207581 
    [ 5.000,  7.500) = 25482 
    [ 7.500, 10.000) = 1463 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     20.783 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.296 ± 3.141  ops/ms
ClientGrpc.existUser                       thrpt       3  10.879 ± 1.746  ops/ms
ClientGrpc.getUser                         thrpt       3  10.362 ± 0.325  ops/ms
ClientGrpc.listUser                        thrpt       3   7.749 ± 1.149  ops/ms
ClientGrpc.createUser                       avgt       3   3.081 ± 0.646   ms/op
ClientGrpc.existUser                        avgt       3   2.927 ± 1.484   ms/op
ClientGrpc.getUser                          avgt       3   3.102 ± 0.498   ms/op
ClientGrpc.listUser                         avgt       3   3.998 ± 1.156   ms/op
ClientGrpc.createUser                     sample  312941   3.066 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.829           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.699           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.390           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.583           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.578           ms/op
ClientGrpc.existUser                      sample  327068   2.936 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.765           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.815           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.475           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.219           ms/op
ClientGrpc.getUser                        sample  310134   3.096 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.847           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.747           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.228           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.475           ms/op
ClientGrpc.listUser                       sample  237644   4.040 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.853           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.631           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.923           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.906           ms/op
