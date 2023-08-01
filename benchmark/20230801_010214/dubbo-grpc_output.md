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
# Warmup Iteration   1: 2.265 ops/ms
# Warmup Iteration   2: 5.622 ops/ms
# Warmup Iteration   3: 6.963 ops/ms
Iteration   1: 7.399 ops/ms
Iteration   2: 7.551 ops/ms
Iteration   3: 7.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.494 ±(99.9%) 1.512 ops/ms [Average]
  (min, avg, max) = (7.399, 7.494, 7.551), stdev = 0.083
  CI (99.9%): [5.983, 9.006] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.641 ops/ms
# Warmup Iteration   2: 7.371 ops/ms
# Warmup Iteration   3: 8.267 ops/ms
Iteration   1: 8.154 ops/ms
Iteration   2: 8.301 ops/ms
Iteration   3: 8.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.272 ±(99.9%) 1.959 ops/ms [Average]
  (min, avg, max) = (8.154, 8.272, 8.363), stdev = 0.107
  CI (99.9%): [6.313, 10.232] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.309 ops/ms
# Warmup Iteration   2: 7.020 ops/ms
# Warmup Iteration   3: 7.379 ops/ms
Iteration   1: 7.646 ops/ms
Iteration   2: 7.554 ops/ms
Iteration   3: 7.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.639 ±(99.9%) 1.490 ops/ms [Average]
  (min, avg, max) = (7.554, 7.639, 7.717), stdev = 0.082
  CI (99.9%): [6.149, 9.129] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.389 ops/ms
# Warmup Iteration   2: 5.445 ops/ms
# Warmup Iteration   3: 5.845 ops/ms
Iteration   1: 5.870 ops/ms
Iteration   2: 6.014 ops/ms
Iteration   3: 5.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.957 ±(99.9%) 1.397 ops/ms [Average]
  (min, avg, max) = (5.870, 5.957, 6.014), stdev = 0.077
  CI (99.9%): [4.560, 7.354] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.704 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.003 ms/op
Iteration   1: 4.269 ±(99.9%) 0.003 ms/op
Iteration   2: 4.229 ±(99.9%) 0.003 ms/op
Iteration   3: 4.150 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.216 ±(99.9%) 1.109 ms/op [Average]
  (min, avg, max) = (4.150, 4.216, 4.269), stdev = 0.061
  CI (99.9%): [3.107, 5.325] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.066 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.003 ms/op
Iteration   1: 3.824 ±(99.9%) 0.003 ms/op
Iteration   2: 3.835 ±(99.9%) 0.002 ms/op
Iteration   3: 3.925 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.861 ±(99.9%) 1.013 ms/op [Average]
  (min, avg, max) = (3.824, 3.861, 3.925), stdev = 0.056
  CI (99.9%): [2.848, 4.875] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.574 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.003 ms/op
Iteration   1: 4.084 ±(99.9%) 0.005 ms/op
Iteration   2: 4.048 ±(99.9%) 0.003 ms/op
Iteration   3: 4.086 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.073 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (4.048, 4.073, 4.086), stdev = 0.021
  CI (99.9%): [3.685, 4.460] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.673 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.940 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.701 ±(99.9%) 0.014 ms/op
Iteration   1: 5.478 ±(99.9%) 0.027 ms/op
Iteration   2: 5.402 ±(99.9%) 0.027 ms/op
Iteration   3: 5.482 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.454 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (5.402, 5.454, 5.482), stdev = 0.045
  CI (99.9%): [4.634, 6.273] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.783 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.613 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.409 ±(99.9%) 0.014 ms/op
