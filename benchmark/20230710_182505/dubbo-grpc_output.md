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
# Warmup Iteration   1: 4.324 ops/ms
# Warmup Iteration   2: 9.283 ops/ms
# Warmup Iteration   3: 10.310 ops/ms
Iteration   1: 10.799 ops/ms
Iteration   2: 10.688 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.735 ±(99.9%) 1.046 ops/ms [Average]
  (min, avg, max) = (10.688, 10.735, 10.799), stdev = 0.057
  CI (99.9%): [9.688, 11.781] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.882 ops/ms
# Warmup Iteration   2: 10.690 ops/ms
# Warmup Iteration   3: 11.016 ops/ms
Iteration   1: 10.903 ops/ms
Iteration   2: 11.043 ops/ms
Iteration   3: 11.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.038 ±(99.9%) 2.432 ops/ms [Average]
  (min, avg, max) = (10.903, 11.038, 11.169), stdev = 0.133
  CI (99.9%): [8.607, 13.470] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.738 ops/ms
# Warmup Iteration   2: 10.429 ops/ms
# Warmup Iteration   3: 10.748 ops/ms
Iteration   1: 10.479 ops/ms
Iteration   2: 10.620 ops/ms
Iteration   3: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.549 ±(99.9%) 1.286 ops/ms [Average]
  (min, avg, max) = (10.479, 10.549, 10.620), stdev = 0.070
  CI (99.9%): [9.263, 11.834] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.957 ops/ms
# Warmup Iteration   2: 7.746 ops/ms
# Warmup Iteration   3: 8.150 ops/ms
Iteration   1: 8.208 ops/ms
Iteration   2: 8.104 ops/ms
Iteration   3: 8.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.143 ±(99.9%) 1.033 ops/ms [Average]
  (min, avg, max) = (8.104, 8.143, 8.208), stdev = 0.057
  CI (99.9%): [7.109, 9.176] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.015 ms/op
Iteration   1: 2.996 ±(99.9%) 0.002 ms/op
Iteration   2: 2.953 ±(99.9%) 0.002 ms/op
Iteration   3: 2.967 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.972 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (2.953, 2.972, 2.996), stdev = 0.022
  CI (99.9%): [2.573, 3.371] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.698 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.003 ms/op
Iteration   1: 2.864 ±(99.9%) 0.002 ms/op
Iteration   2: 2.837 ±(99.9%) 0.003 ms/op
Iteration   3: 2.873 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.858 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.837, 2.858, 2.873), stdev = 0.019
  CI (99.9%): [2.512, 3.204] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.861 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.002 ms/op
Iteration   1: 3.035 ±(99.9%) 0.003 ms/op
Iteration   2: 3.017 ±(99.9%) 0.002 ms/op
Iteration   3: 2.982 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.011 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (2.982, 3.011, 3.035), stdev = 0.027
  CI (99.9%): [2.516, 3.507] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.960 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.042 ms/op
Iteration   1: 3.904 ±(99.9%) 0.028 ms/op
Iteration   2: 3.907 ±(99.9%) 0.031 ms/op
Iteration   3: 3.872 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.894 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.872, 3.894, 3.907), stdev = 0.020
  CI (99.9%): [3.536, 4.252] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.808 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
Iteration   1: 3.009 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.925 ms/op
                 createUser·p0.9999: 11.973 ms/op
                 createUser·p1.00:   12.272 ms/op

Iteration   2: 3.004 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.807 ms/op
                 createUser·p0.9999: 20.873 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   3: 2.976 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.539 ms/op
                 createUser·p0.9999: 16.036 ms/op
                 createUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320170
  mean =      2.996 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26493 
    [ 2.500,  5.000) = 292347 
    [ 5.000,  7.500) = 948 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     19.928 ms/op
     p(99.9990) =     21.220 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.005 ms/op
Iteration   1: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.856 ms/op
                 existUser·p0.9999: 11.861 ms/op
                 existUser·p1.00:   12.272 ms/op

Iteration   2: 2.924 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.819 ms/op
                 existUser·p0.9999: 13.207 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.914 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.620 ms/op
                 existUser·p0.9999: 20.316 ms/op
                 existUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329403
  mean =      2.914 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39114 
    [ 2.500,  5.000) = 289082 
    [ 5.000,  7.500) = 873 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.533 ms/op
     p(99.9900) =     15.151 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.178 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 2.978 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.639 ms/op
                 getUser·p0.999:  8.415 ms/op
                 getUser·p0.9999: 16.512 ms/op
                 getUser·p1.00:   16.744 ms/op

Iteration   2: 2.957 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.702 ms/op
                 getUser·p0.9999: 13.503 ms/op
                 getUser·p1.00:   15.565 ms/op

Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  9.799 ms/op
                 getUser·p0.9999: 17.967 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322430
  mean =      2.976 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1545 
    [ 1.250,  2.500) = 27876 
    [ 2.500,  3.750) = 279990 
    [ 3.750,  5.000) = 11548 
    [ 5.000,  6.250) = 614 
    [ 6.250,  7.500) = 405 
    [ 7.500,  8.750) = 132 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.630 ms/op
     p(99.9900) =     16.462 ms/op
     p(99.9990) =     18.401 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 5.240 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.930 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.011 ms/op
Iteration   1: 3.919 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   2: 3.931 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  18.044 ms/op
                 listUser·p0.9999: 27.296 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   3: 3.923 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.700 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.047 ms/op
                 listUser·p0.9999: 16.884 ms/op
                 listUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244589
  mean =      3.924 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4889 
    [ 2.500,  5.000) = 217378 
    [ 5.000,  7.500) = 20929 
    [ 7.500, 10.000) = 833 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     14.736 ms/op
     p(99.9900) =     26.887 ms/op
     p(99.9990) =     27.758 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.735 ± 1.046  ops/ms
ClientGrpc.existUser                       thrpt       3  11.038 ± 2.432  ops/ms
ClientGrpc.getUser                         thrpt       3  10.549 ± 1.286  ops/ms
ClientGrpc.listUser                        thrpt       3   8.143 ± 1.033  ops/ms
ClientGrpc.createUser                       avgt       3   2.972 ± 0.399   ms/op
ClientGrpc.existUser                        avgt       3   2.858 ± 0.346   ms/op
ClientGrpc.getUser                          avgt       3   3.011 ± 0.496   ms/op
ClientGrpc.listUser                         avgt       3   3.894 ± 0.358   ms/op
ClientGrpc.createUser                     sample  320170   2.996 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.651           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.928           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.365           ms/op
ClientGrpc.existUser                      sample  329403   2.914 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.515           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.533           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.151           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.546           ms/op
ClientGrpc.getUser                        sample  322430   2.976 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.630           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.462           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.547           ms/op
ClientGrpc.listUser                       sample  244589   3.924 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.700           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.736           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.887           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.508           ms/op
