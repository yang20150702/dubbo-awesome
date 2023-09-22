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
# Warmup Iteration   1: 3.958 ops/ms
# Warmup Iteration   2: 8.978 ops/ms
# Warmup Iteration   3: 9.724 ops/ms
Iteration   1: 9.922 ops/ms
Iteration   2: 10.464 ops/ms
Iteration   3: 10.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.164 ±(99.9%) 5.030 ops/ms [Average]
  (min, avg, max) = (9.922, 10.164, 10.464), stdev = 0.276
  CI (99.9%): [5.134, 15.194] (assumes normal distribution)


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
# Warmup Iteration   1: 7.427 ops/ms
# Warmup Iteration   2: 10.361 ops/ms
# Warmup Iteration   3: 10.562 ops/ms
Iteration   1: 10.650 ops/ms
Iteration   2: 10.596 ops/ms
Iteration   3: 10.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.645 ±(99.9%) 0.858 ops/ms [Average]
  (min, avg, max) = (10.596, 10.645, 10.690), stdev = 0.047
  CI (99.9%): [9.787, 11.503] (assumes normal distribution)


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
# Warmup Iteration   1: 7.992 ops/ms
# Warmup Iteration   2: 9.647 ops/ms
# Warmup Iteration   3: 10.007 ops/ms
Iteration   1: 10.115 ops/ms
Iteration   2: 10.104 ops/ms
Iteration   3: 10.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.114 ±(99.9%) 0.186 ops/ms [Average]
  (min, avg, max) = (10.104, 10.114, 10.125), stdev = 0.010
  CI (99.9%): [9.928, 10.301] (assumes normal distribution)


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
# Warmup Iteration   1: 5.665 ops/ms
# Warmup Iteration   2: 7.876 ops/ms
# Warmup Iteration   3: 8.080 ops/ms
Iteration   1: 8.155 ops/ms
Iteration   2: 8.110 ops/ms
Iteration   3: 8.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.132 ±(99.9%) 0.408 ops/ms [Average]
  (min, avg, max) = (8.110, 8.132, 8.155), stdev = 0.022
  CI (99.9%): [7.724, 8.540] (assumes normal distribution)


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.003 ms/op
Iteration   1: 3.177 ±(99.9%) 0.002 ms/op
Iteration   2: 3.125 ±(99.9%) 0.002 ms/op
Iteration   3: 3.107 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.136 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (3.107, 3.136, 3.177), stdev = 0.036
  CI (99.9%): [2.476, 3.796] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.003 ms/op
Iteration   1: 2.963 ±(99.9%) 0.004 ms/op
Iteration   2: 3.059 ±(99.9%) 0.003 ms/op
Iteration   3: 2.991 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.004 ±(99.9%) 0.903 ms/op [Average]
  (min, avg, max) = (2.963, 3.004, 3.059), stdev = 0.049
  CI (99.9%): [2.102, 3.907] (assumes normal distribution)


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.002 ms/op
Iteration   1: 3.164 ±(99.9%) 0.003 ms/op
Iteration   2: 3.125 ±(99.9%) 0.003 ms/op
Iteration   3: 3.064 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.118 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (3.064, 3.118, 3.164), stdev = 0.050
  CI (99.9%): [2.203, 4.033] (assumes normal distribution)


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
# Warmup Iteration   1: 5.136 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.049 ms/op
Iteration   1: 3.715 ±(99.9%) 0.011 ms/op
Iteration   2: 3.909 ±(99.9%) 0.010 ms/op
Iteration   3: 3.864 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.829 ±(99.9%) 1.853 ms/op [Average]
  (min, avg, max) = (3.715, 3.829, 3.909), stdev = 0.102
  CI (99.9%): [1.976, 5.683] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.007 ms/op
Iteration   1: 3.175 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.791 ms/op
                 createUser·p0.9999: 16.807 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.122 ms/op
                 createUser·p0.9999: 27.448 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   3: 3.167 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.395 ms/op
                 createUser·p0.999:  10.409 ms/op
                 createUser·p0.9999: 17.662 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305391
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6191 
    [ 2.500,  5.000) = 297733 
    [ 5.000,  7.500) = 1082 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.066 ms/op
     p(99.9900) =     26.623 ms/op
     p(99.9990) =     27.720 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.005 ms/op
Iteration   1: 3.018 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  6.914 ms/op
                 existUser·p0.9999: 10.607 ms/op
                 existUser·p1.00:   11.010 ms/op

Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.750 ms/op
                 existUser·p0.9999: 13.055 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   3: 2.996 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.439 ms/op
                 existUser·p0.9999: 15.907 ms/op
                 existUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318760
  mean =      3.012 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1042 
    [ 1.250,  2.500) = 18493 
    [ 2.500,  3.750) = 284668 
    [ 3.750,  5.000) = 12956 
    [ 5.000,  6.250) = 991 
    [ 6.250,  7.500) = 383 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      6.971 ms/op
     p(99.9900) =     15.309 ms/op
     p(99.9990) =     16.106 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.006 ms/op
Iteration   1: 3.122 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.174 ms/op
                 getUser·p0.9999: 15.111 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 3.169 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.297 ms/op
                 getUser·p0.9999: 16.105 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   3: 3.212 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 18.417 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303064
  mean =      3.167 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 347 
    [ 1.250,  2.500) = 4380 
    [ 2.500,  3.750) = 276832 
    [ 3.750,  5.000) = 20171 
    [ 5.000,  6.250) = 537 
    [ 6.250,  7.500) = 369 
    [ 7.500,  8.750) = 123 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     18.775 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.008 ms/op
Iteration   1: 3.840 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  12.496 ms/op
                 listUser·p0.9999: 13.992 ms/op
                 listUser·p1.00:   15.303 ms/op

Iteration   2: 3.860 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  12.732 ms/op
                 listUser·p0.9999: 14.856 ms/op
                 listUser·p1.00:   15.237 ms/op

Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.937 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247496
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 5484 
    [ 2.500,  3.750) = 115491 
    [ 3.750,  5.000) = 106914 
    [ 5.000,  6.250) = 14030 
    [ 6.250,  7.500) = 4613 
    [ 7.500,  8.750) = 331 
    [ 8.750, 10.000) = 134 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 118 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     13.247 ms/op
     p(99.9900) =     17.506 ms/op
     p(99.9990) =     18.566 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.164 ± 5.030  ops/ms
ClientGrpc.existUser                       thrpt       3  10.645 ± 0.858  ops/ms
ClientGrpc.getUser                         thrpt       3  10.114 ± 0.186  ops/ms
ClientGrpc.listUser                        thrpt       3   8.132 ± 0.408  ops/ms
ClientGrpc.createUser                       avgt       3   3.136 ± 0.660   ms/op
ClientGrpc.existUser                        avgt       3   3.004 ± 0.903   ms/op
ClientGrpc.getUser                          avgt       3   3.118 ± 0.915   ms/op
ClientGrpc.listUser                         avgt       3   3.829 ± 1.853   ms/op
ClientGrpc.createUser                     sample  305391   3.142 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.716           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.066           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.623           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.820           ms/op
ClientGrpc.existUser                      sample  318760   3.012 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.706           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.971           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.309           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.204           ms/op
ClientGrpc.getUser                        sample  303064   3.167 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.591           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.831           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.269           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.907           ms/op
ClientGrpc.listUser                       sample  247496   3.877 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.190           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.653           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.247           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.506           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.711           ms/op
