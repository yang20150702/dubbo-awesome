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
# Warmup Iteration   1: 4.352 ops/ms
# Warmup Iteration   2: 8.973 ops/ms
# Warmup Iteration   3: 9.963 ops/ms
Iteration   1: 10.337 ops/ms
Iteration   2: 10.330 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.369 ±(99.9%) 1.130 ops/ms [Average]
  (min, avg, max) = (10.330, 10.369, 10.441), stdev = 0.062
  CI (99.9%): [9.239, 11.500] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.781 ops/ms
# Warmup Iteration   2: 10.418 ops/ms
# Warmup Iteration   3: 10.804 ops/ms
Iteration   1: 10.668 ops/ms
Iteration   2: 10.697 ops/ms
Iteration   3: 10.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.699 ±(99.9%) 0.589 ops/ms [Average]
  (min, avg, max) = (10.668, 10.699, 10.732), stdev = 0.032
  CI (99.9%): [10.110, 11.288] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.958 ops/ms
# Warmup Iteration   2: 9.771 ops/ms
# Warmup Iteration   3: 10.064 ops/ms
Iteration   1: 10.071 ops/ms
Iteration   2: 10.008 ops/ms
Iteration   3: 10.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.127 ±(99.9%) 2.806 ops/ms [Average]
  (min, avg, max) = (10.008, 10.127, 10.300), stdev = 0.154
  CI (99.9%): [7.321, 12.932] (assumes normal distribution)


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
# Warmup Iteration   1: 5.558 ops/ms
# Warmup Iteration   2: 8.064 ops/ms
# Warmup Iteration   3: 8.273 ops/ms
Iteration   1: 8.311 ops/ms
Iteration   2: 8.225 ops/ms
Iteration   3: 8.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.279 ±(99.9%) 0.862 ops/ms [Average]
  (min, avg, max) = (8.225, 8.279, 8.311), stdev = 0.047
  CI (99.9%): [7.418, 9.141] (assumes normal distribution)


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.003 ms/op
Iteration   1: 3.237 ±(99.9%) 0.002 ms/op
Iteration   2: 3.160 ±(99.9%) 0.002 ms/op
Iteration   3: 3.140 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.179 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.140, 3.179, 3.237), stdev = 0.051
  CI (99.9%): [2.240, 4.118] (assumes normal distribution)


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.003 ms/op
Iteration   1: 3.002 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.002 ms/op
Iteration   3: 3.018 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.000 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.981, 3.000, 3.018), stdev = 0.018
  CI (99.9%): [2.665, 3.336] (assumes normal distribution)


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
# Warmup Iteration   1: 3.646 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.001 ms/op
Iteration   1: 3.135 ±(99.9%) 0.004 ms/op
Iteration   2: 3.160 ±(99.9%) 0.002 ms/op
Iteration   3: 3.159 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.151 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (3.135, 3.151, 3.160), stdev = 0.014
  CI (99.9%): [2.898, 3.404] (assumes normal distribution)


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
# Warmup Iteration   1: 5.363 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.013 ms/op
Iteration   1: 3.861 ±(99.9%) 0.014 ms/op
Iteration   2: 3.883 ±(99.9%) 0.039 ms/op
Iteration   3: 3.820 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.855 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (3.820, 3.855, 3.883), stdev = 0.032
  CI (99.9%): [3.273, 4.436] (assumes normal distribution)


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.005 ms/op
Iteration   1: 3.109 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  8.152 ms/op
                 createUser·p0.9999: 15.106 ms/op
                 createUser·p1.00:   15.417 ms/op

Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.692 ms/op
                 createUser·p0.9999: 16.723 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  16.142 ms/op
                 createUser·p0.9999: 17.678 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310837
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1085 
    [ 1.250,  2.500) = 13994 
    [ 2.500,  3.750) = 277807 
    [ 3.750,  5.000) = 16416 
    [ 5.000,  6.250) = 893 
    [ 6.250,  7.500) = 294 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 114 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =     10.194 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     17.986 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.032 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.005 ms/op
Iteration   1: 3.044 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  7.208 ms/op
                 existUser·p0.9999: 11.714 ms/op
                 existUser·p1.00:   12.141 ms/op

Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.734 ms/op
                 existUser·p0.9999: 15.343 ms/op
                 existUser·p1.00:   15.696 ms/op

Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  9.088 ms/op
                 existUser·p0.9999: 15.400 ms/op
                 existUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316823
  mean =      3.028 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1027 
    [ 1.250,  2.500) = 18036 
    [ 2.500,  3.750) = 285721 
    [ 3.750,  5.000) = 10541 
    [ 5.000,  6.250) = 827 
    [ 6.250,  7.500) = 344 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.644 ms/op
     p(99.9900) =     15.204 ms/op
     p(99.9990) =     15.647 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 4.478 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.007 ms/op
Iteration   1: 3.123 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.534 ms/op
                 getUser·p0.9999: 14.860 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   2: 3.065 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.045 ms/op
                 getUser·p0.9999: 15.270 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.744 ms/op
                 getUser·p0.9999: 16.708 ms/op
                 getUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309355
  mean =      3.103 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 563 
    [ 1.250,  2.500) = 8521 
    [ 2.500,  3.750) = 282181 
    [ 3.750,  5.000) = 16668 
    [ 5.000,  6.250) = 915 
    [ 6.250,  7.500) = 288 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.854 ms/op
     p(99.9900) =     16.303 ms/op
     p(99.9990) =     18.251 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 5.454 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.008 ms/op
Iteration   1: 3.897 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.720 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.026 ms/op
                 listUser·p0.9999: 15.930 ms/op
                 listUser·p1.00:   16.515 ms/op

Iteration   2: 3.894 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  13.238 ms/op
                 listUser·p0.9999: 15.780 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 3.956 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  13.911 ms/op
                 listUser·p0.9999: 16.317 ms/op
                 listUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245241
  mean =      3.915 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 3220 
    [ 2.500,  3.750) = 100032 
    [ 3.750,  5.000) = 126831 
    [ 5.000,  6.250) = 10170 
    [ 6.250,  7.500) = 3861 
    [ 7.500,  8.750) = 397 
    [ 8.750, 10.000) = 136 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 132 
    [13.750, 15.000) = 84 
    [15.000, 16.250) = 76 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     13.116 ms/op
     p(99.9900) =     16.187 ms/op
     p(99.9990) =     18.288 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.369 ± 1.130  ops/ms
ClientGrpc.existUser                       thrpt       3  10.699 ± 0.589  ops/ms
ClientGrpc.getUser                         thrpt       3  10.127 ± 2.806  ops/ms
ClientGrpc.listUser                        thrpt       3   8.279 ± 0.862  ops/ms
ClientGrpc.createUser                       avgt       3   3.179 ± 0.939   ms/op
ClientGrpc.existUser                        avgt       3   3.000 ± 0.335   ms/op
ClientGrpc.getUser                          avgt       3   3.151 ± 0.253   ms/op
ClientGrpc.listUser                         avgt       3   3.855 ± 0.581   ms/op
ClientGrpc.createUser                     sample  310837   3.091 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.647           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.194           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.302           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.088           ms/op
ClientGrpc.existUser                      sample  316823   3.028 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.484           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.644           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.204           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.696           ms/op
ClientGrpc.getUser                        sample  309355   3.103 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.734           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.854           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.303           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.579           ms/op
ClientGrpc.listUser                       sample  245241   3.915 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.720           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.424           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.116           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.187           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.202           ms/op
