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
# Warmup Iteration   1: 4.335 ops/ms
# Warmup Iteration   2: 8.972 ops/ms
# Warmup Iteration   3: 9.583 ops/ms
Iteration   1: 10.301 ops/ms
Iteration   2: 10.231 ops/ms
Iteration   3: 9.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.151 ±(99.9%) 3.685 ops/ms [Average]
  (min, avg, max) = (9.921, 10.151, 10.301), stdev = 0.202
  CI (99.9%): [6.466, 13.837] (assumes normal distribution)


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
# Warmup Iteration   1: 7.436 ops/ms
# Warmup Iteration   2: 10.413 ops/ms
# Warmup Iteration   3: 10.855 ops/ms
Iteration   1: 11.091 ops/ms
Iteration   2: 10.902 ops/ms
Iteration   3: 11.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.087 ±(99.9%) 3.359 ops/ms [Average]
  (min, avg, max) = (10.902, 11.087, 11.270), stdev = 0.184
  CI (99.9%): [7.729, 14.446] (assumes normal distribution)


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
# Warmup Iteration   1: 6.735 ops/ms
# Warmup Iteration   2: 9.945 ops/ms
# Warmup Iteration   3: 10.227 ops/ms
Iteration   1: 10.282 ops/ms
Iteration   2: 10.497 ops/ms
Iteration   3: 10.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.425 ±(99.9%) 2.250 ops/ms [Average]
  (min, avg, max) = (10.282, 10.425, 10.497), stdev = 0.123
  CI (99.9%): [8.175, 12.675] (assumes normal distribution)


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
# Warmup Iteration   1: 6.301 ops/ms
# Warmup Iteration   2: 7.501 ops/ms
# Warmup Iteration   3: 7.987 ops/ms
Iteration   1: 7.917 ops/ms
Iteration   2: 7.918 ops/ms
Iteration   3: 7.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.853 ±(99.9%) 2.047 ops/ms [Average]
  (min, avg, max) = (7.723, 7.853, 7.918), stdev = 0.112
  CI (99.9%): [5.806, 9.900] (assumes normal distribution)


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.003 ms/op
Iteration   1: 3.146 ±(99.9%) 0.002 ms/op
Iteration   2: 3.035 ±(99.9%) 0.002 ms/op
Iteration   3: 3.054 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.078 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (3.035, 3.078, 3.146), stdev = 0.059
  CI (99.9%): [1.994, 4.161] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.002 ms/op
Iteration   1: 2.891 ±(99.9%) 0.002 ms/op
Iteration   2: 2.929 ±(99.9%) 0.002 ms/op
Iteration   3: 2.942 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.921 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (2.891, 2.921, 2.942), stdev = 0.026
  CI (99.9%): [2.438, 3.404] (assumes normal distribution)


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.003 ms/op
Iteration   1: 3.138 ±(99.9%) 0.003 ms/op
Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
Iteration   3: 3.106 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.124 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (3.106, 3.124, 3.138), stdev = 0.017
  CI (99.9%): [2.819, 3.430] (assumes normal distribution)


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.019 ms/op
Iteration   1: 4.085 ±(99.9%) 0.017 ms/op
Iteration   2: 3.945 ±(99.9%) 0.013 ms/op
Iteration   3: 4.013 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.014 ±(99.9%) 1.271 ms/op [Average]
  (min, avg, max) = (3.945, 4.014, 4.085), stdev = 0.070
  CI (99.9%): [2.743, 5.286] (assumes normal distribution)


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.008 ms/op
Iteration   1: 3.099 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.558 ms/op
                 createUser·p0.999:  11.514 ms/op
                 createUser·p0.9999: 19.431 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.109 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.483 ms/op
                 createUser·p0.999:  9.669 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  9.171 ms/op
                 createUser·p0.9999: 23.380 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311224
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19634 
    [ 2.500,  5.000) = 287630 
    [ 5.000,  7.500) = 3116 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     10.449 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     24.073 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
Iteration   1: 2.992 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.337 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  7.503 ms/op
                 existUser·p0.9999: 10.998 ms/op
                 existUser·p1.00:   11.354 ms/op

Iteration   2: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.285 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  8.065 ms/op
                 existUser·p0.9999: 14.713 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   3: 2.930 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.566 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.976 ms/op
                 existUser·p0.9999: 18.285 ms/op
                 existUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325040
  mean =      2.955 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1716 
    [ 1.250,  2.500) = 37369 
    [ 2.500,  3.750) = 271870 
    [ 3.750,  5.000) = 11962 
    [ 5.000,  6.250) = 1026 
    [ 6.250,  7.500) = 693 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.285 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      7.733 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     18.342 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.157 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.120 ms/op
                 getUser·p0.999:  9.531 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.475 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.965 ms/op
                 getUser·p0.999:  8.193 ms/op
                 getUser·p0.9999: 22.134 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 3.121 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  7.815 ms/op
                 getUser·p0.9999: 28.689 ms/op
                 getUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309129
  mean =      3.103 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18604 
    [ 2.500,  5.000) = 286672 
    [ 5.000,  7.500) = 3168 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     27.594 ms/op
     p(99.9990) =     28.866 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 5.939 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.015 ms/op
Iteration   1: 4.092 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 16.983 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   2: 4.134 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.526 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  16.864 ms/op
                 listUser·p0.9999: 25.111 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 4.021 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  15.619 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235328
  mean =      4.081 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3836 
    [ 2.500,  5.000) = 196768 
    [ 5.000,  7.500) = 32079 
    [ 7.500, 10.000) = 2046 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      7.633 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     21.214 ms/op
     p(99.9990) =     25.536 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.151 ± 3.685  ops/ms
ClientGrpc.existUser                       thrpt       3  11.087 ± 3.359  ops/ms
ClientGrpc.getUser                         thrpt       3  10.425 ± 2.250  ops/ms
ClientGrpc.listUser                        thrpt       3   7.853 ± 2.047  ops/ms
ClientGrpc.createUser                       avgt       3   3.078 ± 1.083   ms/op
ClientGrpc.existUser                        avgt       3   2.921 ± 0.483   ms/op
ClientGrpc.getUser                          avgt       3   3.124 ± 0.305   ms/op
ClientGrpc.listUser                         avgt       3   4.014 ± 1.271   ms/op
ClientGrpc.createUser                     sample  311224   3.084 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.483           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.449           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.249           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.216           ms/op
ClientGrpc.existUser                      sample  325040   2.955 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.285           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.733           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.072           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.890           ms/op
ClientGrpc.getUser                        sample  309129   3.103 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.475           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.965           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.618           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.594           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.967           ms/op
ClientGrpc.listUser                       sample  235328   4.081 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.526           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.136           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.633           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.214           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
