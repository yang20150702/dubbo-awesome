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
# Warmup Iteration   1: 4.473 ops/ms
# Warmup Iteration   2: 9.104 ops/ms
# Warmup Iteration   3: 9.872 ops/ms
Iteration   1: 10.449 ops/ms
Iteration   2: 10.315 ops/ms
Iteration   3: 10.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.379 ±(99.9%) 1.223 ops/ms [Average]
  (min, avg, max) = (10.315, 10.379, 10.449), stdev = 0.067
  CI (99.9%): [9.156, 11.602] (assumes normal distribution)


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
# Warmup Iteration   1: 7.908 ops/ms
# Warmup Iteration   2: 10.506 ops/ms
# Warmup Iteration   3: 10.676 ops/ms
Iteration   1: 10.950 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.783 ±(99.9%) 2.654 ops/ms [Average]
  (min, avg, max) = (10.691, 10.783, 10.950), stdev = 0.145
  CI (99.9%): [8.129, 13.436] (assumes normal distribution)


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
# Warmup Iteration   1: 7.302 ops/ms
# Warmup Iteration   2: 9.641 ops/ms
# Warmup Iteration   3: 9.915 ops/ms
Iteration   1: 10.035 ops/ms
Iteration   2: 9.908 ops/ms
Iteration   3: 9.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.955 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (9.908, 9.955, 10.035), stdev = 0.070
  CI (99.9%): [8.684, 11.225] (assumes normal distribution)


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
# Warmup Iteration   1: 5.561 ops/ms
# Warmup Iteration   2: 7.953 ops/ms
# Warmup Iteration   3: 8.289 ops/ms
Iteration   1: 8.234 ops/ms
Iteration   2: 8.205 ops/ms
Iteration   3: 8.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.223 ±(99.9%) 0.279 ops/ms [Average]
  (min, avg, max) = (8.205, 8.223, 8.234), stdev = 0.015
  CI (99.9%): [7.944, 8.502] (assumes normal distribution)


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.003 ms/op
Iteration   1: 3.204 ±(99.9%) 0.001 ms/op
Iteration   2: 3.084 ±(99.9%) 0.004 ms/op
Iteration   3: 3.178 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.155 ±(99.9%) 1.155 ms/op [Average]
  (min, avg, max) = (3.084, 3.155, 3.204), stdev = 0.063
  CI (99.9%): [2.001, 4.310] (assumes normal distribution)


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.002 ms/op
Iteration   1: 3.062 ±(99.9%) 0.002 ms/op
Iteration   2: 3.000 ±(99.9%) 0.002 ms/op
Iteration   3: 2.972 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.011 ±(99.9%) 0.841 ms/op [Average]
  (min, avg, max) = (2.972, 3.011, 3.062), stdev = 0.046
  CI (99.9%): [2.170, 3.852] (assumes normal distribution)


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.001 ms/op
Iteration   1: 3.125 ±(99.9%) 0.003 ms/op
Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
Iteration   3: 3.125 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.106 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.067, 3.106, 3.125), stdev = 0.034
  CI (99.9%): [2.489, 3.722] (assumes normal distribution)


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
# Warmup Iteration   1: 5.664 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.025 ms/op
Iteration   1: 3.897 ±(99.9%) 0.014 ms/op
Iteration   2: 3.768 ±(99.9%) 0.012 ms/op
Iteration   3: 3.876 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.847 ±(99.9%) 1.260 ms/op [Average]
  (min, avg, max) = (3.768, 3.847, 3.897), stdev = 0.069
  CI (99.9%): [2.587, 5.107] (assumes normal distribution)


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.006 ms/op
Iteration   1: 3.157 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.327 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 15.825 ms/op
                 createUser·p1.00:   16.695 ms/op

Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  7.753 ms/op
                 createUser·p0.9999: 17.442 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 19.595 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309048
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11306 
    [ 2.500,  5.000) = 295800 
    [ 5.000,  7.500) = 1400 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     20.507 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
Iteration   1: 2.905 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.537 ms/op
                 existUser·p0.9999: 14.729 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   2: 3.081 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.973 ms/op
                 existUser·p0.9999: 18.272 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.850 ms/op
                 existUser·p0.9999: 19.639 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320723
  mean =      2.994 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22486 
    [ 2.500,  5.000) = 296797 
    [ 5.000,  7.500) = 1226 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      6.826 ms/op
     p(99.9900) =     18.348 ms/op
     p(99.9990) =     19.889 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 4.298 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  9.330 ms/op
                 getUser·p0.9999: 17.001 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.340 ms/op
                 getUser·p0.9999: 17.528 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.515 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.096 ms/op
                 getUser·p0.9999: 18.674 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306399
  mean =      3.133 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 415 
    [ 1.250,  2.500) = 10207 
    [ 2.500,  3.750) = 269112 
    [ 3.750,  5.000) = 24969 
    [ 5.000,  6.250) = 931 
    [ 6.250,  7.500) = 368 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 72 
    [17.500, 18.750) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.333 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     18.872 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.867 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.010 ms/op
Iteration   1: 3.910 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  13.061 ms/op
                 listUser·p0.9999: 16.542 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   2: 3.873 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 17.202 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   3: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 18.658 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247364
  mean =      3.879 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 3031 
    [ 2.500,  3.750) = 109351 
    [ 3.750,  5.000) = 121424 
    [ 5.000,  6.250) = 8728 
    [ 6.250,  7.500) = 3771 
    [ 7.500,  8.750) = 331 
    [ 8.750, 10.000) = 179 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 158 
    [13.750, 15.000) = 95 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 78 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     19.711 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.379 ± 1.223  ops/ms
ClientGrpc.existUser                       thrpt       3  10.783 ± 2.654  ops/ms
ClientGrpc.getUser                         thrpt       3   9.955 ± 1.271  ops/ms
ClientGrpc.listUser                        thrpt       3   8.223 ± 0.279  ops/ms
ClientGrpc.createUser                       avgt       3   3.155 ± 1.155   ms/op
ClientGrpc.existUser                        avgt       3   3.011 ± 0.841   ms/op
ClientGrpc.getUser                          avgt       3   3.106 ± 0.617   ms/op
ClientGrpc.listUser                         avgt       3   3.847 ± 1.260   ms/op
ClientGrpc.createUser                     sample  309048   3.106 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.327           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.159           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.285           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.611           ms/op
ClientGrpc.existUser                      sample  320723   2.994 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.635           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.826           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.348           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.087           ms/op
ClientGrpc.getUser                        sample  306399   3.133 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.515           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.333           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.924           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.169           ms/op
ClientGrpc.listUser                       sample  247364   3.879 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.992           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.317           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.562           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.861           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.022           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.825           ms/op
