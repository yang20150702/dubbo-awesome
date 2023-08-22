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
# Warmup Iteration   1: 4.017 ops/ms
# Warmup Iteration   2: 8.653 ops/ms
# Warmup Iteration   3: 9.731 ops/ms
Iteration   1: 9.945 ops/ms
Iteration   2: 10.373 ops/ms
Iteration   3: 10.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.258 ±(99.9%) 5.013 ops/ms [Average]
  (min, avg, max) = (9.945, 10.258, 10.457), stdev = 0.275
  CI (99.9%): [5.245, 15.271] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.340 ops/ms
# Warmup Iteration   2: 10.514 ops/ms
# Warmup Iteration   3: 10.829 ops/ms
Iteration   1: 10.937 ops/ms
Iteration   2: 11.119 ops/ms
Iteration   3: 11.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.025 ±(99.9%) 1.668 ops/ms [Average]
  (min, avg, max) = (10.937, 11.025, 11.119), stdev = 0.091
  CI (99.9%): [9.357, 12.692] (assumes normal distribution)


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
# Warmup Iteration   1: 6.747 ops/ms
# Warmup Iteration   2: 9.729 ops/ms
# Warmup Iteration   3: 10.135 ops/ms
Iteration   1: 10.131 ops/ms
Iteration   2: 10.344 ops/ms
Iteration   3: 10.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.317 ±(99.9%) 3.183 ops/ms [Average]
  (min, avg, max) = (10.131, 10.317, 10.477), stdev = 0.174
  CI (99.9%): [7.134, 13.500] (assumes normal distribution)


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
# Warmup Iteration   1: 5.024 ops/ms
# Warmup Iteration   2: 7.664 ops/ms
# Warmup Iteration   3: 7.970 ops/ms
Iteration   1: 7.876 ops/ms
Iteration   2: 8.050 ops/ms
Iteration   3: 7.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.957 ±(99.9%) 1.601 ops/ms [Average]
  (min, avg, max) = (7.876, 7.957, 8.050), stdev = 0.088
  CI (99.9%): [6.356, 9.558] (assumes normal distribution)


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
# Warmup Iteration   1: 4.355 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.003 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
Iteration   2: 2.977 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.030 ±(99.9%) 0.850 ms/op [Average]
  (min, avg, max) = (2.977, 3.030, 3.063), stdev = 0.047
  CI (99.9%): [2.181, 3.880] (assumes normal distribution)


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.003 ms/op
Iteration   1: 2.952 ±(99.9%) 0.003 ms/op
Iteration   2: 2.953 ±(99.9%) 0.003 ms/op
Iteration   3: 2.945 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.950 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (2.945, 2.950, 2.953), stdev = 0.004
  CI (99.9%): [2.873, 3.026] (assumes normal distribution)


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
# Warmup Iteration   1: 4.349 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.002 ms/op
Iteration   1: 3.100 ±(99.9%) 0.003 ms/op
Iteration   2: 3.108 ±(99.9%) 0.003 ms/op
Iteration   3: 3.086 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.098 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (3.086, 3.098, 3.108), stdev = 0.011
  CI (99.9%): [2.889, 3.307] (assumes normal distribution)


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
# Warmup Iteration   1: 5.623 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.016 ms/op
Iteration   1: 4.036 ±(99.9%) 0.015 ms/op
Iteration   2: 3.998 ±(99.9%) 0.024 ms/op
Iteration   3: 4.069 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.034 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (3.998, 4.034, 4.069), stdev = 0.036
  CI (99.9%): [3.384, 4.684] (assumes normal distribution)


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
# Warmup Iteration   1: 4.525 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 3.149 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  9.919 ms/op
                 createUser·p0.9999: 18.766 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.700 ms/op
                 createUser·p0.999:  8.652 ms/op
                 createUser·p0.9999: 22.990 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   3: 3.124 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  13.848 ms/op
                 createUser·p0.9999: 26.010 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307882
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17764 
    [ 2.500,  5.000) = 286936 
    [ 5.000,  7.500) = 2428 
    [ 7.500, 10.000) = 434 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =     10.338 ms/op
     p(99.9900) =     25.245 ms/op
     p(99.9990) =     26.245 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.007 ms/op
Iteration   1: 2.955 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.414 ms/op
                 existUser·p0.9999: 12.193 ms/op
                 existUser·p1.00:   12.337 ms/op

Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.530 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  8.321 ms/op
                 existUser·p0.9999: 13.965 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 3.007 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  12.830 ms/op
                 existUser·p0.9999: 18.088 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320962
  mean =      2.992 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 839 
    [ 1.250,  2.500) = 30786 
    [ 2.500,  3.750) = 274293 
    [ 3.750,  5.000) = 13159 
    [ 5.000,  6.250) = 765 
    [ 6.250,  7.500) = 570 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     17.296 ms/op
     p(99.9990) =     18.179 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 4.197 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
Iteration   1: 3.068 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  9.995 ms/op
                 getUser·p0.9999: 20.597 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  7.471 ms/op
                 getUser·p0.9999: 18.822 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.603 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  7.712 ms/op
                 getUser·p0.9999: 24.543 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312067
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21907 
    [ 2.500,  5.000) = 287509 
    [ 5.000,  7.500) = 2136 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     24.797 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.355 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.013 ms/op
Iteration   1: 4.002 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 3.975 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  16.679 ms/op
                 listUser·p0.9999: 26.772 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   3: 4.083 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  19.518 ms/op
                 listUser·p0.9999: 26.580 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238988
  mean =      4.019 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3108 
    [ 2.500,  5.000) = 207899 
    [ 5.000,  7.500) = 25940 
    [ 7.500, 10.000) = 1453 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.074 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.258 ± 5.013  ops/ms
ClientGrpc.existUser                       thrpt       3  11.025 ± 1.668  ops/ms
ClientGrpc.getUser                         thrpt       3  10.317 ± 3.183  ops/ms
ClientGrpc.listUser                        thrpt       3   7.957 ± 1.601  ops/ms
ClientGrpc.createUser                       avgt       3   3.030 ± 0.850   ms/op
ClientGrpc.existUser                        avgt       3   2.950 ± 0.077   ms/op
ClientGrpc.getUser                          avgt       3   3.098 ± 0.209   ms/op
ClientGrpc.listUser                         avgt       3   4.034 ± 0.650   ms/op
ClientGrpc.createUser                     sample  307882   3.118 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.774           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.338           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.245           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.378           ms/op
ClientGrpc.existUser                      sample  320962   2.992 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.530           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.798           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.296           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.645           ms/op
ClientGrpc.getUser                        sample  312067   3.076 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.603           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.882           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.380           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.643           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.936           ms/op
ClientGrpc.listUser                       sample  238988   4.019 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.771           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.315           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.464           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.345           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
