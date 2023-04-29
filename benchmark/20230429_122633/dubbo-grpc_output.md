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
# Warmup Iteration   1: 4.429 ops/ms
# Warmup Iteration   2: 9.354 ops/ms
# Warmup Iteration   3: 10.477 ops/ms
Iteration   1: 10.678 ops/ms
Iteration   2: 10.679 ops/ms
Iteration   3: 10.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.701 ±(99.9%) 0.715 ops/ms [Average]
  (min, avg, max) = (10.678, 10.701, 10.746), stdev = 0.039
  CI (99.9%): [9.986, 11.416] (assumes normal distribution)


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
# Warmup Iteration   1: 7.734 ops/ms
# Warmup Iteration   2: 10.645 ops/ms
# Warmup Iteration   3: 11.118 ops/ms
Iteration   1: 11.127 ops/ms
Iteration   2: 11.158 ops/ms
Iteration   3: 11.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.122 ±(99.9%) 0.685 ops/ms [Average]
  (min, avg, max) = (11.083, 11.122, 11.158), stdev = 0.038
  CI (99.9%): [10.437, 11.808] (assumes normal distribution)


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
# Warmup Iteration   1: 7.169 ops/ms
# Warmup Iteration   2: 10.347 ops/ms
# Warmup Iteration   3: 10.626 ops/ms
Iteration   1: 10.734 ops/ms
Iteration   2: 10.699 ops/ms
Iteration   3: 10.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.676 ±(99.9%) 1.319 ops/ms [Average]
  (min, avg, max) = (10.595, 10.676, 10.734), stdev = 0.072
  CI (99.9%): [9.357, 11.995] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.725 ops/ms
# Warmup Iteration   2: 7.750 ops/ms
# Warmup Iteration   3: 7.923 ops/ms
Iteration   1: 8.070 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.078 ±(99.9%) 0.148 ops/ms [Average]
  (min, avg, max) = (8.070, 8.078, 8.086), stdev = 0.008
  CI (99.9%): [7.930, 8.227] (assumes normal distribution)


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.011 ms/op
Iteration   1: 3.013 ±(99.9%) 0.004 ms/op
Iteration   2: 3.022 ±(99.9%) 0.002 ms/op
Iteration   3: 2.978 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.004 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.978, 3.004, 3.022), stdev = 0.023
  CI (99.9%): [2.578, 3.430] (assumes normal distribution)


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.855 ±(99.9%) 0.004 ms/op
Iteration   1: 2.897 ±(99.9%) 0.003 ms/op
Iteration   2: 2.866 ±(99.9%) 0.003 ms/op
Iteration   3: 2.869 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.877 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (2.866, 2.877, 2.897), stdev = 0.017
  CI (99.9%): [2.570, 3.184] (assumes normal distribution)


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.001 ms/op
Iteration   3: 3.093 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.797 ms/op [Average]
  (min, avg, max) = (3.017, 3.043, 3.093), stdev = 0.044
  CI (99.9%): [2.246, 3.840] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.320 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.009 ms/op
Iteration   1: 3.942 ±(99.9%) 0.016 ms/op
Iteration   2: 3.944 ±(99.9%) 0.008 ms/op
Iteration   3: 3.904 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.930 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (3.904, 3.930, 3.944), stdev = 0.022
  CI (99.9%): [3.524, 4.335] (assumes normal distribution)


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
# Warmup Iteration   1: 4.333 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.064 ms/op
                 createUser·p0.9999: 12.130 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  9.437 ms/op
                 createUser·p0.9999: 14.358 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  11.129 ms/op
                 createUser·p0.9999: 16.516 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317553
  mean =      3.023 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1076 
    [ 1.250,  2.500) = 29216 
    [ 2.500,  3.750) = 268386 
    [ 3.750,  5.000) = 17252 
    [ 5.000,  6.250) = 934 
    [ 6.250,  7.500) = 298 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.878 ms/op
     p(99.9900) =     15.729 ms/op
     p(99.9990) =     16.771 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.006 ms/op
Iteration   1: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  6.323 ms/op
                 existUser·p0.9999: 17.332 ms/op
                 existUser·p1.00:   17.760 ms/op

Iteration   2: 2.917 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.650 ms/op
                 existUser·p0.9999: 22.086 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   3: 2.864 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  6.855 ms/op
                 existUser·p0.9999: 16.758 ms/op
                 existUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331819
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43912 
    [ 2.500,  5.000) = 286813 
    [ 5.000,  7.500) = 890 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.604 ms/op
     p(99.9900) =     17.748 ms/op
     p(99.9990) =     22.239 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  10.485 ms/op
                 getUser·p0.9999: 14.074 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.941 ms/op
                 getUser·p0.9999: 14.811 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   3: 2.971 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.338 ms/op
                 getUser·p0.95:   3.531 ms/op
                 getUser·p0.99:   4.063 ms/op
                 getUser·p0.999:  7.016 ms/op
                 getUser·p0.9999: 16.734 ms/op
                 getUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318867
  mean =      3.008 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 316 
    [ 1.250,  2.500) = 21927 
    [ 2.500,  3.750) = 282221 
    [ 3.750,  5.000) = 12999 
    [ 5.000,  6.250) = 788 
    [ 6.250,  7.500) = 297 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.504 ms/op
     p(99.9900) =     15.976 ms/op
     p(99.9990) =     18.213 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 5.195 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.011 ms/op
Iteration   1: 3.965 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.471 ms/op
                 listUser·p0.9999: 20.572 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 3.930 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.825 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 21.907 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 3.925 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.770 ms/op
                 listUser·p0.9999: 22.736 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243641
  mean =      3.940 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2280 
    [ 2.500,  5.000) = 224333 
    [ 5.000,  7.500) = 15781 
    [ 7.500, 10.000) = 789 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     22.172 ms/op
     p(99.9990) =     23.157 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.701 ± 0.715  ops/ms
ClientGrpc.existUser                       thrpt       3  11.122 ± 0.685  ops/ms
ClientGrpc.getUser                         thrpt       3  10.676 ± 1.319  ops/ms
ClientGrpc.listUser                        thrpt       3   8.078 ± 0.148  ops/ms
ClientGrpc.createUser                       avgt       3   3.004 ± 0.426   ms/op
ClientGrpc.existUser                        avgt       3   2.877 ± 0.307   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.797   ms/op
ClientGrpc.listUser                         avgt       3   3.930 ± 0.406   ms/op
ClientGrpc.createUser                     sample  317553   3.023 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.709           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.878           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.729           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.908           ms/op
ClientGrpc.existUser                      sample  331819   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.675           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.604           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.748           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.315           ms/op
ClientGrpc.getUser                        sample  318867   3.008 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.591           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.504           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.976           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.252           ms/op
ClientGrpc.listUser                       sample  243641   3.940 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.879           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.713           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.172           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.298           ms/op
