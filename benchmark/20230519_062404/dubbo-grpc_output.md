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
# Warmup Iteration   1: 4.017 ops/ms
# Warmup Iteration   2: 8.374 ops/ms
# Warmup Iteration   3: 9.897 ops/ms
Iteration   1: 9.836 ops/ms
Iteration   2: 10.361 ops/ms
Iteration   3: 10.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.220 ±(99.9%) 6.140 ops/ms [Average]
  (min, avg, max) = (9.836, 10.220, 10.463), stdev = 0.337
  CI (99.9%): [4.080, 16.359] (assumes normal distribution)


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
# Warmup Iteration   1: 6.956 ops/ms
# Warmup Iteration   2: 10.342 ops/ms
# Warmup Iteration   3: 10.941 ops/ms
Iteration   1: 10.977 ops/ms
Iteration   2: 10.947 ops/ms
Iteration   3: 11.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.994 ±(99.9%) 1.050 ops/ms [Average]
  (min, avg, max) = (10.947, 10.994, 11.058), stdev = 0.058
  CI (99.9%): [9.944, 12.044] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.029 ops/ms
# Warmup Iteration   2: 9.760 ops/ms
# Warmup Iteration   3: 10.171 ops/ms
Iteration   1: 10.455 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.468 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (10.455, 10.468, 10.490), stdev = 0.019
  CI (99.9%): [10.128, 10.809] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.477 ops/ms
# Warmup Iteration   2: 7.256 ops/ms
# Warmup Iteration   3: 7.938 ops/ms
Iteration   1: 7.772 ops/ms
Iteration   2: 8.057 ops/ms
Iteration   3: 7.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.893 ±(99.9%) 2.693 ops/ms [Average]
  (min, avg, max) = (7.772, 7.893, 8.057), stdev = 0.148
  CI (99.9%): [5.200, 10.586] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.429 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.003 ms/op
Iteration   1: 3.100 ±(99.9%) 0.002 ms/op
Iteration   2: 3.083 ±(99.9%) 0.002 ms/op
Iteration   3: 3.150 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.111 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.083, 3.111, 3.150), stdev = 0.035
  CI (99.9%): [2.481, 3.741] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.162 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.002 ms/op
Iteration   1: 2.933 ±(99.9%) 0.002 ms/op
Iteration   2: 2.895 ±(99.9%) 0.002 ms/op
Iteration   3: 2.949 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.926 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (2.895, 2.926, 2.949), stdev = 0.028
  CI (99.9%): [2.418, 3.433] (assumes normal distribution)


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
# Warmup Iteration   1: 4.558 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.002 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.100 ±(99.9%) 0.002 ms/op
Iteration   3: 3.186 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.112 ±(99.9%) 1.260 ms/op [Average]
  (min, avg, max) = (3.049, 3.112, 3.186), stdev = 0.069
  CI (99.9%): [1.852, 4.372] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.051 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.133 ±(99.9%) 0.012 ms/op
Iteration   1: 4.068 ±(99.9%) 0.029 ms/op
Iteration   2: 4.091 ±(99.9%) 0.011 ms/op
Iteration   3: 4.081 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.080 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (4.068, 4.080, 4.091), stdev = 0.012
  CI (99.9%): [3.867, 4.293] (assumes normal distribution)


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.008 ms/op
Iteration   1: 3.099 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  7.543 ms/op
                 createUser·p0.9999: 19.552 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  10.722 ms/op
                 createUser·p0.9999: 19.657 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  9.884 ms/op
                 createUser·p0.9999: 22.503 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308558
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18151 
    [ 2.500,  5.000) = 288007 
    [ 5.000,  7.500) = 1866 
    [ 7.500, 10.000) = 245 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =      9.574 ms/op
     p(99.9900) =     21.622 ms/op
     p(99.9990) =     23.653 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 2.892 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  7.479 ms/op
                 existUser·p0.9999: 11.992 ms/op
                 existUser·p1.00:   12.239 ms/op

Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  8.889 ms/op
                 existUser·p0.9999: 25.541 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.042 ms/op
                 existUser·p0.9999: 18.419 ms/op
                 existUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325123
  mean =      2.955 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32234 
    [ 2.500,  5.000) = 290525 
    [ 5.000,  7.500) = 2006 
    [ 7.500, 10.000) = 195 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      7.675 ms/op
     p(99.9900) =     19.274 ms/op
     p(99.9990) =     25.837 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.007 ms/op
Iteration   1: 3.141 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  10.568 ms/op
                 getUser·p0.9999: 23.521 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 19.362 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  8.061 ms/op
                 getUser·p0.9999: 22.505 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305016
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13245 
    [ 2.500,  5.000) = 289245 
    [ 5.000,  7.500) = 1913 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     23.853 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 6.224 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.012 ms/op
Iteration   1: 4.054 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 17.719 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   2: 4.162 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  18.333 ms/op
                 listUser·p0.9999: 31.073 ms/op
                 listUser·p1.00:   32.080 ms/op

Iteration   3: 4.079 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  18.206 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234180
  mean =      4.098 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1882 
    [ 2.500,  5.000) = 203723 
    [ 5.000,  7.500) = 26516 
    [ 7.500, 10.000) = 1496 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.366 ms/op
     p(99.9000) =     16.725 ms/op
     p(99.9900) =     30.723 ms/op
     p(99.9990) =     31.358 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.220 ± 6.140  ops/ms
ClientGrpc.existUser                       thrpt       3  10.994 ± 1.050  ops/ms
ClientGrpc.getUser                         thrpt       3  10.468 ± 0.340  ops/ms
ClientGrpc.listUser                        thrpt       3   7.893 ± 2.693  ops/ms
ClientGrpc.createUser                       avgt       3   3.111 ± 0.630   ms/op
ClientGrpc.existUser                        avgt       3   2.926 ± 0.507   ms/op
ClientGrpc.getUser                          avgt       3   3.112 ± 1.260   ms/op
ClientGrpc.listUser                         avgt       3   4.080 ± 0.213   ms/op
ClientGrpc.createUser                     sample  308558   3.111 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.713           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.574           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.622           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.757           ms/op
ClientGrpc.existUser                      sample  325123   2.955 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.672           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.694           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.675           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.274           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.952           ms/op
ClientGrpc.getUser                        sample  305016   3.145 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.773           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.940           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.765           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.643           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.888           ms/op
ClientGrpc.listUser                       sample  234180   4.098 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.053           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.366           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.725           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.723           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.080           ms/op
