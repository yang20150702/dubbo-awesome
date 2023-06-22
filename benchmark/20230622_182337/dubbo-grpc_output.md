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
# Warmup Iteration   1: 1.997 ops/ms
# Warmup Iteration   2: 4.924 ops/ms
# Warmup Iteration   3: 6.802 ops/ms
Iteration   1: 7.012 ops/ms
Iteration   2: 7.163 ops/ms
Iteration   3: 6.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.032 ±(99.9%) 2.233 ops/ms [Average]
  (min, avg, max) = (6.921, 7.032, 7.163), stdev = 0.122
  CI (99.9%): [4.798, 9.265] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ops/ms
# Warmup Iteration   2: 6.919 ops/ms
# Warmup Iteration   3: 7.275 ops/ms
Iteration   1: 7.686 ops/ms
Iteration   2: 7.470 ops/ms
Iteration   3: 7.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.653 ±(99.9%) 3.088 ops/ms [Average]
  (min, avg, max) = (7.470, 7.653, 7.804), stdev = 0.169
  CI (99.9%): [4.566, 10.741] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ops/ms
# Warmup Iteration   2: 6.668 ops/ms
# Warmup Iteration   3: 6.892 ops/ms
Iteration   1: 7.194 ops/ms
Iteration   2: 7.012 ops/ms
Iteration   3: 7.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.078 ±(99.9%) 1.835 ops/ms [Average]
  (min, avg, max) = (7.012, 7.078, 7.194), stdev = 0.101
  CI (99.9%): [5.244, 8.913] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.357 ops/ms
# Warmup Iteration   2: 4.955 ops/ms
# Warmup Iteration   3: 5.391 ops/ms
Iteration   1: 5.526 ops/ms
Iteration   2: 5.448 ops/ms
Iteration   3: 5.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.491 ±(99.9%) 0.728 ops/ms [Average]
  (min, avg, max) = (5.448, 5.491, 5.526), stdev = 0.040
  CI (99.9%): [4.764, 6.219] (assumes normal distribution)


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
# Warmup Iteration   1: 7.225 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.927 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.823 ±(99.9%) 0.004 ms/op
Iteration   1: 4.611 ±(99.9%) 0.004 ms/op
Iteration   2: 4.733 ±(99.9%) 0.003 ms/op
Iteration   3: 4.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.624 ±(99.9%) 1.874 ms/op [Average]
  (min, avg, max) = (4.528, 4.624, 4.733), stdev = 0.103
  CI (99.9%): [2.750, 6.498] (assumes normal distribution)


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
# Warmup Iteration   1: 6.639 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.348 ±(99.9%) 0.004 ms/op
Iteration   1: 4.237 ±(99.9%) 0.004 ms/op
Iteration   2: 4.180 ±(99.9%) 0.005 ms/op
Iteration   3: 4.142 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.187 ±(99.9%) 0.868 ms/op [Average]
  (min, avg, max) = (4.142, 4.187, 4.237), stdev = 0.048
  CI (99.9%): [3.318, 5.055] (assumes normal distribution)


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
# Warmup Iteration   1: 7.053 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.609 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.460 ±(99.9%) 0.016 ms/op
Iteration   1: 4.570 ±(99.9%) 0.004 ms/op
Iteration   2: 4.671 ±(99.9%) 0.005 ms/op
Iteration   3: 4.433 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.558 ±(99.9%) 2.178 ms/op [Average]
  (min, avg, max) = (4.433, 4.558, 4.671), stdev = 0.119
  CI (99.9%): [2.380, 6.736] (assumes normal distribution)


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
# Warmup Iteration   1: 8.003 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 6.495 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.928 ±(99.9%) 0.026 ms/op
Iteration   1: 5.941 ±(99.9%) 0.012 ms/op
Iteration   2: 5.901 ±(99.9%) 0.015 ms/op
Iteration   3: 5.871 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.904 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (5.871, 5.904, 5.941), stdev = 0.035
  CI (99.9%): [5.258, 6.551] (assumes normal distribution)


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
# Warmup Iteration   1: 7.143 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.684 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.510 ±(99.9%) 0.013 ms/op
Iteration   1: 4.406 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.399 ms/op
                 createUser·p0.95:   5.865 ms/op
                 createUser·p0.99:   7.234 ms/op
                 createUser·p0.999:  12.234 ms/op
                 createUser·p0.9999: 16.658 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   2: 4.462 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  12.474 ms/op
                 createUser·p0.9999: 18.700 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   3: 4.307 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.284 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   7.259 ms/op
                 createUser·p0.999:  19.386 ms/op
                 createUser·p0.9999: 23.634 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 218619
  mean =      4.391 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3923 
    [ 2.500,  5.000) = 173081 
    [ 5.000,  7.500) = 39624 
    [ 7.500, 10.000) = 1482 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     13.818 ms/op
     p(99.9900) =     22.647 ms/op
     p(99.9990) =     24.263 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 6.446 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.598 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.012 ms/op
