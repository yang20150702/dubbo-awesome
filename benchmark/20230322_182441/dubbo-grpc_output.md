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
# Warmup Iteration   1: 4.378 ops/ms
# Warmup Iteration   2: 8.513 ops/ms
# Warmup Iteration   3: 9.642 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.739 ops/ms
Iteration   3: 10.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.626 ±(99.9%) 2.131 ops/ms [Average]
  (min, avg, max) = (10.505, 10.626, 10.739), stdev = 0.117
  CI (99.9%): [8.495, 12.757] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 8.016 ops/ms
# Warmup Iteration   2: 10.907 ops/ms
# Warmup Iteration   3: 11.443 ops/ms
Iteration   1: 11.120 ops/ms
Iteration   2: 11.424 ops/ms
Iteration   3: 10.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.163 ±(99.9%) 4.410 ops/ms [Average]
  (min, avg, max) = (10.946, 11.163, 11.424), stdev = 0.242
  CI (99.9%): [6.753, 15.573] (assumes normal distribution)


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
# Warmup Iteration   1: 7.364 ops/ms
# Warmup Iteration   2: 10.040 ops/ms
# Warmup Iteration   3: 10.647 ops/ms
Iteration   1: 10.858 ops/ms
Iteration   2: 10.685 ops/ms
Iteration   3: 10.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.735 ±(99.9%) 1.952 ops/ms [Average]
  (min, avg, max) = (10.662, 10.735, 10.858), stdev = 0.107
  CI (99.9%): [8.782, 12.687] (assumes normal distribution)


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
# Warmup Iteration   1: 6.207 ops/ms
# Warmup Iteration   2: 7.829 ops/ms
# Warmup Iteration   3: 8.159 ops/ms
Iteration   1: 8.287 ops/ms
Iteration   2: 8.433 ops/ms
Iteration   3: 8.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.345 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (8.287, 8.345, 8.433), stdev = 0.078
  CI (99.9%): [6.928, 9.761] (assumes normal distribution)


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.007 ms/op
Iteration   1: 2.975 ±(99.9%) 0.002 ms/op
Iteration   2: 2.973 ±(99.9%) 0.003 ms/op
Iteration   3: 2.908 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.952 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (2.908, 2.952, 2.975), stdev = 0.038
  CI (99.9%): [2.261, 3.643] (assumes normal distribution)


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.911 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.003 ms/op
Iteration   1: 2.875 ±(99.9%) 0.004 ms/op
Iteration   2: 2.923 ±(99.9%) 0.003 ms/op
Iteration   3: 2.872 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.890 ±(99.9%) 0.526 ms/op [Average]
  (min, avg, max) = (2.872, 2.890, 2.923), stdev = 0.029
  CI (99.9%): [2.364, 3.415] (assumes normal distribution)


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.002 ms/op
Iteration   1: 2.981 ±(99.9%) 0.002 ms/op
Iteration   2: 2.983 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.976 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.965, 2.976, 2.983), stdev = 0.010
  CI (99.9%): [2.794, 3.158] (assumes normal distribution)


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
# Warmup Iteration   1: 5.698 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.009 ms/op
Iteration   1: 3.872 ±(99.9%) 0.014 ms/op
Iteration   2: 3.833 ±(99.9%) 0.032 ms/op
Iteration   3: 3.803 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.836 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (3.803, 3.836, 3.872), stdev = 0.034
  CI (99.9%): [3.213, 4.459] (assumes normal distribution)


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.609 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.805 ms/op
                 createUser·p0.9999: 16.327 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.502 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  6.326 ms/op
                 createUser·p0.9999: 16.104 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   3: 2.930 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.540 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.766 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  7.657 ms/op
                 createUser·p0.9999: 17.337 ms/op
                 createUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323222
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2053 
    [ 1.250,  2.500) = 27996 
    [ 2.500,  3.750) = 279234 
    [ 3.750,  5.000) = 12597 
    [ 5.000,  6.250) = 912 
    [ 6.250,  7.500) = 115 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.087 ms/op
     p(99.9900) =     16.761 ms/op
     p(99.9990) =     19.694 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.839 ±(99.9%) 0.007 ms/op
Iteration   1: 2.944 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.354 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.013 ms/op
                 existUser·p0.9999: 12.438 ms/op
                 existUser·p1.00:   12.681 ms/op

Iteration   2: 2.895 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 24.738 ms/op
                 existUser·p1.00:   25.166 ms/op

Iteration   3: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.285 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.463 ms/op
                 existUser·p0.9999: 20.185 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327734
  mean =      2.927 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39449 
    [ 2.500,  5.000) = 287291 
    [ 5.000,  7.500) = 825 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.285 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      6.234 ms/op
     p(99.9900) =     21.208 ms/op
     p(99.9990) =     24.960 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.927 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.127 ms/op
                 getUser·p0.9999: 11.774 ms/op
                 getUser·p1.00:   12.124 ms/op

Iteration   2: 2.919 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.301 ms/op
                 getUser·p0.95:   3.453 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.057 ms/op
                 getUser·p0.9999: 15.156 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  6.668 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323557
  mean =      2.966 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2149 
    [ 1.250,  2.500) = 20422 
    [ 2.500,  3.750) = 288971 
    [ 3.750,  5.000) = 10950 
    [ 5.000,  6.250) = 490 
    [ 6.250,  7.500) = 353 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.028 ms/op
     p(99.9900) =     17.982 ms/op
     p(99.9990) =     19.686 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 4.999 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.010 ms/op
Iteration   1: 3.866 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  12.452 ms/op
                 listUser·p0.9999: 14.098 ms/op
                 listUser·p1.00:   14.434 ms/op

Iteration   2: 3.875 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.360 ms/op
                 listUser·p0.9999: 26.919 ms/op
                 listUser·p1.00:   27.329 ms/op

Iteration   3: 3.915 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.444 ms/op
                 listUser·p0.9999: 19.775 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246939
  mean =      3.885 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4698 
    [ 2.500,  5.000) = 220838 
    [ 5.000,  7.500) = 20145 
    [ 7.500, 10.000) = 746 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     13.829 ms/op
     p(99.9900) =     25.143 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.626 ± 2.131  ops/ms
ClientGrpc.existUser                       thrpt       3  11.163 ± 4.410  ops/ms
ClientGrpc.getUser                         thrpt       3  10.735 ± 1.952  ops/ms
ClientGrpc.listUser                        thrpt       3   8.345 ± 1.416  ops/ms
ClientGrpc.createUser                       avgt       3   2.952 ± 0.691   ms/op
ClientGrpc.existUser                        avgt       3   2.890 ± 0.526   ms/op
ClientGrpc.getUser                          avgt       3   2.976 ± 0.182   ms/op
ClientGrpc.listUser                         avgt       3   3.836 ± 0.623   ms/op
ClientGrpc.createUser                     sample  323222   2.967 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.540           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.087           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.761           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.792           ms/op
ClientGrpc.existUser                      sample  327734   2.927 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.285           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.234           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.208           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.166           ms/op
ClientGrpc.getUser                        sample  323557   2.966 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.739           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.416           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.028           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.982           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.923           ms/op
ClientGrpc.listUser                       sample  246939   3.885 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.940           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.829           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.143           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.329           ms/op
