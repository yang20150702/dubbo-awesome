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
# Warmup Iteration   1: 1.953 ops/ms
# Warmup Iteration   2: 4.813 ops/ms
# Warmup Iteration   3: 6.519 ops/ms
Iteration   1: 6.788 ops/ms
Iteration   2: 6.723 ops/ms
Iteration   3: 6.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.743 ±(99.9%) 0.705 ops/ms [Average]
  (min, avg, max) = (6.719, 6.743, 6.788), stdev = 0.039
  CI (99.9%): [6.038, 7.449] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.311 ops/ms
# Warmup Iteration   2: 6.493 ops/ms
# Warmup Iteration   3: 7.187 ops/ms
Iteration   1: 7.312 ops/ms
Iteration   2: 7.410 ops/ms
Iteration   3: 7.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.395 ±(99.9%) 1.410 ops/ms [Average]
  (min, avg, max) = (7.312, 7.395, 7.465), stdev = 0.077
  CI (99.9%): [5.986, 8.805] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.814 ops/ms
# Warmup Iteration   2: 6.163 ops/ms
# Warmup Iteration   3: 6.738 ops/ms
Iteration   1: 6.942 ops/ms
Iteration   2: 6.940 ops/ms
Iteration   3: 6.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.944 ±(99.9%) 0.102 ops/ms [Average]
  (min, avg, max) = (6.940, 6.944, 6.951), stdev = 0.006
  CI (99.9%): [6.843, 7.046] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.586 ops/ms
# Warmup Iteration   2: 4.892 ops/ms
# Warmup Iteration   3: 5.281 ops/ms
Iteration   1: 5.469 ops/ms
Iteration   2: 5.448 ops/ms
Iteration   3: 5.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.455 ±(99.9%) 0.227 ops/ms [Average]
  (min, avg, max) = (5.447, 5.455, 5.469), stdev = 0.012
  CI (99.9%): [5.228, 5.682] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.065 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.054 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.935 ±(99.9%) 0.010 ms/op
Iteration   1: 4.900 ±(99.9%) 0.006 ms/op
Iteration   2: 4.735 ±(99.9%) 0.006 ms/op
Iteration   3: 4.647 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.761 ±(99.9%) 2.341 ms/op [Average]
  (min, avg, max) = (4.647, 4.761, 4.900), stdev = 0.128
  CI (99.9%): [2.420, 7.101] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.166 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.731 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.417 ±(99.9%) 0.006 ms/op
Iteration   1: 4.401 ±(99.9%) 0.004 ms/op
Iteration   2: 4.240 ±(99.9%) 0.007 ms/op
Iteration   3: 4.261 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.301 ±(99.9%) 1.607 ms/op [Average]
  (min, avg, max) = (4.240, 4.301, 4.401), stdev = 0.088
  CI (99.9%): [2.694, 5.907] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.801 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.939 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.693 ±(99.9%) 0.009 ms/op
Iteration   1: 4.674 ±(99.9%) 0.006 ms/op
Iteration   2: 4.668 ±(99.9%) 0.008 ms/op
Iteration   3: 4.606 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.649 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (4.606, 4.649, 4.674), stdev = 0.038
  CI (99.9%): [3.961, 5.337] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.899 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 6.397 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.859 ±(99.9%) 0.013 ms/op
Iteration   1: 5.989 ±(99.9%) 0.022 ms/op
Iteration   2: 5.794 ±(99.9%) 0.023 ms/op
Iteration   3: 6.055 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.946 ±(99.9%) 2.479 ms/op [Average]
  (min, avg, max) = (5.794, 5.946, 6.055), stdev = 0.136
  CI (99.9%): [3.467, 8.425] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.868 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.144 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.827 ±(99.9%) 0.017 ms/op
Iteration   1: 4.839 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   4.686 ms/op
                 createUser·p0.90:   5.972 ms/op
                 createUser·p0.95:   6.455 ms/op
                 createUser·p0.99:   8.913 ms/op
                 createUser·p0.999:  13.954 ms/op
                 createUser·p0.9999: 21.718 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 4.732 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   4.563 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   6.513 ms/op
                 createUser·p0.99:   8.913 ms/op
                 createUser·p0.999:  11.960 ms/op
                 createUser·p0.9999: 26.656 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   3: 4.706 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   4.579 ms/op
                 createUser·p0.90:   5.857 ms/op
                 createUser·p0.95:   6.414 ms/op
                 createUser·p0.99:   9.175 ms/op
                 createUser·p0.999:  18.975 ms/op
                 createUser·p0.9999: 29.698 ms/op
                 createUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 201733
  mean =      4.758 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3725 
    [ 2.500,  5.000) = 132585 
    [ 5.000,  7.500) = 60975 
    [ 7.500, 10.000) = 3316 
    [10.000, 12.500) = 821 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     14.279 ms/op
     p(99.9900) =     28.443 ms/op
     p(99.9990) =     31.523 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.503 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.860 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.533 ±(99.9%) 0.014 ms/op
