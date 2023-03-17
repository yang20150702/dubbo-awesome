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
# Warmup Iteration   1: 4.269 ops/ms
# Warmup Iteration   2: 9.389 ops/ms
# Warmup Iteration   3: 10.372 ops/ms
Iteration   1: 10.638 ops/ms
Iteration   2: 10.622 ops/ms
Iteration   3: 10.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.638 ±(99.9%) 0.300 ops/ms [Average]
  (min, avg, max) = (10.622, 10.638, 10.655), stdev = 0.016
  CI (99.9%): [10.339, 10.938] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.249 ops/ms
# Warmup Iteration   2: 10.513 ops/ms
# Warmup Iteration   3: 11.133 ops/ms
Iteration   1: 10.875 ops/ms
Iteration   2: 11.192 ops/ms
Iteration   3: 11.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.056 ±(99.9%) 2.984 ops/ms [Average]
  (min, avg, max) = (10.875, 11.056, 11.192), stdev = 0.164
  CI (99.9%): [8.072, 14.040] (assumes normal distribution)


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
# Warmup Iteration   1: 6.300 ops/ms
# Warmup Iteration   2: 9.919 ops/ms
# Warmup Iteration   3: 10.614 ops/ms
Iteration   1: 10.487 ops/ms
Iteration   2: 10.761 ops/ms
Iteration   3: 10.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.600 ±(99.9%) 2.613 ops/ms [Average]
  (min, avg, max) = (10.487, 10.600, 10.761), stdev = 0.143
  CI (99.9%): [7.987, 13.213] (assumes normal distribution)


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
# Warmup Iteration   1: 5.386 ops/ms
# Warmup Iteration   2: 7.602 ops/ms
# Warmup Iteration   3: 7.989 ops/ms
Iteration   1: 8.073 ops/ms
Iteration   2: 7.859 ops/ms
Iteration   3: 7.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.902 ±(99.9%) 2.815 ops/ms [Average]
  (min, avg, max) = (7.773, 7.902, 8.073), stdev = 0.154
  CI (99.9%): [5.086, 10.717] (assumes normal distribution)


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
# Warmup Iteration   1: 4.467 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.002 ms/op
Iteration   1: 3.171 ±(99.9%) 0.010 ms/op
Iteration   2: 3.037 ±(99.9%) 0.002 ms/op
Iteration   3: 3.035 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.081 ±(99.9%) 1.425 ms/op [Average]
  (min, avg, max) = (3.035, 3.081, 3.171), stdev = 0.078
  CI (99.9%): [1.656, 4.506] (assumes normal distribution)


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.003 ms/op
Iteration   1: 2.983 ±(99.9%) 0.002 ms/op
Iteration   2: 2.889 ±(99.9%) 0.003 ms/op
Iteration   3: 2.870 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 1.102 ms/op [Average]
  (min, avg, max) = (2.870, 2.914, 2.983), stdev = 0.060
  CI (99.9%): [1.812, 4.016] (assumes normal distribution)


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.003 ms/op
Iteration   1: 3.012 ±(99.9%) 0.003 ms/op
Iteration   2: 3.060 ±(99.9%) 0.003 ms/op
Iteration   3: 3.072 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.048 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.012, 3.048, 3.072), stdev = 0.032
  CI (99.9%): [2.469, 3.627] (assumes normal distribution)


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
# Warmup Iteration   1: 4.806 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.012 ms/op
Iteration   1: 3.916 ±(99.9%) 0.033 ms/op
Iteration   2: 3.958 ±(99.9%) 0.020 ms/op
Iteration   3: 3.866 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.913 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (3.866, 3.913, 3.958), stdev = 0.046
  CI (99.9%): [3.074, 4.753] (assumes normal distribution)


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.008 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.328 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.366 ms/op
                 createUser·p0.9999: 13.266 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.086 ms/op
                 createUser·p0.9999: 20.860 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  10.748 ms/op
                 createUser·p0.9999: 15.787 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320506
  mean =      2.996 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22599 
    [ 2.500,  5.000) = 296616 
    [ 5.000,  7.500) = 913 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.328 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.327 ms/op
     p(99.9900) =     20.106 ms/op
     p(99.9990) =     21.063 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.005 ms/op
Iteration   1: 2.901 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.290 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  6.785 ms/op
                 existUser·p0.9999: 13.909 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.932 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  5.774 ms/op
                 existUser·p0.9999: 14.226 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   3: 2.910 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.276 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  6.824 ms/op
                 existUser·p0.9999: 16.056 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329627
  mean =      2.914 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1147 
    [ 1.250,  2.500) = 34627 
    [ 2.500,  3.750) = 286179 
    [ 3.750,  5.000) = 6868 
    [ 5.000,  6.250) = 450 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.276 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =      6.347 ms/op
     p(99.9900) =     15.499 ms/op
     p(99.9990) =     16.540 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.107 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.056 ms/op
                 getUser·p0.9999: 13.418 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  13.006 ms/op
                 getUser·p0.9999: 21.151 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.515 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.486 ms/op
                 getUser·p0.9999: 16.810 ms/op
                 getUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315664
  mean =      3.040 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21767 
    [ 2.500,  5.000) = 292384 
    [ 5.000,  7.500) = 1105 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.020 ms/op
     p(99.9900) =     18.463 ms/op
     p(99.9990) =     21.332 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.894 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.011 ms/op
Iteration   1: 3.906 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  15.436 ms/op
                 listUser·p0.9999: 17.912 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   2: 3.926 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.715 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 16.704 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   3: 3.968 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  17.937 ms/op
                 listUser·p0.9999: 20.206 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244075
  mean =      3.933 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2408 
    [ 2.500,  5.000) = 221475 
    [ 5.000,  7.500) = 19005 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     15.087 ms/op
     p(99.9900) =     19.405 ms/op
     p(99.9990) =     20.713 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.638 ± 0.300  ops/ms
ClientGrpc.existUser                       thrpt       3  11.056 ± 2.984  ops/ms
ClientGrpc.getUser                         thrpt       3  10.600 ± 2.613  ops/ms
ClientGrpc.listUser                        thrpt       3   7.902 ± 2.815  ops/ms
ClientGrpc.createUser                       avgt       3   3.081 ± 1.425   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ± 1.102   ms/op
ClientGrpc.getUser                          avgt       3   3.048 ± 0.579   ms/op
ClientGrpc.listUser                         avgt       3   3.913 ± 0.839   ms/op
ClientGrpc.createUser                     sample  320506   2.996 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.328           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.445           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.327           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.106           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.593           ms/op
ClientGrpc.existUser                      sample  329627   2.914 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.276           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.347           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.499           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.465           ms/op
ClientGrpc.getUser                        sample  315664   3.040 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.515           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.020           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.463           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.053           ms/op
ClientGrpc.listUser                       sample  244075   3.933 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.938           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.087           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.405           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.775           ms/op
