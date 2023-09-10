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
# Warmup Iteration   1: 3.428 ops/ms
# Warmup Iteration   2: 7.773 ops/ms
# Warmup Iteration   3: 8.936 ops/ms
Iteration   1: 8.923 ops/ms
Iteration   2: 8.922 ops/ms
Iteration   3: 9.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.951 ±(99.9%) 0.918 ops/ms [Average]
  (min, avg, max) = (8.922, 8.951, 9.010), stdev = 0.050
  CI (99.9%): [8.033, 9.870] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.245 ops/ms
# Warmup Iteration   2: 9.181 ops/ms
# Warmup Iteration   3: 9.144 ops/ms
Iteration   1: 9.041 ops/ms
Iteration   2: 9.106 ops/ms
Iteration   3: 9.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.106 ±(99.9%) 1.189 ops/ms [Average]
  (min, avg, max) = (9.041, 9.106, 9.171), stdev = 0.065
  CI (99.9%): [7.917, 10.295] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.417 ops/ms
# Warmup Iteration   2: 8.505 ops/ms
# Warmup Iteration   3: 9.046 ops/ms
Iteration   1: 8.931 ops/ms
Iteration   2: 8.788 ops/ms
Iteration   3: 8.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.860 ±(99.9%) 1.301 ops/ms [Average]
  (min, avg, max) = (8.788, 8.860, 8.931), stdev = 0.071
  CI (99.9%): [7.559, 10.161] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.290 ops/ms
# Warmup Iteration   2: 6.259 ops/ms
# Warmup Iteration   3: 6.625 ops/ms
Iteration   1: 6.700 ops/ms
Iteration   2: 6.620 ops/ms
Iteration   3: 6.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.737 ±(99.9%) 2.525 ops/ms [Average]
  (min, avg, max) = (6.620, 6.737, 6.890), stdev = 0.138
  CI (99.9%): [4.212, 9.261] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.344 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.007 ms/op
Iteration   1: 3.576 ±(99.9%) 0.004 ms/op
Iteration   2: 3.578 ±(99.9%) 0.004 ms/op
Iteration   3: 3.599 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.584 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (3.576, 3.584, 3.599), stdev = 0.013
  CI (99.9%): [3.347, 3.822] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.618 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.004 ms/op
Iteration   1: 3.476 ±(99.9%) 0.005 ms/op
Iteration   2: 3.203 ±(99.9%) 0.005 ms/op
Iteration   3: 3.292 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.324 ±(99.9%) 2.538 ms/op [Average]
  (min, avg, max) = (3.203, 3.324, 3.476), stdev = 0.139
  CI (99.9%): [0.786, 5.861] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.881 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.004 ms/op
Iteration   1: 3.406 ±(99.9%) 0.005 ms/op
Iteration   2: 3.517 ±(99.9%) 0.004 ms/op
Iteration   3: 3.439 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.454 ±(99.9%) 1.038 ms/op [Average]
  (min, avg, max) = (3.406, 3.454, 3.517), stdev = 0.057
  CI (99.9%): [2.416, 4.492] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.329 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.189 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.725 ±(99.9%) 0.014 ms/op
Iteration   1: 4.599 ±(99.9%) 0.017 ms/op
Iteration   2: 4.747 ±(99.9%) 0.015 ms/op
Iteration   3: 4.680 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.675 ±(99.9%) 1.357 ms/op [Average]
  (min, avg, max) = (4.599, 4.675, 4.747), stdev = 0.074
  CI (99.9%): [3.318, 6.032] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.302 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.009 ms/op
Iteration   1: 3.661 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 15.930 ms/op
                 createUser·p1.00:   16.450 ms/op

Iteration   2: 3.749 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  13.143 ms/op
                 createUser·p0.9999: 27.573 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   3: 3.533 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  15.216 ms/op
                 createUser·p0.9999: 20.799 ms/op
                 createUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263371
  mean =      3.646 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11777 
    [ 2.500,  5.000) = 241013 
    [ 5.000,  7.500) = 9441 
    [ 7.500, 10.000) = 750 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     25.832 ms/op
     p(99.9990) =     27.999 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.857 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.008 ms/op
Iteration   1: 3.494 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  10.846 ms/op
                 existUser·p0.9999: 16.644 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   2: 3.466 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  8.892 ms/op
                 existUser·p0.9999: 14.527 ms/op
                 existUser·p1.00:   15.565 ms/op

Iteration   3: 3.501 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  11.455 ms/op
                 existUser·p0.9999: 21.098 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275231
  mean =      3.487 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9505 
    [ 2.500,  5.000) = 259355 
    [ 5.000,  7.500) = 5385 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     10.564 ms/op
     p(99.9900) =     19.414 ms/op
     p(99.9990) =     21.658 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 5.317 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.011 ms/op
Iteration   1: 3.679 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  10.438 ms/op
                 getUser·p0.9999: 16.318 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 3.587 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  9.673 ms/op
                 getUser·p0.9999: 21.632 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.675 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.386 ms/op
                 getUser·p0.999:  10.519 ms/op
                 getUser·p0.9999: 20.546 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263229
  mean =      3.647 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9961 
    [ 2.500,  5.000) = 244253 
    [ 5.000,  7.500) = 7786 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     22.149 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 6.393 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.987 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.010 ±(99.9%) 0.017 ms/op
Iteration   1: 4.632 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  14.580 ms/op
                 listUser·p0.9999: 19.893 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 4.934 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.668 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  18.398 ms/op
                 listUser·p0.9999: 20.384 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 5.089 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  20.580 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196887
  mean =      4.877 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 791 
    [ 2.500,  5.000) = 134554 
    [ 5.000,  7.500) = 51258 
    [ 7.500, 10.000) = 8524 
    [10.000, 12.500) = 1123 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 179 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.545 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     22.129 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.951 ± 0.918  ops/ms
ClientGrpc.existUser                       thrpt       3   9.106 ± 1.189  ops/ms
ClientGrpc.getUser                         thrpt       3   8.860 ± 1.301  ops/ms
ClientGrpc.listUser                        thrpt       3   6.737 ± 2.525  ops/ms
ClientGrpc.createUser                       avgt       3   3.584 ± 0.238   ms/op
ClientGrpc.existUser                        avgt       3   3.324 ± 2.538   ms/op
ClientGrpc.getUser                          avgt       3   3.454 ± 1.038   ms/op
ClientGrpc.listUser                         avgt       3   4.675 ± 1.357   ms/op
ClientGrpc.createUser                     sample  263371   3.646 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.774           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.250           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.304           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.832           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.213           ms/op
ClientGrpc.existUser                      sample  275231   3.487 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.692           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.751           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.564           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.414           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.151           ms/op
ClientGrpc.getUser                        sample  263229   3.647 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.612           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.136           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.371           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.546           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.462           ms/op
ClientGrpc.listUser                       sample  196887   4.877 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.157           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.798           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.842           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.129           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.691           ms/op
