# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.912 ops/ms
# Warmup Iteration   2: 4.846 ops/ms
# Warmup Iteration   3: 6.267 ops/ms
Iteration   1: 6.650 ops/ms
Iteration   2: 6.856 ops/ms
Iteration   3: 6.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.786 ±(99.9%) 2.146 ops/ms [Average]
  (min, avg, max) = (6.650, 6.786, 6.856), stdev = 0.118
  CI (99.9%): [4.639, 8.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ops/ms
# Warmup Iteration   2: 6.436 ops/ms
# Warmup Iteration   3: 7.320 ops/ms
Iteration   1: 7.295 ops/ms
Iteration   2: 7.254 ops/ms
Iteration   3: 7.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.317 ±(99.9%) 1.401 ops/ms [Average]
  (min, avg, max) = (7.254, 7.317, 7.403), stdev = 0.077
  CI (99.9%): [5.916, 8.719] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.794 ops/ms
# Warmup Iteration   2: 6.175 ops/ms
# Warmup Iteration   3: 6.693 ops/ms
Iteration   1: 6.905 ops/ms
Iteration   2: 7.078 ops/ms
Iteration   3: 6.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.960 ±(99.9%) 1.859 ops/ms [Average]
  (min, avg, max) = (6.898, 6.960, 7.078), stdev = 0.102
  CI (99.9%): [5.101, 8.819] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.161 ops/ms
# Warmup Iteration   2: 4.873 ops/ms
# Warmup Iteration   3: 5.087 ops/ms
Iteration   1: 4.854 ops/ms
Iteration   2: 5.116 ops/ms
Iteration   3: 4.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.990 ±(99.9%) 2.401 ops/ms [Average]
  (min, avg, max) = (4.854, 4.990, 5.116), stdev = 0.132
  CI (99.9%): [2.589, 7.391] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.652 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.038 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.670 ±(99.9%) 0.007 ms/op
Iteration   1: 4.632 ±(99.9%) 0.007 ms/op
Iteration   2: 4.684 ±(99.9%) 0.006 ms/op
Iteration   3: 4.487 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.601 ±(99.9%) 1.863 ms/op [Average]
  (min, avg, max) = (4.487, 4.601, 4.684), stdev = 0.102
  CI (99.9%): [2.738, 6.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.756 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.539 ±(99.9%) 0.013 ms/op
Iteration   1: 4.427 ±(99.9%) 0.005 ms/op
Iteration   2: 4.537 ±(99.9%) 0.006 ms/op
Iteration   3: 4.506 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.490 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (4.427, 4.490, 4.537), stdev = 0.057
  CI (99.9%): [3.453, 5.527] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.085 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.099 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.736 ±(99.9%) 0.015 ms/op
Iteration   1: 4.596 ±(99.9%) 0.004 ms/op
Iteration   2: 4.467 ±(99.9%) 0.010 ms/op
Iteration   3: 4.544 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.535 ±(99.9%) 1.183 ms/op [Average]
  (min, avg, max) = (4.467, 4.535, 4.596), stdev = 0.065
  CI (99.9%): [3.353, 5.718] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.255 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 6.675 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.017 ±(99.9%) 0.013 ms/op
Iteration   1: 5.875 ±(99.9%) 0.016 ms/op
Iteration   2: 6.174 ±(99.9%) 0.021 ms/op
Iteration   3: 6.271 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.107 ±(99.9%) 3.764 ms/op [Average]
  (min, avg, max) = (5.875, 6.107, 6.271), stdev = 0.206
  CI (99.9%): [2.342, 9.871] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.934 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.308 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.785 ±(99.9%) 0.018 ms/op
Iteration   1: 4.727 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   6.005 ms/op
                 createUser·p0.95:   6.857 ms/op
                 createUser·p0.99:   9.954 ms/op
                 createUser·p0.999:  19.268 ms/op
                 createUser·p0.9999: 20.536 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   2: 4.766 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   4.571 ms/op
                 createUser·p0.90:   6.152 ms/op
                 createUser·p0.95:   6.791 ms/op
                 createUser·p0.99:   9.292 ms/op
                 createUser·p0.999:  14.573 ms/op
                 createUser·p0.9999: 18.533 ms/op
                 createUser·p1.00:   19.137 ms/op

Iteration   3: 4.613 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   4.440 ms/op
                 createUser·p0.90:   5.898 ms/op
                 createUser·p0.95:   6.488 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  15.647 ms/op
                 createUser·p0.9999: 23.760 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 204218
  mean =      4.701 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3774 
    [ 2.500,  5.000) = 138868 
    [ 5.000,  7.500) = 55788 
    [ 7.500, 10.000) = 4340 
    [10.000, 12.500) = 906 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     23.055 ms/op
     p(99.9990) =     24.146 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.582 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.419 ±(99.9%) 0.016 ms/op
Iteration   1: 4.435 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.636 ms/op
                 existUser·p0.95:   6.504 ms/op
                 existUser·p0.99:   9.224 ms/op
                 existUser·p0.999:  16.776 ms/op
                 existUser·p0.9999: 25.192 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   2: 4.466 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.784 ms/op
                 existUser·p0.95:   6.504 ms/op
                 existUser·p0.99:   9.322 ms/op
                 existUser·p0.999:  14.828 ms/op
                 existUser·p0.9999: 21.889 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 4.333 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   4.162 ms/op
                 existUser·p0.90:   5.489 ms/op
                 existUser·p0.95:   6.201 ms/op
                 existUser·p0.99:   8.585 ms/op
                 existUser·p0.999:  14.408 ms/op
                 existUser·p0.9999: 23.444 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 217564
  mean =      4.411 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5240 
    [ 2.500,  5.000) = 169617 
    [ 5.000,  7.500) = 37113 
    [ 7.500, 10.000) = 4352 
    [10.000, 12.500) = 792 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.406 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     15.219 ms/op
     p(99.9900) =     22.993 ms/op
     p(99.9990) =     25.324 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.898 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.326 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.882 ±(99.9%) 0.020 ms/op
Iteration   1: 4.605 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.997 ms/op
                 getUser·p0.95:   6.881 ms/op
                 getUser·p0.99:   9.748 ms/op
                 getUser·p0.999:  14.438 ms/op
                 getUser·p0.9999: 18.481 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   2: 4.841 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   4.604 ms/op
                 getUser·p0.90:   6.300 ms/op
                 getUser·p0.95:   7.283 ms/op
                 getUser·p0.99:   10.174 ms/op
                 getUser·p0.999:  15.545 ms/op
                 getUser·p0.9999: 24.392 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   3: 4.634 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   6.013 ms/op
                 getUser·p0.95:   6.898 ms/op
                 getUser·p0.99:   9.516 ms/op
                 getUser·p0.999:  17.399 ms/op
                 getUser·p0.9999: 25.529 ms/op
                 getUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 204496
  mean =      4.691 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6816 
    [ 2.500,  5.000) = 136955 
    [ 5.000,  7.500) = 53033 
    [ 7.500, 10.000) = 5875 
    [10.000, 12.500) = 1300 
    [12.500, 15.000) = 315 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     25.851 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.153 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 7.020 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.147 ±(99.9%) 0.029 ms/op
Iteration   1: 6.188 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   8.798 ms/op
                 listUser·p0.95:   10.043 ms/op
                 listUser·p0.99:   13.194 ms/op
                 listUser·p0.999:  18.262 ms/op
                 listUser·p0.9999: 24.221 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   2: 6.259 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   8.831 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   12.730 ms/op
                 listUser·p0.999:  22.901 ms/op
                 listUser·p0.9999: 30.310 ms/op
                 listUser·p1.00:   31.719 ms/op

Iteration   3: 6.229 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   9.830 ms/op
                 listUser·p0.99:   12.567 ms/op
                 listUser·p0.999:  27.605 ms/op
                 listUser·p0.9999: 33.601 ms/op
                 listUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 154244
  mean =      6.225 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190 
    [ 2.500,  5.000) = 39539 
    [ 5.000,  7.500) = 84612 
    [ 7.500, 10.000) = 22238 
    [10.000, 12.500) = 5765 
    [12.500, 15.000) = 1241 
    [15.000, 17.500) = 318 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      5.726 ms/op
     p(90.0000) =      8.749 ms/op
     p(95.0000) =      9.994 ms/op
     p(99.0000) =     12.845 ms/op
     p(99.9000) =     21.726 ms/op
     p(99.9900) =     32.212 ms/op
     p(99.9990) =     34.073 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.786 ± 2.146  ops/ms
ClientGrpc.existUser                       thrpt       3   7.317 ± 1.401  ops/ms
ClientGrpc.getUser                         thrpt       3   6.960 ± 1.859  ops/ms
ClientGrpc.listUser                        thrpt       3   4.990 ± 2.401  ops/ms
ClientGrpc.createUser                       avgt       3   4.601 ± 1.863   ms/op
ClientGrpc.existUser                        avgt       3   4.490 ± 1.037   ms/op
ClientGrpc.getUser                          avgt       3   4.535 ± 1.183   ms/op
ClientGrpc.listUser                         avgt       3   6.107 ± 3.764   ms/op
ClientGrpc.createUser                     sample  204218   4.701 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.600           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.021           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.693           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.322           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.499           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.055           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.248           ms/op
ClientGrpc.existUser                      sample  217564   4.411 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.909           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.636           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.406           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.044           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.219           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.993           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.362           ms/op
ClientGrpc.getUser                        sample  204496   4.691 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.911           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.103           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.021           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.798           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.942           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.478           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.378           ms/op
ClientGrpc.listUser                       sample  154244   6.225 ± 0.017   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.829           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.749           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.994           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.845           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.726           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.212           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.144           ms/op
