# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.848 ops/ms
# Warmup Iteration   2: 8.700 ops/ms
# Warmup Iteration   3: 9.714 ops/ms
Iteration   1: 10.035 ops/ms
Iteration   2: 10.204 ops/ms
Iteration   3: 9.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.037 ±(99.9%) 3.047 ops/ms [Average]
  (min, avg, max) = (9.870, 10.037, 10.204), stdev = 0.167
  CI (99.9%): [6.989, 13.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.059 ops/ms
# Warmup Iteration   2: 10.397 ops/ms
# Warmup Iteration   3: 10.340 ops/ms
Iteration   1: 10.364 ops/ms
Iteration   2: 10.482 ops/ms
Iteration   3: 10.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.424 ±(99.9%) 1.077 ops/ms [Average]
  (min, avg, max) = (10.364, 10.424, 10.482), stdev = 0.059
  CI (99.9%): [9.346, 11.501] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.145 ops/ms
# Warmup Iteration   2: 9.791 ops/ms
# Warmup Iteration   3: 10.264 ops/ms
Iteration   1: 10.255 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.392 ±(99.9%) 2.192 ops/ms [Average]
  (min, avg, max) = (10.255, 10.392, 10.479), stdev = 0.120
  CI (99.9%): [8.200, 12.584] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.758 ops/ms
# Warmup Iteration   2: 7.517 ops/ms
# Warmup Iteration   3: 7.739 ops/ms
Iteration   1: 7.819 ops/ms
Iteration   2: 7.946 ops/ms
Iteration   3: 7.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.855 ±(99.9%) 1.452 ops/ms [Average]
  (min, avg, max) = (7.799, 7.855, 7.946), stdev = 0.080
  CI (99.9%): [6.403, 9.307] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.191 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.002 ms/op
Iteration   1: 3.111 ±(99.9%) 0.003 ms/op
Iteration   2: 3.188 ±(99.9%) 0.002 ms/op
Iteration   3: 3.194 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.164 ±(99.9%) 0.845 ms/op [Average]
  (min, avg, max) = (3.111, 3.164, 3.194), stdev = 0.046
  CI (99.9%): [2.319, 4.009] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.003 ms/op
Iteration   1: 2.951 ±(99.9%) 0.002 ms/op
Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
Iteration   3: 3.043 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.007 ±(99.9%) 0.899 ms/op [Average]
  (min, avg, max) = (2.951, 3.007, 3.043), stdev = 0.049
  CI (99.9%): [2.108, 3.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.781 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.002 ms/op
Iteration   1: 3.158 ±(99.9%) 0.003 ms/op
Iteration   2: 3.087 ±(99.9%) 0.003 ms/op
Iteration   3: 3.164 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.136 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (3.087, 3.136, 3.164), stdev = 0.043
  CI (99.9%): [2.358, 3.915] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.341 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.322 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.023 ms/op
Iteration   1: 4.081 ±(99.9%) 0.015 ms/op
Iteration   2: 3.984 ±(99.9%) 0.070 ms/op
Iteration   3: 4.155 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.073 ±(99.9%) 1.563 ms/op [Average]
  (min, avg, max) = (3.984, 4.073, 4.155), stdev = 0.086
  CI (99.9%): [2.510, 5.636] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.018 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
Iteration   1: 3.127 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.219 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  9.400 ms/op
                 createUser·p0.9999: 13.673 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 3.141 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  6.839 ms/op
                 createUser·p0.9999: 15.293 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.396 ms/op
                 createUser·p0.9999: 16.204 ms/op
                 createUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306043
  mean =      3.137 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1282 
    [ 1.250,  2.500) = 19205 
    [ 2.500,  3.750) = 254567 
    [ 3.750,  5.000) = 29758 
    [ 5.000,  6.250) = 553 
    [ 6.250,  7.500) = 339 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 129 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.219 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.814 ms/op
     p(99.9900) =     15.666 ms/op
     p(99.9990) =     17.646 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.007 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.128 ms/op
                 existUser·p0.9999: 12.082 ms/op
                 existUser·p1.00:   12.599 ms/op

Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.836 ms/op
                 existUser·p0.9999: 15.163 ms/op
                 existUser·p1.00:   15.581 ms/op

Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 15.731 ms/op
                 existUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319749
  mean =      3.002 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1310 
    [ 1.250,  2.500) = 36148 
    [ 2.500,  3.750) = 264043 
    [ 3.750,  5.000) = 17470 
    [ 5.000,  6.250) = 384 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.998 ms/op
     p(99.9900) =     14.993 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.142 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   4.063 ms/op
                 getUser·p0.999:  6.010 ms/op
                 getUser·p0.9999: 19.488 ms/op
                 getUser·p1.00:   20.054 ms/op

Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.496 ms/op
                 getUser·p0.9999: 12.403 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.289 ms/op
                 getUser·p0.9999: 23.186 ms/op
                 getUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315080
  mean =      3.048 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23254 
    [ 2.500,  5.000) = 290873 
    [ 5.000,  7.500) = 710 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     22.626 ms/op
     p(99.9990) =     23.485 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.320 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.011 ms/op
Iteration   1: 4.003 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  13.089 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 3.994 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  17.052 ms/op
                 listUser·p0.9999: 24.214 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   3: 4.177 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  13.524 ms/op
                 listUser·p0.9999: 20.601 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236788
  mean =      4.056 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4743 
    [ 2.500,  5.000) = 200309 
    [ 5.000,  7.500) = 30632 
    [ 7.500, 10.000) = 701 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     15.408 ms/op
     p(99.9900) =     22.991 ms/op
     p(99.9990) =     24.507 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.037 ± 3.047  ops/ms
ClientGrpc.existUser                       thrpt       3  10.424 ± 1.077  ops/ms
ClientGrpc.getUser                         thrpt       3  10.392 ± 2.192  ops/ms
ClientGrpc.listUser                        thrpt       3   7.855 ± 1.452  ops/ms
ClientGrpc.createUser                       avgt       3   3.164 ± 0.845   ms/op
ClientGrpc.existUser                        avgt       3   3.007 ± 0.899   ms/op
ClientGrpc.getUser                          avgt       3   3.136 ± 0.778   ms/op
ClientGrpc.listUser                         avgt       3   4.073 ± 1.563   ms/op
ClientGrpc.createUser                     sample  306043   3.137 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.219           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.814           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.666           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.826           ms/op
ClientGrpc.existUser                      sample  319749   3.002 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.602           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.998           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.993           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.876           ms/op
ClientGrpc.getUser                        sample  315080   3.048 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.568           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.881           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.626           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.658           ms/op
ClientGrpc.listUser                       sample  236788   4.056 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.771           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.408           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.991           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.609           ms/op
