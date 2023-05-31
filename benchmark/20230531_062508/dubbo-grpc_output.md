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
# Warmup Iteration   1: 4.133 ops/ms
# Warmup Iteration   2: 9.031 ops/ms
# Warmup Iteration   3: 10.375 ops/ms
Iteration   1: 10.555 ops/ms
Iteration   2: 10.800 ops/ms
Iteration   3: 10.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.749 ±(99.9%) 3.188 ops/ms [Average]
  (min, avg, max) = (10.555, 10.749, 10.893), stdev = 0.175
  CI (99.9%): [7.561, 13.937] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.287 ops/ms
# Warmup Iteration   2: 10.723 ops/ms
# Warmup Iteration   3: 11.171 ops/ms
Iteration   1: 11.358 ops/ms
Iteration   2: 11.251 ops/ms
Iteration   3: 11.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.317 ±(99.9%) 1.055 ops/ms [Average]
  (min, avg, max) = (11.251, 11.317, 11.358), stdev = 0.058
  CI (99.9%): [10.262, 12.372] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.922 ops/ms
# Warmup Iteration   2: 10.276 ops/ms
# Warmup Iteration   3: 10.737 ops/ms
Iteration   1: 10.628 ops/ms
Iteration   2: 10.624 ops/ms
Iteration   3: 10.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.654 ±(99.9%) 0.885 ops/ms [Average]
  (min, avg, max) = (10.624, 10.654, 10.710), stdev = 0.048
  CI (99.9%): [9.769, 11.539] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.510 ops/ms
# Warmup Iteration   2: 8.118 ops/ms
# Warmup Iteration   3: 8.203 ops/ms
Iteration   1: 8.286 ops/ms
Iteration   2: 8.321 ops/ms
Iteration   3: 8.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.300 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (8.286, 8.300, 8.321), stdev = 0.019
  CI (99.9%): [7.959, 8.640] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.329 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.003 ms/op
Iteration   1: 2.939 ±(99.9%) 0.003 ms/op
Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
Iteration   3: 3.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.002 ±(99.9%) 1.103 ms/op [Average]
  (min, avg, max) = (2.939, 3.002, 3.059), stdev = 0.060
  CI (99.9%): [1.899, 4.105] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.750 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.876 ±(99.9%) 0.003 ms/op
Iteration   1: 2.900 ±(99.9%) 0.002 ms/op
Iteration   2: 2.966 ±(99.9%) 0.002 ms/op
Iteration   3: 2.966 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.944 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (2.900, 2.944, 2.966), stdev = 0.038
  CI (99.9%): [2.247, 3.641] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.297 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 3.024 ±(99.9%) 0.004 ms/op
Iteration   2: 2.990 ±(99.9%) 0.004 ms/op
Iteration   3: 3.081 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.032 ±(99.9%) 0.834 ms/op [Average]
  (min, avg, max) = (2.990, 3.032, 3.081), stdev = 0.046
  CI (99.9%): [2.198, 3.866] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.922 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.021 ms/op
Iteration   1: 3.898 ±(99.9%) 0.057 ms/op
Iteration   2: 3.828 ±(99.9%) 0.017 ms/op
Iteration   3: 3.887 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.871 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (3.828, 3.871, 3.898), stdev = 0.038
  CI (99.9%): [3.177, 4.565] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.336 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.008 ms/op
Iteration   1: 2.992 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  6.979 ms/op
                 createUser·p0.9999: 16.302 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 2.970 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.529 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.510 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.407 ms/op
                 createUser·p0.9999: 28.162 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  11.216 ms/op
                 createUser·p0.9999: 21.561 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321582
  mean =      2.988 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27105 
    [ 2.500,  5.000) = 292619 
    [ 5.000,  7.500) = 1427 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     26.879 ms/op
     p(99.9990) =     28.527 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.875 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.006 ms/op
Iteration   1: 2.911 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  6.848 ms/op
                 existUser·p0.9999: 14.582 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.283 ms/op
                 existUser·p0.9999: 13.958 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   3: 2.800 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.916 ms/op
                 existUser·p0.9999: 17.830 ms/op
                 existUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335147
  mean =      2.866 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2182 
    [ 1.250,  2.500) = 45024 
    [ 2.500,  3.750) = 279444 
    [ 3.750,  5.000) = 7601 
    [ 5.000,  6.250) = 485 
    [ 6.250,  7.500) = 183 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      6.470 ms/op
     p(99.9900) =     16.048 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.117 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.005 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.844 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  7.230 ms/op
                 getUser·p0.9999: 13.840 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   2: 2.958 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.569 ms/op
                 getUser·p0.9999: 13.801 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.382 ms/op
                 getUser·p0.9999: 16.179 ms/op
                 getUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323527
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 735 
    [ 1.250,  2.500) = 33992 
    [ 2.500,  3.750) = 273099 
    [ 3.750,  5.000) = 14364 
    [ 5.000,  6.250) = 791 
    [ 6.250,  7.500) = 273 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.201 ms/op
     p(99.9900) =     14.414 ms/op
     p(99.9990) =     16.582 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 4.802 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.011 ms/op
Iteration   1: 3.825 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.718 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.411 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   2: 3.798 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 24.547 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   3: 3.881 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.657 ms/op
                 listUser·p0.9999: 20.857 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250370
  mean =      3.834 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3589 
    [ 2.500,  5.000) = 226128 
    [ 5.000,  7.500) = 19587 
    [ 7.500, 10.000) = 610 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.744 ms/op
     p(99.9000) =     15.493 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.749 ± 3.188  ops/ms
ClientGrpc.existUser                       thrpt       3  11.317 ± 1.055  ops/ms
ClientGrpc.getUser                         thrpt       3  10.654 ± 0.885  ops/ms
ClientGrpc.listUser                        thrpt       3   8.300 ± 0.340  ops/ms
ClientGrpc.createUser                       avgt       3   3.002 ± 1.103   ms/op
ClientGrpc.existUser                        avgt       3   2.944 ± 0.697   ms/op
ClientGrpc.getUser                          avgt       3   3.032 ± 0.834   ms/op
ClientGrpc.listUser                         avgt       3   3.871 ± 0.694   ms/op
ClientGrpc.createUser                     sample  321582   2.988 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.529           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.428           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.503           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.879           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.639           ms/op
ClientGrpc.existUser                      sample  335147   2.866 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.703           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.470           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.048           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.219           ms/op
ClientGrpc.getUser                        sample  323527   2.967 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.643           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.201           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.414           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.663           ms/op
ClientGrpc.listUser                       sample  250370   3.834 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.116           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.670           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.744           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.493           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.101           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.936           ms/op
