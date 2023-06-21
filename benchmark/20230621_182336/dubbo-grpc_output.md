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
# Warmup Iteration   1: 3.968 ops/ms
# Warmup Iteration   2: 9.121 ops/ms
# Warmup Iteration   3: 9.967 ops/ms
Iteration   1: 10.560 ops/ms
Iteration   2: 10.480 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.507 ±(99.9%) 0.839 ops/ms [Average]
  (min, avg, max) = (10.480, 10.507, 10.560), stdev = 0.046
  CI (99.9%): [9.668, 11.345] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.574 ops/ms
# Warmup Iteration   2: 10.347 ops/ms
# Warmup Iteration   3: 10.790 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 11.026 ops/ms
Iteration   3: 11.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.923 ±(99.9%) 5.380 ops/ms [Average]
  (min, avg, max) = (10.590, 10.923, 11.152), stdev = 0.295
  CI (99.9%): [5.543, 16.303] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.038 ops/ms
# Warmup Iteration   2: 9.873 ops/ms
# Warmup Iteration   3: 10.272 ops/ms
Iteration   1: 10.170 ops/ms
Iteration   2: 10.383 ops/ms
Iteration   3: 10.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.268 ±(99.9%) 1.960 ops/ms [Average]
  (min, avg, max) = (10.170, 10.268, 10.383), stdev = 0.107
  CI (99.9%): [8.308, 12.228] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.287 ops/ms
# Warmup Iteration   2: 7.857 ops/ms
# Warmup Iteration   3: 8.042 ops/ms
Iteration   1: 7.934 ops/ms
Iteration   2: 7.895 ops/ms
Iteration   3: 7.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.872 ±(99.9%) 1.392 ops/ms [Average]
  (min, avg, max) = (7.787, 7.872, 7.934), stdev = 0.076
  CI (99.9%): [6.480, 9.264] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.793 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.421 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.002 ms/op
Iteration   1: 3.207 ±(99.9%) 0.002 ms/op
Iteration   2: 3.104 ±(99.9%) 0.003 ms/op
Iteration   3: 3.066 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.126 ±(99.9%) 1.336 ms/op [Average]
  (min, avg, max) = (3.066, 3.126, 3.207), stdev = 0.073
  CI (99.9%): [1.790, 4.461] (assumes normal distribution)


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.003 ms/op
Iteration   1: 2.934 ±(99.9%) 0.002 ms/op
Iteration   2: 2.964 ±(99.9%) 0.002 ms/op
Iteration   3: 2.931 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.943 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (2.931, 2.943, 2.964), stdev = 0.018
  CI (99.9%): [2.606, 3.280] (assumes normal distribution)


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
# Warmup Iteration   1: 4.178 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.005 ms/op
Iteration   1: 3.105 ±(99.9%) 0.004 ms/op
Iteration   2: 3.084 ±(99.9%) 0.005 ms/op
Iteration   3: 3.091 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.093 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (3.084, 3.093, 3.105), stdev = 0.011
  CI (99.9%): [2.901, 3.286] (assumes normal distribution)


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
# Warmup Iteration   1: 5.809 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.017 ms/op
Iteration   1: 4.036 ±(99.9%) 0.034 ms/op
Iteration   2: 4.102 ±(99.9%) 0.011 ms/op
Iteration   3: 4.098 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.079 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (4.036, 4.079, 4.102), stdev = 0.037
  CI (99.9%): [3.408, 4.749] (assumes normal distribution)


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
# Warmup Iteration   1: 4.532 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.006 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.293 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.946 ms/op
                 createUser·p0.9999: 15.013 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   2: 3.094 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  12.037 ms/op
                 createUser·p0.9999: 13.348 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   3: 3.074 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.742 ms/op
                 createUser·p0.9999: 16.843 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309583
  mean =      3.100 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 270 
    [ 1.250,  2.500) = 9589 
    [ 2.500,  3.750) = 285743 
    [ 3.750,  5.000) = 12600 
    [ 5.000,  6.250) = 741 
    [ 6.250,  7.500) = 297 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.293 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.374 ms/op
     p(99.9900) =     16.271 ms/op
     p(99.9990) =     16.971 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.005 ms/op
Iteration   1: 2.805 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  7.500 ms/op
                 existUser·p0.9999: 12.183 ms/op
                 existUser·p1.00:   12.485 ms/op

Iteration   2: 2.899 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  6.628 ms/op
                 existUser·p0.9999: 14.172 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   3: 2.957 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  11.010 ms/op
                 existUser·p0.9999: 16.275 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332666
  mean =      2.886 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1723 
    [ 1.250,  2.500) = 34334 
    [ 2.500,  3.750) = 290489 
    [ 3.750,  5.000) = 5056 
    [ 5.000,  6.250) = 543 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.437 ms/op
     p(99.0000) =      4.035 ms/op
     p(99.9000) =      7.242 ms/op
     p(99.9900) =     15.155 ms/op
     p(99.9990) =     17.040 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 4.505 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  8.595 ms/op
                 getUser·p0.9999: 18.008 ms/op
                 getUser·p1.00:   20.152 ms/op

Iteration   2: 3.092 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.562 ms/op
                 getUser·p0.9999: 15.854 ms/op
                 getUser·p1.00:   16.073 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.796 ms/op
                 getUser·p0.9999: 16.567 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311302
  mean =      3.083 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19300 
    [ 2.500,  5.000) = 289917 
    [ 5.000,  7.500) = 1798 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      7.360 ms/op
     p(99.9900) =     17.195 ms/op
     p(99.9990) =     19.531 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 5.695 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.012 ms/op
Iteration   1: 4.058 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.189 ms/op
                 listUser·p0.9999: 16.932 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   2: 4.113 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.174 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.127 ms/op
                 listUser·p0.9999: 16.112 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   3: 4.114 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   3.918 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  20.421 ms/op
                 listUser·p0.9999: 27.951 ms/op
                 listUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234340
  mean =      4.095 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1819 
    [ 2.500,  5.000) = 206735 
    [ 5.000,  7.500) = 24182 
    [ 7.500, 10.000) = 1160 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     14.117 ms/op
     p(99.9900) =     27.525 ms/op
     p(99.9990) =     28.844 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.507 ± 0.839  ops/ms
ClientGrpc.existUser                       thrpt       3  10.923 ± 5.380  ops/ms
ClientGrpc.getUser                         thrpt       3  10.268 ± 1.960  ops/ms
ClientGrpc.listUser                        thrpt       3   7.872 ± 1.392  ops/ms
ClientGrpc.createUser                       avgt       3   3.126 ± 1.336   ms/op
ClientGrpc.existUser                        avgt       3   2.943 ± 0.337   ms/op
ClientGrpc.getUser                          avgt       3   3.093 ± 0.192   ms/op
ClientGrpc.listUser                         avgt       3   4.079 ± 0.671   ms/op
ClientGrpc.createUser                     sample  309583   3.100 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.293           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.374           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.271           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.236           ms/op
ClientGrpc.existUser                      sample  332666   2.886 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.695           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.297           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.035           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.242           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.155           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.203           ms/op
ClientGrpc.getUser                        sample  311302   3.083 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.551           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.360           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.195           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.152           ms/op
ClientGrpc.listUser                       sample  234340   4.095 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.966           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.117           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.525           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.426           ms/op
