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
# Warmup Iteration   1: 2.316 ops/ms
# Warmup Iteration   2: 5.811 ops/ms
# Warmup Iteration   3: 7.354 ops/ms
Iteration   1: 7.813 ops/ms
Iteration   2: 7.992 ops/ms
Iteration   3: 7.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.933 ±(99.9%) 1.887 ops/ms [Average]
  (min, avg, max) = (7.813, 7.933, 7.993), stdev = 0.103
  CI (99.9%): [6.046, 9.820] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.715 ops/ms
# Warmup Iteration   2: 7.707 ops/ms
# Warmup Iteration   3: 8.090 ops/ms
Iteration   1: 8.495 ops/ms
Iteration   2: 8.561 ops/ms
Iteration   3: 8.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.453 ±(99.9%) 2.456 ops/ms [Average]
  (min, avg, max) = (8.302, 8.453, 8.561), stdev = 0.135
  CI (99.9%): [5.997, 10.909] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.269 ops/ms
# Warmup Iteration   2: 7.398 ops/ms
# Warmup Iteration   3: 7.986 ops/ms
Iteration   1: 8.262 ops/ms
Iteration   2: 8.215 ops/ms
Iteration   3: 8.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.201 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (8.125, 8.201, 8.262), stdev = 0.069
  CI (99.9%): [6.933, 9.469] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.538 ops/ms
# Warmup Iteration   2: 5.446 ops/ms
# Warmup Iteration   3: 5.980 ops/ms
Iteration   1: 6.047 ops/ms
Iteration   2: 5.341 ops/ms
Iteration   3: 6.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.818 ±(99.9%) 7.550 ops/ms [Average]
  (min, avg, max) = (5.341, 5.818, 6.068), stdev = 0.414
  CI (99.9%): [≈ 0, 13.368] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.584 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.007 ms/op
Iteration   1: 4.084 ±(99.9%) 0.004 ms/op
Iteration   2: 4.181 ±(99.9%) 0.003 ms/op
Iteration   3: 4.176 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.147 ±(99.9%) 0.997 ms/op [Average]
  (min, avg, max) = (4.084, 4.147, 4.181), stdev = 0.055
  CI (99.9%): [3.149, 5.144] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.115 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.004 ms/op
Iteration   1: 3.724 ±(99.9%) 0.002 ms/op
Iteration   2: 3.760 ±(99.9%) 0.002 ms/op
Iteration   3: 3.734 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.739 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (3.724, 3.739, 3.760), stdev = 0.019
  CI (99.9%): [3.399, 4.080] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.332 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.005 ms/op
Iteration   1: 4.048 ±(99.9%) 0.003 ms/op
Iteration   2: 4.030 ±(99.9%) 0.005 ms/op
Iteration   3: 4.018 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.032 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (4.018, 4.032, 4.048), stdev = 0.015
  CI (99.9%): [3.761, 4.303] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.581 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.535 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.360 ±(99.9%) 0.021 ms/op
Iteration   1: 5.287 ±(99.9%) 0.012 ms/op
Iteration   2: 5.154 ±(99.9%) 0.020 ms/op
Iteration   3: 5.226 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.222 ±(99.9%) 1.210 ms/op [Average]
  (min, avg, max) = (5.154, 5.222, 5.287), stdev = 0.066
  CI (99.9%): [4.012, 6.433] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.618 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.524 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.014 ms/op
Iteration   1: 4.154 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   5.005 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   7.972 ms/op
                 createUser·p0.999:  14.960 ms/op
                 createUser·p0.9999: 21.332 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 4.110 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   5.104 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  14.254 ms/op
                 createUser·p0.9999: 32.244 ms/op
                 createUser·p1.00:   32.801 ms/op

