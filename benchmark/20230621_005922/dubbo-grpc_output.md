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
# Warmup Iteration   1: 2.226 ops/ms
# Warmup Iteration   2: 5.304 ops/ms
# Warmup Iteration   3: 7.339 ops/ms
Iteration   1: 7.493 ops/ms
Iteration   2: 7.466 ops/ms
Iteration   3: 7.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.577 ±(99.9%) 3.097 ops/ms [Average]
  (min, avg, max) = (7.466, 7.577, 7.773), stdev = 0.170
  CI (99.9%): [4.480, 10.674] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.288 ops/ms
# Warmup Iteration   2: 7.652 ops/ms
# Warmup Iteration   3: 8.245 ops/ms
Iteration   1: 8.113 ops/ms
Iteration   2: 8.370 ops/ms
Iteration   3: 8.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.213 ±(99.9%) 2.512 ops/ms [Average]
  (min, avg, max) = (8.113, 8.213, 8.370), stdev = 0.138
  CI (99.9%): [5.701, 10.724] (assumes normal distribution)


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
# Warmup Iteration   1: 4.257 ops/ms
# Warmup Iteration   2: 7.089 ops/ms
# Warmup Iteration   3: 7.356 ops/ms
Iteration   1: 7.654 ops/ms
Iteration   2: 7.605 ops/ms
Iteration   3: 7.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.551 ±(99.9%) 2.527 ops/ms [Average]
  (min, avg, max) = (7.393, 7.551, 7.654), stdev = 0.138
  CI (99.9%): [5.024, 10.077] (assumes normal distribution)


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
# Warmup Iteration   1: 3.568 ops/ms
# Warmup Iteration   2: 5.273 ops/ms
# Warmup Iteration   3: 5.622 ops/ms
Iteration   1: 5.711 ops/ms
Iteration   2: 5.721 ops/ms
Iteration   3: 5.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.730 ±(99.9%) 0.439 ops/ms [Average]
  (min, avg, max) = (5.711, 5.730, 5.757), stdev = 0.024
  CI (99.9%): [5.291, 6.169] (assumes normal distribution)


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
# Warmup Iteration   1: 7.290 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.118 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.647 ±(99.9%) 0.017 ms/op
Iteration   1: 4.385 ±(99.9%) 0.006 ms/op
Iteration   2: 4.333 ±(99.9%) 0.005 ms/op
Iteration   3: 4.602 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.440 ±(99.9%) 2.606 ms/op [Average]
  (min, avg, max) = (4.333, 4.440, 4.602), stdev = 0.143
  CI (99.9%): [1.834, 7.046] (assumes normal distribution)


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
# Warmup Iteration   1: 6.105 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.005 ms/op
Iteration   1: 3.946 ±(99.9%) 0.003 ms/op
Iteration   2: 3.804 ±(99.9%) 0.004 ms/op
Iteration   3: 3.820 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.857 ±(99.9%) 1.420 ms/op [Average]
  (min, avg, max) = (3.804, 3.857, 3.946), stdev = 0.078
  CI (99.9%): [2.437, 5.276] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.788 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.004 ms/op
Iteration   1: 4.187 ±(99.9%) 0.004 ms/op
Iteration   2: 4.159 ±(99.9%) 0.032 ms/op
Iteration   3: 4.114 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.153 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (4.114, 4.153, 4.187), stdev = 0.037
  CI (99.9%): [3.486, 4.821] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.682 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.600 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.430 ±(99.9%) 0.022 ms/op
Iteration   1: 5.351 ±(99.9%) 0.018 ms/op
Iteration   2: 5.493 ±(99.9%) 0.023 ms/op
Iteration   3: 5.263 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.369 ±(99.9%) 2.123 ms/op [Average]
  (min, avg, max) = (5.263, 5.369, 5.493), stdev = 0.116
  CI (99.9%): [3.246, 7.492] (assumes normal distribution)


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
# Warmup Iteration   1: 6.966 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.704 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.545 ±(99.9%) 0.017 ms/op
Iteration   1: 4.478 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.595 ms/op
                 createUser·p0.99:   9.814 ms/op
                 createUser·p0.999:  16.721 ms/op
                 createUser·p0.9999: 24.609 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   2: 4.308 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   4.137 ms/op
                 createUser·p0.90:   5.374 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  15.962 ms/op
                 createUser·p0.9999: 27.296 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   3: 4.104 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   5.161 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   7.610 ms/op
                 createUser·p0.999:  11.748 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 223773
  mean =      4.291 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5390 
    [ 2.500,  5.000) = 181574 
    [ 5.000,  7.500) = 32419 
    [ 7.500, 10.000) = 3083 
    [10.000, 12.500) = 892 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     15.006 ms/op
     p(99.9900) =     25.711 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 5.689 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.012 ms/op
