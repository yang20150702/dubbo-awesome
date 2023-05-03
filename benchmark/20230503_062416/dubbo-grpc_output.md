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
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 5.829 ops/ms
# Warmup Iteration   3: 6.693 ops/ms
Iteration   1: 7.030 ops/ms
Iteration   2: 7.156 ops/ms
Iteration   3: 7.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.066 ±(99.9%) 1.423 ops/ms [Average]
  (min, avg, max) = (7.013, 7.066, 7.156), stdev = 0.078
  CI (99.9%): [5.643, 8.489] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.873 ops/ms
# Warmup Iteration   2: 7.334 ops/ms
# Warmup Iteration   3: 7.592 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 7.913 ops/ms
Iteration   3: 7.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.795 ±(99.9%) 1.889 ops/ms [Average]
  (min, avg, max) = (7.723, 7.795, 7.913), stdev = 0.104
  CI (99.9%): [5.906, 9.683] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ops/ms
# Warmup Iteration   2: 6.588 ops/ms
# Warmup Iteration   3: 6.764 ops/ms
Iteration   1: 7.161 ops/ms
Iteration   2: 7.206 ops/ms
Iteration   3: 7.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.223 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (7.161, 7.223, 7.303), stdev = 0.073
  CI (99.9%): [5.894, 8.552] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.517 ops/ms
# Warmup Iteration   2: 5.138 ops/ms
# Warmup Iteration   3: 5.613 ops/ms
Iteration   1: 5.654 ops/ms
Iteration   2: 5.579 ops/ms
Iteration   3: 5.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.618 ±(99.9%) 0.691 ops/ms [Average]
  (min, avg, max) = (5.579, 5.618, 5.654), stdev = 0.038
  CI (99.9%): [4.927, 6.309] (assumes normal distribution)


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
# Warmup Iteration   1: 6.457 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.666 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.476 ±(99.9%) 0.014 ms/op
Iteration   1: 4.333 ±(99.9%) 0.003 ms/op
Iteration   2: 4.174 ±(99.9%) 0.004 ms/op
Iteration   3: 4.289 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.266 ±(99.9%) 1.504 ms/op [Average]
  (min, avg, max) = (4.174, 4.266, 4.333), stdev = 0.082
  CI (99.9%): [2.761, 5.770] (assumes normal distribution)


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
# Warmup Iteration   1: 6.778 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.003 ms/op
Iteration   1: 4.117 ±(99.9%) 0.003 ms/op
Iteration   2: 4.211 ±(99.9%) 0.003 ms/op
Iteration   3: 4.082 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.136 ±(99.9%) 1.216 ms/op [Average]
  (min, avg, max) = (4.082, 4.136, 4.211), stdev = 0.067
  CI (99.9%): [2.921, 5.352] (assumes normal distribution)


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
# Warmup Iteration   1: 6.493 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.536 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.410 ±(99.9%) 0.005 ms/op
Iteration   1: 4.335 ±(99.9%) 0.004 ms/op
Iteration   2: 4.342 ±(99.9%) 0.004 ms/op
Iteration   3: 4.304 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.327 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (4.304, 4.327, 4.342), stdev = 0.020
  CI (99.9%): [3.959, 4.695] (assumes normal distribution)


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
# Warmup Iteration   1: 8.917 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 6.197 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.805 ±(99.9%) 0.015 ms/op
Iteration   1: 5.700 ±(99.9%) 0.021 ms/op
Iteration   2: 5.591 ±(99.9%) 0.017 ms/op
Iteration   3: 5.638 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.643 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (5.591, 5.643, 5.700), stdev = 0.055
  CI (99.9%): [4.642, 6.645] (assumes normal distribution)


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
# Warmup Iteration   1: 6.765 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.719 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.470 ±(99.9%) 0.014 ms/op
Iteration   1: 4.478 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   7.855 ms/op
                 createUser·p0.999:  12.746 ms/op
                 createUser·p0.9999: 18.232 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   2: 4.330 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.915 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  14.500 ms/op
                 createUser·p0.9999: 21.109 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 4.447 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   6.070 ms/op
                 createUser·p0.99:   8.297 ms/op
                 createUser·p0.999:  14.632 ms/op
                 createUser·p0.9999: 23.699 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 217424
  mean =      4.418 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2497 
    [ 2.500,  5.000) = 168994 
    [ 5.000,  7.500) = 43156 
    [ 7.500, 10.000) = 2246 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.840 ms/op
     p(99.9000) =     13.987 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     24.133 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 6.302 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.013 ms/op
