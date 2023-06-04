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
# Warmup Iteration   1: 1.975 ops/ms
# Warmup Iteration   2: 5.035 ops/ms
# Warmup Iteration   3: 6.888 ops/ms
Iteration   1: 7.027 ops/ms
Iteration   2: 7.092 ops/ms
Iteration   3: 7.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.088 ±(99.9%) 1.076 ops/ms [Average]
  (min, avg, max) = (7.027, 7.088, 7.145), stdev = 0.059
  CI (99.9%): [6.012, 8.164] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.492 ops/ms
# Warmup Iteration   2: 7.014 ops/ms
# Warmup Iteration   3: 7.619 ops/ms
Iteration   1: 7.410 ops/ms
Iteration   2: 7.506 ops/ms
Iteration   3: 7.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.464 ±(99.9%) 0.900 ops/ms [Average]
  (min, avg, max) = (7.410, 7.464, 7.506), stdev = 0.049
  CI (99.9%): [6.565, 8.364] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.285 ops/ms
# Warmup Iteration   2: 6.529 ops/ms
# Warmup Iteration   3: 7.102 ops/ms
Iteration   1: 7.103 ops/ms
Iteration   2: 7.125 ops/ms
Iteration   3: 7.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.152 ±(99.9%) 1.213 ops/ms [Average]
  (min, avg, max) = (7.103, 7.152, 7.227), stdev = 0.066
  CI (99.9%): [5.939, 8.365] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ops/ms
# Warmup Iteration   2: 4.944 ops/ms
# Warmup Iteration   3: 5.345 ops/ms
Iteration   1: 5.422 ops/ms
Iteration   2: 5.404 ops/ms
Iteration   3: 5.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.546 ±(99.9%) 4.192 ops/ms [Average]
  (min, avg, max) = (5.404, 5.546, 5.811), stdev = 0.230
  CI (99.9%): [1.354, 9.738] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.010 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.683 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.442 ±(99.9%) 0.005 ms/op
Iteration   1: 4.481 ±(99.9%) 0.003 ms/op
Iteration   2: 4.447 ±(99.9%) 0.002 ms/op
Iteration   3: 4.457 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.462 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (4.447, 4.462, 4.481), stdev = 0.017
  CI (99.9%): [4.149, 4.774] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.779 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.461 ±(99.9%) 0.003 ms/op
Iteration   1: 4.396 ±(99.9%) 0.004 ms/op
Iteration   2: 4.485 ±(99.9%) 0.002 ms/op
Iteration   3: 4.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.463 ±(99.9%) 1.067 ms/op [Average]
  (min, avg, max) = (4.396, 4.463, 4.507), stdev = 0.058
  CI (99.9%): [3.396, 5.529] (assumes normal distribution)


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
# Warmup Iteration   1: 6.409 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.960 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.764 ±(99.9%) 0.019 ms/op
Iteration   1: 4.706 ±(99.9%) 0.004 ms/op
Iteration   2: 4.577 ±(99.9%) 0.003 ms/op
Iteration   3: 4.594 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.626 ±(99.9%) 1.274 ms/op [Average]
  (min, avg, max) = (4.577, 4.626, 4.706), stdev = 0.070
  CI (99.9%): [3.351, 5.900] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.563 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 6.507 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 6.092 ±(99.9%) 0.013 ms/op
Iteration   1: 5.907 ±(99.9%) 0.017 ms/op
Iteration   2: 5.936 ±(99.9%) 0.022 ms/op
Iteration   3: 5.994 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.946 ±(99.9%) 0.806 ms/op [Average]
  (min, avg, max) = (5.907, 5.946, 5.994), stdev = 0.044
  CI (99.9%): [5.140, 6.752] (assumes normal distribution)


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
# Warmup Iteration   1: 7.147 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.902 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.646 ±(99.9%) 0.014 ms/op
Iteration   1: 4.590 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   4.465 ms/op
                 createUser·p0.90:   5.652 ms/op
                 createUser·p0.95:   6.070 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  10.448 ms/op
                 createUser·p0.9999: 19.566 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   2: 4.502 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   7.545 ms/op
                 createUser·p0.999:  14.221 ms/op
                 createUser·p0.9999: 19.231 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 4.544 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.497 ms/op
                 createUser·p0.95:   5.861 ms/op
                 createUser·p0.99:   7.252 ms/op
                 createUser·p0.999:  14.074 ms/op
                 createUser·p0.9999: 19.951 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 211172
  mean =      4.545 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1149 
    [ 2.500,  5.000) = 162074 
    [ 5.000,  7.500) = 46100 
    [ 7.500, 10.000) = 1411 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     13.672 ms/op
     p(99.9900) =     19.817 ms/op
     p(99.9990) =     20.797 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 6.451 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.464 ±(99.9%) 0.011 ms/op
