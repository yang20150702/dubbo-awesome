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
# Warmup Iteration   1: 1.895 ops/ms
# Warmup Iteration   2: 4.444 ops/ms
# Warmup Iteration   3: 6.200 ops/ms
Iteration   1: 6.363 ops/ms
Iteration   2: 6.770 ops/ms
Iteration   3: 6.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.604 ±(99.9%) 3.905 ops/ms [Average]
  (min, avg, max) = (6.363, 6.604, 6.770), stdev = 0.214
  CI (99.9%): [2.699, 10.509] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ops/ms
# Warmup Iteration   2: 6.373 ops/ms
# Warmup Iteration   3: 6.877 ops/ms
Iteration   1: 7.103 ops/ms
Iteration   2: 6.699 ops/ms
Iteration   3: 6.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.923 ±(99.9%) 3.746 ops/ms [Average]
  (min, avg, max) = (6.699, 6.923, 7.103), stdev = 0.205
  CI (99.9%): [3.177, 10.668] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.514 ops/ms
# Warmup Iteration   2: 6.235 ops/ms
# Warmup Iteration   3: 6.616 ops/ms
Iteration   1: 6.732 ops/ms
Iteration   2: 6.799 ops/ms
Iteration   3: 6.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.736 ±(99.9%) 1.114 ops/ms [Average]
  (min, avg, max) = (6.677, 6.736, 6.799), stdev = 0.061
  CI (99.9%): [5.621, 7.850] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.154 ops/ms
# Warmup Iteration   2: 4.202 ops/ms
# Warmup Iteration   3: 4.886 ops/ms
Iteration   1: 4.861 ops/ms
Iteration   2: 4.911 ops/ms
Iteration   3: 5.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.943 ±(99.9%) 1.848 ops/ms [Average]
  (min, avg, max) = (4.861, 4.943, 5.056), stdev = 0.101
  CI (99.9%): [3.095, 6.790] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.002 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.503 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.290 ±(99.9%) 0.020 ms/op
Iteration   1: 5.108 ±(99.9%) 0.006 ms/op
Iteration   2: 5.111 ±(99.9%) 0.005 ms/op
Iteration   3: 5.035 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.085 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (5.035, 5.085, 5.111), stdev = 0.043
  CI (99.9%): [4.297, 5.872] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.287 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.225 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.029 ±(99.9%) 0.007 ms/op
Iteration   1: 4.903 ±(99.9%) 0.004 ms/op
Iteration   2: 4.721 ±(99.9%) 0.004 ms/op
Iteration   3: 4.615 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.746 ±(99.9%) 2.657 ms/op [Average]
  (min, avg, max) = (4.615, 4.746, 4.903), stdev = 0.146
  CI (99.9%): [2.090, 7.403] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.037 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.184 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.007 ±(99.9%) 0.006 ms/op
Iteration   1: 4.893 ±(99.9%) 0.023 ms/op
Iteration   2: 4.741 ±(99.9%) 0.005 ms/op
Iteration   3: 4.701 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.778 ±(99.9%) 1.848 ms/op [Average]
  (min, avg, max) = (4.701, 4.778, 4.893), stdev = 0.101
  CI (99.9%): [2.930, 6.626] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.532 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 6.766 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 6.287 ±(99.9%) 0.021 ms/op
Iteration   1: 6.090 ±(99.9%) 0.012 ms/op
Iteration   2: 6.110 ±(99.9%) 0.014 ms/op
Iteration   3: 6.073 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.091 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (6.073, 6.091, 6.110), stdev = 0.019
  CI (99.9%): [5.749, 6.433] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.340 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 5.258 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.992 ±(99.9%) 0.019 ms/op
Iteration   1: 4.806 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   4.604 ms/op
                 createUser·p0.90:   6.128 ms/op
                 createUser·p0.95:   6.963 ms/op
                 createUser·p0.99:   9.322 ms/op
                 createUser·p0.999:  15.077 ms/op
                 createUser·p0.9999: 16.450 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   2: 4.862 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   4.637 ms/op
                 createUser·p0.90:   6.324 ms/op
                 createUser·p0.95:   7.307 ms/op
                 createUser·p0.99:   10.294 ms/op
                 createUser·p0.999:  16.437 ms/op
                 createUser·p0.9999: 24.328 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   3: 4.710 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   5.988 ms/op
                 createUser·p0.95:   6.775 ms/op
                 createUser·p0.99:   9.568 ms/op
                 createUser·p0.999:  15.745 ms/op
                 createUser·p0.9999: 24.236 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 200302
  mean =      4.792 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3869 
    [ 2.500,  5.000) = 131037 
    [ 5.000,  7.500) = 58265 
    [ 7.500, 10.000) = 5353 
    [10.000, 12.500) = 1076 
    [12.500, 15.000) = 425 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      7.012 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     15.576 ms/op
     p(99.9900) =     23.427 ms/op
     p(99.9990) =     27.424 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.634 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.131 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.567 ±(99.9%) 0.015 ms/op
