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
# Warmup Iteration   1: 2.323 ops/ms
# Warmup Iteration   2: 6.105 ops/ms
# Warmup Iteration   3: 7.502 ops/ms
Iteration   1: 7.502 ops/ms
Iteration   2: 7.747 ops/ms
Iteration   3: 8.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.768 ±(99.9%) 5.037 ops/ms [Average]
  (min, avg, max) = (7.502, 7.768, 8.053), stdev = 0.276
  CI (99.9%): [2.730, 12.805] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.810 ops/ms
# Warmup Iteration   2: 7.656 ops/ms
# Warmup Iteration   3: 8.023 ops/ms
Iteration   1: 8.124 ops/ms
Iteration   2: 8.270 ops/ms
Iteration   3: 8.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.274 ±(99.9%) 2.768 ops/ms [Average]
  (min, avg, max) = (8.124, 8.274, 8.427), stdev = 0.152
  CI (99.9%): [5.506, 11.042] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.757 ops/ms
# Warmup Iteration   2: 7.288 ops/ms
# Warmup Iteration   3: 7.765 ops/ms
Iteration   1: 7.918 ops/ms
Iteration   2: 7.805 ops/ms
Iteration   3: 7.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.885 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (7.805, 7.885, 7.932), stdev = 0.070
  CI (99.9%): [6.614, 9.156] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.721 ops/ms
# Warmup Iteration   2: 5.554 ops/ms
# Warmup Iteration   3: 5.844 ops/ms
Iteration   1: 5.930 ops/ms
Iteration   2: 6.127 ops/ms
Iteration   3: 6.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.078 ±(99.9%) 2.371 ops/ms [Average]
  (min, avg, max) = (5.930, 6.078, 6.176), stdev = 0.130
  CI (99.9%): [3.706, 8.449] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.624 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.010 ms/op
Iteration   1: 4.076 ±(99.9%) 0.003 ms/op
Iteration   2: 4.034 ±(99.9%) 0.003 ms/op
Iteration   3: 3.996 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.035 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.996, 4.035, 4.076), stdev = 0.040
  CI (99.9%): [3.306, 4.764] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.424 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.159 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.006 ms/op
Iteration   1: 3.688 ±(99.9%) 0.004 ms/op
Iteration   2: 3.790 ±(99.9%) 0.004 ms/op
Iteration   3: 3.674 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.718 ±(99.9%) 1.146 ms/op [Average]
  (min, avg, max) = (3.674, 3.718, 3.790), stdev = 0.063
  CI (99.9%): [2.571, 4.864] (assumes normal distribution)


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
# Warmup Iteration   1: 6.427 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.464 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.002 ms/op
Iteration   1: 4.265 ±(99.9%) 0.005 ms/op
Iteration   2: 4.206 ±(99.9%) 0.004 ms/op
Iteration   3: 4.076 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.182 ±(99.9%) 1.766 ms/op [Average]
  (min, avg, max) = (4.076, 4.182, 4.265), stdev = 0.097
  CI (99.9%): [2.416, 5.948] (assumes normal distribution)


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
# Warmup Iteration   1: 8.041 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.573 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.263 ±(99.9%) 0.016 ms/op
Iteration   1: 5.279 ±(99.9%) 0.022 ms/op
Iteration   2: 5.217 ±(99.9%) 0.015 ms/op
Iteration   3: 5.121 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.206 ±(99.9%) 1.449 ms/op [Average]
  (min, avg, max) = (5.121, 5.206, 5.279), stdev = 0.079
  CI (99.9%): [3.757, 6.655] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.309 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.013 ms/op
