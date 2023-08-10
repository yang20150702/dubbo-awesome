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
# Warmup Iteration   1: 4.336 ops/ms
# Warmup Iteration   2: 8.822 ops/ms
# Warmup Iteration   3: 9.757 ops/ms
Iteration   1: 10.447 ops/ms
Iteration   2: 10.237 ops/ms
Iteration   3: 10.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.350 ±(99.9%) 1.935 ops/ms [Average]
  (min, avg, max) = (10.237, 10.350, 10.447), stdev = 0.106
  CI (99.9%): [8.415, 12.286] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.486 ops/ms
# Warmup Iteration   2: 10.510 ops/ms
# Warmup Iteration   3: 10.831 ops/ms
Iteration   1: 10.887 ops/ms
Iteration   2: 10.845 ops/ms
Iteration   3: 10.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.870 ±(99.9%) 0.400 ops/ms [Average]
  (min, avg, max) = (10.845, 10.870, 10.887), stdev = 0.022
  CI (99.9%): [10.469, 11.270] (assumes normal distribution)


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
# Warmup Iteration   1: 6.977 ops/ms
# Warmup Iteration   2: 10.061 ops/ms
# Warmup Iteration   3: 10.320 ops/ms
Iteration   1: 10.419 ops/ms
Iteration   2: 10.422 ops/ms
Iteration   3: 10.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.498 ±(99.9%) 2.433 ops/ms [Average]
  (min, avg, max) = (10.419, 10.498, 10.652), stdev = 0.133
  CI (99.9%): [8.065, 12.930] (assumes normal distribution)


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
# Warmup Iteration   1: 5.689 ops/ms
# Warmup Iteration   2: 7.531 ops/ms
# Warmup Iteration   3: 7.834 ops/ms
Iteration   1: 7.897 ops/ms
Iteration   2: 7.920 ops/ms
Iteration   3: 8.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.940 ±(99.9%) 1.014 ops/ms [Average]
  (min, avg, max) = (7.897, 7.940, 8.003), stdev = 0.056
  CI (99.9%): [6.926, 8.954] (assumes normal distribution)


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.003 ms/op
Iteration   1: 3.098 ±(99.9%) 0.004 ms/op
Iteration   2: 3.019 ±(99.9%) 0.002 ms/op
Iteration   3: 3.047 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.054 ±(99.9%) 0.732 ms/op [Average]
  (min, avg, max) = (3.019, 3.054, 3.098), stdev = 0.040
  CI (99.9%): [2.323, 3.786] (assumes normal distribution)


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.002 ms/op
Iteration   1: 2.829 ±(99.9%) 0.003 ms/op
Iteration   2: 2.946 ±(99.9%) 0.003 ms/op
Iteration   3: 2.909 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (2.829, 2.894, 2.946), stdev = 0.060
  CI (99.9%): [1.804, 3.985] (assumes normal distribution)


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.009 ms/op
Iteration   1: 3.074 ±(99.9%) 0.002 ms/op
Iteration   2: 3.104 ±(99.9%) 0.001 ms/op
Iteration   3: 3.010 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.063 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (3.010, 3.063, 3.104), stdev = 0.048
  CI (99.9%): [2.179, 3.947] (assumes normal distribution)


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
# Warmup Iteration   1: 5.652 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.010 ms/op
Iteration   1: 3.968 ±(99.9%) 0.010 ms/op
Iteration   2: 4.058 ±(99.9%) 0.011 ms/op
Iteration   3: 4.021 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.016 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (3.968, 4.016, 4.058), stdev = 0.045
  CI (99.9%): [3.195, 4.836] (assumes normal distribution)


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
# Warmup Iteration   1: 4.560 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  8.217 ms/op
                 createUser·p0.9999: 18.645 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.676 ms/op
                 createUser·p0.9999: 17.141 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 20.756 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315282
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25050 
    [ 2.500,  5.000) = 288458 
    [ 5.000,  7.500) = 1292 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.304 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     21.869 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.007 ms/op
Iteration   1: 2.963 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.645 ms/op
                 existUser·p0.9999: 13.248 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  11.274 ms/op
                 existUser·p0.9999: 14.583 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  7.712 ms/op
                 existUser·p0.9999: 18.158 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325503
  mean =      2.950 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1348 
    [ 1.250,  2.500) = 33842 
    [ 2.500,  3.750) = 279596 
    [ 3.750,  5.000) = 9172 
    [ 5.000,  6.250) = 610 
    [ 6.250,  7.500) = 473 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.315 ms/op
     p(99.9900) =     16.834 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  9.388 ms/op
                 getUser·p0.9999: 17.582 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  8.193 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.660 ms/op
                 getUser·p0.999:  8.177 ms/op
                 getUser·p0.9999: 19.759 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312970
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20036 
    [ 2.500,  5.000) = 290939 
    [ 5.000,  7.500) = 1523 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     20.434 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 5.733 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.011 ms/op
Iteration   1: 4.005 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.601 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  15.271 ms/op
                 listUser·p0.9999: 22.709 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 3.997 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.365 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  14.531 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 4.014 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 21.465 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239702
  mean =      4.005 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2303 
    [ 2.500,  5.000) = 213116 
    [ 5.000,  7.500) = 22277 
    [ 7.500, 10.000) = 1426 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.004 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.350 ± 1.935  ops/ms
ClientGrpc.existUser                       thrpt       3  10.870 ± 0.400  ops/ms
ClientGrpc.getUser                         thrpt       3  10.498 ± 2.433  ops/ms
ClientGrpc.listUser                        thrpt       3   7.940 ± 1.014  ops/ms
ClientGrpc.createUser                       avgt       3   3.054 ± 0.732   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 1.090   ms/op
ClientGrpc.getUser                          avgt       3   3.063 ± 0.884   ms/op
ClientGrpc.listUser                         avgt       3   4.016 ± 0.820   ms/op
ClientGrpc.createUser                     sample  315282   3.044 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.647           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.304           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.726           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.348           ms/op
ClientGrpc.existUser                      sample  325503   2.950 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.702           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.315           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.834           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.973           ms/op
ClientGrpc.getUser                        sample  312970   3.066 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.640           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.988           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.742           ms/op
ClientGrpc.listUser                       sample  239702   4.005 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.365           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.041           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.217           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.167           ms/op
