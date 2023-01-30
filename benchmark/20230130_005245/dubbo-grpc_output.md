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
# Warmup Iteration   1: 4.263 ops/ms
# Warmup Iteration   2: 8.773 ops/ms
# Warmup Iteration   3: 9.812 ops/ms
Iteration   1: 10.487 ops/ms
Iteration   2: 9.998 ops/ms
Iteration   3: 10.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.242 ±(99.9%) 4.461 ops/ms [Average]
  (min, avg, max) = (9.998, 10.242, 10.487), stdev = 0.245
  CI (99.9%): [5.781, 14.703] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.315 ops/ms
# Warmup Iteration   2: 10.086 ops/ms
# Warmup Iteration   3: 10.550 ops/ms
Iteration   1: 10.571 ops/ms
Iteration   2: 10.513 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.566 ±(99.9%) 0.936 ops/ms [Average]
  (min, avg, max) = (10.513, 10.566, 10.615), stdev = 0.051
  CI (99.9%): [9.630, 11.502] (assumes normal distribution)


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
# Warmup Iteration   1: 6.693 ops/ms
# Warmup Iteration   2: 9.817 ops/ms
# Warmup Iteration   3: 10.101 ops/ms
Iteration   1: 10.086 ops/ms
Iteration   2: 10.250 ops/ms
Iteration   3: 10.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.145 ±(99.9%) 1.663 ops/ms [Average]
  (min, avg, max) = (10.086, 10.145, 10.250), stdev = 0.091
  CI (99.9%): [8.482, 11.808] (assumes normal distribution)


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
# Warmup Iteration   1: 5.184 ops/ms
# Warmup Iteration   2: 7.739 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 7.644 ops/ms
Iteration   2: 7.857 ops/ms
Iteration   3: 7.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.785 ±(99.9%) 2.225 ops/ms [Average]
  (min, avg, max) = (7.644, 7.785, 7.857), stdev = 0.122
  CI (99.9%): [5.559, 10.010] (assumes normal distribution)


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
# Warmup Iteration   1: 4.500 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.002 ms/op
Iteration   1: 3.145 ±(99.9%) 0.004 ms/op
Iteration   2: 3.232 ±(99.9%) 0.002 ms/op
Iteration   3: 3.274 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.217 ±(99.9%) 1.193 ms/op [Average]
  (min, avg, max) = (3.145, 3.217, 3.274), stdev = 0.065
  CI (99.9%): [2.024, 4.410] (assumes normal distribution)


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.004 ms/op
Iteration   1: 3.107 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.002 ms/op
Iteration   3: 3.030 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.055 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (3.028, 3.055, 3.107), stdev = 0.045
  CI (99.9%): [2.231, 3.879] (assumes normal distribution)


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
# Warmup Iteration   1: 4.145 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.002 ms/op
Iteration   1: 3.175 ±(99.9%) 0.002 ms/op
Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
Iteration   3: 3.222 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.151 ±(99.9%) 1.564 ms/op [Average]
  (min, avg, max) = (3.056, 3.151, 3.222), stdev = 0.086
  CI (99.9%): [1.588, 4.715] (assumes normal distribution)


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
# Warmup Iteration   1: 5.568 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.010 ms/op
Iteration   1: 4.132 ±(99.9%) 0.020 ms/op
Iteration   2: 4.046 ±(99.9%) 0.010 ms/op
Iteration   3: 3.867 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.015 ±(99.9%) 2.471 ms/op [Average]
  (min, avg, max) = (3.867, 4.015, 4.132), stdev = 0.135
  CI (99.9%): [1.544, 6.486] (assumes normal distribution)


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.402 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.007 ms/op
Iteration   1: 3.255 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.420 ms/op
                 createUser·p0.9999: 13.998 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 3.154 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.398 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 14.858 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   3: 3.254 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.377 ms/op
                 createUser·p0.9999: 19.169 ms/op
                 createUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298215
  mean =      3.220 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 385 
    [ 1.250,  2.500) = 15165 
    [ 2.500,  3.750) = 238898 
    [ 3.750,  5.000) = 42806 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 270 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 84 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.190 ms/op
     p(99.9900) =     17.662 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.599 ms/op
                 existUser·p0.9999: 13.786 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.479 ms/op
                 existUser·p0.9999: 13.495 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.261 ms/op
                 existUser·p0.999:  6.901 ms/op
                 existUser·p0.9999: 18.563 ms/op
                 existUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311453
  mean =      3.080 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 829 
    [ 1.250,  2.500) = 33106 
    [ 2.500,  3.750) = 245352 
    [ 3.750,  5.000) = 31334 
    [ 5.000,  6.250) = 416 
    [ 6.250,  7.500) = 235 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.676 ms/op
     p(99.9900) =     17.531 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.006 ms/op
Iteration   1: 3.161 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.498 ms/op
                 getUser·p0.9999: 13.124 ms/op
                 getUser·p1.00:   13.304 ms/op

Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.440 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.477 ms/op
                 getUser·p0.9999: 15.155 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   3: 3.113 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.914 ms/op
                 getUser·p0.9999: 18.702 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305576
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 710 
    [ 1.250,  2.500) = 22493 
    [ 2.500,  3.750) = 249636 
    [ 3.750,  5.000) = 31500 
    [ 5.000,  6.250) = 650 
    [ 6.250,  7.500) = 300 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     17.378 ms/op
     p(99.9990) =     18.931 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 4.863 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.012 ms/op
Iteration   1: 4.068 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 22.323 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   2: 3.974 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   3: 4.054 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.716 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  16.818 ms/op
                 listUser·p0.9999: 24.970 ms/op
                 listUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238128
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2089 
    [ 2.500,  5.000) = 208268 
    [ 5.000,  7.500) = 26149 
    [ 7.500, 10.000) = 1129 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     16.263 ms/op
     p(99.9900) =     26.974 ms/op
     p(99.9990) =     28.680 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.242 ± 4.461  ops/ms
ClientGrpc.existUser                       thrpt       3  10.566 ± 0.936  ops/ms
ClientGrpc.getUser                         thrpt       3  10.145 ± 1.663  ops/ms
ClientGrpc.listUser                        thrpt       3   7.785 ± 2.225  ops/ms
ClientGrpc.createUser                       avgt       3   3.217 ± 1.193   ms/op
ClientGrpc.existUser                        avgt       3   3.055 ± 0.824   ms/op
ClientGrpc.getUser                          avgt       3   3.151 ± 1.564   ms/op
ClientGrpc.listUser                         avgt       3   4.015 ± 2.471   ms/op
ClientGrpc.createUser                     sample  298215   3.220 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.398           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.187           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.080           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.190           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.662           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.268           ms/op
ClientGrpc.existUser                      sample  311453   3.080 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.793           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.056           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.944           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.676           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.531           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.776           ms/op
ClientGrpc.getUser                        sample  305576   3.140 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.440           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.389           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.378           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.005           ms/op
ClientGrpc.listUser                       sample  238128   4.032 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.716           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.263           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.974           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.738           ms/op
