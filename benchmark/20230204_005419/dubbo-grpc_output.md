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
# Warmup Iteration   1: 3.845 ops/ms
# Warmup Iteration   2: 8.364 ops/ms
# Warmup Iteration   3: 9.366 ops/ms
Iteration   1: 9.637 ops/ms
Iteration   2: 9.789 ops/ms
Iteration   3: 9.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.774 ±(99.9%) 2.384 ops/ms [Average]
  (min, avg, max) = (9.637, 9.774, 9.897), stdev = 0.131
  CI (99.9%): [7.390, 12.158] (assumes normal distribution)


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
# Warmup Iteration   1: 6.626 ops/ms
# Warmup Iteration   2: 9.803 ops/ms
# Warmup Iteration   3: 10.315 ops/ms
Iteration   1: 10.249 ops/ms
Iteration   2: 10.341 ops/ms
Iteration   3: 10.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.268 ±(99.9%) 1.206 ops/ms [Average]
  (min, avg, max) = (10.213, 10.268, 10.341), stdev = 0.066
  CI (99.9%): [9.062, 11.474] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 5.994 ops/ms
# Warmup Iteration   2: 9.674 ops/ms
# Warmup Iteration   3: 9.830 ops/ms
Iteration   1: 10.014 ops/ms
Iteration   2: 10.007 ops/ms
Iteration   3: 9.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.961 ±(99.9%) 1.571 ops/ms [Average]
  (min, avg, max) = (9.862, 9.961, 10.014), stdev = 0.086
  CI (99.9%): [8.390, 11.532] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.923 ops/ms
# Warmup Iteration   2: 7.181 ops/ms
# Warmup Iteration   3: 7.715 ops/ms
Iteration   1: 7.834 ops/ms
Iteration   2: 7.830 ops/ms
Iteration   3: 7.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.800 ±(99.9%) 1.026 ops/ms [Average]
  (min, avg, max) = (7.735, 7.800, 7.834), stdev = 0.056
  CI (99.9%): [6.774, 8.825] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.605 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.003 ms/op
Iteration   1: 3.268 ±(99.9%) 0.001 ms/op
Iteration   2: 3.248 ±(99.9%) 0.002 ms/op
Iteration   3: 3.208 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.241 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.208, 3.241, 3.268), stdev = 0.030
  CI (99.9%): [2.687, 3.796] (assumes normal distribution)


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.003 ms/op
Iteration   1: 3.147 ±(99.9%) 0.002 ms/op
Iteration   2: 3.125 ±(99.9%) 0.001 ms/op
Iteration   3: 3.165 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.146 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (3.125, 3.146, 3.165), stdev = 0.020
  CI (99.9%): [2.776, 3.515] (assumes normal distribution)


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
# Warmup Iteration   1: 4.286 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.002 ms/op
Iteration   1: 3.195 ±(99.9%) 0.002 ms/op
Iteration   2: 3.200 ±(99.9%) 0.003 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.164 ±(99.9%) 1.049 ms/op [Average]
  (min, avg, max) = (3.098, 3.164, 3.200), stdev = 0.058
  CI (99.9%): [2.115, 4.213] (assumes normal distribution)


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
# Warmup Iteration   1: 5.903 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.021 ms/op
Iteration   1: 4.036 ±(99.9%) 0.006 ms/op
Iteration   2: 4.024 ±(99.9%) 0.006 ms/op
Iteration   3: 4.078 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.046 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (4.024, 4.046, 4.078), stdev = 0.028
  CI (99.9%): [3.528, 4.564] (assumes normal distribution)


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.007 ms/op
Iteration   1: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  10.243 ms/op
                 createUser·p0.9999: 17.262 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   2: 3.253 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  12.239 ms/op
                 createUser·p0.9999: 27.269 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   3: 3.335 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  10.800 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296411
  mean =      3.241 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18955 
    [ 2.500,  5.000) = 275669 
    [ 5.000,  7.500) = 1218 
    [ 7.500, 10.000) = 245 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =     11.265 ms/op
     p(99.9900) =     26.292 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 4.378 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
Iteration   1: 3.095 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.518 ms/op
                 existUser·p0.9999: 16.723 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.337 ms/op
                 existUser·p0.9999: 15.297 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   3: 3.138 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  10.589 ms/op
                 existUser·p0.9999: 15.807 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 306892
  mean =      3.127 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 651 
    [ 1.250,  2.500) = 22804 
    [ 2.500,  3.750) = 251543 
    [ 3.750,  5.000) = 30849 
    [ 5.000,  6.250) = 404 
    [ 6.250,  7.500) = 186 
    [ 7.500,  8.750) = 96 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     10.260 ms/op
     p(99.9900) =     16.165 ms/op
     p(99.9990) =     17.537 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.379 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.007 ms/op
Iteration   1: 3.251 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  6.922 ms/op
                 getUser·p0.9999: 14.830 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.693 ms/op
                 getUser·p0.9999: 14.811 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   3: 3.214 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.498 ms/op
                 getUser·p0.9999: 18.121 ms/op
                 getUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297879
  mean =      3.221 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 336 
    [ 1.250,  2.500) = 17202 
    [ 2.500,  3.750) = 233362 
    [ 3.750,  5.000) = 45938 
    [ 5.000,  6.250) = 526 
    [ 6.250,  7.500) = 248 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 92 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 5.141 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
Iteration   1: 4.232 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.261 ms/op
                 listUser·p0.9999: 18.659 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 4.087 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.204 ms/op
                 listUser·p0.9999: 26.057 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   3: 4.100 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 20.178 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231835
  mean =      4.138 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1861 
    [ 2.500,  5.000) = 199133 
    [ 5.000,  7.500) = 29355 
    [ 7.500, 10.000) = 989 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     25.291 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.774 ± 2.384  ops/ms
ClientGrpc.existUser                       thrpt       3  10.268 ± 1.206  ops/ms
ClientGrpc.getUser                         thrpt       3   9.961 ± 1.571  ops/ms
ClientGrpc.listUser                        thrpt       3   7.800 ± 1.026  ops/ms
ClientGrpc.createUser                       avgt       3   3.241 ± 0.554   ms/op
ClientGrpc.existUser                        avgt       3   3.146 ± 0.370   ms/op
ClientGrpc.getUser                          avgt       3   3.164 ± 1.049   ms/op
ClientGrpc.listUser                         avgt       3   4.046 ± 0.518   ms/op
ClientGrpc.createUser                     sample  296411   3.241 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.773           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.199           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.162           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.265           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.292           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.410           ms/op
ClientGrpc.existUser                      sample  306892   3.127 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.703           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.097           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.965           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.260           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.165           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.760           ms/op
ClientGrpc.getUser                        sample  297879   3.221 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.751           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.195           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.112           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.299           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.302           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.252           ms/op
ClientGrpc.listUser                       sample  231835   4.138 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.972           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.944           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.696           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.291           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.377           ms/op
