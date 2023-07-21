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
# Warmup Iteration   1: 4.895 ops/ms
# Warmup Iteration   2: 9.609 ops/ms
# Warmup Iteration   3: 10.506 ops/ms
Iteration   1: 10.663 ops/ms
Iteration   2: 10.667 ops/ms
Iteration   3: 10.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.702 ±(99.9%) 1.168 ops/ms [Average]
  (min, avg, max) = (10.663, 10.702, 10.776), stdev = 0.064
  CI (99.9%): [9.534, 11.870] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.952 ops/ms
# Warmup Iteration   2: 10.676 ops/ms
# Warmup Iteration   3: 11.289 ops/ms
Iteration   1: 11.313 ops/ms
Iteration   2: 11.322 ops/ms
Iteration   3: 11.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.329 ±(99.9%) 0.370 ops/ms [Average]
  (min, avg, max) = (11.313, 11.329, 11.351), stdev = 0.020
  CI (99.9%): [10.958, 11.699] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.741 ops/ms
# Warmup Iteration   2: 10.296 ops/ms
# Warmup Iteration   3: 10.689 ops/ms
Iteration   1: 10.827 ops/ms
Iteration   2: 10.628 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.712 ±(99.9%) 1.879 ops/ms [Average]
  (min, avg, max) = (10.628, 10.712, 10.827), stdev = 0.103
  CI (99.9%): [8.833, 12.590] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.964 ops/ms
# Warmup Iteration   2: 7.916 ops/ms
# Warmup Iteration   3: 8.064 ops/ms
Iteration   1: 8.220 ops/ms
Iteration   2: 8.047 ops/ms
Iteration   3: 8.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.144 ±(99.9%) 1.610 ops/ms [Average]
  (min, avg, max) = (8.047, 8.144, 8.220), stdev = 0.088
  CI (99.9%): [6.534, 9.754] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.033 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.002 ms/op
Iteration   1: 2.981 ±(99.9%) 0.003 ms/op
Iteration   2: 3.001 ±(99.9%) 0.003 ms/op
Iteration   3: 2.973 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.985 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (2.973, 2.985, 3.001), stdev = 0.014
  CI (99.9%): [2.723, 3.246] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.767 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.004 ms/op
Iteration   1: 2.832 ±(99.9%) 0.003 ms/op
Iteration   2: 2.828 ±(99.9%) 0.004 ms/op
Iteration   3: 2.827 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.829 ±(99.9%) 0.051 ms/op [Average]
  (min, avg, max) = (2.827, 2.829, 2.832), stdev = 0.003
  CI (99.9%): [2.778, 2.880] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.123 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.004 ms/op
Iteration   1: 2.954 ±(99.9%) 0.003 ms/op
Iteration   2: 3.022 ±(99.9%) 0.001 ms/op
Iteration   3: 2.976 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.984 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (2.954, 2.984, 3.022), stdev = 0.035
  CI (99.9%): [2.346, 3.622] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.808 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.014 ms/op
Iteration   1: 3.884 ±(99.9%) 0.008 ms/op
Iteration   2: 3.913 ±(99.9%) 0.037 ms/op
Iteration   3: 3.911 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.903 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (3.884, 3.903, 3.913), stdev = 0.016
  CI (99.9%): [3.602, 4.203] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.872 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
Iteration   1: 2.985 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.595 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.454 ms/op
                 createUser·p0.9999: 12.080 ms/op
                 createUser·p1.00:   12.255 ms/op

Iteration   2: 2.933 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.451 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  8.122 ms/op
                 createUser·p0.9999: 14.141 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 15.453 ms/op
                 createUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323929
  mean =      2.963 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2297 
    [ 1.250,  2.500) = 27725 
    [ 2.500,  3.750) = 280051 
    [ 3.750,  5.000) = 12502 
    [ 5.000,  6.250) = 742 
    [ 6.250,  7.500) = 207 
    [ 7.500,  8.750) = 147 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 83 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.143 ms/op
     p(99.9900) =     14.684 ms/op
     p(99.9990) =     16.536 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.570 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.791 ±(99.9%) 0.007 ms/op
Iteration   1: 2.845 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.457 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  6.727 ms/op
                 existUser·p0.9999: 32.375 ms/op
                 existUser·p1.00:   33.423 ms/op

Iteration   2: 2.887 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.489 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  9.503 ms/op
                 existUser·p0.9999: 15.268 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   3: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.589 ms/op
                 existUser·p0.9999: 18.907 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334697
  mean =      2.868 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55377 
    [ 2.500,  5.000) = 277865 
    [ 5.000,  7.500) = 1165 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.228 ms/op
     p(99.9900) =     19.219 ms/op
     p(99.9990) =     33.150 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.963 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 2.947 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.267 ms/op
                 getUser·p0.9999: 16.941 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 3.017 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.080 ms/op
                 getUser·p0.999:  5.874 ms/op
                 getUser·p0.9999: 13.566 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   3: 3.021 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.393 ms/op
                 getUser·p0.9999: 17.198 ms/op
                 getUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320343
  mean =      2.995 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1446 
    [ 1.250,  2.500) = 20157 
    [ 2.500,  3.750) = 284681 
    [ 3.750,  5.000) = 13223 
    [ 5.000,  6.250) = 465 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 63 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     17.511 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.809 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.943 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.010 ms/op
Iteration   1: 3.897 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.287 ms/op
                 listUser·p0.9999: 19.261 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 3.875 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  16.099 ms/op
                 listUser·p0.9999: 27.951 ms/op
                 listUser·p1.00:   28.705 ms/op

Iteration   3: 3.857 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  15.667 ms/op
                 listUser·p0.9999: 23.214 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247512
  mean =      3.876 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5371 
    [ 2.500,  5.000) = 222498 
    [ 5.000,  7.500) = 18627 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     28.625 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.702 ± 1.168  ops/ms
ClientGrpc.existUser                       thrpt       3  11.329 ± 0.370  ops/ms
ClientGrpc.getUser                         thrpt       3  10.712 ± 1.879  ops/ms
ClientGrpc.listUser                        thrpt       3   8.144 ± 1.610  ops/ms
ClientGrpc.createUser                       avgt       3   2.985 ± 0.262   ms/op
ClientGrpc.existUser                        avgt       3   2.829 ± 0.051   ms/op
ClientGrpc.getUser                          avgt       3   2.984 ± 0.638   ms/op
ClientGrpc.listUser                         avgt       3   3.903 ± 0.300   ms/op
ClientGrpc.createUser                     sample  323929   2.963 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.451           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.445           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.143           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.684           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.630           ms/op
ClientGrpc.existUser                      sample  334697   2.868 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.457           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.228           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.219           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.423           ms/op
ClientGrpc.getUser                        sample  320343   2.995 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.726           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.941           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.088           ms/op
ClientGrpc.listUser                       sample  247512   3.876 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.057           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.034           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.705           ms/op
