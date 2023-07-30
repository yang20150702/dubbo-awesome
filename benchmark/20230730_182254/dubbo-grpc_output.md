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
# Warmup Iteration   1: 3.611 ops/ms
# Warmup Iteration   2: 8.506 ops/ms
# Warmup Iteration   3: 9.913 ops/ms
Iteration   1: 10.431 ops/ms
Iteration   2: 10.402 ops/ms
Iteration   3: 10.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.330 ±(99.9%) 2.749 ops/ms [Average]
  (min, avg, max) = (10.157, 10.330, 10.431), stdev = 0.151
  CI (99.9%): [7.581, 13.078] (assumes normal distribution)


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
# Warmup Iteration   1: 7.275 ops/ms
# Warmup Iteration   2: 10.239 ops/ms
# Warmup Iteration   3: 10.582 ops/ms
Iteration   1: 10.880 ops/ms
Iteration   2: 10.880 ops/ms
Iteration   3: 10.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.903 ±(99.9%) 0.718 ops/ms [Average]
  (min, avg, max) = (10.880, 10.903, 10.948), stdev = 0.039
  CI (99.9%): [10.185, 11.621] (assumes normal distribution)


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
# Warmup Iteration   1: 7.257 ops/ms
# Warmup Iteration   2: 10.113 ops/ms
# Warmup Iteration   3: 10.300 ops/ms
Iteration   1: 10.322 ops/ms
Iteration   2: 10.573 ops/ms
Iteration   3: 10.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.410 ±(99.9%) 2.572 ops/ms [Average]
  (min, avg, max) = (10.322, 10.410, 10.573), stdev = 0.141
  CI (99.9%): [7.838, 12.983] (assumes normal distribution)


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
# Warmup Iteration   1: 4.796 ops/ms
# Warmup Iteration   2: 7.559 ops/ms
# Warmup Iteration   3: 7.814 ops/ms
Iteration   1: 7.941 ops/ms
Iteration   2: 7.988 ops/ms
Iteration   3: 7.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.935 ±(99.9%) 1.034 ops/ms [Average]
  (min, avg, max) = (7.875, 7.935, 7.988), stdev = 0.057
  CI (99.9%): [6.901, 8.968] (assumes normal distribution)


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
# Warmup Iteration   1: 4.567 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.003 ms/op
Iteration   1: 3.078 ±(99.9%) 0.003 ms/op
Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.089 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (3.078, 3.089, 3.102), stdev = 0.012
  CI (99.9%): [2.873, 3.305] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.003 ms/op
Iteration   1: 2.948 ±(99.9%) 0.003 ms/op
Iteration   2: 2.957 ±(99.9%) 0.002 ms/op
Iteration   3: 2.984 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.963 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.948, 2.963, 2.984), stdev = 0.019
  CI (99.9%): [2.617, 3.310] (assumes normal distribution)


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
# Warmup Iteration   1: 4.461 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.004 ms/op
Iteration   1: 3.119 ±(99.9%) 0.003 ms/op
Iteration   2: 3.081 ±(99.9%) 0.001 ms/op
Iteration   3: 3.146 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.115 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (3.081, 3.115, 3.146), stdev = 0.033
  CI (99.9%): [2.518, 3.713] (assumes normal distribution)


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
# Warmup Iteration   1: 5.129 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.014 ms/op
Iteration   1: 4.074 ±(99.9%) 0.026 ms/op
Iteration   2: 4.024 ±(99.9%) 0.010 ms/op
Iteration   3: 4.094 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.064 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (4.024, 4.064, 4.094), stdev = 0.036
  CI (99.9%): [3.406, 4.723] (assumes normal distribution)


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  7.657 ms/op
                 createUser·p0.9999: 16.861 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.563 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.501 ms/op
                 createUser·p0.999:  7.243 ms/op
                 createUser·p0.9999: 22.741 ms/op
                 createUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313062
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17848 
    [ 2.500,  5.000) = 293186 
    [ 5.000,  7.500) = 1708 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      7.537 ms/op
     p(99.9900) =     21.060 ms/op
     p(99.9990) =     22.802 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 4.137 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.945 ms/op
                 existUser·p0.9999: 13.325 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  7.721 ms/op
                 existUser·p0.9999: 14.797 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   3: 3.015 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.809 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 17.085 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321424
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1397 
    [ 1.250,  2.500) = 28047 
    [ 2.500,  3.750) = 277026 
    [ 3.750,  5.000) = 12824 
    [ 5.000,  6.250) = 1171 
    [ 6.250,  7.500) = 461 
    [ 7.500,  8.750) = 176 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     16.428 ms/op
     p(99.9990) =     17.262 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 4.463 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.006 ms/op
Iteration   1: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.778 ms/op
                 getUser·p0.9999: 19.071 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   2: 3.154 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.578 ms/op
                 getUser·p0.999:  8.853 ms/op
                 getUser·p0.9999: 17.105 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   3: 3.100 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.209 ms/op
                 getUser·p0.9999: 17.477 ms/op
                 getUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308192
  mean =      3.115 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 354 
    [ 1.250,  2.500) = 8779 
    [ 2.500,  3.750) = 278834 
    [ 3.750,  5.000) = 18768 
    [ 5.000,  6.250) = 779 
    [ 6.250,  7.500) = 340 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 64 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     18.553 ms/op
     p(99.9990) =     19.361 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 5.784 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.011 ms/op
Iteration   1: 4.082 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 22.260 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   2: 4.106 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  15.105 ms/op
                 listUser·p0.9999: 23.730 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   3: 4.135 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  18.285 ms/op
                 listUser·p0.9999: 26.968 ms/op
                 listUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233824
  mean =      4.107 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2357 
    [ 2.500,  5.000) = 204406 
    [ 5.000,  7.500) = 25306 
    [ 7.500, 10.000) = 1276 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     16.130 ms/op
     p(99.9900) =     26.464 ms/op
     p(99.9990) =     30.455 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.330 ± 2.749  ops/ms
ClientGrpc.existUser                       thrpt       3  10.903 ± 0.718  ops/ms
ClientGrpc.getUser                         thrpt       3  10.410 ± 2.572  ops/ms
ClientGrpc.listUser                        thrpt       3   7.935 ± 1.034  ops/ms
ClientGrpc.createUser                       avgt       3   3.089 ± 0.216   ms/op
ClientGrpc.existUser                        avgt       3   2.963 ± 0.346   ms/op
ClientGrpc.getUser                          avgt       3   3.115 ± 0.597   ms/op
ClientGrpc.listUser                         avgt       3   4.064 ± 0.658   ms/op
ClientGrpc.createUser                     sample  313062   3.067 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.649           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.537           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.060           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.905           ms/op
ClientGrpc.existUser                      sample  321424   2.985 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.656           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.719           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.765           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.428           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.400           ms/op
ClientGrpc.getUser                        sample  308192   3.115 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.798           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.758           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.553           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.464           ms/op
ClientGrpc.listUser                       sample  233824   4.107 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.029           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.250           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.130           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.464           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.064           ms/op