Iteration   1: 4.087 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.977 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.512 ms/op
                 existUser·p0.999:  12.889 ms/op
                 existUser·p0.9999: 16.242 ms/op
                 existUser·p1.00:   16.728 ms/op

Iteration   2: 4.004 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   3.920 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   7.023 ms/op
                 existUser·p0.999:  9.833 ms/op
                 existUser·p0.9999: 17.662 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 4.078 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  14.008 ms/op
                 existUser·p0.9999: 21.900 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236571
  mean =      4.056 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8177 
    [ 2.500,  5.000) = 203657 
    [ 5.000,  7.500) = 22779 
    [ 7.500, 10.000) = 1543 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     12.950 ms/op
     p(99.9900) =     20.196 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 6.630 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.568 ±(99.9%) 0.013 ms/op
Iteration   1: 4.415 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.956 ms/op
                 getUser·p0.99:   7.774 ms/op
                 getUser·p0.999:  13.910 ms/op
                 getUser·p0.9999: 17.859 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 4.335 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  13.271 ms/op
                 getUser·p0.9999: 44.671 ms/op
                 getUser·p1.00:   46.203 ms/op

Iteration   3: 4.377 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  17.169 ms/op
                 getUser·p0.9999: 22.282 ms/op
                 getUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 219310
  mean =      4.376 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 179772 
    [ 5.000, 10.000) = 38869 
    [10.000, 15.000) = 484 
    [15.000, 20.000) = 93 
    [20.000, 25.000) = 60 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.414 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     14.032 ms/op
     p(99.9900) =     44.176 ms/op
     p(99.9990) =     44.932 ms/op
     p(99.9999) =     46.203 ms/op
    p(100.0000) =     46.203 ms/op


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
# Warmup Iteration   1: 8.641 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.288 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.743 ±(99.9%) 0.022 ms/op
Iteration   1: 5.801 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  18.410 ms/op
                 listUser·p0.9999: 25.428 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   2: 5.638 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.380 ms/op
                 listUser·p0.99:   10.729 ms/op
                 listUser·p0.999:  28.193 ms/op
                 listUser·p0.9999: 32.326 ms/op
                 listUser·p1.00:   36.700 ms/op

Iteration   3: 5.768 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.502 ms/op
                 listUser·p0.999:  20.561 ms/op
                 listUser·p0.9999: 28.698 ms/op
                 listUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167515
  mean =      5.735 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 210 
    [ 2.500,  5.000) = 52068 
    [ 5.000,  7.500) = 97879 
    [ 7.500, 10.000) = 14446 
    [10.000, 12.500) = 2375 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.553 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     10.729 ms/op
     p(99.9000) =     20.168 ms/op
     p(99.9900) =     30.310 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.066 ± 1.423  ops/ms
ClientGrpc.existUser                       thrpt       3   7.795 ± 1.889  ops/ms
ClientGrpc.getUser                         thrpt       3   7.223 ± 1.329  ops/ms
ClientGrpc.listUser                        thrpt       3   5.618 ± 0.691  ops/ms
ClientGrpc.createUser                       avgt       3   4.266 ± 1.504   ms/op
ClientGrpc.existUser                        avgt       3   4.136 ± 1.216   ms/op
ClientGrpc.getUser                          avgt       3   4.327 ± 0.368   ms/op
ClientGrpc.listUser                         avgt       3   5.643 ± 1.001   ms/op
ClientGrpc.createUser                     sample  217424   4.418 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.009           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.046           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.840           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.987           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.234           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.248           ms/op
ClientGrpc.existUser                      sample  236571   4.056 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.614           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.513           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.209           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.950           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.196           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.217           ms/op
ClientGrpc.getUser                        sample  219310   4.376 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.857           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.414           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.931           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.692           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.032           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          44.176           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          46.203           ms/op
ClientGrpc.listUser                       sample  167515   5.735 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.477           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.553           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.729           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.168           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.310           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.700           ms/op
