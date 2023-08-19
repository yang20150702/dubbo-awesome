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
# Warmup Iteration   1: 2.094 ops/ms
# Warmup Iteration   2: 5.528 ops/ms
# Warmup Iteration   3: 6.941 ops/ms
Iteration   1: 7.056 ops/ms
Iteration   2: 7.201 ops/ms
Iteration   3: 7.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.119 ±(99.9%) 1.358 ops/ms [Average]
  (min, avg, max) = (7.056, 7.119, 7.201), stdev = 0.074
  CI (99.9%): [5.761, 8.477] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.538 ops/ms
# Warmup Iteration   2: 7.787 ops/ms
# Warmup Iteration   3: 8.256 ops/ms
Iteration   1: 8.178 ops/ms
Iteration   2: 7.726 ops/ms
Iteration   3: 7.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.858 ±(99.9%) 5.091 ops/ms [Average]
  (min, avg, max) = (7.669, 7.858, 8.178), stdev = 0.279
  CI (99.9%): [2.767, 12.949] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.335 ops/ms
# Warmup Iteration   2: 6.772 ops/ms
# Warmup Iteration   3: 7.336 ops/ms
Iteration   1: 7.491 ops/ms
Iteration   2: 7.591 ops/ms
Iteration   3: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.625 ±(99.9%) 2.799 ops/ms [Average]
  (min, avg, max) = (7.491, 7.625, 7.792), stdev = 0.153
  CI (99.9%): [4.825, 10.424] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 4.124 ops/ms
# Warmup Iteration   2: 5.505 ops/ms
# Warmup Iteration   3: 5.865 ops/ms
Iteration   1: 5.929 ops/ms
Iteration   2: 5.818 ops/ms
Iteration   3: 5.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.896 ±(99.9%) 1.224 ops/ms [Average]
  (min, avg, max) = (5.818, 5.896, 5.939), stdev = 0.067
  CI (99.9%): [4.672, 7.119] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.481 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.588 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.004 ms/op
Iteration   1: 4.309 ±(99.9%) 0.003 ms/op
Iteration   2: 4.170 ±(99.9%) 0.002 ms/op
Iteration   3: 4.164 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.214 ±(99.9%) 1.492 ms/op [Average]
  (min, avg, max) = (4.164, 4.214, 4.309), stdev = 0.082
  CI (99.9%): [2.722, 5.706] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.051 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.002 ms/op
Iteration   1: 3.988 ±(99.9%) 0.003 ms/op
Iteration   2: 3.970 ±(99.9%) 0.002 ms/op
Iteration   3: 3.944 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.967 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (3.944, 3.967, 3.988), stdev = 0.022
  CI (99.9%): [3.564, 4.370] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.227 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.343 ±(99.9%) 0.005 ms/op
Iteration   1: 4.307 ±(99.9%) 0.004 ms/op
Iteration   2: 4.176 ±(99.9%) 0.003 ms/op
Iteration   3: 4.184 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.222 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (4.176, 4.222, 4.307), stdev = 0.074
  CI (99.9%): [2.880, 5.564] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.660 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.599 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.424 ±(99.9%) 0.013 ms/op
Iteration   1: 5.381 ±(99.9%) 0.017 ms/op
Iteration   2: 5.242 ±(99.9%) 0.013 ms/op
Iteration   3: 5.251 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.291 ±(99.9%) 1.421 ms/op [Average]
  (min, avg, max) = (5.242, 5.291, 5.381), stdev = 0.078
  CI (99.9%): [3.871, 6.712] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.591 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.012 ms/op
Iteration   1: 4.213 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   4.145 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  10.142 ms/op
                 createUser·p0.9999: 20.684 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   2: 4.134 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   4.051 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  11.364 ms/op
                 createUser·p0.9999: 15.630 ms/op
                 createUser·p1.00:   16.204 ms/op

