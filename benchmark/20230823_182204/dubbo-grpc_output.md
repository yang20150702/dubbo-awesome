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
# Warmup Iteration   1: 4.339 ops/ms
# Warmup Iteration   2: 8.818 ops/ms
# Warmup Iteration   3: 10.145 ops/ms
Iteration   1: 10.879 ops/ms
Iteration   2: 10.375 ops/ms
Iteration   3: 10.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.687 ±(99.9%) 4.965 ops/ms [Average]
  (min, avg, max) = (10.375, 10.687, 10.879), stdev = 0.272
  CI (99.9%): [5.722, 15.652] (assumes normal distribution)


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
# Warmup Iteration   1: 7.243 ops/ms
# Warmup Iteration   2: 10.507 ops/ms
# Warmup Iteration   3: 10.996 ops/ms
Iteration   1: 11.276 ops/ms
Iteration   2: 11.216 ops/ms
Iteration   3: 11.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.166 ±(99.9%) 2.579 ops/ms [Average]
  (min, avg, max) = (11.007, 11.166, 11.276), stdev = 0.141
  CI (99.9%): [8.587, 13.745] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.233 ops/ms
# Warmup Iteration   2: 10.373 ops/ms
# Warmup Iteration   3: 10.660 ops/ms
Iteration   1: 10.509 ops/ms
Iteration   2: 10.650 ops/ms
Iteration   3: 10.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.602 ±(99.9%) 1.462 ops/ms [Average]
  (min, avg, max) = (10.509, 10.602, 10.650), stdev = 0.080
  CI (99.9%): [9.140, 12.064] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.794 ops/ms
# Warmup Iteration   2: 7.900 ops/ms
# Warmup Iteration   3: 8.042 ops/ms
Iteration   1: 8.162 ops/ms
Iteration   2: 8.261 ops/ms
Iteration   3: 8.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.227 ±(99.9%) 1.024 ops/ms [Average]
  (min, avg, max) = (8.162, 8.227, 8.261), stdev = 0.056
  CI (99.9%): [7.202, 9.251] (assumes normal distribution)


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.004 ms/op
Iteration   1: 3.091 ±(99.9%) 0.003 ms/op
Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
Iteration   3: 3.014 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.042 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (3.014, 3.042, 3.091), stdev = 0.043
  CI (99.9%): [2.267, 3.818] (assumes normal distribution)


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.003 ms/op
Iteration   1: 2.944 ±(99.9%) 0.003 ms/op
Iteration   2: 2.875 ±(99.9%) 0.004 ms/op
Iteration   3: 2.854 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (2.854, 2.891, 2.944), stdev = 0.047
  CI (99.9%): [2.029, 3.754] (assumes normal distribution)


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
Iteration   3: 2.984 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.006 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.984, 3.006, 3.027), stdev = 0.021
  CI (99.9%): [2.620, 3.392] (assumes normal distribution)


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
# Warmup Iteration   1: 5.607 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.021 ms/op
Iteration   1: 3.923 ±(99.9%) 0.013 ms/op
Iteration   2: 3.854 ±(99.9%) 0.012 ms/op
Iteration   3: 3.928 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.902 ±(99.9%) 0.758 ms/op [Average]
  (min, avg, max) = (3.854, 3.902, 3.928), stdev = 0.042
  CI (99.9%): [3.144, 4.660] (assumes normal distribution)


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.573 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  8.289 ms/op
                 createUser·p0.9999: 13.637 ms/op
                 createUser·p1.00:   13.828 ms/op

Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.471 ms/op
                 createUser·p0.9999: 15.602 ms/op
                 createUser·p1.00:   15.942 ms/op

Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.540 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  10.387 ms/op
                 createUser·p0.9999: 19.466 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316241
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24104 
    [ 2.500,  5.000) = 290165 
    [ 5.000,  7.500) = 1496 
    [ 7.500, 10.000) = 204 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      8.434 ms/op
     p(99.9900) =     18.235 ms/op
     p(99.9990) =     19.973 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
Iteration   1: 2.855 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.617 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.422 ms/op
                 existUser·p0.9999: 16.364 ms/op
                 existUser·p1.00:   16.548 ms/op

Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 16.404 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.135 ms/op
                 existUser·p0.9999: 15.819 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327121
  mean =      2.934 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2672 
    [ 1.250,  2.500) = 36136 
    [ 2.500,  3.750) = 276123 
    [ 3.750,  5.000) = 10451 
    [ 5.000,  6.250) = 874 
    [ 6.250,  7.500) = 386 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     16.307 ms/op
     p(99.9990) =     17.906 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.183 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.550 ms/op
                 getUser·p0.9999: 14.034 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.384 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.489 ms/op
                 getUser·p0.9999: 14.294 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   3: 3.104 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 30.835 ms/op
                 getUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310032
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19632 
    [ 2.500,  5.000) = 288378 
    [ 5.000,  7.500) = 1337 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.384 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     29.491 ms/op
     p(99.9990) =     31.054 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 5.520 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.013 ms/op
Iteration   1: 3.996 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  16.033 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 4.004 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.300 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 26.280 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 4.034 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.296 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 22.940 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239388
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4244 
    [ 2.500,  5.000) = 205869 
    [ 5.000,  7.500) = 27032 
    [ 7.500, 10.000) = 1687 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.296 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     25.203 ms/op
     p(99.9990) =     26.634 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.687 ± 4.965  ops/ms
ClientGrpc.existUser                       thrpt       3  11.166 ± 2.579  ops/ms
ClientGrpc.getUser                         thrpt       3  10.602 ± 1.462  ops/ms
ClientGrpc.listUser                        thrpt       3   8.227 ± 1.024  ops/ms
ClientGrpc.createUser                       avgt       3   3.042 ± 0.775   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 0.863   ms/op
ClientGrpc.getUser                          avgt       3   3.006 ± 0.386   ms/op
ClientGrpc.listUser                         avgt       3   3.902 ± 0.758   ms/op
ClientGrpc.createUser                     sample  316241   3.035 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.540           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.434           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.235           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.414           ms/op
ClientGrpc.existUser                      sample  327121   2.934 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.617           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.487           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.307           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.022           ms/op
ClientGrpc.getUser                        sample  310032   3.094 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.384           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.503           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.491           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.130           ms/op
ClientGrpc.listUser                       sample  239388   4.011 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.296           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.422           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.073           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.203           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.001           ms/op
