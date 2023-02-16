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
# Warmup Iteration   1: 2.476 ops/ms
# Warmup Iteration   2: 5.942 ops/ms
# Warmup Iteration   3: 7.320 ops/ms
Iteration   1: 7.307 ops/ms
Iteration   2: 7.239 ops/ms
Iteration   3: 6.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.153 ±(99.9%) 3.855 ops/ms [Average]
  (min, avg, max) = (6.912, 7.153, 7.307), stdev = 0.211
  CI (99.9%): [3.297, 11.008] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.751 ops/ms
# Warmup Iteration   2: 6.939 ops/ms
# Warmup Iteration   3: 7.661 ops/ms
Iteration   1: 7.588 ops/ms
Iteration   2: 7.622 ops/ms
Iteration   3: 7.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.633 ±(99.9%) 0.925 ops/ms [Average]
  (min, avg, max) = (7.588, 7.633, 7.688), stdev = 0.051
  CI (99.9%): [6.708, 8.557] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.152 ops/ms
# Warmup Iteration   2: 7.008 ops/ms
# Warmup Iteration   3: 7.191 ops/ms
Iteration   1: 7.003 ops/ms
Iteration   2: 6.989 ops/ms
Iteration   3: 6.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.984 ±(99.9%) 0.413 ops/ms [Average]
  (min, avg, max) = (6.959, 6.984, 7.003), stdev = 0.023
  CI (99.9%): [6.571, 7.397] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.991 ops/ms
# Warmup Iteration   2: 5.255 ops/ms
# Warmup Iteration   3: 5.741 ops/ms
Iteration   1: 5.636 ops/ms
Iteration   2: 5.957 ops/ms
Iteration   3: 5.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.799 ±(99.9%) 2.930 ops/ms [Average]
  (min, avg, max) = (5.636, 5.799, 5.957), stdev = 0.161
  CI (99.9%): [2.869, 8.729] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.950 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.500 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.672 ±(99.9%) 0.003 ms/op
Iteration   1: 4.534 ±(99.9%) 0.004 ms/op
Iteration   2: 4.428 ±(99.9%) 0.003 ms/op
Iteration   3: 4.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.473 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (4.428, 4.473, 4.534), stdev = 0.054
  CI (99.9%): [3.481, 5.465] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.982 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.698 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.445 ±(99.9%) 0.007 ms/op
Iteration   1: 4.294 ±(99.9%) 0.004 ms/op
Iteration   2: 4.416 ±(99.9%) 0.003 ms/op
Iteration   3: 4.100 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.270 ±(99.9%) 2.905 ms/op [Average]
  (min, avg, max) = (4.100, 4.270, 4.416), stdev = 0.159
  CI (99.9%): [1.365, 7.175] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.457 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.855 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.629 ±(99.9%) 0.008 ms/op
Iteration   1: 4.538 ±(99.9%) 0.004 ms/op
Iteration   2: 4.540 ±(99.9%) 0.005 ms/op
Iteration   3: 4.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.529 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (4.510, 4.529, 4.540), stdev = 0.017
  CI (99.9%): [4.224, 4.834] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.114 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.799 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.489 ±(99.9%) 0.017 ms/op
Iteration   1: 5.614 ±(99.9%) 0.015 ms/op
Iteration   2: 5.538 ±(99.9%) 0.013 ms/op
Iteration   3: 5.241 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.464 ±(99.9%) 3.596 ms/op [Average]
  (min, avg, max) = (5.241, 5.464, 5.614), stdev = 0.197
  CI (99.9%): [1.868, 9.060] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.608 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.562 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.343 ±(99.9%) 0.014 ms/op
Iteration   1: 4.500 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.185 ms/op
                 createUser·p0.99:   8.805 ms/op
                 createUser·p0.999:  13.599 ms/op
                 createUser·p0.9999: 20.575 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   2: 4.475 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.661 ms/op
                 createUser·p0.95:   6.084 ms/op
                 createUser·p0.99:   7.939 ms/op
                 createUser·p0.999:  14.394 ms/op
                 createUser·p0.9999: 20.934 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   3: 4.570 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.931 ms/op
                 createUser·p0.95:   6.783 ms/op
                 createUser·p0.99:   10.011 ms/op
                 createUser·p0.999:  18.482 ms/op
                 createUser·p0.9999: 28.836 ms/op
                 createUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 212635
  mean =      4.515 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4231 
    [ 2.500,  5.000) = 152989 
    [ 5.000,  7.500) = 50940 
    [ 7.500, 10.000) = 3097 
    [10.000, 12.500) = 862 
    [12.500, 15.000) = 300 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.734 ms/op
     p(95.0000) =      6.316 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     15.063 ms/op
     p(99.9900) =     28.187 ms/op
     p(99.9990) =     29.180 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.704 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.013 ms/op
