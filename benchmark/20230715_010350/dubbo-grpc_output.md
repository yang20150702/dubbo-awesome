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
# Warmup Iteration   1: 3.863 ops/ms
# Warmup Iteration   2: 8.619 ops/ms
# Warmup Iteration   3: 9.985 ops/ms
Iteration   1: 10.303 ops/ms
Iteration   2: 10.517 ops/ms
Iteration   3: 10.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.400 ±(99.9%) 1.979 ops/ms [Average]
  (min, avg, max) = (10.303, 10.400, 10.517), stdev = 0.108
  CI (99.9%): [8.421, 12.379] (assumes normal distribution)


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
# Warmup Iteration   1: 7.223 ops/ms
# Warmup Iteration   2: 10.283 ops/ms
# Warmup Iteration   3: 10.649 ops/ms
Iteration   1: 10.608 ops/ms
Iteration   2: 10.641 ops/ms
Iteration   3: 10.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.621 ±(99.9%) 0.316 ops/ms [Average]
  (min, avg, max) = (10.608, 10.621, 10.641), stdev = 0.017
  CI (99.9%): [10.305, 10.937] (assumes normal distribution)


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
# Warmup Iteration   1: 6.253 ops/ms
# Warmup Iteration   2: 9.821 ops/ms
# Warmup Iteration   3: 10.364 ops/ms
Iteration   1: 10.546 ops/ms
Iteration   2: 10.386 ops/ms
Iteration   3: 10.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.429 ±(99.9%) 1.879 ops/ms [Average]
  (min, avg, max) = (10.354, 10.429, 10.546), stdev = 0.103
  CI (99.9%): [8.550, 12.308] (assumes normal distribution)


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
# Warmup Iteration   1: 5.035 ops/ms
# Warmup Iteration   2: 7.545 ops/ms
# Warmup Iteration   3: 8.063 ops/ms
Iteration   1: 7.991 ops/ms
Iteration   2: 7.881 ops/ms
Iteration   3: 8.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.010 ±(99.9%) 2.558 ops/ms [Average]
  (min, avg, max) = (7.881, 8.010, 8.159), stdev = 0.140
  CI (99.9%): [5.453, 10.568] (assumes normal distribution)


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
# Warmup Iteration   1: 4.536 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.002 ms/op
Iteration   1: 3.143 ±(99.9%) 0.004 ms/op
Iteration   2: 3.097 ±(99.9%) 0.002 ms/op
Iteration   3: 3.083 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.108 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.083, 3.108, 3.143), stdev = 0.032
  CI (99.9%): [2.530, 3.686] (assumes normal distribution)


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.002 ms/op
Iteration   1: 2.946 ±(99.9%) 0.002 ms/op
Iteration   2: 2.904 ±(99.9%) 0.002 ms/op
Iteration   3: 2.890 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.913 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (2.890, 2.913, 2.946), stdev = 0.029
  CI (99.9%): [2.382, 3.445] (assumes normal distribution)


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
# Warmup Iteration   1: 4.314 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.003 ms/op
Iteration   1: 3.125 ±(99.9%) 0.004 ms/op
Iteration   2: 3.058 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.081 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.058, 3.081, 3.125), stdev = 0.038
  CI (99.9%): [2.382, 3.779] (assumes normal distribution)


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
# Warmup Iteration   1: 5.466 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.019 ms/op
Iteration   1: 4.101 ±(99.9%) 0.013 ms/op
Iteration   2: 4.031 ±(99.9%) 0.009 ms/op
Iteration   3: 3.995 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.042 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.995, 4.042, 4.101), stdev = 0.054
  CI (99.9%): [3.058, 5.026] (assumes normal distribution)


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
# Warmup Iteration   1: 4.500 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 3.046 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  7.857 ms/op
                 createUser·p0.9999: 14.000 ms/op
                 createUser·p1.00:   14.483 ms/op

Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.602 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.477 ms/op
                 createUser·p0.9999: 13.886 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  6.881 ms/op
                 createUser·p0.9999: 17.117 ms/op
                 createUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314720
  mean =      3.048 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 546 
    [ 1.250,  2.500) = 17728 
    [ 2.500,  3.750) = 280962 
    [ 3.750,  5.000) = 14132 
    [ 5.000,  6.250) = 731 
    [ 6.250,  7.500) = 284 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.713 ms/op
     p(99.9900) =     16.343 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.545 ms/op
                 existUser·p0.9999: 18.448 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  6.063 ms/op
                 existUser·p0.9999: 14.305 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   3: 2.924 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.293 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  6.078 ms/op
                 existUser·p0.9999: 17.172 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327429
  mean =      2.931 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22375 
    [ 2.500,  5.000) = 304274 
    [ 5.000,  7.500) = 604 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      6.206 ms/op
     p(99.9900) =     17.558 ms/op
     p(99.9990) =     20.298 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.007 ms/op
Iteration   1: 3.108 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  7.377 ms/op
                 getUser·p0.9999: 12.016 ms/op
                 getUser·p1.00:   12.206 ms/op

Iteration   2: 3.142 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.488 ms/op
                 getUser·p0.9999: 18.868 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 3.139 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.528 ms/op
                 getUser·p0.9999: 19.431 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306713
  mean =      3.129 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 506 
    [ 1.250,  2.500) = 11142 
    [ 2.500,  3.750) = 271847 
    [ 3.750,  5.000) = 21419 
    [ 5.000,  6.250) = 1284 
    [ 6.250,  7.500) = 246 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      7.315 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 5.090 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.012 ms/op
Iteration   1: 3.944 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.059 ms/op
                 listUser·p0.999:  18.287 ms/op
                 listUser·p0.9999: 25.719 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   2: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.741 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 21.530 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   3: 4.004 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  16.207 ms/op
                 listUser·p0.9999: 30.968 ms/op
                 listUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240777
  mean =      3.987 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2804 
    [ 2.500,  5.000) = 214940 
    [ 5.000,  7.500) = 21528 
    [ 7.500, 10.000) = 1087 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.006 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     30.310 ms/op
     p(99.9990) =     31.718 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.400 ± 1.979  ops/ms
ClientGrpc.existUser                       thrpt       3  10.621 ± 0.316  ops/ms
ClientGrpc.getUser                         thrpt       3  10.429 ± 1.879  ops/ms
ClientGrpc.listUser                        thrpt       3   8.010 ± 2.558  ops/ms
ClientGrpc.createUser                       avgt       3   3.108 ± 0.578   ms/op
ClientGrpc.existUser                        avgt       3   2.913 ± 0.531   ms/op
ClientGrpc.getUser                          avgt       3   3.081 ± 0.699   ms/op
ClientGrpc.listUser                         avgt       3   4.042 ± 0.984   ms/op
ClientGrpc.createUser                     sample  314720   3.048 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.602           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.713           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.343           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.695           ms/op
ClientGrpc.existUser                      sample  327429   2.931 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.804           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.206           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.558           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.382           ms/op
ClientGrpc.getUser                        sample  306713   3.129 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.815           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.315           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.907           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.497           ms/op
ClientGrpc.listUser                       sample  240777   3.987 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.741           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.006           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.138           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.310           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.949           ms/op
