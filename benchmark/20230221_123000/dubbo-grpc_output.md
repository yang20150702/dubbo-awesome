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
# Warmup Iteration   1: 4.902 ops/ms
# Warmup Iteration   2: 9.375 ops/ms
# Warmup Iteration   3: 10.127 ops/ms
Iteration   1: 10.135 ops/ms
Iteration   2: 10.066 ops/ms
Iteration   3: 9.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.044 ±(99.9%) 1.880 ops/ms [Average]
  (min, avg, max) = (9.932, 10.044, 10.135), stdev = 0.103
  CI (99.9%): [8.164, 11.924] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.450 ops/ms
# Warmup Iteration   2: 10.680 ops/ms
# Warmup Iteration   3: 10.579 ops/ms
Iteration   1: 10.475 ops/ms
Iteration   2: 10.848 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.588 ±(99.9%) 4.109 ops/ms [Average]
  (min, avg, max) = (10.442, 10.588, 10.848), stdev = 0.225
  CI (99.9%): [6.480, 14.697] (assumes normal distribution)


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
# Warmup Iteration   1: 7.144 ops/ms
# Warmup Iteration   2: 9.941 ops/ms
# Warmup Iteration   3: 9.995 ops/ms
Iteration   1: 10.131 ops/ms
Iteration   2: 10.383 ops/ms
Iteration   3: 10.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.299 ±(99.9%) 2.650 ops/ms [Average]
  (min, avg, max) = (10.131, 10.299, 10.383), stdev = 0.145
  CI (99.9%): [7.649, 12.949] (assumes normal distribution)


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
# Warmup Iteration   1: 5.526 ops/ms
# Warmup Iteration   2: 7.841 ops/ms
# Warmup Iteration   3: 7.802 ops/ms
Iteration   1: 7.739 ops/ms
Iteration   2: 7.535 ops/ms
Iteration   3: 7.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.703 ±(99.9%) 2.791 ops/ms [Average]
  (min, avg, max) = (7.535, 7.703, 7.834), stdev = 0.153
  CI (99.9%): [4.912, 10.493] (assumes normal distribution)


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.002 ms/op
Iteration   1: 3.209 ±(99.9%) 0.006 ms/op
Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
Iteration   3: 3.162 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.144 ±(99.9%) 1.383 ms/op [Average]
  (min, avg, max) = (3.061, 3.144, 3.209), stdev = 0.076
  CI (99.9%): [1.761, 4.527] (assumes normal distribution)


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.002 ms/op
Iteration   1: 3.025 ±(99.9%) 0.002 ms/op
Iteration   2: 2.935 ±(99.9%) 0.002 ms/op
Iteration   3: 2.922 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.961 ±(99.9%) 1.024 ms/op [Average]
  (min, avg, max) = (2.922, 2.961, 3.025), stdev = 0.056
  CI (99.9%): [1.936, 3.985] (assumes normal distribution)


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.122 ±(99.9%) 0.003 ms/op
Iteration   2: 3.092 ±(99.9%) 0.002 ms/op
Iteration   3: 2.972 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 1.451 ms/op [Average]
  (min, avg, max) = (2.972, 3.062, 3.122), stdev = 0.080
  CI (99.9%): [1.611, 4.513] (assumes normal distribution)


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
# Warmup Iteration   1: 5.329 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.012 ms/op
Iteration   1: 3.954 ±(99.9%) 0.004 ms/op
Iteration   2: 4.131 ±(99.9%) 0.009 ms/op
Iteration   3: 4.028 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.038 ±(99.9%) 1.627 ms/op [Average]
  (min, avg, max) = (3.954, 4.038, 4.131), stdev = 0.089
  CI (99.9%): [2.411, 5.665] (assumes normal distribution)


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
Iteration   1: 3.161 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.592 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.485 ms/op
                 createUser·p0.9999: 11.696 ms/op
                 createUser·p1.00:   11.977 ms/op

Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.509 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  5.513 ms/op
                 createUser·p0.9999: 15.471 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   3: 3.181 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.300 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.411 ms/op
                 createUser·p0.9999: 22.149 ms/op
                 createUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305459
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22312 
    [ 2.500,  5.000) = 282190 
    [ 5.000,  7.500) = 646 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.300 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.550 ms/op
     p(99.9900) =     19.345 ms/op
     p(99.9990) =     22.541 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.693 ms/op
                 existUser·p0.9999: 13.034 ms/op
                 existUser·p1.00:   13.238 ms/op

Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  10.862 ms/op
                 existUser·p0.9999: 14.056 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  5.760 ms/op
                 existUser·p0.9999: 26.126 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321229
  mean =      2.990 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42040 
    [ 2.500,  5.000) = 278325 
    [ 5.000,  7.500) = 545 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =     22.670 ms/op
     p(99.9990) =     26.430 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.489 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  7.050 ms/op
                 getUser·p0.9999: 15.344 ms/op
                 getUser·p1.00:   16.253 ms/op

Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.353 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  7.743 ms/op
                 getUser·p0.9999: 15.575 ms/op
                 getUser·p1.00:   16.269 ms/op

Iteration   3: 3.121 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.693 ms/op
                 getUser·p0.9999: 30.433 ms/op
                 getUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310584
  mean =      3.092 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20467 
    [ 2.500,  5.000) = 289410 
    [ 5.000,  7.500) = 418 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.353 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.157 ms/op
     p(99.9900) =     29.879 ms/op
     p(99.9990) =     30.598 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 5.250 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.012 ms/op
Iteration   1: 4.030 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.844 ms/op
                 listUser·p0.999:  11.655 ms/op
                 listUser·p0.9999: 14.226 ms/op
                 listUser·p1.00:   14.746 ms/op

Iteration   2: 4.090 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.427 ms/op
                 listUser·p0.9999: 15.948 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   3: 4.097 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.590 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.138 ms/op
                 listUser·p0.9999: 17.826 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235575
  mean =      4.072 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 3004 
    [ 2.500,  3.750) = 88295 
    [ 3.750,  5.000) = 111666 
    [ 5.000,  6.250) = 26962 
    [ 6.250,  7.500) = 4250 
    [ 7.500,  8.750) = 841 
    [ 8.750, 10.000) = 133 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 88 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     16.692 ms/op
     p(99.9990) =     17.847 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.044 ± 1.880  ops/ms
ClientGrpc.existUser                       thrpt       3  10.588 ± 4.109  ops/ms
ClientGrpc.getUser                         thrpt       3  10.299 ± 2.650  ops/ms
ClientGrpc.listUser                        thrpt       3   7.703 ± 2.791  ops/ms
ClientGrpc.createUser                       avgt       3   3.144 ± 1.383   ms/op
ClientGrpc.existUser                        avgt       3   2.961 ± 1.024   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 1.451   ms/op
ClientGrpc.listUser                         avgt       3   4.038 ± 1.627   ms/op
ClientGrpc.createUser                     sample  305459   3.143 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.300           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.550           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.345           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.643           ms/op
ClientGrpc.existUser                      sample  321229   2.990 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.501           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.487           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.670           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.640           ms/op
ClientGrpc.getUser                        sample  310584   3.092 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.353           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.157           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.879           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.671           ms/op
ClientGrpc.listUser                       sample  235575   4.072 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.590           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.189           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.692           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.891           ms/op
