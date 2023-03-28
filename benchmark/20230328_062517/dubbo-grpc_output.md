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
# Warmup Iteration   1: 1.909 ops/ms
# Warmup Iteration   2: 4.525 ops/ms
# Warmup Iteration   3: 6.713 ops/ms
Iteration   1: 6.807 ops/ms
Iteration   2: 6.813 ops/ms
Iteration   3: 6.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.830 ±(99.9%) 0.646 ops/ms [Average]
  (min, avg, max) = (6.807, 6.830, 6.871), stdev = 0.035
  CI (99.9%): [6.185, 7.476] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.442 ops/ms
# Warmup Iteration   2: 6.163 ops/ms
# Warmup Iteration   3: 7.168 ops/ms
Iteration   1: 7.475 ops/ms
Iteration   2: 7.230 ops/ms
Iteration   3: 7.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.319 ±(99.9%) 2.480 ops/ms [Average]
  (min, avg, max) = (7.230, 7.319, 7.475), stdev = 0.136
  CI (99.9%): [4.839, 9.798] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.380 ops/ms
# Warmup Iteration   2: 5.908 ops/ms
# Warmup Iteration   3: 6.876 ops/ms
Iteration   1: 6.896 ops/ms
Iteration   2: 6.627 ops/ms
Iteration   3: 7.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.843 ±(99.9%) 3.555 ops/ms [Average]
  (min, avg, max) = (6.627, 6.843, 7.006), stdev = 0.195
  CI (99.9%): [3.288, 10.398] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.128 ops/ms
# Warmup Iteration   2: 4.807 ops/ms
# Warmup Iteration   3: 5.267 ops/ms
Iteration   1: 5.339 ops/ms
Iteration   2: 5.457 ops/ms
Iteration   3: 5.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.459 ±(99.9%) 2.227 ops/ms [Average]
  (min, avg, max) = (5.339, 5.459, 5.583), stdev = 0.122
  CI (99.9%): [3.232, 7.687] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.989 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.274 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.743 ±(99.9%) 0.020 ms/op
Iteration   1: 4.636 ±(99.9%) 0.004 ms/op
Iteration   2: 5.019 ±(99.9%) 0.004 ms/op
Iteration   3: 4.716 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.790 ±(99.9%) 3.684 ms/op [Average]
  (min, avg, max) = (4.636, 4.790, 5.019), stdev = 0.202
  CI (99.9%): [1.106, 8.474] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.108 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.019 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.490 ±(99.9%) 0.008 ms/op
Iteration   1: 4.266 ±(99.9%) 0.002 ms/op
Iteration   2: 4.490 ±(99.9%) 0.004 ms/op
Iteration   3: 4.360 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.372 ±(99.9%) 2.054 ms/op [Average]
  (min, avg, max) = (4.266, 4.372, 4.490), stdev = 0.113
  CI (99.9%): [2.318, 6.426] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.948 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.121 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.618 ±(99.9%) 0.003 ms/op
Iteration   1: 4.486 ±(99.9%) 0.002 ms/op
Iteration   2: 4.604 ±(99.9%) 0.002 ms/op
Iteration   3: 4.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.534 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (4.486, 4.534, 4.604), stdev = 0.062
  CI (99.9%): [3.411, 5.658] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.060 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 6.413 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.083 ±(99.9%) 0.022 ms/op
Iteration   1: 6.053 ±(99.9%) 0.019 ms/op
Iteration   2: 5.933 ±(99.9%) 0.010 ms/op
Iteration   3: 6.023 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.003 ±(99.9%) 1.139 ms/op [Average]
  (min, avg, max) = (5.933, 6.003, 6.053), stdev = 0.062
  CI (99.9%): [4.864, 7.142] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.441 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.202 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.702 ±(99.9%) 0.013 ms/op
Iteration   1: 4.838 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   4.710 ms/op
                 createUser·p0.90:   5.923 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   8.470 ms/op
                 createUser·p0.999:  13.468 ms/op
                 createUser·p0.9999: 16.095 ms/op
                 createUser·p1.00:   16.581 ms/op

Iteration   2: 4.745 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   4.612 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.324 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  13.943 ms/op
                 createUser·p0.9999: 18.383 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   3: 4.808 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   4.637 ms/op
                 createUser·p0.90:   5.984 ms/op
                 createUser·p0.95:   6.455 ms/op
                 createUser·p0.99:   8.913 ms/op
                 createUser·p0.999:  16.433 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 200182
  mean =      4.797 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1236 
    [ 2.500,  5.000) = 129883 
    [ 5.000,  7.500) = 65886 
    [ 7.500, 10.000) = 2086 
    [10.000, 12.500) = 601 
    [12.500, 15.000) = 321 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.382 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     14.687 ms/op
     p(99.9900) =     25.165 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.970 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.999 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.576 ±(99.9%) 0.014 ms/op
