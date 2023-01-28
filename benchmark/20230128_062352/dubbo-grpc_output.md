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
# Warmup Iteration   1: 4.644 ops/ms
# Warmup Iteration   2: 9.229 ops/ms
# Warmup Iteration   3: 10.503 ops/ms
Iteration   1: 10.244 ops/ms
Iteration   2: 10.709 ops/ms
Iteration   3: 9.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.292 ±(99.9%) 7.210 ops/ms [Average]
  (min, avg, max) = (9.923, 10.292, 10.709), stdev = 0.395
  CI (99.9%): [3.082, 17.502] (assumes normal distribution)


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
# Warmup Iteration   1: 8.567 ops/ms
# Warmup Iteration   2: 10.717 ops/ms
# Warmup Iteration   3: 10.721 ops/ms
Iteration   1: 11.023 ops/ms
Iteration   2: 10.737 ops/ms
Iteration   3: 10.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.814 ±(99.9%) 3.333 ops/ms [Average]
  (min, avg, max) = (10.682, 10.814, 11.023), stdev = 0.183
  CI (99.9%): [7.481, 14.147] (assumes normal distribution)


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
# Warmup Iteration   1: 7.707 ops/ms
# Warmup Iteration   2: 10.318 ops/ms
# Warmup Iteration   3: 10.556 ops/ms
Iteration   1: 10.461 ops/ms
Iteration   2: 10.347 ops/ms
Iteration   3: 10.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.440 ±(99.9%) 1.544 ops/ms [Average]
  (min, avg, max) = (10.347, 10.440, 10.513), stdev = 0.085
  CI (99.9%): [8.896, 11.984] (assumes normal distribution)


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
# Warmup Iteration   1: 6.390 ops/ms
# Warmup Iteration   2: 7.571 ops/ms
# Warmup Iteration   3: 7.751 ops/ms
Iteration   1: 8.000 ops/ms
Iteration   2: 7.671 ops/ms
Iteration   3: 8.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.920 ±(99.9%) 4.036 ops/ms [Average]
  (min, avg, max) = (7.671, 7.920, 8.091), stdev = 0.221
  CI (99.9%): [3.884, 11.957] (assumes normal distribution)


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.002 ms/op
Iteration   1: 3.177 ±(99.9%) 0.002 ms/op
Iteration   2: 3.196 ±(99.9%) 0.001 ms/op
Iteration   3: 3.134 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.169 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (3.134, 3.169, 3.196), stdev = 0.032
  CI (99.9%): [2.585, 3.753] (assumes normal distribution)


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.004 ms/op
Iteration   1: 2.951 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
Iteration   3: 2.894 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.936 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (2.894, 2.936, 2.962), stdev = 0.036
  CI (99.9%): [2.274, 3.597] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.003 ms/op
Iteration   1: 3.092 ±(99.9%) 0.002 ms/op
Iteration   2: 3.062 ±(99.9%) 0.002 ms/op
Iteration   3: 3.055 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.070 ±(99.9%) 0.363 ms/op [Average]
  (min, avg, max) = (3.055, 3.070, 3.092), stdev = 0.020
  CI (99.9%): [2.707, 3.432] (assumes normal distribution)


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.011 ms/op
Iteration   1: 3.987 ±(99.9%) 0.040 ms/op
Iteration   2: 3.864 ±(99.9%) 0.007 ms/op
Iteration   3: 4.132 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.994 ±(99.9%) 2.448 ms/op [Average]
  (min, avg, max) = (3.864, 3.994, 4.132), stdev = 0.134
  CI (99.9%): [1.546, 6.443] (assumes normal distribution)


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.168 ms/op
                 createUser·p0.9999: 14.074 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 3.158 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.554 ms/op
                 createUser·p0.9999: 12.908 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.410 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  12.451 ms/op
                 createUser·p0.9999: 18.234 ms/op
                 createUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313432
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29011 
    [ 2.500,  5.000) = 283109 
    [ 5.000,  7.500) = 873 
    [ 7.500, 10.000) = 162 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     17.082 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 3.558 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
Iteration   1: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  5.800 ms/op
                 existUser·p0.9999: 21.102 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   2: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  5.982 ms/op
                 existUser·p0.9999: 14.498 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  12.861 ms/op
                 existUser·p0.9999: 16.704 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330148
  mean =      2.907 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47593 
    [ 2.500,  5.000) = 281775 
    [ 5.000,  7.500) = 468 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.610 ms/op
     p(99.9900) =     17.559 ms/op
     p(99.9990) =     21.542 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.567 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  8.126 ms/op
                 getUser·p0.9999: 17.218 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  11.534 ms/op
                 getUser·p0.9999: 15.710 ms/op
                 getUser·p1.00:   16.761 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.242 ms/op
                 getUser·p0.9999: 19.399 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314756
  mean =      3.049 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2204 
    [ 1.250,  2.500) = 18739 
    [ 2.500,  3.750) = 273807 
    [ 3.750,  5.000) = 19066 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 174 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      9.338 ms/op
     p(99.9900) =     17.712 ms/op
     p(99.9990) =     19.820 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 4.942 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.011 ms/op
Iteration   1: 3.982 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  12.381 ms/op
                 listUser·p0.9999: 15.516 ms/op
                 listUser·p1.00:   15.909 ms/op

Iteration   2: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  12.011 ms/op
                 listUser·p0.9999: 15.355 ms/op
                 listUser·p1.00:   16.564 ms/op

Iteration   3: 3.853 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 20.067 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242310
  mean =      3.963 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3468 
    [ 2.500,  5.000) = 214093 
    [ 5.000,  7.500) = 23661 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.708 ms/op
     p(99.9000) =     12.774 ms/op
     p(99.9900) =     18.302 ms/op
     p(99.9990) =     20.794 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.292 ± 7.210  ops/ms
ClientGrpc.existUser                       thrpt       3  10.814 ± 3.333  ops/ms
ClientGrpc.getUser                         thrpt       3  10.440 ± 1.544  ops/ms
ClientGrpc.listUser                        thrpt       3   7.920 ± 4.036  ops/ms
ClientGrpc.createUser                       avgt       3   3.169 ± 0.584   ms/op
ClientGrpc.existUser                        avgt       3   2.936 ± 0.661   ms/op
ClientGrpc.getUser                          avgt       3   3.070 ± 0.363   ms/op
ClientGrpc.listUser                         avgt       3   3.994 ± 2.448   ms/op
ClientGrpc.createUser                     sample  313432   3.062 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.410           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.831           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.082           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.349           ms/op
ClientGrpc.existUser                      sample  330148   2.907 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.635           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.610           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.559           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.627           ms/op
ClientGrpc.getUser                        sample  314756   3.049 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.567           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.338           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.712           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.923           ms/op
ClientGrpc.listUser                       sample  242310   3.963 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.992           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.708           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.774           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.302           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.808           ms/op
