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
# Warmup Iteration   1: 2.991 ops/ms
# Warmup Iteration   2: 6.219 ops/ms
# Warmup Iteration   3: 7.605 ops/ms
Iteration   1: 7.971 ops/ms
Iteration   2: 8.032 ops/ms
Iteration   3: 7.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.978 ±(99.9%) 0.937 ops/ms [Average]
  (min, avg, max) = (7.929, 7.978, 8.032), stdev = 0.051
  CI (99.9%): [7.040, 8.915] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.943 ops/ms
# Warmup Iteration   2: 7.622 ops/ms
# Warmup Iteration   3: 7.802 ops/ms
Iteration   1: 8.550 ops/ms
Iteration   2: 8.308 ops/ms
Iteration   3: 8.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.447 ±(99.9%) 2.282 ops/ms [Average]
  (min, avg, max) = (8.308, 8.447, 8.550), stdev = 0.125
  CI (99.9%): [6.165, 10.729] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.109 ops/ms
# Warmup Iteration   2: 6.877 ops/ms
# Warmup Iteration   3: 7.576 ops/ms
Iteration   1: 8.017 ops/ms
Iteration   2: 8.443 ops/ms
Iteration   3: 7.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.082 ±(99.9%) 6.090 ops/ms [Average]
  (min, avg, max) = (7.785, 8.082, 8.443), stdev = 0.334
  CI (99.9%): [1.992, 14.171] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.971 ops/ms
# Warmup Iteration   2: 5.562 ops/ms
# Warmup Iteration   3: 6.449 ops/ms
Iteration   1: 6.161 ops/ms
Iteration   2: 6.181 ops/ms
Iteration   3: 6.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.215 ±(99.9%) 1.408 ops/ms [Average]
  (min, avg, max) = (6.161, 6.215, 6.304), stdev = 0.077
  CI (99.9%): [4.807, 7.623] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.604 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.301 ±(99.9%) 0.003 ms/op
Iteration   1: 3.949 ±(99.9%) 0.004 ms/op
Iteration   2: 4.049 ±(99.9%) 0.003 ms/op
Iteration   3: 3.888 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.962 ±(99.9%) 1.482 ms/op [Average]
  (min, avg, max) = (3.888, 3.962, 4.049), stdev = 0.081
  CI (99.9%): [2.480, 5.445] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.343 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.002 ms/op
Iteration   1: 4.120 ±(99.9%) 0.003 ms/op
Iteration   2: 4.018 ±(99.9%) 0.003 ms/op
Iteration   3: 3.945 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.027 ±(99.9%) 1.606 ms/op [Average]
  (min, avg, max) = (3.945, 4.027, 4.120), stdev = 0.088
  CI (99.9%): [2.421, 5.633] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.897 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.010 ms/op
Iteration   1: 4.149 ±(99.9%) 0.002 ms/op
Iteration   2: 4.066 ±(99.9%) 0.002 ms/op
Iteration   3: 4.138 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.118 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (4.066, 4.118, 4.149), stdev = 0.045
  CI (99.9%): [3.303, 4.932] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.974 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.431 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.043 ±(99.9%) 0.018 ms/op
Iteration   1: 5.176 ±(99.9%) 0.010 ms/op
Iteration   2: 4.973 ±(99.9%) 0.009 ms/op
Iteration   3: 5.034 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.061 ±(99.9%) 1.909 ms/op [Average]
  (min, avg, max) = (4.973, 5.061, 5.176), stdev = 0.105
  CI (99.9%): [3.152, 6.969] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.182 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.280 ±(99.9%) 0.016 ms/op
Iteration   1: 4.082 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  14.036 ms/op
                 createUser·p0.9999: 17.607 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   2: 4.376 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   4.096 ms/op
                 createUser·p0.90:   5.825 ms/op
                 createUser·p0.95:   6.570 ms/op
                 createUser·p0.99:   8.372 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 20.285 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   3: 4.123 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.250 ms/op
                 createUser·p0.999:  12.203 ms/op
                 createUser·p0.9999: 22.691 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 229135
  mean =      4.190 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5100 
    [ 2.500,  5.000) = 188999 
    [ 5.000,  7.500) = 32322 
    [ 7.500, 10.000) = 2176 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     12.239 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     23.194 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.404 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.266 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.010 ms/op
