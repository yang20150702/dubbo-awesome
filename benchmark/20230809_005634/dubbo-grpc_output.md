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
# Warmup Iteration   1: 2.289 ops/ms
# Warmup Iteration   2: 5.335 ops/ms
# Warmup Iteration   3: 6.750 ops/ms
Iteration   1: 7.125 ops/ms
Iteration   2: 7.219 ops/ms
Iteration   3: 7.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.169 ±(99.9%) 0.860 ops/ms [Average]
  (min, avg, max) = (7.125, 7.169, 7.219), stdev = 0.047
  CI (99.9%): [6.309, 8.029] (assumes normal distribution)


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
# Warmup Iteration   1: 4.630 ops/ms
# Warmup Iteration   2: 7.226 ops/ms
# Warmup Iteration   3: 7.798 ops/ms
Iteration   1: 7.811 ops/ms
Iteration   2: 7.929 ops/ms
Iteration   3: 7.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.822 ±(99.9%) 1.853 ops/ms [Average]
  (min, avg, max) = (7.727, 7.822, 7.929), stdev = 0.102
  CI (99.9%): [5.970, 9.675] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.325 ops/ms
# Warmup Iteration   2: 6.670 ops/ms
# Warmup Iteration   3: 6.810 ops/ms
Iteration   1: 7.330 ops/ms
Iteration   2: 7.170 ops/ms
Iteration   3: 7.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.249 ±(99.9%) 1.460 ops/ms [Average]
  (min, avg, max) = (7.170, 7.249, 7.330), stdev = 0.080
  CI (99.9%): [5.790, 8.709] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.464 ops/ms
# Warmup Iteration   2: 5.342 ops/ms
# Warmup Iteration   3: 5.614 ops/ms
Iteration   1: 5.596 ops/ms
Iteration   2: 5.673 ops/ms
Iteration   3: 5.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.686 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (5.596, 5.686, 5.791), stdev = 0.098
  CI (99.9%): [3.891, 7.482] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.756 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.548 ±(99.9%) 0.023 ms/op
Iteration   1: 4.464 ±(99.9%) 0.004 ms/op
Iteration   2: 4.376 ±(99.9%) 0.003 ms/op
Iteration   3: 4.348 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.396 ±(99.9%) 1.098 ms/op [Average]
  (min, avg, max) = (4.348, 4.396, 4.464), stdev = 0.060
  CI (99.9%): [3.298, 5.494] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.408 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.477 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.229 ±(99.9%) 0.003 ms/op
Iteration   1: 4.081 ±(99.9%) 0.005 ms/op
Iteration   2: 4.171 ±(99.9%) 0.003 ms/op
Iteration   3: 4.164 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.139 ±(99.9%) 0.905 ms/op [Average]
  (min, avg, max) = (4.081, 4.139, 4.171), stdev = 0.050
  CI (99.9%): [3.233, 5.044] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.700 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.668 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.615 ±(99.9%) 0.007 ms/op
Iteration   1: 4.435 ±(99.9%) 0.006 ms/op
Iteration   2: 4.400 ±(99.9%) 0.005 ms/op
Iteration   3: 4.411 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.415 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (4.400, 4.415, 4.435), stdev = 0.018
  CI (99.9%): [4.088, 4.743] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.999 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 6.128 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.687 ±(99.9%) 0.024 ms/op
Iteration   1: 5.852 ±(99.9%) 0.025 ms/op
Iteration   2: 5.887 ±(99.9%) 0.027 ms/op
Iteration   3: 5.838 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.859 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (5.838, 5.859, 5.887), stdev = 0.025
  CI (99.9%): [5.401, 6.317] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.711 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.831 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.364 ±(99.9%) 0.014 ms/op
Iteration   1: 4.536 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.693 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   8.020 ms/op
                 createUser·p0.999:  12.936 ms/op
                 createUser·p0.9999: 15.630 ms/op
                 createUser·p1.00:   16.466 ms/op