Iteration   1: 4.227 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   4.133 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  12.588 ms/op
                 createUser·p0.9999: 19.853 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   2: 4.081 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   5.153 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  9.252 ms/op
                 createUser·p0.9999: 21.698 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   3: 4.325 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   4.186 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.334 ms/op
                 createUser·p0.999:  16.761 ms/op
                 createUser·p0.9999: 19.222 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227970
  mean =      4.208 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4183 
    [ 2.500,  5.000) = 188019 
    [ 5.000,  7.500) = 34068 
    [ 7.500, 10.000) = 1250 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     13.469 ms/op
     p(99.9900) =     21.280 ms/op
     p(99.9990) =     24.221 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 5.931 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.011 ms/op
Iteration   1: 3.905 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.489 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 14.693 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   2: 3.841 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.776 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  10.232 ms/op
                 existUser·p0.9999: 17.061 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   4.973 ms/op
                 existUser·p0.99:   6.357 ms/op
                 existUser·p0.999:  12.305 ms/op
                 existUser·p0.9999: 22.295 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 248263
  mean =      3.866 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9676 
    [ 2.500,  5.000) = 221279 
    [ 5.000,  7.500) = 15759 
    [ 7.500, 10.000) = 1148 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.629 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 6.300 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.551 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.012 ms/op
Iteration   1: 4.160 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   8.167 ms/op
                 getUser·p0.999:  14.326 ms/op
                 getUser·p0.9999: 16.438 ms/op
                 getUser·p1.00:   16.810 ms/op

Iteration   2: 4.198 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   4.092 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  11.614 ms/op
                 getUser·p0.9999: 17.470 ms/op
                 getUser·p1.00:   17.990 ms/op

Iteration   3: 4.084 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  14.053 ms/op
                 getUser·p0.9999: 21.370 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231325
  mean =      4.147 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7328 
    [ 2.500,  5.000) = 195937 
    [ 5.000,  7.500) = 25904 
    [ 7.500, 10.000) = 1375 
    [10.000, 12.500) = 510 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     20.570 ms/op
     p(99.9990) =     21.705 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 8.081 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.487 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.288 ±(99.9%) 0.018 ms/op
Iteration   1: 5.361 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   7.135 ms/op
                 listUser·p0.95:   8.052 ms/op
                 listUser·p0.99:   9.961 ms/op
                 listUser·p0.999:  21.644 ms/op
                 listUser·p0.9999: 26.647 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   2: 5.293 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   6.988 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   10.289 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 30.797 ms/op
                 listUser·p1.00:   31.195 ms/op

Iteration   3: 5.252 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   6.889 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  19.236 ms/op
                 listUser·p0.9999: 39.231 ms/op
                 listUser·p1.00:   39.846 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181210
  mean =      5.302 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 331 
    [ 2.500,  5.000) = 88609 
    [ 5.000,  7.500) = 79577 
    [ 7.500, 10.000) = 10881 
    [10.000, 12.500) = 1261 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     10.009 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     38.118 ms/op
     p(99.9990) =     39.686 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.768 ± 5.037  ops/ms
ClientGrpc.existUser                       thrpt       3   8.274 ± 2.768  ops/ms
ClientGrpc.getUser                         thrpt       3   7.885 ± 1.271  ops/ms
ClientGrpc.listUser                        thrpt       3   6.078 ± 2.371  ops/ms
ClientGrpc.createUser                       avgt       3   4.035 ± 0.729   ms/op
ClientGrpc.existUser                        avgt       3   3.718 ± 1.146   ms/op
ClientGrpc.getUser                          avgt       3   4.182 ± 1.766   ms/op
ClientGrpc.listUser                         avgt       3   5.206 ± 1.449   ms/op
ClientGrpc.createUser                     sample  227970   4.208 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.647           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.104           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.284           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.677           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.004           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.469           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.280           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.379           ms/op
ClientGrpc.existUser                      sample  248263   3.866 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.818           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.784           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.218           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.603           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.190           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.463           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.708           ms/op
ClientGrpc.getUser                        sample  231325   4.147 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.807           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.128           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.603           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.381           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.599           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.570           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.856           ms/op
ClientGrpc.listUser                       sample  181210   5.302 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.872           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.905           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.009           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.185           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          38.118           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.846           ms/op
