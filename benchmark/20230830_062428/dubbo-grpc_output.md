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
# Warmup Iteration   1: 3.699 ops/ms
# Warmup Iteration   2: 8.440 ops/ms
# Warmup Iteration   3: 9.782 ops/ms
Iteration   1: 10.350 ops/ms
Iteration   2: 10.523 ops/ms
Iteration   3: 10.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.418 ±(99.9%) 1.674 ops/ms [Average]
  (min, avg, max) = (10.350, 10.418, 10.523), stdev = 0.092
  CI (99.9%): [8.744, 12.092] (assumes normal distribution)


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
# Warmup Iteration   1: 7.604 ops/ms
# Warmup Iteration   2: 10.468 ops/ms
# Warmup Iteration   3: 10.939 ops/ms
Iteration   1: 10.800 ops/ms
Iteration   2: 10.896 ops/ms
Iteration   3: 10.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.872 ±(99.9%) 1.143 ops/ms [Average]
  (min, avg, max) = (10.800, 10.872, 10.918), stdev = 0.063
  CI (99.9%): [9.729, 12.014] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.681 ops/ms
# Warmup Iteration   2: 9.776 ops/ms
# Warmup Iteration   3: 9.984 ops/ms
Iteration   1: 10.241 ops/ms
Iteration   2: 10.207 ops/ms
Iteration   3: 10.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.304 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (10.207, 10.304, 10.464), stdev = 0.140
  CI (99.9%): [7.750, 12.858] (assumes normal distribution)


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
# Warmup Iteration   1: 5.304 ops/ms
# Warmup Iteration   2: 7.516 ops/ms
# Warmup Iteration   3: 7.751 ops/ms
Iteration   1: 7.721 ops/ms
Iteration   2: 7.817 ops/ms
Iteration   3: 7.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.815 ±(99.9%) 1.696 ops/ms [Average]
  (min, avg, max) = (7.721, 7.815, 7.907), stdev = 0.093
  CI (99.9%): [6.119, 9.511] (assumes normal distribution)


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.004 ms/op
Iteration   1: 3.086 ±(99.9%) 0.003 ms/op
Iteration   2: 3.066 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.054 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.012, 3.054, 3.086), stdev = 0.038
  CI (99.9%): [2.355, 3.753] (assumes normal distribution)


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.002 ms/op
Iteration   1: 2.934 ±(99.9%) 0.003 ms/op
Iteration   2: 2.935 ±(99.9%) 0.002 ms/op
Iteration   3: 2.886 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.919 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (2.886, 2.919, 2.935), stdev = 0.028
  CI (99.9%): [2.408, 3.429] (assumes normal distribution)


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.003 ms/op
Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
Iteration   3: 3.079 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.071 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (3.048, 3.071, 3.086), stdev = 0.020
  CI (99.9%): [2.702, 3.440] (assumes normal distribution)


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
# Warmup Iteration   1: 5.354 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.019 ms/op
Iteration   1: 4.111 ±(99.9%) 0.038 ms/op
Iteration   2: 4.030 ±(99.9%) 0.024 ms/op
Iteration   3: 3.941 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.027 ±(99.9%) 1.555 ms/op [Average]
  (min, avg, max) = (3.941, 4.027, 4.111), stdev = 0.085
  CI (99.9%): [2.473, 5.582] (assumes normal distribution)


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.008 ms/op
Iteration   1: 3.042 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  7.625 ms/op
                 createUser·p0.9999: 22.069 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.039 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  11.600 ms/op
                 createUser·p0.9999: 22.281 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.866 ms/op
                 createUser·p0.999:  8.754 ms/op
                 createUser·p0.9999: 28.869 ms/op
                 createUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316732
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26206 
    [ 2.500,  5.000) = 287923 
    [ 5.000,  7.500) = 2048 
    [ 7.500, 10.000) = 268 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     27.831 ms/op
     p(99.9990) =     30.152 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.538 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.607 ms/op
                 existUser·p0.999:  8.107 ms/op
                 existUser·p0.9999: 12.887 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   2: 2.935 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  8.143 ms/op
                 existUser·p0.9999: 19.697 ms/op
                 existUser·p1.00:   19.956 ms/op

Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  11.099 ms/op
                 existUser·p0.9999: 19.424 ms/op
                 existUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322351
  mean =      2.976 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36021 
    [ 2.500,  5.000) = 283767 
    [ 5.000,  7.500) = 1790 
    [ 7.500, 10.000) = 510 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.801 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     19.260 ms/op
     p(99.9990) =     19.916 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  10.224 ms/op
                 getUser·p0.9999: 15.204 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  12.503 ms/op
                 getUser·p0.9999: 15.212 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  8.804 ms/op
                 getUser·p0.9999: 17.768 ms/op
                 getUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310994
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 422 
    [ 1.250,  2.500) = 17399 
    [ 2.500,  3.750) = 272177 
    [ 3.750,  5.000) = 18090 
    [ 5.000,  6.250) = 1282 
    [ 6.250,  7.500) = 846 
    [ 7.500,  8.750) = 300 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.924 ms/op
     p(99.9000) =     11.747 ms/op
     p(99.9900) =     17.003 ms/op
     p(99.9990) =     18.052 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 5.603 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.012 ms/op
Iteration   1: 4.088 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.125 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 20.682 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 4.042 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.888 ms/op
                 listUser·p0.9999: 22.979 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 4.039 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  16.204 ms/op
                 listUser·p0.9999: 31.625 ms/op
                 listUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236879
  mean =      4.056 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2608 
    [ 2.500,  5.000) = 211443 
    [ 5.000,  7.500) = 20875 
    [ 7.500, 10.000) = 1426 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     31.140 ms/op
     p(99.9990) =     33.379 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.418 ± 1.674  ops/ms
ClientGrpc.existUser                       thrpt       3  10.872 ± 1.143  ops/ms
ClientGrpc.getUser                         thrpt       3  10.304 ± 2.554  ops/ms
ClientGrpc.listUser                        thrpt       3   7.815 ± 1.696  ops/ms
ClientGrpc.createUser                       avgt       3   3.054 ± 0.699   ms/op
ClientGrpc.existUser                        avgt       3   2.919 ± 0.510   ms/op
ClientGrpc.getUser                          avgt       3   3.071 ± 0.369   ms/op
ClientGrpc.listUser                         avgt       3   4.027 ± 1.555   ms/op
ClientGrpc.createUser                     sample  316732   3.030 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.794           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.617           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.831           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.605           ms/op
ClientGrpc.existUser                      sample  322351   2.976 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.538           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.801           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.634           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.260           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.004           ms/op
ClientGrpc.getUser                        sample  310994   3.087 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.701           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.924           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.747           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.003           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.121           ms/op
ClientGrpc.listUser                       sample  236879   4.056 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.907           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.307           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.991           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.140           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.489           ms/op
