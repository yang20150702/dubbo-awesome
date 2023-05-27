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
# Warmup Iteration   1: 3.444 ops/ms
# Warmup Iteration   2: 7.522 ops/ms
# Warmup Iteration   3: 8.760 ops/ms
Iteration   1: 9.117 ops/ms
Iteration   2: 9.154 ops/ms
Iteration   3: 8.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.021 ±(99.9%) 3.619 ops/ms [Average]
  (min, avg, max) = (8.793, 9.021, 9.154), stdev = 0.198
  CI (99.9%): [5.402, 12.641] (assumes normal distribution)


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
# Warmup Iteration   1: 5.899 ops/ms
# Warmup Iteration   2: 8.802 ops/ms
# Warmup Iteration   3: 9.329 ops/ms
Iteration   1: 9.346 ops/ms
Iteration   2: 9.541 ops/ms
Iteration   3: 9.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.492 ±(99.9%) 2.343 ops/ms [Average]
  (min, avg, max) = (9.346, 9.492, 9.589), stdev = 0.128
  CI (99.9%): [7.149, 11.835] (assumes normal distribution)


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
# Warmup Iteration   1: 5.468 ops/ms
# Warmup Iteration   2: 8.050 ops/ms
# Warmup Iteration   3: 8.444 ops/ms
Iteration   1: 8.411 ops/ms
Iteration   2: 9.025 ops/ms
Iteration   3: 8.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.724 ±(99.9%) 5.601 ops/ms [Average]
  (min, avg, max) = (8.411, 8.724, 9.025), stdev = 0.307
  CI (99.9%): [3.123, 14.325] (assumes normal distribution)


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
# Warmup Iteration   1: 4.455 ops/ms
# Warmup Iteration   2: 6.459 ops/ms
# Warmup Iteration   3: 6.788 ops/ms
Iteration   1: 6.708 ops/ms
Iteration   2: 6.988 ops/ms
Iteration   3: 6.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.893 ±(99.9%) 2.914 ops/ms [Average]
  (min, avg, max) = (6.708, 6.893, 6.988), stdev = 0.160
  CI (99.9%): [3.979, 9.807] (assumes normal distribution)


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
# Warmup Iteration   1: 5.619 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.009 ms/op
Iteration   1: 3.528 ±(99.9%) 0.004 ms/op
Iteration   2: 3.445 ±(99.9%) 0.004 ms/op
Iteration   3: 3.359 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.444 ±(99.9%) 1.540 ms/op [Average]
  (min, avg, max) = (3.359, 3.444, 3.528), stdev = 0.084
  CI (99.9%): [1.904, 4.984] (assumes normal distribution)


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
# Warmup Iteration   1: 4.540 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.003 ms/op
Iteration   1: 3.414 ±(99.9%) 0.002 ms/op
Iteration   2: 3.302 ±(99.9%) 0.003 ms/op
Iteration   3: 3.314 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.343 ±(99.9%) 1.122 ms/op [Average]
  (min, avg, max) = (3.302, 3.343, 3.414), stdev = 0.061
  CI (99.9%): [2.222, 4.465] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.027 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.005 ms/op
Iteration   1: 3.435 ±(99.9%) 0.005 ms/op
Iteration   2: 3.545 ±(99.9%) 0.005 ms/op
Iteration   3: 3.540 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.507 ±(99.9%) 1.133 ms/op [Average]
  (min, avg, max) = (3.435, 3.507, 3.545), stdev = 0.062
  CI (99.9%): [2.373, 4.640] (assumes normal distribution)


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
# Warmup Iteration   1: 6.084 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.857 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.620 ±(99.9%) 0.013 ms/op
Iteration   1: 4.569 ±(99.9%) 0.023 ms/op
Iteration   2: 4.642 ±(99.9%) 0.011 ms/op
Iteration   3: 4.514 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.575 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (4.514, 4.575, 4.642), stdev = 0.064
  CI (99.9%): [3.407, 5.742] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.762 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.008 ms/op
Iteration   1: 3.531 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  12.377 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   2: 3.521 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  7.546 ms/op
                 createUser·p0.9999: 14.825 ms/op
                 createUser·p1.00:   16.466 ms/op

Iteration   3: 3.545 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  8.946 ms/op
                 createUser·p0.9999: 18.121 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271657
  mean =      3.532 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8099 
    [ 2.500,  5.000) = 259012 
    [ 5.000,  7.500) = 4106 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     22.628 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 4.722 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.007 ms/op
Iteration   1: 3.302 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  7.504 ms/op
                 existUser·p0.9999: 14.182 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 3.327 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   4.755 ms/op
                 existUser·p0.999:  9.854 ms/op
                 existUser·p0.9999: 16.921 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   3: 3.316 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  12.370 ms/op
                 existUser·p0.9999: 18.317 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 289687
  mean =      3.315 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 674 
    [ 1.250,  2.500) = 11687 
    [ 2.500,  3.750) = 243819 
    [ 3.750,  5.000) = 31212 
    [ 5.000,  6.250) = 1509 
    [ 6.250,  7.500) = 315 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =     10.819 ms/op
     p(99.9900) =     16.909 ms/op
     p(99.9990) =     18.439 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.736 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.008 ms/op
Iteration   1: 3.522 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  7.858 ms/op
                 getUser·p0.9999: 13.582 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   2: 3.516 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  8.274 ms/op
                 getUser·p0.9999: 18.871 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   3: 3.504 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  7.935 ms/op
                 getUser·p0.9999: 30.728 ms/op
                 getUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 273288
  mean =      3.514 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9196 
    [ 2.500,  5.000) = 259791 
    [ 5.000,  7.500) = 3891 
    [ 7.500, 10.000) = 255 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =      8.069 ms/op
     p(99.9900) =     30.180 ms/op
     p(99.9990) =     30.975 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 5.973 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.914 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.541 ±(99.9%) 0.013 ms/op
Iteration   1: 4.591 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  15.057 ms/op
                 listUser·p0.9999: 16.975 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   2: 4.479 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  15.195 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 4.576 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  19.568 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 211073
  mean =      4.548 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 325 
    [ 2.500,  5.000) = 179614 
    [ 5.000,  7.500) = 27697 
    [ 7.500, 10.000) = 3019 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      7.916 ms/op
     p(99.9000) =     15.514 ms/op
     p(99.9900) =     21.063 ms/op
     p(99.9990) =     22.209 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.021 ± 3.619  ops/ms
ClientGrpc.existUser                       thrpt       3   9.492 ± 2.343  ops/ms
ClientGrpc.getUser                         thrpt       3   8.724 ± 5.601  ops/ms
ClientGrpc.listUser                        thrpt       3   6.893 ± 2.914  ops/ms
ClientGrpc.createUser                       avgt       3   3.444 ± 1.540   ms/op
ClientGrpc.existUser                        avgt       3   3.343 ± 1.122   ms/op
ClientGrpc.getUser                          avgt       3   3.507 ± 1.133   ms/op
ClientGrpc.listUser                         avgt       3   4.575 ± 1.168   ms/op
ClientGrpc.createUser                     sample  271657   3.532 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.863           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.166           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.684           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.151           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.774           ms/op
ClientGrpc.existUser                      sample  289687   3.315 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.782           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.858           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.819           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.909           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.678           ms/op
ClientGrpc.getUser                        sample  273288   3.514 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.695           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.166           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.382           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.069           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.180           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.031           ms/op
ClientGrpc.listUser                       sample  211073   4.548 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.149           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.407           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.185           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.916           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.514           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.063           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.282           ms/op
