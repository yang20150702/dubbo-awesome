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
# Warmup Iteration   1: 4.177 ops/ms
# Warmup Iteration   2: 9.535 ops/ms
# Warmup Iteration   3: 10.093 ops/ms
Iteration   1: 10.468 ops/ms
Iteration   2: 10.425 ops/ms
Iteration   3: 10.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.519 ±(99.9%) 2.321 ops/ms [Average]
  (min, avg, max) = (10.425, 10.519, 10.663), stdev = 0.127
  CI (99.9%): [8.198, 12.839] (assumes normal distribution)


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
# Warmup Iteration   1: 8.135 ops/ms
# Warmup Iteration   2: 10.705 ops/ms
# Warmup Iteration   3: 11.159 ops/ms
Iteration   1: 11.160 ops/ms
Iteration   2: 11.179 ops/ms
Iteration   3: 11.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.156 ±(99.9%) 0.470 ops/ms [Average]
  (min, avg, max) = (11.128, 11.156, 11.179), stdev = 0.026
  CI (99.9%): [10.686, 11.626] (assumes normal distribution)


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
# Warmup Iteration   1: 7.386 ops/ms
# Warmup Iteration   2: 10.410 ops/ms
# Warmup Iteration   3: 10.646 ops/ms
Iteration   1: 10.665 ops/ms
Iteration   2: 10.783 ops/ms
Iteration   3: 10.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.764 ±(99.9%) 1.669 ops/ms [Average]
  (min, avg, max) = (10.665, 10.764, 10.845), stdev = 0.091
  CI (99.9%): [9.096, 12.433] (assumes normal distribution)


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
# Warmup Iteration   1: 6.110 ops/ms
# Warmup Iteration   2: 8.069 ops/ms
# Warmup Iteration   3: 8.277 ops/ms
Iteration   1: 8.364 ops/ms
Iteration   2: 8.295 ops/ms
Iteration   3: 8.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.382 ±(99.9%) 1.782 ops/ms [Average]
  (min, avg, max) = (8.295, 8.382, 8.487), stdev = 0.098
  CI (99.9%): [6.600, 10.164] (assumes normal distribution)


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.004 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
Iteration   3: 3.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.035 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.005, 3.035, 3.052), stdev = 0.026
  CI (99.9%): [2.563, 3.508] (assumes normal distribution)


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.808 ±(99.9%) 0.004 ms/op
Iteration   1: 2.882 ±(99.9%) 0.002 ms/op
Iteration   2: 2.850 ±(99.9%) 0.005 ms/op
Iteration   3: 2.854 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.862 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (2.850, 2.862, 2.882), stdev = 0.017
  CI (99.9%): [2.544, 3.180] (assumes normal distribution)


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.003 ms/op
Iteration   1: 3.005 ±(99.9%) 0.002 ms/op
Iteration   2: 2.969 ±(99.9%) 0.003 ms/op
Iteration   3: 2.989 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.988 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (2.969, 2.988, 3.005), stdev = 0.018
  CI (99.9%): [2.660, 3.316] (assumes normal distribution)


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
# Warmup Iteration   1: 5.157 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.027 ms/op
Iteration   1: 3.891 ±(99.9%) 0.019 ms/op
Iteration   2: 3.832 ±(99.9%) 0.009 ms/op
Iteration   3: 3.917 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.880 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (3.832, 3.880, 3.917), stdev = 0.044
  CI (99.9%): [3.081, 4.679] (assumes normal distribution)


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
# Warmup Iteration   1: 4.098 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.005 ms/op
Iteration   1: 3.003 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.266 ms/op
                 createUser·p0.9999: 11.556 ms/op
                 createUser·p1.00:   11.911 ms/op

Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.107 ms/op
                 createUser·p0.9999: 20.302 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   3: 3.044 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 34.144 ms/op
                 createUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318683
  mean =      3.012 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21213 
    [ 2.500,  5.000) = 295843 
    [ 5.000,  7.500) = 1274 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.548 ms/op
     p(99.9000) =      8.118 ms/op
     p(99.9900) =     32.809 ms/op
     p(99.9990) =     34.198 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.006 ms/op
Iteration   1: 2.888 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.162 ms/op
                 existUser·p0.9999: 23.132 ms/op
                 existUser·p1.00:   24.216 ms/op

Iteration   2: 2.892 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  11.600 ms/op
                 existUser·p0.9999: 12.616 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.389 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  8.592 ms/op
                 existUser·p0.9999: 13.828 ms/op
                 existUser·p1.00:   14.516 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331073
  mean =      2.899 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45283 
    [ 2.500,  5.000) = 284126 
    [ 5.000,  7.500) = 1159 
    [ 7.500, 10.000) = 179 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      9.843 ms/op
     p(99.9900) =     14.736 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.733 ms/op
                 getUser·p0.9999: 11.665 ms/op
                 getUser·p1.00:   11.796 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  11.138 ms/op
                 getUser·p0.9999: 14.946 ms/op
                 getUser·p1.00:   16.531 ms/op

Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.983 ms/op
                 getUser·p0.9999: 14.942 ms/op
                 getUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321018
  mean =      2.987 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 933 
    [ 1.250,  2.500) = 24928 
    [ 2.500,  3.750) = 281163 
    [ 3.750,  5.000) = 12511 
    [ 5.000,  6.250) = 832 
    [ 6.250,  7.500) = 231 
    [ 7.500,  8.750) = 131 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.364 ms/op
     p(99.9900) =     14.795 ms/op
     p(99.9990) =     16.430 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


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
# Warmup Iteration   1: 4.874 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.011 ms/op
Iteration   1: 3.898 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.594 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 24.733 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 3.877 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.842 ms/op
                 listUser·p0.999:  13.427 ms/op
                 listUser·p0.9999: 19.669 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 3.862 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  13.353 ms/op
                 listUser·p0.9999: 16.396 ms/op
                 listUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247479
  mean =      3.879 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3502 
    [ 2.500,  5.000) = 225113 
    [ 5.000,  7.500) = 17746 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     24.191 ms/op
     p(99.9990) =     24.971 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.519 ± 2.321  ops/ms
ClientGrpc.existUser                       thrpt       3  11.156 ± 0.470  ops/ms
ClientGrpc.getUser                         thrpt       3  10.764 ± 1.669  ops/ms
ClientGrpc.listUser                        thrpt       3   8.382 ± 1.782  ops/ms
ClientGrpc.createUser                       avgt       3   3.035 ± 0.472   ms/op
ClientGrpc.existUser                        avgt       3   2.862 ± 0.318   ms/op
ClientGrpc.getUser                          avgt       3   2.988 ± 0.328   ms/op
ClientGrpc.listUser                         avgt       3   3.880 ± 0.799   ms/op
ClientGrpc.createUser                     sample  318683   3.012 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.578           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.548           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.118           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.809           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.210           ms/op
ClientGrpc.existUser                      sample  331073   2.899 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.556           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.843           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.736           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.216           ms/op
ClientGrpc.getUser                        sample  321018   2.987 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.641           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.364           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.795           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.531           ms/op
ClientGrpc.listUser                       sample  247479   3.879 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.594           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.894           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.191           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.100           ms/op
