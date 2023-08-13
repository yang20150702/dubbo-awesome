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
# Warmup Iteration   1: 4.455 ops/ms
# Warmup Iteration   2: 9.114 ops/ms
# Warmup Iteration   3: 10.047 ops/ms
Iteration   1: 10.546 ops/ms
Iteration   2: 10.389 ops/ms
Iteration   3: 10.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.532 ±(99.9%) 2.491 ops/ms [Average]
  (min, avg, max) = (10.389, 10.532, 10.661), stdev = 0.137
  CI (99.9%): [8.041, 13.023] (assumes normal distribution)


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
# Warmup Iteration   1: 7.522 ops/ms
# Warmup Iteration   2: 10.509 ops/ms
# Warmup Iteration   3: 10.889 ops/ms
Iteration   1: 10.982 ops/ms
Iteration   2: 11.260 ops/ms
Iteration   3: 11.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.154 ±(99.9%) 2.741 ops/ms [Average]
  (min, avg, max) = (10.982, 11.154, 11.260), stdev = 0.150
  CI (99.9%): [8.414, 13.895] (assumes normal distribution)


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
# Warmup Iteration   1: 6.804 ops/ms
# Warmup Iteration   2: 10.328 ops/ms
# Warmup Iteration   3: 10.584 ops/ms
Iteration   1: 10.454 ops/ms
Iteration   2: 10.479 ops/ms
Iteration   3: 10.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.505 ±(99.9%) 1.215 ops/ms [Average]
  (min, avg, max) = (10.454, 10.505, 10.580), stdev = 0.067
  CI (99.9%): [9.289, 11.720] (assumes normal distribution)


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
# Warmup Iteration   1: 5.529 ops/ms
# Warmup Iteration   2: 8.057 ops/ms
# Warmup Iteration   3: 8.023 ops/ms
Iteration   1: 8.165 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 8.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.138 ±(99.9%) 0.440 ops/ms [Average]
  (min, avg, max) = (8.119, 8.138, 8.165), stdev = 0.024
  CI (99.9%): [7.698, 8.579] (assumes normal distribution)


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.004 ms/op
Iteration   1: 3.042 ±(99.9%) 0.016 ms/op
Iteration   2: 3.028 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (3.028, 3.037, 3.042), stdev = 0.007
  CI (99.9%): [2.901, 3.173] (assumes normal distribution)


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.002 ms/op
Iteration   1: 2.869 ±(99.9%) 0.003 ms/op
Iteration   2: 2.844 ±(99.9%) 0.002 ms/op
Iteration   3: 2.960 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 1.115 ms/op [Average]
  (min, avg, max) = (2.844, 2.891, 2.960), stdev = 0.061
  CI (99.9%): [1.776, 4.007] (assumes normal distribution)


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
# Warmup Iteration   1: 4.148 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.004 ms/op
Iteration   1: 3.014 ±(99.9%) 0.003 ms/op
Iteration   2: 2.998 ±(99.9%) 0.004 ms/op
Iteration   3: 3.039 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.017 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (2.998, 3.017, 3.039), stdev = 0.020
  CI (99.9%): [2.647, 3.387] (assumes normal distribution)


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
# Warmup Iteration   1: 5.419 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.020 ms/op
Iteration   1: 3.823 ±(99.9%) 0.026 ms/op
Iteration   2: 3.922 ±(99.9%) 0.013 ms/op
Iteration   3: 3.932 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 1.094 ms/op [Average]
  (min, avg, max) = (3.823, 3.892, 3.932), stdev = 0.060
  CI (99.9%): [2.798, 4.987] (assumes normal distribution)


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
# Warmup Iteration   1: 4.436 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.406 ms/op
                 createUser·p0.9999: 15.516 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   2: 2.989 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  12.056 ms/op
                 createUser·p0.9999: 16.766 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  14.860 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315980
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1254 
    [ 1.250,  2.500) = 26426 
    [ 2.500,  3.750) = 267161 
    [ 3.750,  5.000) = 18967 
    [ 5.000,  6.250) = 1009 
    [ 6.250,  7.500) = 444 
    [ 7.500,  8.750) = 349 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 130 
    [16.250, 17.500) = 54 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =     11.748 ms/op
     p(99.9900) =     16.804 ms/op
     p(99.9990) =     17.434 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 2.863 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  7.629 ms/op
                 existUser·p0.9999: 11.941 ms/op
                 existUser·p1.00:   12.141 ms/op

Iteration   2: 2.887 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   3.990 ms/op
                 existUser·p0.999:  8.161 ms/op
                 existUser·p0.9999: 14.055 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   3: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  8.719 ms/op
                 existUser·p0.9999: 16.847 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331194
  mean =      2.897 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2452 
    [ 1.250,  2.500) = 34856 
    [ 2.500,  3.750) = 285576 
    [ 3.750,  5.000) = 6942 
    [ 5.000,  6.250) = 607 
    [ 6.250,  7.500) = 346 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.992 ms/op
     p(99.9900) =     16.446 ms/op
     p(99.9990) =     17.652 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.096 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  8.809 ms/op
                 getUser·p0.9999: 16.613 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.642 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  8.361 ms/op
                 getUser·p0.9999: 17.334 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314116
  mean =      3.056 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 565 
    [ 1.250,  2.500) = 19031 
    [ 2.500,  3.750) = 276229 
    [ 3.750,  5.000) = 15981 
    [ 5.000,  6.250) = 1242 
    [ 6.250,  7.500) = 604 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 68 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =      8.248 ms/op
     p(99.9900) =     16.790 ms/op
     p(99.9990) =     17.489 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 5.617 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
Iteration   1: 4.003 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 3.897 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  15.528 ms/op
                 listUser·p0.9999: 16.446 ms/op
                 listUser·p1.00:   16.728 ms/op

Iteration   3: 3.911 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  16.791 ms/op
                 listUser·p0.9999: 19.092 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243811
  mean =      3.936 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3938 
    [ 2.500,  5.000) = 214046 
    [ 5.000,  7.500) = 23999 
    [ 7.500, 10.000) = 1277 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     22.589 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.532 ± 2.491  ops/ms
ClientGrpc.existUser                       thrpt       3  11.154 ± 2.741  ops/ms
ClientGrpc.getUser                         thrpt       3  10.505 ± 1.215  ops/ms
ClientGrpc.listUser                        thrpt       3   8.138 ± 0.440  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.136   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 1.115   ms/op
ClientGrpc.getUser                          avgt       3   3.017 ± 0.370   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 1.094   ms/op
ClientGrpc.createUser                     sample  315980   3.038 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.677           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.748           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.804           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.629           ms/op
ClientGrpc.existUser                      sample  331194   2.897 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.762           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.314           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.992           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.446           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.416           ms/op
ClientGrpc.getUser                        sample  314116   3.056 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.578           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.248           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.790           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.596           ms/op
ClientGrpc.listUser                       sample  243811   3.936 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.075           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.811           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.382           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.741           ms/op
