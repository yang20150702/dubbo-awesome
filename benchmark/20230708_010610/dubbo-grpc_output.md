# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ops/ms
# Warmup Iteration   2: 9.126 ops/ms
# Warmup Iteration   3: 10.101 ops/ms
Iteration   1: 10.454 ops/ms
Iteration   2: 10.251 ops/ms
Iteration   3: 10.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.415 ±(99.9%) 2.714 ops/ms [Average]
  (min, avg, max) = (10.251, 10.415, 10.540), stdev = 0.149
  CI (99.9%): [7.701, 13.129] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.106 ops/ms
# Warmup Iteration   2: 10.895 ops/ms
# Warmup Iteration   3: 10.871 ops/ms
Iteration   1: 10.995 ops/ms
Iteration   2: 11.259 ops/ms
Iteration   3: 10.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.064 ±(99.9%) 3.126 ops/ms [Average]
  (min, avg, max) = (10.938, 11.064, 11.259), stdev = 0.171
  CI (99.9%): [7.938, 14.191] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.040 ops/ms
# Warmup Iteration   2: 9.970 ops/ms
# Warmup Iteration   3: 10.626 ops/ms
Iteration   1: 10.378 ops/ms
Iteration   2: 10.558 ops/ms
Iteration   3: 10.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.530 ±(99.9%) 2.542 ops/ms [Average]
  (min, avg, max) = (10.378, 10.530, 10.652), stdev = 0.139
  CI (99.9%): [7.988, 13.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.357 ops/ms
# Warmup Iteration   2: 7.578 ops/ms
# Warmup Iteration   3: 7.674 ops/ms
Iteration   1: 7.839 ops/ms
Iteration   2: 7.764 ops/ms
Iteration   3: 7.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.805 ±(99.9%) 0.691 ops/ms [Average]
  (min, avg, max) = (7.764, 7.805, 7.839), stdev = 0.038
  CI (99.9%): [7.114, 8.496] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.450 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.002 ms/op
Iteration   1: 3.150 ±(99.9%) 0.002 ms/op
Iteration   2: 3.129 ±(99.9%) 0.002 ms/op
Iteration   3: 3.134 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.137 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (3.129, 3.137, 3.150), stdev = 0.011
  CI (99.9%): [2.939, 3.335] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.906 ±(99.9%) 0.002 ms/op
Iteration   3: 2.938 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.944 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (2.906, 2.944, 2.988), stdev = 0.041
  CI (99.9%): [2.190, 3.698] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.205 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.004 ms/op
Iteration   1: 3.052 ±(99.9%) 0.003 ms/op
Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
Iteration   3: 3.073 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.067 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (3.052, 3.067, 3.075), stdev = 0.013
  CI (99.9%): [2.833, 3.301] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.550 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.011 ms/op
Iteration   1: 4.160 ±(99.9%) 0.018 ms/op
Iteration   2: 4.118 ±(99.9%) 0.036 ms/op
Iteration   3: 3.968 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.082 ±(99.9%) 1.838 ms/op [Average]
  (min, avg, max) = (3.968, 4.082, 4.160), stdev = 0.101
  CI (99.9%): [2.244, 5.921] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.440 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  11.557 ms/op
                 createUser·p0.9999: 12.770 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  7.299 ms/op
                 createUser·p0.9999: 13.484 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 3.055 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.302 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  7.031 ms/op
                 createUser·p0.9999: 31.835 ms/op
                 createUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315203
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21071 
    [ 2.500,  5.000) = 292179 
    [ 5.000,  7.500) = 1629 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.302 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.739 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      8.013 ms/op
     p(99.9900) =     31.194 ms/op
     p(99.9990) =     32.130 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.097 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.005 ms/op
Iteration   1: 2.959 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  8.233 ms/op
                 existUser·p0.9999: 21.331 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   2: 2.951 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  9.490 ms/op
                 existUser·p0.9999: 13.533 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  8.232 ms/op
                 existUser·p0.9999: 15.532 ms/op
                 existUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325603
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33201 
    [ 2.500,  5.000) = 291253 
    [ 5.000,  7.500) = 684 
    [ 7.500, 10.000) = 221 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     17.402 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.536 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  7.125 ms/op
                 getUser·p0.9999: 13.018 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.312 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  9.013 ms/op
                 getUser·p0.9999: 15.347 ms/op
                 getUser·p1.00:   16.171 ms/op

Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.914 ms/op
                 getUser·p0.9999: 27.381 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311248
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17332 
    [ 2.500,  5.000) = 292025 
    [ 5.000,  7.500) = 1536 
    [ 7.500, 10.000) = 148 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.312 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.684 ms/op
     p(99.9900) =     25.645 ms/op
     p(99.9990) =     27.653 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.949 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.011 ms/op
Iteration   1: 4.159 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  13.093 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 4.063 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  17.550 ms/op
                 listUser·p0.9999: 20.049 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 4.069 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.263 ms/op
                 listUser·p0.999:  16.686 ms/op
                 listUser·p0.9999: 20.025 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234334
  mean =      4.096 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2196 
    [ 2.500,  5.000) = 205112 
    [ 5.000,  7.500) = 25139 
    [ 7.500, 10.000) = 1383 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     15.658 ms/op
     p(99.9900) =     20.779 ms/op
     p(99.9990) =     22.652 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.415 ± 2.714  ops/ms
ClientGrpc.existUser                       thrpt       3  11.064 ± 3.126  ops/ms
ClientGrpc.getUser                         thrpt       3  10.530 ± 2.542  ops/ms
ClientGrpc.listUser                        thrpt       3   7.805 ± 0.691  ops/ms
ClientGrpc.createUser                       avgt       3   3.137 ± 0.198   ms/op
ClientGrpc.existUser                        avgt       3   2.944 ± 0.754   ms/op
ClientGrpc.getUser                          avgt       3   3.067 ± 0.234   ms/op
ClientGrpc.listUser                         avgt       3   4.082 ± 1.838   ms/op
ClientGrpc.createUser                     sample  315203   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.302           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.739           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.013           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.194           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.309           ms/op
ClientGrpc.existUser                      sample  325603   2.946 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.569           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.946           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.402           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.625           ms/op
ClientGrpc.getUser                        sample  311248   3.084 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.312           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.684           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.645           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.787           ms/op
ClientGrpc.listUser                       sample  234334   4.096 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.896           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.658           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.779           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.741           ms/op
