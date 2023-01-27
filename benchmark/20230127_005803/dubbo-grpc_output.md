# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.305 ops/ms
# Warmup Iteration   2: 8.861 ops/ms
# Warmup Iteration   3: 9.888 ops/ms
Iteration   1: 10.439 ops/ms
Iteration   2: 10.114 ops/ms
Iteration   3: 10.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.196 ±(99.9%) 3.911 ops/ms [Average]
  (min, avg, max) = (10.035, 10.196, 10.439), stdev = 0.214
  CI (99.9%): [6.284, 14.107] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.381 ops/ms
# Warmup Iteration   2: 10.200 ops/ms
# Warmup Iteration   3: 10.703 ops/ms
Iteration   1: 10.681 ops/ms
Iteration   2: 10.503 ops/ms
Iteration   3: 10.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.533 ±(99.9%) 2.469 ops/ms [Average]
  (min, avg, max) = (10.415, 10.533, 10.681), stdev = 0.135
  CI (99.9%): [8.064, 13.002] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.169 ops/ms
# Warmup Iteration   2: 9.907 ops/ms
# Warmup Iteration   3: 10.183 ops/ms
Iteration   1: 10.154 ops/ms
Iteration   2: 10.294 ops/ms
Iteration   3: 9.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.112 ±(99.9%) 3.751 ops/ms [Average]
  (min, avg, max) = (9.889, 10.112, 10.294), stdev = 0.206
  CI (99.9%): [6.361, 13.863] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.278 ops/ms
# Warmup Iteration   2: 7.774 ops/ms
# Warmup Iteration   3: 7.807 ops/ms
Iteration   1: 7.882 ops/ms
Iteration   2: 8.070 ops/ms
Iteration   3: 8.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.097 ±(99.9%) 4.184 ops/ms [Average]
  (min, avg, max) = (7.882, 8.097, 8.339), stdev = 0.229
  CI (99.9%): [3.913, 12.280] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.010 ms/op
Iteration   1: 3.222 ±(99.9%) 0.002 ms/op
Iteration   2: 3.149 ±(99.9%) 0.002 ms/op
Iteration   3: 3.141 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.170 ±(99.9%) 0.812 ms/op [Average]
  (min, avg, max) = (3.141, 3.170, 3.222), stdev = 0.044
  CI (99.9%): [2.359, 3.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.187 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.002 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 2.959 ±(99.9%) 0.002 ms/op
Iteration   3: 3.143 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.050 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (2.959, 3.050, 3.143), stdev = 0.092
  CI (99.9%): [1.370, 4.731] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.003 ms/op
Iteration   1: 3.150 ±(99.9%) 0.002 ms/op
Iteration   2: 3.169 ±(99.9%) 0.002 ms/op
Iteration   3: 3.181 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.167 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (3.150, 3.167, 3.181), stdev = 0.016
  CI (99.9%): [2.875, 3.458] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.698 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.020 ms/op
Iteration   1: 3.973 ±(99.9%) 0.012 ms/op
Iteration   2: 3.972 ±(99.9%) 0.007 ms/op
Iteration   3: 3.962 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.969 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (3.962, 3.969, 3.973), stdev = 0.006
  CI (99.9%): [3.855, 4.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  8.181 ms/op
                 createUser·p0.9999: 23.284 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.720 ms/op
                 createUser·p0.9999: 17.955 ms/op
                 createUser·p1.00:   18.317 ms/op

Iteration   3: 3.205 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  13.943 ms/op
                 createUser·p0.9999: 32.244 ms/op
                 createUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302721
  mean =      3.171 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23677 
    [ 2.500,  5.000) = 277255 
    [ 5.000,  7.500) = 1341 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.721 ms/op
     p(99.9900) =     30.334 ms/op
     p(99.9990) =     32.439 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.050 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.505 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  6.773 ms/op
                 existUser·p0.9999: 10.686 ms/op
                 existUser·p1.00:   11.911 ms/op

Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.307 ms/op
                 existUser·p0.9999: 14.041 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.933 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 15.979 ms/op
                 existUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327477
  mean =      2.931 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2591 
    [ 1.250,  2.500) = 51278 
    [ 2.500,  3.750) = 256013 
    [ 3.750,  5.000) = 16339 
    [ 5.000,  6.250) = 543 
    [ 6.250,  7.500) = 323 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.959 ms/op
     p(99.9900) =     15.618 ms/op
     p(99.9990) =     16.265 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
Iteration   1: 3.064 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  6.791 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.240 ms/op
                 getUser·p0.9999: 18.247 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   3: 3.144 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  8.475 ms/op
                 getUser·p0.9999: 21.582 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307637
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23514 
    [ 2.500,  5.000) = 282306 
    [ 5.000,  7.500) = 1491 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.635 ms/op
     p(99.9900) =     19.349 ms/op
     p(99.9990) =     22.015 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.573 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.010 ms/op
Iteration   1: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  13.029 ms/op
                 listUser·p0.9999: 19.394 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  14.738 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   3: 4.037 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 18.779 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240348
  mean =      3.993 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2832 
    [ 2.500,  3.750) = 106477 
    [ 3.750,  5.000) = 102715 
    [ 5.000,  6.250) = 20788 
    [ 6.250,  7.500) = 6163 
    [ 7.500,  8.750) = 657 
    [ 8.750, 10.000) = 209 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 101 
    [17.500, 18.750) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     14.954 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     19.719 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.196 ± 3.911  ops/ms
ClientGrpc.existUser                       thrpt       3  10.533 ± 2.469  ops/ms
ClientGrpc.getUser                         thrpt       3  10.112 ± 3.751  ops/ms
ClientGrpc.listUser                        thrpt       3   8.097 ± 4.184  ops/ms
ClientGrpc.createUser                       avgt       3   3.170 ± 0.812   ms/op
ClientGrpc.existUser                        avgt       3   3.050 ± 1.680   ms/op
ClientGrpc.getUser                          avgt       3   3.167 ± 0.292   ms/op
ClientGrpc.listUser                         avgt       3   3.969 ± 0.114   ms/op
ClientGrpc.createUser                     sample  302721   3.171 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.644           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.051           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.721           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.334           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.506           ms/op
ClientGrpc.existUser                      sample  327477   2.931 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.505           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.959           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.618           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.368           ms/op
ClientGrpc.getUser                        sample  307637   3.121 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.673           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.635           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.349           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.118           ms/op
ClientGrpc.listUser                       sample  240348   3.993 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.176           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.954           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.874           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.890           ms/op
