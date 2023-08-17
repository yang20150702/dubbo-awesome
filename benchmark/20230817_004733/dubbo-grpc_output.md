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
# Warmup Iteration   1: 4.014 ops/ms
# Warmup Iteration   2: 8.448 ops/ms
# Warmup Iteration   3: 9.901 ops/ms
Iteration   1: 10.124 ops/ms
Iteration   2: 10.132 ops/ms
Iteration   3: 9.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.075 ±(99.9%) 1.684 ops/ms [Average]
  (min, avg, max) = (9.968, 10.075, 10.132), stdev = 0.092
  CI (99.9%): [8.391, 11.758] (assumes normal distribution)


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
# Warmup Iteration   1: 7.394 ops/ms
# Warmup Iteration   2: 10.489 ops/ms
# Warmup Iteration   3: 10.699 ops/ms
Iteration   1: 10.607 ops/ms
Iteration   2: 10.808 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.706 ±(99.9%) 1.835 ops/ms [Average]
  (min, avg, max) = (10.607, 10.706, 10.808), stdev = 0.101
  CI (99.9%): [8.870, 12.541] (assumes normal distribution)


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
# Warmup Iteration   1: 6.053 ops/ms
# Warmup Iteration   2: 9.341 ops/ms
# Warmup Iteration   3: 9.986 ops/ms
Iteration   1: 10.162 ops/ms
Iteration   2: 10.134 ops/ms
Iteration   3: 10.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.161 ±(99.9%) 0.482 ops/ms [Average]
  (min, avg, max) = (10.134, 10.161, 10.187), stdev = 0.026
  CI (99.9%): [9.679, 10.644] (assumes normal distribution)


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
# Warmup Iteration   1: 4.974 ops/ms
# Warmup Iteration   2: 7.164 ops/ms
# Warmup Iteration   3: 7.668 ops/ms
Iteration   1: 7.879 ops/ms
Iteration   2: 7.681 ops/ms
Iteration   3: 7.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.733 ±(99.9%) 2.335 ops/ms [Average]
  (min, avg, max) = (7.639, 7.733, 7.879), stdev = 0.128
  CI (99.9%): [5.398, 10.068] (assumes normal distribution)


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
# Warmup Iteration   1: 4.727 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.015 ms/op
Iteration   1: 3.109 ±(99.9%) 0.002 ms/op
Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
Iteration   3: 3.154 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.135 ±(99.9%) 0.430 ms/op [Average]
  (min, avg, max) = (3.109, 3.135, 3.154), stdev = 0.024
  CI (99.9%): [2.705, 3.565] (assumes normal distribution)


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.002 ms/op
Iteration   1: 2.954 ±(99.9%) 0.002 ms/op
Iteration   2: 2.920 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.986 ±(99.9%) 1.578 ms/op [Average]
  (min, avg, max) = (2.920, 2.986, 3.084), stdev = 0.086
  CI (99.9%): [1.409, 4.564] (assumes normal distribution)


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
# Warmup Iteration   1: 4.619 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.003 ms/op
Iteration   1: 3.098 ±(99.9%) 0.003 ms/op
Iteration   2: 3.136 ±(99.9%) 0.003 ms/op
Iteration   3: 3.134 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.123 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (3.098, 3.123, 3.136), stdev = 0.021
  CI (99.9%): [2.734, 3.512] (assumes normal distribution)


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
# Warmup Iteration   1: 5.463 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.013 ms/op
Iteration   1: 4.037 ±(99.9%) 0.009 ms/op
Iteration   2: 4.066 ±(99.9%) 0.020 ms/op
Iteration   3: 4.041 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.048 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (4.037, 4.048, 4.066), stdev = 0.016
  CI (99.9%): [3.761, 4.335] (assumes normal distribution)


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  8.666 ms/op
                 createUser·p0.9999: 13.709 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  9.708 ms/op
                 createUser·p0.9999: 14.886 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 23.649 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306951
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11486 
    [ 2.500,  5.000) = 293141 
    [ 5.000,  7.500) = 1541 
    [ 7.500, 10.000) = 525 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     23.111 ms/op
     p(99.9990) =     23.787 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 4.107 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
Iteration   1: 3.018 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.294 ms/op
                 existUser·p0.999:  7.887 ms/op
                 existUser·p0.9999: 13.634 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  9.683 ms/op
                 existUser·p0.9999: 15.176 ms/op
                 existUser·p1.00:   15.794 ms/op

Iteration   3: 2.984 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  8.502 ms/op
                 existUser·p0.9999: 29.032 ms/op
                 existUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320193
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21702 
    [ 2.500,  5.000) = 296562 
    [ 5.000,  7.500) = 1411 
    [ 7.500, 10.000) = 284 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.385 ms/op
     p(99.9900) =     27.779 ms/op
     p(99.9990) =     29.870 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 4.852 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  9.232 ms/op
                 getUser·p0.9999: 18.614 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  8.913 ms/op
                 getUser·p0.9999: 14.214 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   3: 3.178 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  9.523 ms/op
                 getUser·p0.9999: 20.543 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304603
  mean =      3.150 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11594 
    [ 2.500,  5.000) = 290424 
    [ 5.000,  7.500) = 1864 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     21.493 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 5.370 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.587 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.012 ms/op
Iteration   1: 4.120 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  14.602 ms/op
                 listUser·p0.9999: 16.752 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 4.128 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  16.325 ms/op
                 listUser·p0.9999: 25.426 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   3: 4.038 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  22.413 ms/op
                 listUser·p0.9999: 31.951 ms/op
                 listUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234573
  mean =      4.095 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2605 
    [ 2.500,  5.000) = 204506 
    [ 5.000,  7.500) = 25121 
    [ 7.500, 10.000) = 1847 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     15.949 ms/op
     p(99.9900) =     31.004 ms/op
     p(99.9990) =     32.014 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.075 ± 1.684  ops/ms
ClientGrpc.existUser                       thrpt       3  10.706 ± 1.835  ops/ms
ClientGrpc.getUser                         thrpt       3  10.161 ± 0.482  ops/ms
ClientGrpc.listUser                        thrpt       3   7.733 ± 2.335  ops/ms
ClientGrpc.createUser                       avgt       3   3.135 ± 0.430   ms/op
ClientGrpc.existUser                        avgt       3   2.986 ± 1.578   ms/op
ClientGrpc.getUser                          avgt       3   3.123 ± 0.389   ms/op
ClientGrpc.listUser                         avgt       3   4.048 ± 0.287   ms/op
ClientGrpc.createUser                     sample  306951   3.129 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.667           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.454           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.111           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.986           ms/op
ClientGrpc.existUser                      sample  320193   2.997 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.753           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.385           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.779           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.408           ms/op
ClientGrpc.getUser                        sample  304603   3.150 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.893           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.191           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.316           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.692           ms/op
ClientGrpc.listUser                       sample  234573   4.095 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.253           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.496           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.949           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.004           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.047           ms/op
