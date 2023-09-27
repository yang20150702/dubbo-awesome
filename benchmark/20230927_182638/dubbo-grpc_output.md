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
# Warmup Iteration   1: 4.393 ops/ms
# Warmup Iteration   2: 9.161 ops/ms
# Warmup Iteration   3: 10.051 ops/ms
Iteration   1: 10.245 ops/ms
Iteration   2: 10.328 ops/ms
Iteration   3: 10.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.360 ±(99.9%) 2.437 ops/ms [Average]
  (min, avg, max) = (10.245, 10.360, 10.506), stdev = 0.134
  CI (99.9%): [7.923, 12.797] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.222 ops/ms
# Warmup Iteration   2: 10.432 ops/ms
# Warmup Iteration   3: 10.729 ops/ms
Iteration   1: 10.856 ops/ms
Iteration   2: 10.894 ops/ms
Iteration   3: 10.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.865 ±(99.9%) 0.467 ops/ms [Average]
  (min, avg, max) = (10.845, 10.865, 10.894), stdev = 0.026
  CI (99.9%): [10.398, 11.331] (assumes normal distribution)


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
# Warmup Iteration   1: 7.531 ops/ms
# Warmup Iteration   2: 9.941 ops/ms
# Warmup Iteration   3: 10.215 ops/ms
Iteration   1: 10.356 ops/ms
Iteration   2: 10.021 ops/ms
Iteration   3: 10.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.240 ±(99.9%) 3.460 ops/ms [Average]
  (min, avg, max) = (10.021, 10.240, 10.356), stdev = 0.190
  CI (99.9%): [6.780, 13.700] (assumes normal distribution)


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
# Warmup Iteration   1: 6.057 ops/ms
# Warmup Iteration   2: 8.164 ops/ms
# Warmup Iteration   3: 8.349 ops/ms
Iteration   1: 8.361 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 8.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.321 ±(99.9%) 0.857 ops/ms [Average]
  (min, avg, max) = (8.269, 8.321, 8.361), stdev = 0.047
  CI (99.9%): [7.465, 9.178] (assumes normal distribution)


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.003 ms/op
Iteration   1: 3.103 ±(99.9%) 0.002 ms/op
Iteration   2: 3.130 ±(99.9%) 0.001 ms/op
Iteration   3: 3.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.112 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (3.103, 3.112, 3.130), stdev = 0.015
  CI (99.9%): [2.835, 3.389] (assumes normal distribution)


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 2.941 ±(99.9%) 0.002 ms/op
Iteration   2: 2.946 ±(99.9%) 0.004 ms/op
Iteration   3: 2.946 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.945 ±(99.9%) 0.052 ms/op [Average]
  (min, avg, max) = (2.941, 2.945, 2.946), stdev = 0.003
  CI (99.9%): [2.892, 2.997] (assumes normal distribution)


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.003 ms/op
Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
Iteration   3: 3.105 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.101 ±(99.9%) 0.071 ms/op [Average]
  (min, avg, max) = (3.098, 3.101, 3.105), stdev = 0.004
  CI (99.9%): [3.031, 3.172] (assumes normal distribution)


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
# Warmup Iteration   1: 4.734 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.035 ms/op
Iteration   1: 3.810 ±(99.9%) 0.013 ms/op
Iteration   2: 3.817 ±(99.9%) 0.031 ms/op
Iteration   3: 3.829 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.819 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (3.810, 3.819, 3.829), stdev = 0.010
  CI (99.9%): [3.640, 3.998] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
Iteration   1: 3.126 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.189 ms/op
                 createUser·p0.9999: 19.401 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  7.625 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   3: 3.070 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.498 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  9.322 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309240
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10505 
    [ 2.500,  5.000) = 297105 
    [ 5.000,  7.500) = 1189 
    [ 7.500, 10.000) = 246 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.005 ms/op
Iteration   1: 2.917 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   3.961 ms/op
                 existUser·p0.999:  6.029 ms/op
                 existUser·p0.9999: 10.994 ms/op
                 existUser·p1.00:   11.272 ms/op

Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 12.394 ms/op
                 existUser·p1.00:   12.632 ms/op

Iteration   3: 3.058 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.545 ms/op
                 existUser·p0.9999: 15.452 ms/op
                 existUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321844
  mean =      2.981 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 690 
    [ 1.250,  2.500) = 23402 
    [ 2.500,  3.750) = 286017 
    [ 3.750,  5.000) = 10394 
    [ 5.000,  6.250) = 812 
    [ 6.250,  7.500) = 208 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.493 ms/op
     p(99.9900) =     14.413 ms/op
     p(99.9990) =     15.685 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.415 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.641 ms/op
                 getUser·p0.999:  7.340 ms/op
                 getUser·p0.9999: 14.950 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  8.003 ms/op
                 getUser·p0.9999: 15.869 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   3: 3.101 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  9.021 ms/op
                 getUser·p0.9999: 19.640 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308141
  mean =      3.116 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8571 
    [ 2.500,  5.000) = 298034 
    [ 5.000,  7.500) = 1171 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.930 ms/op
     p(99.9900) =     17.537 ms/op
     p(99.9990) =     19.877 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.010 ms/op
Iteration   1: 3.901 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.125 ms/op
                 listUser·p0.9999: 13.651 ms/op
                 listUser·p1.00:   14.057 ms/op

Iteration   2: 3.853 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.541 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  12.975 ms/op
                 listUser·p0.9999: 14.020 ms/op
                 listUser·p1.00:   14.467 ms/op

Iteration   3: 3.910 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  14.028 ms/op
                 listUser·p0.9999: 16.407 ms/op
                 listUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246830
  mean =      3.888 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 2816 
    [ 2.500,  3.750) = 102241 
    [ 3.750,  5.000) = 129016 
    [ 5.000,  6.250) = 8393 
    [ 6.250,  7.500) = 3402 
    [ 7.500,  8.750) = 335 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 189 
    [13.750, 15.000) = 91 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     15.062 ms/op
     p(99.9990) =     16.681 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.360 ± 2.437  ops/ms
ClientGrpc.existUser                       thrpt       3  10.865 ± 0.467  ops/ms
ClientGrpc.getUser                         thrpt       3  10.240 ± 3.460  ops/ms
ClientGrpc.listUser                        thrpt       3   8.321 ± 0.857  ops/ms
ClientGrpc.createUser                       avgt       3   3.112 ± 0.277   ms/op
ClientGrpc.existUser                        avgt       3   2.945 ± 0.052   ms/op
ClientGrpc.getUser                          avgt       3   3.101 ± 0.071   ms/op
ClientGrpc.listUser                         avgt       3   3.819 ± 0.179   ms/op
ClientGrpc.createUser                     sample  309240   3.105 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.498           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.774           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.887           ms/op
ClientGrpc.existUser                      sample  321844   2.981 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.608           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.493           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.413           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.827           ms/op
ClientGrpc.getUser                        sample  308141   3.116 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.415           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.930           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.537           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.021           ms/op
ClientGrpc.listUser                       sample  246830   3.888 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.908           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.301           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.521           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.861           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.062           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          16.876           ms/op
