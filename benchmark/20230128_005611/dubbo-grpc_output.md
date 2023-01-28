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
# Warmup Iteration   1: 3.920 ops/ms
# Warmup Iteration   2: 8.742 ops/ms
# Warmup Iteration   3: 9.796 ops/ms
Iteration   1: 9.818 ops/ms
Iteration   2: 9.687 ops/ms
Iteration   3: 9.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.752 ±(99.9%) 1.195 ops/ms [Average]
  (min, avg, max) = (9.687, 9.752, 9.818), stdev = 0.066
  CI (99.9%): [8.557, 10.948] (assumes normal distribution)


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
# Warmup Iteration   1: 7.269 ops/ms
# Warmup Iteration   2: 10.149 ops/ms
# Warmup Iteration   3: 11.059 ops/ms
Iteration   1: 10.419 ops/ms
Iteration   2: 10.185 ops/ms
Iteration   3: 10.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.318 ±(99.9%) 2.200 ops/ms [Average]
  (min, avg, max) = (10.185, 10.318, 10.419), stdev = 0.121
  CI (99.9%): [8.118, 12.519] (assumes normal distribution)


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
# Warmup Iteration   1: 6.731 ops/ms
# Warmup Iteration   2: 9.819 ops/ms
# Warmup Iteration   3: 9.929 ops/ms
Iteration   1: 9.921 ops/ms
Iteration   2: 9.831 ops/ms
Iteration   3: 9.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.893 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (9.831, 9.893, 9.928), stdev = 0.054
  CI (99.9%): [8.907, 10.880] (assumes normal distribution)


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
# Warmup Iteration   1: 5.356 ops/ms
# Warmup Iteration   2: 7.520 ops/ms
# Warmup Iteration   3: 7.608 ops/ms
Iteration   1: 7.808 ops/ms
Iteration   2: 8.004 ops/ms
Iteration   3: 8.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.023 ±(99.9%) 4.092 ops/ms [Average]
  (min, avg, max) = (7.808, 8.023, 8.256), stdev = 0.224
  CI (99.9%): [3.931, 12.114] (assumes normal distribution)


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
# Warmup Iteration   1: 4.471 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.024 ms/op
Iteration   1: 3.268 ±(99.9%) 0.009 ms/op
Iteration   2: 3.181 ±(99.9%) 0.002 ms/op
Iteration   3: 3.279 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.243 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (3.181, 3.243, 3.279), stdev = 0.053
  CI (99.9%): [2.267, 4.218] (assumes normal distribution)


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.002 ms/op
Iteration   1: 3.154 ±(99.9%) 0.005 ms/op
Iteration   2: 3.116 ±(99.9%) 0.002 ms/op
Iteration   3: 3.041 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.104 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.041, 3.104, 3.154), stdev = 0.058
  CI (99.9%): [2.053, 4.154] (assumes normal distribution)


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.002 ms/op
Iteration   1: 3.204 ±(99.9%) 0.003 ms/op
Iteration   2: 3.234 ±(99.9%) 0.002 ms/op
Iteration   3: 3.211 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.216 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (3.204, 3.216, 3.234), stdev = 0.016
  CI (99.9%): [2.921, 3.511] (assumes normal distribution)


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
# Warmup Iteration   1: 5.281 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.012 ms/op
Iteration   1: 3.995 ±(99.9%) 0.010 ms/op
Iteration   2: 4.034 ±(99.9%) 0.007 ms/op
Iteration   3: 4.016 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.015 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (3.995, 4.015, 4.034), stdev = 0.019
  CI (99.9%): [3.660, 4.370] (assumes normal distribution)


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
# Warmup Iteration   1: 4.492 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.007 ms/op
Iteration   1: 3.233 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.478 ms/op
                 createUser·p0.9999: 13.700 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 3.215 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  11.387 ms/op
                 createUser·p0.9999: 14.993 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   3: 3.269 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.294 ms/op
                 createUser·p0.9999: 24.456 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296506
  mean =      3.239 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20878 
    [ 2.500,  5.000) = 274355 
    [ 5.000,  7.500) = 897 
    [ 7.500, 10.000) = 131 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.327 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     25.823 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.006 ms/op
Iteration   1: 3.075 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  5.325 ms/op
                 existUser·p0.9999: 14.762 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.238 ms/op
                 existUser·p0.9999: 16.446 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   3: 3.090 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.021 ms/op
                 existUser·p0.9999: 27.394 ms/op
                 existUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 309889
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35020 
    [ 2.500,  5.000) = 274104 
    [ 5.000,  7.500) = 592 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     26.281 ms/op
     p(99.9990) =     28.141 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 4.464 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.007 ms/op
Iteration   1: 3.231 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.949 ms/op
                 getUser·p0.9999: 17.108 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.495 ms/op
                 getUser·p0.9999: 20.579 ms/op
                 getUser·p1.00:   21.103 ms/op

Iteration   3: 3.230 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.069 ms/op
                 getUser·p0.9999: 21.630 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297775
  mean =      3.222 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17018 
    [ 2.500,  5.000) = 279447 
    [ 5.000,  7.500) = 941 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.107 ms/op
     p(99.9900) =     20.520 ms/op
     p(99.9990) =     22.185 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 5.480 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.010 ms/op
Iteration   1: 3.923 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.732 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 16.510 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   2: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.681 ms/op
                 listUser·p0.9999: 16.877 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 4.152 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.317 ms/op
                 listUser·p0.9999: 25.312 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238021
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2069 
    [ 2.500,  5.000) = 206824 
    [ 5.000,  7.500) = 27718 
    [ 7.500, 10.000) = 927 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     25.759 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.752 ± 1.195  ops/ms
ClientGrpc.existUser                       thrpt       3  10.318 ± 2.200  ops/ms
ClientGrpc.getUser                         thrpt       3   9.893 ± 0.986  ops/ms
ClientGrpc.listUser                        thrpt       3   8.023 ± 4.092  ops/ms
ClientGrpc.createUser                       avgt       3   3.243 ± 0.975   ms/op
ClientGrpc.existUser                        avgt       3   3.104 ± 1.051   ms/op
ClientGrpc.getUser                          avgt       3   3.216 ± 0.295   ms/op
ClientGrpc.listUser                         avgt       3   4.015 ± 0.355   ms/op
ClientGrpc.createUser                     sample  296506   3.239 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.722           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.224           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.149           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.327           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.298           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.952           ms/op
ClientGrpc.existUser                      sample  309889   3.096 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.545           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.105           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.985           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.521           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.281           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.246           ms/op
ClientGrpc.getUser                        sample  297775   3.222 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.792           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.195           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.067           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.107           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.520           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.217           ms/op
ClientGrpc.listUser                       sample  238021   4.032 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.853           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.106           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.168           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.821           ms/op
