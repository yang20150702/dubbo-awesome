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
# Warmup Iteration   1: 3.753 ops/ms
# Warmup Iteration   2: 8.548 ops/ms
# Warmup Iteration   3: 10.032 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.419 ops/ms
Iteration   3: 10.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.440 ±(99.9%) 0.602 ops/ms [Average]
  (min, avg, max) = (10.419, 10.440, 10.478), stdev = 0.033
  CI (99.9%): [9.838, 11.041] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.824 ops/ms
# Warmup Iteration   2: 10.191 ops/ms
# Warmup Iteration   3: 10.893 ops/ms
Iteration   1: 10.776 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.798 ±(99.9%) 1.981 ops/ms [Average]
  (min, avg, max) = (10.702, 10.798, 10.916), stdev = 0.109
  CI (99.9%): [8.817, 12.779] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.537 ops/ms
# Warmup Iteration   2: 9.834 ops/ms
# Warmup Iteration   3: 10.216 ops/ms
Iteration   1: 10.282 ops/ms
Iteration   2: 10.288 ops/ms
Iteration   3: 10.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.254 ±(99.9%) 0.964 ops/ms [Average]
  (min, avg, max) = (10.193, 10.254, 10.288), stdev = 0.053
  CI (99.9%): [9.290, 11.218] (assumes normal distribution)


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
# Warmup Iteration   1: 5.067 ops/ms
# Warmup Iteration   2: 7.510 ops/ms
# Warmup Iteration   3: 7.614 ops/ms
Iteration   1: 7.720 ops/ms
Iteration   2: 7.749 ops/ms
Iteration   3: 7.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.785 ±(99.9%) 1.624 ops/ms [Average]
  (min, avg, max) = (7.720, 7.785, 7.887), stdev = 0.089
  CI (99.9%): [6.161, 9.409] (assumes normal distribution)


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.002 ms/op
Iteration   1: 3.103 ±(99.9%) 0.004 ms/op
Iteration   2: 3.141 ±(99.9%) 0.003 ms/op
Iteration   3: 3.054 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.100 ±(99.9%) 0.795 ms/op [Average]
  (min, avg, max) = (3.054, 3.100, 3.141), stdev = 0.044
  CI (99.9%): [2.304, 3.895] (assumes normal distribution)


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
# Warmup Iteration   1: 4.098 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.003 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 2.961 ±(99.9%) 0.002 ms/op
Iteration   3: 3.017 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (2.943, 2.974, 3.017), stdev = 0.038
  CI (99.9%): [2.274, 3.673] (assumes normal distribution)


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
# Warmup Iteration   1: 4.355 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.002 ms/op
Iteration   1: 3.124 ±(99.9%) 0.002 ms/op
Iteration   2: 3.124 ±(99.9%) 0.003 ms/op
Iteration   3: 3.024 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (3.024, 3.091, 3.124), stdev = 0.058
  CI (99.9%): [2.039, 4.143] (assumes normal distribution)


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
# Warmup Iteration   1: 5.920 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.025 ms/op
Iteration   1: 4.079 ±(99.9%) 0.014 ms/op
Iteration   2: 4.097 ±(99.9%) 0.017 ms/op
Iteration   3: 3.967 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.048 ±(99.9%) 1.283 ms/op [Average]
  (min, avg, max) = (3.967, 4.048, 4.097), stdev = 0.070
  CI (99.9%): [2.765, 5.331] (assumes normal distribution)


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.105 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.168 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 13.648 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.866 ms/op
                 createUser·p0.999:  8.569 ms/op
                 createUser·p0.9999: 15.282 ms/op
                 createUser·p1.00:   15.532 ms/op

Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  9.559 ms/op
                 createUser·p0.9999: 17.486 ms/op
                 createUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310981
  mean =      3.086 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 338 
    [ 1.250,  2.500) = 16073 
    [ 2.500,  3.750) = 274238 
    [ 3.750,  5.000) = 17531 
    [ 5.000,  6.250) = 1526 
    [ 6.250,  7.500) = 562 
    [ 7.500,  8.750) = 294 
    [ 8.750, 10.000) = 184 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 83 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     16.187 ms/op
     p(99.9990) =     17.596 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.194 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  7.447 ms/op
                 existUser·p0.9999: 13.025 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   2: 2.951 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.684 ms/op
                 existUser·p0.9999: 14.500 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.256 ms/op
                 existUser·p0.999:  11.141 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320174
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28816 
    [ 2.500,  5.000) = 288632 
    [ 5.000,  7.500) = 2237 
    [ 7.500, 10.000) = 271 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      8.223 ms/op
     p(99.9900) =     20.427 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 4.175 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
Iteration   1: 3.144 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.432 ms/op
                 getUser·p0.999:  12.078 ms/op
                 getUser·p0.9999: 13.295 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.561 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.525 ms/op
                 getUser·p0.9999: 14.369 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  7.610 ms/op
                 getUser·p0.9999: 18.285 ms/op
                 getUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308752
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 519 
    [ 1.250,  2.500) = 16233 
    [ 2.500,  3.750) = 268213 
    [ 3.750,  5.000) = 20920 
    [ 5.000,  6.250) = 1776 
    [ 6.250,  7.500) = 619 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     17.895 ms/op
     p(99.9990) =     18.720 ms/op
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
# Warmup Iteration   1: 5.635 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.172 ±(99.9%) 0.013 ms/op
Iteration   1: 4.135 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  15.099 ms/op
                 listUser·p0.9999: 20.829 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   2: 4.150 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.718 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  19.857 ms/op
                 listUser·p0.9999: 26.429 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   3: 4.074 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  17.445 ms/op
                 listUser·p0.9999: 33.199 ms/op
                 listUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233192
  mean =      4.119 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1610 
    [ 2.500,  5.000) = 204338 
    [ 5.000,  7.500) = 25110 
    [ 7.500, 10.000) = 1598 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     32.561 ms/op
     p(99.9990) =     33.664 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.440 ± 0.602  ops/ms
ClientGrpc.existUser                       thrpt       3  10.798 ± 1.981  ops/ms
ClientGrpc.getUser                         thrpt       3  10.254 ± 0.964  ops/ms
ClientGrpc.listUser                        thrpt       3   7.785 ± 1.624  ops/ms
ClientGrpc.createUser                       avgt       3   3.100 ± 0.795   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 0.699   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 1.052   ms/op
ClientGrpc.listUser                         avgt       3   4.048 ± 1.283   ms/op
ClientGrpc.createUser                     sample  310981   3.086 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.746           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.907           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.470           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.187           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.695           ms/op
ClientGrpc.existUser                      sample  320174   2.998 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.711           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.841           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.223           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.427           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.462           ms/op
ClientGrpc.getUser                        sample  308752   3.110 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.561           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.932           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.176           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.895           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.202           ms/op
ClientGrpc.listUser                       sample  233192   4.119 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.718           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.138           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.561           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.751           ms/op