Iteration   1: 4.651 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   4.432 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   7.143 ms/op
                 existUser·p0.99:   9.437 ms/op
                 existUser·p0.999:  12.014 ms/op
                 existUser·p0.9999: 22.585 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 4.597 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   4.350 ms/op
                 existUser·p0.90:   5.988 ms/op
                 existUser·p0.95:   6.865 ms/op
                 existUser·p0.99:   9.781 ms/op
                 existUser·p0.999:  19.005 ms/op
                 existUser·p0.9999: 21.890 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   3: 4.650 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   4.350 ms/op
                 existUser·p0.90:   6.169 ms/op
                 existUser·p0.95:   7.258 ms/op
                 existUser·p0.99:   10.469 ms/op
                 existUser·p0.999:  16.403 ms/op
                 existUser·p0.9999: 28.844 ms/op
                 existUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 207206
  mean =      4.633 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6735 
    [ 2.500,  5.000) = 144215 
    [ 5.000,  7.500) = 48297 
    [ 7.500, 10.000) = 6038 
    [10.000, 12.500) = 1230 
    [12.500, 15.000) = 369 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      7.086 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     16.348 ms/op
     p(99.9900) =     26.813 ms/op
     p(99.9990) =     29.063 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.989 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 5.238 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.781 ±(99.9%) 0.019 ms/op
Iteration   1: 4.741 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   6.119 ms/op
                 getUser·p0.95:   7.037 ms/op
                 getUser·p0.99:   10.706 ms/op
                 getUser·p0.999:  16.713 ms/op
                 getUser·p0.9999: 18.293 ms/op
                 getUser·p1.00:   18.579 ms/op

Iteration   2: 4.746 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   6.078 ms/op
                 getUser·p0.95:   6.791 ms/op
                 getUser·p0.99:   9.404 ms/op
                 getUser·p0.999:  13.771 ms/op
                 getUser·p0.9999: 24.134 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   3: 4.867 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   6.365 ms/op
                 getUser·p0.95:   7.356 ms/op
                 getUser·p0.99:   10.011 ms/op
                 getUser·p0.999:  15.766 ms/op
                 getUser·p0.9999: 24.047 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 200614
  mean =      4.784 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5323 
    [ 2.500,  5.000) = 129645 
    [ 5.000,  7.500) = 58215 
    [ 7.500, 10.000) = 5401 
    [10.000, 12.500) = 1368 
    [12.500, 15.000) = 449 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      6.185 ms/op
     p(95.0000) =      7.053 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     15.426 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     26.147 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.211 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 6.760 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.250 ±(99.9%) 0.030 ms/op
Iteration   1: 6.223 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.595 ms/op
                 listUser·p0.50:   5.710 ms/op
                 listUser·p0.90:   8.684 ms/op
                 listUser·p0.95:   9.798 ms/op
                 listUser·p0.99:   13.108 ms/op
                 listUser·p0.999:  20.008 ms/op
                 listUser·p0.9999: 22.402 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 6.292 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.776 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   8.864 ms/op
                 listUser·p0.95:   10.043 ms/op
                 listUser·p0.99:   13.730 ms/op
                 listUser·p0.999:  21.406 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   27.951 ms/op

Iteration   3: 6.410 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   9.077 ms/op
                 listUser·p0.95:   10.551 ms/op
                 listUser·p0.99:   14.221 ms/op
                 listUser·p0.999:  25.428 ms/op
                 listUser·p0.9999: 39.518 ms/op
                 listUser·p1.00:   40.305 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 152253
  mean =      6.307 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 38753 
    [ 5.000, 10.000) = 105382 
    [10.000, 15.000) = 7091 
    [15.000, 20.000) = 769 
    [20.000, 25.000) = 178 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 22 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.559 ms/op
     p(50.0000) =      5.767 ms/op
     p(90.0000) =      8.864 ms/op
     p(95.0000) =     10.125 ms/op
     p(99.0000) =     13.779 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     35.381 ms/op
     p(99.9990) =     40.236 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.604 ± 3.905  ops/ms
ClientGrpc.existUser                       thrpt       3   6.923 ± 3.746  ops/ms
ClientGrpc.getUser                         thrpt       3   6.736 ± 1.114  ops/ms
ClientGrpc.listUser                        thrpt       3   4.943 ± 1.848  ops/ms
ClientGrpc.createUser                       avgt       3   5.085 ± 0.787   ms/op
ClientGrpc.existUser                        avgt       3   4.746 ± 2.657   ms/op
ClientGrpc.getUser                          avgt       3   4.778 ± 1.848   ms/op
ClientGrpc.listUser                         avgt       3   6.091 ± 0.342   ms/op
ClientGrpc.createUser                     sample  200302   4.792 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.022           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.144           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.012           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.781           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.576           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.427           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.525           ms/op
ClientGrpc.existUser                      sample  207206   4.633 ± 0.011   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.884           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.095           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           7.086           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.863           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          16.348           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.813           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.819           ms/op
ClientGrpc.getUser                        sample  200614   4.784 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.721           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.185           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.053           ms/op
ClientGrpc.getUser:getUser·p0.99          sample          10.027           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.426           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.888           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.149           ms/op
ClientGrpc.listUser                       sample  152253   6.307 ± 0.018   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.559           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.864           ms/op
ClientGrpc.listUser:listUser·p0.95        sample          10.125           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          13.779           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.184           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.381           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.305           ms/op
