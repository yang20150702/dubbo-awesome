# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.150 ops/ms
# Warmup Iteration   2: 9.307 ops/ms
# Warmup Iteration   3: 10.214 ops/ms
Iteration   1: 10.232 ops/ms
Iteration   2: 9.909 ops/ms
Iteration   3: 10.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.093 ±(99.9%) 3.034 ops/ms [Average]
  (min, avg, max) = (9.909, 10.093, 10.232), stdev = 0.166
  CI (99.9%): [7.059, 13.127] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.257 ops/ms
# Warmup Iteration   2: 10.281 ops/ms
# Warmup Iteration   3: 10.428 ops/ms
Iteration   1: 10.781 ops/ms
Iteration   2: 10.771 ops/ms
Iteration   3: 11.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.862 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (10.771, 10.862, 11.034), stdev = 0.149
  CI (99.9%): [8.142, 13.581] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.299 ops/ms
# Warmup Iteration   2: 10.306 ops/ms
# Warmup Iteration   3: 10.537 ops/ms
Iteration   1: 10.449 ops/ms
Iteration   2: 10.223 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.400 ±(99.9%) 2.903 ops/ms [Average]
  (min, avg, max) = (10.223, 10.400, 10.529), stdev = 0.159
  CI (99.9%): [7.498, 13.303] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.350 ops/ms
# Warmup Iteration   2: 7.644 ops/ms
# Warmup Iteration   3: 8.285 ops/ms
Iteration   1: 8.246 ops/ms
Iteration   2: 7.958 ops/ms
Iteration   3: 8.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.134 ±(99.9%) 2.813 ops/ms [Average]
  (min, avg, max) = (7.958, 8.134, 8.246), stdev = 0.154
  CI (99.9%): [5.321, 10.947] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.309 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.009 ms/op
Iteration   1: 3.148 ±(99.9%) 0.003 ms/op
Iteration   2: 3.145 ±(99.9%) 0.002 ms/op
Iteration   3: 3.196 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.163 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.145, 3.163, 3.196), stdev = 0.029
  CI (99.9%): [2.642, 3.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.091 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 2.993 ±(99.9%) 0.002 ms/op
Iteration   2: 2.863 ±(99.9%) 0.002 ms/op
Iteration   3: 2.999 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.952 ±(99.9%) 1.410 ms/op [Average]
  (min, avg, max) = (2.863, 2.952, 2.999), stdev = 0.077
  CI (99.9%): [1.542, 4.362] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.300 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.004 ms/op
Iteration   1: 3.108 ±(99.9%) 0.002 ms/op
Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
Iteration   3: 3.048 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.082 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (3.048, 3.082, 3.108), stdev = 0.031
  CI (99.9%): [2.519, 3.644] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.962 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
Iteration   1: 3.919 ±(99.9%) 0.017 ms/op
Iteration   2: 4.058 ±(99.9%) 0.030 ms/op
Iteration   3: 3.884 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.954 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (3.884, 3.954, 4.058), stdev = 0.092
  CI (99.9%): [2.274, 5.633] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.360 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
Iteration   1: 3.200 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  6.997 ms/op
                 createUser·p0.9999: 13.452 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.987 ms/op
                 createUser·p0.9999: 14.441 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  10.084 ms/op
                 createUser·p0.9999: 17.389 ms/op
                 createUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308960
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 327 
    [ 1.250,  2.500) = 41077 
    [ 2.500,  3.750) = 230658 
    [ 3.750,  5.000) = 35591 
    [ 5.000,  6.250) = 558 
    [ 6.250,  7.500) = 296 
    [ 7.500,  8.750) = 160 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 68 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.455 ms/op
     p(99.9900) =     16.096 ms/op
     p(99.9990) =     17.561 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.721 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
Iteration   1: 2.920 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  9.022 ms/op
                 existUser·p0.9999: 18.317 ms/op
                 existUser·p1.00:   18.547 ms/op

Iteration   2: 2.957 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.257 ms/op
                 existUser·p0.9999: 15.568 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   3: 2.936 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.454 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  8.978 ms/op
                 existUser·p0.9999: 18.487 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326911
  mean =      2.937 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1580 
    [ 1.250,  2.500) = 69290 
    [ 2.500,  3.750) = 231787 
    [ 3.750,  5.000) = 23200 
    [ 5.000,  6.250) = 452 
    [ 6.250,  7.500) = 226 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     18.964 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.238 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 17.498 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.866 ms/op
                 getUser·p0.9999: 20.939 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  6.473 ms/op
                 getUser·p0.9999: 18.303 ms/op
                 getUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313844
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48679 
    [ 2.500,  5.000) = 264056 
    [ 5.000,  7.500) = 836 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.105 ms/op
     p(99.9900) =     19.240 ms/op
     p(99.9990) =     21.098 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.594 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
Iteration   1: 3.905 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.960 ms/op
                 listUser·p0.999:  14.126 ms/op
                 listUser·p0.9999: 20.172 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 3.917 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  16.056 ms/op
                 listUser·p0.9999: 19.402 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 3.927 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.978 ms/op
                 listUser·p0.999:  17.107 ms/op
                 listUser·p0.9999: 22.577 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245034
  mean =      3.916 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3572 
    [ 2.500,  5.000) = 218081 
    [ 5.000,  7.500) = 21874 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     22.069 ms/op
     p(99.9990) =     22.661 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.093 ± 3.034  ops/ms
ClientGrpc.existUser                       thrpt       3  10.862 ± 2.720  ops/ms
ClientGrpc.getUser                         thrpt       3  10.400 ± 2.903  ops/ms
ClientGrpc.listUser                        thrpt       3   8.134 ± 2.813  ops/ms
ClientGrpc.createUser                       avgt       3   3.163 ± 0.521   ms/op
ClientGrpc.existUser                        avgt       3   2.952 ± 1.410   ms/op
ClientGrpc.getUser                          avgt       3   3.082 ± 0.562   ms/op
ClientGrpc.listUser                         avgt       3   3.954 ± 1.680   ms/op
ClientGrpc.createUser                     sample  308960   3.107 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.577           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.455           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.096           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.695           ms/op
ClientGrpc.existUser                      sample  326911   2.937 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.454           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.875           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.733           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.219           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.973           ms/op
ClientGrpc.getUser                        sample  313844   3.058 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.625           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.105           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.240           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.594           ms/op
ClientGrpc.listUser                       sample  245034   3.916 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.781           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.647           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.069           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.774           ms/op