Iteration   1: 4.157 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   4.100 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   5.743 ms/op
                 existUser·p0.99:   7.307 ms/op
                 existUser·p0.999:  13.158 ms/op
                 existUser·p0.9999: 16.666 ms/op
                 existUser·p1.00:   17.007 ms/op

Iteration   2: 4.125 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.702 ms/op
                 existUser·p0.99:   7.373 ms/op
                 existUser·p0.999:  13.198 ms/op
                 existUser·p0.9999: 28.803 ms/op
                 existUser·p1.00:   29.983 ms/op

Iteration   3: 4.244 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   4.092 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   8.200 ms/op
                 existUser·p0.999:  12.304 ms/op
                 existUser·p0.9999: 19.202 ms/op
                 existUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229761
  mean =      4.175 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10447 
    [ 2.500,  5.000) = 182663 
    [ 5.000,  7.500) = 34205 
    [ 7.500, 10.000) = 1804 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     13.046 ms/op
     p(99.9900) =     28.214 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.199 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.750 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.981 ±(99.9%) 0.019 ms/op
Iteration   1: 4.604 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   4.481 ms/op
                 getUser·p0.90:   5.865 ms/op
                 getUser·p0.95:   6.365 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  14.587 ms/op
                 getUser·p0.9999: 17.764 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   2: 4.606 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   6.332 ms/op
                 getUser·p0.99:   8.135 ms/op
                 getUser·p0.999:  13.124 ms/op
                 getUser·p0.9999: 19.435 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   3: 4.525 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.816 ms/op
                 getUser·p0.95:   6.439 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  16.366 ms/op
                 getUser·p0.9999: 21.393 ms/op
                 getUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 209540
  mean =      4.578 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4603 
    [ 2.500,  5.000) = 141977 
    [ 5.000,  7.500) = 59193 
    [ 7.500, 10.000) = 2964 
    [10.000, 12.500) = 476 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.373 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     14.892 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     21.650 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 8.139 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.294 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.522 ±(99.9%) 0.020 ms/op
Iteration   1: 5.755 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.013 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.823 ms/op
                 listUser·p0.95:   8.929 ms/op
                 listUser·p0.99:   12.065 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 22.140 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 5.742 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   7.864 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   12.108 ms/op
                 listUser·p0.999:  17.713 ms/op
                 listUser·p0.9999: 26.022 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   3: 5.652 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.639 ms/op
                 listUser·p0.999:  24.107 ms/op
                 listUser·p0.9999: 29.262 ms/op
                 listUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167944
  mean =      5.716 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 62346 
    [ 5.000,  7.500) = 86045 
    [ 7.500, 10.000) = 15217 
    [10.000, 12.500) = 2912 
    [12.500, 15.000) = 834 
    [15.000, 17.500) = 255 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      7.717 ms/op
     p(95.0000) =      8.815 ms/op
     p(99.0000) =     11.960 ms/op
     p(99.9000) =     18.776 ms/op
     p(99.9900) =     28.528 ms/op
     p(99.9990) =     29.511 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.153 ± 3.855  ops/ms
ClientGrpc.existUser                       thrpt       3   7.633 ± 0.925  ops/ms
ClientGrpc.getUser                         thrpt       3   6.984 ± 0.413  ops/ms
ClientGrpc.listUser                        thrpt       3   5.799 ± 2.930  ops/ms
ClientGrpc.createUser                       avgt       3   4.473 ± 0.992   ms/op
ClientGrpc.existUser                        avgt       3   4.270 ± 2.905   ms/op
ClientGrpc.getUser                          avgt       3   4.529 ± 0.305   ms/op
ClientGrpc.listUser                         avgt       3   5.464 ± 3.596   ms/op
ClientGrpc.createUser                     sample  212635   4.515 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.748           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.734           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.316           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.946           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.063           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.187           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.327           ms/op
ClientGrpc.existUser                      sample  229761   4.175 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.943           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.084           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.800           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.586           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.046           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.214           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.983           ms/op
ClientGrpc.getUser                        sample  209540   4.578 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.839           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.857           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.373           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.405           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.892           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.709           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.758           ms/op
ClientGrpc.listUser                       sample  167944   5.716 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.339           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.717           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.815           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.960           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.776           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.528           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.622           ms/op
