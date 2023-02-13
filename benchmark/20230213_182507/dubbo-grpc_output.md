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
# Warmup Iteration   1: 3.790 ops/ms
# Warmup Iteration   2: 8.422 ops/ms
# Warmup Iteration   3: 9.711 ops/ms
Iteration   1: 9.809 ops/ms
Iteration   2: 9.838 ops/ms
Iteration   3: 9.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.870 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (9.809, 9.870, 9.962), stdev = 0.081
  CI (99.9%): [8.383, 11.356] (assumes normal distribution)


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
# Warmup Iteration   1: 7.181 ops/ms
# Warmup Iteration   2: 9.743 ops/ms
# Warmup Iteration   3: 10.292 ops/ms
Iteration   1: 10.200 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 10.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.266 ±(99.9%) 1.045 ops/ms [Average]
  (min, avg, max) = (10.200, 10.266, 10.299), stdev = 0.057
  CI (99.9%): [9.221, 11.312] (assumes normal distribution)


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
# Warmup Iteration   1: 6.389 ops/ms
# Warmup Iteration   2: 9.599 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 9.980 ops/ms
Iteration   2: 9.843 ops/ms
Iteration   3: 10.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.946 ±(99.9%) 1.651 ops/ms [Average]
  (min, avg, max) = (9.843, 9.946, 10.014), stdev = 0.090
  CI (99.9%): [8.295, 11.597] (assumes normal distribution)


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
# Warmup Iteration   1: 5.640 ops/ms
# Warmup Iteration   2: 7.352 ops/ms
# Warmup Iteration   3: 7.641 ops/ms
Iteration   1: 7.784 ops/ms
Iteration   2: 7.802 ops/ms
Iteration   3: 7.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.784 ±(99.9%) 0.323 ops/ms [Average]
  (min, avg, max) = (7.766, 7.784, 7.802), stdev = 0.018
  CI (99.9%): [7.461, 8.107] (assumes normal distribution)


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.002 ms/op
Iteration   1: 3.210 ±(99.9%) 0.004 ms/op
Iteration   2: 3.232 ±(99.9%) 0.001 ms/op
Iteration   3: 3.352 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.265 ±(99.9%) 1.396 ms/op [Average]
  (min, avg, max) = (3.210, 3.265, 3.352), stdev = 0.077
  CI (99.9%): [1.869, 4.661] (assumes normal distribution)


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.004 ms/op
Iteration   1: 3.065 ±(99.9%) 0.003 ms/op
Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.068 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (3.040, 3.068, 3.100), stdev = 0.030
  CI (99.9%): [2.519, 3.618] (assumes normal distribution)


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.002 ms/op
Iteration   1: 3.198 ±(99.9%) 0.002 ms/op
Iteration   2: 3.258 ±(99.9%) 0.002 ms/op
Iteration   3: 3.239 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.232 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (3.198, 3.232, 3.258), stdev = 0.030
  CI (99.9%): [2.676, 3.788] (assumes normal distribution)


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
# Warmup Iteration   1: 5.680 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.022 ms/op
Iteration   1: 4.161 ±(99.9%) 0.011 ms/op
Iteration   2: 4.149 ±(99.9%) 0.019 ms/op
Iteration   3: 4.138 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.150 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (4.138, 4.150, 4.161), stdev = 0.011
  CI (99.9%): [3.944, 4.355] (assumes normal distribution)


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.007 ms/op
Iteration   1: 3.258 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  7.193 ms/op
                 createUser·p0.9999: 13.028 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 3.248 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.987 ms/op
                 createUser·p0.9999: 15.299 ms/op
                 createUser·p1.00:   15.876 ms/op

Iteration   3: 3.172 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 25.985 ms/op
                 createUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297711
  mean =      3.225 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18349 
    [ 2.500,  5.000) = 277999 
    [ 5.000,  7.500) = 925 
    [ 7.500, 10.000) = 168 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     24.525 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.916 ms/op
                 existUser·p0.9999: 13.510 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.832 ms/op
                 existUser·p0.9999: 14.823 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  5.650 ms/op
                 existUser·p0.9999: 17.601 ms/op
                 existUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311284
  mean =      3.084 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 755 
    [ 1.250,  2.500) = 30228 
    [ 2.500,  3.750) = 250281 
    [ 3.750,  5.000) = 29142 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 207 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.930 ms/op
     p(99.9900) =     15.653 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.168 ms/op
                 getUser·p0.9999: 17.720 ms/op
                 getUser·p1.00:   18.219 ms/op

Iteration   2: 3.250 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.449 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.987 ms/op
                 getUser·p0.9999: 18.299 ms/op
                 getUser·p1.00:   20.316 ms/op

Iteration   3: 3.186 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.863 ms/op
                 getUser·p0.9999: 21.987 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300044
  mean =      3.201 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15346 
    [ 2.500,  5.000) = 283442 
    [ 5.000,  7.500) = 1064 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.449 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 5.512 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.012 ms/op
Iteration   1: 4.176 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   2: 4.149 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.195 ms/op
                 listUser·p0.999:  18.610 ms/op
                 listUser·p0.9999: 23.439 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 4.184 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  16.358 ms/op
                 listUser·p0.9999: 24.829 ms/op
                 listUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230323
  mean =      4.169 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1444 
    [ 2.500,  5.000) = 200563 
    [ 5.000,  7.500) = 26524 
    [ 7.500, 10.000) = 1261 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     15.281 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.254 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.870 ± 1.486  ops/ms
ClientGrpc.existUser                       thrpt       3  10.266 ± 1.045  ops/ms
ClientGrpc.getUser                         thrpt       3   9.946 ± 1.651  ops/ms
ClientGrpc.listUser                        thrpt       3   7.784 ± 0.323  ops/ms
ClientGrpc.createUser                       avgt       3   3.265 ± 1.396   ms/op
ClientGrpc.existUser                        avgt       3   3.068 ± 0.549   ms/op
ClientGrpc.getUser                          avgt       3   3.232 ± 0.556   ms/op
ClientGrpc.listUser                         avgt       3   4.150 ± 0.205   ms/op
ClientGrpc.createUser                     sample  297711   3.225 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.812           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.191           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.112           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.224           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.525           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.985           ms/op
ClientGrpc.existUser                      sample  311284   3.084 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.608           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.068           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.930           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.653           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.481           ms/op
ClientGrpc.getUser                        sample  300044   3.201 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.449           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.102           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.758           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.577           ms/op
ClientGrpc.listUser                       sample  230323   4.169 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.077           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.994           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.281           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.150           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.264           ms/op
