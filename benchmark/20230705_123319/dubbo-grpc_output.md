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
# Warmup Iteration   1: 3.770 ops/ms
# Warmup Iteration   2: 8.669 ops/ms
# Warmup Iteration   3: 10.007 ops/ms
Iteration   1: 10.327 ops/ms
Iteration   2: 10.311 ops/ms
Iteration   3: 10.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.337 ±(99.9%) 0.585 ops/ms [Average]
  (min, avg, max) = (10.311, 10.337, 10.373), stdev = 0.032
  CI (99.9%): [9.752, 10.922] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.369 ops/ms
# Warmup Iteration   2: 10.598 ops/ms
# Warmup Iteration   3: 10.913 ops/ms
Iteration   1: 10.909 ops/ms
Iteration   2: 10.963 ops/ms
Iteration   3: 10.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.943 ±(99.9%) 0.536 ops/ms [Average]
  (min, avg, max) = (10.909, 10.943, 10.963), stdev = 0.029
  CI (99.9%): [10.407, 11.480] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.609 ops/ms
# Warmup Iteration   2: 10.049 ops/ms
# Warmup Iteration   3: 10.257 ops/ms
Iteration   1: 10.672 ops/ms
Iteration   2: 10.453 ops/ms
Iteration   3: 10.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.538 ±(99.9%) 2.137 ops/ms [Average]
  (min, avg, max) = (10.453, 10.538, 10.672), stdev = 0.117
  CI (99.9%): [8.401, 12.674] (assumes normal distribution)


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
# Warmup Iteration   1: 6.307 ops/ms
# Warmup Iteration   2: 7.505 ops/ms
# Warmup Iteration   3: 7.860 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 8.083 ops/ms
Iteration   3: 7.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.054 ±(99.9%) 2.288 ops/ms [Average]
  (min, avg, max) = (7.917, 8.054, 8.163), stdev = 0.125
  CI (99.9%): [5.766, 10.343] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.566 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.002 ms/op
Iteration   1: 3.103 ±(99.9%) 0.001 ms/op
Iteration   2: 3.063 ±(99.9%) 0.002 ms/op
Iteration   3: 3.117 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.094 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (3.063, 3.094, 3.117), stdev = 0.028
  CI (99.9%): [2.581, 3.607] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.188 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.002 ms/op
Iteration   1: 3.037 ±(99.9%) 0.002 ms/op
Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
Iteration   3: 2.892 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.961 ±(99.9%) 1.321 ms/op [Average]
  (min, avg, max) = (2.892, 2.961, 3.037), stdev = 0.072
  CI (99.9%): [1.640, 4.282] (assumes normal distribution)


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
# Warmup Iteration   1: 4.712 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
Iteration   2: 3.044 ±(99.9%) 0.004 ms/op
Iteration   3: 3.039 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.047 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (3.039, 3.047, 3.057), stdev = 0.009
  CI (99.9%): [2.879, 3.215] (assumes normal distribution)


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
# Warmup Iteration   1: 5.411 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.017 ms/op
Iteration   1: 4.049 ±(99.9%) 0.009 ms/op
Iteration   2: 3.983 ±(99.9%) 0.049 ms/op
Iteration   3: 3.969 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.000 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (3.969, 4.000, 4.049), stdev = 0.043
  CI (99.9%): [3.223, 4.777] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.340 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.006 ms/op
Iteration   1: 3.105 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  8.471 ms/op
                 createUser·p0.9999: 13.053 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.811 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  10.715 ms/op
                 createUser·p0.9999: 15.486 ms/op
                 createUser·p1.00:   15.958 ms/op

Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  8.732 ms/op
                 createUser·p0.9999: 16.499 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308111
  mean =      3.114 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 237 
    [ 1.250,  2.500) = 13824 
    [ 2.500,  3.750) = 273341 
    [ 3.750,  5.000) = 18854 
    [ 5.000,  6.250) = 919 
    [ 6.250,  7.500) = 449 
    [ 7.500,  8.750) = 160 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      9.091 ms/op
     p(99.9900) =     15.794 ms/op
     p(99.9990) =     17.954 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.037 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  6.582 ms/op
                 existUser·p0.9999: 21.570 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   2: 2.916 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  6.803 ms/op
                 existUser·p0.9999: 14.206 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   3: 2.887 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  6.539 ms/op
                 existUser·p0.9999: 17.692 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329279
  mean =      2.914 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32290 
    [ 2.500,  5.000) = 296196 
    [ 5.000,  7.500) = 592 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     18.202 ms/op
     p(99.9990) =     22.034 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.636 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  7.946 ms/op
                 getUser·p0.9999: 13.462 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  8.380 ms/op
                 getUser·p0.9999: 15.206 ms/op
                 getUser·p1.00:   15.581 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.632 ms/op
                 getUser·p0.9999: 19.322 ms/op
                 getUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311247
  mean =      3.084 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 432 
    [ 1.250,  2.500) = 15568 
    [ 2.500,  3.750) = 276148 
    [ 3.750,  5.000) = 17257 
    [ 5.000,  6.250) = 1166 
    [ 6.250,  7.500) = 308 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      8.143 ms/op
     p(99.9900) =     16.933 ms/op
     p(99.9990) =     19.621 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 5.471 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.011 ms/op
Iteration   1: 4.029 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 19.714 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 3.923 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.013 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  13.901 ms/op
                 listUser·p0.9999: 17.329 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 3.941 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   7.103 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242299
  mean =      3.964 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2573 
    [ 2.500,  5.000) = 218618 
    [ 5.000,  7.500) = 19566 
    [ 7.500, 10.000) = 969 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     14.446 ms/op
     p(99.9900) =     19.532 ms/op
     p(99.9990) =     20.761 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.337 ± 0.585  ops/ms
ClientGrpc.existUser                       thrpt       3  10.943 ± 0.536  ops/ms
ClientGrpc.getUser                         thrpt       3  10.538 ± 2.137  ops/ms
ClientGrpc.listUser                        thrpt       3   8.054 ± 2.288  ops/ms
ClientGrpc.createUser                       avgt       3   3.094 ± 0.513   ms/op
ClientGrpc.existUser                        avgt       3   2.961 ± 1.321   ms/op
ClientGrpc.getUser                          avgt       3   3.047 ± 0.168   ms/op
ClientGrpc.listUser                         avgt       3   4.000 ± 0.777   ms/op
ClientGrpc.createUser                     sample  308111   3.114 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.637           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.091           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.794           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.219           ms/op
ClientGrpc.existUser                      sample  329279   2.914 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.646           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.578           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.202           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.184           ms/op
ClientGrpc.getUser                        sample  311247   3.084 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.872           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.143           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.933           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.726           ms/op
ClientGrpc.listUser                       sample  242299   3.964 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.013           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.446           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.532           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.103           ms/op
