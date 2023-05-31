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
# Warmup Iteration   1: 2.567 ops/ms
# Warmup Iteration   2: 5.879 ops/ms
# Warmup Iteration   3: 7.380 ops/ms
Iteration   1: 7.855 ops/ms
Iteration   2: 7.692 ops/ms
Iteration   3: 7.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.733 ±(99.9%) 1.964 ops/ms [Average]
  (min, avg, max) = (7.652, 7.733, 7.855), stdev = 0.108
  CI (99.9%): [5.769, 9.697] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.323 ops/ms
# Warmup Iteration   2: 7.416 ops/ms
# Warmup Iteration   3: 8.001 ops/ms
Iteration   1: 8.431 ops/ms
Iteration   2: 7.897 ops/ms
Iteration   3: 8.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.232 ±(99.9%) 5.318 ops/ms [Average]
  (min, avg, max) = (7.897, 8.232, 8.431), stdev = 0.291
  CI (99.9%): [2.914, 13.549] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.436 ops/ms
# Warmup Iteration   2: 6.732 ops/ms
# Warmup Iteration   3: 7.136 ops/ms
Iteration   1: 7.576 ops/ms
Iteration   2: 7.479 ops/ms
Iteration   3: 7.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.482 ±(99.9%) 1.672 ops/ms [Average]
  (min, avg, max) = (7.393, 7.482, 7.576), stdev = 0.092
  CI (99.9%): [5.810, 9.155] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.593 ops/ms
# Warmup Iteration   2: 5.243 ops/ms
# Warmup Iteration   3: 5.843 ops/ms
Iteration   1: 5.774 ops/ms
Iteration   2: 5.787 ops/ms
Iteration   3: 5.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.848 ±(99.9%) 2.118 ops/ms [Average]
  (min, avg, max) = (5.774, 5.848, 5.981), stdev = 0.116
  CI (99.9%): [3.729, 7.966] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.655 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.261 ±(99.9%) 0.017 ms/op
Iteration   1: 4.241 ±(99.9%) 0.007 ms/op
Iteration   2: 4.296 ±(99.9%) 0.002 ms/op
Iteration   3: 4.356 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.298 ±(99.9%) 1.042 ms/op [Average]
  (min, avg, max) = (4.241, 4.298, 4.356), stdev = 0.057
  CI (99.9%): [3.256, 5.339] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.283 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.003 ms/op
Iteration   1: 3.972 ±(99.9%) 0.005 ms/op
Iteration   2: 4.003 ±(99.9%) 0.002 ms/op
Iteration   3: 4.110 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.029 ±(99.9%) 1.324 ms/op [Average]
  (min, avg, max) = (3.972, 4.029, 4.110), stdev = 0.073
  CI (99.9%): [2.704, 5.353] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.490 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.565 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.417 ±(99.9%) 0.008 ms/op
Iteration   1: 4.211 ±(99.9%) 0.004 ms/op
Iteration   2: 4.264 ±(99.9%) 0.003 ms/op
Iteration   3: 4.235 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.237 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (4.211, 4.237, 4.264), stdev = 0.027
  CI (99.9%): [3.752, 4.721] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.915 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.859 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.461 ±(99.9%) 0.020 ms/op
Iteration   1: 5.375 ±(99.9%) 0.010 ms/op
Iteration   2: 5.540 ±(99.9%) 0.013 ms/op
Iteration   3: 5.407 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.441 ±(99.9%) 1.595 ms/op [Average]
  (min, avg, max) = (5.375, 5.441, 5.540), stdev = 0.087
  CI (99.9%): [3.846, 7.036] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.632 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.576 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.362 ±(99.9%) 0.012 ms/op
Iteration   1: 4.195 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   6.711 ms/op
                 createUser·p0.999:  12.693 ms/op
                 createUser·p0.9999: 29.590 ms/op
                 createUser·p1.00:   32.047 ms/op

Iteration   2: 4.212 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   4.129 ms/op
                 createUser·p0.90:   5.186 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  14.042 ms/op
                 createUser·p0.9999: 26.608 ms/op
                 createUser·p1.00:   27.787 ms/op

