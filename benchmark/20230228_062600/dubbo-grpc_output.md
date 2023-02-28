# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.195 ops/ms
# Warmup Iteration   2: 8.523 ops/ms
# Warmup Iteration   3: 9.780 ops/ms
Iteration   1: 10.188 ops/ms
Iteration   2: 10.173 ops/ms
Iteration   3: 10.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.181 ±(99.9%) 0.135 ops/ms [Average]
  (min, avg, max) = (10.173, 10.181, 10.188), stdev = 0.007
  CI (99.9%): [10.047, 10.316] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.337 ops/ms
# Warmup Iteration   2: 10.295 ops/ms
# Warmup Iteration   3: 10.530 ops/ms
Iteration   1: 10.479 ops/ms
Iteration   2: 10.404 ops/ms
Iteration   3: 10.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.434 ±(99.9%) 0.731 ops/ms [Average]
  (min, avg, max) = (10.404, 10.434, 10.479), stdev = 0.040
  CI (99.9%): [9.703, 11.165] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.327 ops/ms
# Warmup Iteration   2: 9.794 ops/ms
# Warmup Iteration   3: 9.899 ops/ms
Iteration   1: 9.852 ops/ms
Iteration   2: 9.778 ops/ms
Iteration   3: 9.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.875 ±(99.9%) 1.994 ops/ms [Average]
  (min, avg, max) = (9.778, 9.875, 9.994), stdev = 0.109
  CI (99.9%): [7.881, 11.869] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.161 ops/ms
# Warmup Iteration   2: 7.198 ops/ms
# Warmup Iteration   3: 7.769 ops/ms
Iteration   1: 7.877 ops/ms
Iteration   2: 7.763 ops/ms
Iteration   3: 7.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.765 ±(99.9%) 2.014 ops/ms [Average]
  (min, avg, max) = (7.656, 7.765, 7.877), stdev = 0.110
  CI (99.9%): [5.752, 9.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.469 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.007 ms/op
Iteration   1: 3.209 ±(99.9%) 0.002 ms/op
Iteration   2: 3.188 ±(99.9%) 0.001 ms/op
Iteration   3: 3.123 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.173 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (3.123, 3.173, 3.209), stdev = 0.044
  CI (99.9%): [2.362, 3.984] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.349 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.002 ms/op
Iteration   1: 3.111 ±(99.9%) 0.002 ms/op
Iteration   2: 3.104 ±(99.9%) 0.001 ms/op
Iteration   3: 3.108 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.107 ±(99.9%) 0.066 ms/op [Average]
  (min, avg, max) = (3.104, 3.107, 3.111), stdev = 0.004
  CI (99.9%): [3.041, 3.174] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.451 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.002 ms/op
Iteration   1: 3.223 ±(99.9%) 0.002 ms/op
Iteration   2: 3.217 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.206 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (3.177, 3.206, 3.223), stdev = 0.025
  CI (99.9%): [2.747, 3.664] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.904 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.005 ms/op
Iteration   1: 4.144 ±(99.9%) 0.015 ms/op
Iteration   2: 4.148 ±(99.9%) 0.011 ms/op
Iteration   3: 4.138 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.144 ±(99.9%) 0.090 ms/op [Average]
  (min, avg, max) = (4.138, 4.144, 4.148), stdev = 0.005
  CI (99.9%): [4.054, 4.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.407 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.007 ms/op
Iteration   1: 3.134 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.517 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  7.617 ms/op
                 createUser·p0.9999: 18.277 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.116 ms/op
                 createUser·p0.9999: 18.945 ms/op
                 createUser·p1.00:   20.087 ms/op

Iteration   3: 3.243 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.358 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  7.528 ms/op
                 createUser·p0.9999: 20.414 ms/op
                 createUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302963
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23391 
    [ 2.500,  5.000) = 277702 
    [ 5.000,  7.500) = 1577 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.358 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      7.422 ms/op
     p(99.9900) =     19.815 ms/op
     p(99.9990) =     21.855 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.103 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.007 ms/op
Iteration   1: 2.988 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.397 ms/op
                 existUser·p0.9999: 14.762 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   2: 3.076 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.240 ms/op
                 existUser·p0.9999: 14.080 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.107 ms/op
                 existUser·p0.9999: 17.476 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314707
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1525 
    [ 1.250,  2.500) = 38720 
    [ 2.500,  3.750) = 243778 
    [ 3.750,  5.000) = 29343 
    [ 5.000,  6.250) = 652 
    [ 6.250,  7.500) = 423 
    [ 7.500,  8.750) = 101 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     15.567 ms/op
     p(99.9990) =     17.854 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
Iteration   1: 3.237 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.504 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  10.764 ms/op
                 getUser·p0.9999: 19.861 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  8.133 ms/op
                 getUser·p0.9999: 24.093 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   3: 3.156 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.808 ms/op
                 getUser·p0.9999: 21.424 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298786
  mean =      3.212 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15669 
    [ 2.500,  5.000) = 281691 
    [ 5.000,  7.500) = 1097 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.770 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.249 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.012 ms/op
Iteration   1: 4.179 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  14.442 ms/op
                 listUser·p0.9999: 23.342 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   2: 4.046 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  18.448 ms/op
                 listUser·p0.9999: 26.149 ms/op
                 listUser·p1.00:   26.542 ms/op

Iteration   3: 4.060 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.057 ms/op
                 listUser·p0.999:  17.211 ms/op
                 listUser·p0.9999: 29.757 ms/op
                 listUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234451
  mean =      4.094 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2284 
    [ 2.500,  5.000) = 202907 
    [ 5.000,  7.500) = 27431 
    [ 7.500, 10.000) = 1360 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     28.854 ms/op
     p(99.9990) =     29.982 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.181 ± 0.135  ops/ms
ClientGrpc.existUser                       thrpt       3  10.434 ± 0.731  ops/ms
ClientGrpc.getUser                         thrpt       3   9.875 ± 1.994  ops/ms
ClientGrpc.listUser                        thrpt       3   7.765 ± 2.014  ops/ms
ClientGrpc.createUser                       avgt       3   3.173 ± 0.811   ms/op
ClientGrpc.existUser                        avgt       3   3.107 ± 0.066   ms/op
ClientGrpc.getUser                          avgt       3   3.206 ± 0.458   ms/op
ClientGrpc.listUser                         avgt       3   4.144 ± 0.090   ms/op
ClientGrpc.createUser                     sample  302963   3.169 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.358           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.422           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.815           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.987           ms/op
ClientGrpc.existUser                      sample  314707   3.051 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.680           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.928           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.299           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.567           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  298786   3.212 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.504           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.174           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.084           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.799           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.790           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.478           ms/op
ClientGrpc.listUser                       sample  234451   4.094 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.038           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.250           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.138           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.854           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.048           ms/op
