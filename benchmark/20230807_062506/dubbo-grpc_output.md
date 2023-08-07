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
# Warmup Iteration   1: 2.084 ops/ms
# Warmup Iteration   2: 5.218 ops/ms
# Warmup Iteration   3: 7.174 ops/ms
Iteration   1: 7.220 ops/ms
Iteration   2: 7.428 ops/ms
Iteration   3: 7.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.321 ±(99.9%) 1.899 ops/ms [Average]
  (min, avg, max) = (7.220, 7.321, 7.428), stdev = 0.104
  CI (99.9%): [5.422, 9.220] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.296 ops/ms
# Warmup Iteration   2: 6.814 ops/ms
# Warmup Iteration   3: 7.607 ops/ms
Iteration   1: 7.952 ops/ms
Iteration   2: 8.134 ops/ms
Iteration   3: 8.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.038 ±(99.9%) 1.668 ops/ms [Average]
  (min, avg, max) = (7.952, 8.038, 8.134), stdev = 0.091
  CI (99.9%): [6.371, 9.706] (assumes normal distribution)


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
# Warmup Iteration   1: 4.531 ops/ms
# Warmup Iteration   2: 7.202 ops/ms
# Warmup Iteration   3: 7.545 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 7.644 ops/ms
Iteration   3: 7.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.750 ±(99.9%) 3.362 ops/ms [Average]
  (min, avg, max) = (7.644, 7.750, 7.963), stdev = 0.184
  CI (99.9%): [4.389, 11.112] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ops/ms
# Warmup Iteration   2: 6.240 ops/ms
# Warmup Iteration   3: 6.803 ops/ms
Iteration   1: 6.666 ops/ms
Iteration   2: 6.562 ops/ms
Iteration   3: 6.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.524 ±(99.9%) 2.989 ops/ms [Average]
  (min, avg, max) = (6.345, 6.524, 6.666), stdev = 0.164
  CI (99.9%): [3.535, 9.513] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.339 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.008 ms/op
Iteration   1: 4.248 ±(99.9%) 0.007 ms/op
Iteration   2: 4.105 ±(99.9%) 0.004 ms/op
Iteration   3: 4.134 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.162 ±(99.9%) 1.381 ms/op [Average]
  (min, avg, max) = (4.105, 4.162, 4.248), stdev = 0.076
  CI (99.9%): [2.781, 5.543] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.379 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.003 ms/op
Iteration   1: 3.513 ±(99.9%) 0.003 ms/op
Iteration   2: 3.651 ±(99.9%) 0.003 ms/op
Iteration   3: 3.892 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.685 ±(99.9%) 3.499 ms/op [Average]
  (min, avg, max) = (3.513, 3.685, 3.892), stdev = 0.192
  CI (99.9%): [0.186, 7.184] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.799 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.003 ms/op
Iteration   1: 3.855 ±(99.9%) 0.015 ms/op
Iteration   2: 3.607 ±(99.9%) 0.003 ms/op
Iteration   3: 3.603 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.688 ±(99.9%) 2.626 ms/op [Average]
  (min, avg, max) = (3.603, 3.688, 3.855), stdev = 0.144
  CI (99.9%): [1.062, 6.315] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.107 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.523 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.034 ±(99.9%) 0.016 ms/op
Iteration   1: 5.226 ±(99.9%) 0.021 ms/op
Iteration   2: 5.011 ±(99.9%) 0.021 ms/op
Iteration   3: 4.934 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.057 ±(99.9%) 2.768 ms/op [Average]
  (min, avg, max) = (4.934, 5.057, 5.226), stdev = 0.152
  CI (99.9%): [2.289, 7.825] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.463 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.013 ms/op
Iteration   1: 4.068 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   5.104 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  11.639 ms/op
                 createUser·p0.9999: 20.873 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   2: 4.092 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   7.776 ms/op
                 createUser·p0.999:  16.768 ms/op
                 createUser·p0.9999: 26.357 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   3: 4.149 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.857 ms/op
                 createUser·p0.99:   8.140 ms/op
                 createUser·p0.999:  12.368 ms/op
                 createUser·p0.9999: 29.796 ms/op
                 createUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 233950
  mean =      4.103 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4694 
    [ 2.500,  5.000) = 200743 
    [ 5.000,  7.500) = 25836 
    [ 7.500, 10.000) = 1976 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     14.404 ms/op
     p(99.9900) =     27.376 ms/op
     p(99.9990) =     29.982 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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
