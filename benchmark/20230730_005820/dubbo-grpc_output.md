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
# Warmup Iteration   1: 4.078 ops/ms
# Warmup Iteration   2: 9.041 ops/ms
# Warmup Iteration   3: 9.886 ops/ms
Iteration   1: 10.340 ops/ms
Iteration   2: 10.377 ops/ms
Iteration   3: 10.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.355 ±(99.9%) 0.352 ops/ms [Average]
  (min, avg, max) = (10.340, 10.355, 10.377), stdev = 0.019
  CI (99.9%): [10.003, 10.707] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.571 ops/ms
# Warmup Iteration   2: 10.507 ops/ms
# Warmup Iteration   3: 11.393 ops/ms
Iteration   1: 10.990 ops/ms
Iteration   2: 10.862 ops/ms
Iteration   3: 11.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.954 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (10.862, 10.954, 11.010), stdev = 0.080
  CI (99.9%): [9.493, 12.416] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.571 ops/ms
# Warmup Iteration   2: 9.729 ops/ms
# Warmup Iteration   3: 10.309 ops/ms
Iteration   1: 10.446 ops/ms
Iteration   2: 10.281 ops/ms
Iteration   3: 10.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.363 ±(99.9%) 1.510 ops/ms [Average]
  (min, avg, max) = (10.281, 10.363, 10.446), stdev = 0.083
  CI (99.9%): [8.853, 11.873] (assumes normal distribution)


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
# Warmup Iteration   1: 5.867 ops/ms
# Warmup Iteration   2: 7.478 ops/ms
# Warmup Iteration   3: 8.209 ops/ms
Iteration   1: 8.014 ops/ms
Iteration   2: 7.954 ops/ms
Iteration   3: 7.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.957 ±(99.9%) 1.005 ops/ms [Average]
  (min, avg, max) = (7.904, 7.957, 8.014), stdev = 0.055
  CI (99.9%): [6.952, 8.962] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.364 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.001 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 3.060 ±(99.9%) 0.003 ms/op
Iteration   3: 3.017 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.057 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.017, 3.057, 3.093), stdev = 0.038
  CI (99.9%): [2.358, 3.756] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.926 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.003 ms/op
Iteration   1: 2.887 ±(99.9%) 0.002 ms/op
Iteration   2: 2.932 ±(99.9%) 0.003 ms/op
Iteration   3: 2.984 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.935 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (2.887, 2.935, 2.984), stdev = 0.048
  CI (99.9%): [2.050, 3.819] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.428 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.002 ms/op
Iteration   1: 3.081 ±(99.9%) 0.003 ms/op
Iteration   2: 3.009 ±(99.9%) 0.004 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.047 ±(99.9%) 0.656 ms/op [Average]
  (min, avg, max) = (3.009, 3.047, 3.081), stdev = 0.036
  CI (99.9%): [2.391, 3.703] (assumes normal distribution)


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
# Warmup Iteration   1: 5.879 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.024 ms/op
Iteration   1: 4.037 ±(99.9%) 0.015 ms/op
Iteration   2: 3.962 ±(99.9%) 0.014 ms/op
Iteration   3: 3.952 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.983 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (3.952, 3.983, 4.037), stdev = 0.047
  CI (99.9%): [3.127, 4.840] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.501 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  7.457 ms/op
                 createUser·p0.9999: 15.834 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  8.780 ms/op
                 createUser·p0.9999: 23.874 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   3: 3.069 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.084 ms/op
                 createUser·p0.999:  8.143 ms/op
                 createUser·p0.9999: 16.789 ms/op
                 createUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313927
  mean =      3.056 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14566 
    [ 2.500,  5.000) = 298056 
    [ 5.000,  7.500) = 905 
    [ 7.500, 10.000) = 170 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.184 ms/op
     p(99.9900) =     22.571 ms/op
     p(99.9990) =     24.141 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.105 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.005 ms/op
Iteration   1: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  6.893 ms/op
                 existUser·p0.9999: 19.632 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   2: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.883 ms/op
                 existUser·p0.9999: 17.793 ms/op
                 existUser·p1.00:   18.973 ms/op

Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  7.175 ms/op
                 existUser·p0.9999: 19.929 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327987
  mean =      2.927 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31525 
    [ 2.500,  5.000) = 295493 
    [ 5.000,  7.500) = 708 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.922 ms/op
     p(99.9900) =     19.667 ms/op
     p(99.9990) =     20.265 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 4.512 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.008 ms/op
Iteration   1: 3.058 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  10.581 ms/op
                 getUser·p0.9999: 22.136 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  6.742 ms/op
                 getUser·p0.9999: 32.178 ms/op
                 getUser·p1.00:   32.506 ms/op

Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.053 ms/op
                 getUser·p0.9999: 22.053 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313677
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16033 
    [ 2.500,  5.000) = 296049 
    [ 5.000,  7.500) = 1312 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.225 ms/op
     p(99.9900) =     31.707 ms/op
     p(99.9990) =     32.361 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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
# Warmup Iteration   1: 5.789 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.011 ms/op
Iteration   1: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.769 ms/op
                 listUser·p0.9999: 21.304 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   2: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.073 ms/op
                 listUser·p0.999:  15.989 ms/op
                 listUser·p0.9999: 18.160 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 3.977 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.397 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238337
  mean =      4.025 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1730 
    [ 2.500,  5.000) = 212171 
    [ 5.000,  7.500) = 22911 
    [ 7.500, 10.000) = 1016 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     15.379 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     23.427 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.355 ± 0.352  ops/ms
ClientGrpc.existUser                       thrpt       3  10.954 ± 1.461  ops/ms
ClientGrpc.getUser                         thrpt       3  10.363 ± 1.510  ops/ms
ClientGrpc.listUser                        thrpt       3   7.957 ± 1.005  ops/ms
ClientGrpc.createUser                       avgt       3   3.057 ± 0.699   ms/op
ClientGrpc.existUser                        avgt       3   2.935 ± 0.884   ms/op
ClientGrpc.getUser                          avgt       3   3.047 ± 0.656   ms/op
ClientGrpc.listUser                         avgt       3   3.983 ± 0.857   ms/op
ClientGrpc.createUser                     sample  313927   3.056 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.783           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.184           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.571           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.183           ms/op
ClientGrpc.existUser                      sample  327987   2.927 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.553           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.922           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.667           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.103           ms/op
ClientGrpc.getUser                        sample  313677   3.060 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.787           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.225           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.707           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.506           ms/op
ClientGrpc.listUser                       sample  238337   4.025 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.031           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.379           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.939           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.527           ms/op
