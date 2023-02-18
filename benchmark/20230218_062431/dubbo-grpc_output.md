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
# Warmup Iteration   1: 4.453 ops/ms
# Warmup Iteration   2: 8.851 ops/ms
# Warmup Iteration   3: 10.332 ops/ms
Iteration   1: 10.283 ops/ms
Iteration   2: 10.321 ops/ms
Iteration   3: 10.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.346 ±(99.9%) 1.432 ops/ms [Average]
  (min, avg, max) = (10.283, 10.346, 10.434), stdev = 0.078
  CI (99.9%): [8.914, 11.778] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.109 ops/ms
# Warmup Iteration   2: 10.537 ops/ms
# Warmup Iteration   3: 10.764 ops/ms
Iteration   1: 11.075 ops/ms
Iteration   2: 11.109 ops/ms
Iteration   3: 10.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.005 ±(99.9%) 2.781 ops/ms [Average]
  (min, avg, max) = (10.830, 11.005, 11.109), stdev = 0.152
  CI (99.9%): [8.224, 13.786] (assumes normal distribution)


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
# Warmup Iteration   1: 7.963 ops/ms
# Warmup Iteration   2: 9.990 ops/ms
# Warmup Iteration   3: 10.414 ops/ms
Iteration   1: 10.284 ops/ms
Iteration   2: 10.053 ops/ms
Iteration   3: 10.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.251 ±(99.9%) 3.364 ops/ms [Average]
  (min, avg, max) = (10.053, 10.251, 10.417), stdev = 0.184
  CI (99.9%): [6.887, 13.615] (assumes normal distribution)


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
# Warmup Iteration   1: 5.505 ops/ms
# Warmup Iteration   2: 7.554 ops/ms
# Warmup Iteration   3: 7.670 ops/ms
Iteration   1: 7.822 ops/ms
Iteration   2: 7.723 ops/ms
Iteration   3: 7.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.803 ±(99.9%) 1.337 ops/ms [Average]
  (min, avg, max) = (7.723, 7.803, 7.865), stdev = 0.073
  CI (99.9%): [6.466, 9.140] (assumes normal distribution)


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
# Warmup Iteration   1: 4.248 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.003 ms/op
Iteration   1: 3.068 ±(99.9%) 0.003 ms/op
Iteration   2: 3.209 ±(99.9%) 0.001 ms/op
Iteration   3: 3.226 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.167 ±(99.9%) 1.579 ms/op [Average]
  (min, avg, max) = (3.068, 3.167, 3.226), stdev = 0.087
  CI (99.9%): [1.588, 4.747] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.003 ms/op
Iteration   1: 2.959 ±(99.9%) 0.003 ms/op
Iteration   2: 2.971 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.965 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.959, 2.965, 2.971), stdev = 0.006
  CI (99.9%): [2.858, 3.071] (assumes normal distribution)


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.003 ms/op
Iteration   1: 3.002 ±(99.9%) 0.003 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.153 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.074 ±(99.9%) 1.384 ms/op [Average]
  (min, avg, max) = (3.002, 3.074, 3.153), stdev = 0.076
  CI (99.9%): [1.690, 4.458] (assumes normal distribution)


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
# Warmup Iteration   1: 4.947 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.006 ms/op
Iteration   1: 3.992 ±(99.9%) 0.010 ms/op
Iteration   2: 3.913 ±(99.9%) 0.030 ms/op
Iteration   3: 3.851 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.919 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (3.851, 3.919, 3.992), stdev = 0.071
  CI (99.9%): [2.623, 5.215] (assumes normal distribution)


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.329 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.283 ms/op
                 createUser·p0.9999: 11.821 ms/op
                 createUser·p1.00:   12.108 ms/op

Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  6.758 ms/op
                 createUser·p0.9999: 16.628 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.147 ms/op
                 createUser·p0.9999: 16.283 ms/op
                 createUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308977
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1013 
    [ 1.250,  2.500) = 20397 
    [ 2.500,  3.750) = 260755 
    [ 3.750,  5.000) = 25706 
    [ 5.000,  6.250) = 507 
    [ 6.250,  7.500) = 273 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     16.269 ms/op
     p(99.9990) =     16.935 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.753 ms/op
                 existUser·p0.9999: 14.406 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 3.021 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.477 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.200 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   3: 2.979 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  9.489 ms/op
                 existUser·p0.9999: 20.783 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319128
  mean =      3.009 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41015 
    [ 2.500,  5.000) = 277196 
    [ 5.000,  7.500) = 564 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      9.140 ms/op
     p(99.9900) =     20.912 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.537 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.968 ms/op
                 getUser·p0.9999: 13.627 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.941 ms/op
                 getUser·p0.9999: 13.301 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.298 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.477 ms/op
                 getUser·p0.9999: 24.083 ms/op
                 getUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315520
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27268 
    [ 2.500,  5.000) = 287203 
    [ 5.000,  7.500) = 733 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.512 ms/op
     p(99.9900) =     23.164 ms/op
     p(99.9990) =     24.533 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 5.205 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.010 ms/op
Iteration   1: 4.024 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.691 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  11.796 ms/op
                 listUser·p0.9999: 14.383 ms/op
                 listUser·p1.00:   15.696 ms/op

Iteration   2: 4.169 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.398 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  12.683 ms/op
                 listUser·p0.9999: 15.613 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   3: 4.175 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.058 ms/op
                 listUser·p0.999:  14.369 ms/op
                 listUser·p0.9999: 27.995 ms/op
                 listUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233133
  mean =      4.121 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3911 
    [ 2.500,  5.000) = 188772 
    [ 5.000,  7.500) = 38841 
    [ 7.500, 10.000) = 1115 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     24.234 ms/op
     p(99.9990) =     28.301 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.346 ± 1.432  ops/ms
ClientGrpc.existUser                       thrpt       3  11.005 ± 2.781  ops/ms
ClientGrpc.getUser                         thrpt       3  10.251 ± 3.364  ops/ms
ClientGrpc.listUser                        thrpt       3   7.803 ± 1.337  ops/ms
ClientGrpc.createUser                       avgt       3   3.167 ± 1.579   ms/op
ClientGrpc.existUser                        avgt       3   2.965 ± 0.106   ms/op
ClientGrpc.getUser                          avgt       3   3.074 ± 1.384   ms/op
ClientGrpc.listUser                         avgt       3   3.919 ± 1.296   ms/op
ClientGrpc.createUser                     sample  308977   3.106 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.329           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.594           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.269           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.039           ms/op
ClientGrpc.existUser                      sample  319128   3.009 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.477           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.140           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.912           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.151           ms/op
ClientGrpc.getUser                        sample  315520   3.040 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.298           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.512           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.164           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.642           ms/op
ClientGrpc.listUser                       sample  233133   4.121 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.398           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.912           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.796           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.234           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.836           ms/op
