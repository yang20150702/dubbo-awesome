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
# Warmup Iteration   1: 2.005 ops/ms
# Warmup Iteration   2: 4.505 ops/ms
# Warmup Iteration   3: 6.346 ops/ms
Iteration   1: 6.696 ops/ms
Iteration   2: 6.876 ops/ms
Iteration   3: 6.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.845 ±(99.9%) 2.498 ops/ms [Average]
  (min, avg, max) = (6.696, 6.845, 6.964), stdev = 0.137
  CI (99.9%): [4.348, 9.343] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.842 ops/ms
# Warmup Iteration   2: 6.343 ops/ms
# Warmup Iteration   3: 6.719 ops/ms
Iteration   1: 7.342 ops/ms
Iteration   2: 7.167 ops/ms
Iteration   3: 7.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.306 ±(99.9%) 2.268 ops/ms [Average]
  (min, avg, max) = (7.167, 7.306, 7.408), stdev = 0.124
  CI (99.9%): [5.038, 9.574] (assumes normal distribution)


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
# Warmup Iteration   1: 3.559 ops/ms
# Warmup Iteration   2: 6.071 ops/ms
# Warmup Iteration   3: 6.554 ops/ms
Iteration   1: 6.751 ops/ms
Iteration   2: 6.370 ops/ms
Iteration   3: 6.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.664 ±(99.9%) 4.768 ops/ms [Average]
  (min, avg, max) = (6.370, 6.664, 6.870), stdev = 0.261
  CI (99.9%): [1.896, 11.432] (assumes normal distribution)


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
# Warmup Iteration   1: 2.806 ops/ms
# Warmup Iteration   2: 4.702 ops/ms
# Warmup Iteration   3: 5.206 ops/ms
Iteration   1: 5.169 ops/ms
Iteration   2: 5.279 ops/ms
Iteration   3: 5.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.287 ±(99.9%) 2.231 ops/ms [Average]
  (min, avg, max) = (5.169, 5.287, 5.413), stdev = 0.122
  CI (99.9%): [3.056, 7.518] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.351 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.330 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.863 ±(99.9%) 0.011 ms/op
Iteration   1: 4.731 ±(99.9%) 0.004 ms/op
Iteration   2: 4.690 ±(99.9%) 0.005 ms/op
Iteration   3: 4.747 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.723 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (4.690, 4.723, 4.747), stdev = 0.029
  CI (99.9%): [4.186, 5.259] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.356 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.793 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.376 ±(99.9%) 0.004 ms/op
Iteration   1: 4.478 ±(99.9%) 0.003 ms/op
Iteration   2: 4.473 ±(99.9%) 0.004 ms/op
Iteration   3: 4.538 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.496 ±(99.9%) 0.665 ms/op [Average]
  (min, avg, max) = (4.473, 4.496, 4.538), stdev = 0.036
  CI (99.9%): [3.831, 5.162] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.252 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.002 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.742 ±(99.9%) 0.005 ms/op
Iteration   1: 4.780 ±(99.9%) 0.005 ms/op
Iteration   2: 4.739 ±(99.9%) 0.005 ms/op
Iteration   3: 4.669 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.729 ±(99.9%) 1.019 ms/op [Average]
  (min, avg, max) = (4.669, 4.729, 4.780), stdev = 0.056
  CI (99.9%): [3.711, 5.748] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.506 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.588 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.965 ±(99.9%) 0.023 ms/op
Iteration   1: 5.983 ±(99.9%) 0.017 ms/op
Iteration   2: 6.399 ±(99.9%) 0.017 ms/op
Iteration   3: 6.176 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.186 ±(99.9%) 3.797 ms/op [Average]
  (min, avg, max) = (5.983, 6.186, 6.399), stdev = 0.208
  CI (99.9%): [2.389, 9.983] (assumes normal distribution)


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
# Warmup Iteration   1: 7.844 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 5.114 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.786 ±(99.9%) 0.017 ms/op
Iteration   1: 4.753 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   4.637 ms/op
                 createUser·p0.90:   6.103 ms/op
                 createUser·p0.95:   6.726 ms/op
                 createUser·p0.99:   8.995 ms/op
                 createUser·p0.999:  14.008 ms/op
                 createUser·p0.9999: 21.498 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 4.750 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   4.579 ms/op
                 createUser·p0.90:   5.997 ms/op
                 createUser·p0.95:   6.701 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  14.577 ms/op
                 createUser·p0.9999: 21.990 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   3: 4.681 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   5.898 ms/op
                 createUser·p0.95:   6.480 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  16.597 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 203048
  mean =      4.728 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4652 
    [ 2.500,  5.000) = 131653 
    [ 5.000,  7.500) = 61613 
    [ 7.500, 10.000) = 3732 
    [10.000, 12.500) = 915 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      6.005 ms/op
     p(95.0000) =      6.627 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     23.982 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 6.580 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.834 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.554 ±(99.9%) 0.015 ms/op
