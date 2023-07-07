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
# Warmup Iteration   1: 2.169 ops/ms
# Warmup Iteration   2: 5.735 ops/ms
# Warmup Iteration   3: 7.396 ops/ms
Iteration   1: 8.206 ops/ms
Iteration   2: 7.858 ops/ms
Iteration   3: 7.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.007 ±(99.9%) 3.269 ops/ms [Average]
  (min, avg, max) = (7.858, 8.007, 8.206), stdev = 0.179
  CI (99.9%): [4.738, 11.276] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.994 ops/ms
# Warmup Iteration   2: 7.496 ops/ms
# Warmup Iteration   3: 8.749 ops/ms
Iteration   1: 8.761 ops/ms
Iteration   2: 8.575 ops/ms
Iteration   3: 8.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.552 ±(99.9%) 4.038 ops/ms [Average]
  (min, avg, max) = (8.320, 8.552, 8.761), stdev = 0.221
  CI (99.9%): [4.514, 12.591] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.147 ops/ms
# Warmup Iteration   2: 6.643 ops/ms
# Warmup Iteration   3: 7.374 ops/ms
Iteration   1: 7.812 ops/ms
Iteration   2: 7.911 ops/ms
Iteration   3: 7.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.893 ±(99.9%) 1.348 ops/ms [Average]
  (min, avg, max) = (7.812, 7.893, 7.957), stdev = 0.074
  CI (99.9%): [6.545, 9.242] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ops/ms
# Warmup Iteration   2: 5.617 ops/ms
# Warmup Iteration   3: 5.911 ops/ms
Iteration   1: 6.046 ops/ms
Iteration   2: 6.180 ops/ms
Iteration   3: 6.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.111 ±(99.9%) 1.220 ops/ms [Average]
  (min, avg, max) = (6.046, 6.111, 6.180), stdev = 0.067
  CI (99.9%): [4.891, 7.331] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.244 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.469 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.016 ms/op
Iteration   1: 4.152 ±(99.9%) 0.005 ms/op
Iteration   2: 4.063 ±(99.9%) 0.003 ms/op
Iteration   3: 4.067 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.094 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (4.063, 4.094, 4.152), stdev = 0.050
  CI (99.9%): [3.180, 5.008] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.059 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.005 ms/op
Iteration   1: 3.995 ±(99.9%) 0.003 ms/op
Iteration   2: 3.872 ±(99.9%) 0.002 ms/op
Iteration   3: 3.792 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.886 ±(99.9%) 1.868 ms/op [Average]
  (min, avg, max) = (3.792, 3.886, 3.995), stdev = 0.102
  CI (99.9%): [2.018, 5.754] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.265 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.003 ms/op
Iteration   1: 4.274 ±(99.9%) 0.005 ms/op
Iteration   2: 4.259 ±(99.9%) 0.003 ms/op
Iteration   3: 3.935 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.156 ±(99.9%) 3.492 ms/op [Average]
  (min, avg, max) = (3.935, 4.156, 4.274), stdev = 0.191
  CI (99.9%): [0.664, 7.648] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.937 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 6.080 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.732 ±(99.9%) 0.016 ms/op
Iteration   1: 5.424 ±(99.9%) 0.021 ms/op
Iteration   2: 5.327 ±(99.9%) 0.013 ms/op
Iteration   3: 5.591 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.447 ±(99.9%) 2.437 ms/op [Average]
  (min, avg, max) = (5.327, 5.447, 5.591), stdev = 0.134
  CI (99.9%): [3.010, 7.884] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.395 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.561 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.013 ms/op
Iteration   1: 3.967 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  12.972 ms/op
                 createUser·p0.9999: 18.350 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   2: 3.794 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.462 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  10.129 ms/op
                 createUser·p0.9999: 19.089 ms/op
                 createUser·p1.00:   19.595 ms/op

Iteration   3: 3.788 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  19.394 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 249538
  mean =      3.848 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7009 
    [ 2.500,  5.000) = 224977 
    [ 5.000,  7.500) = 15889 
    [ 7.500, 10.000) = 1111 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     22.648 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.431 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.012 ms/op