Iteration   3: 4.226 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   4.137 ms/op
                 createUser·p0.90:   5.136 ms/op
                 createUser·p0.95:   5.489 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  13.795 ms/op
                 createUser·p0.9999: 30.288 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227898
  mean =      4.211 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3519 
    [ 2.500,  5.000) = 194914 
    [ 5.000,  7.500) = 28432 
    [ 7.500, 10.000) = 620 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     29.039 ms/op
     p(99.9990) =     31.091 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.119 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.423 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.009 ms/op
Iteration   1: 3.944 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.061 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  14.395 ms/op
                 existUser·p0.9999: 21.553 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   2: 3.927 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   4.719 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  9.918 ms/op
                 existUser·p0.9999: 15.902 ms/op
                 existUser·p1.00:   18.973 ms/op

Iteration   3: 3.885 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  8.842 ms/op
                 existUser·p0.9999: 36.110 ms/op
                 existUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 244940
  mean =      3.919 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6811 
    [ 2.500,  5.000) = 224974 
    [ 5.000,  7.500) = 12173 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     35.717 ms/op
     p(99.9990) =     36.445 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.429 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.567 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.286 ±(99.9%) 0.011 ms/op
Iteration   1: 4.266 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.218 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  12.783 ms/op
                 getUser·p0.9999: 16.409 ms/op
                 getUser·p1.00:   16.630 ms/op

Iteration   2: 4.263 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.423 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.063 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   6.383 ms/op
                 getUser·p0.999:  9.303 ms/op
                 getUser·p0.9999: 16.875 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 4.343 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   5.562 ms/op
                 getUser·p0.99:   6.755 ms/op
                 getUser·p0.999:  10.148 ms/op
                 getUser·p0.9999: 21.046 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 223658
  mean =      4.290 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4026 
    [ 2.500,  5.000) = 188176 
    [ 5.000,  7.500) = 30277 
    [ 7.500, 10.000) = 928 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     20.423 ms/op
     p(99.9990) =     21.710 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 7.932 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.754 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.474 ±(99.9%) 0.017 ms/op
Iteration   1: 5.528 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.832 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  15.469 ms/op
                 listUser·p0.9999: 17.367 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 5.450 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   6.693 ms/op
                 listUser·p0.95:   7.673 ms/op
                 listUser·p0.99:   10.027 ms/op
                 listUser·p0.999:  18.099 ms/op
                 listUser·p0.9999: 21.644 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   3: 5.439 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   6.947 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  20.585 ms/op
                 listUser·p0.9999: 25.788 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175273
  mean =      5.472 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 117 
    [ 2.500,  5.000) = 63239 
    [ 5.000,  7.500) = 100858 
    [ 7.500, 10.000) = 9419 
    [10.000, 12.500) = 1096 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.823 ms/op
     p(99.0000) =      9.912 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     25.035 ms/op
     p(99.9990) =     26.303 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.733 ± 1.964  ops/ms
ClientGrpc.existUser                       thrpt       3   8.232 ± 5.318  ops/ms
ClientGrpc.getUser                         thrpt       3   7.482 ± 1.672  ops/ms
ClientGrpc.listUser                        thrpt       3   5.848 ± 2.118  ops/ms
ClientGrpc.createUser                       avgt       3   4.298 ± 1.042   ms/op
ClientGrpc.existUser                        avgt       3   4.029 ± 1.324   ms/op
ClientGrpc.getUser                          avgt       3   4.237 ± 0.484   ms/op
ClientGrpc.listUser                         avgt       3   5.441 ± 1.595   ms/op
ClientGrpc.createUser                     sample  227898   4.211 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.016           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.153           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.398           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.779           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.039           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.047           ms/op
ClientGrpc.existUser                      sample  244940   3.919 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.925           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.038           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.054           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.223           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          35.717           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.504           ms/op
ClientGrpc.getUser                        sample  223658   4.290 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.057           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.177           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.619           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.240           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.423           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.101           ms/op
ClientGrpc.listUser                       sample  175273   5.472 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.405           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.823           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.912           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.035           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.771           ms/op