# Warmup Iteration   1: 5.649 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.012 ms/op
Iteration   1: 3.890 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  11.740 ms/op
                 existUser·p0.9999: 19.195 ms/op
                 existUser·p1.00:   19.792 ms/op

Iteration   2: 3.948 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   5.505 ms/op
                 existUser·p0.99:   7.406 ms/op
                 existUser·p0.999:  14.352 ms/op
                 existUser·p0.9999: 26.989 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.827 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  11.083 ms/op
                 existUser·p0.9999: 42.505 ms/op
                 existUser·p1.00:   43.057 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 246953
  mean =      3.888 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 225676 
    [ 5.000, 10.000) = 20568 
    [10.000, 15.000) = 581 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 41 
    [25.000, 30.000) = 23 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     12.256 ms/op
     p(99.9900) =     41.191 ms/op
     p(99.9990) =     42.965 ms/op
     p(99.9999) =     43.057 ms/op
    p(100.0000) =     43.057 ms/op


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
# Warmup Iteration   1: 6.024 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.287 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.011 ms/op
Iteration   1: 4.120 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   7.945 ms/op
                 getUser·p0.999:  14.335 ms/op
                 getUser·p0.9999: 21.823 ms/op
                 getUser·p1.00:   22.217 ms/op

Iteration   2: 3.959 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.940 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  13.532 ms/op
                 getUser·p0.9999: 27.845 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   3: 3.887 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   7.225 ms/op
                 getUser·p0.999:  16.757 ms/op
                 getUser·p0.9999: 33.335 ms/op
                 getUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 240689
  mean =      3.986 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8623 
    [ 2.500,  5.000) = 208574 
    [ 5.000,  7.500) = 21197 
    [ 7.500, 10.000) = 1643 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     14.112 ms/op
     p(99.9900) =     28.569 ms/op
     p(99.9990) =     33.987 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.870 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.869 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.148 ±(99.9%) 0.018 ms/op
Iteration   1: 5.016 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   6.496 ms/op
                 listUser·p0.95:   7.430 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  14.635 ms/op
                 listUser·p0.9999: 18.279 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   2: 5.070 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.504 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   10.109 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 22.353 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 5.210 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   4.915 ms/op
                 listUser·p0.90:   6.828 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   10.337 ms/op
                 listUser·p0.999:  22.092 ms/op
                 listUser·p0.9999: 28.368 ms/op
                 listUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188404
  mean =      5.097 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 230 
    [ 2.500,  5.000) = 109018 
    [ 5.000,  7.500) = 69401 
    [ 7.500, 10.000) = 7763 
    [10.000, 12.500) = 1258 
    [12.500, 15.000) = 407 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.603 ms/op
     p(95.0000) =      7.553 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     17.354 ms/op
     p(99.9900) =     27.301 ms/op
     p(99.9990) =     28.868 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.321 ± 1.899  ops/ms
ClientGrpc.existUser                       thrpt       3   8.038 ± 1.668  ops/ms
ClientGrpc.getUser                         thrpt       3   7.750 ± 3.362  ops/ms
ClientGrpc.listUser                        thrpt       3   6.524 ± 2.989  ops/ms
ClientGrpc.createUser                       avgt       3   4.162 ± 1.381   ms/op
ClientGrpc.existUser                        avgt       3   3.685 ± 3.499   ms/op
ClientGrpc.getUser                          avgt       3   3.688 ± 2.626   ms/op
ClientGrpc.listUser                         avgt       3   5.057 ± 2.768   ms/op
ClientGrpc.createUser                     sample  233950   4.103 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.689           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.136           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.741           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.404           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.376           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.700           ms/op
ClientGrpc.existUser                      sample  246953   3.888 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.694           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.349           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.070           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.256           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          41.191           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          43.057           ms/op
ClientGrpc.getUser                        sample  240689   3.986 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.824           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.989           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.464           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.422           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.112           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.569           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.079           ms/op
ClientGrpc.listUser                       sample  188404   5.097 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.122           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.553           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.109           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.354           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.301           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.360           ms/op
