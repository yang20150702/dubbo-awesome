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
# Warmup Iteration   1: 3.830 ops/ms
# Warmup Iteration   2: 8.817 ops/ms
# Warmup Iteration   3: 9.700 ops/ms
Iteration   1: 10.230 ops/ms
Iteration   2: 10.531 ops/ms
Iteration   3: 10.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.359 ±(99.9%) 2.821 ops/ms [Average]
  (min, avg, max) = (10.230, 10.359, 10.531), stdev = 0.155
  CI (99.9%): [7.539, 13.180] (assumes normal distribution)


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
# Warmup Iteration   1: 7.229 ops/ms
# Warmup Iteration   2: 10.483 ops/ms
# Warmup Iteration   3: 10.897 ops/ms
Iteration   1: 10.880 ops/ms
Iteration   2: 10.782 ops/ms
Iteration   3: 10.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.837 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (10.782, 10.837, 10.880), stdev = 0.050
  CI (99.9%): [9.923, 11.750] (assumes normal distribution)


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
# Warmup Iteration   1: 6.635 ops/ms
# Warmup Iteration   2: 9.969 ops/ms
# Warmup Iteration   3: 10.171 ops/ms
Iteration   1: 10.465 ops/ms
Iteration   2: 10.379 ops/ms
Iteration   3: 10.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.398 ±(99.9%) 1.105 ops/ms [Average]
  (min, avg, max) = (10.348, 10.398, 10.465), stdev = 0.061
  CI (99.9%): [9.293, 11.502] (assumes normal distribution)


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
# Warmup Iteration   1: 5.351 ops/ms
# Warmup Iteration   2: 7.236 ops/ms
# Warmup Iteration   3: 7.687 ops/ms
Iteration   1: 7.711 ops/ms
Iteration   2: 7.845 ops/ms
Iteration   3: 7.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.786 ±(99.9%) 1.240 ops/ms [Average]
  (min, avg, max) = (7.711, 7.786, 7.845), stdev = 0.068
  CI (99.9%): [6.546, 9.025] (assumes normal distribution)


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.004 ms/op
Iteration   1: 3.070 ±(99.9%) 0.002 ms/op
Iteration   2: 3.550 ±(99.9%) 0.004 ms/op
Iteration   3: 3.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.362 ±(99.9%) 4.676 ms/op [Average]
  (min, avg, max) = (3.070, 3.362, 3.550), stdev = 0.256
  CI (99.9%): [≈ 0, 8.038] (assumes normal distribution)


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.002 ms/op
Iteration   1: 3.117 ±(99.9%) 0.004 ms/op
Iteration   2: 3.004 ±(99.9%) 0.004 ms/op
Iteration   3: 3.140 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.087 ±(99.9%) 1.330 ms/op [Average]
  (min, avg, max) = (3.004, 3.087, 3.140), stdev = 0.073
  CI (99.9%): [1.758, 4.417] (assumes normal distribution)


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
# Warmup Iteration   1: 4.893 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.005 ms/op
Iteration   1: 3.332 ±(99.9%) 0.005 ms/op
Iteration   2: 3.306 ±(99.9%) 0.004 ms/op
Iteration   3: 3.269 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.302 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (3.269, 3.302, 3.332), stdev = 0.032
  CI (99.9%): [2.722, 3.883] (assumes normal distribution)


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
# Warmup Iteration   1: 6.323 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.235 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.020 ms/op
Iteration   1: 4.164 ±(99.9%) 0.028 ms/op
Iteration   2: 4.139 ±(99.9%) 0.013 ms/op
Iteration   3: 4.108 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.137 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (4.108, 4.137, 4.164), stdev = 0.028
  CI (99.9%): [3.631, 4.643] (assumes normal distribution)


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
# Warmup Iteration   1: 4.584 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
Iteration   1: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  11.030 ms/op
                 createUser·p0.9999: 17.637 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  9.140 ms/op
                 createUser·p0.9999: 19.726 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 19.848 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312776
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22800 
    [ 2.500,  5.000) = 287509 
    [ 5.000,  7.500) = 1746 
    [ 7.500, 10.000) = 382 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =     10.748 ms/op
     p(99.9900) =     19.595 ms/op
     p(99.9990) =     21.520 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 14.227 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.971 ms/op
                 existUser·p0.9999: 14.227 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  8.651 ms/op
                 existUser·p0.9999: 16.849 ms/op
                 existUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319817
  mean =      3.000 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 560 
    [ 1.250,  2.500) = 20179 
    [ 2.500,  3.750) = 284830 
    [ 3.750,  5.000) = 12670 
    [ 5.000,  6.250) = 509 
    [ 6.250,  7.500) = 464 
    [ 7.500,  8.750) = 329 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     16.466 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
Iteration   1: 3.167 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  8.019 ms/op
                 getUser·p0.9999: 13.136 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   2: 3.076 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  11.189 ms/op
                 getUser·p0.9999: 16.502 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   3: 3.077 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  8.685 ms/op
                 getUser·p0.9999: 17.663 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309193
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 665 
    [ 1.250,  2.500) = 16187 
    [ 2.500,  3.750) = 268422 
    [ 3.750,  5.000) = 21403 
    [ 5.000,  6.250) = 1546 
    [ 6.250,  7.500) = 486 
    [ 7.500,  8.750) = 186 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     16.404 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 5.756 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.012 ms/op
Iteration   1: 4.137 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  14.332 ms/op
                 listUser·p0.9999: 16.479 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   2: 4.121 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 24.158 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   3: 4.101 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  18.124 ms/op
                 listUser·p0.9999: 26.978 ms/op
                 listUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232880
  mean =      4.120 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2458 
    [ 2.500,  5.000) = 202290 
    [ 5.000,  7.500) = 25829 
    [ 7.500, 10.000) = 1720 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     15.452 ms/op
     p(99.9900) =     25.255 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.359 ± 2.821  ops/ms
ClientGrpc.existUser                       thrpt       3  10.837 ± 0.913  ops/ms
ClientGrpc.getUser                         thrpt       3  10.398 ± 1.105  ops/ms
ClientGrpc.listUser                        thrpt       3   7.786 ± 1.240  ops/ms
ClientGrpc.createUser                       avgt       3   3.362 ± 4.676   ms/op
ClientGrpc.existUser                        avgt       3   3.087 ± 1.330   ms/op
ClientGrpc.getUser                          avgt       3   3.302 ± 0.580   ms/op
ClientGrpc.listUser                         avgt       3   4.137 ± 0.506   ms/op
ClientGrpc.createUser                     sample  312776   3.068 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.559           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.748           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.595           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.348           ms/op
ClientGrpc.existUser                      sample  319817   3.000 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.815           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.471           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.466           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.695           ms/op
ClientGrpc.getUser                        sample  309193   3.106 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.855           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.618           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.404           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.957           ms/op
ClientGrpc.listUser                       sample  232880   4.120 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.928           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.087           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.487           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.452           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.255           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.475           ms/op
