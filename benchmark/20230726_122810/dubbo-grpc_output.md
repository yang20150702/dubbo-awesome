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
# Warmup Iteration   1: 4.658 ops/ms
# Warmup Iteration   2: 9.692 ops/ms
# Warmup Iteration   3: 10.295 ops/ms
Iteration   1: 10.334 ops/ms
Iteration   2: 10.759 ops/ms
Iteration   3: 10.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.555 ±(99.9%) 3.885 ops/ms [Average]
  (min, avg, max) = (10.334, 10.555, 10.759), stdev = 0.213
  CI (99.9%): [6.670, 14.440] (assumes normal distribution)


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
# Warmup Iteration   1: 7.823 ops/ms
# Warmup Iteration   2: 10.620 ops/ms
# Warmup Iteration   3: 10.891 ops/ms
Iteration   1: 11.090 ops/ms
Iteration   2: 11.084 ops/ms
Iteration   3: 11.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.081 ±(99.9%) 0.208 ops/ms [Average]
  (min, avg, max) = (11.068, 11.081, 11.090), stdev = 0.011
  CI (99.9%): [10.873, 11.289] (assumes normal distribution)


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
# Warmup Iteration   1: 7.612 ops/ms
# Warmup Iteration   2: 10.127 ops/ms
# Warmup Iteration   3: 10.404 ops/ms
Iteration   1: 10.401 ops/ms
Iteration   2: 10.465 ops/ms
Iteration   3: 10.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.455 ±(99.9%) 0.902 ops/ms [Average]
  (min, avg, max) = (10.401, 10.455, 10.499), stdev = 0.049
  CI (99.9%): [9.553, 11.357] (assumes normal distribution)


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
# Warmup Iteration   1: 6.350 ops/ms
# Warmup Iteration   2: 8.170 ops/ms
# Warmup Iteration   3: 8.363 ops/ms
Iteration   1: 8.283 ops/ms
Iteration   2: 8.419 ops/ms
Iteration   3: 8.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.357 ±(99.9%) 1.258 ops/ms [Average]
  (min, avg, max) = (8.283, 8.357, 8.419), stdev = 0.069
  CI (99.9%): [7.099, 9.615] (assumes normal distribution)


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.003 ms/op
Iteration   1: 3.004 ±(99.9%) 0.002 ms/op
Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
Iteration   3: 3.005 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.011 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (3.004, 3.011, 3.025), stdev = 0.012
  CI (99.9%): [2.795, 3.226] (assumes normal distribution)


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
# Warmup Iteration   1: 3.309 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.846 ±(99.9%) 0.004 ms/op
Iteration   1: 2.866 ±(99.9%) 0.002 ms/op
Iteration   2: 2.919 ±(99.9%) 0.003 ms/op
Iteration   3: 2.886 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (2.866, 2.891, 2.919), stdev = 0.026
  CI (99.9%): [2.408, 3.373] (assumes normal distribution)


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 3.053 ±(99.9%) 0.002 ms/op
Iteration   3: 2.980 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.020 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (2.980, 3.020, 3.053), stdev = 0.037
  CI (99.9%): [2.342, 3.697] (assumes normal distribution)


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.053 ms/op
Iteration   1: 3.887 ±(99.9%) 0.012 ms/op
Iteration   2: 3.865 ±(99.9%) 0.017 ms/op
Iteration   3: 3.782 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.845 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.782, 3.845, 3.887), stdev = 0.055
  CI (99.9%): [2.834, 4.855] (assumes normal distribution)


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  6.794 ms/op
                 createUser·p0.9999: 17.681 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  10.434 ms/op
                 createUser·p0.9999: 13.091 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   3: 3.072 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.682 ms/op
                 createUser·p0.9999: 28.017 ms/op
                 createUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317728
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24589 
    [ 2.500,  5.000) = 291527 
    [ 5.000,  7.500) = 1264 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.377 ms/op
     p(99.9900) =     26.761 ms/op
     p(99.9990) =     29.185 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.771 ±(99.9%) 0.007 ms/op
Iteration   1: 2.861 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.138 ms/op
                 existUser·p0.999:  6.203 ms/op
                 existUser·p0.9999: 18.246 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   2: 2.903 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  8.181 ms/op
                 existUser·p0.9999: 19.005 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   3: 2.897 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.307 ms/op
                 existUser·p0.9999: 14.236 ms/op
                 existUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332310
  mean =      2.887 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2699 
    [ 1.250,  2.500) = 37884 
    [ 2.500,  3.750) = 281833 
    [ 3.750,  5.000) = 8798 
    [ 5.000,  6.250) = 536 
    [ 6.250,  7.500) = 231 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.455 ms/op
     p(99.9900) =     18.244 ms/op
     p(99.9990) =     19.323 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  7.281 ms/op
                 getUser·p0.9999: 12.761 ms/op
                 getUser·p1.00:   13.337 ms/op

Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  7.848 ms/op
                 getUser·p0.9999: 13.844 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   3: 3.050 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  6.636 ms/op
                 getUser·p0.9999: 15.802 ms/op
                 getUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314261
  mean =      3.055 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 846 
    [ 1.250,  2.500) = 12959 
    [ 2.500,  3.750) = 286554 
    [ 3.750,  5.000) = 12764 
    [ 5.000,  6.250) = 621 
    [ 6.250,  7.500) = 222 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.338 ms/op
     p(99.9900) =     14.919 ms/op
     p(99.9990) =     16.115 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


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
# Warmup Iteration   1: 5.401 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.011 ms/op
Iteration   1: 3.849 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.403 ms/op
                 listUser·p0.9999: 15.699 ms/op
                 listUser·p1.00:   16.335 ms/op

Iteration   2: 3.824 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.043 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.948 ms/op
                 listUser·p0.9999: 22.160 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   3: 3.892 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.688 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  14.988 ms/op
                 listUser·p0.9999: 22.410 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248862
  mean =      3.855 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4563 
    [ 2.500,  5.000) = 223848 
    [ 5.000,  7.500) = 19348 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     23.102 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.555 ± 3.885  ops/ms
ClientGrpc.existUser                       thrpt       3  11.081 ± 0.208  ops/ms
ClientGrpc.getUser                         thrpt       3  10.455 ± 0.902  ops/ms
ClientGrpc.listUser                        thrpt       3   8.357 ± 1.258  ops/ms
ClientGrpc.createUser                       avgt       3   3.011 ± 0.216   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 0.482   ms/op
ClientGrpc.getUser                          avgt       3   3.020 ± 0.678   ms/op
ClientGrpc.listUser                         avgt       3   3.845 ± 1.010   ms/op
ClientGrpc.createUser                     sample  317728   3.020 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.656           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.377           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.761           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.229           ms/op
ClientGrpc.existUser                      sample  332310   2.887 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.524           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.455           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.244           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  314261   3.055 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.616           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.338           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.919           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.220           ms/op
ClientGrpc.listUser                       sample  248862   3.855 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.688           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.107           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.692           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.560           ms/op
