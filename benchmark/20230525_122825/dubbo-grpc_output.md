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
# Warmup Iteration   1: 3.263 ops/ms
# Warmup Iteration   2: 7.042 ops/ms
# Warmup Iteration   3: 8.362 ops/ms
Iteration   1: 8.695 ops/ms
Iteration   2: 8.670 ops/ms
Iteration   3: 8.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.692 ±(99.9%) 0.375 ops/ms [Average]
  (min, avg, max) = (8.670, 8.692, 8.711), stdev = 0.021
  CI (99.9%): [8.317, 9.067] (assumes normal distribution)


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
# Warmup Iteration   1: 6.078 ops/ms
# Warmup Iteration   2: 8.418 ops/ms
# Warmup Iteration   3: 8.980 ops/ms
Iteration   1: 9.261 ops/ms
Iteration   2: 9.448 ops/ms
Iteration   3: 9.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.356 ±(99.9%) 1.705 ops/ms [Average]
  (min, avg, max) = (9.261, 9.356, 9.448), stdev = 0.093
  CI (99.9%): [7.651, 11.062] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.469 ops/ms
# Warmup Iteration   2: 8.304 ops/ms
# Warmup Iteration   3: 8.654 ops/ms
Iteration   1: 8.688 ops/ms
Iteration   2: 8.804 ops/ms
Iteration   3: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.691 ±(99.9%) 2.031 ops/ms [Average]
  (min, avg, max) = (8.581, 8.691, 8.804), stdev = 0.111
  CI (99.9%): [6.660, 10.722] (assumes normal distribution)


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
# Warmup Iteration   1: 4.201 ops/ms
# Warmup Iteration   2: 6.282 ops/ms
# Warmup Iteration   3: 6.587 ops/ms
Iteration   1: 6.670 ops/ms
Iteration   2: 7.041 ops/ms
Iteration   3: 6.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.856 ±(99.9%) 3.388 ops/ms [Average]
  (min, avg, max) = (6.670, 6.856, 7.041), stdev = 0.186
  CI (99.9%): [3.468, 10.243] (assumes normal distribution)


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
# Warmup Iteration   1: 5.359 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.014 ms/op
Iteration   1: 3.648 ±(99.9%) 0.003 ms/op
Iteration   2: 3.635 ±(99.9%) 0.003 ms/op
Iteration   3: 3.629 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.637 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.629, 3.637, 3.648), stdev = 0.010
  CI (99.9%): [3.461, 3.814] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.853 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.004 ms/op
Iteration   1: 3.359 ±(99.9%) 0.005 ms/op
Iteration   2: 3.460 ±(99.9%) 0.003 ms/op
Iteration   3: 3.447 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.422 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (3.359, 3.422, 3.460), stdev = 0.055
  CI (99.9%): [2.426, 4.418] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.391 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.004 ms/op
Iteration   1: 3.611 ±(99.9%) 0.004 ms/op
Iteration   2: 3.539 ±(99.9%) 0.004 ms/op
Iteration   3: 3.537 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.562 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.537, 3.562, 3.611), stdev = 0.042
  CI (99.9%): [2.795, 4.330] (assumes normal distribution)


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
# Warmup Iteration   1: 6.265 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.940 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.765 ±(99.9%) 0.010 ms/op
Iteration   1: 4.866 ±(99.9%) 0.026 ms/op
Iteration   2: 4.695 ±(99.9%) 0.012 ms/op
Iteration   3: 4.692 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.751 ±(99.9%) 1.817 ms/op [Average]
  (min, avg, max) = (4.692, 4.751, 4.866), stdev = 0.100
  CI (99.9%): [2.933, 6.568] (assumes normal distribution)


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
# Warmup Iteration   1: 5.747 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.010 ms/op
Iteration   1: 3.762 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  12.139 ms/op
                 createUser·p0.9999: 15.090 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   2: 3.755 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  11.436 ms/op
                 createUser·p0.9999: 18.185 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   3: 3.659 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  16.678 ms/op
                 createUser·p0.9999: 30.876 ms/op
                 createUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257689
  mean =      3.725 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5413 
    [ 2.500,  5.000) = 244409 
    [ 5.000,  7.500) = 6906 
    [ 7.500, 10.000) = 617 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     12.064 ms/op
     p(99.9900) =     30.285 ms/op
     p(99.9990) =     31.130 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 4.889 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.008 ms/op
Iteration   1: 3.585 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.783 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 15.050 ms/op
                 existUser·p1.00:   15.696 ms/op

Iteration   2: 3.431 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 17.697 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   3: 3.550 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  10.566 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272392
  mean =      3.521 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11749 
    [ 2.500,  5.000) = 255427 
    [ 5.000,  7.500) = 4462 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     18.475 ms/op
     p(99.9990) =     19.650 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 5.528 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.009 ms/op
Iteration   1: 3.633 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   5.788 ms/op
                 getUser·p0.999:  11.855 ms/op
                 getUser·p0.9999: 16.810 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   2: 3.639 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  8.962 ms/op
                 getUser·p0.9999: 16.686 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   3: 3.667 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  10.653 ms/op
                 getUser·p0.9999: 20.531 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263242
  mean =      3.646 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6629 
    [ 2.500,  5.000) = 250683 
    [ 5.000,  7.500) = 5232 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     19.421 ms/op
     p(99.9990) =     22.044 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 7.089 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.129 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.759 ±(99.9%) 0.015 ms/op
Iteration   1: 4.623 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.660 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  15.904 ms/op
                 listUser·p0.9999: 18.624 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 4.764 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.734 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  16.740 ms/op
                 listUser·p0.9999: 19.386 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 4.806 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.300 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  20.637 ms/op
                 listUser·p0.9999: 24.676 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203016
  mean =      4.730 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 457 
    [ 2.500,  5.000) = 156528 
    [ 5.000,  7.500) = 39999 
    [ 7.500, 10.000) = 5153 
    [10.000, 12.500) = 485 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.972 ms/op
     p(95.0000) =      6.939 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     25.163 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.692 ± 0.375  ops/ms
ClientGrpc.existUser                       thrpt       3   9.356 ± 1.705  ops/ms
ClientGrpc.getUser                         thrpt       3   8.691 ± 2.031  ops/ms
ClientGrpc.listUser                        thrpt       3   6.856 ± 3.388  ops/ms
ClientGrpc.createUser                       avgt       3   3.637 ± 0.177   ms/op
ClientGrpc.existUser                        avgt       3   3.422 ± 0.996   ms/op
ClientGrpc.getUser                          avgt       3   3.562 ± 0.768   ms/op
ClientGrpc.listUser                         avgt       3   4.751 ± 1.817   ms/op
ClientGrpc.createUser                     sample  257689   3.725 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.743           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.064           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.285           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.293           ms/op
ClientGrpc.existUser                      sample  272392   3.521 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.653           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.603           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.322           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.475           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.054           ms/op
ClientGrpc.getUser                        sample  263242   3.646 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.919           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.781           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.421           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.151           ms/op
ClientGrpc.listUser                       sample  203016   4.730 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.174           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.972           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.700           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.810           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.577           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.231           ms/op
