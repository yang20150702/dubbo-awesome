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
# Warmup Iteration   1: 2.484 ops/ms
# Warmup Iteration   2: 5.776 ops/ms
# Warmup Iteration   3: 7.356 ops/ms
Iteration   1: 7.570 ops/ms
Iteration   2: 7.650 ops/ms
Iteration   3: 7.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.656 ±(99.9%) 1.616 ops/ms [Average]
  (min, avg, max) = (7.570, 7.656, 7.747), stdev = 0.089
  CI (99.9%): [6.040, 9.271] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.932 ops/ms
# Warmup Iteration   2: 7.611 ops/ms
# Warmup Iteration   3: 8.258 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 8.692 ops/ms
Iteration   3: 7.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.282 ±(99.9%) 6.655 ops/ms [Average]
  (min, avg, max) = (7.993, 8.282, 8.692), stdev = 0.365
  CI (99.9%): [1.627, 14.938] (assumes normal distribution)


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
# Warmup Iteration   1: 4.543 ops/ms
# Warmup Iteration   2: 7.161 ops/ms
# Warmup Iteration   3: 7.615 ops/ms
Iteration   1: 7.816 ops/ms
Iteration   2: 7.877 ops/ms
Iteration   3: 7.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.834 ±(99.9%) 0.679 ops/ms [Average]
  (min, avg, max) = (7.810, 7.834, 7.877), stdev = 0.037
  CI (99.9%): [7.156, 8.513] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ops/ms
# Warmup Iteration   2: 5.375 ops/ms
# Warmup Iteration   3: 5.955 ops/ms
Iteration   1: 5.932 ops/ms
Iteration   2: 5.909 ops/ms
Iteration   3: 5.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.920 ±(99.9%) 0.212 ops/ms [Average]
  (min, avg, max) = (5.909, 5.920, 5.932), stdev = 0.012
  CI (99.9%): [5.708, 6.133] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.192 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.274 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.011 ms/op
Iteration   1: 4.125 ±(99.9%) 0.003 ms/op
Iteration   2: 4.092 ±(99.9%) 0.006 ms/op
Iteration   3: 4.194 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.137 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (4.092, 4.137, 4.194), stdev = 0.052
  CI (99.9%): [3.184, 5.089] (assumes normal distribution)


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
# Warmup Iteration   1: 6.244 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.389 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.003 ms/op
Iteration   1: 3.795 ±(99.9%) 0.002 ms/op
Iteration   2: 3.972 ±(99.9%) 0.003 ms/op
Iteration   3: 3.747 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.838 ±(99.9%) 2.166 ms/op [Average]
  (min, avg, max) = (3.747, 3.838, 3.972), stdev = 0.119
  CI (99.9%): [1.672, 6.004] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.301 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.344 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.005 ms/op
Iteration   1: 4.173 ±(99.9%) 0.005 ms/op
Iteration   2: 4.131 ±(99.9%) 0.004 ms/op
Iteration   3: 4.194 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.166 ±(99.9%) 0.583 ms/op [Average]
  (min, avg, max) = (4.131, 4.166, 4.194), stdev = 0.032
  CI (99.9%): [3.583, 4.749] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.537 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.938 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.433 ±(99.9%) 0.014 ms/op
Iteration   1: 5.129 ±(99.9%) 0.025 ms/op
Iteration   2: 5.201 ±(99.9%) 0.014 ms/op
Iteration   3: 5.360 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.230 ±(99.9%) 2.163 ms/op [Average]
  (min, avg, max) = (5.129, 5.230, 5.360), stdev = 0.119
  CI (99.9%): [3.067, 7.393] (assumes normal distribution)


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
# Warmup Iteration   1: 6.348 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.725 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.455 ±(99.9%) 0.013 ms/op
Iteration   1: 4.166 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.397 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   5.177 ms/op
                 createUser·p0.95:   5.620 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  14.879 ms/op
                 createUser·p0.9999: 26.147 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   2: 4.258 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   4.149 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   6.717 ms/op
                 createUser·p0.999:  12.009 ms/op
                 createUser·p0.9999: 30.445 ms/op
                 createUser·p1.00:   32.735 ms/op

