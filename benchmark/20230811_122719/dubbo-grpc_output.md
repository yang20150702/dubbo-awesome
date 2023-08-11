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
# Warmup Iteration   1: 4.486 ops/ms
# Warmup Iteration   2: 9.458 ops/ms
# Warmup Iteration   3: 10.307 ops/ms
Iteration   1: 10.577 ops/ms
Iteration   2: 10.647 ops/ms
Iteration   3: 10.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.575 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (10.500, 10.575, 10.647), stdev = 0.073
  CI (99.9%): [9.242, 11.908] (assumes normal distribution)


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
# Warmup Iteration   1: 7.845 ops/ms
# Warmup Iteration   2: 10.715 ops/ms
# Warmup Iteration   3: 10.936 ops/ms
Iteration   1: 11.054 ops/ms
Iteration   2: 11.087 ops/ms
Iteration   3: 11.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.047 ±(99.9%) 0.796 ops/ms [Average]
  (min, avg, max) = (11.001, 11.047, 11.087), stdev = 0.044
  CI (99.9%): [10.252, 11.843] (assumes normal distribution)


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
# Warmup Iteration   1: 7.547 ops/ms
# Warmup Iteration   2: 10.344 ops/ms
# Warmup Iteration   3: 10.404 ops/ms
Iteration   1: 10.714 ops/ms
Iteration   2: 10.631 ops/ms
Iteration   3: 10.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.646 ±(99.9%) 1.115 ops/ms [Average]
  (min, avg, max) = (10.594, 10.646, 10.714), stdev = 0.061
  CI (99.9%): [9.532, 11.761] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.321 ops/ms
# Warmup Iteration   2: 7.744 ops/ms
# Warmup Iteration   3: 8.133 ops/ms
Iteration   1: 8.143 ops/ms
Iteration   2: 8.276 ops/ms
Iteration   3: 8.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.220 ±(99.9%) 1.257 ops/ms [Average]
  (min, avg, max) = (8.143, 8.220, 8.276), stdev = 0.069
  CI (99.9%): [6.962, 9.477] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.003 ms/op
Iteration   1: 3.022 ±(99.9%) 0.011 ms/op
Iteration   2: 3.001 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.022 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.001, 3.022, 3.044), stdev = 0.021
  CI (99.9%): [2.635, 3.410] (assumes normal distribution)


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
# Warmup Iteration   1: 3.526 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.941 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.005 ms/op
Iteration   1: 2.892 ±(99.9%) 0.003 ms/op
Iteration   2: 2.857 ±(99.9%) 0.003 ms/op
Iteration   3: 2.910 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.886 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (2.857, 2.886, 2.910), stdev = 0.027
  CI (99.9%): [2.398, 3.374] (assumes normal distribution)


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.002 ms/op
Iteration   1: 3.043 ±(99.9%) 0.002 ms/op
Iteration   2: 2.995 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.006 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (2.979, 3.006, 3.043), stdev = 0.033
  CI (99.9%): [2.402, 3.609] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.149 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.015 ms/op
Iteration   1: 3.905 ±(99.9%) 0.031 ms/op
Iteration   2: 3.921 ±(99.9%) 0.024 ms/op
Iteration   3: 3.870 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.899 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.870, 3.899, 3.921), stdev = 0.026
  CI (99.9%): [3.427, 4.370] (assumes normal distribution)


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
# Warmup Iteration   1: 3.910 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.429 ms/op
                 createUser·p0.999:  7.848 ms/op
                 createUser·p0.9999: 16.031 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  7.937 ms/op
                 createUser·p0.9999: 16.536 ms/op
                 createUser·p1.00:   16.744 ms/op

Iteration   3: 3.054 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  9.598 ms/op
                 createUser·p0.9999: 26.804 ms/op
                 createUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317762
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23552 
    [ 2.500,  5.000) = 292424 
    [ 5.000,  7.500) = 1267 
    [ 7.500, 10.000) = 294 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     26.131 ms/op
     p(99.9990) =     27.028 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.005 ms/op
Iteration   1: 2.863 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.572 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  8.151 ms/op
                 existUser·p0.9999: 11.299 ms/op
                 existUser·p1.00:   11.551 ms/op

Iteration   2: 2.889 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.933 ms/op
                 existUser·p0.9999: 14.925 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   3: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.037 ms/op
                 existUser·p0.9999: 18.325 ms/op
                 existUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331322
  mean =      2.898 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2378 
    [ 1.250,  2.500) = 44717 
    [ 2.500,  3.750) = 271224 
    [ 3.750,  5.000) = 11534 
    [ 5.000,  6.250) = 764 
    [ 6.250,  7.500) = 389 
    [ 7.500,  8.750) = 126 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =     15.198 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.484 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  7.986 ms/op
                 getUser·p0.9999: 15.563 ms/op
                 getUser·p1.00:   15.860 ms/op

Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  8.473 ms/op
                 getUser·p0.9999: 25.477 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  8.493 ms/op
                 getUser·p0.9999: 33.218 ms/op
                 getUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318306
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26690 
    [ 2.500,  5.000) = 289697 
    [ 5.000,  7.500) = 1399 
    [ 7.500, 10.000) = 296 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.293 ms/op
     p(99.9900) =     31.883 ms/op
     p(99.9990) =     33.385 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.012 ms/op
Iteration   1: 3.896 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.587 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.053 ms/op
                 listUser·p0.9999: 20.295 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   2: 3.849 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.724 ms/op
                 listUser·p0.9999: 23.643 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   3: 3.932 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 17.878 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246539
  mean =      3.892 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5278 
    [ 2.500,  5.000) = 220843 
    [ 5.000,  7.500) = 19026 
    [ 7.500, 10.000) = 913 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.459 ms/op
     p(99.9900) =     21.933 ms/op
     p(99.9990) =     24.334 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.575 ± 1.333  ops/ms
ClientGrpc.existUser                       thrpt       3  11.047 ± 0.796  ops/ms
ClientGrpc.getUser                         thrpt       3  10.646 ± 1.115  ops/ms
ClientGrpc.listUser                        thrpt       3   8.220 ± 1.257  ops/ms
ClientGrpc.createUser                       avgt       3   3.022 ± 0.388   ms/op
ClientGrpc.existUser                        avgt       3   2.886 ± 0.488   ms/op
ClientGrpc.getUser                          avgt       3   3.006 ± 0.603   ms/op
ClientGrpc.listUser                         avgt       3   3.899 ± 0.472   ms/op
ClientGrpc.createUser                     sample  317762   3.024 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.558           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.405           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.131           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.622           ms/op
ClientGrpc.existUser                      sample  331322   2.898 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.572           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.438           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.198           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.514           ms/op
ClientGrpc.getUser                        sample  318306   3.014 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.484           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.293           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.883           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.456           ms/op
ClientGrpc.listUser                       sample  246539   3.892 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.124           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.459           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.933           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.543           ms/op
