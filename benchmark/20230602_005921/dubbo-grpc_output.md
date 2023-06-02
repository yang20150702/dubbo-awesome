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
# Warmup Iteration   1: 3.498 ops/ms
# Warmup Iteration   2: 7.875 ops/ms
# Warmup Iteration   3: 8.766 ops/ms
Iteration   1: 9.205 ops/ms
Iteration   2: 9.452 ops/ms
Iteration   3: 9.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.302 ±(99.9%) 2.398 ops/ms [Average]
  (min, avg, max) = (9.205, 9.302, 9.452), stdev = 0.131
  CI (99.9%): [6.905, 11.700] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.963 ops/ms
# Warmup Iteration   2: 8.865 ops/ms
# Warmup Iteration   3: 9.431 ops/ms
Iteration   1: 9.691 ops/ms
Iteration   2: 9.266 ops/ms
Iteration   3: 9.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.487 ±(99.9%) 3.883 ops/ms [Average]
  (min, avg, max) = (9.266, 9.487, 9.691), stdev = 0.213
  CI (99.9%): [5.605, 13.370] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.751 ops/ms
# Warmup Iteration   2: 8.769 ops/ms
# Warmup Iteration   3: 8.940 ops/ms
Iteration   1: 9.084 ops/ms
Iteration   2: 8.939 ops/ms
Iteration   3: 9.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.084 ±(99.9%) 2.623 ops/ms [Average]
  (min, avg, max) = (8.939, 9.084, 9.227), stdev = 0.144
  CI (99.9%): [6.461, 11.707] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.597 ops/ms
# Warmup Iteration   2: 6.821 ops/ms
# Warmup Iteration   3: 7.195 ops/ms
Iteration   1: 7.445 ops/ms
Iteration   2: 7.167 ops/ms
Iteration   3: 7.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.291 ±(99.9%) 2.578 ops/ms [Average]
  (min, avg, max) = (7.167, 7.291, 7.445), stdev = 0.141
  CI (99.9%): [4.713, 9.869] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 4.885 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.002 ms/op
Iteration   1: 3.501 ±(99.9%) 0.003 ms/op
Iteration   2: 3.333 ±(99.9%) 0.003 ms/op
Iteration   3: 3.371 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.402 ±(99.9%) 1.615 ms/op [Average]
  (min, avg, max) = (3.333, 3.402, 3.501), stdev = 0.089
  CI (99.9%): [1.786, 5.017] (assumes normal distribution)


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
# Warmup Iteration   1: 4.831 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.003 ms/op
Iteration   1: 3.341 ±(99.9%) 0.003 ms/op
Iteration   2: 3.290 ±(99.9%) 0.002 ms/op
Iteration   3: 3.299 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.310 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (3.290, 3.310, 3.341), stdev = 0.027
  CI (99.9%): [2.812, 3.808] (assumes normal distribution)


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
# Warmup Iteration   1: 5.143 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.003 ms/op
Iteration   1: 3.491 ±(99.9%) 0.003 ms/op
Iteration   2: 3.466 ±(99.9%) 0.002 ms/op
Iteration   3: 3.513 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.490 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (3.466, 3.490, 3.513), stdev = 0.024
  CI (99.9%): [3.054, 3.927] (assumes normal distribution)


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
# Warmup Iteration   1: 6.071 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.630 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.436 ±(99.9%) 0.012 ms/op
Iteration   1: 4.422 ±(99.9%) 0.020 ms/op
Iteration   2: 4.354 ±(99.9%) 0.011 ms/op
Iteration   3: 4.410 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.395 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (4.354, 4.395, 4.422), stdev = 0.036
  CI (99.9%): [3.738, 5.053] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.033 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.010 ms/op
Iteration   1: 3.579 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 21.174 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   2: 3.534 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.497 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  11.652 ms/op
                 createUser·p0.9999: 24.014 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   3: 3.493 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  20.054 ms/op
                 createUser·p0.9999: 28.758 ms/op
                 createUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271825
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10412 
    [ 2.500,  5.000) = 254087 
    [ 5.000,  7.500) = 6474 
    [ 7.500, 10.000) = 590 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =      9.915 ms/op
     p(99.9900) =     27.617 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 5.046 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.008 ms/op
Iteration   1: 3.263 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  11.452 ms/op
                 existUser·p0.9999: 15.788 ms/op
                 existUser·p1.00:   16.204 ms/op

Iteration   2: 3.319 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  8.937 ms/op
                 existUser·p0.9999: 20.449 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   3: 3.354 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  10.846 ms/op
                 existUser·p0.9999: 21.592 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 289869
  mean =      3.311 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15518 
    [ 2.500,  5.000) = 270125 
    [ 5.000,  7.500) = 3612 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     10.420 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     21.961 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 4.955 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.007 ms/op
Iteration   1: 3.487 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  11.034 ms/op
                 getUser·p0.9999: 27.028 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   2: 3.446 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  10.962 ms/op
                 getUser·p0.9999: 32.440 ms/op
                 getUser·p1.00:   33.128 ms/op

Iteration   3: 3.461 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  9.611 ms/op
                 getUser·p0.9999: 21.856 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 277089
  mean =      3.465 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13206 
    [ 2.500,  5.000) = 258688 
    [ 5.000,  7.500) = 4424 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     10.042 ms/op
     p(99.9900) =     31.631 ms/op
     p(99.9990) =     32.995 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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
# Warmup Iteration   1: 6.925 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.647 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.523 ±(99.9%) 0.016 ms/op
Iteration   1: 4.557 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   6.300 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 21.035 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   2: 4.720 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.370 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   6.423 ms/op
                 listUser·p0.95:   7.078 ms/op
                 listUser·p0.99:   8.691 ms/op
                 listUser·p0.999:  21.782 ms/op
                 listUser·p0.9999: 24.846 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   3: 4.628 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  23.917 ms/op
                 listUser·p0.9999: 26.259 ms/op
                 listUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207013
  mean =      4.634 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2053 
    [ 2.500,  5.000) = 151321 
    [ 5.000,  7.500) = 47178 
    [ 7.500, 10.000) = 5385 
    [10.000, 12.500) = 566 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      6.291 ms/op
     p(95.0000) =      7.053 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     26.800 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.302 ± 2.398  ops/ms
ClientGrpc.existUser                       thrpt       3   9.487 ± 3.883  ops/ms
ClientGrpc.getUser                         thrpt       3   9.084 ± 2.623  ops/ms
ClientGrpc.listUser                        thrpt       3   7.291 ± 2.578  ops/ms
ClientGrpc.createUser                       avgt       3   3.402 ± 1.615   ms/op
ClientGrpc.existUser                        avgt       3   3.310 ± 0.498   ms/op
ClientGrpc.getUser                          avgt       3   3.490 ± 0.436   ms/op
ClientGrpc.listUser                         avgt       3   4.395 ± 0.658   ms/op
ClientGrpc.createUser                     sample  271825   3.535 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.497           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.457           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.874           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.915           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.617           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.196           ms/op
ClientGrpc.existUser                      sample  289869   3.311 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.896           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.260           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.949           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.333           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.420           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.939           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.086           ms/op
ClientGrpc.getUser                        sample  277089   3.465 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.669           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.420           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.149           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.546           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.042           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.631           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.128           ms/op
ClientGrpc.listUser                       sample  207013   4.634 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.370           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.366           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.291           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.782           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.185           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.264           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.837           ms/op
