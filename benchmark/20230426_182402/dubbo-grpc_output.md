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
# Warmup Iteration   1: 2.022 ops/ms
# Warmup Iteration   2: 4.590 ops/ms
# Warmup Iteration   3: 6.505 ops/ms
Iteration   1: 6.633 ops/ms
Iteration   2: 6.802 ops/ms
Iteration   3: 6.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.765 ±(99.9%) 2.163 ops/ms [Average]
  (min, avg, max) = (6.633, 6.765, 6.861), stdev = 0.119
  CI (99.9%): [4.602, 8.929] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ops/ms
# Warmup Iteration   2: 6.546 ops/ms
# Warmup Iteration   3: 7.248 ops/ms
Iteration   1: 7.259 ops/ms
Iteration   2: 7.275 ops/ms
Iteration   3: 7.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.301 ±(99.9%) 1.080 ops/ms [Average]
  (min, avg, max) = (7.259, 7.301, 7.369), stdev = 0.059
  CI (99.9%): [6.221, 8.381] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ops/ms
# Warmup Iteration   2: 5.552 ops/ms
# Warmup Iteration   3: 6.612 ops/ms
Iteration   1: 6.810 ops/ms
Iteration   2: 6.844 ops/ms
Iteration   3: 6.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.821 ±(99.9%) 0.353 ops/ms [Average]
  (min, avg, max) = (6.810, 6.821, 6.844), stdev = 0.019
  CI (99.9%): [6.468, 7.175] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.188 ops/ms
# Warmup Iteration   2: 4.522 ops/ms
# Warmup Iteration   3: 5.260 ops/ms
Iteration   1: 5.211 ops/ms
Iteration   2: 5.164 ops/ms
Iteration   3: 5.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.217 ±(99.9%) 1.024 ops/ms [Average]
  (min, avg, max) = (5.164, 5.217, 5.276), stdev = 0.056
  CI (99.9%): [4.193, 6.241] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.511 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.000 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.901 ±(99.9%) 0.018 ms/op
Iteration   1: 4.644 ±(99.9%) 0.003 ms/op
Iteration   2: 4.652 ±(99.9%) 0.003 ms/op
Iteration   3: 4.566 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.621 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (4.566, 4.621, 4.652), stdev = 0.047
  CI (99.9%): [3.757, 5.484] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.999 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.854 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.523 ±(99.9%) 0.005 ms/op
Iteration   1: 4.430 ±(99.9%) 0.004 ms/op
Iteration   2: 4.481 ±(99.9%) 0.004 ms/op
Iteration   3: 4.387 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.433 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (4.387, 4.433, 4.481), stdev = 0.047
  CI (99.9%): [3.579, 5.287] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.220 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.369 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.869 ±(99.9%) 0.003 ms/op
Iteration   1: 4.697 ±(99.9%) 0.004 ms/op
Iteration   2: 4.708 ±(99.9%) 0.004 ms/op
Iteration   3: 4.642 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.682 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (4.642, 4.682, 4.708), stdev = 0.036
  CI (99.9%): [4.032, 5.332] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.095 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 6.908 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 6.102 ±(99.9%) 0.012 ms/op
Iteration   1: 6.023 ±(99.9%) 0.018 ms/op
Iteration   2: 5.934 ±(99.9%) 0.018 ms/op
Iteration   3: 6.122 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.026 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (5.934, 6.026, 6.122), stdev = 0.094
  CI (99.9%): [4.306, 7.747] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.789 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.097 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.746 ±(99.9%) 0.016 ms/op
Iteration   1: 4.655 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   5.800 ms/op
                 createUser·p0.95:   6.365 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  11.495 ms/op
                 createUser·p0.9999: 32.351 ms/op
                 createUser·p1.00:   33.686 ms/op

Iteration   2: 4.702 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   4.579 ms/op
                 createUser·p0.90:   6.013 ms/op
                 createUser·p0.95:   6.595 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  12.071 ms/op
                 createUser·p0.9999: 30.178 ms/op
                 createUser·p1.00:   30.802 ms/op

Iteration   3: 4.712 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   4.563 ms/op
                 createUser·p0.90:   5.857 ms/op
                 createUser·p0.95:   6.414 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  17.466 ms/op
                 createUser·p0.9999: 31.189 ms/op
                 createUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 204729
  mean =      4.690 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4188 
    [ 2.500,  5.000) = 137629 
    [ 5.000,  7.500) = 58970 
    [ 7.500, 10.000) = 3197 
    [10.000, 12.500) = 502 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.898 ms/op
     p(95.0000) =      6.472 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     13.534 ms/op
     p(99.9900) =     31.868 ms/op
     p(99.9990) =     33.010 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.772 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.503 ±(99.9%) 0.013 ms/op
