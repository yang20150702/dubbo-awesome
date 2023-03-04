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
# Warmup Iteration   1: 4.867 ops/ms
# Warmup Iteration   2: 9.755 ops/ms
# Warmup Iteration   3: 10.749 ops/ms
Iteration   1: 11.074 ops/ms
Iteration   2: 11.008 ops/ms
Iteration   3: 10.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.941 ±(99.9%) 3.205 ops/ms [Average]
  (min, avg, max) = (10.742, 10.941, 11.074), stdev = 0.176
  CI (99.9%): [7.737, 14.146] (assumes normal distribution)


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
# Warmup Iteration   1: 8.424 ops/ms
# Warmup Iteration   2: 11.484 ops/ms
# Warmup Iteration   3: 11.294 ops/ms
Iteration   1: 11.117 ops/ms
Iteration   2: 11.682 ops/ms
Iteration   3: 11.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.433 ±(99.9%) 5.257 ops/ms [Average]
  (min, avg, max) = (11.117, 11.433, 11.682), stdev = 0.288
  CI (99.9%): [6.176, 16.690] (assumes normal distribution)


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
# Warmup Iteration   1: 7.965 ops/ms
# Warmup Iteration   2: 10.586 ops/ms
# Warmup Iteration   3: 10.803 ops/ms
Iteration   1: 10.545 ops/ms
Iteration   2: 10.499 ops/ms
Iteration   3: 10.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.543 ±(99.9%) 0.790 ops/ms [Average]
  (min, avg, max) = (10.499, 10.543, 10.585), stdev = 0.043
  CI (99.9%): [9.753, 11.333] (assumes normal distribution)


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
# Warmup Iteration   1: 7.629 ops/ms
# Warmup Iteration   2: 7.876 ops/ms
# Warmup Iteration   3: 8.005 ops/ms
Iteration   1: 8.027 ops/ms
Iteration   2: 8.032 ops/ms
Iteration   3: 8.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.113 ±(99.9%) 2.623 ops/ms [Average]
  (min, avg, max) = (8.027, 8.113, 8.279), stdev = 0.144
  CI (99.9%): [5.489, 10.736] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.002 ms/op
Iteration   2: 2.954 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.977 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (2.954, 2.977, 3.000), stdev = 0.023
  CI (99.9%): [2.563, 3.390] (assumes normal distribution)


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.002 ms/op
Iteration   1: 2.863 ±(99.9%) 0.002 ms/op
Iteration   2: 2.800 ±(99.9%) 0.002 ms/op
Iteration   3: 2.914 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.859 ±(99.9%) 1.045 ms/op [Average]
  (min, avg, max) = (2.800, 2.859, 2.914), stdev = 0.057
  CI (99.9%): [1.814, 3.904] (assumes normal distribution)


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.002 ms/op
Iteration   1: 2.941 ±(99.9%) 0.002 ms/op
Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
Iteration   3: 2.942 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.963 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (2.941, 2.963, 3.007), stdev = 0.038
  CI (99.9%): [2.276, 3.651] (assumes normal distribution)


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.010 ms/op
Iteration   1: 4.085 ±(99.9%) 0.039 ms/op
Iteration   2: 3.866 ±(99.9%) 0.025 ms/op
Iteration   3: 3.848 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.933 ±(99.9%) 2.401 ms/op [Average]
  (min, avg, max) = (3.848, 3.933, 4.085), stdev = 0.132
  CI (99.9%): [1.532, 6.334] (assumes normal distribution)


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.047 ms/op
                 createUser·p0.999:  5.626 ms/op
                 createUser·p0.9999: 11.363 ms/op
                 createUser·p1.00:   11.616 ms/op

Iteration   2: 3.096 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  9.383 ms/op
                 createUser·p0.9999: 21.256 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  13.342 ms/op
                 createUser·p0.9999: 18.345 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316441
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40104 
    [ 2.500,  5.000) = 275452 
    [ 5.000,  7.500) = 446 
    [ 7.500, 10.000) = 193 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      8.889 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     21.649 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 2.912 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.851 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  6.335 ms/op
                 existUser·p0.9999: 11.682 ms/op
                 existUser·p1.00:   11.960 ms/op

Iteration   2: 2.816 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.427 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  7.424 ms/op
                 existUser·p0.9999: 24.388 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   3: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  5.243 ms/op
                 existUser·p0.9999: 18.121 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332200
  mean =      2.889 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60682 
    [ 2.500,  5.000) = 270781 
    [ 5.000,  7.500) = 534 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.427 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.026 ms/op
     p(99.9000) =      6.390 ms/op
     p(99.9900) =     18.401 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 3.521 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.007 ms/op
Iteration   1: 2.927 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  8.047 ms/op
                 getUser·p0.9999: 11.994 ms/op
                 getUser·p1.00:   12.288 ms/op

Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  7.661 ms/op
                 getUser·p0.9999: 15.262 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.092 ms/op
                 getUser·p0.999:  9.209 ms/op
                 getUser·p0.9999: 14.651 ms/op
                 getUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323608
  mean =      2.964 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1401 
    [ 1.250,  2.500) = 42044 
    [ 2.500,  3.750) = 264623 
    [ 3.750,  5.000) = 14437 
    [ 5.000,  6.250) = 431 
    [ 6.250,  7.500) = 279 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      8.118 ms/op
     p(99.9900) =     14.422 ms/op
     p(99.9990) =     15.803 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.012 ms/op
Iteration   1: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.681 ms/op
                 listUser·p0.9999: 19.881 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 3.938 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  18.601 ms/op
                 listUser·p0.9999: 23.809 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 3.850 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  16.037 ms/op
                 listUser·p0.9999: 19.159 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245908
  mean =      3.905 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4668 
    [ 2.500,  5.000) = 215810 
    [ 5.000,  7.500) = 24239 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     15.916 ms/op
     p(99.9900) =     22.945 ms/op
     p(99.9990) =     24.120 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.941 ± 3.205  ops/ms
ClientGrpc.existUser                       thrpt       3  11.433 ± 5.257  ops/ms
ClientGrpc.getUser                         thrpt       3  10.543 ± 0.790  ops/ms
ClientGrpc.listUser                        thrpt       3   8.113 ± 2.623  ops/ms
ClientGrpc.createUser                       avgt       3   2.977 ± 0.414   ms/op
ClientGrpc.existUser                        avgt       3   2.859 ± 1.045   ms/op
ClientGrpc.getUser                          avgt       3   2.963 ± 0.688   ms/op
ClientGrpc.listUser                         avgt       3   3.933 ± 2.401   ms/op
ClientGrpc.createUser                     sample  316441   3.031 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.604           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.889           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.349           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.725           ms/op
ClientGrpc.existUser                      sample  332200   2.889 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.427           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.390           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.401           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.904           ms/op
ClientGrpc.getUser                        sample  323608   2.964 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.729           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.129           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.118           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.422           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.204           ms/op
ClientGrpc.listUser                       sample  245908   3.905 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.892           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.916           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.945           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
