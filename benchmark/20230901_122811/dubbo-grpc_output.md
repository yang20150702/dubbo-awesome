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
# Warmup Iteration   1: 1.983 ops/ms
# Warmup Iteration   2: 4.725 ops/ms
# Warmup Iteration   3: 6.433 ops/ms
Iteration   1: 6.481 ops/ms
Iteration   2: 6.774 ops/ms
Iteration   3: 6.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.575 ±(99.9%) 3.155 ops/ms [Average]
  (min, avg, max) = (6.468, 6.575, 6.774), stdev = 0.173
  CI (99.9%): [3.419, 9.730] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.493 ops/ms
# Warmup Iteration   2: 6.488 ops/ms
# Warmup Iteration   3: 6.967 ops/ms
Iteration   1: 7.166 ops/ms
Iteration   2: 7.157 ops/ms
Iteration   3: 7.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.277 ±(99.9%) 3.657 ops/ms [Average]
  (min, avg, max) = (7.157, 7.277, 7.509), stdev = 0.200
  CI (99.9%): [3.621, 10.934] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ops/ms
# Warmup Iteration   2: 5.984 ops/ms
# Warmup Iteration   3: 6.475 ops/ms
Iteration   1: 6.794 ops/ms
Iteration   2: 6.751 ops/ms
Iteration   3: 6.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.758 ±(99.9%) 0.590 ops/ms [Average]
  (min, avg, max) = (6.730, 6.758, 6.794), stdev = 0.032
  CI (99.9%): [6.168, 7.348] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.218 ops/ms
# Warmup Iteration   2: 4.679 ops/ms
# Warmup Iteration   3: 5.146 ops/ms
Iteration   1: 5.115 ops/ms
Iteration   2: 5.019 ops/ms
Iteration   3: 5.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.066 ±(99.9%) 0.884 ops/ms [Average]
  (min, avg, max) = (5.019, 5.066, 5.115), stdev = 0.048
  CI (99.9%): [4.182, 5.950] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.654 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.181 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.894 ±(99.9%) 0.012 ms/op
Iteration   1: 4.977 ±(99.9%) 0.004 ms/op
Iteration   2: 4.789 ±(99.9%) 0.003 ms/op
Iteration   3: 4.588 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.785 ±(99.9%) 3.552 ms/op [Average]
  (min, avg, max) = (4.588, 4.785, 4.977), stdev = 0.195
  CI (99.9%): [1.233, 8.336] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.806 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.943 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.640 ±(99.9%) 0.009 ms/op
Iteration   1: 4.589 ±(99.9%) 0.004 ms/op
Iteration   2: 4.615 ±(99.9%) 0.004 ms/op
Iteration   3: 4.422 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.542 ±(99.9%) 1.905 ms/op [Average]
  (min, avg, max) = (4.422, 4.542, 4.615), stdev = 0.104
  CI (99.9%): [2.637, 6.447] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.405 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.205 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.871 ±(99.9%) 0.005 ms/op
Iteration   1: 4.866 ±(99.9%) 0.004 ms/op
Iteration   2: 4.862 ±(99.9%) 0.006 ms/op
Iteration   3: 5.021 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.916 ±(99.9%) 1.654 ms/op [Average]
  (min, avg, max) = (4.862, 4.916, 5.021), stdev = 0.091
  CI (99.9%): [3.262, 6.570] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.629 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 7.360 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.326 ±(99.9%) 0.030 ms/op
Iteration   1: 6.171 ±(99.9%) 0.031 ms/op
Iteration   2: 6.220 ±(99.9%) 0.032 ms/op
Iteration   3: 6.151 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.180 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (6.151, 6.180, 6.220), stdev = 0.035
  CI (99.9%): [5.536, 6.825] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.929 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.367 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.089 ±(99.9%) 0.018 ms/op
Iteration   1: 4.854 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   4.645 ms/op
                 createUser·p0.90:   6.226 ms/op
                 createUser·p0.95:   6.873 ms/op
                 createUser·p0.99:   9.388 ms/op
                 createUser·p0.999:  16.126 ms/op
                 createUser·p0.9999: 20.690 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   2: 4.923 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   4.751 ms/op
                 createUser·p0.90:   6.193 ms/op
                 createUser·p0.95:   6.717 ms/op
                 createUser·p0.99:   8.815 ms/op
                 createUser·p0.999:  15.112 ms/op
                 createUser·p0.9999: 20.759 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   3: 4.906 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   6.193 ms/op
                 createUser·p0.95:   6.660 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  13.547 ms/op
                 createUser·p0.9999: 19.677 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 196079
  mean =      4.894 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1782 
    [ 2.500,  5.000) = 118491 
    [ 5.000,  7.500) = 71138 
    [ 7.500, 10.000) = 3513 
    [10.000, 12.500) = 744 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.201 ms/op
     p(95.0000) =      6.742 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     15.203 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     21.392 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.991 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.794 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.489 ±(99.9%) 0.013 ms/op
