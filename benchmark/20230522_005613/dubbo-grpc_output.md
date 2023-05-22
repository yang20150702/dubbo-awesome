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
# Warmup Iteration   1: 3.572 ops/ms
# Warmup Iteration   2: 8.540 ops/ms
# Warmup Iteration   3: 9.759 ops/ms
Iteration   1: 10.179 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.379 ±(99.9%) 4.081 ops/ms [Average]
  (min, avg, max) = (10.179, 10.379, 10.621), stdev = 0.224
  CI (99.9%): [6.298, 14.461] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.154 ops/ms
# Warmup Iteration   2: 10.248 ops/ms
# Warmup Iteration   3: 10.942 ops/ms
Iteration   1: 10.692 ops/ms
Iteration   2: 10.838 ops/ms
Iteration   3: 10.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.810 ±(99.9%) 1.935 ops/ms [Average]
  (min, avg, max) = (10.692, 10.810, 10.899), stdev = 0.106
  CI (99.9%): [8.875, 12.744] (assumes normal distribution)


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
# Warmup Iteration   1: 6.495 ops/ms
# Warmup Iteration   2: 9.931 ops/ms
# Warmup Iteration   3: 10.186 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.307 ops/ms
Iteration   3: 10.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.409 ±(99.9%) 1.753 ops/ms [Average]
  (min, avg, max) = (10.307, 10.409, 10.498), stdev = 0.096
  CI (99.9%): [8.656, 12.161] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.326 ops/ms
# Warmup Iteration   2: 7.641 ops/ms
# Warmup Iteration   3: 7.936 ops/ms
Iteration   1: 7.798 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 7.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.938 ±(99.9%) 2.261 ops/ms [Average]
  (min, avg, max) = (7.798, 7.938, 8.035), stdev = 0.124
  CI (99.9%): [5.678, 10.199] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.175 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.003 ms/op
Iteration   1: 3.132 ±(99.9%) 0.002 ms/op
Iteration   2: 3.123 ±(99.9%) 0.002 ms/op
Iteration   3: 3.017 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.091 ±(99.9%) 1.164 ms/op [Average]
  (min, avg, max) = (3.017, 3.091, 3.132), stdev = 0.064
  CI (99.9%): [1.927, 4.255] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.403 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.002 ms/op
Iteration   1: 2.872 ±(99.9%) 0.002 ms/op
Iteration   2: 2.900 ±(99.9%) 0.002 ms/op
Iteration   3: 2.961 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.911 ±(99.9%) 0.832 ms/op [Average]
  (min, avg, max) = (2.872, 2.911, 2.961), stdev = 0.046
  CI (99.9%): [2.078, 3.743] (assumes normal distribution)


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.004 ms/op
Iteration   1: 3.138 ±(99.9%) 0.002 ms/op
Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
Iteration   3: 3.065 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.082 ±(99.9%) 0.912 ms/op [Average]
  (min, avg, max) = (3.042, 3.082, 3.138), stdev = 0.050
  CI (99.9%): [2.169, 3.994] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.800 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.261 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.024 ms/op
Iteration   1: 3.971 ±(99.9%) 0.014 ms/op
Iteration   2: 3.919 ±(99.9%) 0.006 ms/op
Iteration   3: 3.854 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.914 ±(99.9%) 1.069 ms/op [Average]
  (min, avg, max) = (3.854, 3.914, 3.971), stdev = 0.059
  CI (99.9%): [2.845, 4.984] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.381 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.107 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.806 ms/op
                 createUser·p0.9999: 17.554 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  6.931 ms/op
                 createUser·p0.9999: 18.554 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.457 ms/op
                 createUser·p0.9999: 20.366 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311831
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21011 
    [ 2.500,  5.000) = 289633 
    [ 5.000,  7.500) = 867 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.563 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     20.574 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.005 ms/op
Iteration   1: 2.938 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  9.013 ms/op
                 existUser·p0.9999: 18.026 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   2: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.493 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  9.880 ms/op
                 existUser·p0.9999: 15.076 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   3: 2.949 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  11.332 ms/op
                 existUser·p0.9999: 14.893 ms/op
                 existUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325686
  mean =      2.947 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29013 
    [ 2.500,  5.000) = 295264 
    [ 5.000,  7.500) = 981 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     17.093 ms/op
     p(99.9990) =     18.796 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.006 ms/op
Iteration   1: 3.186 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  7.258 ms/op
                 getUser·p0.9999: 13.320 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   2: 3.080 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  10.784 ms/op
                 getUser·p0.9999: 15.427 ms/op
                 getUser·p1.00:   15.745 ms/op

Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  6.840 ms/op
                 getUser·p0.9999: 15.355 ms/op
                 getUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306992
  mean =      3.127 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 326 
    [ 1.250,  2.500) = 11941 
    [ 2.500,  3.750) = 272277 
    [ 3.750,  5.000) = 20926 
    [ 5.000,  6.250) = 963 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.447 ms/op
     p(99.9900) =     15.308 ms/op
     p(99.9990) =     15.870 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 5.625 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.257 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.011 ms/op
Iteration   1: 4.016 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 17.434 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  17.428 ms/op
                 listUser·p0.9999: 23.723 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   3: 3.937 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  16.265 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241149
  mean =      3.981 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2342 
    [ 2.500,  5.000) = 218163 
    [ 5.000,  7.500) = 19307 
    [ 7.500, 10.000) = 816 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     15.284 ms/op
     p(99.9900) =     22.828 ms/op
     p(99.9990) =     25.000 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.379 ± 4.081  ops/ms
ClientGrpc.existUser                       thrpt       3  10.810 ± 1.935  ops/ms
ClientGrpc.getUser                         thrpt       3  10.409 ± 1.753  ops/ms
ClientGrpc.listUser                        thrpt       3   7.938 ± 2.261  ops/ms
ClientGrpc.createUser                       avgt       3   3.091 ± 1.164   ms/op
ClientGrpc.existUser                        avgt       3   2.911 ± 0.832   ms/op
ClientGrpc.getUser                          avgt       3   3.082 ± 0.912   ms/op
ClientGrpc.listUser                         avgt       3   3.914 ± 1.069   ms/op
ClientGrpc.createUser                     sample  311831   3.078 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.775           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.563           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.825           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.611           ms/op
ClientGrpc.existUser                      sample  325686   2.947 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.493           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.503           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.093           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  306992   3.127 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.638           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.447           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.308           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.073           ms/op
ClientGrpc.listUser                       sample  241149   3.981 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.846           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.284           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.828           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