Iteration   3: 4.177 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   4.088 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   6.816 ms/op
                 createUser·p0.999:  13.933 ms/op
                 createUser·p0.9999: 29.994 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 228553
  mean =      4.200 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3841 
    [ 2.500,  5.000) = 192431 
    [ 5.000,  7.500) = 30703 
    [ 7.500, 10.000) = 959 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.744 ms/op
     p(99.9900) =     29.758 ms/op
     p(99.9990) =     32.642 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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
# Warmup Iteration   1: 5.503 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.518 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.010 ms/op
Iteration   1: 3.949 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  10.404 ms/op
                 existUser·p0.9999: 18.380 ms/op
                 existUser·p1.00:   18.776 ms/op

Iteration   2: 3.931 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  12.414 ms/op
                 existUser·p0.9999: 18.805 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   3: 3.911 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.366 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 22.271 ms/op
                 existUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 244006
  mean =      3.930 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7571 
    [ 2.500,  5.000) = 215010 
    [ 5.000,  7.500) = 20315 
    [ 7.500, 10.000) = 705 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     22.712 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 5.919 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.010 ms/op
Iteration   1: 4.095 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  12.845 ms/op
                 getUser·p0.9999: 21.466 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 4.049 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.964 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  9.815 ms/op
                 getUser·p0.9999: 21.237 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   3: 4.073 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   5.087 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  10.324 ms/op
                 getUser·p0.9999: 22.789 ms/op
                 getUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235539
  mean =      4.072 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4526 
    [ 2.500,  5.000) = 206254 
    [ 5.000,  7.500) = 23555 
    [ 7.500, 10.000) = 891 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     11.091 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     23.155 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 8.659 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.632 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.344 ±(99.9%) 0.019 ms/op
Iteration   1: 5.103 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   6.472 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  16.504 ms/op
                 listUser·p0.9999: 23.403 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 5.358 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.913 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   6.783 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  16.766 ms/op
                 listUser·p0.9999: 21.670 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   3: 5.274 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   10.222 ms/op
                 listUser·p0.999:  19.680 ms/op
                 listUser·p0.9999: 26.041 ms/op
                 listUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 183062
  mean =      5.243 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 159 
    [ 2.500,  5.000) = 93399 
    [ 5.000,  7.500) = 78196 
    [ 7.500, 10.000) = 9542 
    [10.000, 12.500) = 1144 
    [12.500, 15.000) = 321 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      4.981 ms/op
     p(90.0000) =      6.750 ms/op
     p(95.0000) =      7.782 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.656 ± 1.616  ops/ms
ClientGrpc.existUser                       thrpt       3   8.282 ± 6.655  ops/ms
ClientGrpc.getUser                         thrpt       3   7.834 ± 0.679  ops/ms
ClientGrpc.listUser                        thrpt       3   5.920 ± 0.212  ops/ms
ClientGrpc.createUser                       avgt       3   4.137 ± 0.953   ms/op
ClientGrpc.existUser                        avgt       3   3.838 ± 2.166   ms/op
ClientGrpc.getUser                          avgt       3   4.166 ± 0.583   ms/op
ClientGrpc.listUser                         avgt       3   5.230 ± 2.163   ms/op
ClientGrpc.createUser                     sample  228553   4.200 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.397           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.100           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.202           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.889           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.744           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.758           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.735           ms/op
ClientGrpc.existUser                      sample  244006   3.930 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.819           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.923           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.349           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.504           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.436           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.300           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.807           ms/op
ClientGrpc.getUser                        sample  235539   4.072 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.530           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.030           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.448           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.644           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.091           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.627           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.855           ms/op
ClientGrpc.listUser                       sample  183062   5.243 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.075           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.782           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.929           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.367           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.773           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.673           ms/op
