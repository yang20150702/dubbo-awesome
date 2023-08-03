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
# Warmup Iteration   1: 4.317 ops/ms
# Warmup Iteration   2: 9.305 ops/ms
# Warmup Iteration   3: 10.330 ops/ms
Iteration   1: 10.628 ops/ms
Iteration   2: 10.679 ops/ms
Iteration   3: 10.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.665 ±(99.9%) 0.590 ops/ms [Average]
  (min, avg, max) = (10.628, 10.665, 10.688), stdev = 0.032
  CI (99.9%): [10.075, 11.255] (assumes normal distribution)


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
# Warmup Iteration   1: 7.829 ops/ms
# Warmup Iteration   2: 10.820 ops/ms
# Warmup Iteration   3: 11.405 ops/ms
Iteration   1: 11.342 ops/ms
Iteration   2: 11.479 ops/ms
Iteration   3: 11.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.367 ±(99.9%) 1.862 ops/ms [Average]
  (min, avg, max) = (11.279, 11.367, 11.479), stdev = 0.102
  CI (99.9%): [9.505, 13.228] (assumes normal distribution)


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
# Warmup Iteration   1: 7.330 ops/ms
# Warmup Iteration   2: 10.206 ops/ms
# Warmup Iteration   3: 10.749 ops/ms
Iteration   1: 10.957 ops/ms
Iteration   2: 10.698 ops/ms
Iteration   3: 10.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.843 ±(99.9%) 2.402 ops/ms [Average]
  (min, avg, max) = (10.698, 10.843, 10.957), stdev = 0.132
  CI (99.9%): [8.440, 13.245] (assumes normal distribution)


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
# Warmup Iteration   1: 6.547 ops/ms
# Warmup Iteration   2: 8.062 ops/ms
# Warmup Iteration   3: 8.240 ops/ms
Iteration   1: 8.162 ops/ms
Iteration   2: 8.317 ops/ms
Iteration   3: 8.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.262 ±(99.9%) 1.585 ops/ms [Average]
  (min, avg, max) = (8.162, 8.262, 8.317), stdev = 0.087
  CI (99.9%): [6.677, 9.847] (assumes normal distribution)


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
# Warmup Iteration   1: 3.758 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.003 ms/op
Iteration   1: 2.963 ±(99.9%) 0.003 ms/op
Iteration   2: 2.986 ±(99.9%) 0.003 ms/op
Iteration   3: 2.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.968 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (2.955, 2.968, 2.986), stdev = 0.016
  CI (99.9%): [2.678, 3.258] (assumes normal distribution)


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
# Warmup Iteration   1: 3.691 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.908 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.806 ±(99.9%) 0.004 ms/op
Iteration   1: 2.873 ±(99.9%) 0.003 ms/op
Iteration   2: 2.868 ±(99.9%) 0.003 ms/op
Iteration   3: 2.825 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.855 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (2.825, 2.855, 2.873), stdev = 0.026
  CI (99.9%): [2.375, 3.335] (assumes normal distribution)


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.927 ±(99.9%) 0.003 ms/op
Iteration   1: 2.987 ±(99.9%) 0.002 ms/op
Iteration   2: 2.946 ±(99.9%) 0.003 ms/op
Iteration   3: 2.956 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.963 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (2.946, 2.963, 2.987), stdev = 0.022
  CI (99.9%): [2.565, 3.361] (assumes normal distribution)


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
# Warmup Iteration   1: 5.497 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.903 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.041 ms/op
Iteration   1: 3.688 ±(99.9%) 0.007 ms/op
Iteration   2: 3.832 ±(99.9%) 0.008 ms/op
Iteration   3: 3.876 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.799 ±(99.9%) 1.789 ms/op [Average]
  (min, avg, max) = (3.688, 3.799, 3.876), stdev = 0.098
  CI (99.9%): [2.010, 5.588] (assumes normal distribution)


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.007 ms/op
Iteration   1: 2.927 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.231 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  9.175 ms/op
                 createUser·p0.9999: 17.926 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   2: 2.953 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.470 ms/op
                 createUser·p0.9999: 15.297 ms/op
                 createUser·p1.00:   15.368 ms/op

Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.908 ms/op
                 createUser·p0.9999: 15.486 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325634
  mean =      2.947 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2248 
    [ 1.250,  2.500) = 31649 
    [ 2.500,  3.750) = 276714 
    [ 3.750,  5.000) = 13327 
    [ 5.000,  6.250) = 917 
    [ 6.250,  7.500) = 328 
    [ 7.500,  8.750) = 112 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.231 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     17.115 ms/op
     p(99.9990) =     18.047 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.859 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.927 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.801 ±(99.9%) 0.006 ms/op
