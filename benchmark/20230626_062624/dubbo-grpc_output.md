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
# Warmup Iteration   1: 4.620 ops/ms
# Warmup Iteration   2: 9.613 ops/ms
# Warmup Iteration   3: 10.618 ops/ms
Iteration   1: 10.469 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.616 ±(99.9%) 2.919 ops/ms [Average]
  (min, avg, max) = (10.469, 10.616, 10.787), stdev = 0.160
  CI (99.9%): [7.697, 13.534] (assumes normal distribution)


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
# Warmup Iteration   1: 7.876 ops/ms
# Warmup Iteration   2: 11.107 ops/ms
# Warmup Iteration   3: 11.169 ops/ms
Iteration   1: 11.123 ops/ms
Iteration   2: 10.944 ops/ms
Iteration   3: 11.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.147 ±(99.9%) 3.929 ops/ms [Average]
  (min, avg, max) = (10.944, 11.147, 11.373), stdev = 0.215
  CI (99.9%): [7.217, 15.076] (assumes normal distribution)


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
# Warmup Iteration   1: 7.618 ops/ms
# Warmup Iteration   2: 10.282 ops/ms
# Warmup Iteration   3: 10.520 ops/ms
Iteration   1: 10.621 ops/ms
Iteration   2: 10.396 ops/ms
Iteration   3: 10.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.522 ±(99.9%) 2.096 ops/ms [Average]
  (min, avg, max) = (10.396, 10.522, 10.621), stdev = 0.115
  CI (99.9%): [8.426, 12.618] (assumes normal distribution)


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
# Warmup Iteration   1: 6.181 ops/ms
# Warmup Iteration   2: 8.004 ops/ms
# Warmup Iteration   3: 8.211 ops/ms
Iteration   1: 8.183 ops/ms
Iteration   2: 8.263 ops/ms
Iteration   3: 8.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.212 ±(99.9%) 0.812 ops/ms [Average]
  (min, avg, max) = (8.183, 8.212, 8.263), stdev = 0.045
  CI (99.9%): [7.400, 9.024] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.025 ±(99.9%) 0.003 ms/op
Iteration   2: 2.993 ±(99.9%) 0.002 ms/op
Iteration   3: 3.013 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.010 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (2.993, 3.010, 3.025), stdev = 0.016
  CI (99.9%): [2.713, 3.308] (assumes normal distribution)


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.003 ms/op
Iteration   1: 2.887 ±(99.9%) 0.003 ms/op
Iteration   2: 2.831 ±(99.9%) 0.003 ms/op
Iteration   3: 2.886 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.868 ±(99.9%) 0.583 ms/op [Average]
  (min, avg, max) = (2.831, 2.868, 2.887), stdev = 0.032
  CI (99.9%): [2.285, 3.450] (assumes normal distribution)


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.003 ms/op
Iteration   1: 2.974 ±(99.9%) 0.003 ms/op
Iteration   2: 3.034 ±(99.9%) 0.003 ms/op
Iteration   3: 2.963 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.990 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (2.963, 2.990, 3.034), stdev = 0.038
  CI (99.9%): [2.290, 3.691] (assumes normal distribution)


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
# Warmup Iteration   1: 5.432 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.019 ms/op
Iteration   1: 3.870 ±(99.9%) 0.022 ms/op
Iteration   2: 3.891 ±(99.9%) 0.013 ms/op
Iteration   3: 3.881 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.881 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (3.870, 3.881, 3.891), stdev = 0.010
  CI (99.9%): [3.693, 4.069] (assumes normal distribution)


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.796 ms/op
                 createUser·p0.9999: 17.539 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.423 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.580 ms/op
                 createUser·p0.9999: 13.877 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.866 ms/op
                 createUser·p0.9999: 15.292 ms/op
                 createUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320670
  mean =      2.996 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1432 
    [ 1.250,  2.500) = 22655 
    [ 2.500,  3.750) = 283462 
    [ 3.750,  5.000) = 11901 
    [ 5.000,  6.250) = 705 
    [ 6.250,  7.500) = 170 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 118 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.941 ms/op
     p(99.9900) =     16.471 ms/op
     p(99.9990) =     17.852 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.006 ms/op
Iteration   1: 2.882 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.464 ms/op
                 existUser·p0.9999: 25.258 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   2: 2.845 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.278 ms/op
                 existUser·p0.9999: 25.059 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 2.857 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  10.650 ms/op
                 existUser·p0.9999: 29.976 ms/op
                 existUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335461
  mean =      2.861 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46698 
    [ 2.500,  5.000) = 287511 
    [ 5.000,  7.500) = 932 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.394 ms/op
     p(99.9900) =     25.458 ms/op
     p(99.9990) =     30.463 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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
# Warmup Iteration   1: 4.093 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
Iteration   1: 2.965 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  8.151 ms/op
                 getUser·p0.9999: 14.880 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.184 ms/op
                 getUser·p0.9999: 17.849 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   3: 2.988 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.561 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.102 ms/op
                 getUser·p0.9999: 21.843 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321362
  mean =      2.985 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28284 
    [ 2.500,  5.000) = 291782 
    [ 5.000,  7.500) = 936 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.025 ms/op
     p(99.9900) =     20.132 ms/op
     p(99.9990) =     22.341 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.009 ms/op
Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.175 ms/op
                 listUser·p0.9999: 22.240 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 3.763 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.237 ms/op
                 listUser·p0.9999: 15.581 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   3: 3.931 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  18.418 ms/op
                 listUser·p0.9999: 22.601 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247885
  mean =      3.872 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5766 
    [ 2.500,  5.000) = 219608 
    [ 5.000,  7.500) = 21222 
    [ 7.500, 10.000) = 725 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     22.889 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.616 ± 2.919  ops/ms
ClientGrpc.existUser                       thrpt       3  11.147 ± 3.929  ops/ms
ClientGrpc.getUser                         thrpt       3  10.522 ± 2.096  ops/ms
ClientGrpc.listUser                        thrpt       3   8.212 ± 0.812  ops/ms
ClientGrpc.createUser                       avgt       3   3.010 ± 0.297   ms/op
ClientGrpc.existUser                        avgt       3   2.868 ± 0.583   ms/op
ClientGrpc.getUser                          avgt       3   2.990 ± 0.701   ms/op
ClientGrpc.listUser                         avgt       3   3.881 ± 0.188   ms/op
ClientGrpc.createUser                     sample  320670   2.996 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.423           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.941           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.471           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.924           ms/op
ClientGrpc.existUser                      sample  335461   2.861 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.515           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.277           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.394           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.458           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.966           ms/op
ClientGrpc.getUser                        sample  321362   2.985 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.561           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.025           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.132           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.446           ms/op
ClientGrpc.listUser                       sample  247885   3.872 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.994           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.723           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.648           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.249           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.331           ms/op
