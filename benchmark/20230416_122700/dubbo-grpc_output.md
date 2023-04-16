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
# Warmup Iteration   1: 2.021 ops/ms
# Warmup Iteration   2: 5.021 ops/ms
# Warmup Iteration   3: 6.677 ops/ms
Iteration   1: 6.834 ops/ms
Iteration   2: 7.154 ops/ms
Iteration   3: 7.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.003 ±(99.9%) 2.935 ops/ms [Average]
  (min, avg, max) = (6.834, 7.003, 7.154), stdev = 0.161
  CI (99.9%): [4.068, 9.938] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ops/ms
# Warmup Iteration   2: 6.748 ops/ms
# Warmup Iteration   3: 7.078 ops/ms
Iteration   1: 7.369 ops/ms
Iteration   2: 7.463 ops/ms
Iteration   3: 7.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.385 ±(99.9%) 1.307 ops/ms [Average]
  (min, avg, max) = (7.323, 7.385, 7.463), stdev = 0.072
  CI (99.9%): [6.078, 8.692] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.807 ops/ms
# Warmup Iteration   2: 6.263 ops/ms
# Warmup Iteration   3: 6.815 ops/ms
Iteration   1: 7.239 ops/ms
Iteration   2: 7.057 ops/ms
Iteration   3: 7.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.151 ±(99.9%) 1.658 ops/ms [Average]
  (min, avg, max) = (7.057, 7.151, 7.239), stdev = 0.091
  CI (99.9%): [5.493, 8.809] (assumes normal distribution)


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
# Warmup Iteration   1: 3.345 ops/ms
# Warmup Iteration   2: 5.040 ops/ms
# Warmup Iteration   3: 5.364 ops/ms
Iteration   1: 5.481 ops/ms
Iteration   2: 5.496 ops/ms
Iteration   3: 5.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.514 ±(99.9%) 0.808 ops/ms [Average]
  (min, avg, max) = (5.481, 5.514, 5.564), stdev = 0.044
  CI (99.9%): [4.706, 6.322] (assumes normal distribution)


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
# Warmup Iteration   1: 7.453 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.856 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.710 ±(99.9%) 0.020 ms/op
Iteration   1: 4.579 ±(99.9%) 0.004 ms/op
Iteration   2: 4.444 ±(99.9%) 0.005 ms/op
Iteration   3: 4.446 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.490 ±(99.9%) 1.419 ms/op [Average]
  (min, avg, max) = (4.444, 4.490, 4.579), stdev = 0.078
  CI (99.9%): [3.070, 5.909] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.915 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.324 ±(99.9%) 0.003 ms/op
Iteration   1: 4.199 ±(99.9%) 0.007 ms/op
Iteration   2: 4.247 ±(99.9%) 0.003 ms/op
Iteration   3: 4.165 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.204 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (4.165, 4.204, 4.247), stdev = 0.041
  CI (99.9%): [3.450, 4.957] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.331 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.979 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.542 ±(99.9%) 0.007 ms/op
Iteration   1: 4.723 ±(99.9%) 0.004 ms/op
Iteration   2: 4.473 ±(99.9%) 0.004 ms/op
Iteration   3: 4.473 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.556 ±(99.9%) 2.637 ms/op [Average]
  (min, avg, max) = (4.473, 4.556, 4.723), stdev = 0.145
  CI (99.9%): [1.920, 7.193] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.889 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.287 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.842 ±(99.9%) 0.016 ms/op
Iteration   1: 5.599 ±(99.9%) 0.016 ms/op
Iteration   2: 5.807 ±(99.9%) 0.028 ms/op
Iteration   3: 5.849 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.752 ±(99.9%) 2.445 ms/op [Average]
  (min, avg, max) = (5.599, 5.752, 5.849), stdev = 0.134
  CI (99.9%): [3.307, 8.197] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.076 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.189 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.896 ±(99.9%) 0.017 ms/op
Iteration   1: 4.733 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   4.563 ms/op
                 createUser·p0.90:   6.119 ms/op
                 createUser·p0.95:   6.603 ms/op
                 createUser·p0.99:   8.086 ms/op
                 createUser·p0.999:  12.091 ms/op
                 createUser·p0.9999: 16.556 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 4.634 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   5.857 ms/op
                 createUser·p0.95:   6.365 ms/op
                 createUser·p0.99:   7.774 ms/op
                 createUser·p0.999:  11.174 ms/op
                 createUser·p0.9999: 19.825 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   3: 4.661 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   4.530 ms/op
                 createUser·p0.90:   5.890 ms/op
                 createUser·p0.95:   6.373 ms/op
                 createUser·p0.99:   7.782 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 27.132 ms/op
                 createUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 205300
  mean =      4.676 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2079 
    [ 2.500,  5.000) = 139185 
    [ 5.000,  7.500) = 61108 
    [ 7.500, 10.000) = 2368 
    [10.000, 12.500) = 379 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.964 ms/op
     p(95.0000) =      6.455 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     12.157 ms/op
     p(99.9900) =     26.918 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 6.086 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.729 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.379 ±(99.9%) 0.014 ms/op