Iteration   3: 4.160 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   7.798 ms/op
                 createUser·p0.999:  15.501 ms/op
                 createUser·p0.9999: 26.835 ms/op
                 createUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 231835
  mean =      4.141 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3791 
    [ 2.500,  5.000) = 201388 
    [ 5.000,  7.500) = 23965 
    [ 7.500, 10.000) = 1421 
    [10.000, 12.500) = 696 
    [12.500, 15.000) = 352 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.968 ms/op
     p(99.9000) =     14.866 ms/op
     p(99.9900) =     29.840 ms/op
     p(99.9990) =     32.638 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.645 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.010 ms/op
Iteration   1: 3.828 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  12.984 ms/op
                 existUser·p0.9999: 20.555 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 3.810 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   6.835 ms/op
                 existUser·p0.999:  14.598 ms/op
                 existUser·p0.9999: 17.308 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   3: 3.713 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  13.580 ms/op
                 existUser·p0.9999: 24.359 ms/op
                 existUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 253760
  mean =      3.783 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11183 
    [ 2.500,  5.000) = 229233 
    [ 5.000,  7.500) = 11502 
    [ 7.500, 10.000) = 966 
    [10.000, 12.500) = 457 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     13.688 ms/op
     p(99.9900) =     22.008 ms/op
     p(99.9990) =     24.916 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.632 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.012 ms/op
Iteration   1: 4.101 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   8.038 ms/op
                 getUser·p0.999:  14.828 ms/op
                 getUser·p0.9999: 19.956 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 4.045 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  15.466 ms/op
                 getUser·p0.9999: 17.111 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   3: 4.057 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  14.601 ms/op
                 getUser·p0.9999: 18.788 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235901
  mean =      4.067 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7372 
    [ 2.500,  5.000) = 203135 
    [ 5.000,  7.500) = 23055 
    [ 7.500, 10.000) = 1257 
    [10.000, 12.500) = 596 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     19.321 ms/op
     p(99.9990) =     20.325 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 8.252 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.694 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.365 ±(99.9%) 0.020 ms/op
Iteration   1: 5.304 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.862 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   6.873 ms/op
                 listUser·p0.95:   7.913 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  16.681 ms/op
                 listUser·p0.9999: 23.493 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   2: 5.267 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.713 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   6.996 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   10.813 ms/op
                 listUser·p0.999:  18.424 ms/op
                 listUser·p0.9999: 20.894 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   3: 5.233 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.729 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   7.946 ms/op
                 listUser·p0.99:   11.319 ms/op
                 listUser·p0.999:  26.573 ms/op
                 listUser·p0.9999: 35.759 ms/op
                 listUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 182223
  mean =      5.268 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 264 
    [ 2.500,  5.000) = 94129 
    [ 5.000,  7.500) = 75204 
    [ 7.500, 10.000) = 10076 
    [10.000, 12.500) = 1567 
    [12.500, 15.000) = 430 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 194 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     31.141 ms/op
     p(99.9990) =     36.253 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.933 ± 1.887  ops/ms
ClientGrpc.existUser                       thrpt       3   8.453 ± 2.456  ops/ms
ClientGrpc.getUser                         thrpt       3   8.201 ± 1.268  ops/ms
ClientGrpc.listUser                        thrpt       3   5.818 ± 7.550  ops/ms
ClientGrpc.createUser                       avgt       3   4.147 ± 0.997   ms/op
ClientGrpc.existUser                        avgt       3   3.739 ± 0.340   ms/op
ClientGrpc.getUser                          avgt       3   4.032 ± 0.271   ms/op
ClientGrpc.listUser                         avgt       3   5.222 ± 1.210   ms/op
ClientGrpc.createUser                     sample  231835   4.141 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.978           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.087           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.505           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.968           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.866           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.840           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.801           ms/op
ClientGrpc.existUser                      sample  253760   3.783 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.788           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.627           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.688           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.008           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.068           ms/op
ClientGrpc.getUser                        sample  235901   4.067 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.024           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.046           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.464           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.471           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.877           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.321           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.447           ms/op
ClientGrpc.listUser                       sample  182223   5.268 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.713           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.913           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.830           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.366           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.141           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.307           ms/op
