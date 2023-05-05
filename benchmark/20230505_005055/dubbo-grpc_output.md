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
# Warmup Iteration   1: 3.778 ops/ms
# Warmup Iteration   2: 8.907 ops/ms
# Warmup Iteration   3: 9.889 ops/ms
Iteration   1: 10.487 ops/ms
Iteration   2: 10.481 ops/ms
Iteration   3: 10.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.582 ±(99.9%) 3.121 ops/ms [Average]
  (min, avg, max) = (10.481, 10.582, 10.780), stdev = 0.171
  CI (99.9%): [7.462, 13.703] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.623 ops/ms
# Warmup Iteration   2: 8.567 ops/ms
# Warmup Iteration   3: 10.194 ops/ms
Iteration   1: 11.288 ops/ms
Iteration   2: 11.010 ops/ms
Iteration   3: 10.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.025 ±(99.9%) 4.675 ops/ms [Average]
  (min, avg, max) = (10.776, 11.025, 11.288), stdev = 0.256
  CI (99.9%): [6.350, 15.700] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 6.477 ops/ms
# Warmup Iteration   2: 9.868 ops/ms
# Warmup Iteration   3: 10.356 ops/ms
Iteration   1: 10.041 ops/ms
Iteration   2: 10.279 ops/ms
Iteration   3: 10.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.255 ±(99.9%) 3.695 ops/ms [Average]
  (min, avg, max) = (10.041, 10.255, 10.444), stdev = 0.203
  CI (99.9%): [6.560, 13.950] (assumes normal distribution)


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
# Warmup Iteration   1: 4.964 ops/ms
# Warmup Iteration   2: 7.252 ops/ms
# Warmup Iteration   3: 7.706 ops/ms
Iteration   1: 7.683 ops/ms
Iteration   2: 7.892 ops/ms
Iteration   3: 7.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.797 ±(99.9%) 1.927 ops/ms [Average]
  (min, avg, max) = (7.683, 7.797, 7.892), stdev = 0.106
  CI (99.9%): [5.870, 9.724] (assumes normal distribution)


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
# Warmup Iteration   1: 4.271 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.003 ms/op
Iteration   1: 3.202 ±(99.9%) 0.003 ms/op
Iteration   2: 3.102 ±(99.9%) 0.002 ms/op
Iteration   3: 3.169 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.158 ±(99.9%) 0.935 ms/op [Average]
  (min, avg, max) = (3.102, 3.158, 3.202), stdev = 0.051
  CI (99.9%): [2.223, 4.092] (assumes normal distribution)


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
# Warmup Iteration   1: 4.226 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.004 ms/op
Iteration   1: 2.980 ±(99.9%) 0.002 ms/op
Iteration   2: 3.005 ±(99.9%) 0.002 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.994 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.980, 2.994, 3.005), stdev = 0.013
  CI (99.9%): [2.765, 3.224] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.004 ms/op
Iteration   1: 3.081 ±(99.9%) 0.005 ms/op
Iteration   2: 3.116 ±(99.9%) 0.002 ms/op
Iteration   3: 3.239 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.145 ±(99.9%) 1.507 ms/op [Average]
  (min, avg, max) = (3.081, 3.145, 3.239), stdev = 0.083
  CI (99.9%): [1.639, 4.652] (assumes normal distribution)


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
# Warmup Iteration   1: 10.673 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.007 ms/op
Iteration   1: 4.208 ±(99.9%) 0.016 ms/op
Iteration   2: 4.085 ±(99.9%) 0.006 ms/op
Iteration   3: 4.186 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.160 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (4.085, 4.160, 4.208), stdev = 0.065
  CI (99.9%): [2.966, 5.353] (assumes normal distribution)


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
# Warmup Iteration   1: 4.331 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
Iteration   1: 3.194 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  11.548 ms/op
                 createUser·p0.9999: 15.220 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  11.013 ms/op
                 createUser·p0.9999: 16.872 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  11.435 ms/op
                 createUser·p0.9999: 20.198 ms/op
                 createUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302652
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15900 
    [ 2.500,  5.000) = 282418 
    [ 5.000,  7.500) = 2842 
    [ 7.500, 10.000) = 1070 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     11.458 ms/op
     p(99.9900) =     19.030 ms/op
     p(99.9990) =     20.609 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 4.392 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   7.717 ms/op
                 existUser·p0.999:  10.565 ms/op
                 existUser·p0.9999: 19.075 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.448 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   7.250 ms/op
                 existUser·p0.999:  11.682 ms/op
                 existUser·p0.9999: 21.374 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  10.811 ms/op
                 existUser·p0.9999: 18.889 ms/op
                 existUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314703
  mean =      3.049 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32371 
    [ 2.500,  5.000) = 274528 
    [ 5.000,  7.500) = 4776 
    [ 7.500, 10.000) = 2518 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     11.469 ms/op
     p(99.9900) =     19.350 ms/op
     p(99.9990) =     21.973 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 4.715 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   6.012 ms/op
                 getUser·p0.999:  11.400 ms/op
                 getUser·p0.9999: 14.623 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  10.748 ms/op
                 getUser·p0.9999: 16.941 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.102 ms/op
                 getUser·p0.9999: 19.333 ms/op
                 getUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303090
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15848 
    [ 2.500,  5.000) = 283107 
    [ 5.000,  7.500) = 2928 
    [ 7.500, 10.000) = 862 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     10.517 ms/op
     p(99.9900) =     18.700 ms/op
     p(99.9990) =     19.692 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 5.941 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.012 ms/op
Iteration   1: 4.039 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   8.885 ms/op
                 listUser·p0.999:  16.313 ms/op
                 listUser·p0.9999: 20.548 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 4.184 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  20.942 ms/op
                 listUser·p0.9999: 28.838 ms/op
                 listUser·p1.00:   29.295 ms/op

Iteration   3: 4.074 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 20.550 ms/op
                 listUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234152
  mean =      4.098 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2075 
    [ 2.500,  5.000) = 205224 
    [ 5.000,  7.500) = 23646 
    [ 7.500, 10.000) = 2261 
    [10.000, 12.500) = 430 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      8.024 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     28.265 ms/op
     p(99.9990) =     29.207 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.582 ± 3.121  ops/ms
ClientGrpc.existUser                       thrpt       3  11.025 ± 4.675  ops/ms
ClientGrpc.getUser                         thrpt       3  10.255 ± 3.695  ops/ms
ClientGrpc.listUser                        thrpt       3   7.797 ± 1.927  ops/ms
ClientGrpc.createUser                       avgt       3   3.158 ± 0.935   ms/op
ClientGrpc.existUser                        avgt       3   2.994 ± 0.230   ms/op
ClientGrpc.getUser                          avgt       3   3.145 ± 1.507   ms/op
ClientGrpc.listUser                         avgt       3   4.160 ± 1.194   ms/op
ClientGrpc.createUser                     sample  302652   3.172 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.653           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.047           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.458           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.030           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.103           ms/op
ClientGrpc.existUser                      sample  314703   3.049 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.448           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.035           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.463           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.469           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.350           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.805           ms/op
ClientGrpc.getUser                        sample  303090   3.167 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.640           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.071           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.517           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.700           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.414           ms/op
ClientGrpc.listUser                       sample  234152   4.098 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.022           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.024           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.727           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.265           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.295           ms/op
