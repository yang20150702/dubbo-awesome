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
# Warmup Iteration   1: 4.246 ops/ms
# Warmup Iteration   2: 8.775 ops/ms
# Warmup Iteration   3: 9.940 ops/ms
Iteration   1: 10.242 ops/ms
Iteration   2: 10.072 ops/ms
Iteration   3: 9.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.102 ±(99.9%) 2.343 ops/ms [Average]
  (min, avg, max) = (9.991, 10.102, 10.242), stdev = 0.128
  CI (99.9%): [7.758, 12.445] (assumes normal distribution)


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
# Warmup Iteration   1: 7.237 ops/ms
# Warmup Iteration   2: 10.313 ops/ms
# Warmup Iteration   3: 10.625 ops/ms
Iteration   1: 10.465 ops/ms
Iteration   2: 10.679 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.619 ±(99.9%) 2.451 ops/ms [Average]
  (min, avg, max) = (10.465, 10.619, 10.713), stdev = 0.134
  CI (99.9%): [8.168, 13.070] (assumes normal distribution)


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
# Warmup Iteration   1: 6.680 ops/ms
# Warmup Iteration   2: 9.808 ops/ms
# Warmup Iteration   3: 9.968 ops/ms
Iteration   1: 10.096 ops/ms
Iteration   2: 9.996 ops/ms
Iteration   3: 10.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.049 ±(99.9%) 0.917 ops/ms [Average]
  (min, avg, max) = (9.996, 10.049, 10.096), stdev = 0.050
  CI (99.9%): [9.132, 10.966] (assumes normal distribution)


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
# Warmup Iteration   1: 5.530 ops/ms
# Warmup Iteration   2: 7.637 ops/ms
# Warmup Iteration   3: 7.901 ops/ms
Iteration   1: 8.083 ops/ms
Iteration   2: 8.010 ops/ms
Iteration   3: 8.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.039 ±(99.9%) 0.710 ops/ms [Average]
  (min, avg, max) = (8.010, 8.039, 8.083), stdev = 0.039
  CI (99.9%): [7.329, 8.748] (assumes normal distribution)


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
# Warmup Iteration   1: 4.298 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.002 ms/op
Iteration   1: 3.240 ±(99.9%) 0.010 ms/op
Iteration   2: 3.134 ±(99.9%) 0.002 ms/op
Iteration   3: 3.162 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.179 ±(99.9%) 1.008 ms/op [Average]
  (min, avg, max) = (3.134, 3.179, 3.240), stdev = 0.055
  CI (99.9%): [2.171, 4.186] (assumes normal distribution)


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.002 ms/op
Iteration   1: 2.972 ±(99.9%) 0.002 ms/op
Iteration   2: 2.975 ±(99.9%) 0.002 ms/op
Iteration   3: 3.001 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.982 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (2.972, 2.982, 3.001), stdev = 0.016
  CI (99.9%): [2.693, 3.272] (assumes normal distribution)


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.002 ms/op
Iteration   1: 3.207 ±(99.9%) 0.001 ms/op
Iteration   2: 3.198 ±(99.9%) 0.002 ms/op
Iteration   3: 3.157 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.187 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (3.157, 3.187, 3.207), stdev = 0.026
  CI (99.9%): [2.704, 3.670] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.344 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.042 ms/op
Iteration   1: 3.939 ±(99.9%) 0.007 ms/op
Iteration   2: 3.957 ±(99.9%) 0.008 ms/op
Iteration   3: 4.015 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.970 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (3.939, 3.970, 4.015), stdev = 0.040
  CI (99.9%): [3.242, 4.699] (assumes normal distribution)


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
Iteration   1: 3.240 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.607 ms/op
                 createUser·p0.9999: 13.156 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.031 ms/op
                 createUser·p0.9999: 18.802 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   3: 3.192 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  12.413 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301062
  mean =      3.187 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21924 
    [ 2.500,  5.000) = 278111 
    [ 5.000,  7.500) = 665 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.995 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 3.071 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  8.365 ms/op
                 existUser·p0.9999: 14.505 ms/op
                 existUser·p1.00:   15.729 ms/op

Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  9.391 ms/op
                 existUser·p0.9999: 14.866 ms/op
                 existUser·p1.00:   15.237 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.540 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316444
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 744 
    [ 1.250,  2.500) = 37874 
    [ 2.500,  3.750) = 254032 
    [ 3.750,  5.000) = 22700 
    [ 5.000,  6.250) = 396 
    [ 6.250,  7.500) = 342 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 86 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.816 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     18.072 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.007 ms/op
Iteration   1: 3.236 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.668 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.561 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   2: 3.185 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  6.924 ms/op
                 getUser·p0.9999: 19.707 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   3: 3.208 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   4.460 ms/op
                 getUser·p0.999:  6.956 ms/op
                 getUser·p0.9999: 23.003 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299262
  mean =      3.209 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19311 
    [ 2.500,  5.000) = 278727 
    [ 5.000,  7.500) = 898 
    [ 7.500, 10.000) = 100 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.674 ms/op
     p(99.9900) =     21.662 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 4.607 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.012 ms/op
Iteration   1: 4.036 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.156 ms/op
                 listUser·p0.9999: 16.513 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   2: 3.964 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  17.869 ms/op
                 listUser·p0.9999: 27.165 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   3: 4.013 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  15.640 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239627
  mean =      4.004 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3446 
    [ 2.500,  5.000) = 210330 
    [ 5.000,  7.500) = 24606 
    [ 7.500, 10.000) = 774 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.102 ± 2.343  ops/ms
ClientGrpc.existUser                       thrpt       3  10.619 ± 2.451  ops/ms
ClientGrpc.getUser                         thrpt       3  10.049 ± 0.917  ops/ms
ClientGrpc.listUser                        thrpt       3   8.039 ± 0.710  ops/ms
ClientGrpc.createUser                       avgt       3   3.179 ± 1.008   ms/op
ClientGrpc.existUser                        avgt       3   2.982 ± 0.290   ms/op
ClientGrpc.getUser                          avgt       3   3.187 ± 0.483   ms/op
ClientGrpc.listUser                         avgt       3   3.970 ± 0.728   ms/op
ClientGrpc.createUser                     sample  301062   3.187 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.675           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.150           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.995           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.480           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.135           ms/op
ClientGrpc.existUser                      sample  316444   3.033 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.672           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.816           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.302           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.153           ms/op
ClientGrpc.getUser                        sample  299262   3.209 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.668           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.903           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.674           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.662           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.429           ms/op
ClientGrpc.listUser                       sample  239627   4.004 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.041           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.673           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.967           ms/op
