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
# Warmup Iteration   1: 4.700 ops/ms
# Warmup Iteration   2: 9.457 ops/ms
# Warmup Iteration   3: 10.504 ops/ms
Iteration   1: 10.676 ops/ms
Iteration   2: 10.737 ops/ms
Iteration   3: 10.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.707 ±(99.9%) 0.562 ops/ms [Average]
  (min, avg, max) = (10.676, 10.707, 10.737), stdev = 0.031
  CI (99.9%): [10.146, 11.269] (assumes normal distribution)


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
# Warmup Iteration   1: 8.050 ops/ms
# Warmup Iteration   2: 10.831 ops/ms
# Warmup Iteration   3: 11.118 ops/ms
Iteration   1: 11.239 ops/ms
Iteration   2: 11.398 ops/ms
Iteration   3: 11.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.357 ±(99.9%) 1.901 ops/ms [Average]
  (min, avg, max) = (11.239, 11.357, 11.435), stdev = 0.104
  CI (99.9%): [9.456, 13.259] (assumes normal distribution)


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
# Warmup Iteration   1: 7.704 ops/ms
# Warmup Iteration   2: 10.700 ops/ms
# Warmup Iteration   3: 10.684 ops/ms
Iteration   1: 10.874 ops/ms
Iteration   2: 10.650 ops/ms
Iteration   3: 10.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.774 ±(99.9%) 2.073 ops/ms [Average]
  (min, avg, max) = (10.650, 10.774, 10.874), stdev = 0.114
  CI (99.9%): [8.701, 12.847] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.719 ops/ms
# Warmup Iteration   2: 7.874 ops/ms
# Warmup Iteration   3: 8.276 ops/ms
Iteration   1: 8.422 ops/ms
Iteration   2: 8.380 ops/ms
Iteration   3: 8.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.390 ±(99.9%) 0.515 ops/ms [Average]
  (min, avg, max) = (8.369, 8.390, 8.422), stdev = 0.028
  CI (99.9%): [7.875, 8.906] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.848 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.003 ms/op
Iteration   1: 2.948 ±(99.9%) 0.002 ms/op
Iteration   2: 2.961 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.966 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (2.948, 2.966, 2.988), stdev = 0.020
  CI (99.9%): [2.599, 3.332] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.907 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.004 ms/op
Iteration   1: 2.835 ±(99.9%) 0.005 ms/op
Iteration   2: 2.796 ±(99.9%) 0.004 ms/op
Iteration   3: 2.849 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.827 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (2.796, 2.827, 2.849), stdev = 0.028
  CI (99.9%): [2.320, 3.333] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.691 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.003 ms/op
Iteration   1: 3.006 ±(99.9%) 0.002 ms/op
Iteration   2: 2.950 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.973 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (2.950, 2.973, 3.006), stdev = 0.029
  CI (99.9%): [2.435, 3.511] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.027 ms/op
Iteration   1: 3.825 ±(99.9%) 0.007 ms/op
Iteration   2: 3.847 ±(99.9%) 0.034 ms/op
Iteration   3: 3.850 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.841 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (3.825, 3.841, 3.850), stdev = 0.014
  CI (99.9%): [3.589, 4.092] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  6.980 ms/op
                 createUser·p0.9999: 16.509 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.415 ms/op
                 createUser·p0.9999: 15.367 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.397 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  10.471 ms/op
                 createUser·p0.9999: 14.918 ms/op
                 createUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316936
  mean =      3.028 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1208 
    [ 1.250,  2.500) = 20750 
    [ 2.500,  3.750) = 275780 
    [ 3.750,  5.000) = 17668 
    [ 5.000,  6.250) = 768 
    [ 6.250,  7.500) = 343 
    [ 7.500,  8.750) = 135 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.979 ms/op
     p(99.9900) =     15.821 ms/op
     p(99.9990) =     16.744 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.935 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.006 ms/op
Iteration   1: 2.880 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  10.350 ms/op
                 existUser·p0.9999: 16.908 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   2: 2.819 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  5.906 ms/op
                 existUser·p0.9999: 12.932 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.891 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  7.281 ms/op
                 existUser·p0.9999: 25.068 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335469
  mean =      2.863 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43678 
    [ 2.500,  5.000) = 290999 
    [ 5.000,  7.500) = 448 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      7.783 ms/op
     p(99.9900) =     17.447 ms/op
     p(99.9990) =     25.218 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.108 ms/op
                 getUser·p0.9999: 11.702 ms/op
                 getUser·p1.00:   11.862 ms/op

Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.068 ms/op
                 getUser·p0.9999: 12.728 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.517 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.947 ms/op
                 getUser·p0.9999: 23.634 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322665
  mean =      2.974 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30558 
    [ 2.500,  5.000) = 290977 
    [ 5.000,  7.500) = 884 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.955 ms/op
     p(99.9900) =     20.314 ms/op
     p(99.9990) =     24.050 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.009 ms/op
Iteration   1: 3.856 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  12.240 ms/op
                 listUser·p0.9999: 14.890 ms/op
                 listUser·p1.00:   16.302 ms/op

Iteration   2: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.437 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  12.942 ms/op
                 listUser·p0.9999: 14.790 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   3: 3.883 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  13.542 ms/op
                 listUser·p0.9999: 18.622 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248381
  mean =      3.865 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 5990 
    [ 2.500,  3.750) = 123727 
    [ 3.750,  5.000) = 97578 
    [ 5.000,  6.250) = 16391 
    [ 6.250,  7.500) = 3686 
    [ 7.500,  8.750) = 450 
    [ 8.750, 10.000) = 137 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 149 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     12.937 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     19.517 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.707 ± 0.562  ops/ms
ClientGrpc.existUser                       thrpt       3  11.357 ± 1.901  ops/ms
ClientGrpc.getUser                         thrpt       3  10.774 ± 2.073  ops/ms
ClientGrpc.listUser                        thrpt       3   8.390 ± 0.515  ops/ms
ClientGrpc.createUser                       avgt       3   2.966 ± 0.367   ms/op
ClientGrpc.existUser                        avgt       3   2.827 ± 0.506   ms/op
ClientGrpc.getUser                          avgt       3   2.973 ± 0.538   ms/op
ClientGrpc.listUser                         avgt       3   3.841 ± 0.252   ms/op
ClientGrpc.createUser                     sample  316936   3.028 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.397           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.979           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.821           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.810           ms/op
ClientGrpc.existUser                      sample  335469   2.863 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.503           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.783           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.447           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.034           ms/op
ClientGrpc.getUser                        sample  322665   2.974 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.517           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.955           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.314           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.281           ms/op
ClientGrpc.listUser                       sample  248381   3.865 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.437           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.595           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.937           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.924           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.726           ms/op
