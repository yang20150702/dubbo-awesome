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
# Warmup Iteration   1: 4.381 ops/ms
# Warmup Iteration   2: 9.265 ops/ms
# Warmup Iteration   3: 10.386 ops/ms
Iteration   1: 10.415 ops/ms
Iteration   2: 10.196 ops/ms
Iteration   3: 10.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.389 ±(99.9%) 3.317 ops/ms [Average]
  (min, avg, max) = (10.196, 10.389, 10.557), stdev = 0.182
  CI (99.9%): [7.073, 13.706] (assumes normal distribution)


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
# Warmup Iteration   1: 7.161 ops/ms
# Warmup Iteration   2: 10.077 ops/ms
# Warmup Iteration   3: 10.332 ops/ms
Iteration   1: 10.437 ops/ms
Iteration   2: 10.838 ops/ms
Iteration   3: 10.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.614 ±(99.9%) 3.734 ops/ms [Average]
  (min, avg, max) = (10.437, 10.614, 10.838), stdev = 0.205
  CI (99.9%): [6.880, 14.348] (assumes normal distribution)


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
# Warmup Iteration   1: 7.258 ops/ms
# Warmup Iteration   2: 9.973 ops/ms
# Warmup Iteration   3: 10.084 ops/ms
Iteration   1: 10.169 ops/ms
Iteration   2: 10.110 ops/ms
Iteration   3: 10.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.138 ±(99.9%) 0.544 ops/ms [Average]
  (min, avg, max) = (10.110, 10.138, 10.169), stdev = 0.030
  CI (99.9%): [9.594, 10.682] (assumes normal distribution)


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
# Warmup Iteration   1: 5.517 ops/ms
# Warmup Iteration   2: 7.667 ops/ms
# Warmup Iteration   3: 8.022 ops/ms
Iteration   1: 8.073 ops/ms
Iteration   2: 7.977 ops/ms
Iteration   3: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.032 ±(99.9%) 0.911 ops/ms [Average]
  (min, avg, max) = (7.977, 8.032, 8.073), stdev = 0.050
  CI (99.9%): [7.121, 8.943] (assumes normal distribution)


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.001 ms/op
Iteration   1: 3.132 ±(99.9%) 0.003 ms/op
Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
Iteration   3: 3.214 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.163 ±(99.9%) 0.806 ms/op [Average]
  (min, avg, max) = (3.132, 3.163, 3.214), stdev = 0.044
  CI (99.9%): [2.357, 3.969] (assumes normal distribution)


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.002 ms/op
Iteration   1: 2.910 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.002 ms/op
Iteration   3: 3.023 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.971 ±(99.9%) 1.045 ms/op [Average]
  (min, avg, max) = (2.910, 2.971, 3.023), stdev = 0.057
  CI (99.9%): [1.926, 4.016] (assumes normal distribution)


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.003 ms/op
Iteration   1: 3.177 ±(99.9%) 0.002 ms/op
Iteration   2: 3.183 ±(99.9%) 0.001 ms/op
Iteration   3: 3.081 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.147 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (3.081, 3.147, 3.183), stdev = 0.057
  CI (99.9%): [2.110, 4.184] (assumes normal distribution)


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
# Warmup Iteration   1: 5.214 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.010 ms/op
Iteration   1: 4.053 ±(99.9%) 0.009 ms/op
Iteration   2: 4.134 ±(99.9%) 0.012 ms/op
Iteration   3: 4.034 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.073 ±(99.9%) 0.967 ms/op [Average]
  (min, avg, max) = (4.034, 4.073, 4.134), stdev = 0.053
  CI (99.9%): [3.107, 5.040] (assumes normal distribution)


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
# Warmup Iteration   1: 4.293 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.545 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.610 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  7.650 ms/op
                 createUser·p0.9999: 14.007 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  5.910 ms/op
                 createUser·p0.9999: 19.497 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   3: 3.256 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.632 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.147 ms/op
                 createUser·p0.9999: 23.801 ms/op
                 createUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304032
  mean =      3.157 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27732 
    [ 2.500,  5.000) = 275124 
    [ 5.000,  7.500) = 867 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.536 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     24.050 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
Iteration   1: 2.949 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.275 ms/op
                 existUser·p0.9999: 12.927 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   2: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.420 ms/op
                 existUser·p0.999:  7.076 ms/op
                 existUser·p0.9999: 17.891 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   3: 2.986 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  9.564 ms/op
                 existUser·p0.9999: 16.344 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324627
  mean =      2.957 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1689 
    [ 1.250,  2.500) = 50793 
    [ 2.500,  3.750) = 252137 
    [ 3.750,  5.000) = 18806 
    [ 5.000,  6.250) = 688 
    [ 6.250,  7.500) = 206 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.286 ms/op
     p(99.9900) =     16.642 ms/op
     p(99.9990) =     18.014 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.006 ms/op
Iteration   1: 3.121 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.016 ms/op
                 getUser·p0.9999: 19.939 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  10.969 ms/op
                 getUser·p0.9999: 14.337 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   3: 3.173 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.251 ms/op
                 getUser·p0.9999: 17.233 ms/op
                 getUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303078
  mean =      3.170 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23748 
    [ 2.500,  5.000) = 278118 
    [ 5.000,  7.500) = 835 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     19.237 ms/op
     p(99.9990) =     20.150 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 5.377 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.010 ms/op
Iteration   1: 4.069 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.163 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 4.101 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.237 ms/op
                 listUser·p0.9999: 21.077 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 4.052 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  15.967 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235406
  mean =      4.074 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2302 
    [ 2.500,  5.000) = 204308 
    [ 5.000,  7.500) = 27483 
    [ 7.500, 10.000) = 860 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     15.509 ms/op
     p(99.9900) =     20.495 ms/op
     p(99.9990) =     21.800 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.389 ± 3.317  ops/ms
ClientGrpc.existUser                       thrpt       3  10.614 ± 3.734  ops/ms
ClientGrpc.getUser                         thrpt       3  10.138 ± 0.544  ops/ms
ClientGrpc.listUser                        thrpt       3   8.032 ± 0.911  ops/ms
ClientGrpc.createUser                       avgt       3   3.163 ± 0.806   ms/op
ClientGrpc.existUser                        avgt       3   2.971 ± 1.045   ms/op
ClientGrpc.getUser                          avgt       3   3.147 ± 1.037   ms/op
ClientGrpc.listUser                         avgt       3   4.073 ± 0.967   ms/op
ClientGrpc.createUser                     sample  304032   3.157 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.545           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.536           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.332           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.117           ms/op
ClientGrpc.existUser                      sample  324627   2.957 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.286           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.642           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.104           ms/op
ClientGrpc.getUser                        sample  303078   3.170 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.833           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.026           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.552           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.237           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  235406   4.074 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.027           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.509           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.495           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.889           ms/op
