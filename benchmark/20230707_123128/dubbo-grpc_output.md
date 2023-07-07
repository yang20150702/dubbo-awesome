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
# Warmup Iteration   1: 3.094 ops/ms
# Warmup Iteration   2: 6.634 ops/ms
# Warmup Iteration   3: 8.072 ops/ms
Iteration   1: 8.348 ops/ms
Iteration   2: 8.511 ops/ms
Iteration   3: 8.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.495 ±(99.9%) 2.546 ops/ms [Average]
  (min, avg, max) = (8.348, 8.495, 8.626), stdev = 0.140
  CI (99.9%): [5.949, 11.041] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.909 ops/ms
# Warmup Iteration   2: 7.947 ops/ms
# Warmup Iteration   3: 8.709 ops/ms
Iteration   1: 9.012 ops/ms
Iteration   2: 9.015 ops/ms
Iteration   3: 9.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.075 ±(99.9%) 1.951 ops/ms [Average]
  (min, avg, max) = (9.012, 9.075, 9.199), stdev = 0.107
  CI (99.9%): [7.125, 11.026] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.506 ops/ms
# Warmup Iteration   2: 7.766 ops/ms
# Warmup Iteration   3: 8.371 ops/ms
Iteration   1: 8.314 ops/ms
Iteration   2: 8.516 ops/ms
Iteration   3: 8.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.463 ±(99.9%) 2.390 ops/ms [Average]
  (min, avg, max) = (8.314, 8.463, 8.559), stdev = 0.131
  CI (99.9%): [6.073, 10.853] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.212 ops/ms
# Warmup Iteration   2: 6.393 ops/ms
# Warmup Iteration   3: 6.794 ops/ms
Iteration   1: 6.834 ops/ms
Iteration   2: 6.907 ops/ms
Iteration   3: 6.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.901 ±(99.9%) 1.176 ops/ms [Average]
  (min, avg, max) = (6.834, 6.901, 6.963), stdev = 0.064
  CI (99.9%): [5.725, 8.077] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.064 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.033 ms/op
Iteration   1: 3.704 ±(99.9%) 0.004 ms/op
Iteration   2: 3.628 ±(99.9%) 0.004 ms/op
Iteration   3: 3.661 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.664 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (3.628, 3.664, 3.704), stdev = 0.038
  CI (99.9%): [2.969, 4.360] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.542 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.003 ms/op
Iteration   1: 3.566 ±(99.9%) 0.004 ms/op
Iteration   2: 3.526 ±(99.9%) 0.002 ms/op
Iteration   3: 3.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.546 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (3.526, 3.546, 3.566), stdev = 0.020
  CI (99.9%): [3.178, 3.913] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.076 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.003 ms/op
Iteration   1: 3.692 ±(99.9%) 0.004 ms/op
Iteration   2: 3.721 ±(99.9%) 0.029 ms/op
Iteration   3: 3.706 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.706 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (3.692, 3.706, 3.721), stdev = 0.014
  CI (99.9%): [3.446, 3.967] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.802 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.085 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.850 ±(99.9%) 0.034 ms/op
Iteration   1: 4.665 ±(99.9%) 0.015 ms/op
Iteration   2: 4.789 ±(99.9%) 0.014 ms/op
Iteration   3: 4.841 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.765 ±(99.9%) 1.655 ms/op [Average]
  (min, avg, max) = (4.665, 4.765, 4.841), stdev = 0.091
  CI (99.9%): [3.110, 6.420] (assumes normal distribution)


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
# Warmup Iteration   1: 5.285 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.010 ms/op
Iteration   1: 3.681 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  13.731 ms/op
                 createUser·p0.9999: 19.431 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   2: 3.714 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  8.763 ms/op
                 createUser·p0.9999: 24.294 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   3: 3.726 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  9.929 ms/op
                 createUser·p0.9999: 23.527 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259084
  mean =      3.707 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3864 
    [ 2.500,  5.000) = 249417 
    [ 5.000,  7.500) = 5016 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     11.582 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     24.865 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 5.236 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.008 ms/op
Iteration   1: 3.624 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  11.338 ms/op
                 existUser·p0.9999: 16.558 ms/op
                 existUser·p1.00:   17.007 ms/op

Iteration   2: 3.503 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.030 ms/op
                 existUser·p0.999:  8.925 ms/op
                 existUser·p0.9999: 14.881 ms/op
                 existUser·p1.00:   15.958 ms/op

Iteration   3: 3.635 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  9.172 ms/op
                 existUser·p0.9999: 19.012 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267937
  mean =      3.587 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 177 
    [ 1.250,  2.500) = 8284 
    [ 2.500,  3.750) = 174714 
    [ 3.750,  5.000) = 79105 
    [ 5.000,  6.250) = 4232 
    [ 6.250,  7.500) = 820 
    [ 7.500,  8.750) = 275 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     18.200 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 5.588 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.008 ms/op
Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  11.600 ms/op
                 getUser·p0.9999: 22.913 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.678 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  9.505 ms/op
                 getUser·p0.9999: 16.213 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   3: 3.758 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  8.273 ms/op
                 getUser·p0.9999: 22.462 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255856
  mean =      3.750 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5544 
    [ 2.500,  5.000) = 241738 
    [ 5.000,  7.500) = 7654 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     22.591 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 6.377 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.295 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.056 ±(99.9%) 0.017 ms/op
Iteration   1: 4.704 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.644 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  17.698 ms/op
                 listUser·p0.9999: 21.856 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 4.706 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.570 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  19.270 ms/op
                 listUser·p0.9999: 24.753 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   3: 5.085 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.365 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  23.298 ms/op
                 listUser·p0.9999: 30.062 ms/op
                 listUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198786
  mean =      4.825 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 260 
    [ 2.500,  5.000) = 143223 
    [ 5.000,  7.500) = 49085 
    [ 7.500, 10.000) = 5336 
    [10.000, 12.500) = 478 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      6.889 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     19.340 ms/op
     p(99.9900) =     29.786 ms/op
     p(99.9990) =     32.065 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.495 ± 2.546  ops/ms
ClientGrpc.existUser                       thrpt       3   9.075 ± 1.951  ops/ms
ClientGrpc.getUser                         thrpt       3   8.463 ± 2.390  ops/ms
ClientGrpc.listUser                        thrpt       3   6.901 ± 1.176  ops/ms
ClientGrpc.createUser                       avgt       3   3.664 ± 0.695   ms/op
ClientGrpc.existUser                        avgt       3   3.546 ± 0.368   ms/op
ClientGrpc.getUser                          avgt       3   3.706 ± 0.261   ms/op
ClientGrpc.listUser                         avgt       3   4.765 ± 1.655   ms/op
ClientGrpc.createUser                     sample  259084   3.707 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.786           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.652           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.582           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.019           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.166           ms/op
ClientGrpc.existUser                      sample  267937   3.587 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.772           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.595           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.470           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.200           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.235           ms/op
ClientGrpc.getUser                        sample  255856   3.750 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.914           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.111           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.764           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.591           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.200           ms/op
ClientGrpc.listUser                       sample  198786   4.825 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.305           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.831           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.340           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.786           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.489           ms/op
