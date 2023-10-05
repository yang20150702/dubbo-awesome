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
# Warmup Iteration   1: 2.129 ops/ms
# Warmup Iteration   2: 5.267 ops/ms
# Warmup Iteration   3: 7.274 ops/ms
Iteration   1: 7.477 ops/ms
Iteration   2: 7.555 ops/ms
Iteration   3: 7.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.472 ±(99.9%) 1.567 ops/ms [Average]
  (min, avg, max) = (7.384, 7.472, 7.555), stdev = 0.086
  CI (99.9%): [5.905, 9.039] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ops/ms
# Warmup Iteration   2: 6.936 ops/ms
# Warmup Iteration   3: 7.815 ops/ms
Iteration   1: 8.256 ops/ms
Iteration   2: 8.194 ops/ms
Iteration   3: 8.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.172 ±(99.9%) 1.775 ops/ms [Average]
  (min, avg, max) = (8.065, 8.172, 8.256), stdev = 0.097
  CI (99.9%): [6.396, 9.947] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.183 ops/ms
# Warmup Iteration   2: 6.867 ops/ms
# Warmup Iteration   3: 7.349 ops/ms
Iteration   1: 7.307 ops/ms
Iteration   2: 7.602 ops/ms
Iteration   3: 7.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.475 ±(99.9%) 2.776 ops/ms [Average]
  (min, avg, max) = (7.307, 7.475, 7.602), stdev = 0.152
  CI (99.9%): [4.699, 10.252] (assumes normal distribution)


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
# Warmup Iteration   1: 3.668 ops/ms
# Warmup Iteration   2: 5.341 ops/ms
# Warmup Iteration   3: 5.828 ops/ms
Iteration   1: 5.940 ops/ms
Iteration   2: 5.996 ops/ms
Iteration   3: 5.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.975 ±(99.9%) 0.552 ops/ms [Average]
  (min, avg, max) = (5.940, 5.975, 5.996), stdev = 0.030
  CI (99.9%): [5.422, 6.527] (assumes normal distribution)


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
# Warmup Iteration   1: 6.643 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.513 ±(99.9%) 0.011 ms/op
Iteration   1: 4.223 ±(99.9%) 0.005 ms/op
Iteration   2: 4.411 ±(99.9%) 0.005 ms/op
Iteration   3: 4.299 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.311 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (4.223, 4.311, 4.411), stdev = 0.094
  CI (99.9%): [2.589, 6.032] (assumes normal distribution)


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
# Warmup Iteration   1: 6.057 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.004 ms/op
Iteration   1: 3.984 ±(99.9%) 0.003 ms/op
Iteration   2: 3.885 ±(99.9%) 0.004 ms/op
Iteration   3: 4.015 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.961 ±(99.9%) 1.237 ms/op [Average]
  (min, avg, max) = (3.885, 3.961, 4.015), stdev = 0.068
  CI (99.9%): [2.724, 5.198] (assumes normal distribution)


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
# Warmup Iteration   1: 6.757 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.321 ±(99.9%) 0.005 ms/op
Iteration   1: 4.335 ±(99.9%) 0.005 ms/op
Iteration   2: 4.419 ±(99.9%) 0.004 ms/op
Iteration   3: 4.324 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.359 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (4.324, 4.359, 4.419), stdev = 0.052
  CI (99.9%): [3.409, 5.310] (assumes normal distribution)


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
# Warmup Iteration   1: 7.603 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.861 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.486 ±(99.9%) 0.024 ms/op
Iteration   1: 5.391 ±(99.9%) 0.016 ms/op
Iteration   2: 5.426 ±(99.9%) 0.015 ms/op
Iteration   3: 5.215 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.344 ±(99.9%) 2.063 ms/op [Average]
  (min, avg, max) = (5.215, 5.344, 5.426), stdev = 0.113
  CI (99.9%): [3.281, 7.407] (assumes normal distribution)


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
# Warmup Iteration   1: 7.156 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.582 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.355 ±(99.9%) 0.014 ms/op
Iteration   1: 4.426 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.571 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   8.053 ms/op
                 createUser·p0.999:  15.200 ms/op
                 createUser·p0.9999: 17.836 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   2: 4.381 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   8.405 ms/op
                 createUser·p0.999:  19.234 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 4.318 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   4.162 ms/op
                 createUser·p0.90:   5.521 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   7.938 ms/op
                 createUser·p0.999:  11.482 ms/op
                 createUser·p0.9999: 20.368 ms/op
                 createUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219308
  mean =      4.374 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2744 
    [ 2.500,  5.000) = 172442 
    [ 5.000,  7.500) = 40961 
    [ 7.500, 10.000) = 2407 
    [10.000, 12.500) = 374 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     23.993 ms/op
     p(99.9990) =     28.604 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 6.468 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.014 ms/op
