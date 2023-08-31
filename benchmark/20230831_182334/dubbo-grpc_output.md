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
# Warmup Iteration   1: 3.706 ops/ms
# Warmup Iteration   2: 8.368 ops/ms
# Warmup Iteration   3: 9.675 ops/ms
Iteration   1: 10.097 ops/ms
Iteration   2: 9.958 ops/ms
Iteration   3: 10.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.051 ±(99.9%) 1.474 ops/ms [Average]
  (min, avg, max) = (9.958, 10.051, 10.099), stdev = 0.081
  CI (99.9%): [8.577, 11.526] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.535 ops/ms
# Warmup Iteration   2: 10.025 ops/ms
# Warmup Iteration   3: 10.541 ops/ms
Iteration   1: 10.732 ops/ms
Iteration   2: 10.654 ops/ms
Iteration   3: 10.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.659 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (10.592, 10.659, 10.732), stdev = 0.070
  CI (99.9%): [9.377, 11.942] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.815 ops/ms
# Warmup Iteration   2: 9.626 ops/ms
# Warmup Iteration   3: 10.509 ops/ms
Iteration   1: 10.429 ops/ms
Iteration   2: 10.364 ops/ms
Iteration   3: 10.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.387 ±(99.9%) 0.675 ops/ms [Average]
  (min, avg, max) = (10.364, 10.387, 10.429), stdev = 0.037
  CI (99.9%): [9.711, 11.062] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.022 ops/ms
# Warmup Iteration   2: 7.546 ops/ms
# Warmup Iteration   3: 7.711 ops/ms
Iteration   1: 7.683 ops/ms
Iteration   2: 7.804 ops/ms
Iteration   3: 7.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.771 ±(99.9%) 1.397 ops/ms [Average]
  (min, avg, max) = (7.683, 7.771, 7.825), stdev = 0.077
  CI (99.9%): [6.374, 9.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.003 ms/op
Iteration   1: 3.073 ±(99.9%) 0.004 ms/op
Iteration   2: 3.107 ±(99.9%) 0.003 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.087 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.073, 3.087, 3.107), stdev = 0.018
  CI (99.9%): [2.764, 3.409] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.002 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 2.902 ±(99.9%) 0.003 ms/op
Iteration   3: 2.870 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.927 ±(99.9%) 1.310 ms/op [Average]
  (min, avg, max) = (2.870, 2.927, 3.007), stdev = 0.072
  CI (99.9%): [1.616, 4.237] (assumes normal distribution)


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.003 ms/op
Iteration   1: 3.037 ±(99.9%) 0.003 ms/op
Iteration   2: 3.090 ±(99.9%) 0.002 ms/op
Iteration   3: 3.074 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.067 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.037, 3.067, 3.090), stdev = 0.028
  CI (99.9%): [2.565, 3.569] (assumes normal distribution)


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
# Warmup Iteration   1: 5.261 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.257 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.009 ms/op
Iteration   1: 4.040 ±(99.9%) 0.014 ms/op
Iteration   2: 4.034 ±(99.9%) 0.016 ms/op
Iteration   3: 4.002 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.025 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (4.002, 4.025, 4.040), stdev = 0.021
  CI (99.9%): [3.643, 4.408] (assumes normal distribution)


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
# Warmup Iteration   1: 4.572 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
Iteration   1: 3.123 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  9.381 ms/op
                 createUser·p0.9999: 22.955 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.624 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.386 ms/op
                 createUser·p0.9999: 27.560 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 3.092 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  10.931 ms/op
                 createUser·p0.9999: 36.372 ms/op
                 createUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309694
  mean =      3.099 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14686 
    [ 2.500,  5.000) = 292628 
    [ 5.000,  7.500) = 1628 
    [ 7.500, 10.000) = 458 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      9.835 ms/op
     p(99.9900) =     34.607 ms/op
     p(99.9990) =     36.563 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  7.765 ms/op
                 existUser·p0.9999: 14.078 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  8.183 ms/op
                 existUser·p0.9999: 16.171 ms/op
                 existUser·p1.00:   16.417 ms/op

Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  8.555 ms/op
                 existUser·p0.9999: 18.403 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321649
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 938 
    [ 1.250,  2.500) = 27574 
    [ 2.500,  3.750) = 281561 
    [ 3.750,  5.000) = 9898 
    [ 5.000,  6.250) = 779 
    [ 6.250,  7.500) = 428 
    [ 7.500,  8.750) = 222 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.190 ms/op
     p(99.9900) =     17.073 ms/op
     p(99.9990) =     18.991 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 4.500 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.007 ms/op
Iteration   1: 3.150 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.069 ms/op
                 getUser·p0.9999: 14.107 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  13.453 ms/op
                 getUser·p0.9999: 16.674 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  9.081 ms/op
                 getUser·p0.9999: 27.152 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308034
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14608 
    [ 2.500,  5.000) = 291095 
    [ 5.000,  7.500) = 1682 
    [ 7.500, 10.000) = 413 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =      9.174 ms/op
     p(99.9900) =     25.114 ms/op
     p(99.9990) =     27.228 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 5.207 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.012 ms/op
Iteration   1: 4.127 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  14.704 ms/op
                 listUser·p0.9999: 23.773 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 4.163 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 25.917 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   3: 4.098 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  16.754 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232531
  mean =      4.129 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1932 
    [ 2.500,  5.000) = 201967 
    [ 5.000,  7.500) = 26146 
    [ 7.500, 10.000) = 1969 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     15.375 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     26.434 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.051 ± 1.474  ops/ms
ClientGrpc.existUser                       thrpt       3  10.659 ± 1.283  ops/ms
ClientGrpc.getUser                         thrpt       3  10.387 ± 0.675  ops/ms
ClientGrpc.listUser                        thrpt       3   7.771 ± 1.397  ops/ms
ClientGrpc.createUser                       avgt       3   3.087 ± 0.322   ms/op
ClientGrpc.existUser                        avgt       3   2.927 ± 1.310   ms/op
ClientGrpc.getUser                          avgt       3   3.067 ± 0.502   ms/op
ClientGrpc.listUser                         avgt       3   4.025 ± 0.382   ms/op
ClientGrpc.createUser                     sample  309694   3.099 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.596           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.727           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.835           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.607           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.700           ms/op
ClientGrpc.existUser                      sample  321649   2.983 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.812           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.190           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.073           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  308034   3.115 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.684           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.174           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.114           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.296           ms/op
ClientGrpc.listUser                       sample  232531   4.129 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.106           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.936           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.569           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.375           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.510           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.575           ms/op