Iteration   1: 4.423 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   4.293 ms/op
                 existUser·p0.90:   5.456 ms/op
                 existUser·p0.95:   6.046 ms/op
                 existUser·p0.99:   7.864 ms/op
                 existUser·p0.999:  13.397 ms/op
                 existUser·p0.9999: 21.181 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   2: 4.627 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   4.497 ms/op
                 existUser·p0.90:   5.644 ms/op
                 existUser·p0.95:   6.070 ms/op
                 existUser·p0.99:   7.471 ms/op
                 existUser·p0.999:  13.120 ms/op
                 existUser·p0.9999: 24.975 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 4.345 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   5.276 ms/op
                 existUser·p0.95:   5.734 ms/op
                 existUser·p0.99:   8.208 ms/op
                 existUser·p0.999:  17.197 ms/op
                 existUser·p0.9999: 27.239 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 215054
  mean =      4.462 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3220 
    [ 2.500,  5.000) = 167587 
    [ 5.000,  7.500) = 41716 
    [ 7.500, 10.000) = 1602 
    [10.000, 12.500) = 492 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      5.966 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     27.838 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.554 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.167 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.566 ±(99.9%) 0.014 ms/op
Iteration   1: 4.589 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   5.849 ms/op
                 getUser·p0.95:   6.365 ms/op
                 getUser·p0.99:   7.799 ms/op
                 getUser·p0.999:  13.866 ms/op
                 getUser·p0.9999: 26.642 ms/op
                 getUser·p1.00:   26.870 ms/op

Iteration   2: 4.481 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.841 ms/op
                 getUser·p0.99:   7.381 ms/op
                 getUser·p0.999:  11.567 ms/op
                 getUser·p0.9999: 19.586 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   3: 4.620 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   7.684 ms/op
                 getUser·p0.999:  13.808 ms/op
                 getUser·p0.9999: 21.564 ms/op
                 getUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 210357
  mean =      4.562 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3154 
    [ 2.500,  5.000) = 155789 
    [ 5.000,  7.500) = 49042 
    [ 7.500, 10.000) = 1777 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     13.718 ms/op
     p(99.9900) =     23.493 ms/op
     p(99.9990) =     26.837 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.252 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 6.798 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.982 ±(99.9%) 0.023 ms/op
Iteration   1: 5.977 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   8.028 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  17.788 ms/op
                 listUser·p0.9999: 22.037 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   2: 5.922 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   7.414 ms/op
                 listUser·p0.95:   8.323 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  20.480 ms/op
                 listUser·p0.9999: 25.828 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   3: 5.832 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.498 ms/op
                 listUser·p0.99:   11.158 ms/op
                 listUser·p0.999:  24.478 ms/op
                 listUser·p0.9999: 27.248 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 162366
  mean =      5.910 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 38607 
    [ 5.000,  7.500) = 105111 
    [ 7.500, 10.000) = 15226 
    [10.000, 12.500) = 2583 
    [12.500, 15.000) = 407 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      5.612 ms/op
     p(90.0000) =      7.676 ms/op
     p(95.0000) =      8.634 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     20.620 ms/op
     p(99.9900) =     26.698 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.830 ± 0.646  ops/ms
ClientGrpc.existUser                       thrpt       3   7.319 ± 2.480  ops/ms
ClientGrpc.getUser                         thrpt       3   6.843 ± 3.555  ops/ms
ClientGrpc.listUser                        thrpt       3   5.459 ± 2.227  ops/ms
ClientGrpc.createUser                       avgt       3   4.790 ± 3.684   ms/op
ClientGrpc.existUser                        avgt       3   4.372 ± 2.054   ms/op
ClientGrpc.getUser                          avgt       3   4.534 ± 1.123   ms/op
ClientGrpc.listUser                         avgt       3   6.003 ± 1.139   ms/op
ClientGrpc.createUser                     sample  200182   4.797 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.041           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.915           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.382           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.487           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.687           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.165           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.887           ms/op
ClientGrpc.existUser                      sample  215054   4.462 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.015           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.472           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.966           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.799           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.122           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.297           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.951           ms/op
ClientGrpc.getUser                        sample  210357   4.562 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.143           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.078           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.660           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.718           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.493           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.870           ms/op
ClientGrpc.listUser                       sample  162366   5.910 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.294           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.676           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.634           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.190           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.620           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.698           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.886           ms/op
