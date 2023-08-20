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
# Warmup Iteration   1: 3.970 ops/ms
# Warmup Iteration   2: 9.075 ops/ms
# Warmup Iteration   3: 9.750 ops/ms
Iteration   1: 10.174 ops/ms
Iteration   2: 10.258 ops/ms
Iteration   3: 10.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.277 ±(99.9%) 2.071 ops/ms [Average]
  (min, avg, max) = (10.174, 10.277, 10.399), stdev = 0.114
  CI (99.9%): [8.206, 12.348] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.016 ops/ms
# Warmup Iteration   2: 10.095 ops/ms
# Warmup Iteration   3: 10.738 ops/ms
Iteration   1: 11.077 ops/ms
Iteration   2: 10.737 ops/ms
Iteration   3: 11.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.956 ±(99.9%) 3.456 ops/ms [Average]
  (min, avg, max) = (10.737, 10.956, 11.077), stdev = 0.189
  CI (99.9%): [7.500, 14.412] (assumes normal distribution)


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
# Warmup Iteration   1: 6.810 ops/ms
# Warmup Iteration   2: 9.511 ops/ms
# Warmup Iteration   3: 9.712 ops/ms
Iteration   1: 10.058 ops/ms
Iteration   2: 10.068 ops/ms
Iteration   3: 10.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.124 ±(99.9%) 1.951 ops/ms [Average]
  (min, avg, max) = (10.058, 10.124, 10.248), stdev = 0.107
  CI (99.9%): [8.173, 12.076] (assumes normal distribution)


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
# Warmup Iteration   1: 4.996 ops/ms
# Warmup Iteration   2: 7.390 ops/ms
# Warmup Iteration   3: 7.727 ops/ms
Iteration   1: 7.965 ops/ms
Iteration   2: 7.962 ops/ms
Iteration   3: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.991 ±(99.9%) 0.880 ops/ms [Average]
  (min, avg, max) = (7.962, 7.991, 8.047), stdev = 0.048
  CI (99.9%): [7.112, 8.871] (assumes normal distribution)


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.002 ms/op
Iteration   1: 3.127 ±(99.9%) 0.012 ms/op
Iteration   2: 3.062 ±(99.9%) 0.004 ms/op
Iteration   3: 3.122 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.103 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (3.062, 3.103, 3.127), stdev = 0.036
  CI (99.9%): [2.441, 3.766] (assumes normal distribution)


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.003 ms/op
Iteration   1: 2.892 ±(99.9%) 0.003 ms/op
Iteration   2: 2.940 ±(99.9%) 0.002 ms/op
Iteration   3: 2.961 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.931 ±(99.9%) 0.642 ms/op [Average]
  (min, avg, max) = (2.892, 2.931, 2.961), stdev = 0.035
  CI (99.9%): [2.289, 3.573] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.647 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.002 ms/op
Iteration   1: 3.087 ±(99.9%) 0.003 ms/op
Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
Iteration   3: 3.090 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 0.079 ms/op [Average]
  (min, avg, max) = (3.087, 3.091, 3.095), stdev = 0.004
  CI (99.9%): [3.012, 3.170] (assumes normal distribution)


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
# Warmup Iteration   1: 5.395 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.020 ms/op
Iteration   1: 4.174 ±(99.9%) 0.016 ms/op
Iteration   2: 4.157 ±(99.9%) 0.023 ms/op
Iteration   3: 4.079 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.137 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (4.079, 4.137, 4.174), stdev = 0.051
  CI (99.9%): [3.209, 5.064] (assumes normal distribution)


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 2.992 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.673 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 13.363 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  8.221 ms/op
                 createUser·p0.9999: 14.522 ms/op
                 createUser·p1.00:   15.008 ms/op

Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  13.431 ms/op
                 createUser·p0.9999: 23.495 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314760
  mean =      3.049 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22144 
    [ 2.500,  5.000) = 290808 
    [ 5.000,  7.500) = 1282 
    [ 7.500, 10.000) = 252 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     18.481 ms/op
     p(99.9990) =     23.864 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.933 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.489 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.513 ms/op
                 existUser·p0.999:  9.879 ms/op
                 existUser·p0.9999: 19.346 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 2.930 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  11.076 ms/op
                 existUser·p0.9999: 16.744 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  9.302 ms/op
                 existUser·p0.9999: 16.089 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326882
  mean =      2.938 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1999 
    [ 1.250,  2.500) = 32991 
    [ 2.500,  3.750) = 280440 
    [ 3.750,  5.000) = 9406 
    [ 5.000,  6.250) = 933 
    [ 6.250,  7.500) = 424 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 151 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     10.211 ms/op
     p(99.9900) =     18.436 ms/op
     p(99.9990) =     19.741 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  8.083 ms/op
                 getUser·p0.9999: 21.561 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  8.281 ms/op
                 getUser·p0.9999: 14.500 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   3: 3.128 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  9.105 ms/op
                 getUser·p0.9999: 16.569 ms/op
                 getUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312004
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19395 
    [ 2.500,  5.000) = 290390 
    [ 5.000,  7.500) = 1728 
    [ 7.500, 10.000) = 298 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.726 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     17.780 ms/op
     p(99.9990) =     21.881 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 5.314 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.282 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.011 ms/op
Iteration   1: 3.990 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.304 ms/op
                 listUser·p0.999:  14.579 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 3.957 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.697 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 24.671 ms/op
                 listUser·p1.00:   28.115 ms/op

Iteration   3: 3.997 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   7.148 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241078
  mean =      3.981 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1939 
    [ 2.500,  5.000) = 217623 
    [ 5.000,  7.500) = 19731 
    [ 7.500, 10.000) = 1255 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     16.171 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     27.374 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.277 ± 2.071  ops/ms
ClientGrpc.existUser                       thrpt       3  10.956 ± 3.456  ops/ms
ClientGrpc.getUser                         thrpt       3  10.124 ± 1.951  ops/ms
ClientGrpc.listUser                        thrpt       3   7.991 ± 0.880  ops/ms
ClientGrpc.createUser                       avgt       3   3.103 ± 0.662   ms/op
ClientGrpc.existUser                        avgt       3   2.931 ± 0.642   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 0.079   ms/op
ClientGrpc.listUser                         avgt       3   4.137 ± 0.928   ms/op
ClientGrpc.createUser                     sample  314760   3.049 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.616           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.044           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.481           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.576           ms/op
ClientGrpc.existUser                      sample  326882   2.938 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.489           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.211           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.436           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.825           ms/op
ClientGrpc.getUser                        sample  312004   3.077 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.797           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.726           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.389           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.780           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  241078   3.981 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.037           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.171           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.167           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.115           ms/op
