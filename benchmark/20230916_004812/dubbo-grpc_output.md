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
# Warmup Iteration   1: 4.490 ops/ms
# Warmup Iteration   2: 9.404 ops/ms
# Warmup Iteration   3: 9.968 ops/ms
Iteration   1: 10.203 ops/ms
Iteration   2: 10.420 ops/ms
Iteration   3: 10.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.344 ±(99.9%) 2.243 ops/ms [Average]
  (min, avg, max) = (10.203, 10.344, 10.420), stdev = 0.123
  CI (99.9%): [8.101, 12.588] (assumes normal distribution)


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
# Warmup Iteration   1: 7.529 ops/ms
# Warmup Iteration   2: 10.310 ops/ms
# Warmup Iteration   3: 10.516 ops/ms
Iteration   1: 10.502 ops/ms
Iteration   2: 10.861 ops/ms
Iteration   3: 10.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.665 ±(99.9%) 3.312 ops/ms [Average]
  (min, avg, max) = (10.502, 10.665, 10.861), stdev = 0.182
  CI (99.9%): [7.353, 13.976] (assumes normal distribution)


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
# Warmup Iteration   1: 7.325 ops/ms
# Warmup Iteration   2: 10.178 ops/ms
# Warmup Iteration   3: 10.232 ops/ms
Iteration   1: 10.385 ops/ms
Iteration   2: 10.311 ops/ms
Iteration   3: 10.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.361 ±(99.9%) 0.780 ops/ms [Average]
  (min, avg, max) = (10.311, 10.361, 10.386), stdev = 0.043
  CI (99.9%): [9.580, 11.141] (assumes normal distribution)


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
# Warmup Iteration   1: 7.067 ops/ms
# Warmup Iteration   2: 7.880 ops/ms
# Warmup Iteration   3: 8.120 ops/ms
Iteration   1: 8.330 ops/ms
Iteration   2: 8.193 ops/ms
Iteration   3: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.251 ±(99.9%) 1.294 ops/ms [Average]
  (min, avg, max) = (8.193, 8.251, 8.330), stdev = 0.071
  CI (99.9%): [6.957, 9.545] (assumes normal distribution)


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.002 ms/op
Iteration   1: 3.106 ±(99.9%) 0.003 ms/op
Iteration   2: 3.131 ±(99.9%) 0.001 ms/op
Iteration   3: 3.133 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.123 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.106, 3.123, 3.133), stdev = 0.015
  CI (99.9%): [2.854, 3.392] (assumes normal distribution)


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
# Warmup Iteration   1: 3.888 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.003 ms/op
Iteration   1: 2.947 ±(99.9%) 0.003 ms/op
Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
Iteration   3: 2.934 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.993 ±(99.9%) 1.677 ms/op [Average]
  (min, avg, max) = (2.934, 2.993, 3.099), stdev = 0.092
  CI (99.9%): [1.316, 4.670] (assumes normal distribution)


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.002 ms/op
Iteration   1: 3.028 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.002 ms/op
Iteration   3: 3.176 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.078 ±(99.9%) 1.560 ms/op [Average]
  (min, avg, max) = (3.028, 3.078, 3.176), stdev = 0.085
  CI (99.9%): [1.518, 4.637] (assumes normal distribution)


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
# Warmup Iteration   1: 4.731 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.020 ms/op
Iteration   1: 3.893 ±(99.9%) 0.030 ms/op
Iteration   2: 3.794 ±(99.9%) 0.029 ms/op
Iteration   3: 3.792 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.826 ±(99.9%) 1.046 ms/op [Average]
  (min, avg, max) = (3.792, 3.826, 3.893), stdev = 0.057
  CI (99.9%): [2.780, 4.873] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
Iteration   1: 3.088 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.650 ms/op
                 createUser·p0.9999: 14.527 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.520 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  10.191 ms/op
                 createUser·p0.9999: 15.254 ms/op
                 createUser·p1.00:   16.581 ms/op

Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  9.193 ms/op
                 createUser·p0.9999: 17.826 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311372
  mean =      3.085 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 625 
    [ 1.250,  2.500) = 10923 
    [ 2.500,  3.750) = 281346 
    [ 3.750,  5.000) = 16882 
    [ 5.000,  6.250) = 844 
    [ 6.250,  7.500) = 321 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.776 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     18.175 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 3.568 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.005 ms/op
Iteration   1: 3.020 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  6.604 ms/op
                 existUser·p0.9999: 11.328 ms/op
                 existUser·p1.00:   11.616 ms/op

Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  10.866 ms/op
                 existUser·p0.9999: 16.199 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.891 ms/op
                 existUser·p0.9999: 16.394 ms/op
                 existUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319160
  mean =      3.008 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1474 
    [ 1.250,  2.500) = 21786 
    [ 2.500,  3.750) = 280515 
    [ 3.750,  5.000) = 14217 
    [ 5.000,  6.250) = 609 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.379 ms/op
     p(99.9900) =     16.026 ms/op
     p(99.9990) =     16.804 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.006 ms/op
Iteration   1: 3.177 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.145 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 13.417 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.163 ms/op
                 getUser·p0.9999: 14.711 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 3.080 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  8.364 ms/op
                 getUser·p0.9999: 14.828 ms/op
                 getUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306776
  mean =      3.128 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 645 
    [ 1.250,  2.500) = 9154 
    [ 2.500,  3.750) = 269296 
    [ 3.750,  5.000) = 25580 
    [ 5.000,  6.250) = 1359 
    [ 6.250,  7.500) = 379 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      7.966 ms/op
     p(99.9900) =     14.669 ms/op
     p(99.9990) =     15.198 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.009 ms/op
Iteration   1: 3.897 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  12.262 ms/op
                 listUser·p0.9999: 15.103 ms/op
                 listUser·p1.00:   15.909 ms/op

Iteration   2: 3.928 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 18.144 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 3.875 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.726 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  15.214 ms/op
                 listUser·p0.9999: 18.571 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246331
  mean =      3.900 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 2708 
    [ 2.500,  3.750) = 101559 
    [ 3.750,  5.000) = 129496 
    [ 5.000,  6.250) = 8251 
    [ 6.250,  7.500) = 3417 
    [ 7.500,  8.750) = 312 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     19.023 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.344 ± 2.243  ops/ms
ClientGrpc.existUser                       thrpt       3  10.665 ± 3.312  ops/ms
ClientGrpc.getUser                         thrpt       3  10.361 ± 0.780  ops/ms
ClientGrpc.listUser                        thrpt       3   8.251 ± 1.294  ops/ms
ClientGrpc.createUser                       avgt       3   3.123 ± 0.269   ms/op
ClientGrpc.existUser                        avgt       3   2.993 ± 1.677   ms/op
ClientGrpc.getUser                          avgt       3   3.078 ± 1.560   ms/op
ClientGrpc.listUser                         avgt       3   3.826 ± 1.046   ms/op
ClientGrpc.createUser                     sample  311372   3.085 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.520           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.776           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.908           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.317           ms/op
ClientGrpc.existUser                      sample  319160   3.008 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.581           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.379           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.026           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.908           ms/op
ClientGrpc.getUser                        sample  306776   3.128 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.699           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.920           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.966           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.669           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.039           ms/op
ClientGrpc.listUser                       sample  246331   3.900 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.726           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.334           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.074           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.350           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.137           ms/op
