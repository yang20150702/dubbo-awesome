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
# Warmup Iteration   1: 3.536 ops/ms
# Warmup Iteration   2: 7.647 ops/ms
# Warmup Iteration   3: 8.993 ops/ms
Iteration   1: 9.087 ops/ms
Iteration   2: 9.380 ops/ms
Iteration   3: 9.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.246 ±(99.9%) 2.708 ops/ms [Average]
  (min, avg, max) = (9.087, 9.246, 9.380), stdev = 0.148
  CI (99.9%): [6.538, 11.954] (assumes normal distribution)


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
# Warmup Iteration   1: 6.339 ops/ms
# Warmup Iteration   2: 9.277 ops/ms
# Warmup Iteration   3: 9.556 ops/ms
Iteration   1: 9.780 ops/ms
Iteration   2: 9.755 ops/ms
Iteration   3: 9.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.790 ±(99.9%) 0.742 ops/ms [Average]
  (min, avg, max) = (9.755, 9.790, 9.835), stdev = 0.041
  CI (99.9%): [9.048, 10.532] (assumes normal distribution)


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
# Warmup Iteration   1: 5.575 ops/ms
# Warmup Iteration   2: 8.764 ops/ms
# Warmup Iteration   3: 9.035 ops/ms
Iteration   1: 9.213 ops/ms
Iteration   2: 9.205 ops/ms
Iteration   3: 9.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.193 ±(99.9%) 0.504 ops/ms [Average]
  (min, avg, max) = (9.161, 9.193, 9.213), stdev = 0.028
  CI (99.9%): [8.689, 9.697] (assumes normal distribution)


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
# Warmup Iteration   1: 4.394 ops/ms
# Warmup Iteration   2: 6.992 ops/ms
# Warmup Iteration   3: 6.931 ops/ms
Iteration   1: 7.084 ops/ms
Iteration   2: 7.685 ops/ms
Iteration   3: 7.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.303 ±(99.9%) 6.055 ops/ms [Average]
  (min, avg, max) = (7.084, 7.303, 7.685), stdev = 0.332
  CI (99.9%): [1.247, 13.358] (assumes normal distribution)


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
# Warmup Iteration   1: 4.782 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.003 ms/op
Iteration   1: 3.512 ±(99.9%) 0.004 ms/op
Iteration   2: 3.508 ±(99.9%) 0.004 ms/op
Iteration   3: 3.395 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.472 ±(99.9%) 1.215 ms/op [Average]
  (min, avg, max) = (3.395, 3.472, 3.512), stdev = 0.067
  CI (99.9%): [2.256, 4.687] (assumes normal distribution)


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
# Warmup Iteration   1: 4.474 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.004 ms/op
Iteration   1: 3.275 ±(99.9%) 0.003 ms/op
Iteration   2: 3.270 ±(99.9%) 0.004 ms/op
Iteration   3: 3.287 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.278 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (3.270, 3.278, 3.287), stdev = 0.009
  CI (99.9%): [3.117, 3.438] (assumes normal distribution)


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
# Warmup Iteration   1: 4.731 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.005 ms/op
Iteration   1: 3.547 ±(99.9%) 0.003 ms/op
Iteration   2: 3.524 ±(99.9%) 0.004 ms/op
Iteration   3: 3.607 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.560 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (3.524, 3.560, 3.607), stdev = 0.043
  CI (99.9%): [2.781, 4.338] (assumes normal distribution)


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
# Warmup Iteration   1: 6.408 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.768 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.729 ±(99.9%) 0.020 ms/op
Iteration   1: 4.712 ±(99.9%) 0.016 ms/op
Iteration   2: 4.783 ±(99.9%) 0.023 ms/op
Iteration   3: 4.801 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.765 ±(99.9%) 0.860 ms/op [Average]
  (min, avg, max) = (4.712, 4.765, 4.801), stdev = 0.047
  CI (99.9%): [3.905, 5.625] (assumes normal distribution)


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
# Warmup Iteration   1: 5.182 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.949 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.008 ms/op
Iteration   1: 3.567 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.537 ms/op
                 createUser·p0.999:  12.330 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   2: 3.569 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 28.412 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 3.621 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  9.143 ms/op
                 createUser·p0.9999: 22.615 ms/op
                 createUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 267691
  mean =      3.585 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5734 
    [ 2.500,  5.000) = 257017 
    [ 5.000,  7.500) = 4261 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     11.638 ms/op
     p(99.9900) =     27.901 ms/op
     p(99.9990) =     28.617 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 4.856 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.008 ms/op