Iteration   3: 4.180 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.516 ms/op
                 createUser·p0.50:   4.063 ms/op
                 createUser·p0.90:   5.136 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   6.397 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 33.489 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 229930
  mean =      4.175 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3081 
    [ 2.500,  5.000) = 199556 
    [ 5.000,  7.500) = 26048 
    [ 7.500, 10.000) = 808 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     11.993 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.798 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.009 ms/op
Iteration   1: 4.052 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  12.437 ms/op
                 existUser·p0.9999: 28.807 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   2: 3.936 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.891 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   6.393 ms/op
                 existUser·p0.999:  11.004 ms/op
                 existUser·p0.9999: 21.459 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   3: 4.078 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.969 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   5.489 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 18.552 ms/op
                 existUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238694
  mean =      4.021 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3974 
    [ 2.500,  5.000) = 211573 
    [ 5.000,  7.500) = 21957 
    [ 7.500, 10.000) = 803 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     11.031 ms/op
     p(99.9900) =     25.633 ms/op
     p(99.9990) =     29.622 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 6.478 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.509 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.286 ±(99.9%) 0.011 ms/op
Iteration   1: 4.187 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   4.080 ms/op
                 getUser·p0.90:   5.136 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  13.176 ms/op
                 getUser·p0.9999: 18.776 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   2: 4.175 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   4.104 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  9.585 ms/op
                 getUser·p0.9999: 18.907 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   3: 4.230 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.218 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  9.554 ms/op
                 getUser·p0.9999: 19.264 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 228612
  mean =      4.197 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 3397 
    [ 2.500,  3.750) = 63806 
    [ 3.750,  5.000) = 131157 
    [ 5.000,  6.250) = 26658 
    [ 6.250,  7.500) = 2244 
    [ 7.500,  8.750) = 738 
    [ 8.750, 10.000) = 343 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 58 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     10.964 ms/op
     p(99.9900) =     18.818 ms/op
     p(99.9990) =     19.577 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.840 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 6.134 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.455 ±(99.9%) 0.020 ms/op
Iteration   1: 5.422 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   6.652 ms/op
                 listUser·p0.95:   7.709 ms/op
                 listUser·p0.99:   10.174 ms/op
                 listUser·p0.999:  18.318 ms/op
                 listUser·p0.9999: 20.909 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 5.342 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   6.545 ms/op
                 listUser·p0.95:   7.586 ms/op
                 listUser·p0.99:   9.519 ms/op
                 listUser·p0.999:  17.860 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 5.343 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   5.145 ms/op
                 listUser·p0.90:   6.619 ms/op
                 listUser·p0.95:   7.741 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  20.089 ms/op
                 listUser·p0.9999: 26.673 ms/op
                 listUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178860
  mean =      5.369 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 72157 
    [ 5.000,  7.500) = 96502 
    [ 7.500, 10.000) = 8428 
    [10.000, 12.500) = 1127 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =      9.912 ms/op
     p(99.9000) =     18.711 ms/op
     p(99.9900) =     22.522 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.119 ± 1.358  ops/ms
ClientGrpc.existUser                       thrpt       3   7.858 ± 5.091  ops/ms
ClientGrpc.getUser                         thrpt       3   7.625 ± 2.799  ops/ms
ClientGrpc.listUser                        thrpt       3   5.896 ± 1.224  ops/ms
ClientGrpc.createUser                       avgt       3   4.214 ± 1.492   ms/op
ClientGrpc.existUser                        avgt       3   3.967 ± 0.403   ms/op
ClientGrpc.getUser                          avgt       3   4.222 ± 1.342   ms/op
ClientGrpc.listUser                         avgt       3   5.291 ± 1.421   ms/op
ClientGrpc.createUser                     sample  229930   4.175 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.516           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.087           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.480           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.993           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.260           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.554           ms/op
ClientGrpc.existUser                      sample  238694   4.021 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.883           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.981           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.374           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.365           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.031           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.633           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.278           ms/op
ClientGrpc.getUser                        sample  228612   4.197 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.653           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.108           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.153           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.530           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.652           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.964           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.818           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.661           ms/op
ClientGrpc.listUser                       sample  178860   5.369 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.329           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.676           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.912           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.711           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.522           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.165           ms/op
