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
# Warmup Iteration   1: 3.969 ops/ms
# Warmup Iteration   2: 8.623 ops/ms
# Warmup Iteration   3: 10.106 ops/ms
Iteration   1: 10.331 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 10.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.321 ±(99.9%) 0.345 ops/ms [Average]
  (min, avg, max) = (10.299, 10.321, 10.333), stdev = 0.019
  CI (99.9%): [9.976, 10.666] (assumes normal distribution)


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
# Warmup Iteration   1: 7.188 ops/ms
# Warmup Iteration   2: 10.303 ops/ms
# Warmup Iteration   3: 10.763 ops/ms
Iteration   1: 11.280 ops/ms
Iteration   2: 10.973 ops/ms
Iteration   3: 10.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.042 ±(99.9%) 3.877 ops/ms [Average]
  (min, avg, max) = (10.872, 11.042, 11.280), stdev = 0.212
  CI (99.9%): [7.165, 14.919] (assumes normal distribution)


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
# Warmup Iteration   1: 7.436 ops/ms
# Warmup Iteration   2: 9.743 ops/ms
# Warmup Iteration   3: 10.324 ops/ms
Iteration   1: 10.319 ops/ms
Iteration   2: 10.204 ops/ms
Iteration   3: 10.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.242 ±(99.9%) 1.209 ops/ms [Average]
  (min, avg, max) = (10.204, 10.242, 10.319), stdev = 0.066
  CI (99.9%): [9.033, 11.452] (assumes normal distribution)


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
# Warmup Iteration   1: 4.923 ops/ms
# Warmup Iteration   2: 7.355 ops/ms
# Warmup Iteration   3: 7.841 ops/ms
Iteration   1: 7.738 ops/ms
Iteration   2: 7.733 ops/ms
Iteration   3: 7.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.783 ±(99.9%) 1.492 ops/ms [Average]
  (min, avg, max) = (7.733, 7.783, 7.877), stdev = 0.082
  CI (99.9%): [6.291, 9.275] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.002 ms/op
Iteration   1: 3.149 ±(99.9%) 0.003 ms/op
Iteration   2: 3.118 ±(99.9%) 0.001 ms/op
Iteration   3: 3.051 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.106 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (3.051, 3.106, 3.149), stdev = 0.050
  CI (99.9%): [2.189, 4.022] (assumes normal distribution)


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.002 ms/op
Iteration   1: 2.903 ±(99.9%) 0.003 ms/op
Iteration   2: 2.931 ±(99.9%) 0.003 ms/op
Iteration   3: 2.920 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.918 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.903, 2.918, 2.931), stdev = 0.014
  CI (99.9%): [2.659, 3.177] (assumes normal distribution)


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
# Warmup Iteration   1: 4.186 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.003 ms/op
Iteration   1: 3.069 ±(99.9%) 0.003 ms/op
Iteration   2: 3.062 ±(99.9%) 0.002 ms/op
Iteration   3: 3.068 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.067 ±(99.9%) 0.067 ms/op [Average]
  (min, avg, max) = (3.062, 3.067, 3.069), stdev = 0.004
  CI (99.9%): [3.000, 3.134] (assumes normal distribution)


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
# Warmup Iteration   1: 4.847 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.027 ms/op
Iteration   1: 4.145 ±(99.9%) 0.019 ms/op
Iteration   2: 4.124 ±(99.9%) 0.010 ms/op
Iteration   3: 4.074 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.114 ±(99.9%) 0.669 ms/op [Average]
  (min, avg, max) = (4.074, 4.114, 4.145), stdev = 0.037
  CI (99.9%): [3.445, 4.783] (assumes normal distribution)


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
# Warmup Iteration   1: 4.695 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.482 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  7.207 ms/op
                 createUser·p0.9999: 16.523 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.869 ms/op
                 createUser·p0.9999: 14.959 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.492 ms/op
                 createUser·p0.999:  9.221 ms/op
                 createUser·p0.9999: 26.688 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311501
  mean =      3.080 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13314 
    [ 2.500,  5.000) = 296687 
    [ 5.000,  7.500) = 1162 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.619 ms/op
     p(99.9900) =     24.538 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 4.308 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.005 ms/op
Iteration   1: 2.915 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  5.994 ms/op
                 existUser·p0.9999: 13.681 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.957 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  6.729 ms/op
                 existUser·p0.9999: 15.751 ms/op
                 existUser·p1.00:   16.105 ms/op

Iteration   3: 2.965 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.018 ms/op
                 existUser·p0.999:  6.697 ms/op
                 existUser·p0.9999: 17.506 ms/op
                 existUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325886
  mean =      2.945 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2548 
    [ 1.250,  2.500) = 19883 
    [ 2.500,  3.750) = 296672 
    [ 3.750,  5.000) = 6139 
    [ 5.000,  6.250) = 284 
    [ 6.250,  7.500) = 189 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 61 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =      6.481 ms/op
     p(99.9900) =     17.053 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 4.477 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.006 ms/op
Iteration   1: 3.102 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.234 ms/op
                 getUser·p0.9999: 12.846 ms/op
                 getUser·p1.00:   13.124 ms/op

Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.345 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.616 ms/op
                 getUser·p0.999:  7.856 ms/op
                 getUser·p0.9999: 14.112 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  9.213 ms/op
                 getUser·p0.9999: 18.777 ms/op
                 getUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310103
  mean =      3.094 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16435 
    [ 2.500,  5.000) = 292005 
    [ 5.000,  7.500) = 1335 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.664 ms/op
     p(99.9900) =     18.513 ms/op
     p(99.9990) =     19.480 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 4.819 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.012 ms/op
Iteration   1: 4.109 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  15.236 ms/op
                 listUser·p0.9999: 19.471 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 4.125 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  14.641 ms/op
                 listUser·p0.9999: 16.667 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 4.163 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  17.337 ms/op
                 listUser·p0.9999: 20.518 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232165
  mean =      4.132 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2470 
    [ 2.500,  5.000) = 203089 
    [ 5.000,  7.500) = 24734 
    [ 7.500, 10.000) = 1314 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     19.195 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.321 ± 0.345  ops/ms
ClientGrpc.existUser                       thrpt       3  11.042 ± 3.877  ops/ms
ClientGrpc.getUser                         thrpt       3  10.242 ± 1.209  ops/ms
ClientGrpc.listUser                        thrpt       3   7.783 ± 1.492  ops/ms
ClientGrpc.createUser                       avgt       3   3.106 ± 0.916   ms/op
ClientGrpc.existUser                        avgt       3   2.918 ± 0.259   ms/op
ClientGrpc.getUser                          avgt       3   3.067 ± 0.067   ms/op
ClientGrpc.listUser                         avgt       3   4.114 ± 0.669   ms/op
ClientGrpc.createUser                     sample  311501   3.080 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.888           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.619           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.538           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.099           ms/op
ClientGrpc.existUser                      sample  325886   2.945 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.586           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.022           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.481           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.053           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.596           ms/op
ClientGrpc.getUser                        sample  310103   3.094 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.345           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.664           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.513           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.218           ms/op
ClientGrpc.listUser                       sample  232165   4.132 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.053           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.106           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.195           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.823           ms/op
