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
# Warmup Iteration   1: 3.382 ops/ms
# Warmup Iteration   2: 7.593 ops/ms
# Warmup Iteration   3: 8.466 ops/ms
Iteration   1: 9.009 ops/ms
Iteration   2: 9.351 ops/ms
Iteration   3: 9.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.173 ±(99.9%) 3.127 ops/ms [Average]
  (min, avg, max) = (9.009, 9.173, 9.351), stdev = 0.171
  CI (99.9%): [6.046, 12.300] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.325 ops/ms
# Warmup Iteration   2: 9.093 ops/ms
# Warmup Iteration   3: 9.499 ops/ms
Iteration   1: 9.571 ops/ms
Iteration   2: 9.615 ops/ms
Iteration   3: 9.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.612 ±(99.9%) 0.719 ops/ms [Average]
  (min, avg, max) = (9.571, 9.612, 9.649), stdev = 0.039
  CI (99.9%): [8.893, 10.331] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.828 ops/ms
# Warmup Iteration   2: 8.773 ops/ms
# Warmup Iteration   3: 8.960 ops/ms
Iteration   1: 9.237 ops/ms
Iteration   2: 9.093 ops/ms
Iteration   3: 9.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.240 ±(99.9%) 2.715 ops/ms [Average]
  (min, avg, max) = (9.093, 9.240, 9.391), stdev = 0.149
  CI (99.9%): [6.525, 11.955] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.909 ops/ms
# Warmup Iteration   2: 6.423 ops/ms
# Warmup Iteration   3: 6.928 ops/ms
Iteration   1: 6.872 ops/ms
Iteration   2: 6.948 ops/ms
Iteration   3: 7.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.993 ±(99.9%) 2.714 ops/ms [Average]
  (min, avg, max) = (6.872, 6.993, 7.159), stdev = 0.149
  CI (99.9%): [4.279, 9.706] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.500 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.005 ms/op
Iteration   1: 3.475 ±(99.9%) 0.004 ms/op
Iteration   2: 3.557 ±(99.9%) 0.002 ms/op
Iteration   3: 3.503 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.511 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (3.475, 3.511, 3.557), stdev = 0.042
  CI (99.9%): [2.747, 4.276] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.792 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.006 ms/op
Iteration   1: 3.338 ±(99.9%) 0.003 ms/op
Iteration   2: 3.408 ±(99.9%) 0.003 ms/op
Iteration   3: 3.448 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.398 ±(99.9%) 1.019 ms/op [Average]
  (min, avg, max) = (3.338, 3.398, 3.448), stdev = 0.056
  CI (99.9%): [2.379, 4.417] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.164 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.003 ms/op
Iteration   1: 3.543 ±(99.9%) 0.004 ms/op
Iteration   2: 3.521 ±(99.9%) 0.005 ms/op
Iteration   3: 3.550 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.538 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (3.521, 3.538, 3.550), stdev = 0.015
  CI (99.9%): [3.262, 3.814] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.256 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.959 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.703 ±(99.9%) 0.020 ms/op
Iteration   1: 4.634 ±(99.9%) 0.015 ms/op
Iteration   2: 4.603 ±(99.9%) 0.013 ms/op
Iteration   3: 4.639 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.625 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (4.603, 4.625, 4.639), stdev = 0.020
  CI (99.9%): [4.266, 4.985] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.285 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.009 ms/op
Iteration   1: 3.462 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 31.746 ms/op
                 createUser·p1.00:   32.113 ms/op

Iteration   2: 3.509 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  9.546 ms/op
                 createUser·p0.9999: 20.014 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   3: 3.423 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.625 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  9.437 ms/op
                 createUser·p0.9999: 23.364 ms/op
                 createUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 276917
  mean =      3.464 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16093 
    [ 2.500,  5.000) = 256140 
    [ 5.000,  7.500) = 3973 
    [ 7.500, 10.000) = 502 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =      9.406 ms/op
     p(99.9900) =     30.789 ms/op
     p(99.9990) =     32.055 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.572 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.007 ms/op
Iteration   1: 3.409 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  8.051 ms/op
                 existUser·p0.9999: 14.487 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 3.374 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  12.886 ms/op
                 existUser·p0.9999: 14.574 ms/op
                 existUser·p1.00:   16.548 ms/op

Iteration   3: 3.375 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  9.983 ms/op
                 existUser·p0.9999: 33.505 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 283502
  mean =      3.386 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10095 
    [ 2.500,  5.000) = 269544 
    [ 5.000,  7.500) = 3182 
    [ 7.500, 10.000) = 376 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     11.051 ms/op
     p(99.9900) =     32.789 ms/op
     p(99.9990) =     33.762 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 5.115 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.008 ms/op
Iteration   1: 3.544 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  8.645 ms/op
                 getUser·p0.9999: 14.826 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   2: 3.452 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  7.807 ms/op
                 getUser·p0.9999: 15.670 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   3: 3.520 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  8.996 ms/op
                 getUser·p0.9999: 22.053 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 274012
  mean =      3.505 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10443 
    [ 2.500,  5.000) = 258248 
    [ 5.000,  7.500) = 4807 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     19.811 ms/op
     p(99.9990) =     22.094 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 6.223 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.009 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.495 ±(99.9%) 0.014 ms/op
Iteration   1: 4.720 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.685 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 20.633 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 4.700 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.849 ms/op
                 listUser·p0.95:   6.660 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  15.236 ms/op
                 listUser·p0.9999: 17.574 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 4.676 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   8.257 ms/op
                 listUser·p0.999:  18.796 ms/op
                 listUser·p0.9999: 22.681 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204246
  mean =      4.698 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 546 
    [ 2.500,  5.000) = 154806 
    [ 5.000,  7.500) = 44397 
    [ 7.500, 10.000) = 3823 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      8.307 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     20.532 ms/op
     p(99.9990) =     23.157 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.173 ± 3.127  ops/ms
ClientGrpc.existUser                       thrpt       3   9.612 ± 0.719  ops/ms
ClientGrpc.getUser                         thrpt       3   9.240 ± 2.715  ops/ms
ClientGrpc.listUser                        thrpt       3   6.993 ± 2.714  ops/ms
ClientGrpc.createUser                       avgt       3   3.511 ± 0.765   ms/op
ClientGrpc.existUser                        avgt       3   3.398 ± 1.019   ms/op
ClientGrpc.getUser                          avgt       3   3.538 ± 0.276   ms/op
ClientGrpc.listUser                         avgt       3   4.625 ± 0.360   ms/op
ClientGrpc.createUser                     sample  276917   3.464 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.625           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.125           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.406           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.789           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.113           ms/op
ClientGrpc.existUser                      sample  283502   3.386 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.694           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.953           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.051           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.789           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.882           ms/op
ClientGrpc.getUser                        sample  274012   3.505 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.639           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.178           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.585           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.811           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.118           ms/op
ClientGrpc.listUser                       sample  204246   4.698 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.978           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.506           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.307           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.269           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.532           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.364           ms/op