Iteration   1: 4.419 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   4.284 ms/op
                 existUser·p0.90:   5.480 ms/op
                 existUser·p0.95:   5.915 ms/op
                 existUser·p0.99:   7.400 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 20.916 ms/op
                 existUser·p1.00:   21.365 ms/op

Iteration   2: 4.269 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   4.170 ms/op
                 existUser·p0.90:   5.071 ms/op
                 existUser·p0.95:   5.489 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  12.830 ms/op
                 existUser·p0.9999: 17.793 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 4.410 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   4.284 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  13.678 ms/op
                 existUser·p0.9999: 37.487 ms/op
                 existUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 219835
  mean =      4.365 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1889 
    [ 2.500,  5.000) = 180595 
    [ 5.000,  7.500) = 35548 
    [ 7.500, 10.000) = 1313 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     12.673 ms/op
     p(99.9900) =     36.767 ms/op
     p(99.9990) =     37.723 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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
# Warmup Iteration   1: 7.310 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.211 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.691 ±(99.9%) 0.014 ms/op
Iteration   1: 4.630 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   7.594 ms/op
                 getUser·p0.999:  12.071 ms/op
                 getUser·p0.9999: 15.188 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   2: 4.586 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  10.751 ms/op
                 getUser·p0.9999: 19.760 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   3: 4.679 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   5.693 ms/op
                 getUser·p0.95:   6.136 ms/op
                 getUser·p0.99:   7.700 ms/op
                 getUser·p0.999:  13.124 ms/op
                 getUser·p0.9999: 21.545 ms/op
                 getUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 207191
  mean =      4.631 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1738 
    [ 2.500,  5.000) = 147903 
    [ 5.000,  7.500) = 55428 
    [ 7.500, 10.000) = 1688 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     12.259 ms/op
     p(99.9900) =     19.539 ms/op
     p(99.9990) =     22.144 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 9.410 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 6.171 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.932 ±(99.9%) 0.022 ms/op
Iteration   1: 5.825 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.073 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.870 ms/op
                 listUser·p0.999:  18.225 ms/op
                 listUser·p0.9999: 25.314 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   2: 5.931 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   7.782 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.174 ms/op
                 listUser·p0.999:  18.945 ms/op
                 listUser·p0.9999: 20.979 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 5.776 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   8.159 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  23.487 ms/op
                 listUser·p0.9999: 27.996 ms/op
                 listUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 164334
  mean =      5.843 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 39913 
    [ 5.000,  7.500) = 107851 
    [ 7.500, 10.000) = 13665 
    [10.000, 12.500) = 2206 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =      7.504 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     25.465 ms/op
     p(99.9990) =     28.403 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.088 ± 1.076  ops/ms
ClientGrpc.existUser                       thrpt       3   7.464 ± 0.900  ops/ms
ClientGrpc.getUser                         thrpt       3   7.152 ± 1.213  ops/ms
ClientGrpc.listUser                        thrpt       3   5.546 ± 4.192  ops/ms
ClientGrpc.createUser                       avgt       3   4.462 ± 0.313   ms/op
ClientGrpc.existUser                        avgt       3   4.463 ± 1.067   ms/op
ClientGrpc.getUser                          avgt       3   4.626 ± 1.274   ms/op
ClientGrpc.listUser                         avgt       3   5.946 ± 0.806   ms/op
ClientGrpc.createUser                     sample  211172   4.545 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.329           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.530           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.980           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.340           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.672           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.817           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.873           ms/op
ClientGrpc.existUser                      sample  219835   4.365 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.834           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.349           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.759           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.160           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.673           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          36.767           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          37.814           ms/op
ClientGrpc.getUser                        sample  207191   4.631 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.075           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.693           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.119           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.528           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.259           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.539           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.249           ms/op
ClientGrpc.listUser                       sample  164334   5.843 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.696           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.504           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.846           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.333           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.465           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.508           ms/op
