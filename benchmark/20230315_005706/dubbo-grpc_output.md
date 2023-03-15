# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.193 ops/ms
# Warmup Iteration   2: 5.524 ops/ms
# Warmup Iteration   3: 7.150 ops/ms
Iteration   1: 7.426 ops/ms
Iteration   2: 7.606 ops/ms
Iteration   3: 7.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.608 ±(99.9%) 3.351 ops/ms [Average]
  (min, avg, max) = (7.426, 7.608, 7.793), stdev = 0.184
  CI (99.9%): [4.257, 10.959] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.299 ops/ms
# Warmup Iteration   2: 7.295 ops/ms
# Warmup Iteration   3: 8.164 ops/ms
Iteration   1: 8.111 ops/ms
Iteration   2: 8.170 ops/ms
Iteration   3: 8.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.177 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (8.111, 8.177, 8.251), stdev = 0.070
  CI (99.9%): [6.894, 9.461] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.057 ops/ms
# Warmup Iteration   2: 6.942 ops/ms
# Warmup Iteration   3: 7.439 ops/ms
Iteration   1: 7.565 ops/ms
Iteration   2: 7.428 ops/ms
Iteration   3: 7.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.497 ±(99.9%) 1.252 ops/ms [Average]
  (min, avg, max) = (7.428, 7.497, 7.565), stdev = 0.069
  CI (99.9%): [6.245, 8.748] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.683 ops/ms
