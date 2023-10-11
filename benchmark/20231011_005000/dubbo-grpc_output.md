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
# Warmup Iteration   1: 4.196 ops/ms
# Warmup Iteration   2: 8.424 ops/ms
# Warmup Iteration   3: 9.447 ops/ms
Iteration   1: 9.931 ops/ms
Iteration   2: 10.335 ops/ms
Iteration   3: 10.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.228 ±(99.9%) 4.755 ops/ms [Average]
  (min, avg, max) = (9.931, 10.228, 10.418), stdev = 0.261
  CI (99.9%): [5.472, 14.983] (assumes normal distribution)


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
# Warmup Iteration   1: 7.099 ops/ms
# Warmup Iteration   2: 10.365 ops/ms
# Warmup Iteration   3: 10.493 ops/ms
Iteration   1: 10.752 ops/ms
Iteration   2: 10.569 ops/ms
Iteration   3: 10.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.691 ±(99.9%) 1.924 ops/ms [Average]
  (min, avg, max) = (10.569, 10.691, 10.752), stdev = 0.105
  CI (99.9%): [8.767, 12.614] (assumes normal distribution)


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
# Warmup Iteration   1: 6.519 ops/ms
# Warmup Iteration   2: 9.886 ops/ms
# Warmup Iteration   3: 10.097 ops/ms
Iteration   1: 10.144 ops/ms
Iteration   2: 10.219 ops/ms
Iteration   3: 10.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.179 ±(99.9%) 0.695 ops/ms [Average]
  (min, avg, max) = (10.144, 10.179, 10.219), stdev = 0.038
  CI (99.9%): [9.484, 10.874] (assumes normal distribution)


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
# Warmup Iteration   1: 5.303 ops/ms
# Warmup Iteration   2: 7.508 ops/ms
# Warmup Iteration   3: 7.983 ops/ms
Iteration   1: 8.044 ops/ms
Iteration   2: 7.953 ops/ms
Iteration   3: 8.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.002 ±(99.9%) 0.842 ops/ms [Average]
  (min, avg, max) = (7.953, 8.002, 8.044), stdev = 0.046
  CI (99.9%): [7.160, 8.844] (assumes normal distribution)


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.009 ms/op
Iteration   1: 3.157 ±(99.9%) 0.004 ms/op
Iteration   2: 3.135 ±(99.9%) 0.004 ms/op
Iteration   3: 3.094 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.129 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (3.094, 3.129, 3.157), stdev = 0.032
  CI (99.9%): [2.549, 3.708] (assumes normal distribution)


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.005 ms/op
Iteration   1: 2.964 ±(99.9%) 0.002 ms/op
Iteration   2: 2.957 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.972 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (2.957, 2.972, 2.996), stdev = 0.021
  CI (99.9%): [2.586, 3.359] (assumes normal distribution)


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
# Warmup Iteration   1: 4.655 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.006 ms/op
Iteration   1: 3.088 ±(99.9%) 0.002 ms/op
Iteration   2: 3.133 ±(99.9%) 0.003 ms/op
Iteration   3: 3.101 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.107 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (3.088, 3.107, 3.133), stdev = 0.023
  CI (99.9%): [2.686, 3.529] (assumes normal distribution)


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
# Warmup Iteration   1: 5.483 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
Iteration   1: 3.868 ±(99.9%) 0.014 ms/op
Iteration   2: 3.881 ±(99.9%) 0.026 ms/op
Iteration   3: 3.944 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.898 ±(99.9%) 0.739 ms/op [Average]
  (min, avg, max) = (3.868, 3.898, 3.944), stdev = 0.041
  CI (99.9%): [3.158, 4.637] (assumes normal distribution)


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
Iteration   1: 3.139 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  15.041 ms/op
                 createUser·p0.9999: 27.185 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.067 ms/op
                 createUser·p0.9999: 22.596 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.184 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  16.217 ms/op
                 createUser·p0.9999: 23.493 ms/op
                 createUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304368
  mean =      3.152 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13538 
    [ 2.500,  5.000) = 288196 
    [ 5.000,  7.500) = 2072 
    [ 7.500, 10.000) = 218 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =     10.758 ms/op
     p(99.9900) =     23.513 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.768 ms/op
                 existUser·p0.9999: 13.548 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 14.587 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   3: 3.048 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  12.911 ms/op
                 existUser·p0.9999: 21.316 ms/op
                 existUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316137
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23970 
    [ 2.500,  5.000) = 290128 
    [ 5.000,  7.500) = 1286 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =     10.732 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     21.654 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.006 ms/op
Iteration   1: 3.240 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.424 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.006 ms/op
                 getUser·p0.999:  12.304 ms/op
                 getUser·p0.9999: 19.530 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   2: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  7.870 ms/op
                 getUser·p0.9999: 14.615 ms/op
                 getUser·p1.00:   15.090 ms/op

Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 18.926 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303224
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9827 
    [ 2.500,  5.000) = 291198 
    [ 5.000,  7.500) = 1545 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     19.257 ms/op
     p(99.9990) =     21.264 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 5.694 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.012 ms/op
Iteration   1: 4.008 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.983 ms/op
                 listUser·p0.999:  14.404 ms/op
                 listUser·p0.9999: 16.319 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   2: 3.950 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.697 ms/op
                 listUser·p0.9999: 17.233 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.911 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.655 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  20.357 ms/op
                 listUser·p0.9999: 30.043 ms/op
                 listUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242603
  mean =      3.956 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1790 
    [ 2.500,  5.000) = 225649 
    [ 5.000,  7.500) = 13779 
    [ 7.500, 10.000) = 743 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     28.491 ms/op
     p(99.9990) =     30.212 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.228 ± 4.755  ops/ms
ClientGrpc.existUser                       thrpt       3  10.691 ± 1.924  ops/ms
ClientGrpc.getUser                         thrpt       3  10.179 ± 0.695  ops/ms
ClientGrpc.listUser                        thrpt       3   8.002 ± 0.842  ops/ms
ClientGrpc.createUser                       avgt       3   3.129 ± 0.580   ms/op
ClientGrpc.existUser                        avgt       3   2.972 ± 0.387   ms/op
ClientGrpc.getUser                          avgt       3   3.107 ± 0.422   ms/op
ClientGrpc.listUser                         avgt       3   3.898 ± 0.739   ms/op
ClientGrpc.createUser                     sample  304368   3.152 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.660           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.758           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.513           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.329           ms/op
ClientGrpc.existUser                      sample  316137   3.036 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.703           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.732           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.578           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.791           ms/op
ClientGrpc.getUser                        sample  303224   3.165 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.424           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.241           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.257           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.398           ms/op
ClientGrpc.listUser                       sample  242603   3.956 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.655           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.491           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.212           ms/op
