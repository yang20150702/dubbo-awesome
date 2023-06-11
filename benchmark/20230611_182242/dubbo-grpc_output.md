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
# Warmup Iteration   1: 4.366 ops/ms
# Warmup Iteration   2: 9.363 ops/ms
# Warmup Iteration   3: 10.303 ops/ms
Iteration   1: 10.457 ops/ms
Iteration   2: 10.532 ops/ms
Iteration   3: 10.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.476 ±(99.9%) 0.896 ops/ms [Average]
  (min, avg, max) = (10.439, 10.476, 10.532), stdev = 0.049
  CI (99.9%): [9.580, 11.372] (assumes normal distribution)


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
# Warmup Iteration   1: 7.750 ops/ms
# Warmup Iteration   2: 10.746 ops/ms
# Warmup Iteration   3: 10.977 ops/ms
Iteration   1: 11.113 ops/ms
Iteration   2: 11.239 ops/ms
Iteration   3: 11.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.240 ±(99.9%) 2.311 ops/ms [Average]
  (min, avg, max) = (11.113, 11.240, 11.367), stdev = 0.127
  CI (99.9%): [8.929, 13.551] (assumes normal distribution)


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
# Warmup Iteration   1: 7.884 ops/ms
# Warmup Iteration   2: 10.117 ops/ms
# Warmup Iteration   3: 10.521 ops/ms
Iteration   1: 10.577 ops/ms
Iteration   2: 10.662 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.645 ±(99.9%) 1.131 ops/ms [Average]
  (min, avg, max) = (10.577, 10.645, 10.697), stdev = 0.062
  CI (99.9%): [9.514, 11.777] (assumes normal distribution)


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
# Warmup Iteration   1: 5.839 ops/ms
# Warmup Iteration   2: 7.579 ops/ms
# Warmup Iteration   3: 7.765 ops/ms
Iteration   1: 7.974 ops/ms
Iteration   2: 7.844 ops/ms
Iteration   3: 8.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.956 ±(99.9%) 1.916 ops/ms [Average]
  (min, avg, max) = (7.844, 7.956, 8.051), stdev = 0.105
  CI (99.9%): [6.041, 9.872] (assumes normal distribution)


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.004 ms/op
Iteration   1: 3.022 ±(99.9%) 0.004 ms/op
Iteration   2: 3.040 ±(99.9%) 0.004 ms/op
Iteration   3: 3.020 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.027 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (3.020, 3.027, 3.040), stdev = 0.011
  CI (99.9%): [2.830, 3.225] (assumes normal distribution)


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.911 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.856 ±(99.9%) 0.004 ms/op
Iteration   1: 2.867 ±(99.9%) 0.002 ms/op
Iteration   2: 2.860 ±(99.9%) 0.003 ms/op
Iteration   3: 2.897 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.875 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (2.860, 2.875, 2.897), stdev = 0.019
  CI (99.9%): [2.521, 3.229] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.155 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.004 ms/op
Iteration   2: 3.050 ±(99.9%) 0.003 ms/op
Iteration   3: 3.022 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.042 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (3.022, 3.042, 3.055), stdev = 0.018
  CI (99.9%): [2.713, 3.371] (assumes normal distribution)


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
# Warmup Iteration   1: 4.833 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.034 ms/op
Iteration   1: 4.068 ±(99.9%) 0.017 ms/op
Iteration   2: 4.042 ±(99.9%) 0.022 ms/op
Iteration   3: 3.948 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.019 ±(99.9%) 1.151 ms/op [Average]
  (min, avg, max) = (3.948, 4.019, 4.068), stdev = 0.063
  CI (99.9%): [2.868, 5.170] (assumes normal distribution)


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
Iteration   1: 3.045 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.089 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   13.697 ms/op

Iteration   2: 3.031 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  6.495 ms/op
                 createUser·p0.9999: 15.122 ms/op
                 createUser·p1.00:   15.499 ms/op

Iteration   3: 3.028 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.452 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.790 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  7.034 ms/op
                 createUser·p0.9999: 24.703 ms/op
                 createUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316430
  mean =      3.034 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26261 
    [ 2.500,  5.000) = 288756 
    [ 5.000,  7.500) = 1140 
    [ 7.500, 10.000) = 81 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.452 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      6.984 ms/op
     p(99.9900) =     23.268 ms/op
     p(99.9990) =     25.062 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 3.997 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.006 ms/op
Iteration   1: 2.950 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.242 ms/op
                 existUser·p0.999:  6.414 ms/op
                 existUser·p0.9999: 22.255 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 2.880 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.230 ms/op
                 existUser·p0.999:  6.332 ms/op
                 existUser·p0.9999: 23.557 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   3: 2.934 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  6.636 ms/op
                 existUser·p0.9999: 17.665 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328463
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36435 
    [ 2.500,  5.000) = 291004 
    [ 5.000,  7.500) = 789 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      6.476 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     23.902 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 4.365 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
Iteration   1: 3.076 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.021 ms/op
                 getUser·p0.9999: 13.940 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 3.026 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.559 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.093 ms/op
                 getUser·p0.9999: 13.793 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  6.546 ms/op
                 getUser·p0.9999: 16.750 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315413
  mean =      3.043 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 316 
    [ 1.250,  2.500) = 17596 
    [ 2.500,  3.750) = 283289 
    [ 3.750,  5.000) = 12680 
    [ 5.000,  6.250) = 995 
    [ 6.250,  7.500) = 282 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.529 ms/op
     p(99.9000) =      6.976 ms/op
     p(99.9900) =     16.335 ms/op
     p(99.9990) =     17.100 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.779 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.011 ms/op
Iteration   1: 4.050 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  13.511 ms/op
                 listUser·p0.9999: 14.964 ms/op
                 listUser·p1.00:   15.499 ms/op

Iteration   2: 3.832 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.529 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 24.116 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   3: 3.982 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.871 ms/op
                 listUser·p0.999:  14.288 ms/op
                 listUser·p0.9999: 19.429 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242927
  mean =      3.953 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3923 
    [ 2.500,  5.000) = 215557 
    [ 5.000,  7.500) = 22114 
    [ 7.500, 10.000) = 911 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.321 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.476 ± 0.896  ops/ms
ClientGrpc.existUser                       thrpt       3  11.240 ± 2.311  ops/ms
ClientGrpc.getUser                         thrpt       3  10.645 ± 1.131  ops/ms
ClientGrpc.listUser                        thrpt       3   7.956 ± 1.916  ops/ms
ClientGrpc.createUser                       avgt       3   3.027 ± 0.197   ms/op
ClientGrpc.existUser                        avgt       3   2.875 ± 0.354   ms/op
ClientGrpc.getUser                          avgt       3   3.042 ± 0.329   ms/op
ClientGrpc.listUser                         avgt       3   4.019 ± 1.151   ms/op
ClientGrpc.createUser                     sample  316430   3.034 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.452           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.984           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.268           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.461           ms/op
ClientGrpc.existUser                      sample  328463   2.921 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.539           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.476           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.610           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.986           ms/op
ClientGrpc.getUser                        sample  315413   3.043 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.559           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.529           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.976           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.335           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.170           ms/op
ClientGrpc.listUser                       sample  242927   3.953 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.529           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.321           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.479           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.740           ms/op
