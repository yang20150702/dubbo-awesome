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
# Warmup Iteration   1: 2.149 ops/ms
# Warmup Iteration   2: 5.338 ops/ms
# Warmup Iteration   3: 6.543 ops/ms
Iteration   1: 6.943 ops/ms
Iteration   2: 7.046 ops/ms
Iteration   3: 7.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.025 ±(99.9%) 1.362 ops/ms [Average]
  (min, avg, max) = (6.943, 7.025, 7.088), stdev = 0.075
  CI (99.9%): [5.664, 8.387] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.519 ops/ms
# Warmup Iteration   2: 7.193 ops/ms
# Warmup Iteration   3: 7.793 ops/ms
Iteration   1: 7.781 ops/ms
Iteration   2: 7.849 ops/ms
Iteration   3: 7.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.835 ±(99.9%) 0.889 ops/ms [Average]
  (min, avg, max) = (7.781, 7.835, 7.876), stdev = 0.049
  CI (99.9%): [6.946, 8.724] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.168 ops/ms
# Warmup Iteration   2: 6.573 ops/ms
# Warmup Iteration   3: 6.922 ops/ms
Iteration   1: 7.346 ops/ms
Iteration   2: 7.319 ops/ms
Iteration   3: 7.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.356 ±(99.9%) 0.794 ops/ms [Average]
  (min, avg, max) = (7.319, 7.356, 7.404), stdev = 0.044
  CI (99.9%): [6.562, 8.150] (assumes normal distribution)


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
# Warmup Iteration   1: 3.620 ops/ms
# Warmup Iteration   2: 5.355 ops/ms
# Warmup Iteration   3: 5.536 ops/ms
Iteration   1: 5.665 ops/ms
Iteration   2: 5.607 ops/ms
Iteration   3: 5.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.638 ±(99.9%) 0.533 ops/ms [Average]
  (min, avg, max) = (5.607, 5.638, 5.665), stdev = 0.029
  CI (99.9%): [5.106, 6.171] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.913 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.753 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.426 ±(99.9%) 0.005 ms/op
Iteration   1: 4.379 ±(99.9%) 0.007 ms/op
Iteration   2: 4.439 ±(99.9%) 0.003 ms/op
Iteration   3: 4.323 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.380 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (4.323, 4.380, 4.439), stdev = 0.058
  CI (99.9%): [3.327, 5.434] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.672 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.247 ±(99.9%) 0.004 ms/op
Iteration   1: 4.143 ±(99.9%) 0.005 ms/op
Iteration   2: 4.109 ±(99.9%) 0.004 ms/op
Iteration   3: 4.193 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.148 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (4.109, 4.148, 4.193), stdev = 0.042
  CI (99.9%): [3.385, 4.912] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.846 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.497 ±(99.9%) 0.008 ms/op
Iteration   1: 4.457 ±(99.9%) 0.004 ms/op
Iteration   2: 4.392 ±(99.9%) 0.004 ms/op
Iteration   3: 4.397 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.416 ±(99.9%) 0.665 ms/op [Average]
  (min, avg, max) = (4.392, 4.416, 4.457), stdev = 0.036
  CI (99.9%): [3.751, 5.080] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.451 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 6.100 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.491 ±(99.9%) 0.012 ms/op
Iteration   1: 5.624 ±(99.9%) 0.012 ms/op
Iteration   2: 5.723 ±(99.9%) 0.023 ms/op
Iteration   3: 5.640 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.662 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (5.624, 5.662, 5.723), stdev = 0.053
  CI (99.9%): [4.698, 6.627] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.058 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.808 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.604 ±(99.9%) 0.016 ms/op
Iteration   1: 4.492 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  13.121 ms/op
                 createUser·p0.9999: 19.551 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   2: 4.419 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.423 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   8.651 ms/op
                 createUser·p0.999:  15.394 ms/op
                 createUser·p0.9999: 30.376 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   3: 4.474 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.612 ms/op
                 createUser·p0.95:   6.095 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  26.345 ms/op
                 createUser·p0.9999: 29.379 ms/op
                 createUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215136
  mean =      4.461 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5038 
    [ 2.500,  5.000) = 164492 
    [ 5.000,  7.500) = 41309 
    [ 7.500, 10.000) = 3224 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     15.350 ms/op
     p(99.9900) =     29.704 ms/op
     p(99.9990) =     31.831 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 6.672 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.509 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.013 ms/op