Iteration   1: 4.483 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   4.366 ms/op
                 existUser·p0.90:   5.718 ms/op
                 existUser·p0.95:   6.242 ms/op
                 existUser·p0.99:   7.905 ms/op
                 existUser·p0.999:  10.905 ms/op
                 existUser·p0.9999: 16.000 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   2: 4.536 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.743 ms/op
                 existUser·p0.95:   6.210 ms/op
                 existUser·p0.99:   8.012 ms/op
                 existUser·p0.999:  12.665 ms/op
                 existUser·p0.9999: 18.538 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   3: 4.437 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   4.325 ms/op
                 existUser·p0.90:   5.554 ms/op
                 existUser·p0.95:   6.054 ms/op
                 existUser·p0.99:   7.432 ms/op
                 existUser·p0.999:  10.632 ms/op
                 existUser·p0.9999: 20.663 ms/op
                 existUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 214012
  mean =      4.485 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4419 
    [ 2.500,  5.000) = 157630 
    [ 5.000,  7.500) = 49263 
    [ 7.500, 10.000) = 2250 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     20.008 ms/op
     p(99.9990) =     21.047 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.632 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.094 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.927 ±(99.9%) 0.017 ms/op
Iteration   1: 4.790 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   6.021 ms/op
                 getUser·p0.95:   6.595 ms/op
                 getUser·p0.99:   8.913 ms/op
                 getUser·p0.999:  15.602 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 4.751 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   4.604 ms/op
                 getUser·p0.90:   6.070 ms/op
                 getUser·p0.95:   6.554 ms/op
                 getUser·p0.99:   8.143 ms/op
                 getUser·p0.999:  11.997 ms/op
                 getUser·p0.9999: 26.821 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   3: 4.708 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   4.538 ms/op
                 getUser·p0.90:   6.038 ms/op
                 getUser·p0.95:   6.595 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  14.110 ms/op
                 getUser·p0.9999: 26.359 ms/op
                 getUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 202060
  mean =      4.749 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3403 
    [ 2.500,  5.000) = 132508 
    [ 5.000,  7.500) = 62207 
    [ 7.500, 10.000) = 2967 
    [10.000, 12.500) = 685 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      6.578 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     14.024 ms/op
     p(99.9900) =     26.332 ms/op
     p(99.9990) =     27.228 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.710 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 6.597 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 6.242 ±(99.9%) 0.025 ms/op
Iteration   1: 6.239 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.862 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   9.601 ms/op
                 listUser·p0.99:   12.573 ms/op
                 listUser·p0.999:  19.856 ms/op
                 listUser·p0.9999: 33.538 ms/op
                 listUser·p1.00:   34.144 ms/op

Iteration   2: 6.049 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   8.339 ms/op
                 listUser·p0.95:   9.408 ms/op
                 listUser·p0.99:   11.993 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 25.035 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 6.009 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   5.595 ms/op
                 listUser·p0.90:   8.331 ms/op
                 listUser·p0.95:   9.355 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  21.423 ms/op
                 listUser·p0.9999: 31.830 ms/op
                 listUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 157439
  mean =      6.097 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 40535 
    [ 5.000,  7.500) = 90865 
    [ 7.500, 10.000) = 20377 
    [10.000, 12.500) = 4215 
    [12.500, 15.000) = 941 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      5.685 ms/op
     p(90.0000) =      8.389 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     12.206 ms/op
     p(99.9000) =     20.498 ms/op
     p(99.9900) =     31.892 ms/op
     p(99.9990) =     34.069 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.575 ± 3.155  ops/ms
ClientGrpc.existUser                       thrpt       3   7.277 ± 3.657  ops/ms
ClientGrpc.getUser                         thrpt       3   6.758 ± 0.590  ops/ms
ClientGrpc.listUser                        thrpt       3   5.066 ± 0.884  ops/ms
ClientGrpc.createUser                       avgt       3   4.785 ± 3.552   ms/op
ClientGrpc.existUser                        avgt       3   4.542 ± 1.905   ms/op
ClientGrpc.getUser                          avgt       3   4.916 ± 1.654   ms/op
ClientGrpc.listUser                         avgt       3   6.180 ± 0.644   ms/op
ClientGrpc.createUser                     sample  196079   4.894 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.163           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.201           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.742           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.913           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.203           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.709           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.053           ms/op
ClientGrpc.existUser                      sample  214012   4.485 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.933           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.177           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.807           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.452           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.008           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.201           ms/op
ClientGrpc.getUser                        sample  202060   4.749 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.751           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.046           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.578           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.602           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.024           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.332           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.394           ms/op
ClientGrpc.listUser                       sample  157439   6.097 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.622           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.389           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.454           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.206           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.498           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.892           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.144           ms/op
