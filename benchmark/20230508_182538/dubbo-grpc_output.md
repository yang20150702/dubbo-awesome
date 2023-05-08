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
# Warmup Iteration   1: 1.883 ops/ms
# Warmup Iteration   2: 5.033 ops/ms
# Warmup Iteration   3: 6.576 ops/ms
Iteration   1: 6.777 ops/ms
Iteration   2: 6.939 ops/ms
Iteration   3: 6.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.896 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (6.777, 6.896, 6.973), stdev = 0.105
  CI (99.9%): [4.985, 8.808] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.600 ops/ms
# Warmup Iteration   2: 6.658 ops/ms
# Warmup Iteration   3: 7.186 ops/ms
Iteration   1: 7.193 ops/ms
Iteration   2: 7.363 ops/ms
Iteration   3: 7.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.450 ±(99.9%) 5.658 ops/ms [Average]
  (min, avg, max) = (7.193, 7.450, 7.794), stdev = 0.310
  CI (99.9%): [1.792, 13.108] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.780 ops/ms
# Warmup Iteration   2: 6.129 ops/ms
# Warmup Iteration   3: 6.880 ops/ms
Iteration   1: 6.984 ops/ms
Iteration   2: 7.156 ops/ms
Iteration   3: 7.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.130 ±(99.9%) 2.459 ops/ms [Average]
  (min, avg, max) = (6.984, 7.130, 7.249), stdev = 0.135
  CI (99.9%): [4.671, 9.589] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.175 ops/ms
# Warmup Iteration   2: 4.751 ops/ms
# Warmup Iteration   3: 5.060 ops/ms
Iteration   1: 5.144 ops/ms
Iteration   2: 5.264 ops/ms
Iteration   3: 5.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.189 ±(99.9%) 1.187 ops/ms [Average]
  (min, avg, max) = (5.144, 5.189, 5.264), stdev = 0.065
  CI (99.9%): [4.003, 6.376] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.060 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.768 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.678 ±(99.9%) 0.010 ms/op
Iteration   1: 4.554 ±(99.9%) 0.004 ms/op
Iteration   2: 4.478 ±(99.9%) 0.004 ms/op
Iteration   3: 4.590 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.541 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (4.478, 4.541, 4.590), stdev = 0.057
  CI (99.9%): [3.502, 5.580] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.371 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.712 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.312 ±(99.9%) 0.005 ms/op
Iteration   1: 4.619 ±(99.9%) 0.003 ms/op
Iteration   2: 4.364 ±(99.9%) 0.003 ms/op
Iteration   3: 4.277 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.420 ±(99.9%) 3.236 ms/op [Average]
  (min, avg, max) = (4.277, 4.420, 4.619), stdev = 0.177
  CI (99.9%): [1.184, 7.657] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.441 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.211 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.652 ±(99.9%) 0.007 ms/op
Iteration   1: 4.697 ±(99.9%) 0.004 ms/op
Iteration   2: 4.452 ±(99.9%) 0.004 ms/op
Iteration   3: 4.792 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.647 ±(99.9%) 3.198 ms/op [Average]
  (min, avg, max) = (4.452, 4.647, 4.792), stdev = 0.175
  CI (99.9%): [1.449, 7.845] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.406 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 7.021 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 6.226 ±(99.9%) 0.024 ms/op
Iteration   1: 5.976 ±(99.9%) 0.019 ms/op
Iteration   2: 5.823 ±(99.9%) 0.012 ms/op
Iteration   3: 5.974 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.924 ±(99.9%) 1.595 ms/op [Average]
  (min, avg, max) = (5.823, 5.924, 5.976), stdev = 0.087
  CI (99.9%): [4.329, 7.520] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.515 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.001 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.665 ±(99.9%) 0.014 ms/op
Iteration   1: 4.833 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   4.694 ms/op
                 createUser·p0.90:   6.062 ms/op
                 createUser·p0.95:   6.496 ms/op
                 createUser·p0.99:   7.917 ms/op
                 createUser·p0.999:  14.171 ms/op
                 createUser·p0.9999: 22.786 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 4.621 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   4.473 ms/op
                 createUser·p0.90:   5.841 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  12.923 ms/op
                 createUser·p0.9999: 22.156 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   3: 4.809 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   5.925 ms/op
                 createUser·p0.95:   6.283 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  16.390 ms/op
                 createUser·p0.9999: 32.058 ms/op
                 createUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 201974
  mean =      4.752 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2137 
    [ 2.500,  5.000) = 128385 
    [ 5.000,  7.500) = 68993 
    [ 7.500, 10.000) = 1823 
    [10.000, 12.500) = 347 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.349 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     31.674 ms/op
     p(99.9990) =     32.210 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.631 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.840 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.492 ±(99.9%) 0.012 ms/op
