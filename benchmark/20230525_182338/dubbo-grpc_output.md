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
# Warmup Iteration   1: 4.273 ops/ms
# Warmup Iteration   2: 9.271 ops/ms
# Warmup Iteration   3: 9.841 ops/ms
Iteration   1: 10.223 ops/ms
Iteration   2: 10.172 ops/ms
Iteration   3: 10.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.418 ±(99.9%) 6.997 ops/ms [Average]
  (min, avg, max) = (10.172, 10.418, 10.860), stdev = 0.384
  CI (99.9%): [3.421, 17.416] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.643 ops/ms
# Warmup Iteration   2: 10.578 ops/ms
# Warmup Iteration   3: 11.392 ops/ms
Iteration   1: 10.894 ops/ms
Iteration   2: 11.066 ops/ms
Iteration   3: 11.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.011 ±(99.9%) 1.855 ops/ms [Average]
  (min, avg, max) = (10.894, 11.011, 11.074), stdev = 0.102
  CI (99.9%): [9.157, 12.866] (assumes normal distribution)


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
# Warmup Iteration   1: 7.118 ops/ms
# Warmup Iteration   2: 10.095 ops/ms
# Warmup Iteration   3: 10.340 ops/ms
Iteration   1: 10.424 ops/ms
Iteration   2: 10.386 ops/ms
Iteration   3: 10.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.419 ±(99.9%) 0.549 ops/ms [Average]
  (min, avg, max) = (10.386, 10.419, 10.445), stdev = 0.030
  CI (99.9%): [9.870, 10.968] (assumes normal distribution)


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
# Warmup Iteration   1: 5.352 ops/ms
# Warmup Iteration   2: 7.860 ops/ms
# Warmup Iteration   3: 7.944 ops/ms
Iteration   1: 7.985 ops/ms
Iteration   2: 7.944 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.969 ±(99.9%) 0.400 ops/ms [Average]
  (min, avg, max) = (7.944, 7.969, 7.985), stdev = 0.022
  CI (99.9%): [7.569, 8.368] (assumes normal distribution)


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.002 ms/op
Iteration   2: 3.059 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.063 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (3.044, 3.063, 3.085), stdev = 0.021
  CI (99.9%): [2.678, 3.447] (assumes normal distribution)


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.811 ±(99.9%) 0.010 ms/op
Iteration   1: 2.862 ±(99.9%) 0.003 ms/op
Iteration   2: 2.944 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.923 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (2.862, 2.923, 2.963), stdev = 0.054
  CI (99.9%): [1.944, 3.903] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.303 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.003 ms/op
Iteration   1: 3.073 ±(99.9%) 0.005 ms/op
Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
Iteration   3: 3.050 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.057 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (3.048, 3.057, 3.073), stdev = 0.014
  CI (99.9%): [2.802, 3.312] (assumes normal distribution)


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
# Warmup Iteration   1: 5.539 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.023 ms/op
Iteration   1: 3.961 ±(99.9%) 0.008 ms/op
Iteration   2: 3.992 ±(99.9%) 0.011 ms/op
Iteration   3: 3.953 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.969 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (3.953, 3.969, 3.992), stdev = 0.021
  CI (99.9%): [3.592, 4.346] (assumes normal distribution)


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 3.106 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.476 ms/op
                 createUser·p0.999:  10.503 ms/op
                 createUser·p0.9999: 20.470 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.989 ms/op
                 createUser·p0.999:  12.286 ms/op
                 createUser·p0.9999: 15.243 ms/op
                 createUser·p1.00:   15.401 ms/op

Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.220 ms/op
                 createUser·p0.9999: 19.743 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309807
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14512 
    [ 2.500,  5.000) = 293234 
    [ 5.000,  7.500) = 1529 
    [ 7.500, 10.000) = 209 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     10.600 ms/op
     p(99.9900) =     19.859 ms/op
     p(99.9990) =     20.772 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 4.217 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.005 ms/op
Iteration   1: 2.990 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  9.015 ms/op
                 existUser·p0.9999: 12.260 ms/op
                 existUser·p1.00:   12.534 ms/op

Iteration   2: 2.943 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  9.476 ms/op
                 existUser·p0.9999: 13.765 ms/op
                 existUser·p1.00:   16.105 ms/op

Iteration   3: 2.930 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.534 ms/op
                 existUser·p0.9999: 16.956 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324636
  mean =      2.954 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 858 
    [ 1.250,  2.500) = 30597 
    [ 2.500,  3.750) = 282849 
    [ 3.750,  5.000) = 8912 
    [ 5.000,  6.250) = 752 
    [ 6.250,  7.500) = 293 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     16.663 ms/op
     p(99.9990) =     18.694 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 4.311 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
Iteration   1: 3.136 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  8.487 ms/op
                 getUser·p0.9999: 20.021 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  7.427 ms/op
                 getUser·p0.9999: 24.052 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   3: 3.054 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  6.916 ms/op
                 getUser·p0.9999: 32.263 ms/op
                 getUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310368
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22696 
    [ 2.500,  5.000) = 285395 
    [ 5.000,  7.500) = 1951 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =      7.619 ms/op
     p(99.9900) =     31.127 ms/op
     p(99.9990) =     33.249 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 5.627 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.010 ms/op
Iteration   1: 3.965 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  13.686 ms/op
                 listUser·p0.9999: 23.327 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   2: 3.914 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 17.481 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   3: 3.993 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.817 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 21.363 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242459
  mean =      3.957 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3390 
    [ 2.500,  5.000) = 218336 
    [ 5.000,  7.500) = 19408 
    [ 7.500, 10.000) = 820 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     20.923 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.418 ± 6.997  ops/ms
ClientGrpc.existUser                       thrpt       3  11.011 ± 1.855  ops/ms
ClientGrpc.getUser                         thrpt       3  10.419 ± 0.549  ops/ms
ClientGrpc.listUser                        thrpt       3   7.969 ± 0.400  ops/ms
ClientGrpc.createUser                       avgt       3   3.063 ± 0.384   ms/op
ClientGrpc.existUser                        avgt       3   2.923 ± 0.979   ms/op
ClientGrpc.getUser                          avgt       3   3.057 ± 0.255   ms/op
ClientGrpc.listUser                         avgt       3   3.969 ± 0.377   ms/op
ClientGrpc.createUser                     sample  309807   3.098 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.775           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.600           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.859           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.840           ms/op
ClientGrpc.existUser                      sample  324636   2.954 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.767           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.093           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.663           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.809           ms/op
ClientGrpc.getUser                        sample  310368   3.091 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.617           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.903           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.825           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.619           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.127           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.391           ms/op
ClientGrpc.listUser                       sample  242459   3.957 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.817           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.926           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.923           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.724           ms/op