Iteration   1: 3.996 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   8.585 ms/op
                 existUser·p0.999:  14.379 ms/op
                 existUser·p0.9999: 19.464 ms/op
                 existUser·p1.00:   21.365 ms/op

Iteration   2: 3.912 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.673 ms/op
                 existUser·p0.99:   7.971 ms/op
                 existUser·p0.999:  12.020 ms/op
                 existUser·p0.9999: 24.269 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   3: 3.895 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   7.447 ms/op
                 existUser·p0.999:  11.279 ms/op
                 existUser·p0.9999: 24.012 ms/op
                 existUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 244113
  mean =      3.934 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9339 
    [ 2.500,  5.000) = 210201 
    [ 5.000,  7.500) = 21237 
    [ 7.500, 10.000) = 2611 
    [10.000, 12.500) = 478 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     12.565 ms/op
     p(99.9900) =     23.828 ms/op
     p(99.9990) =     25.033 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 6.131 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.539 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.344 ±(99.9%) 0.013 ms/op
Iteration   1: 4.237 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   4.112 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  12.117 ms/op
                 getUser·p0.9999: 20.560 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   2: 4.137 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   8.200 ms/op
                 getUser·p0.999:  14.156 ms/op
                 getUser·p0.9999: 23.766 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   3: 4.190 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   8.272 ms/op
                 getUser·p0.999:  12.480 ms/op
                 getUser·p0.9999: 22.708 ms/op
                 getUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 229120
  mean =      4.188 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5216 
    [ 2.500,  5.000) = 191054 
    [ 5.000,  7.500) = 29717 
    [ 7.500, 10.000) = 2399 
    [10.000, 12.500) = 488 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      8.051 ms/op
     p(99.9000) =     12.909 ms/op
     p(99.9900) =     23.468 ms/op
     p(99.9990) =     24.079 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 8.712 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.011 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.545 ±(99.9%) 0.020 ms/op
Iteration   1: 5.328 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   7.143 ms/op
                 listUser·p0.95:   8.094 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  16.350 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   2: 5.509 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.599 ms/op
                 listUser·p0.50:   5.198 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.266 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  19.234 ms/op
                 listUser·p0.9999: 22.798 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   3: 5.336 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   7.102 ms/op
                 listUser·p0.95:   8.036 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  19.386 ms/op
                 listUser·p0.9999: 25.003 ms/op
                 listUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178001
  mean =      5.390 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 228 
    [ 2.500,  5.000) = 82414 
    [ 5.000,  7.500) = 81236 
    [ 7.500, 10.000) = 11391 
    [10.000, 12.500) = 1924 
    [12.500, 15.000) = 394 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.577 ± 3.097  ops/ms
ClientGrpc.existUser                       thrpt       3   8.213 ± 2.512  ops/ms
ClientGrpc.getUser                         thrpt       3   7.551 ± 2.527  ops/ms
ClientGrpc.listUser                        thrpt       3   5.730 ± 0.439  ops/ms
ClientGrpc.createUser                       avgt       3   4.440 ± 2.606   ms/op
ClientGrpc.existUser                        avgt       3   3.857 ± 1.420   ms/op
ClientGrpc.getUser                          avgt       3   4.153 ± 0.668   ms/op
ClientGrpc.listUser                         avgt       3   5.369 ± 2.123   ms/op
ClientGrpc.createUser                     sample  223773   4.291 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.698           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.116           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.415           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.095           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.929           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.006           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.711           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.329           ms/op
ClientGrpc.existUser                      sample  244113   3.934 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.731           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.005           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.628           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.086           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.565           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.828           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.149           ms/op
ClientGrpc.getUser                        sample  229120   4.188 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.765           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.267           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.849           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.051           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.909           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.468           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.248           ms/op
ClientGrpc.listUser                       sample  178001   5.390 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.358           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.126           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.797           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.121           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.412           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.049           ms/op
