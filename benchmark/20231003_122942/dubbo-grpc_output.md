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
# Warmup Iteration   1: 4.015 ops/ms
# Warmup Iteration   2: 8.759 ops/ms
# Warmup Iteration   3: 9.498 ops/ms
Iteration   1: 9.717 ops/ms
Iteration   2: 9.920 ops/ms
Iteration   3: 9.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.877 ±(99.9%) 2.611 ops/ms [Average]
  (min, avg, max) = (9.717, 9.877, 9.994), stdev = 0.143
  CI (99.9%): [7.266, 12.488] (assumes normal distribution)


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
# Warmup Iteration   1: 7.013 ops/ms
# Warmup Iteration   2: 9.865 ops/ms
# Warmup Iteration   3: 10.509 ops/ms
Iteration   1: 10.418 ops/ms
Iteration   2: 10.721 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.532 ±(99.9%) 3.007 ops/ms [Average]
  (min, avg, max) = (10.418, 10.532, 10.721), stdev = 0.165
  CI (99.9%): [7.525, 13.540] (assumes normal distribution)


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
# Warmup Iteration   1: 6.496 ops/ms
# Warmup Iteration   2: 9.572 ops/ms
# Warmup Iteration   3: 9.928 ops/ms
Iteration   1: 10.044 ops/ms
Iteration   2: 9.863 ops/ms
Iteration   3: 10.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.045 ±(99.9%) 3.345 ops/ms [Average]
  (min, avg, max) = (9.863, 10.045, 10.229), stdev = 0.183
  CI (99.9%): [6.700, 13.390] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.212 ops/ms
# Warmup Iteration   2: 7.969 ops/ms
# Warmup Iteration   3: 8.078 ops/ms
Iteration   1: 7.980 ops/ms
Iteration   2: 8.143 ops/ms
Iteration   3: 8.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.118 ±(99.9%) 2.336 ops/ms [Average]
  (min, avg, max) = (7.980, 8.118, 8.233), stdev = 0.128
  CI (99.9%): [5.782, 10.455] (assumes normal distribution)


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.004 ms/op
Iteration   1: 3.178 ±(99.9%) 0.007 ms/op
Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
Iteration   3: 3.106 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.128 ±(99.9%) 0.802 ms/op [Average]
  (min, avg, max) = (3.099, 3.128, 3.178), stdev = 0.044
  CI (99.9%): [2.326, 3.930] (assumes normal distribution)


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
# Warmup Iteration   1: 4.170 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.002 ms/op
Iteration   1: 3.038 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.007 ms/op
Iteration   3: 2.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.015 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (2.979, 3.015, 3.038), stdev = 0.032
  CI (99.9%): [2.435, 3.594] (assumes normal distribution)


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
# Warmup Iteration   1: 4.350 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.003 ms/op
Iteration   1: 3.121 ±(99.9%) 0.004 ms/op
Iteration   2: 3.090 ±(99.9%) 0.003 ms/op
Iteration   3: 3.060 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.090 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (3.060, 3.090, 3.121), stdev = 0.030
  CI (99.9%): [2.536, 3.645] (assumes normal distribution)


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
# Warmup Iteration   1: 5.423 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.017 ms/op
Iteration   1: 3.968 ±(99.9%) 0.016 ms/op
Iteration   2: 3.936 ±(99.9%) 0.030 ms/op
Iteration   3: 3.915 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.940 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (3.915, 3.940, 3.968), stdev = 0.026
  CI (99.9%): [3.458, 4.421] (assumes normal distribution)


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
# Warmup Iteration   1: 4.369 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.007 ms/op
Iteration   1: 3.120 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.847 ms/op
                 createUser·p0.9999: 19.709 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  13.585 ms/op
                 createUser·p0.9999: 17.587 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  14.809 ms/op
                 createUser·p0.9999: 20.545 ms/op
                 createUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305520
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11936 
    [ 2.500,  5.000) = 291837 
    [ 5.000,  7.500) = 1150 
    [ 7.500, 10.000) = 229 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =     13.639 ms/op
     p(99.9900) =     20.265 ms/op
     p(99.9990) =     21.002 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  7.940 ms/op
                 existUser·p0.9999: 12.905 ms/op
                 existUser·p1.00:   24.216 ms/op

Iteration   2: 2.938 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  10.183 ms/op
                 existUser·p0.9999: 15.836 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   3: 2.914 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   3.969 ms/op
                 existUser·p0.999:  10.273 ms/op
                 existUser·p0.9999: 21.235 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326330
  mean =      2.940 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37567 
    [ 2.500,  5.000) = 287262 
    [ 5.000,  7.500) = 1049 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     16.658 ms/op
     p(99.9990) =     24.076 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 4.379 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
Iteration   1: 3.092 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  11.790 ms/op
                 getUser·p0.9999: 24.652 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.497 ms/op
                 getUser·p0.9999: 14.762 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  9.315 ms/op
                 getUser·p0.9999: 17.933 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309802
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13336 
    [ 2.500,  5.000) = 294596 
    [ 5.000,  7.500) = 1414 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      9.195 ms/op
     p(99.9900) =     16.106 ms/op
     p(99.9990) =     24.966 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 4.955 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.010 ms/op
Iteration   1: 3.940 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   2: 3.893 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 16.685 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 3.987 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 17.857 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243483
  mean =      3.940 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1903 
    [ 2.500,  5.000) = 226989 
    [ 5.000,  7.500) = 13240 
    [ 7.500, 10.000) = 702 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     17.498 ms/op
     p(99.9990) =     20.081 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.877 ± 2.611  ops/ms
ClientGrpc.existUser                       thrpt       3  10.532 ± 3.007  ops/ms
ClientGrpc.getUser                         thrpt       3  10.045 ± 3.345  ops/ms
ClientGrpc.listUser                        thrpt       3   8.118 ± 2.336  ops/ms
ClientGrpc.createUser                       avgt       3   3.128 ± 0.802   ms/op
ClientGrpc.existUser                        avgt       3   3.015 ± 0.579   ms/op
ClientGrpc.getUser                          avgt       3   3.090 ± 0.555   ms/op
ClientGrpc.listUser                         avgt       3   3.940 ± 0.481   ms/op
ClientGrpc.createUser                     sample  305520   3.141 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.717           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.639           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.265           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.070           ms/op
ClientGrpc.existUser                      sample  326330   2.940 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.575           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.798           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.658           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.216           ms/op
ClientGrpc.getUser                        sample  309802   3.096 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.748           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.195           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.106           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.100           ms/op
ClientGrpc.listUser                       sample  243483   3.940 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.081           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.631           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.498           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.382           ms/op
