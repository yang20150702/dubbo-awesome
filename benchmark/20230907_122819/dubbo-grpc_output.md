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
# Warmup Iteration   1: 3.990 ops/ms
# Warmup Iteration   2: 8.870 ops/ms
# Warmup Iteration   3: 9.955 ops/ms
Iteration   1: 10.547 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 10.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.509 ±(99.9%) 1.728 ops/ms [Average]
  (min, avg, max) = (10.401, 10.509, 10.578), stdev = 0.095
  CI (99.9%): [8.780, 12.237] (assumes normal distribution)


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
# Warmup Iteration   1: 7.169 ops/ms
# Warmup Iteration   2: 10.319 ops/ms
# Warmup Iteration   3: 10.859 ops/ms
Iteration   1: 10.894 ops/ms
Iteration   2: 11.000 ops/ms
Iteration   3: 10.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.883 ±(99.9%) 2.252 ops/ms [Average]
  (min, avg, max) = (10.754, 10.883, 11.000), stdev = 0.123
  CI (99.9%): [8.631, 13.134] (assumes normal distribution)


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
# Warmup Iteration   1: 6.976 ops/ms
# Warmup Iteration   2: 9.710 ops/ms
# Warmup Iteration   3: 10.431 ops/ms
Iteration   1: 10.362 ops/ms
Iteration   2: 10.385 ops/ms
Iteration   3: 10.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.308 ±(99.9%) 2.074 ops/ms [Average]
  (min, avg, max) = (10.178, 10.308, 10.385), stdev = 0.114
  CI (99.9%): [8.234, 12.383] (assumes normal distribution)


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
# Warmup Iteration   1: 5.636 ops/ms
# Warmup Iteration   2: 7.582 ops/ms
# Warmup Iteration   3: 7.828 ops/ms
Iteration   1: 7.849 ops/ms
Iteration   2: 7.970 ops/ms
Iteration   3: 7.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.913 ±(99.9%) 1.107 ops/ms [Average]
  (min, avg, max) = (7.849, 7.913, 7.970), stdev = 0.061
  CI (99.9%): [6.806, 9.020] (assumes normal distribution)


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.009 ms/op
Iteration   1: 3.139 ±(99.9%) 0.003 ms/op
Iteration   2: 3.082 ±(99.9%) 0.004 ms/op
Iteration   3: 3.033 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.085 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.033, 3.085, 3.139), stdev = 0.053
  CI (99.9%): [2.114, 4.056] (assumes normal distribution)


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.003 ms/op
Iteration   1: 2.950 ±(99.9%) 0.003 ms/op
Iteration   2: 2.934 ±(99.9%) 0.003 ms/op
Iteration   3: 2.923 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.936 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.923, 2.936, 2.950), stdev = 0.014
  CI (99.9%): [2.684, 3.187] (assumes normal distribution)


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
# Warmup Iteration   1: 4.385 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.004 ms/op
Iteration   1: 3.009 ±(99.9%) 0.003 ms/op
Iteration   2: 3.031 ±(99.9%) 0.002 ms/op
Iteration   3: 3.023 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.021 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (3.009, 3.021, 3.031), stdev = 0.011
  CI (99.9%): [2.821, 3.221] (assumes normal distribution)


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
# Warmup Iteration   1: 4.959 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.019 ms/op
Iteration   1: 4.028 ±(99.9%) 0.015 ms/op
Iteration   2: 3.960 ±(99.9%) 0.021 ms/op
Iteration   3: 3.923 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.970 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.923, 3.970, 4.028), stdev = 0.054
  CI (99.9%): [2.994, 4.947] (assumes normal distribution)


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
# Warmup Iteration   1: 4.510 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.896 ms/op
                 createUser·p0.999:  7.954 ms/op
                 createUser·p0.9999: 13.313 ms/op
                 createUser·p1.00:   13.533 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  8.321 ms/op
                 createUser·p0.9999: 14.688 ms/op
                 createUser·p1.00:   15.008 ms/op

Iteration   3: 3.063 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  9.896 ms/op
                 createUser·p0.9999: 27.300 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313763
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21946 
    [ 2.500,  5.000) = 289459 
    [ 5.000,  7.500) = 1820 
    [ 7.500, 10.000) = 301 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     27.680 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.006 ms/op
Iteration   1: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.672 ms/op
                 existUser·p0.9999: 18.416 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   2: 2.973 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.619 ms/op
                 existUser·p0.9999: 14.569 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  10.416 ms/op
                 existUser·p0.9999: 16.190 ms/op
                 existUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326021
  mean =      2.942 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2169 
    [ 1.250,  2.500) = 32164 
    [ 2.500,  3.750) = 277262 
    [ 3.750,  5.000) = 12838 
    [ 5.000,  6.250) = 716 
    [ 6.250,  7.500) = 390 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.331 ms/op
     p(99.9900) =     16.718 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.565 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.006 ms/op
Iteration   1: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.856 ms/op
                 getUser·p0.9999: 14.254 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.908 ms/op
                 getUser·p0.9999: 15.477 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  12.742 ms/op
                 getUser·p0.9999: 17.029 ms/op
                 getUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310501
  mean =      3.090 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 406 
    [ 1.250,  2.500) = 13798 
    [ 2.500,  3.750) = 276470 
    [ 3.750,  5.000) = 18017 
    [ 5.000,  6.250) = 834 
    [ 6.250,  7.500) = 461 
    [ 7.500,  8.750) = 250 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     16.323 ms/op
     p(99.9990) =     17.659 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 5.343 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.280 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.012 ms/op
Iteration   1: 3.999 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  15.025 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   2: 3.990 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 22.019 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 4.065 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  18.744 ms/op
                 listUser·p0.9999: 21.243 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238896
  mean =      4.018 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2545 
    [ 2.500,  5.000) = 213741 
    [ 5.000,  7.500) = 20801 
    [ 7.500, 10.000) = 1218 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.509 ± 1.728  ops/ms
ClientGrpc.existUser                       thrpt       3  10.883 ± 2.252  ops/ms
ClientGrpc.getUser                         thrpt       3  10.308 ± 2.074  ops/ms
ClientGrpc.listUser                        thrpt       3   7.913 ± 1.107  ops/ms
ClientGrpc.createUser                       avgt       3   3.085 ± 0.971   ms/op
ClientGrpc.existUser                        avgt       3   2.936 ± 0.252   ms/op
ClientGrpc.getUser                          avgt       3   3.021 ± 0.200   ms/op
ClientGrpc.listUser                         avgt       3   3.970 ± 0.976   ms/op
ClientGrpc.createUser                     sample  313763   3.058 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.645           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.634           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.871           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.787           ms/op
ClientGrpc.existUser                      sample  326021   2.942 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.655           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.331           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.718           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.711           ms/op
ClientGrpc.getUser                        sample  310501   3.090 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.570           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.421           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.323           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.793           ms/op
ClientGrpc.listUser                       sample  238896   4.018 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.878           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.384           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.168           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.872           ms/op
