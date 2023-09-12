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
# Warmup Iteration   1: 2.303 ops/ms
# Warmup Iteration   2: 5.577 ops/ms
# Warmup Iteration   3: 6.788 ops/ms
Iteration   1: 6.915 ops/ms
Iteration   2: 6.960 ops/ms
Iteration   3: 6.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.892 ±(99.9%) 1.474 ops/ms [Average]
  (min, avg, max) = (6.803, 6.892, 6.960), stdev = 0.081
  CI (99.9%): [5.418, 8.366] (assumes normal distribution)


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
# Warmup Iteration   1: 4.379 ops/ms
# Warmup Iteration   2: 6.914 ops/ms
# Warmup Iteration   3: 7.487 ops/ms
Iteration   1: 7.884 ops/ms
Iteration   2: 7.796 ops/ms
Iteration   3: 8.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.895 ±(99.9%) 1.913 ops/ms [Average]
  (min, avg, max) = (7.796, 7.895, 8.005), stdev = 0.105
  CI (99.9%): [5.982, 9.808] (assumes normal distribution)


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
# Warmup Iteration   1: 3.986 ops/ms
# Warmup Iteration   2: 6.781 ops/ms
# Warmup Iteration   3: 7.044 ops/ms
Iteration   1: 7.221 ops/ms
Iteration   2: 7.272 ops/ms
Iteration   3: 7.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.238 ±(99.9%) 0.543 ops/ms [Average]
  (min, avg, max) = (7.220, 7.238, 7.272), stdev = 0.030
  CI (99.9%): [6.694, 7.781] (assumes normal distribution)


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
# Warmup Iteration   1: 3.514 ops/ms
# Warmup Iteration   2: 4.654 ops/ms
# Warmup Iteration   3: 5.494 ops/ms
Iteration   1: 5.492 ops/ms
Iteration   2: 5.660 ops/ms
Iteration   3: 5.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.544 ±(99.9%) 1.839 ops/ms [Average]
  (min, avg, max) = (5.480, 5.544, 5.660), stdev = 0.101
  CI (99.9%): [3.705, 7.383] (assumes normal distribution)


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
# Warmup Iteration   1: 7.010 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.684 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.003 ms/op
Iteration   1: 4.388 ±(99.9%) 0.004 ms/op
Iteration   2: 4.386 ±(99.9%) 0.004 ms/op
Iteration   3: 4.414 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.396 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (4.386, 4.396, 4.414), stdev = 0.016
  CI (99.9%): [4.112, 4.680] (assumes normal distribution)


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
# Warmup Iteration   1: 6.744 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.663 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.002 ms/op
Iteration   1: 4.115 ±(99.9%) 0.003 ms/op
Iteration   2: 4.205 ±(99.9%) 0.003 ms/op
Iteration   3: 4.217 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.179 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (4.115, 4.179, 4.217), stdev = 0.056
  CI (99.9%): [3.161, 5.197] (assumes normal distribution)


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
# Warmup Iteration   1: 6.693 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.949 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.547 ±(99.9%) 0.003 ms/op
Iteration   1: 4.498 ±(99.9%) 0.003 ms/op
Iteration   2: 4.536 ±(99.9%) 0.003 ms/op
Iteration   3: 4.643 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.559 ±(99.9%) 1.374 ms/op [Average]
  (min, avg, max) = (4.498, 4.559, 4.643), stdev = 0.075
  CI (99.9%): [3.185, 5.933] (assumes normal distribution)


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
# Warmup Iteration   1: 9.058 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 6.352 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.873 ±(99.9%) 0.029 ms/op
Iteration   1: 5.802 ±(99.9%) 0.015 ms/op
Iteration   2: 5.486 ±(99.9%) 0.021 ms/op
Iteration   3: 5.716 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.668 ±(99.9%) 2.987 ms/op [Average]
  (min, avg, max) = (5.486, 5.668, 5.802), stdev = 0.164
  CI (99.9%): [2.681, 8.655] (assumes normal distribution)


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
# Warmup Iteration   1: 7.241 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.926 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.561 ±(99.9%) 0.015 ms/op
Iteration   1: 4.485 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.543 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  12.645 ms/op
                 createUser·p0.9999: 27.970 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   2: 4.447 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.775 ms/op
                 createUser·p0.99:   7.299 ms/op
                 createUser·p0.999:  12.190 ms/op
                 createUser·p0.9999: 27.640 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   3: 4.351 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.898 ms/op
                 createUser·p0.99:   7.389 ms/op
                 createUser·p0.999:  10.158 ms/op
                 createUser·p0.9999: 29.435 ms/op
                 createUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216814
  mean =      4.427 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2990 
    [ 2.500,  5.000) = 170072 
    [ 5.000,  7.500) = 41559 
    [ 7.500, 10.000) = 1709 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.519 ms/op
     p(99.9000) =     11.944 ms/op
     p(99.9900) =     28.650 ms/op
     p(99.9990) =     29.901 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 6.747 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.526 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.423 ±(99.9%) 0.014 ms/op
