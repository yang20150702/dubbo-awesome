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
# Warmup Iteration   1: 3.302 ops/ms
# Warmup Iteration   2: 7.313 ops/ms
# Warmup Iteration   3: 8.628 ops/ms
Iteration   1: 9.085 ops/ms
Iteration   2: 9.043 ops/ms
Iteration   3: 9.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.128 ±(99.9%) 2.042 ops/ms [Average]
  (min, avg, max) = (9.043, 9.128, 9.255), stdev = 0.112
  CI (99.9%): [7.085, 11.170] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.207 ops/ms
# Warmup Iteration   2: 9.276 ops/ms
# Warmup Iteration   3: 9.541 ops/ms
Iteration   1: 9.440 ops/ms
Iteration   2: 9.691 ops/ms
Iteration   3: 9.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.650 ±(99.9%) 3.517 ops/ms [Average]
  (min, avg, max) = (9.440, 9.650, 9.819), stdev = 0.193
  CI (99.9%): [6.134, 13.167] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.720 ops/ms
# Warmup Iteration   2: 8.902 ops/ms
# Warmup Iteration   3: 9.060 ops/ms
Iteration   1: 8.963 ops/ms
Iteration   2: 9.051 ops/ms
Iteration   3: 9.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.083 ±(99.9%) 2.531 ops/ms [Average]
  (min, avg, max) = (8.963, 9.083, 9.235), stdev = 0.139
  CI (99.9%): [6.552, 11.614] (assumes normal distribution)


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
# Warmup Iteration   1: 4.389 ops/ms
# Warmup Iteration   2: 6.913 ops/ms
# Warmup Iteration   3: 6.932 ops/ms
Iteration   1: 7.112 ops/ms
Iteration   2: 7.077 ops/ms
Iteration   3: 6.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.060 ±(99.9%) 1.135 ops/ms [Average]
  (min, avg, max) = (6.991, 7.060, 7.112), stdev = 0.062
  CI (99.9%): [5.925, 8.195] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.042 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.004 ms/op
Iteration   1: 3.477 ±(99.9%) 0.005 ms/op
Iteration   2: 3.433 ±(99.9%) 0.004 ms/op
Iteration   3: 3.475 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.462 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.433, 3.462, 3.477), stdev = 0.025
  CI (99.9%): [3.007, 3.916] (assumes normal distribution)


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.003 ms/op
Iteration   1: 3.341 ±(99.9%) 0.002 ms/op
Iteration   2: 3.298 ±(99.9%) 0.004 ms/op
Iteration   3: 3.360 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.333 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (3.298, 3.333, 3.360), stdev = 0.032
  CI (99.9%): [2.752, 3.914] (assumes normal distribution)


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
# Warmup Iteration   1: 5.113 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.003 ms/op
Iteration   1: 3.467 ±(99.9%) 0.004 ms/op
Iteration   2: 3.471 ±(99.9%) 0.003 ms/op
Iteration   3: 3.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.460 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.444, 3.460, 3.471), stdev = 0.015
  CI (99.9%): [3.192, 3.729] (assumes normal distribution)


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
# Warmup Iteration   1: 6.285 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.938 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.508 ±(99.9%) 0.017 ms/op
Iteration   1: 4.543 ±(99.9%) 0.015 ms/op
Iteration   2: 4.433 ±(99.9%) 0.015 ms/op
Iteration   3: 4.506 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.494 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (4.433, 4.494, 4.543), stdev = 0.056
  CI (99.9%): [3.473, 5.515] (assumes normal distribution)


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
# Warmup Iteration   1: 5.241 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.007 ms/op
Iteration   1: 3.476 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.345 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.290 ms/op
                 createUser·p0.999:  9.981 ms/op
                 createUser·p0.9999: 24.596 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 3.469 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  10.043 ms/op
                 createUser·p0.9999: 15.840 ms/op
                 createUser·p1.00:   16.269 ms/op

Iteration   3: 3.516 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  17.590 ms/op
                 createUser·p0.9999: 36.176 ms/op
                 createUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 275314
  mean =      3.487 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12029 
    [ 2.500,  5.000) = 259123 
    [ 5.000,  7.500) = 3485 
    [ 7.500, 10.000) = 336 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.356 ms/op
     p(99.9000) =     10.672 ms/op
     p(99.9900) =     34.800 ms/op
     p(99.9990) =     36.176 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 4.811 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.007 ms/op
Iteration   1: 3.276 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  7.490 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 3.235 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  7.384 ms/op
                 existUser·p0.9999: 23.036 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   3: 3.338 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  7.432 ms/op
                 existUser·p0.9999: 17.886 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 292274
  mean =      3.282 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26406 
    [ 2.500,  5.000) = 262684 
    [ 5.000,  7.500) = 2907 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      5.063 ms/op
     p(99.9000) =      7.461 ms/op
     p(99.9900) =     21.238 ms/op
     p(99.9990) =     23.202 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 5.011 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.006 ms/op
Iteration   1: 3.413 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  9.695 ms/op
                 getUser·p0.9999: 15.688 ms/op
                 getUser·p1.00:   16.318 ms/op

Iteration   2: 3.341 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   4.922 ms/op
                 getUser·p0.999:  9.929 ms/op
                 getUser·p0.9999: 15.717 ms/op
                 getUser·p1.00:   16.187 ms/op

Iteration   3: 3.458 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  7.750 ms/op
                 getUser·p0.9999: 17.686 ms/op
                 getUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 282041
  mean =      3.403 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 728 
    [ 1.250,  2.500) = 16652 
    [ 2.500,  3.750) = 204596 
    [ 3.750,  5.000) = 56565 
    [ 5.000,  6.250) = 2514 
    [ 6.250,  7.500) = 504 
    [ 7.500,  8.750) = 214 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 68 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     16.747 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 6.969 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.727 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.545 ±(99.9%) 0.012 ms/op
Iteration   1: 4.445 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   7.630 ms/op
                 listUser·p0.999:  13.222 ms/op
                 listUser·p0.9999: 18.736 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 4.533 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   7.882 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 20.377 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 4.343 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   4.243 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 25.592 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 216401
  mean =      4.439 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 507 
    [ 2.500,  5.000) = 188204 
    [ 5.000,  7.500) = 24685 
    [ 7.500, 10.000) = 2517 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     16.862 ms/op
     p(99.9900) =     24.096 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.128 ± 2.042  ops/ms
ClientGrpc.existUser                       thrpt       3   9.650 ± 3.517  ops/ms
ClientGrpc.getUser                         thrpt       3   9.083 ± 2.531  ops/ms
ClientGrpc.listUser                        thrpt       3   7.060 ± 1.135  ops/ms
ClientGrpc.createUser                       avgt       3   3.462 ± 0.454   ms/op
ClientGrpc.existUser                        avgt       3   3.333 ± 0.581   ms/op
ClientGrpc.getUser                          avgt       3   3.460 ± 0.269   ms/op
ClientGrpc.listUser                         avgt       3   4.494 ± 1.021   ms/op
ClientGrpc.createUser                     sample  275314   3.487 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.345           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.104           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.356           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.672           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.800           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.176           ms/op
ClientGrpc.existUser                      sample  292274   3.282 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.588           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.063           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.461           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.238           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.331           ms/op
ClientGrpc.getUser                        sample  282041   3.403 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.643           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.408           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.552           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.747           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.973           ms/op
ClientGrpc.listUser                       sample  216401   4.439 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.860           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.309           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.111           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.807           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.862           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.096           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