Iteration   1: 4.230 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   4.096 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   7.897 ms/op
                 createUser·p0.999:  12.588 ms/op
                 createUser·p0.9999: 22.849 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 4.289 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   4.141 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  14.198 ms/op
                 createUser·p0.9999: 23.611 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   3: 4.188 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   5.267 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.045 ms/op
                 createUser·p0.999:  13.074 ms/op
                 createUser·p0.9999: 31.687 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 226622
  mean =      4.235 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6141 
    [ 2.500,  5.000) = 181987 
    [ 5.000,  7.500) = 36044 
    [ 7.500, 10.000) = 1914 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     13.113 ms/op
     p(99.9900) =     30.955 ms/op
     p(99.9990) =     32.178 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.083 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.012 ms/op
Iteration   1: 4.093 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   3.953 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   7.242 ms/op
                 existUser·p0.999:  10.977 ms/op
                 existUser·p0.9999: 16.986 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   2: 3.952 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  12.881 ms/op
                 existUser·p0.9999: 17.105 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   3: 3.893 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.817 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   7.331 ms/op
                 existUser·p0.999:  13.490 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 241218
  mean =      3.977 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5961 
    [ 2.500,  5.000) = 212292 
    [ 5.000,  7.500) = 20984 
    [ 7.500, 10.000) = 1423 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     22.799 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.788 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.428 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.014 ms/op
Iteration   1: 4.226 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   4.076 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   7.581 ms/op
                 getUser·p0.999:  12.212 ms/op
                 getUser·p0.9999: 25.686 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   2: 4.035 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  9.281 ms/op
                 getUser·p0.9999: 25.332 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 4.162 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   5.702 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  14.486 ms/op
                 getUser·p0.9999: 29.010 ms/op
                 getUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231850
  mean =      4.140 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6476 
    [ 2.500,  5.000) = 195318 
    [ 5.000,  7.500) = 27818 
    [ 7.500, 10.000) = 1660 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     12.583 ms/op
     p(99.9900) =     28.064 ms/op
     p(99.9990) =     29.329 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 8.461 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.838 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.508 ±(99.9%) 0.020 ms/op
Iteration   1: 5.514 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.837 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.339 ms/op
                 listUser·p0.99:   10.453 ms/op
                 listUser·p0.999:  18.513 ms/op
                 listUser·p0.9999: 21.941 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 5.378 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   5.095 ms/op
                 listUser·p0.90:   7.135 ms/op
                 listUser·p0.95:   8.126 ms/op
                 listUser·p0.99:   10.263 ms/op
                 listUser·p0.999:  20.203 ms/op
                 listUser·p0.9999: 22.490 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   3: 5.426 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.585 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   6.988 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   10.525 ms/op
                 listUser·p0.999:  21.073 ms/op
                 listUser·p0.9999: 28.271 ms/op
                 listUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176433
  mean =      5.439 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 104 
    [ 2.500,  5.000) = 76703 
    [ 5.000,  7.500) = 85217 
    [ 7.500, 10.000) = 12088 
    [10.000, 12.500) = 1675 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.184 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     30.661 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.494 ± 1.512  ops/ms
ClientGrpc.existUser                       thrpt       3   8.272 ± 1.959  ops/ms
ClientGrpc.getUser                         thrpt       3   7.639 ± 1.490  ops/ms
ClientGrpc.listUser                        thrpt       3   5.957 ± 1.397  ops/ms
ClientGrpc.createUser                       avgt       3   4.216 ± 1.109   ms/op
ClientGrpc.existUser                        avgt       3   3.861 ± 1.013   ms/op
ClientGrpc.getUser                          avgt       3   4.073 ± 0.387   ms/op
ClientGrpc.listUser                         avgt       3   5.454 ± 0.820   ms/op
ClientGrpc.createUser                     sample  226622   4.235 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.059           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.407           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.915           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.602           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.113           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.955           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.375           ms/op
ClientGrpc.existUser                      sample  241218   3.977 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.922           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.964           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.464           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.242           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.517           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.202           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.938           ms/op
ClientGrpc.getUser                        sample  231850   4.140 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.988           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.177           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.661           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.438           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.583           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.064           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.458           ms/op
ClientGrpc.listUser                       sample  176433   5.439 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.491           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.184           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.420           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.694           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.938           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.736           ms/op
