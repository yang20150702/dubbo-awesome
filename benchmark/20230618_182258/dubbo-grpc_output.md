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
# Warmup Iteration   1: 4.204 ops/ms
# Warmup Iteration   2: 9.056 ops/ms
# Warmup Iteration   3: 9.983 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.266 ops/ms
Iteration   3: 10.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.386 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (10.266, 10.386, 10.478), stdev = 0.109
  CI (99.9%): [8.400, 12.372] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.424 ops/ms
# Warmup Iteration   2: 10.244 ops/ms
# Warmup Iteration   3: 10.822 ops/ms
Iteration   1: 10.904 ops/ms
Iteration   2: 11.032 ops/ms
Iteration   3: 11.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.031 ±(99.9%) 2.312 ops/ms [Average]
  (min, avg, max) = (10.904, 11.031, 11.158), stdev = 0.127
  CI (99.9%): [8.720, 13.343] (assumes normal distribution)


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
# Warmup Iteration   1: 6.930 ops/ms
# Warmup Iteration   2: 10.221 ops/ms
# Warmup Iteration   3: 10.460 ops/ms
Iteration   1: 10.837 ops/ms
Iteration   2: 10.844 ops/ms
Iteration   3: 10.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.804 ±(99.9%) 1.145 ops/ms [Average]
  (min, avg, max) = (10.732, 10.804, 10.844), stdev = 0.063
  CI (99.9%): [9.659, 11.949] (assumes normal distribution)


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
# Warmup Iteration   1: 6.235 ops/ms
# Warmup Iteration   2: 7.764 ops/ms
# Warmup Iteration   3: 7.978 ops/ms
Iteration   1: 8.007 ops/ms
Iteration   2: 8.223 ops/ms
Iteration   3: 7.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.035 ±(99.9%) 3.200 ops/ms [Average]
  (min, avg, max) = (7.876, 8.035, 8.223), stdev = 0.175
  CI (99.9%): [4.836, 11.235] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.003 ms/op
Iteration   1: 3.047 ±(99.9%) 0.003 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.035 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.050 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (3.035, 3.050, 3.068), stdev = 0.017
  CI (99.9%): [2.746, 3.354] (assumes normal distribution)


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.003 ms/op
Iteration   1: 2.884 ±(99.9%) 0.003 ms/op
Iteration   2: 2.899 ±(99.9%) 0.004 ms/op
Iteration   3: 2.995 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.926 ±(99.9%) 1.105 ms/op [Average]
  (min, avg, max) = (2.884, 2.926, 2.995), stdev = 0.061
  CI (99.9%): [1.821, 4.031] (assumes normal distribution)


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.005 ms/op
Iteration   1: 3.028 ±(99.9%) 0.003 ms/op
Iteration   2: 3.007 ±(99.9%) 0.002 ms/op
Iteration   3: 3.048 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.028 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.007, 3.028, 3.048), stdev = 0.021
  CI (99.9%): [2.653, 3.402] (assumes normal distribution)


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.243 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.118 ±(99.9%) 0.014 ms/op
Iteration   1: 4.088 ±(99.9%) 0.026 ms/op
Iteration   2: 3.929 ±(99.9%) 0.007 ms/op
Iteration   3: 4.057 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.025 ±(99.9%) 1.537 ms/op [Average]
  (min, avg, max) = (3.929, 4.025, 4.088), stdev = 0.084
  CI (99.9%): [2.487, 5.562] (assumes normal distribution)


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
# Warmup Iteration   1: 4.261 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  8.660 ms/op
                 createUser·p0.9999: 18.167 ms/op
                 createUser·p1.00:   18.448 ms/op

Iteration   2: 3.020 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  7.873 ms/op
                 createUser·p0.9999: 22.741 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.476 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.261 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316801
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24066 
    [ 2.500,  5.000) = 291105 
    [ 5.000,  7.500) = 1238 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.192 ms/op
     p(99.9900) =     21.943 ms/op
     p(99.9990) =     22.921 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.271 ms/op
                 existUser·p0.9999: 18.297 ms/op
                 existUser·p1.00:   18.547 ms/op

Iteration   2: 2.961 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  6.169 ms/op
                 existUser·p0.9999: 12.606 ms/op
                 existUser·p1.00:   12.829 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.929 ms/op
                 existUser·p0.9999: 15.073 ms/op
                 existUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322296
  mean =      2.980 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2159 
    [ 1.250,  2.500) = 27811 
    [ 2.500,  3.750) = 281271 
    [ 3.750,  5.000) = 9803 
    [ 5.000,  6.250) = 822 
    [ 6.250,  7.500) = 193 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 64 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     18.441 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.829 ms/op
                 getUser·p0.9999: 13.273 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.112 ms/op
                 getUser·p0.9999: 14.828 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.991 ms/op
                 getUser·p0.9999: 17.826 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316280
  mean =      3.034 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 628 
    [ 1.250,  2.500) = 16779 
    [ 2.500,  3.750) = 286330 
    [ 3.750,  5.000) = 11398 
    [ 5.000,  6.250) = 627 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.304 ms/op
     p(99.9900) =     15.616 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 5.126 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
Iteration   1: 3.901 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  12.504 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   2: 3.941 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 21.590 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 3.862 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.822 ms/op
                 listUser·p0.999:  16.056 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246040
  mean =      3.901 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3997 
    [ 2.500,  5.000) = 221387 
    [ 5.000,  7.500) = 19599 
    [ 7.500, 10.000) = 629 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     20.932 ms/op
     p(99.9990) =     22.401 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.386 ± 1.986  ops/ms
ClientGrpc.existUser                       thrpt       3  11.031 ± 2.312  ops/ms
ClientGrpc.getUser                         thrpt       3  10.804 ± 1.145  ops/ms
ClientGrpc.listUser                        thrpt       3   8.035 ± 3.200  ops/ms
ClientGrpc.createUser                       avgt       3   3.050 ± 0.304   ms/op
ClientGrpc.existUser                        avgt       3   2.926 ± 1.105   ms/op
ClientGrpc.getUser                          avgt       3   3.028 ± 0.375   ms/op
ClientGrpc.listUser                         avgt       3   4.025 ± 1.537   ms/op
ClientGrpc.createUser                     sample  316801   3.030 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.476           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.192           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.943           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.691           ms/op
ClientGrpc.existUser                      sample  322296   2.980 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.726           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.957           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.547           ms/op
ClientGrpc.getUser                        sample  316280   3.034 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.587           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.304           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.616           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.859           ms/op
ClientGrpc.listUser                       sample  246040   3.901 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.993           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.801           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.812           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.932           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.446           ms/op