Iteration   2: 4.428 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.497 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  15.647 ms/op
                 createUser·p0.9999: 20.614 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   3: 4.363 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.882 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  13.196 ms/op
                 createUser·p0.9999: 28.705 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216104
  mean =      4.441 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3653 
    [ 2.500,  5.000) = 164385 
    [ 5.000,  7.500) = 45649 
    [ 7.500, 10.000) = 1786 
    [10.000, 12.500) = 353 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.554 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     26.194 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.842 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.013 ms/op
Iteration   1: 4.185 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   7.848 ms/op
                 existUser·p0.999:  13.088 ms/op
                 existUser·p0.9999: 14.309 ms/op
                 existUser·p1.00:   15.647 ms/op

Iteration   2: 4.236 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   8.045 ms/op
                 existUser·p0.999:  14.737 ms/op
                 existUser·p0.9999: 18.135 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   3: 4.138 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   4.043 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   7.971 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 22.104 ms/op
                 existUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229188
  mean =      4.186 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8368 
    [ 2.500,  5.000) = 185987 
    [ 5.000,  7.500) = 31919 
    [ 7.500, 10.000) = 2289 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     12.989 ms/op
     p(99.9900) =     21.498 ms/op
     p(99.9990) =     22.305 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.396 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.759 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.512 ±(99.9%) 0.015 ms/op
Iteration   1: 4.494 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   7.971 ms/op
                 getUser·p0.999:  11.296 ms/op
                 getUser·p0.9999: 17.629 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   2: 4.473 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.669 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   7.814 ms/op
                 getUser·p0.999:  13.312 ms/op
                 getUser·p0.9999: 21.982 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   3: 4.467 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   7.848 ms/op
                 getUser·p0.999:  11.796 ms/op
                 getUser·p0.9999: 24.374 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214375
  mean =      4.478 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4896 
    [ 2.500,  5.000) = 158786 
    [ 5.000,  7.500) = 47862 
    [ 7.500, 10.000) = 2212 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     12.587 ms/op
     p(99.9900) =     23.583 ms/op
     p(99.9990) =     24.787 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 8.698 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.556 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.974 ±(99.9%) 0.024 ms/op
Iteration   1: 5.741 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  16.635 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 5.707 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.619 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  20.829 ms/op
                 listUser·p0.9999: 26.664 ms/op
                 listUser·p1.00:   30.376 ms/op

Iteration   3: 5.676 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.338 ms/op
                 listUser·p0.999:  22.139 ms/op
                 listUser·p0.9999: 29.503 ms/op
                 listUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168196
  mean =      5.708 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 133 
    [ 2.500,  5.000) = 57681 
    [ 5.000,  7.500) = 91856 
    [ 7.500, 10.000) = 15027 
    [10.000, 12.500) = 2655 
    [12.500, 15.000) = 427 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.559 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.660 ms/op
     p(95.0000) =      8.733 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     28.511 ms/op
     p(99.9990) =     30.309 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.169 ± 0.860  ops/ms
ClientGrpc.existUser                       thrpt       3   7.822 ± 1.853  ops/ms
ClientGrpc.getUser                         thrpt       3   7.249 ± 1.460  ops/ms
ClientGrpc.listUser                        thrpt       3   5.686 ± 1.795  ops/ms
ClientGrpc.createUser                       avgt       3   4.396 ± 1.098   ms/op
ClientGrpc.existUser                        avgt       3   4.139 ± 0.905   ms/op
ClientGrpc.getUser                          avgt       3   4.415 ± 0.328   ms/op
ClientGrpc.listUser                         avgt       3   5.859 ± 0.458   ms/op
ClientGrpc.createUser                     sample  216104   4.441 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.888           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.554           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.997           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.692           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.057           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.194           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.098           ms/op
ClientGrpc.existUser                      sample  229188   4.186 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.603           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.808           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.954           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.989           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.498           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.413           ms/op
ClientGrpc.getUser                        sample  214375   4.478 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.957           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.119           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.889           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.587           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.583           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.936           ms/op
ClientGrpc.listUser                       sample  168196   5.708 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.559           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.382           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.660           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.733           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.141           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.661           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.511           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.376           ms/op