Iteration   1: 3.851 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  11.271 ms/op
                 existUser·p0.9999: 15.134 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   2: 3.884 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   6.789 ms/op
                 existUser·p0.999:  11.966 ms/op
                 existUser·p0.9999: 18.670 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   3: 3.832 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.776 ms/op
                 existUser·p0.95:   5.243 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  12.772 ms/op
                 existUser·p0.9999: 35.760 ms/op
                 existUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 248847
  mean =      3.856 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9321 
    [ 2.500,  5.000) = 222194 
    [ 5.000,  7.500) = 15813 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     12.141 ms/op
     p(99.9900) =     34.676 ms/op
     p(99.9990) =     36.144 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.034 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.465 ±(99.9%) 0.016 ms/op
Iteration   1: 4.470 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.890 ms/op
                 getUser·p0.95:   6.881 ms/op
                 getUser·p0.99:   10.207 ms/op
                 getUser·p0.999:  15.244 ms/op
                 getUser·p0.9999: 19.542 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   2: 4.642 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   6.365 ms/op
                 getUser·p0.95:   7.643 ms/op
                 getUser·p0.99:   11.469 ms/op
                 getUser·p0.999:  17.889 ms/op
                 getUser·p0.9999: 19.923 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   3: 4.263 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   4.133 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   8.200 ms/op
                 getUser·p0.999:  12.452 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215593
  mean =      4.453 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7117 
    [ 2.500,  5.000) = 161009 
    [ 5.000,  7.500) = 40078 
    [ 7.500, 10.000) = 5118 
    [10.000, 12.500) = 1476 
    [12.500, 15.000) = 543 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =     10.126 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     21.451 ms/op
     p(99.9990) =     25.839 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 9.413 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 6.017 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.345 ±(99.9%) 0.022 ms/op
Iteration   1: 5.567 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   5.214 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  21.725 ms/op
                 listUser·p0.9999: 24.282 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   2: 5.485 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   7.447 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   11.534 ms/op
                 listUser·p0.999:  25.330 ms/op
                 listUser·p0.9999: 33.473 ms/op
                 listUser·p1.00:   33.817 ms/op

Iteration   3: 5.476 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.348 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  24.236 ms/op
                 listUser·p0.9999: 35.280 ms/op
                 listUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174181
  mean =      5.509 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 318 
    [ 2.500,  5.000) = 75274 
    [ 5.000,  7.500) = 82109 
    [ 7.500, 10.000) = 13238 
    [10.000, 12.500) = 2135 
    [12.500, 15.000) = 596 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      7.414 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.174 ms/op
     p(99.9000) =     23.069 ms/op
     p(99.9900) =     34.772 ms/op
     p(99.9990) =     36.015 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.007 ± 3.269  ops/ms
ClientGrpc.existUser                       thrpt       3   8.552 ± 4.038  ops/ms
ClientGrpc.getUser                         thrpt       3   7.893 ± 1.348  ops/ms
ClientGrpc.listUser                        thrpt       3   6.111 ± 1.220  ops/ms
ClientGrpc.createUser                       avgt       3   4.094 ± 0.914   ms/op
ClientGrpc.existUser                        avgt       3   3.886 ± 1.868   ms/op
ClientGrpc.getUser                          avgt       3   4.156 ± 3.492   ms/op
ClientGrpc.listUser                         avgt       3   5.447 ± 2.437   ms/op
ClientGrpc.createUser                     sample  249538   3.848 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.462           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.226           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.881           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.730           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.004           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.214           ms/op
ClientGrpc.existUser                      sample  248847   3.856 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.824           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.784           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.218           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.832           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.141           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          34.676           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.307           ms/op
ClientGrpc.getUser                        sample  215593   4.453 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.726           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.833           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.824           ms/op
ClientGrpc.getUser:getUser·p0.99          sample          10.126           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.286           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.451           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.952           ms/op
ClientGrpc.listUser                       sample  174181   5.509 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.798           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.438           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.174           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          23.069           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.772           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.307           ms/op
