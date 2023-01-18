# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.109 ops/ms
# Warmup Iteration   2: 9.494 ops/ms
# Warmup Iteration   3: 10.426 ops/ms
Iteration   1: 10.698 ops/ms
Iteration   2: 10.624 ops/ms
Iteration   3: 10.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.483 ±(99.9%) 5.651 ops/ms [Average]
  (min, avg, max) = (10.128, 10.483, 10.698), stdev = 0.310
  CI (99.9%): [4.832, 16.134] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.997 ops/ms
# Warmup Iteration   2: 10.676 ops/ms
# Warmup Iteration   3: 10.815 ops/ms
Iteration   1: 11.309 ops/ms
Iteration   2: 10.631 ops/ms
Iteration   3: 10.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.975 ±(99.9%) 6.190 ops/ms [Average]
  (min, avg, max) = (10.631, 10.975, 11.309), stdev = 0.339
  CI (99.9%): [4.785, 17.165] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.651 ops/ms
# Warmup Iteration   2: 10.105 ops/ms
# Warmup Iteration   3: 10.359 ops/ms
Iteration   1: 10.257 ops/ms
Iteration   2: 10.570 ops/ms
Iteration   3: 10.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.367 ±(99.9%) 3.213 ops/ms [Average]
  (min, avg, max) = (10.257, 10.367, 10.570), stdev = 0.176
  CI (99.9%): [7.154, 13.580] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.753 ops/ms
# Warmup Iteration   2: 7.732 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 7.962 ops/ms
Iteration   2: 7.981 ops/ms
Iteration   3: 7.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.888 ±(99.9%) 2.651 ops/ms [Average]
  (min, avg, max) = (7.720, 7.888, 7.981), stdev = 0.145
  CI (99.9%): [5.237, 10.539] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.004 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
Iteration   1: 3.071 ±(99.9%) 0.003 ms/op
Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
Iteration   3: 3.123 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.085 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (3.060, 3.085, 3.123), stdev = 0.034
  CI (99.9%): [2.473, 3.697] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.706 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.003 ms/op
Iteration   1: 2.872 ±(99.9%) 0.004 ms/op
Iteration   2: 2.951 ±(99.9%) 0.002 ms/op
Iteration   3: 2.967 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.930 ±(99.9%) 0.933 ms/op [Average]
  (min, avg, max) = (2.872, 2.930, 2.967), stdev = 0.051
  CI (99.9%): [1.997, 3.863] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.003 ms/op
Iteration   1: 3.145 ±(99.9%) 0.003 ms/op
Iteration   2: 3.080 ±(99.9%) 0.002 ms/op
Iteration   3: 3.154 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.126 ±(99.9%) 0.742 ms/op [Average]
  (min, avg, max) = (3.080, 3.126, 3.154), stdev = 0.041
  CI (99.9%): [2.385, 3.868] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.384 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.017 ms/op
Iteration   1: 3.989 ±(99.9%) 0.027 ms/op
Iteration   2: 4.020 ±(99.9%) 0.011 ms/op
Iteration   3: 3.910 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.973 ±(99.9%) 1.040 ms/op [Average]
  (min, avg, max) = (3.910, 3.973, 4.020), stdev = 0.057
  CI (99.9%): [2.933, 5.012] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  10.031 ms/op
                 createUser·p0.9999: 15.031 ms/op
                 createUser·p1.00:   16.728 ms/op

Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.439 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.166 ms/op
                 createUser·p0.999:  6.062 ms/op
                 createUser·p0.9999: 17.695 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   3: 3.121 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.116 ms/op
                 createUser·p0.999:  7.125 ms/op
                 createUser·p0.9999: 17.392 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310217
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1242 
    [ 1.250,  2.500) = 24427 
    [ 2.500,  3.750) = 257085 
    [ 3.750,  5.000) = 26703 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 73 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.953 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     18.019 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.006 ms/op
Iteration   1: 2.880 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.461 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  6.942 ms/op
                 existUser·p0.9999: 16.249 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   2: 2.880 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.274 ms/op
                 existUser·p0.9999: 20.522 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.228 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  6.255 ms/op
                 existUser·p0.9999: 15.712 ms/op
                 existUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330446
  mean =      2.906 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52710 
    [ 2.500,  5.000) = 276847 
    [ 5.000,  7.500) = 632 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.228 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.607 ms/op
     p(99.9900) =     17.076 ms/op
     p(99.9990) =     22.210 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.007 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.191 ms/op
                 getUser·p0.9999: 16.056 ms/op
                 getUser·p1.00:   17.990 ms/op

Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.053 ms/op
                 getUser·p0.9999: 15.510 ms/op
                 getUser·p1.00:   15.843 ms/op

Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.254 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.292 ms/op
                 getUser·p0.999:  6.840 ms/op
                 getUser·p0.9999: 17.714 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312717
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1932 
    [ 1.250,  2.500) = 23945 
    [ 2.500,  3.750) = 262608 
    [ 3.750,  5.000) = 23257 
    [ 5.000,  6.250) = 562 
    [ 6.250,  7.500) = 211 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 73 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.254 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.753 ms/op
     p(99.9900) =     16.625 ms/op
     p(99.9990) =     18.248 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.545 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.013 ms/op
Iteration   1: 4.049 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 15.781 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   2: 4.130 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  13.231 ms/op
                 listUser·p0.9999: 15.983 ms/op
                 listUser·p1.00:   16.286 ms/op

Iteration   3: 4.081 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.582 ms/op
                 listUser·p0.9999: 18.965 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234925
  mean =      4.086 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 2687 
    [ 2.500,  3.750) = 88603 
    [ 3.750,  5.000) = 108395 
    [ 5.000,  6.250) = 29592 
    [ 6.250,  7.500) = 4360 
    [ 7.500,  8.750) = 729 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 86 
    [15.000, 16.250) = 61 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     19.463 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.483 ± 5.651  ops/ms
ClientGrpc.existUser                       thrpt       3  10.975 ± 6.190  ops/ms
ClientGrpc.getUser                         thrpt       3  10.367 ± 3.213  ops/ms
ClientGrpc.listUser                        thrpt       3   7.888 ± 2.651  ops/ms
ClientGrpc.createUser                       avgt       3   3.085 ± 0.612   ms/op
ClientGrpc.existUser                        avgt       3   2.930 ± 0.933   ms/op
ClientGrpc.getUser                          avgt       3   3.126 ± 0.742   ms/op
ClientGrpc.listUser                         avgt       3   3.973 ± 1.040   ms/op
ClientGrpc.createUser                     sample  310217   3.094 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.439           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.953           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.367           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.153           ms/op
ClientGrpc.existUser                      sample  330446   2.906 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.228           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.607           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.076           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.381           ms/op
ClientGrpc.getUser                        sample  312717   3.068 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.254           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.753           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.625           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.514           ms/op
ClientGrpc.listUser                       sample  234925   4.086 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.825           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.795           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.859           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.595           ms/op