Iteration   1: 4.517 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.628 ms/op
                 existUser·p0.95:   6.119 ms/op
                 existUser·p0.99:   8.503 ms/op
                 existUser·p0.999:  14.759 ms/op
                 existUser·p0.9999: 17.564 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   2: 4.232 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   7.250 ms/op
                 existUser·p0.999:  11.427 ms/op
                 existUser·p0.9999: 18.743 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   3: 4.012 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   4.784 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  13.385 ms/op
                 existUser·p0.9999: 19.334 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 226027
  mean =      4.244 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 3830 
    [ 2.500,  3.750) = 60952 
    [ 3.750,  5.000) = 128227 
    [ 5.000,  6.250) = 27221 
    [ 6.250,  7.500) = 3505 
    [ 7.500,  8.750) = 1066 
    [ 8.750, 10.000) = 464 
    [10.000, 11.250) = 304 
    [11.250, 12.500) = 148 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 67 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     18.999 ms/op
     p(99.9990) =     19.521 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 6.573 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.895 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.524 ±(99.9%) 0.014 ms/op
Iteration   1: 4.356 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  11.181 ms/op
                 getUser·p0.9999: 19.964 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 4.437 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  11.810 ms/op
                 getUser·p0.9999: 24.799 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   3: 4.515 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   4.391 ms/op
                 getUser·p0.90:   5.489 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   7.799 ms/op
                 getUser·p0.999:  12.586 ms/op
                 getUser·p0.9999: 27.853 ms/op
                 getUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216398
  mean =      4.435 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2837 
    [ 2.500,  5.000) = 169843 
    [ 5.000,  7.500) = 41680 
    [ 7.500, 10.000) = 1528 
    [10.000, 12.500) = 352 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     11.944 ms/op
     p(99.9900) =     27.102 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 8.281 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 6.187 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.814 ±(99.9%) 0.019 ms/op
Iteration   1: 5.743 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.160 ms/op
                 listUser·p0.95:   8.208 ms/op
                 listUser·p0.99:   10.476 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 20.573 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 5.723 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  19.538 ms/op
                 listUser·p0.9999: 25.960 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   3: 5.812 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   7.332 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  18.148 ms/op
                 listUser·p0.9999: 27.508 ms/op
                 listUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166708
  mean =      5.759 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 42853 
    [ 5.000,  7.500) = 108864 
    [ 7.500, 10.000) = 12483 
    [10.000, 12.500) = 1809 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.372 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     18.336 ms/op
     p(99.9900) =     26.127 ms/op
     p(99.9990) =     27.776 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.892 ± 1.474  ops/ms
ClientGrpc.existUser                       thrpt       3   7.895 ± 1.913  ops/ms
ClientGrpc.getUser                         thrpt       3   7.238 ± 0.543  ops/ms
ClientGrpc.listUser                        thrpt       3   5.544 ± 1.839  ops/ms
ClientGrpc.createUser                       avgt       3   4.396 ± 0.284   ms/op
ClientGrpc.existUser                        avgt       3   4.179 ± 1.018   ms/op
ClientGrpc.getUser                          avgt       3   4.559 ± 1.374   ms/op
ClientGrpc.listUser                         avgt       3   5.668 ± 2.987   ms/op
ClientGrpc.createUser                     sample  216814   4.427 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.667           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.456           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.519           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.944           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.650           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.048           ms/op
ClientGrpc.existUser                      sample  226027   4.244 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.871           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.267           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.734           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.520           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.500           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.999           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.825           ms/op
ClientGrpc.getUser                        sample  216398   4.435 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.009           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.800           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.389           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.944           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.102           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.918           ms/op
ClientGrpc.listUser                       sample  166708   5.759 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.370           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.324           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.372           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.535           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.336           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.127           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.820           ms/op
