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
# Warmup Iteration   1: 3.663 ops/ms
# Warmup Iteration   2: 7.728 ops/ms
# Warmup Iteration   3: 8.621 ops/ms
Iteration   1: 9.213 ops/ms
Iteration   2: 9.721 ops/ms
Iteration   3: 9.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.620 ±(99.9%) 6.696 ops/ms [Average]
  (min, avg, max) = (9.213, 9.620, 9.926), stdev = 0.367
  CI (99.9%): [2.924, 16.316] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.800 ops/ms
# Warmup Iteration   2: 9.587 ops/ms
# Warmup Iteration   3: 9.680 ops/ms
Iteration   1: 9.926 ops/ms
Iteration   2: 9.980 ops/ms
Iteration   3: 10.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.989 ±(99.9%) 1.227 ops/ms [Average]
  (min, avg, max) = (9.926, 9.989, 10.060), stdev = 0.067
  CI (99.9%): [8.762, 11.215] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.410 ops/ms
# Warmup Iteration   2: 8.766 ops/ms
# Warmup Iteration   3: 9.320 ops/ms
Iteration   1: 9.617 ops/ms
Iteration   2: 9.626 ops/ms
Iteration   3: 9.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.610 ±(99.9%) 0.389 ops/ms [Average]
  (min, avg, max) = (9.586, 9.610, 9.626), stdev = 0.021
  CI (99.9%): [9.220, 9.999] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.306 ops/ms
# Warmup Iteration   2: 6.581 ops/ms
# Warmup Iteration   3: 7.265 ops/ms
Iteration   1: 7.332 ops/ms
Iteration   2: 7.176 ops/ms
Iteration   3: 7.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.186 ±(99.9%) 2.581 ops/ms [Average]
  (min, avg, max) = (7.050, 7.186, 7.332), stdev = 0.141
  CI (99.9%): [4.605, 9.767] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.971 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.004 ms/op
Iteration   1: 3.349 ±(99.9%) 0.003 ms/op
Iteration   2: 3.274 ±(99.9%) 0.002 ms/op
Iteration   3: 3.291 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.305 ±(99.9%) 0.711 ms/op [Average]
  (min, avg, max) = (3.274, 3.305, 3.349), stdev = 0.039
  CI (99.9%): [2.593, 4.016] (assumes normal distribution)


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
# Warmup Iteration   1: 4.378 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.002 ms/op
Iteration   1: 3.196 ±(99.9%) 0.003 ms/op
Iteration   2: 3.232 ±(99.9%) 0.002 ms/op
Iteration   3: 3.192 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.207 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (3.192, 3.207, 3.232), stdev = 0.022
  CI (99.9%): [2.806, 3.607] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.861 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.002 ms/op
Iteration   1: 3.286 ±(99.9%) 0.003 ms/op
Iteration   2: 3.294 ±(99.9%) 0.003 ms/op
Iteration   3: 3.346 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.309 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (3.286, 3.309, 3.346), stdev = 0.033
  CI (99.9%): [2.715, 3.903] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.152 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.604 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.478 ±(99.9%) 0.017 ms/op
Iteration   1: 4.305 ±(99.9%) 0.018 ms/op
Iteration   2: 4.406 ±(99.9%) 0.016 ms/op
Iteration   3: 4.252 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.321 ±(99.9%) 1.422 ms/op [Average]
  (min, avg, max) = (4.252, 4.321, 4.406), stdev = 0.078
  CI (99.9%): [2.899, 5.743] (assumes normal distribution)


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
# Warmup Iteration   1: 4.768 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.010 ms/op
Iteration   1: 3.305 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  7.717 ms/op
                 createUser·p0.9999: 18.305 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   2: 3.373 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  11.239 ms/op
                 createUser·p0.9999: 29.574 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   3: 3.309 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  7.463 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 288341
  mean =      3.329 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14519 
    [ 2.500,  5.000) = 269806 
    [ 5.000,  7.500) = 3532 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =      9.049 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     30.118 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.243 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.008 ms/op
Iteration   1: 3.213 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  8.733 ms/op
                 existUser·p0.9999: 23.431 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.221 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  8.977 ms/op
                 existUser·p0.9999: 31.787 ms/op
                 existUser·p1.00:   32.080 ms/op

Iteration   3: 3.229 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 19.762 ms/op
                 existUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 297877
  mean =      3.221 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19769 
    [ 2.500,  5.000) = 274530 
    [ 5.000,  7.500) = 3048 
    [ 7.500, 10.000) = 331 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     30.160 ms/op
     p(99.9990) =     32.015 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 4.596 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.009 ms/op
Iteration   1: 3.383 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.467 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 14.527 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   2: 3.386 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.136 ms/op
                 getUser·p0.999:  7.661 ms/op
                 getUser·p0.9999: 18.729 ms/op
                 getUser·p1.00:   19.005 ms/op

Iteration   3: 3.330 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.510 ms/op
                 getUser·p0.999:  10.010 ms/op
                 getUser·p0.9999: 18.605 ms/op
                 getUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 285011
  mean =      3.366 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 380 
    [ 1.250,  2.500) = 13239 
    [ 2.500,  3.750) = 215147 
    [ 3.750,  5.000) = 52246 
    [ 5.000,  6.250) = 2868 
    [ 6.250,  7.500) = 654 
    [ 7.500,  8.750) = 135 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 54 
    [17.500, 18.750) = 62 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     19.048 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 5.884 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.671 ±(99.9%) 0.015 ms/op
Iteration   1: 4.424 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.250 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 19.424 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 4.586 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   7.968 ms/op
                 listUser·p0.999:  15.548 ms/op
                 listUser·p0.9999: 19.565 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 4.531 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  19.019 ms/op
                 listUser·p0.9999: 24.245 ms/op
                 listUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 212596
  mean =      4.512 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 896 
    [ 2.500,  5.000) = 172438 
    [ 5.000,  7.500) = 35219 
    [ 7.500, 10.000) = 3329 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     22.831 ms/op
     p(99.9990) =     24.723 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.620 ± 6.696  ops/ms
ClientGrpc.existUser                       thrpt       3   9.989 ± 1.227  ops/ms
ClientGrpc.getUser                         thrpt       3   9.610 ± 0.389  ops/ms
ClientGrpc.listUser                        thrpt       3   7.186 ± 2.581  ops/ms
ClientGrpc.createUser                       avgt       3   3.305 ± 0.711   ms/op
ClientGrpc.existUser                        avgt       3   3.207 ± 0.400   ms/op
ClientGrpc.getUser                          avgt       3   3.309 ± 0.594   ms/op
ClientGrpc.listUser                         avgt       3   4.321 ± 1.422   ms/op
ClientGrpc.createUser                     sample  288341   3.329 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.730           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.289           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.259           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.049           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.869           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.179           ms/op
ClientGrpc.existUser                      sample  297877   3.221 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.694           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.178           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.169           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.749           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.160           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.080           ms/op
ClientGrpc.getUser                        sample  285011   3.366 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.467           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.318           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.022           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.454           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.547           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.202           ms/op
ClientGrpc.listUser                       sample  212596   4.512 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.911           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.334           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.398           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.351           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.831           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.805           ms/op
