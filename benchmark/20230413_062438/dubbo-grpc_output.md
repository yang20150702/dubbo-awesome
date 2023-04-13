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
# Warmup Iteration   1: 3.404 ops/ms
# Warmup Iteration   2: 7.500 ops/ms
# Warmup Iteration   3: 9.226 ops/ms
Iteration   1: 9.421 ops/ms
Iteration   2: 9.303 ops/ms
Iteration   3: 9.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.312 ±(99.9%) 1.914 ops/ms [Average]
  (min, avg, max) = (9.212, 9.312, 9.421), stdev = 0.105
  CI (99.9%): [7.398, 11.226] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.522 ops/ms
# Warmup Iteration   2: 9.248 ops/ms
# Warmup Iteration   3: 9.884 ops/ms
Iteration   1: 10.134 ops/ms
Iteration   2: 9.885 ops/ms
Iteration   3: 9.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.961 ±(99.9%) 2.742 ops/ms [Average]
  (min, avg, max) = (9.863, 9.961, 10.134), stdev = 0.150
  CI (99.9%): [7.219, 12.702] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.207 ops/ms
# Warmup Iteration   2: 8.819 ops/ms
# Warmup Iteration   3: 9.294 ops/ms
Iteration   1: 9.888 ops/ms
Iteration   2: 10.123 ops/ms
Iteration   3: 9.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.851 ±(99.9%) 5.323 ops/ms [Average]
  (min, avg, max) = (9.543, 9.851, 10.123), stdev = 0.292
  CI (99.9%): [4.528, 15.175] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.521 ops/ms
# Warmup Iteration   2: 7.172 ops/ms
# Warmup Iteration   3: 7.438 ops/ms
Iteration   1: 7.308 ops/ms
Iteration   2: 7.071 ops/ms
Iteration   3: 7.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.188 ±(99.9%) 2.167 ops/ms [Average]
  (min, avg, max) = (7.071, 7.188, 7.308), stdev = 0.119
  CI (99.9%): [5.021, 9.356] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.822 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.004 ms/op
Iteration   1: 3.404 ±(99.9%) 0.005 ms/op
Iteration   2: 3.397 ±(99.9%) 0.003 ms/op
Iteration   3: 3.399 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.400 ±(99.9%) 0.065 ms/op [Average]
  (min, avg, max) = (3.397, 3.400, 3.404), stdev = 0.004
  CI (99.9%): [3.334, 3.465] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.634 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.002 ms/op
Iteration   1: 3.332 ±(99.9%) 0.005 ms/op
Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
Iteration   3: 3.181 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.221 ±(99.9%) 1.768 ms/op [Average]
  (min, avg, max) = (3.151, 3.221, 3.332), stdev = 0.097
  CI (99.9%): [1.453, 4.989] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.716 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.004 ms/op
Iteration   1: 3.520 ±(99.9%) 0.002 ms/op
Iteration   2: 3.281 ±(99.9%) 0.004 ms/op
Iteration   3: 3.231 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.344 ±(99.9%) 2.815 ms/op [Average]
  (min, avg, max) = (3.231, 3.344, 3.520), stdev = 0.154
  CI (99.9%): [0.529, 6.159] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.960 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.017 ms/op
Iteration   1: 4.219 ±(99.9%) 0.020 ms/op
Iteration   2: 4.183 ±(99.9%) 0.015 ms/op
Iteration   3: 4.370 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.257 ±(99.9%) 1.810 ms/op [Average]
  (min, avg, max) = (4.183, 4.257, 4.370), stdev = 0.099
  CI (99.9%): [2.448, 6.067] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.579 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.007 ms/op
Iteration   1: 3.304 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.549 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.074 ms/op
                 createUser·p0.999:  8.391 ms/op
                 createUser·p0.9999: 14.074 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 3.332 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  6.989 ms/op
                 createUser·p0.9999: 17.347 ms/op
                 createUser·p1.00:   17.662 ms/op

Iteration   3: 3.279 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.087 ms/op
                 createUser·p0.999:  11.291 ms/op
                 createUser·p0.9999: 18.783 ms/op
                 createUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 290659
  mean =      3.305 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 338 
    [ 1.250,  2.500) = 15577 
    [ 2.500,  3.750) = 225038 
    [ 3.750,  5.000) = 46824 
    [ 5.000,  6.250) = 1885 
    [ 6.250,  7.500) = 442 
    [ 7.500,  8.750) = 254 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =      9.132 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.007 ms/op
Iteration   1: 3.179 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.923 ms/op
                 existUser·p0.999:  6.557 ms/op
                 existUser·p0.9999: 15.168 ms/op
                 existUser·p1.00:   15.729 ms/op

Iteration   2: 3.246 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 17.802 ms/op
                 existUser·p1.00:   18.186 ms/op

Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   4.841 ms/op
                 existUser·p0.999:  8.283 ms/op
                 existUser·p0.9999: 22.247 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 299852
  mean =      3.201 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23562 
    [ 2.500,  5.000) = 273967 
    [ 5.000,  7.500) = 1931 
    [ 7.500, 10.000) = 162 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 5.083 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.008 ms/op
Iteration   1: 3.441 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  7.569 ms/op
                 getUser·p0.9999: 13.704 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 3.407 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.496 ms/op
                 getUser·p0.9999: 15.792 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   3: 3.496 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  12.370 ms/op
                 getUser·p0.9999: 19.038 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 278307
  mean =      3.448 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 4867 
    [ 2.500,  3.750) = 212045 
    [ 3.750,  5.000) = 58660 
    [ 5.000,  6.250) = 1970 
    [ 6.250,  7.500) = 260 
    [ 7.500,  8.750) = 148 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =      7.889 ms/op
     p(99.9900) =     18.645 ms/op
     p(99.9990) =     19.216 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 6.796 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.630 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.409 ±(99.9%) 0.013 ms/op
Iteration   1: 4.323 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   4.174 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 16.741 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   2: 4.263 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   4.125 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  16.837 ms/op
                 listUser·p0.9999: 23.806 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   3: 4.454 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.201 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 220946
  mean =      4.345 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1114 
    [ 2.500,  5.000) = 191922 
    [ 5.000,  7.500) = 25415 
    [ 7.500, 10.000) = 2045 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     15.549 ms/op
     p(99.9900) =     22.083 ms/op
     p(99.9990) =     24.240 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.312 ± 1.914  ops/ms
ClientGrpc.existUser                       thrpt       3   9.961 ± 2.742  ops/ms
ClientGrpc.getUser                         thrpt       3   9.851 ± 5.323  ops/ms
ClientGrpc.listUser                        thrpt       3   7.188 ± 2.167  ops/ms
ClientGrpc.createUser                       avgt       3   3.400 ± 0.065   ms/op
ClientGrpc.existUser                        avgt       3   3.221 ± 1.768   ms/op
ClientGrpc.getUser                          avgt       3   3.344 ± 2.815   ms/op
ClientGrpc.listUser                         avgt       3   4.257 ± 1.810   ms/op
ClientGrpc.createUser                     sample  290659   3.305 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.549           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.265           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.997           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.132           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.547           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.300           ms/op
ClientGrpc.existUser                      sample  299852   3.201 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.667           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.207           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.981           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.760           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.471           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.661           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.315           ms/op
ClientGrpc.getUser                        sample  278307   3.448 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.544           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.408           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.956           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.889           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.645           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.890           ms/op
ClientGrpc.listUser                       sample  220946   4.345 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.161           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.211           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.259           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.152           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.586           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.549           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.083           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.347           ms/op
