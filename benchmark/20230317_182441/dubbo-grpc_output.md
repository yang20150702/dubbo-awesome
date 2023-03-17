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
# Warmup Iteration   1: 4.124 ops/ms
# Warmup Iteration   2: 9.315 ops/ms
# Warmup Iteration   3: 10.130 ops/ms
Iteration   1: 10.623 ops/ms
Iteration   2: 10.549 ops/ms
Iteration   3: 10.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.541 ±(99.9%) 1.575 ops/ms [Average]
  (min, avg, max) = (10.451, 10.541, 10.623), stdev = 0.086
  CI (99.9%): [8.966, 12.115] (assumes normal distribution)


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
# Warmup Iteration   1: 7.643 ops/ms
# Warmup Iteration   2: 10.594 ops/ms
# Warmup Iteration   3: 10.629 ops/ms
Iteration   1: 11.086 ops/ms
Iteration   2: 10.851 ops/ms
Iteration   3: 10.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.939 ±(99.9%) 2.327 ops/ms [Average]
  (min, avg, max) = (10.851, 10.939, 11.086), stdev = 0.128
  CI (99.9%): [8.612, 13.267] (assumes normal distribution)


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
# Warmup Iteration   1: 6.195 ops/ms
# Warmup Iteration   2: 9.475 ops/ms
# Warmup Iteration   3: 10.213 ops/ms
Iteration   1: 10.254 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.529 ±(99.9%) 5.410 ops/ms [Average]
  (min, avg, max) = (10.254, 10.529, 10.843), stdev = 0.297
  CI (99.9%): [5.119, 15.939] (assumes normal distribution)


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
# Warmup Iteration   1: 5.583 ops/ms
# Warmup Iteration   2: 8.029 ops/ms
# Warmup Iteration   3: 8.297 ops/ms
Iteration   1: 8.358 ops/ms
Iteration   2: 8.111 ops/ms
Iteration   3: 8.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.260 ±(99.9%) 2.393 ops/ms [Average]
  (min, avg, max) = (8.111, 8.260, 8.358), stdev = 0.131
  CI (99.9%): [5.867, 10.653] (assumes normal distribution)


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.004 ms/op
Iteration   1: 2.995 ±(99.9%) 0.003 ms/op
Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
Iteration   3: 2.973 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.993 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (2.973, 2.993, 3.012), stdev = 0.020
  CI (99.9%): [2.635, 3.352] (assumes normal distribution)


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
# Warmup Iteration   1: 3.698 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.875 ±(99.9%) 0.004 ms/op
Iteration   1: 2.828 ±(99.9%) 0.003 ms/op
Iteration   2: 2.825 ±(99.9%) 0.004 ms/op
Iteration   3: 2.757 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.803 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (2.757, 2.803, 2.828), stdev = 0.040
  CI (99.9%): [2.069, 3.537] (assumes normal distribution)


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.003 ms/op
Iteration   1: 2.976 ±(99.9%) 0.004 ms/op
Iteration   2: 2.957 ±(99.9%) 0.003 ms/op
Iteration   3: 2.982 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.971 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.957, 2.971, 2.982), stdev = 0.013
  CI (99.9%): [2.732, 3.211] (assumes normal distribution)


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.019 ms/op
Iteration   1: 4.043 ±(99.9%) 0.015 ms/op
Iteration   2: 3.786 ±(99.9%) 0.029 ms/op
Iteration   3: 3.853 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.894 ±(99.9%) 2.439 ms/op [Average]
  (min, avg, max) = (3.786, 3.894, 4.043), stdev = 0.134
  CI (99.9%): [1.456, 6.333] (assumes normal distribution)


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  9.438 ms/op
                 createUser·p0.9999: 12.763 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.246 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  9.798 ms/op
                 createUser·p0.9999: 13.054 ms/op
                 createUser·p1.00:   13.238 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.803 ms/op
                 createUser·p0.9999: 16.052 ms/op
                 createUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317103
  mean =      3.028 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2742 
    [ 1.250,  2.500) = 27072 
    [ 2.500,  3.750) = 267141 
    [ 3.750,  5.000) = 18607 
    [ 5.000,  6.250) = 804 
    [ 6.250,  7.500) = 311 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.246 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.778 ms/op
     p(99.9900) =     14.942 ms/op
     p(99.9990) =     16.507 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 2.935 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  6.210 ms/op
                 existUser·p0.9999: 16.074 ms/op
                 existUser·p1.00:   16.679 ms/op

Iteration   2: 3.006 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.124 ms/op
                 existUser·p0.9999: 14.993 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.897 ms/op
                 existUser·p0.9999: 15.168 ms/op
                 existUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321361
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2834 
    [ 1.250,  2.500) = 23024 
    [ 2.500,  3.750) = 281679 
    [ 3.750,  5.000) = 12573 
    [ 5.000,  6.250) = 838 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.194 ms/op
     p(99.9900) =     15.675 ms/op
     p(99.9990) =     16.465 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
Iteration   1: 3.226 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  8.509 ms/op
                 getUser·p0.9999: 12.635 ms/op
                 getUser·p1.00:   13.173 ms/op

Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.527 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  8.716 ms/op
                 getUser·p0.9999: 14.286 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   3: 3.085 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.466 ms/op
                 getUser·p0.9999: 13.730 ms/op
                 getUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303137
  mean =      3.166 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1145 
    [ 1.250,  2.500) = 15848 
    [ 2.500,  3.750) = 253243 
    [ 3.750,  5.000) = 31264 
    [ 5.000,  6.250) = 888 
    [ 6.250,  7.500) = 426 
    [ 7.500,  8.750) = 110 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.625 ms/op
     p(99.9000) =      7.658 ms/op
     p(99.9900) =     13.993 ms/op
     p(99.9990) =     15.480 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 5.427 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.012 ms/op
Iteration   1: 4.194 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 24.534 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   2: 4.080 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.131 ms/op
                 listUser·p0.9999: 23.205 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.154 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  16.497 ms/op
                 listUser·p0.9999: 18.917 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231977
  mean =      4.142 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2499 
    [ 2.500,  5.000) = 198218 
    [ 5.000,  7.500) = 29460 
    [ 7.500, 10.000) = 1328 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     15.680 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     27.586 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.541 ± 1.575  ops/ms
ClientGrpc.existUser                       thrpt       3  10.939 ± 2.327  ops/ms
ClientGrpc.getUser                         thrpt       3  10.529 ± 5.410  ops/ms
ClientGrpc.listUser                        thrpt       3   8.260 ± 2.393  ops/ms
ClientGrpc.createUser                       avgt       3   2.993 ± 0.358   ms/op
ClientGrpc.existUser                        avgt       3   2.803 ± 0.734   ms/op
ClientGrpc.getUser                          avgt       3   2.971 ± 0.239   ms/op
ClientGrpc.listUser                         avgt       3   3.894 ± 2.439   ms/op
ClientGrpc.createUser                     sample  317103   3.028 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.246           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.778           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.942           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.630           ms/op
ClientGrpc.existUser                      sample  321361   2.985 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.563           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.982           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.194           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.675           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.679           ms/op
ClientGrpc.getUser                        sample  303137   3.166 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.527           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.625           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.658           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.993           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.630           ms/op
ClientGrpc.listUser                       sample  231977   4.142 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.930           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.953           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.250           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.680           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.921           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.853           ms/op
