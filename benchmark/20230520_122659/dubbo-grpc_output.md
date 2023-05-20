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
# Warmup Iteration   1: 4.295 ops/ms
# Warmup Iteration   2: 9.162 ops/ms
# Warmup Iteration   3: 10.031 ops/ms
Iteration   1: 10.506 ops/ms
Iteration   2: 10.537 ops/ms
Iteration   3: 10.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.520 ±(99.9%) 0.286 ops/ms [Average]
  (min, avg, max) = (10.506, 10.520, 10.537), stdev = 0.016
  CI (99.9%): [10.233, 10.806] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.760 ops/ms
# Warmup Iteration   2: 10.434 ops/ms
# Warmup Iteration   3: 11.103 ops/ms
Iteration   1: 11.187 ops/ms
Iteration   2: 11.145 ops/ms
Iteration   3: 11.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.242 ±(99.9%) 2.421 ops/ms [Average]
  (min, avg, max) = (11.145, 11.242, 11.393), stdev = 0.133
  CI (99.9%): [8.821, 13.663] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.648 ops/ms
# Warmup Iteration   2: 10.328 ops/ms
# Warmup Iteration   3: 10.529 ops/ms
Iteration   1: 10.700 ops/ms
Iteration   2: 10.635 ops/ms
Iteration   3: 10.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.613 ±(99.9%) 1.810 ops/ms [Average]
  (min, avg, max) = (10.505, 10.613, 10.700), stdev = 0.099
  CI (99.9%): [8.804, 12.423] (assumes normal distribution)


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
# Warmup Iteration   1: 5.356 ops/ms
# Warmup Iteration   2: 7.863 ops/ms
# Warmup Iteration   3: 7.967 ops/ms
Iteration   1: 8.187 ops/ms
Iteration   2: 8.262 ops/ms
Iteration   3: 8.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.250 ±(99.9%) 1.048 ops/ms [Average]
  (min, avg, max) = (8.187, 8.250, 8.300), stdev = 0.057
  CI (99.9%): [7.201, 9.298] (assumes normal distribution)


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
# Warmup Iteration   1: 4.057 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.002 ms/op
Iteration   1: 2.968 ±(99.9%) 0.003 ms/op
Iteration   2: 2.976 ±(99.9%) 0.003 ms/op
Iteration   3: 2.999 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.981 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.968, 2.981, 2.999), stdev = 0.016
  CI (99.9%): [2.689, 3.273] (assumes normal distribution)


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.002 ms/op
Iteration   1: 2.867 ±(99.9%) 0.003 ms/op
Iteration   2: 2.827 ±(99.9%) 0.002 ms/op
Iteration   3: 2.853 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.849 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (2.827, 2.849, 2.867), stdev = 0.020
  CI (99.9%): [2.478, 3.219] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.003 ms/op
Iteration   1: 2.980 ±(99.9%) 0.003 ms/op
Iteration   2: 2.987 ±(99.9%) 0.003 ms/op
Iteration   3: 2.992 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.986 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (2.980, 2.986, 2.992), stdev = 0.006
  CI (99.9%): [2.870, 3.102] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.354 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.016 ms/op
Iteration   1: 3.980 ±(99.9%) 0.030 ms/op
Iteration   2: 3.883 ±(99.9%) 0.013 ms/op
Iteration   3: 3.922 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.928 ±(99.9%) 0.892 ms/op [Average]
  (min, avg, max) = (3.883, 3.928, 3.980), stdev = 0.049
  CI (99.9%): [3.036, 4.820] (assumes normal distribution)


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  9.979 ms/op
                 createUser·p0.9999: 12.313 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.482 ms/op
                 createUser·p0.9999: 20.906 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   3: 2.977 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  8.038 ms/op
                 createUser·p0.9999: 24.216 ms/op
                 createUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319307
  mean =      3.009 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28493 
    [ 2.500,  5.000) = 289284 
    [ 5.000,  7.500) = 1200 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.603 ms/op
     p(99.9900) =     21.806 ms/op
     p(99.9990) =     24.602 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 3.772 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.006 ms/op
Iteration   1: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  6.215 ms/op
                 existUser·p0.9999: 13.255 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   2: 2.900 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 13.959 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   3: 2.922 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  7.107 ms/op
                 existUser·p0.9999: 15.483 ms/op
                 existUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329771
  mean =      2.911 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 976 
    [ 1.250,  2.500) = 40276 
    [ 2.500,  3.750) = 279363 
    [ 3.750,  5.000) = 8433 
    [ 5.000,  6.250) = 309 
    [ 6.250,  7.500) = 199 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      6.637 ms/op
     p(99.9900) =     14.928 ms/op
     p(99.9990) =     16.079 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 4.276 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  7.606 ms/op
                 getUser·p0.9999: 13.152 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   2: 3.033 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.565 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.676 ms/op
                 getUser·p0.9999: 14.276 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  9.204 ms/op
                 getUser·p0.9999: 16.630 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319253
  mean =      3.007 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 346 
    [ 1.250,  2.500) = 22360 
    [ 2.500,  3.750) = 282860 
    [ 3.750,  5.000) = 12217 
    [ 5.000,  6.250) = 733 
    [ 6.250,  7.500) = 291 
    [ 7.500,  8.750) = 173 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     15.732 ms/op
     p(99.9990) =     17.590 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 5.223 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
Iteration   1: 3.966 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.539 ms/op
                 listUser·p0.9999: 21.037 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   2: 3.891 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 15.629 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 4.020 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.999 ms/op
                 listUser·p0.9999: 18.679 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242622
  mean =      3.958 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3397 
    [ 2.500,  5.000) = 213232 
    [ 5.000,  7.500) = 24797 
    [ 7.500, 10.000) = 834 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     20.439 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.520 ± 0.286  ops/ms
ClientGrpc.existUser                       thrpt       3  11.242 ± 2.421  ops/ms
ClientGrpc.getUser                         thrpt       3  10.613 ± 1.810  ops/ms
ClientGrpc.listUser                        thrpt       3   8.250 ± 1.048  ops/ms
ClientGrpc.createUser                       avgt       3   2.981 ± 0.292   ms/op
ClientGrpc.existUser                        avgt       3   2.849 ± 0.370   ms/op
ClientGrpc.getUser                          avgt       3   2.986 ± 0.116   ms/op
ClientGrpc.listUser                         avgt       3   3.928 ± 0.892   ms/op
ClientGrpc.createUser                     sample  319307   3.009 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.603           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.806           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.002           ms/op
ClientGrpc.existUser                      sample  329771   2.911 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.565           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.637           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.928           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.302           ms/op
ClientGrpc.getUser                        sample  319253   3.007 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.565           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.176           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.732           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.891           ms/op
ClientGrpc.listUser                       sample  242622   3.958 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.963           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.582           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.439           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.365           ms/op
