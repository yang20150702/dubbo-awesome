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
# Warmup Iteration   1: 4.228 ops/ms
# Warmup Iteration   2: 8.992 ops/ms
# Warmup Iteration   3: 9.658 ops/ms
Iteration   1: 9.863 ops/ms
Iteration   2: 10.003 ops/ms
Iteration   3: 9.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.927 ±(99.9%) 1.286 ops/ms [Average]
  (min, avg, max) = (9.863, 9.927, 10.003), stdev = 0.071
  CI (99.9%): [8.641, 11.213] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.364 ops/ms
# Warmup Iteration   2: 9.991 ops/ms
# Warmup Iteration   3: 10.701 ops/ms
Iteration   1: 10.372 ops/ms
Iteration   2: 10.749 ops/ms
Iteration   3: 10.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.601 ±(99.9%) 3.678 ops/ms [Average]
  (min, avg, max) = (10.372, 10.601, 10.749), stdev = 0.202
  CI (99.9%): [6.924, 14.279] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.023 ops/ms
# Warmup Iteration   2: 9.890 ops/ms
# Warmup Iteration   3: 10.099 ops/ms
Iteration   1: 10.205 ops/ms
Iteration   2: 10.221 ops/ms
Iteration   3: 10.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.285 ±(99.9%) 2.281 ops/ms [Average]
  (min, avg, max) = (10.205, 10.285, 10.429), stdev = 0.125
  CI (99.9%): [8.004, 12.566] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.612 ops/ms
# Warmup Iteration   2: 7.656 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 8.136 ops/ms
Iteration   2: 8.127 ops/ms
Iteration   3: 8.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.088 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (8.000, 8.088, 8.136), stdev = 0.076
  CI (99.9%): [6.701, 9.475] (assumes normal distribution)


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.004 ms/op
Iteration   1: 3.128 ±(99.9%) 0.002 ms/op
Iteration   2: 3.099 ±(99.9%) 0.003 ms/op
Iteration   3: 3.055 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.094 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.055, 3.094, 3.128), stdev = 0.037
  CI (99.9%): [2.427, 3.761] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 2.979 ±(99.9%) 0.002 ms/op
Iteration   2: 3.053 ±(99.9%) 0.002 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.030 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (2.979, 3.030, 3.058), stdev = 0.044
  CI (99.9%): [2.223, 3.837] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.150 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.002 ms/op
Iteration   1: 3.111 ±(99.9%) 0.002 ms/op
Iteration   2: 3.130 ±(99.9%) 0.002 ms/op
Iteration   3: 3.086 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.109 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (3.086, 3.109, 3.130), stdev = 0.022
  CI (99.9%): [2.703, 3.515] (assumes normal distribution)


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
# Warmup Iteration   1: 5.501 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.012 ms/op
Iteration   1: 3.977 ±(99.9%) 0.007 ms/op
Iteration   2: 3.936 ±(99.9%) 0.009 ms/op
Iteration   3: 3.887 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.933 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (3.887, 3.933, 3.977), stdev = 0.045
  CI (99.9%): [3.109, 4.757] (assumes normal distribution)


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
# Warmup Iteration   1: 4.323 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.162 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  8.920 ms/op
                 createUser·p0.9999: 16.346 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  6.519 ms/op
                 createUser·p0.9999: 21.583 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   3: 3.137 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  10.256 ms/op
                 createUser·p0.9999: 16.318 ms/op
                 createUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306491
  mean =      3.131 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28240 
    [ 2.500,  5.000) = 277175 
    [ 5.000,  7.500) = 706 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.208 ms/op
     p(99.9900) =     20.590 ms/op
     p(99.9990) =     21.981 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
Iteration   1: 3.012 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.632 ms/op
                 existUser·p0.9999: 13.251 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.398 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.312 ms/op
                 existUser·p0.9999: 14.375 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.436 ms/op
                 existUser·p0.9999: 15.096 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317862
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 982 
    [ 1.250,  2.500) = 47206 
    [ 2.500,  3.750) = 241986 
    [ 3.750,  5.000) = 26807 
    [ 5.000,  6.250) = 272 
    [ 6.250,  7.500) = 295 
    [ 7.500,  8.750) = 157 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.479 ms/op
     p(99.9900) =     14.549 ms/op
     p(99.9990) =     15.847 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
Iteration   1: 3.080 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.102 ms/op
                 getUser·p0.9999: 27.725 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.911 ms/op
                 getUser·p0.9999: 20.775 ms/op
                 getUser·p1.00:   21.103 ms/op

Iteration   3: 3.120 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.107 ms/op
                 getUser·p0.9999: 34.062 ms/op
                 getUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309636
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24314 
    [ 2.500,  5.000) = 284245 
    [ 5.000,  7.500) = 761 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.569 ms/op
     p(99.9900) =     33.457 ms/op
     p(99.9990) =     35.692 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 5.537 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
Iteration   1: 4.008 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.343 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.961 ms/op
                 listUser·p0.9999: 19.925 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 3.961 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.998 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.715 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 19.398 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240629
  mean =      3.989 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3065 
    [ 2.500,  5.000) = 208137 
    [ 5.000,  7.500) = 28288 
    [ 7.500, 10.000) = 740 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     19.298 ms/op
     p(99.9990) =     20.650 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.927 ± 1.286  ops/ms
ClientGrpc.existUser                       thrpt       3  10.601 ± 3.678  ops/ms
ClientGrpc.getUser                         thrpt       3  10.285 ± 2.281  ops/ms
ClientGrpc.listUser                        thrpt       3   8.088 ± 1.387  ops/ms
ClientGrpc.createUser                       avgt       3   3.094 ± 0.667   ms/op
ClientGrpc.existUser                        avgt       3   3.030 ± 0.807   ms/op
ClientGrpc.getUser                          avgt       3   3.109 ± 0.406   ms/op
ClientGrpc.listUser                         avgt       3   3.933 ± 0.824   ms/op
ClientGrpc.createUser                     sample  306491   3.131 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.653           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.208           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.590           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  317862   3.018 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.398           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.891           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.479           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.549           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  309636   3.098 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.584           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.569           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.457           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.290           ms/op
ClientGrpc.listUser                       sample  240629   3.989 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.343           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.298           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.234           ms/op
