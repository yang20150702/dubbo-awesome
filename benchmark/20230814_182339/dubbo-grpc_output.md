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
# Warmup Iteration   1: 2.117 ops/ms
# Warmup Iteration   2: 4.920 ops/ms
# Warmup Iteration   3: 6.721 ops/ms
Iteration   1: 6.930 ops/ms
Iteration   2: 6.990 ops/ms
Iteration   3: 7.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.993 ±(99.9%) 1.180 ops/ms [Average]
  (min, avg, max) = (6.930, 6.993, 7.060), stdev = 0.065
  CI (99.9%): [5.813, 8.174] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.742 ops/ms
# Warmup Iteration   2: 7.178 ops/ms
# Warmup Iteration   3: 7.493 ops/ms
Iteration   1: 7.398 ops/ms
Iteration   2: 7.832 ops/ms
Iteration   3: 7.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.672 ±(99.9%) 4.347 ops/ms [Average]
  (min, avg, max) = (7.398, 7.672, 7.832), stdev = 0.238
  CI (99.9%): [3.325, 12.020] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ops/ms
# Warmup Iteration   2: 6.520 ops/ms
# Warmup Iteration   3: 6.912 ops/ms
Iteration   1: 7.182 ops/ms
Iteration   2: 7.184 ops/ms
Iteration   3: 7.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.216 ±(99.9%) 1.060 ops/ms [Average]
  (min, avg, max) = (7.182, 7.216, 7.284), stdev = 0.058
  CI (99.9%): [6.156, 8.277] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.680 ops/ms
# Warmup Iteration   2: 5.046 ops/ms
# Warmup Iteration   3: 5.336 ops/ms
Iteration   1: 5.522 ops/ms
Iteration   2: 5.610 ops/ms
Iteration   3: 5.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.567 ±(99.9%) 0.804 ops/ms [Average]
  (min, avg, max) = (5.522, 5.567, 5.610), stdev = 0.044
  CI (99.9%): [4.763, 6.370] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.941 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.717 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.612 ±(99.9%) 0.012 ms/op
Iteration   1: 4.554 ±(99.9%) 0.004 ms/op
Iteration   2: 4.547 ±(99.9%) 0.006 ms/op
Iteration   3: 4.482 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.527 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (4.482, 4.527, 4.554), stdev = 0.040
  CI (99.9%): [3.802, 5.252] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.431 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.738 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.134 ±(99.9%) 0.005 ms/op
Iteration   1: 4.144 ±(99.9%) 0.003 ms/op
Iteration   2: 4.155 ±(99.9%) 0.005 ms/op
Iteration   3: 4.224 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.174 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (4.144, 4.174, 4.224), stdev = 0.043
  CI (99.9%): [3.388, 4.961] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.724 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.900 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.555 ±(99.9%) 0.015 ms/op
Iteration   1: 4.578 ±(99.9%) 0.005 ms/op
Iteration   2: 4.416 ±(99.9%) 0.006 ms/op
Iteration   3: 4.305 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.433 ±(99.9%) 2.510 ms/op [Average]
  (min, avg, max) = (4.305, 4.433, 4.578), stdev = 0.138
  CI (99.9%): [1.923, 6.943] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.355 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 6.298 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.903 ±(99.9%) 0.016 ms/op
Iteration   1: 5.824 ±(99.9%) 0.023 ms/op
Iteration   2: 5.915 ±(99.9%) 0.015 ms/op
Iteration   3: 5.966 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.902 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (5.824, 5.902, 5.966), stdev = 0.072
  CI (99.9%): [4.593, 7.210] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.979 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.980 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.551 ±(99.9%) 0.016 ms/op
