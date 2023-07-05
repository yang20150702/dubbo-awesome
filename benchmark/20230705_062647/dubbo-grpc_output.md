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
# Warmup Iteration   1: 4.559 ops/ms
# Warmup Iteration   2: 9.338 ops/ms
# Warmup Iteration   3: 10.207 ops/ms
Iteration   1: 10.730 ops/ms
Iteration   2: 10.645 ops/ms
Iteration   3: 10.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.663 ±(99.9%) 1.096 ops/ms [Average]
  (min, avg, max) = (10.613, 10.663, 10.730), stdev = 0.060
  CI (99.9%): [9.567, 11.759] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.604 ops/ms
# Warmup Iteration   2: 10.493 ops/ms
# Warmup Iteration   3: 11.060 ops/ms
Iteration   1: 11.234 ops/ms
Iteration   2: 11.238 ops/ms
Iteration   3: 11.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.208 ±(99.9%) 0.892 ops/ms [Average]
  (min, avg, max) = (11.152, 11.208, 11.238), stdev = 0.049
  CI (99.9%): [10.316, 12.100] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.717 ops/ms
# Warmup Iteration   2: 10.276 ops/ms
# Warmup Iteration   3: 10.746 ops/ms
Iteration   1: 10.731 ops/ms
Iteration   2: 10.509 ops/ms
Iteration   3: 10.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.708 ±(99.9%) 3.426 ops/ms [Average]
  (min, avg, max) = (10.509, 10.708, 10.882), stdev = 0.188
  CI (99.9%): [7.282, 14.133] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.635 ops/ms
# Warmup Iteration   2: 7.570 ops/ms
# Warmup Iteration   3: 8.225 ops/ms
Iteration   1: 8.156 ops/ms
Iteration   2: 8.298 ops/ms
Iteration   3: 8.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.236 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (8.156, 8.236, 8.298), stdev = 0.072
  CI (99.9%): [6.915, 9.557] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.099 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.002 ms/op
Iteration   1: 2.986 ±(99.9%) 0.003 ms/op
Iteration   2: 2.965 ±(99.9%) 0.003 ms/op
Iteration   3: 3.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.985 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.965, 2.985, 3.003), stdev = 0.019
  CI (99.9%): [2.639, 3.331] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.770 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.872 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.848 ±(99.9%) 0.002 ms/op
Iteration   1: 2.859 ±(99.9%) 0.004 ms/op
Iteration   2: 2.833 ±(99.9%) 0.003 ms/op
Iteration   3: 2.898 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.863 ±(99.9%) 0.592 ms/op [Average]
  (min, avg, max) = (2.833, 2.863, 2.898), stdev = 0.032
  CI (99.9%): [2.271, 3.456] (assumes normal distribution)


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.003 ms/op
Iteration   1: 2.913 ±(99.9%) 0.003 ms/op
Iteration   2: 2.949 ±(99.9%) 0.003 ms/op
Iteration   3: 2.951 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.937 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (2.913, 2.937, 2.951), stdev = 0.022
  CI (99.9%): [2.545, 3.330] (assumes normal distribution)


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
# Warmup Iteration   1: 5.457 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.014 ms/op
Iteration   1: 3.856 ±(99.9%) 0.011 ms/op
Iteration   2: 3.858 ±(99.9%) 0.017 ms/op
Iteration   3: 3.917 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.877 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (3.856, 3.877, 3.917), stdev = 0.035
  CI (99.9%): [3.242, 4.512] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.005 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  6.529 ms/op
                 createUser·p0.9999: 21.766 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  13.200 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  10.937 ms/op
                 createUser·p0.9999: 28.717 ms/op
                 createUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320251
  mean =      2.996 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25212 
    [ 2.500,  5.000) = 293804 
    [ 5.000,  7.500) = 878 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      9.580 ms/op
     p(99.9900) =     28.056 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.006 ms/op
Iteration   1: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.917 ms/op
                 existUser·p0.9999: 17.957 ms/op
                 existUser·p1.00:   18.186 ms/op

Iteration   2: 2.845 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  8.202 ms/op
                 existUser·p0.9999: 18.867 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   3: 2.884 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  6.734 ms/op
                 existUser·p0.9999: 14.089 ms/op
                 existUser·p1.00:   15.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333874
  mean =      2.874 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3743 
    [ 1.250,  2.500) = 40280 
    [ 2.500,  3.750) = 278920 
    [ 3.750,  5.000) = 9387 
    [ 5.000,  6.250) = 967 
    [ 6.250,  7.500) = 257 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.318 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     19.613 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.577 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.937 ms/op
                 getUser·p0.9999: 12.501 ms/op
                 getUser·p1.00:   13.025 ms/op

Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.646 ms/op
                 getUser·p0.9999: 14.352 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.854 ms/op
                 getUser·p0.9999: 18.108 ms/op
                 getUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318232
  mean =      3.016 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1432 
    [ 1.250,  2.500) = 27837 
    [ 2.500,  3.750) = 270167 
    [ 3.750,  5.000) = 17500 
    [ 5.000,  6.250) = 680 
    [ 6.250,  7.500) = 273 
    [ 7.500,  8.750) = 121 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.705 ms/op
     p(99.9900) =     15.977 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 4.631 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
Iteration   1: 3.982 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   2: 3.861 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.598 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 24.528 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 3.940 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.448 ms/op
                 listUser·p0.9999: 18.150 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244543
  mean =      3.927 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3692 
    [ 2.500,  5.000) = 216877 
    [ 5.000,  7.500) = 22739 
    [ 7.500, 10.000) = 747 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     14.287 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     25.490 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.663 ± 1.096  ops/ms
ClientGrpc.existUser                       thrpt       3  11.208 ± 0.892  ops/ms
ClientGrpc.getUser                         thrpt       3  10.708 ± 3.426  ops/ms
ClientGrpc.listUser                        thrpt       3   8.236 ± 1.321  ops/ms
ClientGrpc.createUser                       avgt       3   2.985 ± 0.346   ms/op
ClientGrpc.existUser                        avgt       3   2.863 ± 0.592   ms/op
ClientGrpc.getUser                          avgt       3   2.937 ± 0.393   ms/op
ClientGrpc.listUser                         avgt       3   3.877 ± 0.635   ms/op
ClientGrpc.createUser                     sample  320251   2.996 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.638           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.580           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.056           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.934           ms/op
ClientGrpc.existUser                      sample  333874   2.874 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.558           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.318           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.088           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.988           ms/op
ClientGrpc.getUser                        sample  318232   3.016 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.577           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.705           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.977           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.579           ms/op
ClientGrpc.listUser                       sample  244543   3.927 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.598           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.287           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.152           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
