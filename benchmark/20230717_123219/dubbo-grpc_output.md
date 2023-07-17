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
# Warmup Iteration   1: 2.367 ops/ms
# Warmup Iteration   2: 5.144 ops/ms
# Warmup Iteration   3: 6.826 ops/ms
Iteration   1: 7.164 ops/ms
Iteration   2: 7.060 ops/ms
Iteration   3: 7.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.170 ±(99.9%) 2.071 ops/ms [Average]
  (min, avg, max) = (7.060, 7.170, 7.287), stdev = 0.114
  CI (99.9%): [5.099, 9.241] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.707 ops/ms
# Warmup Iteration   2: 7.086 ops/ms
# Warmup Iteration   3: 7.421 ops/ms
Iteration   1: 7.677 ops/ms
Iteration   2: 7.728 ops/ms
Iteration   3: 7.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.770 ±(99.9%) 2.175 ops/ms [Average]
  (min, avg, max) = (7.677, 7.770, 7.904), stdev = 0.119
  CI (99.9%): [5.594, 9.945] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ops/ms
# Warmup Iteration   2: 6.672 ops/ms
# Warmup Iteration   3: 6.889 ops/ms
Iteration   1: 7.166 ops/ms
Iteration   2: 7.248 ops/ms
Iteration   3: 7.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.224 ±(99.9%) 0.915 ops/ms [Average]
  (min, avg, max) = (7.166, 7.224, 7.257), stdev = 0.050
  CI (99.9%): [6.308, 8.139] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.629 ops/ms
# Warmup Iteration   2: 5.323 ops/ms
# Warmup Iteration   3: 5.557 ops/ms
Iteration   1: 5.588 ops/ms
Iteration   2: 5.672 ops/ms
Iteration   3: 5.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.619 ±(99.9%) 0.835 ops/ms [Average]
  (min, avg, max) = (5.588, 5.619, 5.672), stdev = 0.046
  CI (99.9%): [4.784, 6.454] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.209 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.786 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.582 ±(99.9%) 0.013 ms/op
Iteration   1: 4.484 ±(99.9%) 0.004 ms/op
Iteration   2: 4.430 ±(99.9%) 0.003 ms/op
Iteration   3: 4.406 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.440 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (4.406, 4.440, 4.484), stdev = 0.040
  CI (99.9%): [3.707, 5.173] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.466 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.488 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.300 ±(99.9%) 0.003 ms/op
Iteration   1: 4.100 ±(99.9%) 0.005 ms/op
Iteration   2: 4.225 ±(99.9%) 0.003 ms/op
Iteration   3: 4.243 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.190 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (4.100, 4.190, 4.243), stdev = 0.078
  CI (99.9%): [2.772, 5.607] (assumes normal distribution)


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
# Warmup Iteration   1: 7.101 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.886 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.526 ±(99.9%) 0.007 ms/op
Iteration   1: 4.395 ±(99.9%) 0.008 ms/op
Iteration   2: 4.497 ±(99.9%) 0.006 ms/op
Iteration   3: 4.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.456 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (4.395, 4.456, 4.497), stdev = 0.054
  CI (99.9%): [3.474, 5.438] (assumes normal distribution)


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
# Warmup Iteration   1: 8.522 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.920 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.677 ±(99.9%) 0.028 ms/op
Iteration   1: 5.502 ±(99.9%) 0.027 ms/op
Iteration   2: 5.629 ±(99.9%) 0.016 ms/op
Iteration   3: 5.551 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.561 ±(99.9%) 1.172 ms/op [Average]
  (min, avg, max) = (5.502, 5.561, 5.629), stdev = 0.064
  CI (99.9%): [4.388, 6.733] (assumes normal distribution)


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
# Warmup Iteration   1: 6.950 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.925 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.503 ±(99.9%) 0.012 ms/op
Iteration   1: 4.542 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.029 ms/op
                 createUser·p0.99:   8.218 ms/op
                 createUser·p0.999:  15.237 ms/op
                 createUser·p0.9999: 17.628 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   2: 4.439 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.497 ms/op
                 createUser·p0.95:   5.915 ms/op
                 createUser·p0.99:   7.805 ms/op
                 createUser·p0.999:  12.925 ms/op
                 createUser·p0.9999: 17.937 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   3: 4.583 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   4.473 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   7.819 ms/op
                 createUser·p0.999:  16.649 ms/op
                 createUser·p0.9999: 20.351 ms/op
                 createUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 212261
  mean =      4.521 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3739 
    [ 2.500,  5.000) = 157766 
    [ 5.000,  7.500) = 48131 
    [ 7.500, 10.000) = 1954 
    [10.000, 12.500) = 364 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     14.490 ms/op
     p(99.9900) =     19.351 ms/op
     p(99.9990) =     21.851 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 6.543 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.605 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.327 ±(99.9%) 0.011 ms/op
