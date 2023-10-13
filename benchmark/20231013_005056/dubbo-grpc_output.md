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
# Warmup Iteration   1: 3.931 ops/ms
# Warmup Iteration   2: 8.618 ops/ms
# Warmup Iteration   3: 9.838 ops/ms
Iteration   1: 10.063 ops/ms
Iteration   2: 10.328 ops/ms
Iteration   3: 10.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.220 ±(99.9%) 2.533 ops/ms [Average]
  (min, avg, max) = (10.063, 10.220, 10.328), stdev = 0.139
  CI (99.9%): [7.687, 12.753] (assumes normal distribution)


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
# Warmup Iteration   1: 7.310 ops/ms
# Warmup Iteration   2: 9.934 ops/ms
# Warmup Iteration   3: 10.528 ops/ms
Iteration   1: 10.548 ops/ms
Iteration   2: 10.652 ops/ms
Iteration   3: 10.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.558 ±(99.9%) 1.636 ops/ms [Average]
  (min, avg, max) = (10.474, 10.558, 10.652), stdev = 0.090
  CI (99.9%): [8.922, 12.194] (assumes normal distribution)


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
# Warmup Iteration   1: 6.409 ops/ms
# Warmup Iteration   2: 9.793 ops/ms
# Warmup Iteration   3: 9.865 ops/ms
Iteration   1: 10.237 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 10.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.284 ±(99.9%) 0.759 ops/ms [Average]
  (min, avg, max) = (10.237, 10.284, 10.316), stdev = 0.042
  CI (99.9%): [9.525, 11.043] (assumes normal distribution)


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
# Warmup Iteration   1: 5.147 ops/ms
# Warmup Iteration   2: 7.984 ops/ms
# Warmup Iteration   3: 8.122 ops/ms
Iteration   1: 8.141 ops/ms
Iteration   2: 8.070 ops/ms
Iteration   3: 8.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.147 ±(99.9%) 1.469 ops/ms [Average]
  (min, avg, max) = (8.070, 8.147, 8.231), stdev = 0.080
  CI (99.9%): [6.679, 9.616] (assumes normal distribution)


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.004 ms/op
Iteration   1: 3.143 ±(99.9%) 0.004 ms/op
Iteration   2: 3.132 ±(99.9%) 0.003 ms/op
Iteration   3: 3.271 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.182 ±(99.9%) 1.408 ms/op [Average]
  (min, avg, max) = (3.132, 3.182, 3.271), stdev = 0.077
  CI (99.9%): [1.774, 4.590] (assumes normal distribution)


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 2.984 ±(99.9%) 0.003 ms/op
Iteration   2: 2.875 ±(99.9%) 0.004 ms/op
Iteration   3: 2.959 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.939 ±(99.9%) 1.041 ms/op [Average]
  (min, avg, max) = (2.875, 2.939, 2.984), stdev = 0.057
  CI (99.9%): [1.899, 3.980] (assumes normal distribution)


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.003 ms/op
Iteration   1: 3.169 ±(99.9%) 0.005 ms/op
Iteration   2: 3.152 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.140 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (3.100, 3.140, 3.169), stdev = 0.036
  CI (99.9%): [2.492, 3.788] (assumes normal distribution)


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
# Warmup Iteration   1: 5.123 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.021 ms/op
Iteration   1: 3.780 ±(99.9%) 0.014 ms/op
Iteration   2: 3.972 ±(99.9%) 0.017 ms/op
Iteration   3: 3.822 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.858 ±(99.9%) 1.841 ms/op [Average]
  (min, avg, max) = (3.780, 3.858, 3.972), stdev = 0.101
  CI (99.9%): [2.017, 5.699] (assumes normal distribution)


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
# Warmup Iteration   1: 4.471 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.007 ms/op
Iteration   1: 3.112 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  11.423 ms/op
                 createUser·p0.9999: 20.340 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  15.623 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   3: 3.115 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  12.792 ms/op
                 createUser·p0.9999: 29.351 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307016
  mean =      3.128 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13752 
    [ 2.500,  5.000) = 290987 
    [ 5.000,  7.500) = 1566 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =     11.763 ms/op
     p(99.9900) =     21.387 ms/op
     p(99.9990) =     29.426 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.033 ms/op
                 existUser·p0.9999: 17.680 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  13.688 ms/op
                 existUser·p0.9999: 17.174 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  8.928 ms/op
                 existUser·p0.9999: 15.904 ms/op
                 existUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315586
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22683 
    [ 2.500,  5.000) = 291261 
    [ 5.000,  7.500) = 1135 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =     10.922 ms/op
     p(99.9900) =     17.363 ms/op
     p(99.9990) =     20.503 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 4.691 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.008 ms/op
Iteration   1: 3.167 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  10.943 ms/op
                 getUser·p0.9999: 21.836 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  13.744 ms/op
                 getUser·p0.9999: 20.399 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  8.749 ms/op
                 getUser·p0.9999: 18.673 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304991
  mean =      3.146 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12886 
    [ 2.500,  5.000) = 289861 
    [ 5.000,  7.500) = 1699 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     22.345 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 5.773 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.010 ms/op
Iteration   1: 4.033 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  14.118 ms/op
                 listUser·p0.9999: 17.276 ms/op
                 listUser·p1.00:   17.891 ms/op

Iteration   2: 3.906 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.991 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 16.722 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 4.000 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.609 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  17.891 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241093
  mean =      3.979 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2854 
    [ 2.500,  5.000) = 220267 
    [ 5.000,  7.500) = 16261 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     19.395 ms/op
     p(99.9990) =     20.388 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.220 ± 2.533  ops/ms
ClientGrpc.existUser                       thrpt       3  10.558 ± 1.636  ops/ms
ClientGrpc.getUser                         thrpt       3  10.284 ± 0.759  ops/ms
ClientGrpc.listUser                        thrpt       3   8.147 ± 1.469  ops/ms
ClientGrpc.createUser                       avgt       3   3.182 ± 1.408   ms/op
ClientGrpc.existUser                        avgt       3   2.939 ± 1.041   ms/op
ClientGrpc.getUser                          avgt       3   3.140 ± 0.648   ms/op
ClientGrpc.listUser                         avgt       3   3.858 ± 1.841   ms/op
ClientGrpc.createUser                     sample  307016   3.128 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.763           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.387           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.426           ms/op
ClientGrpc.existUser                      sample  315586   3.042 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.697           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.922           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.363           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.611           ms/op
ClientGrpc.getUser                        sample  304991   3.146 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.642           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.255           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.513           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.446           ms/op
ClientGrpc.listUser                       sample  241093   3.979 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.027           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.303           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.395           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.513           ms/op
