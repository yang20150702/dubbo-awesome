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
# Warmup Iteration   1: 3.931 ops/ms
# Warmup Iteration   2: 8.689 ops/ms
# Warmup Iteration   3: 10.124 ops/ms
Iteration   1: 10.646 ops/ms
Iteration   2: 10.568 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.552 ±(99.9%) 1.882 ops/ms [Average]
  (min, avg, max) = (10.442, 10.552, 10.646), stdev = 0.103
  CI (99.9%): [8.670, 12.434] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.445 ops/ms
# Warmup Iteration   2: 10.431 ops/ms
# Warmup Iteration   3: 10.919 ops/ms
Iteration   1: 11.007 ops/ms
Iteration   2: 11.160 ops/ms
Iteration   3: 11.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.158 ±(99.9%) 2.750 ops/ms [Average]
  (min, avg, max) = (11.007, 11.158, 11.308), stdev = 0.151
  CI (99.9%): [8.409, 13.908] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.350 ops/ms
# Warmup Iteration   2: 9.713 ops/ms
# Warmup Iteration   3: 10.153 ops/ms
Iteration   1: 10.352 ops/ms
Iteration   2: 10.429 ops/ms
Iteration   3: 10.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.377 ±(99.9%) 0.816 ops/ms [Average]
  (min, avg, max) = (10.351, 10.377, 10.429), stdev = 0.045
  CI (99.9%): [9.561, 11.193] (assumes normal distribution)


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
# Warmup Iteration   1: 6.281 ops/ms
# Warmup Iteration   2: 7.692 ops/ms
# Warmup Iteration   3: 8.143 ops/ms
Iteration   1: 8.075 ops/ms
Iteration   2: 7.999 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.038 ±(99.9%) 0.688 ops/ms [Average]
  (min, avg, max) = (7.999, 8.038, 8.075), stdev = 0.038
  CI (99.9%): [7.350, 8.726] (assumes normal distribution)


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.004 ms/op
Iteration   1: 2.994 ±(99.9%) 0.007 ms/op
Iteration   2: 3.023 ±(99.9%) 0.003 ms/op
Iteration   3: 3.055 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.024 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (2.994, 3.024, 3.055), stdev = 0.030
  CI (99.9%): [2.474, 3.575] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.002 ms/op
Iteration   1: 2.906 ±(99.9%) 0.002 ms/op
Iteration   2: 2.918 ±(99.9%) 0.002 ms/op
Iteration   3: 2.894 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.906 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.894, 2.906, 2.918), stdev = 0.012
  CI (99.9%): [2.685, 3.127] (assumes normal distribution)


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
# Warmup Iteration   1: 4.126 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.002 ms/op
Iteration   1: 3.010 ±(99.9%) 0.003 ms/op
Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
Iteration   3: 3.023 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.007 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.990, 3.007, 3.023), stdev = 0.017
  CI (99.9%): [2.706, 3.309] (assumes normal distribution)


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.018 ms/op
Iteration   1: 3.930 ±(99.9%) 0.025 ms/op
Iteration   2: 3.961 ±(99.9%) 0.017 ms/op
Iteration   3: 3.907 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.933 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (3.907, 3.933, 3.961), stdev = 0.027
  CI (99.9%): [3.436, 4.430] (assumes normal distribution)


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.053 ms/op
                 createUser·p0.9999: 15.906 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.427 ms/op
                 createUser·p0.9999: 17.938 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  9.754 ms/op
                 createUser·p0.9999: 31.130 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316723
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20607 
    [ 2.500,  5.000) = 294654 
    [ 5.000,  7.500) = 1065 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.985 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     31.976 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.006 ms/op
Iteration   1: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.302 ms/op
                 existUser·p0.999:  8.135 ms/op
                 existUser·p0.9999: 12.336 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   2: 2.864 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  5.516 ms/op
                 existUser·p0.9999: 13.776 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   3: 2.842 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.405 ms/op
                 existUser·p0.9999: 24.740 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334703
  mean =      2.867 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44550 
    [ 2.500,  5.000) = 288833 
    [ 5.000,  7.500) = 1017 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.494 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.283 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     25.197 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  10.211 ms/op
                 getUser·p0.9999: 12.059 ms/op
                 getUser·p1.00:   12.222 ms/op

Iteration   2: 2.982 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  7.281 ms/op
                 getUser·p0.9999: 19.923 ms/op
                 getUser·p1.00:   20.283 ms/op

Iteration   3: 3.015 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.527 ms/op
                 getUser·p0.99:   4.108 ms/op
                 getUser·p0.999:  5.733 ms/op
                 getUser·p0.9999: 19.084 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319861
  mean =      3.001 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26214 
    [ 2.500,  5.000) = 291995 
    [ 5.000,  7.500) = 1331 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.513 ms/op
     p(99.9900) =     19.465 ms/op
     p(99.9990) =     20.146 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 5.355 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.011 ms/op
Iteration   1: 4.003 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.364 ms/op
                 listUser·p0.9999: 15.663 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   2: 3.942 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   3.803 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.716 ms/op
                 listUser·p0.999:  14.088 ms/op
                 listUser·p0.9999: 16.149 ms/op
                 listUser·p1.00:   16.515 ms/op

Iteration   3: 3.944 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.367 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242093
  mean =      3.963 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2155 
    [ 2.500,  3.750) = 101798 
    [ 3.750,  5.000) = 117384 
    [ 5.000,  6.250) = 15259 
    [ 6.250,  7.500) = 4460 
    [ 7.500,  8.750) = 520 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 111 
    [15.000, 16.250) = 140 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     16.544 ms/op
     p(99.9990) =     18.550 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.552 ± 1.882  ops/ms
ClientGrpc.existUser                       thrpt       3  11.158 ± 2.750  ops/ms
ClientGrpc.getUser                         thrpt       3  10.377 ± 0.816  ops/ms
ClientGrpc.listUser                        thrpt       3   8.038 ± 0.688  ops/ms
ClientGrpc.createUser                       avgt       3   3.024 ± 0.551   ms/op
ClientGrpc.existUser                        avgt       3   2.906 ± 0.221   ms/op
ClientGrpc.getUser                          avgt       3   3.007 ± 0.301   ms/op
ClientGrpc.listUser                         avgt       3   3.933 ± 0.497   ms/op
ClientGrpc.createUser                     sample  316723   3.033 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.450           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.985           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.212           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.014           ms/op
ClientGrpc.existUser                      sample  334703   2.867 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.550           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.283           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.776           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.494           ms/op
ClientGrpc.getUser                        sample  319861   3.001 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.801           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.513           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.465           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.283           ms/op
ClientGrpc.listUser                       sample  242093   3.963 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.945           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.205           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.544           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.809           ms/op