Iteration   1: 2.916 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.195 ms/op
                 existUser·p0.999:  7.252 ms/op
                 existUser·p0.9999: 11.354 ms/op
                 existUser·p1.00:   11.485 ms/op

Iteration   2: 2.821 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  7.694 ms/op
                 existUser·p0.9999: 16.526 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   3: 2.844 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.218 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.638 ms/op
                 existUser·p0.9999: 15.141 ms/op
                 existUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335614
  mean =      2.860 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4160 
    [ 1.250,  2.500) = 51670 
    [ 2.500,  3.750) = 267210 
    [ 3.750,  5.000) = 11053 
    [ 5.000,  6.250) = 747 
    [ 6.250,  7.500) = 427 
    [ 7.500,  8.750) = 118 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.218 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.559 ms/op
     p(99.9900) =     15.717 ms/op
     p(99.9990) =     16.821 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.007 ms/op
Iteration   1: 2.972 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.690 ms/op
                 getUser·p0.9999: 11.231 ms/op
                 getUser·p1.00:   11.452 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.782 ms/op
                 getUser·p0.9999: 14.680 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.996 ms/op
                 getUser·p0.9999: 25.526 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322758
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30134 
    [ 2.500,  5.000) = 290790 
    [ 5.000,  7.500) = 1517 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =     22.689 ms/op
     p(99.9990) =     25.774 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.010 ms/op
Iteration   1: 3.810 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.797 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  11.927 ms/op
                 listUser·p0.9999: 17.911 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 3.862 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  15.179 ms/op
                 listUser·p0.9999: 23.730 ms/op
                 listUser·p1.00:   25.494 ms/op

Iteration   3: 3.886 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.308 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.130 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 19.417 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249027
  mean =      3.852 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5494 
    [ 2.500,  5.000) = 222897 
    [ 5.000,  7.500) = 19063 
    [ 7.500, 10.000) = 993 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.936 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     22.456 ms/op
     p(99.9990) =     25.364 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.665 ± 0.590  ops/ms
ClientGrpc.existUser                       thrpt       3  11.367 ± 1.862  ops/ms
ClientGrpc.getUser                         thrpt       3  10.843 ± 2.402  ops/ms
ClientGrpc.listUser                        thrpt       3   8.262 ± 1.585  ops/ms
ClientGrpc.createUser                       avgt       3   2.968 ± 0.290   ms/op
ClientGrpc.existUser                        avgt       3   2.855 ± 0.480   ms/op
ClientGrpc.getUser                          avgt       3   2.963 ± 0.398   ms/op
ClientGrpc.listUser                         avgt       3   3.799 ± 1.789   ms/op
ClientGrpc.createUser                     sample  325634   2.947 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.231           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.937           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.441           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.011           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.115           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.121           ms/op
ClientGrpc.existUser                      sample  335614   2.860 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.218           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.559           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.717           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  322758   2.973 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.699           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.487           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.689           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.887           ms/op
ClientGrpc.listUser                       sample  249027   3.852 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.308           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.695           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.936           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.385           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.456           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.494           ms/op
