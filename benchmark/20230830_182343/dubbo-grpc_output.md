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
# Warmup Iteration   1: 4.127 ops/ms
# Warmup Iteration   2: 8.852 ops/ms
# Warmup Iteration   3: 9.951 ops/ms
Iteration   1: 10.062 ops/ms
Iteration   2: 10.511 ops/ms
Iteration   3: 10.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.392 ±(99.9%) 5.283 ops/ms [Average]
  (min, avg, max) = (10.062, 10.392, 10.604), stdev = 0.290
  CI (99.9%): [5.109, 15.675] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.518 ops/ms
# Warmup Iteration   2: 10.338 ops/ms
# Warmup Iteration   3: 10.924 ops/ms
Iteration   1: 11.086 ops/ms
Iteration   2: 10.903 ops/ms
Iteration   3: 10.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.932 ±(99.9%) 2.579 ops/ms [Average]
  (min, avg, max) = (10.808, 10.932, 11.086), stdev = 0.141
  CI (99.9%): [8.353, 13.511] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.882 ops/ms
# Warmup Iteration   2: 10.119 ops/ms
# Warmup Iteration   3: 10.672 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.540 ±(99.9%) 0.648 ops/ms [Average]
  (min, avg, max) = (10.499, 10.540, 10.563), stdev = 0.036
  CI (99.9%): [9.892, 11.188] (assumes normal distribution)


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
# Warmup Iteration   1: 5.990 ops/ms
# Warmup Iteration   2: 7.505 ops/ms
# Warmup Iteration   3: 8.039 ops/ms
Iteration   1: 8.086 ops/ms
Iteration   2: 8.089 ops/ms
Iteration   3: 8.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.080 ±(99.9%) 0.249 ops/ms [Average]
  (min, avg, max) = (8.064, 8.080, 8.089), stdev = 0.014
  CI (99.9%): [7.831, 8.329] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.154 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.004 ms/op
Iteration   1: 3.078 ±(99.9%) 0.011 ms/op
Iteration   2: 3.045 ±(99.9%) 0.004 ms/op
Iteration   3: 3.032 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.051 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (3.032, 3.051, 3.078), stdev = 0.023
  CI (99.9%): [2.624, 3.479] (assumes normal distribution)


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.002 ms/op
Iteration   1: 2.860 ±(99.9%) 0.003 ms/op
Iteration   2: 2.896 ±(99.9%) 0.002 ms/op
Iteration   3: 2.897 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.884 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.860, 2.884, 2.897), stdev = 0.021
  CI (99.9%): [2.498, 3.270] (assumes normal distribution)


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.003 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.065 ±(99.9%) 0.003 ms/op
Iteration   3: 3.014 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (3.014, 3.043, 3.065), stdev = 0.026
  CI (99.9%): [2.565, 3.520] (assumes normal distribution)


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
# Warmup Iteration   1: 5.599 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.013 ms/op
Iteration   1: 4.018 ±(99.9%) 0.015 ms/op
Iteration   2: 3.966 ±(99.9%) 0.013 ms/op
Iteration   3: 3.937 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.974 ±(99.9%) 0.747 ms/op [Average]
  (min, avg, max) = (3.937, 3.974, 4.018), stdev = 0.041
  CI (99.9%): [3.227, 4.720] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.389 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  7.508 ms/op
                 createUser·p0.9999: 19.185 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   2: 3.015 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.313 ms/op
                 createUser·p0.9999: 29.734 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  7.971 ms/op
                 createUser·p0.9999: 20.136 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316185
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24375 
    [ 2.500,  5.000) = 289712 
    [ 5.000,  7.500) = 1700 
    [ 7.500, 10.000) = 193 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      7.938 ms/op
     p(99.9900) =     28.631 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.145 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
Iteration   1: 2.721 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.798 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.578 ms/op
                 existUser·p0.9999: 18.874 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   2: 2.934 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.575 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.215 ms/op
                 existUser·p0.9999: 14.255 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 14.716 ms/op
                 existUser·p1.00:   15.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334765
  mean =      2.868 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4744 
    [ 1.250,  2.500) = 45950 
    [ 2.500,  3.750) = 273374 
    [ 3.750,  5.000) = 8969 
    [ 5.000,  6.250) = 731 
    [ 6.250,  7.500) = 437 
    [ 7.500,  8.750) = 323 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.339 ms/op
     p(99.9900) =     15.466 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
Iteration   1: 3.038 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.844 ms/op
                 getUser·p0.9999: 13.140 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 17.072 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.082 ms/op
                 getUser·p0.9999: 24.492 ms/op
                 getUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312636
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14615 
    [ 2.500,  5.000) = 296132 
    [ 5.000,  7.500) = 1474 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.977 ms/op
     p(99.9900) =     22.986 ms/op
     p(99.9990) =     25.026 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 5.627 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.011 ms/op
Iteration   1: 4.063 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.406 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.336 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 18.452 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 4.051 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.006 ms/op
                 listUser·p0.9999: 18.812 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   3: 3.905 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  15.486 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239872
  mean =      4.005 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 3050 
    [ 2.500,  3.750) = 98049 
    [ 3.750,  5.000) = 113345 
    [ 5.000,  6.250) = 18343 
    [ 6.250,  7.500) = 5243 
    [ 7.500,  8.750) = 971 
    [ 8.750, 10.000) = 309 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 91 
    [15.000, 16.250) = 97 
    [16.250, 17.500) = 101 
    [17.500, 18.750) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.060 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     15.272 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     19.189 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.392 ± 5.283  ops/ms
ClientGrpc.existUser                       thrpt       3  10.932 ± 2.579  ops/ms
ClientGrpc.getUser                         thrpt       3  10.540 ± 0.648  ops/ms
ClientGrpc.listUser                        thrpt       3   8.080 ± 0.249  ops/ms
ClientGrpc.createUser                       avgt       3   3.051 ± 0.427   ms/op
ClientGrpc.existUser                        avgt       3   2.884 ± 0.386   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.477   ms/op
ClientGrpc.listUser                         avgt       3   3.974 ± 0.747   ms/op
ClientGrpc.createUser                     sample  316185   3.035 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.764           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.938           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.631           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.015           ms/op
ClientGrpc.existUser                      sample  334765   2.868 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.534           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.339           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.466           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.104           ms/op
ClientGrpc.getUser                        sample  312636   3.072 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.648           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.977           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.986           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.166           ms/op
ClientGrpc.listUser                       sample  239872   4.005 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.406           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.060           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.272           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.416           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.726           ms/op