Iteration   1: 4.430 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   4.309 ms/op
                 existUser·p0.90:   5.489 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   8.847 ms/op
                 existUser·p0.999:  14.339 ms/op
                 existUser·p0.9999: 22.032 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   2: 4.451 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   4.342 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   5.915 ms/op
                 existUser·p0.99:   7.611 ms/op
                 existUser·p0.999:  13.287 ms/op
                 existUser·p0.9999: 19.157 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   3: 4.474 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   4.325 ms/op
                 existUser·p0.90:   5.546 ms/op
                 existUser·p0.95:   6.095 ms/op
                 existUser·p0.99:   8.487 ms/op
                 existUser·p0.999:  17.334 ms/op
                 existUser·p0.9999: 27.871 ms/op
                 existUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 215511
  mean =      4.452 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5118 
    [ 2.500,  5.000) = 167139 
    [ 5.000,  7.500) = 40066 
    [ 7.500, 10.000) = 2178 
    [10.000, 12.500) = 587 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.489 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      8.363 ms/op
     p(99.9000) =     15.384 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     27.951 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.894 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.069 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.691 ±(99.9%) 0.016 ms/op
Iteration   1: 4.595 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.478 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.595 ms/op
                 getUser·p0.95:   6.169 ms/op
                 getUser·p0.99:   8.782 ms/op
                 getUser·p0.999:  14.820 ms/op
                 getUser·p0.9999: 26.281 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   2: 4.667 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   4.506 ms/op
                 getUser·p0.90:   5.865 ms/op
                 getUser·p0.95:   6.455 ms/op
                 getUser·p0.99:   8.929 ms/op
                 getUser·p0.999:  14.483 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 4.624 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   4.489 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.267 ms/op
                 getUser·p0.99:   8.270 ms/op
                 getUser·p0.999:  13.795 ms/op
                 getUser·p0.9999: 32.648 ms/op
                 getUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 207405
  mean =      4.628 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4258 
    [ 2.500,  5.000) = 150238 
    [ 5.000,  7.500) = 49145 
    [ 7.500, 10.000) = 2586 
    [10.000, 12.500) = 768 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      6.308 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     14.215 ms/op
     p(99.9900) =     29.205 ms/op
     p(99.9990) =     33.383 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.748 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 7.038 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.084 ±(99.9%) 0.025 ms/op
Iteration   1: 6.109 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   8.552 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   12.272 ms/op
                 listUser·p0.999:  20.543 ms/op
                 listUser·p0.9999: 24.904 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   2: 6.270 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   8.847 ms/op
                 listUser·p0.95:   9.830 ms/op
                 listUser·p0.99:   12.769 ms/op
                 listUser·p0.999:  19.395 ms/op
                 listUser·p0.9999: 25.264 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 6.227 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.509 ms/op
                 listUser·p0.50:   5.800 ms/op
                 listUser·p0.90:   8.552 ms/op
                 listUser·p0.95:   9.535 ms/op
                 listUser·p0.99:   12.075 ms/op
                 listUser·p0.999:  21.922 ms/op
                 listUser·p0.9999: 25.419 ms/op
                 listUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 154888
  mean =      6.201 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 143 
    [ 2.500,  5.000) = 37853 
    [ 5.000,  7.500) = 87483 
    [ 7.500, 10.000) = 23170 
    [10.000, 12.500) = 4811 
    [12.500, 15.000) = 843 
    [15.000, 17.500) = 250 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      5.759 ms/op
     p(90.0000) =      8.667 ms/op
     p(95.0000) =      9.683 ms/op
     p(99.0000) =     12.337 ms/op
     p(99.9000) =     20.884 ms/op
     p(99.9900) =     25.215 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.743 ± 0.705  ops/ms
ClientGrpc.existUser                       thrpt       3   7.395 ± 1.410  ops/ms
ClientGrpc.getUser                         thrpt       3   6.944 ± 0.102  ops/ms
ClientGrpc.listUser                        thrpt       3   5.455 ± 0.227  ops/ms
ClientGrpc.createUser                       avgt       3   4.761 ± 2.341   ms/op
ClientGrpc.existUser                        avgt       3   4.301 ± 1.607   ms/op
ClientGrpc.getUser                          avgt       3   4.649 ± 0.688   ms/op
ClientGrpc.listUser                         avgt       3   5.946 ± 2.479   ms/op
ClientGrpc.createUser                     sample  201733   4.758 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.061           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.931           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.463           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.978           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.279           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.443           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.719           ms/op
ClientGrpc.existUser                      sample  215511   4.452 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.011           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.489           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.005           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.363           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.384           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.100           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.017           ms/op
ClientGrpc.getUser                        sample  207405   4.628 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.478           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.718           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.308           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.684           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.215           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.205           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.489           ms/op
ClientGrpc.listUser                       sample  154888   6.201 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.405           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.667           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.683           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.337           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.884           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.215           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.984           ms/op
