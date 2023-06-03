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
# Warmup Iteration   1: 3.961 ops/ms
# Warmup Iteration   2: 8.479 ops/ms
# Warmup Iteration   3: 10.004 ops/ms
Iteration   1: 10.318 ops/ms
Iteration   2: 10.235 ops/ms
Iteration   3: 10.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.330 ±(99.9%) 1.865 ops/ms [Average]
  (min, avg, max) = (10.235, 10.330, 10.438), stdev = 0.102
  CI (99.9%): [8.465, 12.195] (assumes normal distribution)


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
# Warmup Iteration   1: 6.929 ops/ms
# Warmup Iteration   2: 10.228 ops/ms
# Warmup Iteration   3: 10.880 ops/ms
Iteration   1: 10.780 ops/ms
Iteration   2: 10.742 ops/ms
Iteration   3: 10.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.784 ±(99.9%) 0.808 ops/ms [Average]
  (min, avg, max) = (10.742, 10.784, 10.831), stdev = 0.044
  CI (99.9%): [9.976, 11.592] (assumes normal distribution)


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
# Warmup Iteration   1: 6.007 ops/ms
# Warmup Iteration   2: 9.683 ops/ms
# Warmup Iteration   3: 10.348 ops/ms
Iteration   1: 10.285 ops/ms
Iteration   2: 10.536 ops/ms
Iteration   3: 10.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.397 ±(99.9%) 2.328 ops/ms [Average]
  (min, avg, max) = (10.285, 10.397, 10.536), stdev = 0.128
  CI (99.9%): [8.069, 12.726] (assumes normal distribution)


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
# Warmup Iteration   1: 5.581 ops/ms
# Warmup Iteration   2: 7.595 ops/ms
# Warmup Iteration   3: 7.714 ops/ms
Iteration   1: 7.796 ops/ms
Iteration   2: 7.899 ops/ms
Iteration   3: 7.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.873 ±(99.9%) 1.238 ops/ms [Average]
  (min, avg, max) = (7.796, 7.873, 7.923), stdev = 0.068
  CI (99.9%): [6.635, 9.110] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.003 ms/op
Iteration   1: 3.108 ±(99.9%) 0.002 ms/op
Iteration   2: 3.119 ±(99.9%) 0.002 ms/op
Iteration   3: 2.978 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.068 ±(99.9%) 1.435 ms/op [Average]
  (min, avg, max) = (2.978, 3.068, 3.119), stdev = 0.079
  CI (99.9%): [1.633, 4.503] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.002 ms/op
Iteration   1: 2.857 ±(99.9%) 0.002 ms/op
Iteration   2: 2.925 ±(99.9%) 0.002 ms/op
Iteration   3: 2.889 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.890 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (2.857, 2.890, 2.925), stdev = 0.034
  CI (99.9%): [2.274, 3.506] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.606 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.003 ms/op
Iteration   1: 3.090 ±(99.9%) 0.002 ms/op
Iteration   2: 3.119 ±(99.9%) 0.002 ms/op
Iteration   3: 3.122 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.111 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (3.090, 3.111, 3.122), stdev = 0.017
  CI (99.9%): [2.791, 3.430] (assumes normal distribution)


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
# Warmup Iteration   1: 6.018 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.012 ms/op
Iteration   1: 4.062 ±(99.9%) 0.019 ms/op
Iteration   2: 4.069 ±(99.9%) 0.010 ms/op
Iteration   3: 4.015 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.049 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (4.015, 4.049, 4.069), stdev = 0.029
  CI (99.9%): [3.518, 4.580] (assumes normal distribution)


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
# Warmup Iteration   1: 4.773 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.008 ms/op
Iteration   1: 3.124 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.222 ms/op
                 createUser·p0.9999: 33.620 ms/op
                 createUser·p1.00:   34.013 ms/op

Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  8.192 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305720
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15985 
    [ 2.500,  5.000) = 287716 
    [ 5.000,  7.500) = 1511 
    [ 7.500, 10.000) = 264 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.967 ms/op
     p(99.9900) =     33.142 ms/op
     p(99.9990) =     33.878 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 2.984 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  8.092 ms/op
                 existUser·p0.9999: 14.104 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 14.909 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.997 ms/op
                 existUser·p0.9999: 17.244 ms/op
                 existUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323495
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1426 
    [ 1.250,  2.500) = 24942 
    [ 2.500,  3.750) = 285853 
    [ 3.750,  5.000) = 9777 
    [ 5.000,  6.250) = 656 
    [ 6.250,  7.500) = 367 
    [ 7.500,  8.750) = 179 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     16.799 ms/op
     p(99.9990) =     18.811 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.006 ms/op
Iteration   1: 3.128 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.691 ms/op
                 getUser·p0.999:  8.344 ms/op
                 getUser·p0.9999: 13.317 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  7.438 ms/op
                 getUser·p0.9999: 17.990 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.996 ms/op
                 getUser·p0.9999: 17.334 ms/op
                 getUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309243
  mean =      3.104 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 454 
    [ 1.250,  2.500) = 12783 
    [ 2.500,  3.750) = 274376 
    [ 3.750,  5.000) = 19871 
    [ 5.000,  6.250) = 947 
    [ 6.250,  7.500) = 469 
    [ 7.500,  8.750) = 143 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.729 ms/op
     p(99.9900) =     17.402 ms/op
     p(99.9990) =     18.121 ms/op
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
# Warmup Iteration   1: 5.187 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.012 ms/op
Iteration   1: 4.185 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  15.509 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 4.168 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  16.947 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 4.113 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  16.466 ms/op
                 listUser·p0.9999: 26.065 ms/op
                 listUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230982
  mean =      4.155 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1974 
    [ 2.500,  5.000) = 200214 
    [ 5.000,  7.500) = 26702 
    [ 7.500, 10.000) = 1536 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     26.534 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.330 ± 1.865  ops/ms
ClientGrpc.existUser                       thrpt       3  10.784 ± 0.808  ops/ms
ClientGrpc.getUser                         thrpt       3  10.397 ± 2.328  ops/ms
ClientGrpc.listUser                        thrpt       3   7.873 ± 1.238  ops/ms
ClientGrpc.createUser                       avgt       3   3.068 ± 1.435   ms/op
ClientGrpc.existUser                        avgt       3   2.890 ± 0.616   ms/op
ClientGrpc.getUser                          avgt       3   3.111 ± 0.319   ms/op
ClientGrpc.listUser                         avgt       3   4.049 ± 0.531   ms/op
ClientGrpc.createUser                     sample  305720   3.141 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.744           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.967           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.142           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.013           ms/op
ClientGrpc.existUser                      sample  323495   2.967 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.612           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.380           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.799           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.940           ms/op
ClientGrpc.getUser                        sample  309243   3.104 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.587           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.729           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.402           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.252           ms/op
ClientGrpc.listUser                       sample  230982   4.155 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.922           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.965           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.029           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.397           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.302           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.314           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.673           ms/op