# Warmup Iteration   2: 5.738 ops/ms
# Warmup Iteration   3: 6.018 ops/ms
Iteration   1: 6.128 ops/ms
Iteration   2: 6.199 ops/ms
Iteration   3: 5.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.103 ±(99.9%) 2.018 ops/ms [Average]
  (min, avg, max) = (5.982, 6.103, 6.199), stdev = 0.111
  CI (99.9%): [4.085, 8.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.349 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.455 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.003 ms/op
Iteration   1: 4.261 ±(99.9%) 0.003 ms/op
Iteration   2: 4.268 ±(99.9%) 0.002 ms/op
Iteration   3: 4.241 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.257 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (4.241, 4.257, 4.268), stdev = 0.014
  CI (99.9%): [4.003, 4.510] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.913 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.004 ms/op
Iteration   1: 3.948 ±(99.9%) 0.003 ms/op
Iteration   2: 3.956 ±(99.9%) 0.002 ms/op
Iteration   3: 3.942 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.949 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (3.942, 3.949, 3.956), stdev = 0.007
  CI (99.9%): [3.825, 4.073] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.509 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.407 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.004 ms/op
Iteration   1: 4.086 ±(99.9%) 0.004 ms/op
Iteration   2: 4.048 ±(99.9%) 0.003 ms/op
Iteration   3: 4.249 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.128 ±(99.9%) 1.949 ms/op [Average]
  (min, avg, max) = (4.048, 4.128, 4.249), stdev = 0.107
  CI (99.9%): [2.179, 6.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.768 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.698 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.298 ±(99.9%) 0.011 ms/op
Iteration   1: 5.410 ±(99.9%) 0.015 ms/op
Iteration   2: 5.167 ±(99.9%) 0.017 ms/op
Iteration   3: 5.194 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.257 ±(99.9%) 2.435 ms/op [Average]
  (min, avg, max) = (5.167, 5.257, 5.410), stdev = 0.133
  CI (99.9%): [2.822, 7.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.652 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.368 ±(99.9%) 0.016 ms/op
Iteration   1: 4.174 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   4.026 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   5.743 ms/op
                 createUser·p0.99:   7.930 ms/op
                 createUser·p0.999:  11.836 ms/op
                 createUser·p0.9999: 21.059 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 4.112 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   5.169 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   7.725 ms/op
                 createUser·p0.999:  12.521 ms/op
                 createUser·p0.9999: 22.205 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   3: 4.148 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   5.358 ms/op
                 createUser·p0.95:   5.890 ms/op
                 createUser·p0.99:   7.963 ms/op
                 createUser·p0.999:  16.595 ms/op
                 createUser·p0.9999: 26.388 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 231545
  mean =      4.145 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7332 
    [ 2.500,  5.000) = 190746 
    [ 5.000,  7.500) = 30603 
    [ 7.500, 10.000) = 2213 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.757 ms/op
     p(99.0000) =      7.856 ms/op
     p(99.9000) =     14.559 ms/op
     p(99.9900) =     25.418 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.995 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.013 ms/op
Iteration   1: 3.932 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   7.725 ms/op
                 existUser·p0.999:  14.438 ms/op
                 existUser·p0.9999: 17.390 ms/op
                 existUser·p1.00:   17.957 ms/op

Iteration   2: 3.950 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  10.909 ms/op
                 existUser·p0.9999: 19.562 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   3: 3.930 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   7.635 ms/op
                 existUser·p0.999:  13.347 ms/op
                 existUser·p0.9999: 21.033 ms/op
                 existUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243853
  mean =      3.937 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8222 
    [ 2.500,  5.000) = 212991 
    [ 5.000,  7.500) = 20352 
    [ 7.500, 10.000) = 1586 
    [10.000, 12.500) = 355 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     13.369 ms/op
     p(99.9900) =     20.631 ms/op
     p(99.9990) =     23.019 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.124 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.314 ±(99.9%) 0.013 ms/op
Iteration   1: 4.164 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  10.644 ms/op
                 getUser·p0.9999: 17.027 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 4.268 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   4.125 ms/op
                 getUser·p0.90:   5.374 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   7.700 ms/op
                 getUser·p0.999:  16.747 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   3: 4.244 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   4.112 ms/op
                 getUser·p0.90:   5.276 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.692 ms/op
                 getUser·p0.999:  12.014 ms/op
                 getUser·p0.9999: 25.050 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227116
  mean =      4.225 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5362 
    [ 2.500,  5.000) = 186710 
    [ 5.000,  7.500) = 32449 
    [ 7.500, 10.000) = 2027 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      4.088 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     13.892 ms/op
     p(99.9900) =     24.651 ms/op
     p(99.9990) =     27.106 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.848 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.811 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.328 ±(99.9%) 0.021 ms/op
Iteration   1: 5.297 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   7.160 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 5.357 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   5.022 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   10.821 ms/op
                 listUser·p0.999:  18.628 ms/op
                 listUser·p0.9999: 24.677 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 5.278 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   7.102 ms/op
                 listUser·p0.95:   8.045 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  20.411 ms/op
                 listUser·p0.9999: 24.117 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180821
  mean =      5.310 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 267 
    [ 2.500,  5.000) = 91289 
    [ 5.000,  7.500) = 75056 
    [ 7.500, 10.000) = 11796 
    [10.000, 12.500) = 1614 
    [12.500, 15.000) = 426 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      7.160 ms/op
     p(95.0000) =      8.143 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     24.109 ms/op
     p(99.9990) =     25.519 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.608 ± 3.351  ops/ms
ClientGrpc.existUser                       thrpt       3   8.177 ± 1.283  ops/ms
ClientGrpc.getUser                         thrpt       3   7.497 ± 1.252  ops/ms
ClientGrpc.listUser                        thrpt       3   6.103 ± 2.018  ops/ms
ClientGrpc.createUser                       avgt       3   4.257 ± 0.253   ms/op
ClientGrpc.existUser                        avgt       3   3.949 ± 0.124   ms/op
ClientGrpc.getUser                          avgt       3   4.128 ± 1.949   ms/op
ClientGrpc.listUser                         avgt       3   5.257 ± 2.435   ms/op
ClientGrpc.createUser                     sample  231545   4.145 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.951           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.259           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.757           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.856           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.559           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.418           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.575           ms/op
ClientGrpc.existUser                      sample  243853   3.937 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.790           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.956           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.423           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.365           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.369           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.631           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.134           ms/op
ClientGrpc.getUser                        sample  227116   4.225 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.758           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.300           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.684           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.892           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.651           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.329           ms/op
ClientGrpc.listUser                       sample  180821   5.310 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.237           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.160           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.143           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.584           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.531           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.109           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
