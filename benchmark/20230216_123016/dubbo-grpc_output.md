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
# Warmup Iteration   1: 4.317 ops/ms
# Warmup Iteration   2: 9.352 ops/ms
# Warmup Iteration   3: 10.135 ops/ms
Iteration   1: 10.388 ops/ms
Iteration   2: 10.548 ops/ms
Iteration   3: 10.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.366 ±(99.9%) 3.554 ops/ms [Average]
  (min, avg, max) = (10.161, 10.366, 10.548), stdev = 0.195
  CI (99.9%): [6.812, 13.920] (assumes normal distribution)


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
# Warmup Iteration   1: 8.044 ops/ms
# Warmup Iteration   2: 10.596 ops/ms
# Warmup Iteration   3: 10.333 ops/ms
Iteration   1: 10.620 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.630 ±(99.9%) 1.237 ops/ms [Average]
  (min, avg, max) = (10.568, 10.630, 10.702), stdev = 0.068
  CI (99.9%): [9.394, 11.867] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.931 ops/ms
# Warmup Iteration   2: 9.996 ops/ms
# Warmup Iteration   3: 9.881 ops/ms
Iteration   1: 10.025 ops/ms
Iteration   2: 10.157 ops/ms
Iteration   3: 10.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.184 ±(99.9%) 3.164 ops/ms [Average]
  (min, avg, max) = (10.025, 10.184, 10.369), stdev = 0.173
  CI (99.9%): [7.019, 13.348] (assumes normal distribution)


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
# Warmup Iteration   1: 5.362 ops/ms
# Warmup Iteration   2: 7.576 ops/ms
# Warmup Iteration   3: 7.870 ops/ms
Iteration   1: 7.846 ops/ms
Iteration   2: 7.756 ops/ms
Iteration   3: 7.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.787 ±(99.9%) 0.942 ops/ms [Average]
  (min, avg, max) = (7.756, 7.787, 7.846), stdev = 0.052
  CI (99.9%): [6.845, 8.728] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.007 ms/op
Iteration   2: 3.098 ±(99.9%) 0.004 ms/op
Iteration   3: 3.118 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.104 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (3.098, 3.104, 3.118), stdev = 0.012
  CI (99.9%): [2.893, 3.316] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.002 ms/op
Iteration   1: 3.038 ±(99.9%) 0.002 ms/op
Iteration   2: 2.961 ±(99.9%) 0.003 ms/op
Iteration   3: 2.989 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.996 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (2.961, 2.996, 3.038), stdev = 0.039
  CI (99.9%): [2.281, 3.711] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.117 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.002 ms/op
Iteration   1: 3.263 ±(99.9%) 0.002 ms/op
Iteration   2: 3.178 ±(99.9%) 0.002 ms/op
Iteration   3: 3.242 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.228 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (3.178, 3.228, 3.263), stdev = 0.044
  CI (99.9%): [2.418, 4.037] (assumes normal distribution)


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
# Warmup Iteration   1: 5.209 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.022 ms/op
Iteration   1: 4.065 ±(99.9%) 0.010 ms/op
Iteration   2: 3.994 ±(99.9%) 0.010 ms/op
Iteration   3: 4.178 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.079 ±(99.9%) 1.697 ms/op [Average]
  (min, avg, max) = (3.994, 4.079, 4.178), stdev = 0.093
  CI (99.9%): [2.382, 5.776] (assumes normal distribution)


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
# Warmup Iteration   1: 4.314 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.006 ms/op
Iteration   1: 3.310 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  10.220 ms/op
                 createUser·p0.9999: 38.820 ms/op
                 createUser·p1.00:   51.053 ms/op

Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.724 ms/op
                 createUser·p0.9999: 14.664 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   3: 3.198 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  11.436 ms/op
                 createUser·p0.9999: 17.269 ms/op
                 createUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296189
  mean =      3.239 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 294704 
    [ 5.000, 10.000) = 1203 
    [10.000, 15.000) = 181 
    [15.000, 20.000) = 69 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     38.404 ms/op
     p(99.9990) =     44.832 ms/op
     p(99.9999) =     51.053 ms/op
    p(100.0000) =     51.053 ms/op


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
# Warmup Iteration   1: 3.725 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.900 ms/op
                 existUser·p0.9999: 12.891 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.493 ms/op
                 existUser·p0.9999: 14.563 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.838 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317613
  mean =      3.021 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1171 
    [ 1.250,  2.500) = 44169 
    [ 2.500,  3.750) = 244256 
    [ 3.750,  5.000) = 27042 
    [ 5.000,  6.250) = 610 
    [ 6.250,  7.500) = 183 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.437 ms/op
     p(99.9900) =     15.683 ms/op
     p(99.9990) =     17.754 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
Iteration   1: 3.155 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  9.446 ms/op
                 getUser·p0.9999: 13.531 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.985 ms/op
                 getUser·p0.9999: 15.259 ms/op
                 getUser·p1.00:   15.761 ms/op

Iteration   3: 3.112 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.489 ms/op
                 getUser·p0.9999: 17.587 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307490
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 557 
    [ 1.250,  2.500) = 23119 
    [ 2.500,  3.750) = 251676 
    [ 3.750,  5.000) = 30921 
    [ 5.000,  6.250) = 611 
    [ 6.250,  7.500) = 251 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.770 ms/op
     p(99.9900) =     15.688 ms/op
     p(99.9990) =     17.758 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.663 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.014 ms/op
Iteration   1: 4.140 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 18.883 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 4.037 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.824 ms/op
                 listUser·p0.9999: 24.022 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   3: 4.074 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  17.631 ms/op
                 listUser·p0.9999: 26.870 ms/op
                 listUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234970
  mean =      4.084 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2604 
    [ 2.500,  5.000) = 201812 
    [ 5.000,  7.500) = 29114 
    [ 7.500, 10.000) = 955 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     16.090 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     28.670 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.366 ± 3.554  ops/ms
ClientGrpc.existUser                       thrpt       3  10.630 ± 1.237  ops/ms
ClientGrpc.getUser                         thrpt       3  10.184 ± 3.164  ops/ms
ClientGrpc.listUser                        thrpt       3   7.787 ± 0.942  ops/ms
ClientGrpc.createUser                       avgt       3   3.104 ± 0.211   ms/op
ClientGrpc.existUser                        avgt       3   2.996 ± 0.715   ms/op
ClientGrpc.getUser                          avgt       3   3.228 ± 0.810   ms/op
ClientGrpc.listUser                         avgt       3   4.079 ± 1.697   ms/op
ClientGrpc.createUser                     sample  296189   3.239 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.698           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.203           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.145           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.880           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          38.404           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          51.053           ms/op
ClientGrpc.existUser                      sample  317613   3.021 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.612           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.903           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.437           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.683           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.826           ms/op
ClientGrpc.getUser                        sample  307490   3.121 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.607           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.770           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.688           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.859           ms/op
ClientGrpc.listUser                       sample  234970   4.084 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.854           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.090           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.640           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.869           ms/op