Iteration   1: 4.245 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   4.116 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   7.985 ms/op
                 existUser·p0.999:  13.561 ms/op
                 existUser·p0.9999: 20.069 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 4.288 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   4.149 ms/op
                 existUser·p0.90:   5.423 ms/op
                 existUser·p0.95:   5.906 ms/op
                 existUser·p0.99:   8.036 ms/op
                 existUser·p0.999:  12.949 ms/op
                 existUser·p0.9999: 18.645 ms/op
                 existUser·p1.00:   19.137 ms/op

Iteration   3: 4.244 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   4.112 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   5.857 ms/op
                 existUser·p0.99:   8.364 ms/op
                 existUser·p0.999:  12.854 ms/op
                 existUser·p0.9999: 19.479 ms/op
                 existUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 225424
  mean =      4.259 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8149 
    [ 2.500,  5.000) = 179477 
    [ 5.000,  7.500) = 34554 
    [ 7.500, 10.000) = 2562 
    [10.000, 12.500) = 387 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     19.545 ms/op
     p(99.9990) =     20.537 ms/op
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
# Warmup Iteration   1: 7.163 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.773 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.485 ±(99.9%) 0.015 ms/op
Iteration   1: 4.410 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.595 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  13.164 ms/op
                 getUser·p0.9999: 16.466 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   2: 4.382 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.234 ms/op
                 getUser·p0.99:   9.044 ms/op
                 getUser·p0.999:  13.566 ms/op
                 getUser·p0.9999: 18.878 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   3: 4.458 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   6.111 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  11.794 ms/op
                 getUser·p0.9999: 28.970 ms/op
                 getUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217377
  mean =      4.417 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6500 
    [ 2.500,  5.000) = 165986 
    [ 5.000,  7.500) = 40426 
    [ 7.500, 10.000) = 3530 
    [10.000, 12.500) = 697 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.193 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 8.388 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 6.220 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.842 ±(99.9%) 0.025 ms/op
Iteration   1: 5.697 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  20.425 ms/op
                 listUser·p0.9999: 21.987 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 5.602 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   5.267 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.356 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  27.030 ms/op
                 listUser·p0.9999: 31.548 ms/op
                 listUser·p1.00:   32.342 ms/op

Iteration   3: 5.508 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.307 ms/op
                 listUser·p0.95:   8.323 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  28.934 ms/op
                 listUser·p0.9999: 35.284 ms/op
                 listUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171350
  mean =      5.601 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 249 
    [ 2.500,  5.000) = 63399 
    [ 5.000,  7.500) = 91507 
    [ 7.500, 10.000) = 13208 
    [10.000, 12.500) = 2128 
    [12.500, 15.000) = 461 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      7.414 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     24.813 ms/op
     p(99.9900) =     34.052 ms/op
     p(99.9990) =     35.689 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.025 ± 1.362  ops/ms
ClientGrpc.existUser                       thrpt       3   7.835 ± 0.889  ops/ms
ClientGrpc.getUser                         thrpt       3   7.356 ± 0.794  ops/ms
ClientGrpc.listUser                        thrpt       3   5.638 ± 0.533  ops/ms
ClientGrpc.createUser                       avgt       3   4.380 ± 1.053   ms/op
ClientGrpc.existUser                        avgt       3   4.148 ± 0.764   ms/op
ClientGrpc.getUser                          avgt       3   4.416 ± 0.665   ms/op
ClientGrpc.listUser                         avgt       3   5.662 ± 0.964   ms/op
ClientGrpc.createUser                     sample  215136   4.461 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.729           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.136           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.815           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.350           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.704           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.440           ms/op
ClientGrpc.existUser                      sample  225424   4.259 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.828           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.366           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.865           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.135           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.042           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.545           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.413           ms/op
ClientGrpc.getUser                        sample  217377   4.417 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.063           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.571           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.193           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.684           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.796           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.559           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.131           ms/op
ClientGrpc.listUser                       sample  171350   5.601 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.378           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.421           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.076           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          24.813           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.052           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.783           ms/op
