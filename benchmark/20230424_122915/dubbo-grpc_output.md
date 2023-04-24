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
# Warmup Iteration   1: 3.960 ops/ms
# Warmup Iteration   2: 8.738 ops/ms
# Warmup Iteration   3: 9.857 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.392 ops/ms
Iteration   3: 10.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.482 ±(99.9%) 1.682 ops/ms [Average]
  (min, avg, max) = (10.392, 10.482, 10.576), stdev = 0.092
  CI (99.9%): [8.800, 12.164] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.386 ops/ms
# Warmup Iteration   2: 10.560 ops/ms
# Warmup Iteration   3: 11.085 ops/ms
Iteration   1: 11.167 ops/ms
Iteration   2: 11.160 ops/ms
Iteration   3: 11.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.182 ±(99.9%) 0.592 ops/ms [Average]
  (min, avg, max) = (11.160, 11.182, 11.220), stdev = 0.032
  CI (99.9%): [10.591, 11.774] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.695 ops/ms
# Warmup Iteration   2: 10.111 ops/ms
# Warmup Iteration   3: 10.628 ops/ms
Iteration   1: 10.578 ops/ms
Iteration   2: 10.570 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.623 ±(99.9%) 1.545 ops/ms [Average]
  (min, avg, max) = (10.570, 10.623, 10.720), stdev = 0.085
  CI (99.9%): [9.077, 12.168] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.452 ops/ms
# Warmup Iteration   2: 7.733 ops/ms
# Warmup Iteration   3: 8.202 ops/ms
Iteration   1: 8.038 ops/ms
Iteration   2: 7.979 ops/ms
Iteration   3: 8.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.056 ±(99.9%) 1.579 ops/ms [Average]
  (min, avg, max) = (7.979, 8.056, 8.150), stdev = 0.087
  CI (99.9%): [6.477, 9.634] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.452 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.008, 3.037, 3.058), stdev = 0.026
  CI (99.9%): [2.562, 3.513] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.918 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.004 ms/op
Iteration   1: 2.906 ±(99.9%) 0.003 ms/op
Iteration   2: 2.890 ±(99.9%) 0.002 ms/op
Iteration   3: 2.890 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.895 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.890, 2.895, 2.906), stdev = 0.009
  CI (99.9%): [2.729, 3.062] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.340 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.003 ms/op
Iteration   1: 3.038 ±(99.9%) 0.004 ms/op
Iteration   2: 2.997 ±(99.9%) 0.003 ms/op
Iteration   3: 3.047 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.027 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (2.997, 3.027, 3.047), stdev = 0.026
  CI (99.9%): [2.547, 3.508] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.985 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.017 ms/op
Iteration   1: 3.988 ±(99.9%) 0.020 ms/op
Iteration   2: 3.869 ±(99.9%) 0.015 ms/op
Iteration   3: 3.968 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.942 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (3.869, 3.942, 3.988), stdev = 0.064
  CI (99.9%): [2.774, 5.109] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.177 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.602 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  9.355 ms/op
                 createUser·p0.9999: 16.348 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   3: 3.089 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  8.188 ms/op
                 createUser·p0.9999: 28.562 ms/op
                 createUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313261
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27872 
    [ 2.500,  5.000) = 283821 
    [ 5.000,  7.500) = 1207 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.446 ms/op
     p(99.9900) =     27.995 ms/op
     p(99.9990) =     28.668 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.993 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  6.940 ms/op
                 existUser·p0.9999: 19.707 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   2: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.787 ms/op
                 existUser·p0.9999: 15.266 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   3: 2.946 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  9.828 ms/op
                 existUser·p0.9999: 30.938 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327031
  mean =      2.934 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42425 
    [ 2.500,  5.000) = 283512 
    [ 5.000,  7.500) = 796 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.381 ms/op
     p(99.9900) =     22.846 ms/op
     p(99.9990) =     31.317 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.425 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  8.049 ms/op
                 getUser·p0.9999: 14.829 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.939 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.388 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  11.222 ms/op
                 getUser·p0.9999: 19.811 ms/op
                 getUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316436
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22912 
    [ 2.500,  5.000) = 291971 
    [ 5.000,  7.500) = 1220 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.670 ms/op
     p(99.9900) =     23.605 ms/op
     p(99.9990) =     24.926 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 5.645 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.012 ms/op
Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  13.924 ms/op
                 listUser·p0.9999: 20.584 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   2: 3.973 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  17.162 ms/op
                 listUser·p0.9999: 19.947 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 4.002 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  17.988 ms/op
                 listUser·p0.9999: 23.461 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240065
  mean =      4.001 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1712 
    [ 2.500,  5.000) = 215600 
    [ 5.000,  7.500) = 21026 
    [ 7.500, 10.000) = 1239 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     23.763 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.482 ± 1.682  ops/ms
ClientGrpc.existUser                       thrpt       3  11.182 ± 0.592  ops/ms
ClientGrpc.getUser                         thrpt       3  10.623 ± 1.545  ops/ms
ClientGrpc.listUser                        thrpt       3   8.056 ± 1.579  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.475   ms/op
ClientGrpc.existUser                        avgt       3   2.895 ± 0.166   ms/op
ClientGrpc.getUser                          avgt       3   3.027 ± 0.481   ms/op
ClientGrpc.listUser                         avgt       3   3.942 ± 1.168   ms/op
ClientGrpc.createUser                     sample  313261   3.065 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.754           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.446           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.995           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.836           ms/op
ClientGrpc.existUser                      sample  327031   2.934 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.687           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.381           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.846           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.457           ms/op
ClientGrpc.getUser                        sample  316436   3.035 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.388           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.670           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.605           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.969           ms/op
ClientGrpc.listUser                       sample  240065   4.001 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.905           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.843           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.889           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.855           ms/op