Iteration   1: 3.480 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.119 ms/op
                 existUser·p0.999:  7.799 ms/op
                 existUser·p0.9999: 14.637 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   2: 3.452 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  8.233 ms/op
                 existUser·p0.9999: 16.138 ms/op
                 existUser·p1.00:   16.466 ms/op

Iteration   3: 3.449 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  8.038 ms/op
                 existUser·p0.9999: 18.722 ms/op
                 existUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277401
  mean =      3.460 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 450 
    [ 1.250,  2.500) = 8567 
    [ 2.500,  3.750) = 203911 
    [ 3.750,  5.000) = 61502 
    [ 5.000,  6.250) = 2147 
    [ 6.250,  7.500) = 416 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.054 ms/op
     p(99.9000) =      8.131 ms/op
     p(99.9900) =     17.244 ms/op
     p(99.9990) =     19.060 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 5.296 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.654 ±(99.9%) 0.008 ms/op
Iteration   1: 3.527 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  10.977 ms/op
                 getUser·p0.9999: 19.464 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   2: 3.652 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.455 ms/op
                 getUser·p0.999:  8.045 ms/op
                 getUser·p0.9999: 15.958 ms/op
                 getUser·p1.00:   16.695 ms/op

Iteration   3: 3.601 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.106 ms/op
                 getUser·p0.999:  7.907 ms/op
                 getUser·p0.9999: 20.619 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267196
  mean =      3.593 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6169 
    [ 2.500,  5.000) = 256570 
    [ 5.000,  7.500) = 3919 
    [ 7.500, 10.000) = 295 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =      9.287 ms/op
     p(99.9900) =     20.194 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 5.482 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.086 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.693 ±(99.9%) 0.013 ms/op
Iteration   1: 4.661 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  14.356 ms/op
                 listUser·p0.9999: 16.744 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 4.664 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.644 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 17.423 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 4.597 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.308 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  18.656 ms/op
                 listUser·p0.9999: 21.564 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207101
  mean =      4.640 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 464 
    [ 2.500,  5.000) = 167219 
    [ 5.000,  7.500) = 35210 
    [ 7.500, 10.000) = 3711 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     15.598 ms/op
     p(99.9900) =     21.000 ms/op
     p(99.9990) =     23.097 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.246 ± 2.708  ops/ms
ClientGrpc.existUser                       thrpt       3   9.790 ± 0.742  ops/ms
ClientGrpc.getUser                         thrpt       3   9.193 ± 0.504  ops/ms
ClientGrpc.listUser                        thrpt       3   7.303 ± 6.055  ops/ms
ClientGrpc.createUser                       avgt       3   3.472 ± 1.215   ms/op
ClientGrpc.existUser                        avgt       3   3.278 ± 0.161   ms/op
ClientGrpc.getUser                          avgt       3   3.560 ± 0.778   ms/op
ClientGrpc.listUser                         avgt       3   4.765 ± 0.860   ms/op
ClientGrpc.createUser                     sample  267691   3.585 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.750           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.162           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.638           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.901           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.705           ms/op
ClientGrpc.existUser                      sample  277401   3.460 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.852           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.051           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.054           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.131           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.244           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.497           ms/op
ClientGrpc.getUser                        sample  267196   3.593 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.569           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.190           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.439           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.287           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.194           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  207101   4.640 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.223           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.465           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.110           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.598           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.000           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.233           ms/op
