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
# Warmup Iteration   1: 4.265 ops/ms
# Warmup Iteration   2: 8.628 ops/ms
# Warmup Iteration   3: 9.801 ops/ms
Iteration   1: 10.216 ops/ms
Iteration   2: 10.368 ops/ms
Iteration   3: 10.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.339 ±(99.9%) 2.041 ops/ms [Average]
  (min, avg, max) = (10.216, 10.339, 10.434), stdev = 0.112
  CI (99.9%): [8.299, 12.380] (assumes normal distribution)


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
# Warmup Iteration   1: 7.550 ops/ms
# Warmup Iteration   2: 10.259 ops/ms
# Warmup Iteration   3: 10.727 ops/ms
Iteration   1: 10.609 ops/ms
Iteration   2: 10.706 ops/ms
Iteration   3: 10.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.617 ±(99.9%) 1.547 ops/ms [Average]
  (min, avg, max) = (10.537, 10.617, 10.706), stdev = 0.085
  CI (99.9%): [9.070, 12.164] (assumes normal distribution)


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
# Warmup Iteration   1: 6.903 ops/ms
# Warmup Iteration   2: 9.991 ops/ms
# Warmup Iteration   3: 10.194 ops/ms
Iteration   1: 10.399 ops/ms
Iteration   2: 10.337 ops/ms
Iteration   3: 10.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.334 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (10.266, 10.334, 10.399), stdev = 0.066
  CI (99.9%): [9.122, 11.546] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.685 ops/ms
# Warmup Iteration   2: 7.618 ops/ms
# Warmup Iteration   3: 8.130 ops/ms
Iteration   1: 7.979 ops/ms
Iteration   2: 8.165 ops/ms
Iteration   3: 8.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.095 ±(99.9%) 1.843 ops/ms [Average]
  (min, avg, max) = (7.979, 8.095, 8.165), stdev = 0.101
  CI (99.9%): [6.251, 9.938] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.348 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.001 ms/op
Iteration   1: 3.145 ±(99.9%) 0.002 ms/op
Iteration   2: 3.183 ±(99.9%) 0.006 ms/op
Iteration   3: 3.140 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.156 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.140, 3.156, 3.183), stdev = 0.024
  CI (99.9%): [2.721, 3.591] (assumes normal distribution)


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.002 ms/op
Iteration   1: 2.980 ±(99.9%) 0.002 ms/op
Iteration   2: 2.966 ±(99.9%) 0.002 ms/op
Iteration   3: 3.004 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.983 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.966, 2.983, 3.004), stdev = 0.019
  CI (99.9%): [2.632, 3.335] (assumes normal distribution)


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
# Warmup Iteration   1: 4.296 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.003 ms/op
Iteration   1: 3.127 ±(99.9%) 0.008 ms/op
Iteration   2: 3.193 ±(99.9%) 0.002 ms/op
Iteration   3: 3.116 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.145 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (3.116, 3.145, 3.193), stdev = 0.041
  CI (99.9%): [2.389, 3.902] (assumes normal distribution)


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
# Warmup Iteration   1: 5.834 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.011 ms/op
Iteration   1: 3.936 ±(99.9%) 0.011 ms/op
Iteration   2: 3.911 ±(99.9%) 0.021 ms/op
Iteration   3: 3.909 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.919 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (3.909, 3.919, 3.936), stdev = 0.015
  CI (99.9%): [3.649, 4.189] (assumes normal distribution)


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
# Warmup Iteration   1: 4.309 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.007 ms/op
Iteration   1: 3.097 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.565 ms/op
                 createUser·p0.9999: 16.160 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   2: 3.170 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.938 ms/op
                 createUser·p0.9999: 17.302 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.601 ms/op
                 createUser·p0.999:  13.641 ms/op
                 createUser·p0.9999: 19.853 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305524
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11512 
    [ 2.500,  5.000) = 292103 
    [ 5.000,  7.500) = 1493 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      9.248 ms/op
     p(99.9900) =     19.381 ms/op
     p(99.9990) =     25.524 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.005 ms/op
Iteration   1: 2.964 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.907 ms/op
                 existUser·p0.9999: 12.616 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.913 ms/op
                 existUser·p0.9999: 14.303 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  8.093 ms/op
                 existUser·p0.9999: 17.083 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319161
  mean =      3.006 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 716 
    [ 1.250,  2.500) = 24894 
    [ 2.500,  3.750) = 281194 
    [ 3.750,  5.000) = 10810 
    [ 5.000,  6.250) = 682 
    [ 6.250,  7.500) = 424 
    [ 7.500,  8.750) = 163 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.364 ms/op
     p(99.9900) =     16.335 ms/op
     p(99.9990) =     18.436 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
Iteration   1: 3.177 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.608 ms/op
                 getUser·p0.999:  8.454 ms/op
                 getUser·p0.9999: 16.367 ms/op
                 getUser·p1.00:   16.613 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  7.423 ms/op
                 getUser·p0.9999: 16.540 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   3: 3.132 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  9.565 ms/op
                 getUser·p0.9999: 20.407 ms/op
                 getUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305260
  mean =      3.143 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5278 
    [ 2.500,  5.000) = 298302 
    [ 5.000,  7.500) = 1172 
    [ 7.500, 10.000) = 278 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.859 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     20.642 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 5.197 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.009 ms/op
Iteration   1: 3.929 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.035 ms/op
                 listUser·p0.9999: 16.871 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   2: 3.913 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.967 ms/op
                 listUser·p0.9999: 16.864 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.838 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  13.894 ms/op
                 listUser·p0.9999: 17.935 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246464
  mean =      3.893 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1512 
    [ 2.500,  3.750) = 105125 
    [ 3.750,  5.000) = 127940 
    [ 5.000,  6.250) = 7509 
    [ 6.250,  7.500) = 3394 
    [ 7.500,  8.750) = 387 
    [ 8.750, 10.000) = 146 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 138 
    [15.000, 16.250) = 73 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     14.066 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     18.352 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.339 ± 2.041  ops/ms
ClientGrpc.existUser                       thrpt       3  10.617 ± 1.547  ops/ms
ClientGrpc.getUser                         thrpt       3  10.334 ± 1.212  ops/ms
ClientGrpc.listUser                        thrpt       3   8.095 ± 1.843  ops/ms
ClientGrpc.createUser                       avgt       3   3.156 ± 0.435   ms/op
ClientGrpc.existUser                        avgt       3   2.983 ± 0.351   ms/op
ClientGrpc.getUser                          avgt       3   3.145 ± 0.756   ms/op
ClientGrpc.listUser                         avgt       3   3.919 ± 0.270   ms/op
ClientGrpc.createUser                     sample  305524   3.140 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.648           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.248           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.381           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.657           ms/op
ClientGrpc.existUser                      sample  319161   3.006 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.632           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.364           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.335           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.907           ms/op
ClientGrpc.getUser                        sample  305260   3.143 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.731           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.859           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.038           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.873           ms/op
ClientGrpc.listUser                       sample  246464   3.893 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.055           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.383           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.066           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.974           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.481           ms/op