Iteration   1: 4.402 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.669 ms/op
                 createUser·p0.95:   6.455 ms/op
                 createUser·p0.99:   9.486 ms/op
                 createUser·p0.999:  15.145 ms/op
                 createUser·p0.9999: 21.708 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   2: 4.415 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.734 ms/op
                 createUser·p0.95:   6.359 ms/op
                 createUser·p0.99:   8.714 ms/op
                 createUser·p0.999:  17.433 ms/op
                 createUser·p0.9999: 27.713 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 4.546 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.906 ms/op
                 createUser·p0.95:   6.619 ms/op
                 createUser·p0.99:   9.009 ms/op
                 createUser·p0.999:  12.305 ms/op
                 createUser·p0.9999: 26.801 ms/op
                 createUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215465
  mean =      4.453 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5489 
    [ 2.500,  5.000) = 160063 
    [ 5.000,  7.500) = 44491 
    [ 7.500, 10.000) = 4022 
    [10.000, 12.500) = 922 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.480 ms/op
     p(99.0000) =      9.066 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     27.114 ms/op
     p(99.9990) =     28.339 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.142 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.014 ms/op
Iteration   1: 4.158 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   8.978 ms/op
                 existUser·p0.999:  12.896 ms/op
                 existUser·p0.9999: 23.210 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 4.242 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   6.095 ms/op
                 existUser·p0.99:   8.651 ms/op
                 existUser·p0.999:  14.666 ms/op
                 existUser·p0.9999: 19.988 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   3: 4.138 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   8.667 ms/op
                 existUser·p0.999:  11.968 ms/op
                 existUser·p0.9999: 24.667 ms/op
                 existUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229710
  mean =      4.179 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8703 
    [ 2.500,  5.000) = 189073 
    [ 5.000,  7.500) = 27530 
    [ 7.500, 10.000) = 3323 
    [10.000, 12.500) = 803 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     25.268 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.589 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.685 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.347 ±(99.9%) 0.015 ms/op
Iteration   1: 4.309 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   4.149 ms/op
                 getUser·p0.90:   5.497 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  16.495 ms/op
                 getUser·p0.9999: 21.141 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   2: 4.354 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.234 ms/op
                 getUser·p0.99:   9.093 ms/op
                 getUser·p0.999:  13.569 ms/op
                 getUser·p0.9999: 18.753 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   3: 4.398 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.579 ms/op
                 getUser·p0.95:   6.227 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  12.607 ms/op
                 getUser·p0.9999: 22.109 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 220440
  mean =      4.353 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7055 
    [ 2.500,  5.000) = 170988 
    [ 5.000,  7.500) = 38082 
    [ 7.500, 10.000) = 3271 
    [10.000, 12.500) = 638 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     14.460 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     22.144 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.147 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.523 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.722 ±(99.9%) 0.025 ms/op
Iteration   1: 5.688 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  18.252 ms/op
                 listUser·p0.9999: 24.052 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   2: 5.583 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  20.567 ms/op
                 listUser·p0.9999: 24.135 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   3: 5.666 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.265 ms/op
                 listUser·p0.999:  20.662 ms/op
                 listUser·p0.9999: 23.233 ms/op
                 listUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 170016
  mean =      5.645 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 65216 
    [ 5.000,  7.500) = 86280 
    [ 7.500, 10.000) = 14647 
    [10.000, 12.500) = 2700 
    [12.500, 15.000) = 709 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     24.723 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.993 ± 1.180  ops/ms
ClientGrpc.existUser                       thrpt       3   7.672 ± 4.347  ops/ms
ClientGrpc.getUser                         thrpt       3   7.216 ± 1.060  ops/ms
ClientGrpc.listUser                        thrpt       3   5.567 ± 0.804  ops/ms
ClientGrpc.createUser                       avgt       3   4.527 ± 0.725   ms/op
ClientGrpc.existUser                        avgt       3   4.174 ± 0.787   ms/op
ClientGrpc.getUser                          avgt       3   4.433 ± 2.510   ms/op
ClientGrpc.listUser                         avgt       3   5.902 ± 1.309   ms/op
ClientGrpc.createUser                     sample  215465   4.453 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.837           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.775           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.480           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.066           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.155           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.114           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.065           ms/op
ClientGrpc.existUser                      sample  229710   4.179 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.945           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.022           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.267           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.997           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.700           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.976           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.298           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.362           ms/op
ClientGrpc.getUser                        sample  220440   4.353 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.952           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.546           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.185           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.716           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.460           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.365           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.151           ms/op
ClientGrpc.listUser                       sample  170016   5.645 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.571           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.292           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.627           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.485           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.104           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.691           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.838           ms/op
