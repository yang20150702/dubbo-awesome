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
# Warmup Iteration   1: 4.583 ops/ms
# Warmup Iteration   2: 9.076 ops/ms
# Warmup Iteration   3: 9.681 ops/ms
Iteration   1: 10.283 ops/ms
Iteration   2: 10.208 ops/ms
Iteration   3: 10.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.221 ±(99.9%) 1.050 ops/ms [Average]
  (min, avg, max) = (10.170, 10.221, 10.283), stdev = 0.058
  CI (99.9%): [9.171, 11.270] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.630 ops/ms
# Warmup Iteration   2: 10.290 ops/ms
# Warmup Iteration   3: 10.697 ops/ms
Iteration   1: 10.673 ops/ms
Iteration   2: 10.913 ops/ms
Iteration   3: 10.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.738 ±(99.9%) 2.803 ops/ms [Average]
  (min, avg, max) = (10.627, 10.738, 10.913), stdev = 0.154
  CI (99.9%): [7.934, 13.541] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.670 ops/ms
# Warmup Iteration   2: 9.760 ops/ms
# Warmup Iteration   3: 10.109 ops/ms
Iteration   1: 9.973 ops/ms
Iteration   2: 10.059 ops/ms
Iteration   3: 10.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.084 ±(99.9%) 2.288 ops/ms [Average]
  (min, avg, max) = (9.973, 10.084, 10.220), stdev = 0.125
  CI (99.9%): [7.796, 12.372] (assumes normal distribution)


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
# Warmup Iteration   1: 5.352 ops/ms
# Warmup Iteration   2: 7.716 ops/ms
# Warmup Iteration   3: 7.988 ops/ms
Iteration   1: 8.001 ops/ms
Iteration   2: 8.113 ops/ms
Iteration   3: 8.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.039 ±(99.9%) 1.156 ops/ms [Average]
  (min, avg, max) = (8.001, 8.039, 8.113), stdev = 0.063
  CI (99.9%): [6.884, 9.195] (assumes normal distribution)


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.002 ms/op
Iteration   1: 3.065 ±(99.9%) 0.003 ms/op
Iteration   2: 3.081 ±(99.9%) 0.003 ms/op
Iteration   3: 3.076 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.074 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (3.065, 3.074, 3.081), stdev = 0.008
  CI (99.9%): [2.925, 3.224] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.022 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.002 ms/op
Iteration   1: 2.925 ±(99.9%) 0.002 ms/op
Iteration   2: 2.942 ±(99.9%) 0.002 ms/op
Iteration   3: 2.946 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.938 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.925, 2.938, 2.946), stdev = 0.011
  CI (99.9%): [2.732, 3.144] (assumes normal distribution)


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.003 ms/op
Iteration   1: 3.096 ±(99.9%) 0.001 ms/op
Iteration   2: 3.109 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.127 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (3.096, 3.127, 3.177), stdev = 0.043
  CI (99.9%): [2.340, 3.914] (assumes normal distribution)


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
# Warmup Iteration   1: 5.562 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.033 ms/op
Iteration   1: 3.996 ±(99.9%) 0.025 ms/op
Iteration   2: 3.931 ±(99.9%) 0.013 ms/op
Iteration   3: 3.995 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.974 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.931, 3.974, 3.996), stdev = 0.037
  CI (99.9%): [3.299, 4.649] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.231 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.587 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  8.244 ms/op
                 createUser·p0.9999: 15.003 ms/op
                 createUser·p1.00:   16.597 ms/op

Iteration   2: 3.140 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.458 ms/op
                 createUser·p0.9999: 18.409 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  8.640 ms/op
                 createUser·p0.9999: 19.833 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309873
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11583 
    [ 2.500,  5.000) = 296239 
    [ 5.000,  7.500) = 1693 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.947 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     20.244 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 2.907 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.070 ms/op
                 existUser·p0.9999: 12.271 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   2: 2.921 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  9.413 ms/op
                 existUser·p0.9999: 13.698 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.380 ms/op
                 existUser·p0.999:  8.460 ms/op
                 existUser·p0.9999: 16.206 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327830
  mean =      2.928 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3251 
    [ 1.250,  2.500) = 36211 
    [ 2.500,  3.750) = 274778 
    [ 3.750,  5.000) = 11800 
    [ 5.000,  6.250) = 1120 
    [ 6.250,  7.500) = 324 
    [ 7.500,  8.750) = 90 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.620 ms/op
     p(99.9900) =     15.909 ms/op
     p(99.9990) =     17.555 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.005 ms/op
Iteration   1: 3.133 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  8.530 ms/op
                 getUser·p0.9999: 16.262 ms/op
                 getUser·p1.00:   16.531 ms/op

Iteration   2: 3.175 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.778 ms/op
                 getUser·p0.9999: 17.561 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.578 ms/op
                 getUser·p0.9999: 18.273 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306421
  mean =      3.133 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 227 
    [ 1.250,  2.500) = 7908 
    [ 2.500,  3.750) = 275203 
    [ 3.750,  5.000) = 21180 
    [ 5.000,  6.250) = 1031 
    [ 6.250,  7.500) = 433 
    [ 7.500,  8.750) = 157 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 71 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     18.440 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 5.375 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.010 ms/op
Iteration   1: 3.979 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  12.789 ms/op
                 listUser·p0.9999: 14.252 ms/op
                 listUser·p1.00:   16.089 ms/op

Iteration   2: 3.963 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.242 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   3: 3.932 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  16.231 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242504
  mean =      3.958 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2265 
    [ 2.500,  5.000) = 225866 
    [ 5.000,  7.500) = 13339 
    [ 7.500, 10.000) = 567 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     18.498 ms/op
     p(99.9990) =     21.838 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.221 ± 1.050  ops/ms
ClientGrpc.existUser                       thrpt       3  10.738 ± 2.803  ops/ms
ClientGrpc.getUser                         thrpt       3  10.084 ± 2.288  ops/ms
ClientGrpc.listUser                        thrpt       3   8.039 ± 1.156  ops/ms
ClientGrpc.createUser                       avgt       3   3.074 ± 0.150   ms/op
ClientGrpc.existUser                        avgt       3   2.938 ± 0.206   ms/op
ClientGrpc.getUser                          avgt       3   3.127 ± 0.787   ms/op
ClientGrpc.listUser                         avgt       3   3.974 ± 0.675   ms/op
ClientGrpc.createUser                     sample  309873   3.097 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.539           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.947           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.071           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.316           ms/op
ClientGrpc.existUser                      sample  327830   2.928 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.578           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.620           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.909           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.629           ms/op
ClientGrpc.getUser                        sample  306421   3.133 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.652           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.503           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.990           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.612           ms/op
ClientGrpc.listUser                       sample  242504   3.958 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.781           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.681           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.498           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.217           ms/op
