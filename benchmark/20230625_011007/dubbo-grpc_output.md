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
# Warmup Iteration   1: 4.294 ops/ms
# Warmup Iteration   2: 9.014 ops/ms
# Warmup Iteration   3: 10.149 ops/ms
Iteration   1: 10.340 ops/ms
Iteration   2: 10.503 ops/ms
Iteration   3: 10.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.386 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (10.315, 10.386, 10.503), stdev = 0.102
  CI (99.9%): [8.523, 12.249] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.737 ops/ms
# Warmup Iteration   2: 10.232 ops/ms
# Warmup Iteration   3: 10.618 ops/ms
Iteration   1: 10.642 ops/ms
Iteration   2: 11.249 ops/ms
Iteration   3: 10.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.859 ±(99.9%) 6.184 ops/ms [Average]
  (min, avg, max) = (10.642, 10.859, 11.249), stdev = 0.339
  CI (99.9%): [4.675, 17.042] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.841 ops/ms
# Warmup Iteration   2: 9.915 ops/ms
# Warmup Iteration   3: 10.179 ops/ms
Iteration   1: 10.366 ops/ms
Iteration   2: 10.339 ops/ms
Iteration   3: 10.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.336 ±(99.9%) 0.583 ops/ms [Average]
  (min, avg, max) = (10.303, 10.336, 10.366), stdev = 0.032
  CI (99.9%): [9.753, 10.920] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.229 ops/ms
# Warmup Iteration   2: 7.271 ops/ms
# Warmup Iteration   3: 7.886 ops/ms
Iteration   1: 7.973 ops/ms
Iteration   2: 7.742 ops/ms
Iteration   3: 8.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.935 ±(99.9%) 3.242 ops/ms [Average]
  (min, avg, max) = (7.742, 7.935, 8.091), stdev = 0.178
  CI (99.9%): [4.693, 11.178] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.243 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.003 ms/op
Iteration   1: 3.102 ±(99.9%) 0.002 ms/op
Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.072 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.010, 3.072, 3.103), stdev = 0.054
  CI (99.9%): [2.096, 4.048] (assumes normal distribution)


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
# Warmup Iteration   1: 4.006 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.002 ms/op
Iteration   1: 2.957 ±(99.9%) 0.002 ms/op
Iteration   2: 2.971 ±(99.9%) 0.002 ms/op
Iteration   3: 2.949 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.959 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.949, 2.959, 2.971), stdev = 0.011
  CI (99.9%): [2.750, 3.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.005 ms/op
Iteration   1: 3.080 ±(99.9%) 0.003 ms/op
Iteration   2: 3.103 ±(99.9%) 0.004 ms/op
Iteration   3: 3.034 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.072 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (3.034, 3.072, 3.103), stdev = 0.035
  CI (99.9%): [2.434, 3.711] (assumes normal distribution)


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
# Warmup Iteration   1: 5.540 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.018 ms/op
Iteration   1: 4.018 ±(99.9%) 0.015 ms/op
Iteration   2: 4.029 ±(99.9%) 0.024 ms/op
Iteration   3: 3.961 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.002 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.961, 4.002, 4.029), stdev = 0.037
  CI (99.9%): [3.336, 4.669] (assumes normal distribution)


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
# Warmup Iteration   1: 4.514 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.048 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.447 ms/op
                 createUser·p0.9999: 12.911 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   2: 3.085 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.418 ms/op
                 createUser·p0.999:  7.485 ms/op
                 createUser·p0.9999: 13.986 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  8.568 ms/op
                 createUser·p0.9999: 17.062 ms/op
                 createUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311664
  mean =      3.078 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 459 
    [ 1.250,  2.500) = 14287 
    [ 2.500,  3.750) = 280793 
    [ 3.750,  5.000) = 14279 
    [ 5.000,  6.250) = 1088 
    [ 6.250,  7.500) = 402 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.769 ms/op
     p(99.9900) =     16.725 ms/op
     p(99.9990) =     17.228 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.307 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.269 ms/op
                 existUser·p0.9999: 18.255 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  9.350 ms/op
                 existUser·p0.9999: 19.211 ms/op
                 existUser·p1.00:   20.644 ms/op

Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  10.715 ms/op
                 existUser·p0.9999: 18.874 ms/op
                 existUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321755
  mean =      2.984 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27239 
    [ 2.500,  5.000) = 293403 
    [ 5.000,  7.500) = 632 
    [ 7.500, 10.000) = 210 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     20.496 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 4.540 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.154 ms/op
                 getUser·p0.9999: 12.548 ms/op
                 getUser·p1.00:   12.845 ms/op

Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  7.750 ms/op
                 getUser·p0.9999: 14.305 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   3: 3.082 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.431 ms/op
                 getUser·p0.9999: 30.573 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310722
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19594 
    [ 2.500,  5.000) = 289216 
    [ 5.000,  7.500) = 1531 
    [ 7.500, 10.000) = 157 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      7.709 ms/op
     p(99.9900) =     29.217 ms/op
     p(99.9990) =     31.293 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 4.811 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.012 ms/op
Iteration   1: 4.121 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  14.250 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  20.589 ms/op
                 listUser·p0.9999: 26.291 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   3: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  18.593 ms/op
                 listUser·p0.9999: 23.967 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235032
  mean =      4.084 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2633 
    [ 2.500,  5.000) = 205362 
    [ 5.000,  7.500) = 25396 
    [ 7.500, 10.000) = 1209 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     17.494 ms/op
     p(99.9900) =     25.215 ms/op
     p(99.9990) =     26.606 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.386 ± 1.863  ops/ms
ClientGrpc.existUser                       thrpt       3  10.859 ± 6.184  ops/ms
ClientGrpc.getUser                         thrpt       3  10.336 ± 0.583  ops/ms
ClientGrpc.listUser                        thrpt       3   7.935 ± 3.242  ops/ms
ClientGrpc.createUser                       avgt       3   3.072 ± 0.976   ms/op
ClientGrpc.existUser                        avgt       3   2.959 ± 0.209   ms/op
ClientGrpc.getUser                          avgt       3   3.072 ± 0.638   ms/op
ClientGrpc.listUser                         avgt       3   4.002 ± 0.667   ms/op
ClientGrpc.createUser                     sample  311664   3.078 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.650           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.769           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.725           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.400           ms/op
ClientGrpc.existUser                      sample  321755   2.984 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.307           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.142           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.711           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.644           ms/op
ClientGrpc.getUser                        sample  310722   3.091 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.847           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.709           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.217           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.359           ms/op
ClientGrpc.listUser                       sample  235032   4.084 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.802           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.494           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.215           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.739           ms/op