Iteration   1: 4.031 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   3.883 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.651 ms/op
                 existUser·p0.999:  13.200 ms/op
                 existUser·p0.9999: 20.058 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 3.881 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.423 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 18.777 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   3: 3.940 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   7.832 ms/op
                 existUser·p0.999:  16.000 ms/op
                 existUser·p0.9999: 23.097 ms/op
                 existUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243101
  mean =      3.950 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11185 
    [ 2.500,  5.000) = 208335 
    [ 5.000,  7.500) = 20969 
    [ 7.500, 10.000) = 1822 
    [10.000, 12.500) = 446 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     22.239 ms/op
     p(99.9990) =     25.021 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 7.300 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.602 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.014 ms/op
Iteration   1: 4.250 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   4.100 ms/op
                 getUser·p0.90:   5.284 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   7.900 ms/op
                 getUser·p0.999:  12.640 ms/op
                 getUser·p0.9999: 38.632 ms/op
                 getUser·p1.00:   38.928 ms/op

Iteration   2: 4.222 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   4.100 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   7.389 ms/op
                 getUser·p0.999:  12.619 ms/op
                 getUser·p0.9999: 22.474 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 4.310 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   8.069 ms/op
                 getUser·p0.999:  14.860 ms/op
                 getUser·p0.9999: 39.697 ms/op
                 getUser·p1.00:   41.746 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 225288
  mean =      4.260 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 187938 
    [ 5.000, 10.000) = 36590 
    [10.000, 15.000) = 574 
    [15.000, 20.000) = 50 
    [20.000, 25.000) = 69 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 61 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     14.593 ms/op
     p(99.9900) =     39.156 ms/op
     p(99.9990) =     41.566 ms/op
     p(99.9999) =     41.746 ms/op
    p(100.0000) =     41.746 ms/op


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
# Warmup Iteration   1: 8.417 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.844 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.536 ±(99.9%) 0.022 ms/op
Iteration   1: 5.558 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.813 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 19.882 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   2: 5.531 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  18.393 ms/op
                 listUser·p0.9999: 21.141 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 5.433 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   5.054 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.141 ms/op
                 listUser·p0.999:  22.479 ms/op
                 listUser·p0.9999: 31.374 ms/op
                 listUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174251
  mean =      5.507 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 375 
    [ 2.500,  5.000) = 76198 
    [ 5.000,  7.500) = 80480 
    [ 7.500, 10.000) = 13622 
    [10.000, 12.500) = 2541 
    [12.500, 15.000) = 648 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      7.479 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.338 ms/op
     p(99.9000) =     18.891 ms/op
     p(99.9900) =     29.458 ms/op
     p(99.9990) =     31.753 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.472 ± 1.567  ops/ms
ClientGrpc.existUser                       thrpt       3   8.172 ± 1.775  ops/ms
ClientGrpc.getUser                         thrpt       3   7.475 ± 2.776  ops/ms
ClientGrpc.listUser                        thrpt       3   5.975 ± 0.552  ops/ms
ClientGrpc.createUser                       avgt       3   4.311 ± 1.721   ms/op
ClientGrpc.existUser                        avgt       3   3.961 ± 1.237   ms/op
ClientGrpc.getUser                          avgt       3   4.359 ± 0.950   ms/op
ClientGrpc.listUser                         avgt       3   5.344 ± 2.063   ms/op
ClientGrpc.createUser                     sample  219308   4.374 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.947           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.078           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.094           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.565           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.993           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.705           ms/op
ClientGrpc.existUser                      sample  243101   3.950 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.803           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.826           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.981           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.521           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.602           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.206           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.239           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.526           ms/op
ClientGrpc.getUser                        sample  225288   4.260 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.637           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.349           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.816           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.807           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.593           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          39.156           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          41.746           ms/op
ClientGrpc.listUser                       sample  174251   5.507 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.903           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.479           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.338           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.891           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.458           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.850           ms/op
