# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.870 ops/ms
# Warmup Iteration   2: 4.874 ops/ms
# Warmup Iteration   3: 8.433 ops/ms
Iteration   1: 8.670 ops/ms
Iteration   2: 9.165 ops/ms
Iteration   3: 9.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.008 ±(99.9%) 5.354 ops/ms [Average]
  (min, avg, max) = (8.670, 9.008, 9.190), stdev = 0.293
  CI (99.9%): [3.654, 14.362] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.825 ops/ms
# Warmup Iteration   2: 8.445 ops/ms
# Warmup Iteration   3: 9.478 ops/ms
Iteration   1: 9.502 ops/ms
Iteration   2: 9.461 ops/ms
Iteration   3: 9.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.549 ±(99.9%) 2.161 ops/ms [Average]
  (min, avg, max) = (9.461, 9.549, 9.684), stdev = 0.118
  CI (99.9%): [7.388, 11.710] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 8.005 ops/ms
# Warmup Iteration   3: 9.062 ops/ms
Iteration   1: 9.206 ops/ms
Iteration   2: 9.122 ops/ms
Iteration   3: 9.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.174 ±(99.9%) 0.825 ops/ms [Average]
  (min, avg, max) = (9.122, 9.174, 9.206), stdev = 0.045
  CI (99.9%): [8.349, 9.998] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.970 ops/ms
# Warmup Iteration   2: 7.037 ops/ms
# Warmup Iteration   3: 7.552 ops/ms
Iteration   1: 7.506 ops/ms
Iteration   2: 7.560 ops/ms
Iteration   3: 7.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.508 ±(99.9%) 0.911 ops/ms [Average]
  (min, avg, max) = (7.460, 7.508, 7.560), stdev = 0.050
  CI (99.9%): [6.597, 8.420] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.363 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.003 ms/op
Iteration   1: 3.542 ±(99.9%) 0.003 ms/op
Iteration   2: 3.563 ±(99.9%) 0.005 ms/op
Iteration   3: 3.553 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.553 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.542, 3.553, 3.563), stdev = 0.010
  CI (99.9%): [3.364, 3.742] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.293 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.004 ms/op
Iteration   1: 3.466 ±(99.9%) 0.004 ms/op
Iteration   2: 3.390 ±(99.9%) 0.005 ms/op
Iteration   3: 3.438 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.431 ±(99.9%) 0.704 ms/op [Average]
  (min, avg, max) = (3.390, 3.431, 3.466), stdev = 0.039
  CI (99.9%): [2.727, 4.135] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.797 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.006 ms/op
Iteration   1: 3.663 ±(99.9%) 0.006 ms/op
Iteration   2: 3.538 ±(99.9%) 0.004 ms/op
Iteration   3: 3.506 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.569 ±(99.9%) 1.515 ms/op [Average]
  (min, avg, max) = (3.506, 3.569, 3.663), stdev = 0.083
  CI (99.9%): [2.054, 5.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.654 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.008 ms/op
Iteration   1: 4.241 ±(99.9%) 0.005 ms/op
Iteration   2: 4.138 ±(99.9%) 0.007 ms/op
Iteration   3: 4.119 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.166 ±(99.9%) 1.191 ms/op [Average]
  (min, avg, max) = (4.119, 4.166, 4.241), stdev = 0.065
  CI (99.9%): [2.975, 5.357] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.414 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.014 ms/op
Iteration   1: 3.540 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.806 ms/op
                 createUser·p0.999:  22.217 ms/op
                 createUser·p0.9999: 24.150 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   2: 3.541 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  24.010 ms/op
                 createUser·p0.9999: 26.378 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   3: 3.523 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   7.373 ms/op
                 createUser·p0.999:  18.973 ms/op
                 createUser·p0.9999: 28.453 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271346
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4751 
    [ 2.500,  5.000) = 258520 
    [ 5.000,  7.500) = 6316 
    [ 7.500, 10.000) = 1045 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 127 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     21.845 ms/op
     p(99.9900) =     27.259 ms/op
     p(99.9990) =     29.075 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.154 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
Iteration   1: 3.324 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   6.215 ms/op
                 existUser·p0.999:  18.179 ms/op
                 existUser·p0.9999: 24.293 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   2: 3.480 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.378 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   7.619 ms/op
                 existUser·p0.999:  18.780 ms/op
                 existUser·p0.9999: 20.467 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   3: 3.431 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  18.139 ms/op
                 existUser·p0.9999: 24.926 ms/op
                 existUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281418
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7936 
    [ 2.500,  5.000) = 265427 
    [ 5.000,  7.500) = 6056 
    [ 7.500, 10.000) = 1315 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 216 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     23.813 ms/op
     p(99.9990) =     25.500 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.513 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.012 ms/op
Iteration   1: 3.613 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   7.946 ms/op
                 getUser·p0.999:  18.491 ms/op
                 getUser·p0.9999: 24.280 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   2: 3.518 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  22.970 ms/op
                 getUser·p0.9999: 27.918 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   3: 3.531 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  20.316 ms/op
                 getUser·p0.9999: 27.849 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270228
  mean =      3.554 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4793 
    [ 2.500,  5.000) = 256216 
    [ 5.000,  7.500) = 6527 
    [ 7.500, 10.000) = 1781 
    [10.000, 12.500) = 424 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     20.049 ms/op
     p(99.9900) =     27.456 ms/op
     p(99.9990) =     28.364 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.295 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.572 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.013 ms/op
Iteration   1: 4.222 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.990 ms/op
                 listUser·p0.99:   8.530 ms/op
                 listUser·p0.999:  21.529 ms/op
                 listUser·p0.9999: 24.655 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 4.138 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 17.965 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 4.093 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.928 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231337
  mean =      4.150 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 218888 
    [ 5.000,  7.500) = 8645 
    [ 7.500, 10.000) = 2750 
    [10.000, 12.500) = 352 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 261 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      8.298 ms/op
     p(99.9000) =     16.215 ms/op
     p(99.9900) =     22.900 ms/op
     p(99.9990) =     26.718 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.008 ± 5.354  ops/ms
ClientPb.existUser                       thrpt       3   9.549 ± 2.161  ops/ms
ClientPb.getUser                         thrpt       3   9.174 ± 0.825  ops/ms
ClientPb.listUser                        thrpt       3   7.508 ± 0.911  ops/ms
ClientPb.createUser                       avgt       3   3.553 ± 0.189   ms/op
ClientPb.existUser                        avgt       3   3.431 ± 0.704   ms/op
ClientPb.getUser                          avgt       3   3.569 ± 1.515   ms/op
ClientPb.listUser                         avgt       3   4.166 ± 1.191   ms/op
ClientPb.createUser                     sample  271346   3.535 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.309           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.963           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.845           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.259           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.131           ms/op
ClientPb.existUser                      sample  281418   3.410 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.290           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.266           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.383           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.813           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.756           ms/op
ClientPb.getUser                        sample  270228   3.554 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.629           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.496           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.049           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.456           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.443           ms/op
ClientPb.listUser                       sample  231337   4.150 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.626           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.095           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.298           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.215           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.900           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475           ms/op
