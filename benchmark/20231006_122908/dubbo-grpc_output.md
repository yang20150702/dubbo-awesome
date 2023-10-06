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
# Warmup Iteration   1: 4.492 ops/ms
# Warmup Iteration   2: 9.213 ops/ms
# Warmup Iteration   3: 9.980 ops/ms
Iteration   1: 10.226 ops/ms
Iteration   2: 10.341 ops/ms
Iteration   3: 10.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.328 ±(99.9%) 1.769 ops/ms [Average]
  (min, avg, max) = (10.226, 10.328, 10.418), stdev = 0.097
  CI (99.9%): [8.560, 12.097] (assumes normal distribution)


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
# Warmup Iteration   1: 7.625 ops/ms
# Warmup Iteration   2: 10.600 ops/ms
# Warmup Iteration   3: 10.826 ops/ms
Iteration   1: 10.523 ops/ms
Iteration   2: 10.856 ops/ms
Iteration   3: 10.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.723 ±(99.9%) 3.208 ops/ms [Average]
  (min, avg, max) = (10.523, 10.723, 10.856), stdev = 0.176
  CI (99.9%): [7.515, 13.930] (assumes normal distribution)


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
# Warmup Iteration   1: 7.045 ops/ms
# Warmup Iteration   2: 10.052 ops/ms
# Warmup Iteration   3: 10.061 ops/ms
Iteration   1: 10.322 ops/ms
Iteration   2: 10.243 ops/ms
Iteration   3: 10.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.293 ±(99.9%) 0.787 ops/ms [Average]
  (min, avg, max) = (10.243, 10.293, 10.322), stdev = 0.043
  CI (99.9%): [9.506, 11.079] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.724 ops/ms
# Warmup Iteration   2: 8.091 ops/ms
# Warmup Iteration   3: 8.201 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 8.252 ops/ms
Iteration   3: 8.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.299 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (8.252, 8.299, 8.387), stdev = 0.076
  CI (99.9%): [6.912, 9.686] (assumes normal distribution)


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
# Warmup Iteration   1: 4.183 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.004 ms/op
Iteration   1: 3.088 ±(99.9%) 0.010 ms/op
Iteration   2: 3.111 ±(99.9%) 0.004 ms/op
Iteration   3: 3.115 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.105 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (3.088, 3.105, 3.115), stdev = 0.015
  CI (99.9%): [2.835, 3.374] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.974 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 2.874 ±(99.9%) 0.009 ms/op
Iteration   3: 2.962 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.957 ±(99.9%) 1.462 ms/op [Average]
  (min, avg, max) = (2.874, 2.957, 3.034), stdev = 0.080
  CI (99.9%): [1.495, 4.419] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.003 ms/op
Iteration   2: 3.120 ±(99.9%) 0.004 ms/op
Iteration   3: 3.027 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.067 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (3.027, 3.067, 3.120), stdev = 0.048
  CI (99.9%): [2.198, 3.937] (assumes normal distribution)


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
# Warmup Iteration   1: 5.270 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.035 ms/op
Iteration   1: 3.866 ±(99.9%) 0.024 ms/op
Iteration   2: 3.796 ±(99.9%) 0.018 ms/op
Iteration   3: 3.821 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.828 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (3.796, 3.828, 3.866), stdev = 0.036
  CI (99.9%): [3.173, 4.482] (assumes normal distribution)


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 3.127 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.848 ms/op
                 createUser·p0.9999: 12.208 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.097 ms/op
                 createUser·p0.9999: 13.402 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   3: 3.042 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  11.506 ms/op
                 createUser·p0.9999: 22.265 ms/op
                 createUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310044
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17839 
    [ 2.500,  5.000) = 290287 
    [ 5.000,  7.500) = 1380 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     18.988 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.526 ms/op
                 existUser·p0.9999: 17.992 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  8.981 ms/op
                 existUser·p0.9999: 27.106 ms/op
                 existUser·p1.00:   27.787 ms/op

Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  11.806 ms/op
                 existUser·p0.9999: 16.672 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322138
  mean =      2.979 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24823 
    [ 2.500,  5.000) = 295829 
    [ 5.000,  7.500) = 1089 
    [ 7.500, 10.000) = 146 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.208 ms/op
     p(99.9900) =     17.983 ms/op
     p(99.9990) =     27.511 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.084 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.006 ms/op
Iteration   1: 3.110 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  9.257 ms/op
                 getUser·p0.9999: 24.656 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  12.590 ms/op
                 getUser·p0.9999: 15.286 ms/op
                 getUser·p1.00:   16.646 ms/op

Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.595 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  8.070 ms/op
                 getUser·p0.9999: 15.876 ms/op
                 getUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313769
  mean =      3.057 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17150 
    [ 2.500,  5.000) = 294777 
    [ 5.000,  7.500) = 1357 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.884 ms/op
     p(99.9900) =     15.985 ms/op
     p(99.9990) =     25.517 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 5.586 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
Iteration   1: 3.826 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  19.291 ms/op
                 listUser·p0.9999: 26.977 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   2: 3.849 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.657 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   3: 3.871 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  16.276 ms/op
                 listUser·p0.9999: 25.878 ms/op
                 listUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249329
  mean =      3.849 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6083 
    [ 2.500,  5.000) = 227002 
    [ 5.000,  7.500) = 15162 
    [ 7.500, 10.000) = 490 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     16.297 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     27.707 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.328 ± 1.769  ops/ms
ClientGrpc.existUser                       thrpt       3  10.723 ± 3.208  ops/ms
ClientGrpc.getUser                         thrpt       3  10.293 ± 0.787  ops/ms
ClientGrpc.listUser                        thrpt       3   8.299 ± 1.387  ops/ms
ClientGrpc.createUser                       avgt       3   3.105 ± 0.270   ms/op
ClientGrpc.existUser                        avgt       3   2.957 ± 1.462   ms/op
ClientGrpc.getUser                          avgt       3   3.067 ± 0.869   ms/op
ClientGrpc.listUser                         avgt       3   3.828 ± 0.655   ms/op
ClientGrpc.createUser                     sample  310044   3.094 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.603           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.060           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.988           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.577           ms/op
ClientGrpc.existUser                      sample  322138   2.979 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.208           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.983           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.787           ms/op
ClientGrpc.getUser                        sample  313769   3.057 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.595           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.884           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.985           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.657           ms/op
ClientGrpc.listUser                       sample  249329   3.849 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.024           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.350           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.554           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.297           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.756           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.853           ms/op
