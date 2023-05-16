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
# Warmup Iteration   1: 2.408 ops/ms
# Warmup Iteration   2: 6.454 ops/ms
# Warmup Iteration   3: 7.422 ops/ms
Iteration   1: 7.708 ops/ms
Iteration   2: 8.074 ops/ms
Iteration   3: 7.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.912 ±(99.9%) 3.404 ops/ms [Average]
  (min, avg, max) = (7.708, 7.912, 8.074), stdev = 0.187
  CI (99.9%): [4.507, 11.316] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.278 ops/ms
# Warmup Iteration   2: 7.850 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 8.364 ops/ms
Iteration   2: 8.449 ops/ms
Iteration   3: 8.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.472 ±(99.9%) 2.205 ops/ms [Average]
  (min, avg, max) = (8.364, 8.472, 8.602), stdev = 0.121
  CI (99.9%): [6.267, 10.677] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.655 ops/ms
# Warmup Iteration   2: 7.276 ops/ms
# Warmup Iteration   3: 7.599 ops/ms
Iteration   1: 7.806 ops/ms
Iteration   2: 7.681 ops/ms
Iteration   3: 8.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.845 ±(99.9%) 3.413 ops/ms [Average]
  (min, avg, max) = (7.681, 7.845, 8.049), stdev = 0.187
  CI (99.9%): [4.433, 11.258] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ops/ms
# Warmup Iteration   2: 5.953 ops/ms
# Warmup Iteration   3: 6.493 ops/ms
Iteration   1: 6.238 ops/ms
Iteration   2: 6.426 ops/ms
Iteration   3: 6.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.322 ±(99.9%) 1.742 ops/ms [Average]
  (min, avg, max) = (6.238, 6.322, 6.426), stdev = 0.095
  CI (99.9%): [4.580, 8.065] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.476 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.004 ms/op
Iteration   1: 4.123 ±(99.9%) 0.004 ms/op
Iteration   2: 4.144 ±(99.9%) 0.003 ms/op
Iteration   3: 4.039 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.102 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (4.039, 4.102, 4.144), stdev = 0.056
  CI (99.9%): [3.082, 5.121] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.583 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.003 ms/op
Iteration   1: 3.601 ±(99.9%) 0.004 ms/op
Iteration   2: 3.599 ±(99.9%) 0.003 ms/op
Iteration   3: 3.639 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.613 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (3.599, 3.613, 3.639), stdev = 0.023
  CI (99.9%): [3.198, 4.029] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.224 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.004 ms/op
Iteration   1: 3.948 ±(99.9%) 0.003 ms/op
Iteration   2: 4.071 ±(99.9%) 0.003 ms/op
Iteration   3: 3.966 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.995 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (3.948, 3.995, 4.071), stdev = 0.066
  CI (99.9%): [2.782, 5.208] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.938 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.368 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.069 ±(99.9%) 0.021 ms/op
Iteration   1: 5.054 ±(99.9%) 0.017 ms/op
Iteration   2: 5.136 ±(99.9%) 0.014 ms/op
Iteration   3: 5.115 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.101 ±(99.9%) 0.780 ms/op [Average]
  (min, avg, max) = (5.054, 5.101, 5.136), stdev = 0.043
  CI (99.9%): [4.322, 5.881] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.443 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.344 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.013 ms/op
Iteration   1: 4.105 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   5.161 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   7.544 ms/op
                 createUser·p0.999:  12.569 ms/op
                 createUser·p0.9999: 16.185 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   2: 3.960 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   7.053 ms/op
                 createUser·p0.999:  15.011 ms/op
                 createUser·p0.9999: 18.117 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   3: 4.067 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  10.525 ms/op
                 createUser·p0.9999: 21.608 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 237173
  mean =      4.043 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6566 
    [ 2.500,  5.000) = 204315 
    [ 5.000,  7.500) = 24392 
    [ 7.500, 10.000) = 1421 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     12.626 ms/op
     p(99.9900) =     20.672 ms/op
     p(99.9990) =     22.180 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.846 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.010 ms/op
Iteration   1: 3.891 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.891 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   7.239 ms/op
                 existUser·p0.999:  11.682 ms/op
                 existUser·p0.9999: 21.587 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.699 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  10.523 ms/op
                 existUser·p0.9999: 24.084 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   3: 3.708 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  10.912 ms/op
                 existUser·p0.9999: 18.809 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 255103
  mean =      3.764 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8433 
    [ 2.500,  5.000) = 231803 
    [ 5.000,  7.500) = 13323 
    [ 7.500, 10.000) = 1110 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     11.158 ms/op
     p(99.9900) =     22.261 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.023 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.010 ms/op
Iteration   1: 3.953 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 15.070 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   2: 3.950 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  8.378 ms/op
                 getUser·p0.9999: 15.090 ms/op
                 getUser·p1.00:   15.581 ms/op

Iteration   3: 3.932 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.874 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  10.447 ms/op
                 getUser·p0.9999: 19.783 ms/op
                 getUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 243276
  mean =      3.945 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5054 
    [ 2.500,  5.000) = 220570 
    [ 5.000,  7.500) = 16886 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     20.180 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 7.923 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.519 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.300 ±(99.9%) 0.021 ms/op
Iteration   1: 5.128 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   6.365 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  27.001 ms/op
                 listUser·p0.9999: 32.049 ms/op
                 listUser·p1.00:   32.702 ms/op

Iteration   2: 5.037 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.293 ms/op
                 listUser·p0.999:  23.902 ms/op
                 listUser·p0.9999: 25.723 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   3: 5.245 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   6.922 ms/op
                 listUser·p0.95:   7.823 ms/op
                 listUser·p0.99:   9.934 ms/op
                 listUser·p0.999:  19.958 ms/op
                 listUser·p0.9999: 24.543 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186896
  mean =      5.135 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 283 
    [ 2.500,  5.000) = 104150 
    [ 5.000,  7.500) = 73340 
    [ 7.500, 10.000) = 7694 
    [10.000, 12.500) = 932 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.586 ms/op
     p(95.0000) =      7.471 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     23.534 ms/op
     p(99.9900) =     30.517 ms/op
     p(99.9990) =     32.589 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.912 ± 3.404  ops/ms
ClientGrpc.existUser                       thrpt       3   8.472 ± 2.205  ops/ms
ClientGrpc.getUser                         thrpt       3   7.845 ± 3.413  ops/ms
ClientGrpc.listUser                        thrpt       3   6.322 ± 1.742  ops/ms
ClientGrpc.createUser                       avgt       3   4.102 ± 1.020   ms/op
ClientGrpc.existUser                        avgt       3   3.613 ± 0.415   ms/op
ClientGrpc.getUser                          avgt       3   3.995 ± 1.213   ms/op
ClientGrpc.listUser                         avgt       3   5.101 ± 0.780   ms/op
ClientGrpc.createUser                     sample  237173   4.043 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.775           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.071           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.530           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.086           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.626           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.672           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.249           ms/op
ClientGrpc.existUser                      sample  255103   3.764 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.720           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.104           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.676           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.158           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.261           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.640           ms/op
ClientGrpc.getUser                        sample  243276   3.945 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.008           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.250           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.815           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.990           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.382           ms/op
ClientGrpc.listUser                       sample  186896   5.135 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.007           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.471           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.585           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          23.534           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.517           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.702           ms/op