Iteration   1: 4.450 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.513 ms/op
                 existUser·p0.95:   6.005 ms/op
                 existUser·p0.99:   7.496 ms/op
                 existUser·p0.999:  10.148 ms/op
                 existUser·p0.9999: 24.216 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   2: 4.254 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   4.186 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   7.505 ms/op
                 existUser·p0.999:  14.533 ms/op
                 existUser·p0.9999: 18.889 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   3: 4.313 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.308 ms/op
                 existUser·p0.95:   5.702 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  10.863 ms/op
                 existUser·p0.9999: 22.643 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 221353
  mean =      4.338 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5035 
    [ 2.500,  5.000) = 177989 
    [ 5.000,  7.500) = 36346 
    [ 7.500, 10.000) = 1484 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     12.648 ms/op
     p(99.9900) =     23.879 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.332 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.128 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.703 ±(99.9%) 0.017 ms/op
Iteration   1: 4.912 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   6.070 ms/op
                 getUser·p0.95:   6.603 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  15.825 ms/op
                 getUser·p0.9999: 18.709 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   2: 4.715 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   4.612 ms/op
                 getUser·p0.90:   5.833 ms/op
                 getUser·p0.95:   6.341 ms/op
                 getUser·p0.99:   8.090 ms/op
                 getUser·p0.999:  15.678 ms/op
                 getUser·p0.9999: 21.065 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   3: 4.809 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   4.669 ms/op
                 getUser·p0.90:   6.046 ms/op
                 getUser·p0.95:   6.595 ms/op
                 getUser·p0.99:   8.499 ms/op
                 getUser·p0.999:  14.080 ms/op
                 getUser·p0.9999: 20.873 ms/op
                 getUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 199457
  mean =      4.810 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2117 
    [ 2.500,  5.000) = 125297 
    [ 5.000,  7.500) = 68262 
    [ 7.500, 10.000) = 2959 
    [10.000, 12.500) = 488 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     20.777 ms/op
     p(99.9990) =     21.803 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.054 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 6.782 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.264 ±(99.9%) 0.028 ms/op
Iteration   1: 6.312 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   8.716 ms/op
                 listUser·p0.95:   9.699 ms/op
                 listUser·p0.99:   12.485 ms/op
                 listUser·p0.999:  25.516 ms/op
                 listUser·p0.9999: 30.173 ms/op
                 listUser·p1.00:   32.702 ms/op

Iteration   2: 6.462 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   8.875 ms/op
                 listUser·p0.95:   9.912 ms/op
                 listUser·p0.99:   12.730 ms/op
                 listUser·p0.999:  22.954 ms/op
                 listUser·p0.9999: 44.437 ms/op
                 listUser·p1.00:   44.892 ms/op

Iteration   3: 6.269 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   11.764 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 37.269 ms/op
                 listUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 151239
  mean =      6.346 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 29027 
    [ 5.000, 10.000) = 116031 
    [10.000, 15.000) = 5660 
    [15.000, 20.000) = 230 
    [20.000, 25.000) = 170 
    [25.000, 30.000) = 53 
    [30.000, 35.000) = 22 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      5.956 ms/op
     p(90.0000) =      8.700 ms/op
     p(95.0000) =      9.716 ms/op
     p(99.0000) =     12.272 ms/op
     p(99.9000) =     22.897 ms/op
     p(99.9900) =     42.713 ms/op
     p(99.9990) =     44.859 ms/op
     p(99.9999) =     44.892 ms/op
    p(100.0000) =     44.892 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.896 ± 1.912  ops/ms
ClientGrpc.existUser                       thrpt       3   7.450 ± 5.658  ops/ms
ClientGrpc.getUser                         thrpt       3   7.130 ± 2.459  ops/ms
ClientGrpc.listUser                        thrpt       3   5.189 ± 1.187  ops/ms
ClientGrpc.createUser                       avgt       3   4.541 ± 1.039   ms/op
ClientGrpc.existUser                        avgt       3   4.420 ± 3.236   ms/op
ClientGrpc.getUser                          avgt       3   4.647 ± 3.198   ms/op
ClientGrpc.listUser                         avgt       3   5.924 ± 1.595   ms/op
ClientGrpc.createUser                     sample  201974   4.752 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.916           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.947           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.349           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.750           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.435           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.674           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.276           ms/op
ClientGrpc.existUser                      sample  221353   4.338 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.770           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.349           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.816           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.356           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.648           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.879           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.478           ms/op
ClientGrpc.getUser                        sample  199457   4.810 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.151           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.988           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.513           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.352           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.777           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.019           ms/op
ClientGrpc.listUser                       sample  151239   6.346 ± 0.017   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.036           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.700           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.716           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.272           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.897           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          42.713           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          44.892           ms/op