Iteration   1: 4.258 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   4.162 ms/op
                 existUser·p0.90:   5.415 ms/op
                 existUser·p0.95:   5.906 ms/op
                 existUser·p0.99:   7.537 ms/op
                 existUser·p0.999:  13.130 ms/op
                 existUser·p0.9999: 16.506 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   2: 4.289 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   4.170 ms/op
                 existUser·p0.90:   5.276 ms/op
                 existUser·p0.95:   5.751 ms/op
                 existUser·p0.99:   7.397 ms/op
                 existUser·p0.999:  10.656 ms/op
                 existUser·p0.9999: 20.518 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   3: 4.428 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   4.284 ms/op
                 existUser·p0.90:   5.546 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   7.717 ms/op
                 existUser·p0.999:  13.222 ms/op
                 existUser·p0.9999: 26.134 ms/op
                 existUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 222052
  mean =      4.324 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4866 
    [ 2.500,  5.000) = 176177 
    [ 5.000,  7.500) = 38713 
    [ 7.500, 10.000) = 1713 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     12.679 ms/op
     p(99.9900) =     24.923 ms/op
     p(99.9990) =     26.331 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 7.009 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.961 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.500 ±(99.9%) 0.013 ms/op
Iteration   1: 4.450 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.177 ms/op
                 getUser·p0.99:   8.143 ms/op
                 getUser·p0.999:  13.720 ms/op
                 getUser·p0.9999: 15.739 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   2: 4.456 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   8.048 ms/op
                 getUser·p0.999:  14.259 ms/op
                 getUser·p0.9999: 17.048 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   3: 4.468 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.497 ms/op
                 getUser·p0.95:   5.988 ms/op
                 getUser·p0.99:   7.848 ms/op
                 getUser·p0.999:  12.896 ms/op
                 getUser·p0.9999: 21.692 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215414
  mean =      4.458 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5215 
    [ 2.500,  5.000) = 163518 
    [ 5.000,  7.500) = 43738 
    [ 7.500, 10.000) = 2219 
    [10.000, 12.500) = 426 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.554 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     13.838 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     22.169 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 9.001 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.285 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.897 ±(99.9%) 0.023 ms/op
Iteration   1: 5.872 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   8.045 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   11.846 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 21.809 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   2: 6.030 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   8.274 ms/op
                 listUser·p0.95:   9.552 ms/op
                 listUser·p0.99:   13.615 ms/op
                 listUser·p0.999:  18.965 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 5.948 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   8.061 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   11.715 ms/op
                 listUser·p0.999:  22.355 ms/op
                 listUser·p0.9999: 27.480 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 161320
  mean =      5.950 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 47876 
    [ 5.000,  7.500) = 90003 
    [ 7.500, 10.000) = 18114 
    [10.000, 12.500) = 3748 
    [12.500, 15.000) = 824 
    [15.000, 17.500) = 360 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      5.538 ms/op
     p(90.0000) =      8.117 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     12.239 ms/op
     p(99.9000) =     19.738 ms/op
     p(99.9900) =     26.300 ms/op
     p(99.9990) =     27.825 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.003 ± 2.935  ops/ms
ClientGrpc.existUser                       thrpt       3   7.385 ± 1.307  ops/ms
ClientGrpc.getUser                         thrpt       3   7.151 ± 1.658  ops/ms
ClientGrpc.listUser                        thrpt       3   5.514 ± 0.808  ops/ms
ClientGrpc.createUser                       avgt       3   4.490 ± 1.419   ms/op
ClientGrpc.existUser                        avgt       3   4.204 ± 0.753   ms/op
ClientGrpc.getUser                          avgt       3   4.556 ± 2.637   ms/op
ClientGrpc.listUser                         avgt       3   5.752 ± 2.445   ms/op
ClientGrpc.createUser                     sample  205300   4.676 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.971           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.964           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.455           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.881           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.157           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.918           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.263           ms/op
ClientGrpc.existUser                      sample  222052   4.324 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.859           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.423           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.890           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.545           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.679           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.923           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.444           ms/op
ClientGrpc.getUser                        sample  215414   4.458 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.110           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.554           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.078           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.004           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.838           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.037           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.348           ms/op
ClientGrpc.listUser                       sample  161320   5.950 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.501           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.117           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.224           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.239           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.738           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.300           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.886           ms/op