Iteration   1: 4.188 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.816 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  12.733 ms/op
                 existUser·p0.9999: 20.564 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   2: 4.367 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   4.268 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   6.994 ms/op
                 existUser·p0.999:  13.386 ms/op
                 existUser·p0.9999: 19.344 ms/op
                 existUser·p1.00:   19.956 ms/op

Iteration   3: 4.370 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   7.168 ms/op
                 existUser·p0.999:  13.722 ms/op
                 existUser·p0.9999: 21.037 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 222846
  mean =      4.307 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5715 
    [ 2.500,  5.000) = 180300 
    [ 5.000,  7.500) = 35168 
    [ 7.500, 10.000) = 1137 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.107 ms/op
     p(99.9000) =     13.274 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     22.248 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 6.934 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.730 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.487 ±(99.9%) 0.013 ms/op
Iteration   1: 4.462 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   5.980 ms/op
                 getUser·p0.99:   7.818 ms/op
                 getUser·p0.999:  14.494 ms/op
                 getUser·p0.9999: 17.127 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   2: 4.468 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.800 ms/op
                 getUser·p0.99:   7.091 ms/op
                 getUser·p0.999:  12.332 ms/op
                 getUser·p0.9999: 18.208 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   3: 4.419 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215749
  mean =      4.450 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 4157 
    [ 2.500,  3.750) = 32342 
    [ 3.750,  5.000) = 135787 
    [ 5.000,  6.250) = 37409 
    [ 6.250,  7.500) = 4093 
    [ 7.500,  8.750) = 944 
    [ 8.750, 10.000) = 404 
    [10.000, 11.250) = 177 
    [11.250, 12.500) = 195 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     18.266 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 7.689 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.253 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.670 ±(99.9%) 0.019 ms/op
Iteration   1: 5.777 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   10.243 ms/op
                 listUser·p0.999:  17.846 ms/op
                 listUser·p0.9999: 23.099 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 5.687 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  18.065 ms/op
                 listUser·p0.9999: 24.318 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   3: 5.547 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   6.988 ms/op
                 listUser·p0.95:   7.922 ms/op
                 listUser·p0.99:   9.929 ms/op
                 listUser·p0.999:  22.708 ms/op
                 listUser·p0.9999: 28.443 ms/op
                 listUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169389
  mean =      5.669 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 49631 
    [ 5.000,  7.500) = 106042 
    [ 7.500, 10.000) = 11607 
    [10.000, 12.500) = 1475 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      7.201 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     25.792 ms/op
     p(99.9990) =     28.808 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.170 ± 2.071  ops/ms
ClientGrpc.existUser                       thrpt       3   7.770 ± 2.175  ops/ms
ClientGrpc.getUser                         thrpt       3   7.224 ± 0.915  ops/ms
ClientGrpc.listUser                        thrpt       3   5.619 ± 0.835  ops/ms
ClientGrpc.createUser                       avgt       3   4.440 ± 0.733   ms/op
ClientGrpc.existUser                        avgt       3   4.190 ± 1.418   ms/op
ClientGrpc.getUser                          avgt       3   4.456 ± 0.982   ms/op
ClientGrpc.listUser                         avgt       3   5.561 ± 1.172   ms/op
ClientGrpc.createUser                     sample  212261   4.521 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.057           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.980           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.922           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.490           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.351           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.282           ms/op
ClientGrpc.existUser                      sample  222846   4.307 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.951           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.702           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.107           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.274           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.709           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.381           ms/op
ClientGrpc.getUser                        sample  215749   4.450 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.631           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.431           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.849           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.340           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.534           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.266           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.890           ms/op
ClientGrpc.listUser                       sample  169389   5.669 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.212           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.201           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.126           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.497           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.792           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.967           ms/op
