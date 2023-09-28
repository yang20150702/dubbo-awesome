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
# Warmup Iteration   1: 4.439 ops/ms
# Warmup Iteration   2: 8.993 ops/ms
# Warmup Iteration   3: 9.797 ops/ms
Iteration   1: 10.536 ops/ms
Iteration   2: 10.202 ops/ms
Iteration   3: 10.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.370 ±(99.9%) 3.046 ops/ms [Average]
  (min, avg, max) = (10.202, 10.370, 10.536), stdev = 0.167
  CI (99.9%): [7.324, 13.416] (assumes normal distribution)


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
# Warmup Iteration   1: 7.595 ops/ms
# Warmup Iteration   2: 10.236 ops/ms
# Warmup Iteration   3: 10.836 ops/ms
Iteration   1: 10.775 ops/ms
Iteration   2: 10.854 ops/ms
Iteration   3: 10.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.744 ±(99.9%) 2.333 ops/ms [Average]
  (min, avg, max) = (10.604, 10.744, 10.854), stdev = 0.128
  CI (99.9%): [8.411, 13.078] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.938 ops/ms
# Warmup Iteration   2: 9.805 ops/ms
# Warmup Iteration   3: 10.095 ops/ms
Iteration   1: 10.342 ops/ms
Iteration   2: 10.235 ops/ms
Iteration   3: 10.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.257 ±(99.9%) 1.397 ops/ms [Average]
  (min, avg, max) = (10.194, 10.257, 10.342), stdev = 0.077
  CI (99.9%): [8.860, 11.654] (assumes normal distribution)


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
# Warmup Iteration   1: 5.805 ops/ms
# Warmup Iteration   2: 7.855 ops/ms
# Warmup Iteration   3: 8.382 ops/ms
Iteration   1: 8.482 ops/ms
Iteration   2: 8.344 ops/ms
Iteration   3: 8.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.483 ±(99.9%) 2.546 ops/ms [Average]
  (min, avg, max) = (8.344, 8.483, 8.623), stdev = 0.140
  CI (99.9%): [5.936, 11.029] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.002 ms/op
Iteration   1: 3.162 ±(99.9%) 0.004 ms/op
Iteration   2: 3.117 ±(99.9%) 0.002 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.119 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (3.080, 3.119, 3.162), stdev = 0.041
  CI (99.9%): [2.365, 3.874] (assumes normal distribution)


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.002 ms/op
Iteration   1: 3.001 ±(99.9%) 0.002 ms/op
Iteration   2: 3.016 ±(99.9%) 0.004 ms/op
Iteration   3: 3.057 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.024 ±(99.9%) 0.528 ms/op [Average]
  (min, avg, max) = (3.001, 3.024, 3.057), stdev = 0.029
  CI (99.9%): [2.497, 3.552] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.025 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.002 ms/op
Iteration   1: 3.118 ±(99.9%) 0.003 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 3.094 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.098 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (3.082, 3.098, 3.118), stdev = 0.018
  CI (99.9%): [2.765, 3.431] (assumes normal distribution)


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.017 ms/op
Iteration   1: 3.687 ±(99.9%) 0.038 ms/op
Iteration   2: 3.756 ±(99.9%) 0.047 ms/op
Iteration   3: 3.793 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.745 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (3.687, 3.745, 3.793), stdev = 0.054
  CI (99.9%): [2.766, 4.724] (assumes normal distribution)


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
# Warmup Iteration   1: 4.215 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.165 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  8.437 ms/op
                 createUser·p0.9999: 15.345 ms/op
                 createUser·p1.00:   15.778 ms/op

Iteration   2: 3.201 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.511 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  10.242 ms/op
                 createUser·p0.9999: 15.729 ms/op
                 createUser·p1.00:   16.237 ms/op

Iteration   3: 3.146 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.475 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  10.738 ms/op
                 createUser·p0.9999: 17.913 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302588
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 239 
    [ 1.250,  2.500) = 4648 
    [ 2.500,  3.750) = 267626 
    [ 3.750,  5.000) = 28626 
    [ 5.000,  6.250) = 716 
    [ 6.250,  7.500) = 243 
    [ 7.500,  8.750) = 115 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 106 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      9.847 ms/op
     p(99.9900) =     16.294 ms/op
     p(99.9990) =     18.219 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.887 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.734 ms/op
                 existUser·p0.9999: 15.820 ms/op
                 existUser·p1.00:   16.269 ms/op

Iteration   2: 2.953 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.121 ms/op
                 existUser·p0.9999: 16.406 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.642 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  7.830 ms/op
                 existUser·p0.9999: 17.602 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323615
  mean =      2.964 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1154 
    [ 1.250,  2.500) = 24914 
    [ 2.500,  3.750) = 286613 
    [ 3.750,  5.000) = 9439 
    [ 5.000,  6.250) = 1068 
    [ 6.250,  7.500) = 183 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 66 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      6.627 ms/op
     p(99.9900) =     17.290 ms/op
     p(99.9990) =     17.876 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.006 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.703 ms/op
                 getUser·p0.999:  9.210 ms/op
                 getUser·p0.9999: 11.690 ms/op
                 getUser·p1.00:   11.911 ms/op

Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  12.012 ms/op
                 getUser·p0.9999: 14.086 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 3.114 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.165 ms/op
                 getUser·p0.999:  8.398 ms/op
                 getUser·p0.9999: 15.265 ms/op
                 getUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310426
  mean =      3.092 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 802 
    [ 1.250,  2.500) = 11382 
    [ 2.500,  3.750) = 278222 
    [ 3.750,  5.000) = 18120 
    [ 5.000,  6.250) = 993 
    [ 6.250,  7.500) = 314 
    [ 7.500,  8.750) = 191 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     14.989 ms/op
     p(99.9990) =     15.591 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 5.137 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.008 ms/op
Iteration   1: 3.798 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  12.321 ms/op
                 listUser·p0.9999: 14.627 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   2: 3.841 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  12.858 ms/op
                 listUser·p0.9999: 16.150 ms/op
                 listUser·p1.00:   16.581 ms/op

Iteration   3: 3.801 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  14.135 ms/op
                 listUser·p0.9999: 15.565 ms/op
                 listUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251730
  mean =      3.813 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4084 
    [ 2.500,  5.000) = 234167 
    [ 5.000,  7.500) = 12612 
    [ 7.500, 10.000) = 331 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     12.702 ms/op
     p(99.9900) =     15.685 ms/op
     p(99.9990) =     19.976 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.370 ± 3.046  ops/ms
ClientGrpc.existUser                       thrpt       3  10.744 ± 2.333  ops/ms
ClientGrpc.getUser                         thrpt       3  10.257 ± 1.397  ops/ms
ClientGrpc.listUser                        thrpt       3   8.483 ± 2.546  ops/ms
ClientGrpc.createUser                       avgt       3   3.119 ± 0.754   ms/op
ClientGrpc.existUser                        avgt       3   3.024 ± 0.528   ms/op
ClientGrpc.getUser                          avgt       3   3.098 ± 0.333   ms/op
ClientGrpc.listUser                         avgt       3   3.745 ± 0.979   ms/op
ClientGrpc.createUser                     sample  302588   3.171 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.475           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.847           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.294           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.219           ms/op
ClientGrpc.existUser                      sample  323615   2.964 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.564           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.627           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.290           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  310426   3.092 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.731           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.798           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.989           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.712           ms/op
ClientGrpc.listUser                       sample  251730   3.813 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.145           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.227           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.447           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.702           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.685           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.775           ms/op