Iteration   1: 3.870 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.284 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 15.822 ms/op
                 existUser·p1.00:   16.105 ms/op

Iteration   2: 3.825 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.801 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  10.043 ms/op
                 existUser·p0.9999: 17.289 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 3.802 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.637 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  9.869 ms/op
                 existUser·p0.9999: 18.150 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 250521
  mean =      3.832 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 6276 
    [ 2.500,  3.750) = 125973 
    [ 3.750,  5.000) = 100779 
    [ 5.000,  6.250) = 14400 
    [ 6.250,  7.500) = 1979 
    [ 7.500,  8.750) = 607 
    [ 8.750, 10.000) = 159 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 52 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =      9.904 ms/op
     p(99.9900) =     17.396 ms/op
     p(99.9990) =     18.677 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.467 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.279 ±(99.9%) 0.012 ms/op
Iteration   1: 4.180 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   4.055 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   7.741 ms/op
                 getUser·p0.999:  12.657 ms/op
                 getUser·p0.9999: 16.658 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 4.112 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   5.112 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 19.078 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   3: 4.148 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   5.612 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  11.554 ms/op
                 getUser·p0.9999: 20.508 ms/op
                 getUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231480
  mean =      4.147 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5134 
    [ 2.500,  5.000) = 196575 
    [ 5.000,  7.500) = 27720 
    [ 7.500, 10.000) = 1588 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     12.231 ms/op
     p(99.9900) =     20.049 ms/op
     p(99.9990) =     21.715 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 7.792 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.112 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.285 ±(99.9%) 0.020 ms/op
Iteration   1: 5.325 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  20.082 ms/op
                 listUser·p0.9999: 27.984 ms/op
                 listUser·p1.00:   28.410 ms/op

Iteration   2: 5.295 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   6.955 ms/op
                 listUser·p0.95:   7.920 ms/op
                 listUser·p0.99:   10.453 ms/op
                 listUser·p0.999:  30.258 ms/op
                 listUser·p0.9999: 50.526 ms/op
                 listUser·p1.00:   51.118 ms/op

Iteration   3: 5.144 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   4.882 ms/op
                 listUser·p0.90:   6.529 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  20.677 ms/op
                 listUser·p0.9999: 23.080 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 182623
  mean =      5.254 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 96677 
    [ 5.000, 10.000) = 84164 
    [10.000, 15.000) = 1451 
    [15.000, 20.000) = 82 
    [20.000, 25.000) = 151 
    [25.000, 30.000) = 37 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 25 
    [50.000, 55.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.799 ms/op
     p(95.0000) =      7.741 ms/op
     p(99.0000) =      9.961 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     49.152 ms/op
     p(99.9990) =     51.064 ms/op
     p(99.9999) =     51.118 ms/op
    p(100.0000) =     51.118 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.978 ± 0.937  ops/ms
ClientGrpc.existUser                       thrpt       3   8.447 ± 2.282  ops/ms
ClientGrpc.getUser                         thrpt       3   8.082 ± 6.090  ops/ms
ClientGrpc.listUser                        thrpt       3   6.215 ± 1.408  ops/ms
ClientGrpc.createUser                       avgt       3   3.962 ± 1.482   ms/op
ClientGrpc.existUser                        avgt       3   4.027 ± 1.606   ms/op
ClientGrpc.getUser                          avgt       3   4.118 ± 0.815   ms/op
ClientGrpc.listUser                         avgt       3   5.061 ± 1.909   ms/op
ClientGrpc.createUser                     sample  229135   4.190 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.021           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.341           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.939           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.725           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.239           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.529           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  250521   3.832 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.904           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.760           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.210           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.406           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.904           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.396           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.743           ms/op
ClientGrpc.getUser                        sample  231480   4.147 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.702           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.022           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.169           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.677           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.315           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.231           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.049           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.791           ms/op
ClientGrpc.listUser                       sample  182623   5.254 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.329           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.741           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.961           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.037           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          49.152           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          51.118           ms/op
