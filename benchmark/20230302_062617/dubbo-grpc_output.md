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
# Warmup Iteration   1: 5.052 ops/ms
# Warmup Iteration   2: 9.392 ops/ms
# Warmup Iteration   3: 10.391 ops/ms
Iteration   1: 10.399 ops/ms
Iteration   2: 10.427 ops/ms
Iteration   3: 10.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.417 ±(99.9%) 0.291 ops/ms [Average]
  (min, avg, max) = (10.399, 10.417, 10.427), stdev = 0.016
  CI (99.9%): [10.126, 10.708] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.931 ops/ms
# Warmup Iteration   2: 10.545 ops/ms
# Warmup Iteration   3: 10.650 ops/ms
Iteration   1: 10.968 ops/ms
Iteration   2: 10.878 ops/ms
Iteration   3: 10.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.854 ±(99.9%) 2.331 ops/ms [Average]
  (min, avg, max) = (10.716, 10.854, 10.968), stdev = 0.128
  CI (99.9%): [8.524, 13.185] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.430 ops/ms
# Warmup Iteration   2: 10.240 ops/ms
# Warmup Iteration   3: 10.409 ops/ms
Iteration   1: 10.346 ops/ms
Iteration   2: 10.324 ops/ms
Iteration   3: 10.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.462 ±(99.9%) 4.012 ops/ms [Average]
  (min, avg, max) = (10.324, 10.462, 10.715), stdev = 0.220
  CI (99.9%): [6.449, 14.474] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.886 ops/ms
# Warmup Iteration   2: 7.531 ops/ms
# Warmup Iteration   3: 8.040 ops/ms
Iteration   1: 7.954 ops/ms
Iteration   2: 8.105 ops/ms
Iteration   3: 8.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.089 ±(99.9%) 2.322 ops/ms [Average]
  (min, avg, max) = (7.954, 8.089, 8.207), stdev = 0.127
  CI (99.9%): [5.767, 10.411] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.003 ms/op
Iteration   1: 3.001 ±(99.9%) 0.005 ms/op
Iteration   2: 3.094 ±(99.9%) 0.002 ms/op
Iteration   3: 3.128 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.074 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (3.001, 3.074, 3.128), stdev = 0.065
  CI (99.9%): [1.880, 4.269] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.837 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.003 ms/op
Iteration   1: 2.945 ±(99.9%) 0.003 ms/op
Iteration   2: 2.980 ±(99.9%) 0.002 ms/op
Iteration   3: 2.961 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.962 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.945, 2.962, 2.980), stdev = 0.018
  CI (99.9%): [2.639, 3.285] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.943 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.005 ms/op
Iteration   2: 3.148 ±(99.9%) 0.002 ms/op
Iteration   3: 3.168 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.125 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (3.057, 3.125, 3.168), stdev = 0.059
  CI (99.9%): [2.041, 4.208] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.024 ms/op
Iteration   1: 3.977 ±(99.9%) 0.039 ms/op
Iteration   2: 4.008 ±(99.9%) 0.017 ms/op
Iteration   3: 4.051 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.012 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.977, 4.012, 4.051), stdev = 0.037
  CI (99.9%): [3.333, 4.692] (assumes normal distribution)


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
Iteration   1: 3.086 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.509 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  8.167 ms/op
                 createUser·p0.9999: 21.877 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.347 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  11.176 ms/op
                 createUser·p0.9999: 17.066 ms/op
                 createUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308773
  mean =      3.108 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25161 
    [ 2.500,  5.000) = 282459 
    [ 5.000,  7.500) = 791 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.251 ms/op
     p(99.9900) =     21.139 ms/op
     p(99.9990) =     22.181 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.534 ms/op
                 existUser·p0.9999: 15.849 ms/op
                 existUser·p1.00:   16.138 ms/op

Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  5.328 ms/op
                 existUser·p0.9999: 14.280 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.457 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.306 ms/op
                 existUser·p0.999:  6.070 ms/op
                 existUser·p0.9999: 14.820 ms/op
                 existUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318541
  mean =      3.014 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1469 
    [ 1.250,  2.500) = 38551 
    [ 2.500,  3.750) = 255764 
    [ 3.750,  5.000) = 22051 
    [ 5.000,  6.250) = 409 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.144 ms/op
     p(99.9900) =     15.361 ms/op
     p(99.9990) =     16.024 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.178 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  8.454 ms/op
                 getUser·p0.9999: 12.024 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.358 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.466 ms/op
                 getUser·p0.9999: 13.100 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   3: 3.162 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.062 ms/op
                 getUser·p0.9999: 13.369 ms/op
                 getUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305426
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1258 
    [ 1.250,  2.500) = 21696 
    [ 2.500,  3.750) = 242600 
    [ 3.750,  5.000) = 39123 
    [ 5.000,  6.250) = 325 
    [ 6.250,  7.500) = 140 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.358 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.132 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


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
# Warmup Iteration   1: 4.619 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.011 ms/op
Iteration   1: 3.996 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.760 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 18.514 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 3.965 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 22.565 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   3: 4.142 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.475 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  13.298 ms/op
                 listUser·p0.9999: 17.212 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238117
  mean =      4.033 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3559 
    [ 2.500,  5.000) = 203163 
    [ 5.000,  7.500) = 30146 
    [ 7.500, 10.000) = 839 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     13.349 ms/op
     p(99.9900) =     21.934 ms/op
     p(99.9990) =     22.802 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.417 ± 0.291  ops/ms
ClientGrpc.existUser                       thrpt       3  10.854 ± 2.331  ops/ms
ClientGrpc.getUser                         thrpt       3  10.462 ± 4.012  ops/ms
ClientGrpc.listUser                        thrpt       3   8.089 ± 2.322  ops/ms
ClientGrpc.createUser                       avgt       3   3.074 ± 1.194   ms/op
ClientGrpc.existUser                        avgt       3   2.962 ± 0.323   ms/op
ClientGrpc.getUser                          avgt       3   3.125 ± 1.083   ms/op
ClientGrpc.listUser                         avgt       3   4.012 ± 0.679   ms/op
ClientGrpc.createUser                     sample  308773   3.108 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.509           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.251           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.139           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.315           ms/op
ClientGrpc.existUser                      sample  318541   3.014 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.457           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.842           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.144           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.361           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.138           ms/op
ClientGrpc.getUser                        sample  305426   3.143 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.358           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.973           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.132           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.206           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          13.615           ms/op
ClientGrpc.listUser                       sample  238117   4.033 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.475           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.349           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.934           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.314           ms/op
