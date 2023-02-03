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
# Warmup Iteration   1: 3.938 ops/ms
# Warmup Iteration   2: 8.768 ops/ms
# Warmup Iteration   3: 9.904 ops/ms
Iteration   1: 10.192 ops/ms
Iteration   2: 10.031 ops/ms
Iteration   3: 10.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.120 ±(99.9%) 1.488 ops/ms [Average]
  (min, avg, max) = (10.031, 10.120, 10.192), stdev = 0.082
  CI (99.9%): [8.632, 11.608] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.117 ops/ms
# Warmup Iteration   2: 9.961 ops/ms
# Warmup Iteration   3: 10.356 ops/ms
Iteration   1: 10.398 ops/ms
Iteration   2: 10.424 ops/ms
Iteration   3: 10.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.460 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (10.398, 10.460, 10.557), stdev = 0.086
  CI (99.9%): [8.899, 12.020] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.593 ops/ms
# Warmup Iteration   2: 9.885 ops/ms
# Warmup Iteration   3: 10.179 ops/ms
Iteration   1: 10.179 ops/ms
Iteration   2: 10.019 ops/ms
Iteration   3: 10.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.076 ±(99.9%) 1.630 ops/ms [Average]
  (min, avg, max) = (10.019, 10.076, 10.179), stdev = 0.089
  CI (99.9%): [8.446, 11.706] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.025 ops/ms
# Warmup Iteration   2: 7.429 ops/ms
# Warmup Iteration   3: 7.830 ops/ms
Iteration   1: 7.838 ops/ms
Iteration   2: 7.916 ops/ms
Iteration   3: 7.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.899 ±(99.9%) 1.001 ops/ms [Average]
  (min, avg, max) = (7.838, 7.899, 7.944), stdev = 0.055
  CI (99.9%): [6.899, 8.900] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.534 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.010 ms/op
Iteration   1: 3.241 ±(99.9%) 0.001 ms/op
Iteration   2: 3.232 ±(99.9%) 0.002 ms/op
Iteration   3: 3.201 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.225 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (3.201, 3.225, 3.241), stdev = 0.021
  CI (99.9%): [2.841, 3.608] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.368 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.002 ms/op
Iteration   1: 3.051 ±(99.9%) 0.002 ms/op
Iteration   2: 3.065 ±(99.9%) 0.002 ms/op
Iteration   3: 3.062 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.059 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (3.051, 3.059, 3.065), stdev = 0.007
  CI (99.9%): [2.931, 3.188] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.365 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.002 ms/op
Iteration   1: 3.232 ±(99.9%) 0.002 ms/op
Iteration   2: 3.157 ±(99.9%) 0.001 ms/op
Iteration   3: 3.218 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.202 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.157, 3.202, 3.232), stdev = 0.040
  CI (99.9%): [2.480, 3.925] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.460 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.023 ms/op
Iteration   1: 4.035 ±(99.9%) 0.019 ms/op
Iteration   2: 4.023 ±(99.9%) 0.020 ms/op
Iteration   3: 4.003 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.020 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (4.003, 4.020, 4.035), stdev = 0.017
  CI (99.9%): [3.718, 4.322] (assumes normal distribution)


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
# Warmup Iteration   1: 4.442 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.006 ms/op
Iteration   1: 3.196 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  10.304 ms/op
                 createUser·p0.9999: 20.021 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   2: 3.204 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.529 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  7.291 ms/op
                 createUser·p0.9999: 17.589 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301172
  mean =      3.187 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18657 
    [ 2.500,  5.000) = 281438 
    [ 5.000,  7.500) = 725 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.683 ms/op
     p(99.9900) =     20.006 ms/op
     p(99.9990) =     20.676 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.005 ms/op
Iteration   1: 3.142 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.669 ms/op
                 existUser·p0.9999: 14.659 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.248 ms/op
                 existUser·p0.9999: 14.789 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.902 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  6.938 ms/op
                 existUser·p0.9999: 16.380 ms/op
                 existUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312713
  mean =      3.070 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1137 
    [ 1.250,  2.500) = 32411 
    [ 2.500,  3.750) = 248593 
    [ 3.750,  5.000) = 29632 
    [ 5.000,  6.250) = 473 
    [ 6.250,  7.500) = 258 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.086 ms/op
     p(99.9900) =     15.233 ms/op
     p(99.9990) =     16.595 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.007 ms/op
Iteration   1: 3.200 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  10.288 ms/op
                 getUser·p0.9999: 14.238 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.636 ms/op
                 getUser·p0.9999: 24.150 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 3.243 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  5.916 ms/op
                 getUser·p0.9999: 17.339 ms/op
                 getUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298840
  mean =      3.212 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16807 
    [ 2.500,  5.000) = 280771 
    [ 5.000,  7.500) = 912 
    [ 7.500, 10.000) = 146 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.898 ms/op
     p(99.9900) =     23.728 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 5.892 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.012 ms/op
Iteration   1: 4.108 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  14.634 ms/op
                 listUser·p0.9999: 20.363 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 4.144 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  17.459 ms/op
                 listUser·p0.9999: 24.183 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   3: 3.978 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.739 ms/op
                 listUser·p0.9999: 18.445 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235434
  mean =      4.076 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1997 
    [ 2.500,  5.000) = 204171 
    [ 5.000,  7.500) = 27727 
    [ 7.500, 10.000) = 1022 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.108 ms/op
     p(99.9000) =     16.377 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     24.466 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.120 ± 1.488  ops/ms
ClientGrpc.existUser                       thrpt       3  10.460 ± 1.560  ops/ms
ClientGrpc.getUser                         thrpt       3  10.076 ± 1.630  ops/ms
ClientGrpc.listUser                        thrpt       3   7.899 ± 1.001  ops/ms
ClientGrpc.createUser                       avgt       3   3.225 ± 0.384   ms/op
ClientGrpc.existUser                        avgt       3   3.059 ± 0.128   ms/op
ClientGrpc.getUser                          avgt       3   3.202 ± 0.723   ms/op
ClientGrpc.listUser                         avgt       3   4.020 ± 0.302   ms/op
ClientGrpc.createUser                     sample  301172   3.187 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.718           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.158           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.030           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.683           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.006           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.775           ms/op
ClientGrpc.existUser                      sample  312713   3.070 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.495           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.039           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.949           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.086           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.233           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.761           ms/op
ClientGrpc.getUser                        sample  298840   3.212 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.762           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.183           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.092           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.898           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.728           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.347           ms/op
ClientGrpc.listUser                       sample  235434   4.076 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.042           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.108           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.377           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.167           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.609           ms/op
