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
# Warmup Iteration   1: 4.368 ops/ms
# Warmup Iteration   2: 8.570 ops/ms
# Warmup Iteration   3: 9.905 ops/ms
Iteration   1: 9.963 ops/ms
Iteration   2: 10.056 ops/ms
Iteration   3: 9.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.954 ±(99.9%) 1.948 ops/ms [Average]
  (min, avg, max) = (9.843, 9.954, 10.056), stdev = 0.107
  CI (99.9%): [8.007, 11.902] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.330 ops/ms
# Warmup Iteration   2: 10.010 ops/ms
# Warmup Iteration   3: 10.281 ops/ms
Iteration   1: 10.249 ops/ms
Iteration   2: 10.492 ops/ms
Iteration   3: 10.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.330 ±(99.9%) 2.555 ops/ms [Average]
  (min, avg, max) = (10.249, 10.330, 10.492), stdev = 0.140
  CI (99.9%): [7.775, 12.885] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.385 ops/ms
# Warmup Iteration   2: 9.720 ops/ms
# Warmup Iteration   3: 10.246 ops/ms
Iteration   1: 10.068 ops/ms
Iteration   2: 10.019 ops/ms
Iteration   3: 9.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.015 ±(99.9%) 1.006 ops/ms [Average]
  (min, avg, max) = (9.958, 10.015, 10.068), stdev = 0.055
  CI (99.9%): [9.008, 11.021] (assumes normal distribution)


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
# Warmup Iteration   1: 5.192 ops/ms
# Warmup Iteration   2: 7.790 ops/ms
# Warmup Iteration   3: 7.852 ops/ms
Iteration   1: 7.880 ops/ms
Iteration   2: 7.887 ops/ms
Iteration   3: 7.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.921 ±(99.9%) 1.181 ops/ms [Average]
  (min, avg, max) = (7.880, 7.921, 7.996), stdev = 0.065
  CI (99.9%): [6.741, 9.102] (assumes normal distribution)


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.002 ms/op
Iteration   1: 3.217 ±(99.9%) 0.007 ms/op
Iteration   2: 3.081 ±(99.9%) 0.002 ms/op
Iteration   3: 3.192 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.163 ±(99.9%) 1.323 ms/op [Average]
  (min, avg, max) = (3.081, 3.163, 3.217), stdev = 0.073
  CI (99.9%): [1.840, 4.487] (assumes normal distribution)


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.002 ms/op
Iteration   1: 3.113 ±(99.9%) 0.002 ms/op
Iteration   2: 3.102 ±(99.9%) 0.001 ms/op
Iteration   3: 3.076 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.097 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (3.076, 3.097, 3.113), stdev = 0.019
  CI (99.9%): [2.750, 3.444] (assumes normal distribution)


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.005 ms/op
Iteration   1: 3.154 ±(99.9%) 0.004 ms/op
Iteration   2: 3.183 ±(99.9%) 0.001 ms/op
Iteration   3: 3.144 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.160 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (3.144, 3.160, 3.183), stdev = 0.020
  CI (99.9%): [2.797, 3.524] (assumes normal distribution)


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
# Warmup Iteration   1: 5.438 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.015 ms/op
Iteration   1: 4.077 ±(99.9%) 0.008 ms/op
Iteration   2: 4.030 ±(99.9%) 0.011 ms/op
Iteration   3: 3.932 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.013 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (3.932, 4.013, 4.077), stdev = 0.074
  CI (99.9%): [2.657, 5.368] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.410 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.176 ms/op
                 createUser·p0.9999: 12.643 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  7.921 ms/op
                 createUser·p0.9999: 14.363 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.393 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  8.669 ms/op
                 createUser·p0.9999: 21.676 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311176
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23708 
    [ 2.500,  5.000) = 285883 
    [ 5.000,  7.500) = 1172 
    [ 7.500, 10.000) = 173 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.215 ms/op
     p(99.9900) =     21.087 ms/op
     p(99.9990) =     22.016 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.074 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 2.943 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.093 ms/op
                 existUser·p0.9999: 13.044 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   2: 3.055 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  8.066 ms/op
                 existUser·p0.9999: 15.411 ms/op
                 existUser·p1.00:   16.122 ms/op

Iteration   3: 3.011 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.431 ms/op
                 existUser·p0.9999: 16.138 ms/op
                 existUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319631
  mean =      3.002 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2728 
    [ 1.250,  2.500) = 50084 
    [ 2.500,  3.750) = 233186 
    [ 3.750,  5.000) = 32870 
    [ 5.000,  6.250) = 328 
    [ 6.250,  7.500) = 173 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.138 ms/op
     p(99.9900) =     15.778 ms/op
     p(99.9990) =     16.279 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.343 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.006 ms/op
Iteration   1: 3.223 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  6.937 ms/op
                 getUser·p0.9999: 16.979 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   2: 3.235 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.703 ms/op
                 getUser·p0.9999: 23.302 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.215 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.693 ms/op
                 getUser·p0.9999: 28.672 ms/op
                 getUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297455
  mean =      3.225 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20818 
    [ 2.500,  5.000) = 275502 
    [ 5.000,  7.500) = 839 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.488 ms/op
     p(99.9900) =     28.263 ms/op
     p(99.9990) =     28.738 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 6.076 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.011 ms/op
Iteration   1: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 15.861 ms/op
                 listUser·p1.00:   16.138 ms/op

Iteration   2: 3.998 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.532 ms/op
                 listUser·p0.9999: 16.449 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   3: 4.065 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  16.242 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238414
  mean =      4.028 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2158 
    [ 2.500,  5.000) = 210918 
    [ 5.000,  7.500) = 24215 
    [ 7.500, 10.000) = 640 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     21.950 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.954 ± 1.948  ops/ms
ClientGrpc.existUser                       thrpt       3  10.330 ± 2.555  ops/ms
ClientGrpc.getUser                         thrpt       3  10.015 ± 1.006  ops/ms
ClientGrpc.listUser                        thrpt       3   7.921 ± 1.181  ops/ms
ClientGrpc.createUser                       avgt       3   3.163 ± 1.323   ms/op
ClientGrpc.existUser                        avgt       3   3.097 ± 0.347   ms/op
ClientGrpc.getUser                          avgt       3   3.160 ± 0.364   ms/op
ClientGrpc.listUser                         avgt       3   4.013 ± 1.356   ms/op
ClientGrpc.createUser                     sample  311176   3.083 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.393           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.215           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.087           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.053           ms/op
ClientGrpc.existUser                      sample  319631   3.002 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.731           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.944           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.138           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.778           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.531           ms/op
ClientGrpc.getUser                        sample  297455   3.225 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.736           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.183           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.125           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.488           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.263           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.770           ms/op
ClientGrpc.listUser                       sample  238414   4.028 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.983           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.516           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.054           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.086           ms/op
