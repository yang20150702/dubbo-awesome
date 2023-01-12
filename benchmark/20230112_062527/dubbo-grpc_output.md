# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.995 ops/ms
# Warmup Iteration   2: 5.515 ops/ms
# Warmup Iteration   3: 6.843 ops/ms
Iteration   1: 7.101 ops/ms
Iteration   2: 7.253 ops/ms
Iteration   3: 7.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.168 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (7.101, 7.168, 7.253), stdev = 0.078
  CI (99.9%): [5.752, 8.583] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.644 ops/ms
# Warmup Iteration   2: 6.877 ops/ms
# Warmup Iteration   3: 6.543 ops/ms
Iteration   1: 6.616 ops/ms
Iteration   2: 7.075 ops/ms
Iteration   3: 6.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.864 ±(99.9%) 4.227 ops/ms [Average]
  (min, avg, max) = (6.616, 6.864, 7.075), stdev = 0.232
  CI (99.9%): [2.637, 11.092] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ops/ms
# Warmup Iteration   2: 6.135 ops/ms
# Warmup Iteration   3: 6.300 ops/ms
Iteration   1: 6.513 ops/ms
Iteration   2: 6.356 ops/ms
Iteration   3: 6.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.478 ±(99.9%) 1.990 ops/ms [Average]
  (min, avg, max) = (6.356, 6.478, 6.566), stdev = 0.109
  CI (99.9%): [4.488, 8.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.026 ops/ms
# Warmup Iteration   2: 4.359 ops/ms
# Warmup Iteration   3: 4.876 ops/ms
Iteration   1: 4.933 ops/ms
Iteration   2: 4.936 ops/ms
Iteration   3: 5.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.972 ±(99.9%) 1.172 ops/ms [Average]
  (min, avg, max) = (4.933, 4.972, 5.046), stdev = 0.064
  CI (99.9%): [3.799, 6.144] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.717 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.108 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.890 ±(99.9%) 0.008 ms/op
Iteration   1: 4.543 ±(99.9%) 0.003 ms/op
Iteration   2: 4.552 ±(99.9%) 0.002 ms/op
Iteration   3: 4.567 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.554 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (4.543, 4.554, 4.567), stdev = 0.012
  CI (99.9%): [4.340, 4.768] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.289 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.754 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.488 ±(99.9%) 0.009 ms/op
Iteration   1: 4.483 ±(99.9%) 0.002 ms/op
Iteration   2: 4.523 ±(99.9%) 0.005 ms/op
Iteration   3: 4.417 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.474 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (4.417, 4.474, 4.523), stdev = 0.054
  CI (99.9%): [3.495, 5.453] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.510 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.844 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.071 ±(99.9%) 0.005 ms/op
Iteration   1: 4.880 ±(99.9%) 0.006 ms/op
Iteration   2: 4.814 ±(99.9%) 0.012 ms/op
Iteration   3: 4.770 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.821 ±(99.9%) 1.009 ms/op [Average]
  (min, avg, max) = (4.770, 4.821, 4.880), stdev = 0.055
  CI (99.9%): [3.812, 5.831] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.624 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 7.352 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.745 ±(99.9%) 0.037 ms/op
Iteration   1: 6.703 ±(99.9%) 0.030 ms/op
Iteration   2: 6.613 ±(99.9%) 0.025 ms/op
Iteration   3: 5.995 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.437 ±(99.9%) 7.034 ms/op [Average]
  (min, avg, max) = (5.995, 6.437, 6.703), stdev = 0.386
  CI (99.9%): [≈ 0, 13.471] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.956 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.922 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.886 ±(99.9%) 0.018 ms/op
Iteration   1: 4.887 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   4.694 ms/op
                 createUser·p0.90:   6.250 ms/op
                 createUser·p0.95:   6.947 ms/op
                 createUser·p0.99:   9.093 ms/op
                 createUser·p0.999:  17.946 ms/op
                 createUser·p0.9999: 29.783 ms/op
                 createUser·p1.00:   30.212 ms/op

Iteration   2: 4.738 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   4.604 ms/op
                 createUser·p0.90:   6.152 ms/op
                 createUser·p0.95:   6.808 ms/op
                 createUser·p0.99:   8.932 ms/op
                 createUser·p0.999:  19.431 ms/op
                 createUser·p0.9999: 27.034 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   3: 5.062 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   6.521 ms/op
                 createUser·p0.95:   7.225 ms/op
                 createUser·p0.99:   9.339 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 30.092 ms/op
                 createUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 196202
  mean =      4.892 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4097 
    [ 2.500,  5.000) = 117205 
    [ 5.000,  7.500) = 68553 
    [ 7.500, 10.000) = 5184 
    [10.000, 12.500) = 681 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.316 ms/op
     p(95.0000) =      7.004 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     18.396 ms/op
     p(99.9900) =     29.721 ms/op
     p(99.9990) =     30.448 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.368 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.176 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.693 ±(99.9%) 0.016 ms/op
Iteration   1: 4.727 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   4.563 ms/op
                 existUser·p0.90:   6.054 ms/op
                 existUser·p0.95:   6.685 ms/op
                 existUser·p0.99:   8.864 ms/op
                 existUser·p0.999:  15.440 ms/op
                 existUser·p0.9999: 18.161 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 4.655 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   4.497 ms/op
                 existUser·p0.90:   5.964 ms/op
                 existUser·p0.95:   6.578 ms/op
                 existUser·p0.99:   9.372 ms/op
                 existUser·p0.999:  15.250 ms/op
                 existUser·p0.9999: 30.806 ms/op
                 existUser·p1.00:   31.162 ms/op

Iteration   3: 4.608 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   4.481 ms/op
                 existUser·p0.90:   5.882 ms/op
                 existUser·p0.95:   6.423 ms/op
                 existUser·p0.99:   8.634 ms/op
                 existUser·p0.999:  17.362 ms/op
                 existUser·p0.9999: 26.083 ms/op
                 existUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 205682
  mean =      4.663 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5433 
    [ 2.500,  5.000) = 136452 
    [ 5.000,  7.500) = 59020 
    [ 7.500, 10.000) = 3571 
    [10.000, 12.500) = 668 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.964 ms/op
     p(95.0000) =      6.562 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     15.799 ms/op
     p(99.9900) =     30.283 ms/op
     p(99.9990) =     31.062 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.928 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.993 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.680 ±(99.9%) 0.015 ms/op
Iteration   1: 4.610 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   4.497 ms/op
                 getUser·p0.90:   5.997 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   8.339 ms/op
                 getUser·p0.999:  11.978 ms/op
                 getUser·p0.9999: 25.533 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   2: 4.589 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.906 ms/op
                 getUser·p0.95:   6.455 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  11.814 ms/op
                 getUser·p0.9999: 17.237 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   3: 4.505 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.816 ms/op
                 getUser·p0.95:   6.316 ms/op
                 getUser·p0.99:   7.897 ms/op
                 getUser·p0.999:  10.387 ms/op
                 getUser·p0.9999: 24.959 ms/op
                 getUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 210239
  mean =      4.568 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4853 
    [ 2.500,  5.000) = 141359 
    [ 5.000,  7.500) = 60355 
    [ 7.500, 10.000) = 3151 
    [10.000, 12.500) = 378 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.906 ms/op
     p(95.0000) =      6.423 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     11.432 ms/op
     p(99.9900) =     25.165 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.184 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.157 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.863 ±(99.9%) 0.023 ms/op
Iteration   1: 5.720 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  17.301 ms/op
                 listUser·p0.9999: 22.983 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 5.795 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.833 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   11.338 ms/op
                 listUser·p0.999:  16.393 ms/op
                 listUser·p0.9999: 22.232 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 6.348 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   8.536 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   13.009 ms/op
                 listUser·p0.999:  24.679 ms/op
                 listUser·p0.9999: 28.998 ms/op
                 listUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 161571
  mean =      5.941 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 47485 
    [ 5.000,  7.500) = 91439 
    [ 7.500, 10.000) = 17892 
    [10.000, 12.500) = 3578 
    [12.500, 15.000) = 665 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =      8.036 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     11.796 ms/op
     p(99.9000) =     20.265 ms/op
     p(99.9900) =     28.170 ms/op
     p(99.9990) =     29.247 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.168 ± 1.416  ops/ms
ClientGrpc.existUser                       thrpt       3   6.864 ± 4.227  ops/ms
ClientGrpc.getUser                         thrpt       3   6.478 ± 1.990  ops/ms
ClientGrpc.listUser                        thrpt       3   4.972 ± 1.172  ops/ms
ClientGrpc.createUser                       avgt       3   4.554 ± 0.214   ms/op
ClientGrpc.existUser                        avgt       3   4.474 ± 0.979   ms/op
ClientGrpc.getUser                          avgt       3   4.821 ± 1.009   ms/op
ClientGrpc.listUser                         avgt       3   6.437 ± 7.034   ms/op
ClientGrpc.createUser                     sample  196202   4.892 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.180           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.316           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.004           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.126           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          18.396           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.721           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.605           ms/op
ClientGrpc.existUser                      sample  205682   4.663 ± 0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.992           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.964           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.562           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.962           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.799           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.283           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.162           ms/op
ClientGrpc.getUser                        sample  210239   4.568 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.821           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.906           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.423           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.225           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.432           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.165           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.608           ms/op
ClientGrpc.listUser                       sample  161571   5.941 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.487           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.036           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.126           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.796           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.265           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.170           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.327           ms/op
