# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.364 ops/ms
# Warmup Iteration   2: 9.310 ops/ms
# Warmup Iteration   3: 10.412 ops/ms
Iteration   1: 10.720 ops/ms
Iteration   2: 10.638 ops/ms
Iteration   3: 10.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.688 ±(99.9%) 0.795 ops/ms [Average]
  (min, avg, max) = (10.638, 10.688, 10.720), stdev = 0.044
  CI (99.9%): [9.893, 11.483] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.331 ops/ms
# Warmup Iteration   2: 10.665 ops/ms
# Warmup Iteration   3: 11.101 ops/ms
Iteration   1: 11.176 ops/ms
Iteration   2: 11.002 ops/ms
Iteration   3: 11.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.065 ±(99.9%) 1.762 ops/ms [Average]
  (min, avg, max) = (11.002, 11.065, 11.176), stdev = 0.097
  CI (99.9%): [9.302, 12.827] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.095 ops/ms
# Warmup Iteration   2: 10.229 ops/ms
# Warmup Iteration   3: 10.397 ops/ms
Iteration   1: 10.578 ops/ms
Iteration   2: 10.518 ops/ms
Iteration   3: 10.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.554 ±(99.9%) 0.574 ops/ms [Average]
  (min, avg, max) = (10.518, 10.554, 10.578), stdev = 0.031
  CI (99.9%): [9.979, 11.128] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.780 ops/ms
# Warmup Iteration   2: 7.459 ops/ms
# Warmup Iteration   3: 7.882 ops/ms
Iteration   1: 7.969 ops/ms
Iteration   2: 7.954 ops/ms
Iteration   3: 8.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.998 ±(99.9%) 1.168 ops/ms [Average]
  (min, avg, max) = (7.954, 7.998, 8.072), stdev = 0.064
  CI (99.9%): [6.830, 9.166] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.282 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 3.015 ±(99.9%) 0.001 ms/op
Iteration   3: 3.060 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.032 ±(99.9%) 0.443 ms/op [Average]
  (min, avg, max) = (3.015, 3.032, 3.060), stdev = 0.024
  CI (99.9%): [2.590, 3.475] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.002 ms/op
Iteration   1: 2.940 ±(99.9%) 0.002 ms/op
Iteration   2: 2.949 ±(99.9%) 0.002 ms/op
Iteration   3: 2.881 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.924 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (2.881, 2.924, 2.949), stdev = 0.037
  CI (99.9%): [2.250, 3.597] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.939 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.003 ms/op
Iteration   1: 3.073 ±(99.9%) 0.004 ms/op
Iteration   2: 3.074 ±(99.9%) 0.002 ms/op
Iteration   3: 3.055 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.067 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (3.055, 3.067, 3.074), stdev = 0.011
  CI (99.9%): [2.866, 3.268] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.867 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.009 ms/op
Iteration   1: 4.002 ±(99.9%) 0.021 ms/op
Iteration   2: 3.991 ±(99.9%) 0.013 ms/op
Iteration   3: 4.075 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.022 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (3.991, 4.022, 4.075), stdev = 0.046
  CI (99.9%): [3.189, 4.856] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.073 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.161 ms/op
                 createUser·p0.9999: 21.632 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.109 ms/op
                 createUser·p0.999:  7.201 ms/op
                 createUser·p0.9999: 23.921 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 2.989 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  19.694 ms/op
                 createUser·p0.9999: 37.814 ms/op
                 createUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316702
  mean =      3.029 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24853 
    [ 2.500,  5.000) = 290526 
    [ 5.000,  7.500) = 972 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      8.039 ms/op
     p(99.9900) =     37.246 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.028 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.005 ms/op
Iteration   1: 2.970 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.297 ms/op
                 existUser·p0.999:  8.454 ms/op
                 existUser·p0.9999: 12.820 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   2: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  8.356 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.908 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   3.959 ms/op
                 existUser·p0.999:  8.472 ms/op
                 existUser·p0.9999: 26.444 ms/op
                 existUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327923
  mean =      2.927 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30101 
    [ 2.500,  5.000) = 296728 
    [ 5.000,  7.500) = 646 
    [ 7.500, 10.000) = 214 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     19.622 ms/op
     p(99.9990) =     26.697 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.395 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.005 ms/op
Iteration   1: 3.087 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.446 ms/op
                 getUser·p0.9999: 16.798 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  12.503 ms/op
                 getUser·p0.9999: 14.303 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 3.034 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  6.223 ms/op
                 getUser·p0.9999: 17.186 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313809
  mean =      3.057 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 297 
    [ 1.250,  2.500) = 11820 
    [ 2.500,  3.750) = 288640 
    [ 3.750,  5.000) = 11942 
    [ 5.000,  6.250) = 518 
    [ 6.250,  7.500) = 285 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.427 ms/op
     p(99.9900) =     16.929 ms/op
     p(99.9990) =     17.587 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.547 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.010 ms/op
Iteration   1: 4.024 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.929 ms/op
                 listUser·p0.9999: 19.760 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   2: 3.986 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 23.297 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   3: 3.976 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  17.088 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240344
  mean =      3.995 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2828 
    [ 2.500,  5.000) = 215789 
    [ 5.000,  7.500) = 20296 
    [ 7.500, 10.000) = 984 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     24.332 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.688 ± 0.795  ops/ms
ClientGrpc.existUser                       thrpt       3  11.065 ± 1.762  ops/ms
ClientGrpc.getUser                         thrpt       3  10.554 ± 0.574  ops/ms
ClientGrpc.listUser                        thrpt       3   7.998 ± 1.168  ops/ms
ClientGrpc.createUser                       avgt       3   3.032 ± 0.443   ms/op
ClientGrpc.existUser                        avgt       3   2.924 ± 0.674   ms/op
ClientGrpc.getUser                          avgt       3   3.067 ± 0.201   ms/op
ClientGrpc.listUser                         avgt       3   4.022 ± 0.833   ms/op
ClientGrpc.createUser                     sample  316702   3.029 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.700           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.039           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          37.246           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          38.142           ms/op
ClientGrpc.existUser                      sample  327923   2.927 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.684           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.014           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.421           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.622           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.771           ms/op
ClientGrpc.getUser                        sample  313809   3.057 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.633           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.427           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.929           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.695           ms/op
ClientGrpc.listUser                       sample  240344   3.995 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.192           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.581           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.200           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