Iteration   1: 4.408 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   4.309 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   5.997 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  9.001 ms/op
                 existUser·p0.9999: 16.339 ms/op
                 existUser·p1.00:   16.630 ms/op

Iteration   2: 4.294 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   4.170 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   7.283 ms/op
                 existUser·p0.999:  12.182 ms/op
                 existUser·p0.9999: 18.040 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   3: 4.343 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   5.521 ms/op
                 existUser·p0.95:   6.103 ms/op
                 existUser·p0.99:   7.930 ms/op
                 existUser·p0.999:  13.801 ms/op
                 existUser·p0.9999: 21.978 ms/op
                 existUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 220790
  mean =      4.348 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4997 
    [ 2.500,  5.000) = 172790 
    [ 5.000,  7.500) = 40930 
    [ 7.500, 10.000) = 1630 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     19.484 ms/op
     p(99.9990) =     22.334 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 7.026 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.926 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.479 ±(99.9%) 0.013 ms/op
Iteration   1: 4.351 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   7.741 ms/op
                 getUser·p0.999:  10.985 ms/op
                 getUser·p0.9999: 17.246 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 4.338 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  14.602 ms/op
                 getUser·p0.9999: 19.386 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   3: 4.350 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   7.217 ms/op
                 getUser·p0.999:  11.064 ms/op
                 getUser·p0.9999: 27.291 ms/op
                 getUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 220820
  mean =      4.346 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3638 
    [ 2.500,  5.000) = 176705 
    [ 5.000,  7.500) = 38169 
    [ 7.500, 10.000) = 1873 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     11.029 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     28.389 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 8.269 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 6.089 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.710 ±(99.9%) 0.022 ms/op
Iteration   1: 5.711 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   2: 5.679 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   5.341 ms/op
                 listUser·p0.90:   7.758 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   10.813 ms/op
                 listUser·p0.999:  19.840 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 5.760 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.213 ms/op
                 listUser·p0.999:  21.323 ms/op
                 listUser·p0.9999: 27.343 ms/op
                 listUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167973
  mean =      5.716 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 251 
    [ 2.500,  5.000) = 55962 
    [ 5.000,  7.500) = 92764 
    [ 7.500, 10.000) = 16373 
    [10.000, 12.500) = 2060 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      7.676 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     17.532 ms/op
     p(99.9900) =     25.691 ms/op
     p(99.9990) =     27.536 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.032 ± 2.233  ops/ms
ClientGrpc.existUser                       thrpt       3   7.653 ± 3.088  ops/ms
ClientGrpc.getUser                         thrpt       3   7.078 ± 1.835  ops/ms
ClientGrpc.listUser                        thrpt       3   5.491 ± 0.728  ops/ms
ClientGrpc.createUser                       avgt       3   4.624 ± 1.874   ms/op
ClientGrpc.existUser                        avgt       3   4.187 ± 0.868   ms/op
ClientGrpc.getUser                          avgt       3   4.558 ± 2.178   ms/op
ClientGrpc.listUser                         avgt       3   5.904 ± 0.646   ms/op
ClientGrpc.createUser                     sample  218619   4.391 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.931           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.415           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.389           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.818           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.647           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.576           ms/op
ClientGrpc.existUser                      sample  220790   4.348 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.059           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.472           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.956           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.422           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.386           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.484           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.413           ms/op
ClientGrpc.getUser                        sample  220820   4.346 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.945           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.390           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.841           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.569           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.029           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.706           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.508           ms/op
ClientGrpc.listUser                       sample  167973   5.716 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.542           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.676           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.584           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.532           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.691           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.558           ms/op