Iteration   1: 4.531 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   4.407 ms/op
                 existUser·p0.90:   5.751 ms/op
                 existUser·p0.95:   6.423 ms/op
                 existUser·p0.99:   8.749 ms/op
                 existUser·p0.999:  12.883 ms/op
                 existUser·p0.9999: 18.086 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 4.335 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.530 ms/op
                 existUser·p0.95:   6.070 ms/op
                 existUser·p0.99:   8.217 ms/op
                 existUser·p0.999:  13.343 ms/op
                 existUser·p0.9999: 19.661 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 4.433 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   4.252 ms/op
                 existUser·p0.90:   5.554 ms/op
                 existUser·p0.95:   6.169 ms/op
                 existUser·p0.99:   9.348 ms/op
                 existUser·p0.999:  15.115 ms/op
                 existUser·p0.9999: 34.669 ms/op
                 existUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 216591
  mean =      4.431 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6992 
    [ 2.500,  5.000) = 162602 
    [ 5.000,  7.500) = 42755 
    [ 7.500, 10.000) = 3096 
    [10.000, 12.500) = 775 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.210 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     33.303 ms/op
     p(99.9990) =     35.040 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 7.624 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.106 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.834 ±(99.9%) 0.016 ms/op
Iteration   1: 4.859 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   4.678 ms/op
                 getUser·p0.90:   6.111 ms/op
                 getUser·p0.95:   6.808 ms/op
                 getUser·p0.99:   9.486 ms/op
                 getUser·p0.999:  16.952 ms/op
                 getUser·p0.9999: 19.005 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   2: 4.735 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   4.612 ms/op
                 getUser·p0.90:   6.087 ms/op
                 getUser·p0.95:   6.676 ms/op
                 getUser·p0.99:   8.859 ms/op
                 getUser·p0.999:  13.623 ms/op
                 getUser·p0.9999: 19.521 ms/op
                 getUser·p1.00:   20.054 ms/op

Iteration   3: 4.779 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   6.021 ms/op
                 getUser·p0.95:   6.660 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  14.212 ms/op
                 getUser·p0.9999: 22.479 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 200343
  mean =      4.790 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3629 
    [ 2.500,  5.000) = 126142 
    [ 5.000,  7.500) = 65268 
    [ 7.500, 10.000) = 4080 
    [10.000, 12.500) = 816 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.070 ms/op
     p(95.0000) =      6.709 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     14.794 ms/op
     p(99.9900) =     21.886 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 9.009 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 6.917 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.259 ±(99.9%) 0.027 ms/op
Iteration   1: 6.040 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   12.583 ms/op
                 listUser·p0.999:  18.743 ms/op
                 listUser·p0.9999: 20.012 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   2: 5.931 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   8.094 ms/op
                 listUser·p0.95:   9.257 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  20.906 ms/op
                 listUser·p0.9999: 24.197 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 6.093 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   7.782 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   11.565 ms/op
                 listUser·p0.999:  26.787 ms/op
                 listUser·p0.9999: 35.455 ms/op
                 listUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 159443
  mean =      6.021 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102 
    [ 2.500,  5.000) = 39515 
    [ 5.000,  7.500) = 97975 
    [ 7.500, 10.000) = 16903 
    [10.000, 12.500) = 3614 
    [12.500, 15.000) = 760 
    [15.000, 17.500) = 223 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.559 ms/op
     p(50.0000) =      5.669 ms/op
     p(90.0000) =      8.028 ms/op
     p(95.0000) =      9.191 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     22.122 ms/op
     p(99.9900) =     33.624 ms/op
     p(99.9990) =     35.731 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.845 ± 2.498  ops/ms
ClientGrpc.existUser                       thrpt       3   7.306 ± 2.268  ops/ms
ClientGrpc.getUser                         thrpt       3   6.664 ± 4.768  ops/ms
ClientGrpc.listUser                        thrpt       3   5.287 ± 2.231  ops/ms
ClientGrpc.createUser                       avgt       3   4.723 ± 0.537   ms/op
ClientGrpc.existUser                        avgt       3   4.496 ± 0.665   ms/op
ClientGrpc.getUser                          avgt       3   4.729 ± 1.019   ms/op
ClientGrpc.listUser                         avgt       3   6.186 ± 3.797   ms/op
ClientGrpc.createUser                     sample  203048   4.728 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.139           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.005           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.627           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.159           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.598           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.529           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.084           ms/op
ClientGrpc.existUser                      sample  216591   4.431 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.980           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.612           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.210           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.684           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.418           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.303           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.062           ms/op
ClientGrpc.getUser                        sample  200343   4.790 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.900           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.070           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.709           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.110           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.794           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.886           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.544           ms/op
ClientGrpc.listUser                       sample  159443   6.021 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.559           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.028           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.191           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.075           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.624           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.848           ms/op