Iteration   1: 4.301 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   4.186 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   6.021 ms/op
                 existUser·p0.99:   7.807 ms/op
                 existUser·p0.999:  11.855 ms/op
                 existUser·p0.9999: 17.778 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   2: 4.358 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   5.956 ms/op
                 existUser·p0.99:   7.709 ms/op
                 existUser·p0.999:  17.295 ms/op
                 existUser·p0.9999: 23.658 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 4.329 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.890 ms/op
                 existUser·p0.99:   7.747 ms/op
                 existUser·p0.999:  13.421 ms/op
                 existUser·p0.9999: 21.254 ms/op
                 existUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 221704
  mean =      4.329 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5911 
    [ 2.500,  5.000) = 180197 
    [ 5.000,  7.500) = 32984 
    [ 7.500, 10.000) = 1986 
    [10.000, 12.500) = 347 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     13.341 ms/op
     p(99.9900) =     22.746 ms/op
     p(99.9990) =     23.750 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.474 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.047 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.821 ±(99.9%) 0.017 ms/op
Iteration   1: 4.774 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   6.013 ms/op
                 getUser·p0.95:   6.562 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  15.696 ms/op
                 getUser·p0.9999: 17.770 ms/op
                 getUser·p1.00:   17.990 ms/op

Iteration   2: 4.676 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   6.054 ms/op
                 getUser·p0.95:   6.709 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  14.577 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   3: 4.695 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   5.849 ms/op
                 getUser·p0.95:   6.362 ms/op
                 getUser·p0.99:   8.061 ms/op
                 getUser·p0.999:  13.222 ms/op
                 getUser·p0.9999: 24.457 ms/op
                 getUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 203563
  mean =      4.714 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5393 
    [ 2.500,  5.000) = 131953 
    [ 5.000,  7.500) = 62151 
    [ 7.500, 10.000) = 3116 
    [10.000, 12.500) = 643 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.972 ms/op
     p(95.0000) =      6.545 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     14.392 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     25.195 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.196 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 7.068 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.224 ±(99.9%) 0.025 ms/op
Iteration   1: 6.292 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   8.782 ms/op
                 listUser·p0.95:   9.798 ms/op
                 listUser·p0.99:   12.024 ms/op
                 listUser·p0.999:  18.386 ms/op
                 listUser·p0.9999: 20.441 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   2: 6.270 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   5.800 ms/op
                 listUser·p0.90:   8.749 ms/op
                 listUser·p0.95:   9.994 ms/op
                 listUser·p0.99:   12.747 ms/op
                 listUser·p0.999:  20.414 ms/op
                 listUser·p0.9999: 25.159 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 6.111 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   8.700 ms/op
                 listUser·p0.95:   9.699 ms/op
                 listUser·p0.99:   12.075 ms/op
                 listUser·p0.999:  22.107 ms/op
                 listUser·p0.9999: 27.452 ms/op
                 listUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 154358
  mean =      6.223 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 141 
    [ 2.500,  5.000) = 38030 
    [ 5.000,  7.500) = 86110 
    [ 7.500, 10.000) = 23173 
    [10.000, 12.500) = 5509 
    [12.500, 15.000) = 924 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      5.775 ms/op
     p(90.0000) =      8.749 ms/op
     p(95.0000) =      9.830 ms/op
     p(99.0000) =     12.304 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     26.211 ms/op
     p(99.9990) =     28.166 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.765 ± 2.163  ops/ms
ClientGrpc.existUser                       thrpt       3   7.301 ± 1.080  ops/ms
ClientGrpc.getUser                         thrpt       3   6.821 ± 0.353  ops/ms
ClientGrpc.listUser                        thrpt       3   5.217 ± 1.024  ops/ms
ClientGrpc.createUser                       avgt       3   4.621 ± 0.863   ms/op
ClientGrpc.existUser                        avgt       3   4.433 ± 0.854   ms/op
ClientGrpc.getUser                          avgt       3   4.682 ± 0.650   ms/op
ClientGrpc.listUser                         avgt       3   6.026 ± 1.721   ms/op
ClientGrpc.createUser                     sample  204729   4.690 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.995           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.898           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.472           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.438           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.534           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.868           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.686           ms/op
ClientGrpc.existUser                      sample  221704   4.329 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.950           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.374           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.956           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.758           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.341           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.746           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.002           ms/op
ClientGrpc.getUser                        sample  203563   4.714 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.143           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.972           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.545           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.454           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.392           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.118           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.297           ms/op
ClientGrpc.listUser                       sample  154358   6.223 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.534           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.749           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.830           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.304           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.414           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.211           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.344           ms/op
