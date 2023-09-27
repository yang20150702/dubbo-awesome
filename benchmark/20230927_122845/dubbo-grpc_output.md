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
# Warmup Iteration   1: 3.999 ops/ms
# Warmup Iteration   2: 8.337 ops/ms
# Warmup Iteration   3: 9.602 ops/ms
Iteration   1: 9.987 ops/ms
Iteration   2: 10.206 ops/ms
Iteration   3: 9.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.061 ±(99.9%) 2.290 ops/ms [Average]
  (min, avg, max) = (9.987, 10.061, 10.206), stdev = 0.126
  CI (99.9%): [7.771, 12.351] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.113 ops/ms
# Warmup Iteration   2: 10.447 ops/ms
# Warmup Iteration   3: 10.258 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.803 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.723 ±(99.9%) 1.303 ops/ms [Average]
  (min, avg, max) = (10.664, 10.723, 10.803), stdev = 0.071
  CI (99.9%): [9.420, 12.026] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.735 ops/ms
# Warmup Iteration   2: 9.846 ops/ms
# Warmup Iteration   3: 10.314 ops/ms
Iteration   1: 10.111 ops/ms
Iteration   2: 10.173 ops/ms
Iteration   3: 10.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.120 ±(99.9%) 0.899 ops/ms [Average]
  (min, avg, max) = (10.076, 10.120, 10.173), stdev = 0.049
  CI (99.9%): [9.221, 11.019] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.351 ops/ms
# Warmup Iteration   2: 7.936 ops/ms
# Warmup Iteration   3: 8.092 ops/ms
Iteration   1: 8.080 ops/ms
Iteration   2: 8.315 ops/ms
Iteration   3: 8.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.155 ±(99.9%) 2.524 ops/ms [Average]
  (min, avg, max) = (8.070, 8.155, 8.315), stdev = 0.138
  CI (99.9%): [5.631, 10.679] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.390 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.002 ms/op
Iteration   1: 3.150 ±(99.9%) 0.002 ms/op
Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
Iteration   3: 3.120 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.138 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.120, 3.138, 3.150), stdev = 0.016
  CI (99.9%): [2.850, 3.425] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.002 ms/op
Iteration   1: 3.006 ±(99.9%) 0.002 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 2.925 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.988 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (2.925, 2.988, 3.033), stdev = 0.057
  CI (99.9%): [1.957, 4.019] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.353 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.002 ms/op
Iteration   1: 3.140 ±(99.9%) 0.002 ms/op
Iteration   2: 3.202 ±(99.9%) 0.001 ms/op
Iteration   3: 3.132 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.158 ±(99.9%) 0.692 ms/op [Average]
  (min, avg, max) = (3.132, 3.158, 3.202), stdev = 0.038
  CI (99.9%): [2.466, 3.850] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.739 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.008 ms/op
Iteration   1: 3.981 ±(99.9%) 0.018 ms/op
Iteration   2: 3.993 ±(99.9%) 0.033 ms/op
Iteration   3: 3.922 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.965 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.922, 3.965, 3.993), stdev = 0.038
  CI (99.9%): [3.274, 4.657] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.649 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
Iteration   1: 3.159 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  6.794 ms/op
                 createUser·p0.9999: 13.222 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   2: 3.084 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.351 ms/op
                 createUser·p0.9999: 15.241 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  10.688 ms/op
                 createUser·p0.9999: 25.264 ms/op
                 createUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305706
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10843 
    [ 2.500,  5.000) = 292929 
    [ 5.000,  7.500) = 1449 
    [ 7.500, 10.000) = 209 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      9.606 ms/op
     p(99.9900) =     24.754 ms/op
     p(99.9990) =     25.362 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.240 ms/op
                 existUser·p0.9999: 13.162 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  6.531 ms/op
                 existUser·p0.9999: 14.350 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  7.824 ms/op
                 existUser·p0.9999: 16.515 ms/op
                 existUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316768
  mean =      3.029 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 745 
    [ 1.250,  2.500) = 20086 
    [ 2.500,  3.750) = 281446 
    [ 3.750,  5.000) = 13177 
    [ 5.000,  6.250) = 661 
    [ 6.250,  7.500) = 341 
    [ 7.500,  8.750) = 130 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      7.479 ms/op
     p(99.9900) =     14.685 ms/op
     p(99.9990) =     17.001 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 4.610 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
Iteration   1: 3.206 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  9.953 ms/op
                 getUser·p0.9999: 13.355 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  7.356 ms/op
                 getUser·p0.9999: 14.190 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   3: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.355 ms/op
                 getUser·p0.9999: 16.123 ms/op
                 getUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304999
  mean =      3.147 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 437 
    [ 1.250,  2.500) = 9479 
    [ 2.500,  3.750) = 267955 
    [ 3.750,  5.000) = 24863 
    [ 5.000,  6.250) = 1155 
    [ 6.250,  7.500) = 611 
    [ 7.500,  8.750) = 237 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      8.356 ms/op
     p(99.9900) =     15.442 ms/op
     p(99.9990) =     16.624 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 6.151 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.010 ms/op
Iteration   1: 3.965 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 20.316 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   2: 3.886 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.995 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 17.828 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 3.862 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 17.512 ms/op
                 listUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245800
  mean =      3.904 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1943 
    [ 2.500,  5.000) = 230765 
    [ 5.000,  7.500) = 11805 
    [ 7.500, 10.000) = 673 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 231 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     15.814 ms/op
     p(99.9900) =     19.538 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.061 ± 2.290  ops/ms
ClientGrpc.existUser                       thrpt       3  10.723 ± 1.303  ops/ms
ClientGrpc.getUser                         thrpt       3  10.120 ± 0.899  ops/ms
ClientGrpc.listUser                        thrpt       3   8.155 ± 2.524  ops/ms
ClientGrpc.createUser                       avgt       3   3.138 ± 0.287   ms/op
ClientGrpc.existUser                        avgt       3   2.988 ± 1.031   ms/op
ClientGrpc.getUser                          avgt       3   3.158 ± 0.692   ms/op
ClientGrpc.listUser                         avgt       3   3.965 ± 0.691   ms/op
ClientGrpc.createUser                     sample  305706   3.141 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.629           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.606           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.754           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.362           ms/op
ClientGrpc.existUser                      sample  316768   3.029 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.839           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.479           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.685           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.105           ms/op
ClientGrpc.getUser                        sample  304999   3.147 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.662           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.920           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.356           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.442           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.646           ms/op
ClientGrpc.listUser                       sample  245800   3.904 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.891           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.391           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.814           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.538           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.266           ms/op
