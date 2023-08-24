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
# Warmup Iteration   1: 2.101 ops/ms
# Warmup Iteration   2: 5.117 ops/ms
# Warmup Iteration   3: 6.250 ops/ms
Iteration   1: 6.362 ops/ms
Iteration   2: 6.803 ops/ms
Iteration   3: 6.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.594 ±(99.9%) 4.034 ops/ms [Average]
  (min, avg, max) = (6.362, 6.594, 6.803), stdev = 0.221
  CI (99.9%): [2.560, 10.628] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.577 ops/ms
# Warmup Iteration   2: 6.608 ops/ms
# Warmup Iteration   3: 6.931 ops/ms
Iteration   1: 7.052 ops/ms
Iteration   2: 6.676 ops/ms
Iteration   3: 7.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.994 ±(99.9%) 5.350 ops/ms [Average]
  (min, avg, max) = (6.676, 6.994, 7.254), stdev = 0.293
  CI (99.9%): [1.644, 12.344] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.871 ops/ms
# Warmup Iteration   2: 5.975 ops/ms
# Warmup Iteration   3: 6.569 ops/ms
Iteration   1: 6.184 ops/ms
Iteration   2: 5.615 ops/ms
Iteration   3: 5.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.791 ±(99.9%) 6.222 ops/ms [Average]
  (min, avg, max) = (5.574, 5.791, 6.184), stdev = 0.341
  CI (99.9%): [≈ 0, 12.013] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.970 ops/ms
# Warmup Iteration   2: 4.450 ops/ms
# Warmup Iteration   3: 4.966 ops/ms
Iteration   1: 5.133 ops/ms
Iteration   2: 5.083 ops/ms
Iteration   3: 5.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.114 ±(99.9%) 0.495 ops/ms [Average]
  (min, avg, max) = (5.083, 5.114, 5.133), stdev = 0.027
  CI (99.9%): [4.618, 5.609] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.584 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.987 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.935 ±(99.9%) 0.009 ms/op
Iteration   1: 4.703 ±(99.9%) 0.005 ms/op
Iteration   2: 4.725 ±(99.9%) 0.005 ms/op
Iteration   3: 4.670 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.699 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (4.670, 4.699, 4.725), stdev = 0.028
  CI (99.9%): [4.195, 5.204] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.895 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.979 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.019 ms/op
Iteration   1: 4.482 ±(99.9%) 0.006 ms/op
Iteration   2: 4.418 ±(99.9%) 0.007 ms/op
Iteration   3: 4.479 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.460 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (4.418, 4.460, 4.482), stdev = 0.036
  CI (99.9%): [3.798, 5.121] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.774 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.433 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.924 ±(99.9%) 0.006 ms/op
Iteration   1: 4.678 ±(99.9%) 0.007 ms/op
Iteration   2: 4.785 ±(99.9%) 0.005 ms/op
Iteration   3: 4.921 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.795 ±(99.9%) 2.225 ms/op [Average]
  (min, avg, max) = (4.678, 4.795, 4.921), stdev = 0.122
  CI (99.9%): [2.570, 7.019] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.437 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 6.997 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.339 ±(99.9%) 0.022 ms/op
Iteration   1: 6.040 ±(99.9%) 0.016 ms/op
Iteration   2: 6.102 ±(99.9%) 0.019 ms/op
Iteration   3: 6.063 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.068 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (6.040, 6.068, 6.102), stdev = 0.031
  CI (99.9%): [5.498, 6.639] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 6.981 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.069 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.774 ±(99.9%) 0.017 ms/op
Iteration   1: 4.887 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   4.702 ms/op
                 createUser·p0.90:   6.242 ms/op
                 createUser·p0.95:   7.094 ms/op
                 createUser·p0.99:   9.404 ms/op
                 createUser·p0.999:  14.254 ms/op
                 createUser·p0.9999: 16.923 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   2: 4.853 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   4.661 ms/op
                 createUser·p0.90:   6.226 ms/op
                 createUser·p0.95:   6.922 ms/op
                 createUser·p0.99:   9.404 ms/op
                 createUser·p0.999:  13.764 ms/op
                 createUser·p0.9999: 23.928 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   3: 4.778 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   4.571 ms/op
                 createUser·p0.90:   6.201 ms/op
                 createUser·p0.95:   7.045 ms/op
                 createUser·p0.99:   9.765 ms/op
                 createUser·p0.999:  16.025 ms/op
                 createUser·p0.9999: 21.863 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 198353
  mean =      4.839 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3794 
    [ 2.500,  5.000) = 123324 
    [ 5.000,  7.500) = 64261 
    [ 7.500, 10.000) = 5497 
    [10.000, 12.500) = 986 
    [12.500, 15.000) = 322 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      7.012 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     21.845 ms/op
     p(99.9990) =     24.578 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.710 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.629 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.474 ±(99.9%) 0.014 ms/op
Iteration   1: 4.457 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   4.293 ms/op
                 existUser·p0.90:   5.661 ms/op
                 existUser·p0.95:   6.365 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  14.018 ms/op
                 existUser·p0.9999: 16.759 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 4.270 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   4.145 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   5.956 ms/op
                 existUser·p0.99:   7.995 ms/op
                 existUser·p0.999:  10.961 ms/op
                 existUser·p0.9999: 22.741 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 4.374 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.521 ms/op
                 existUser·p0.95:   6.144 ms/op
                 existUser·p0.99:   8.422 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 21.398 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 219933
  mean =      4.366 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7022 
    [ 2.500,  5.000) = 172286 
    [ 5.000,  7.500) = 36580 
    [ 7.500, 10.000) = 3286 
    [10.000, 12.500) = 540 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.155 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     12.471 ms/op
     p(99.9900) =     21.562 ms/op
     p(99.9990) =     23.062 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 7.435 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.982 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.790 ±(99.9%) 0.017 ms/op
Iteration   1: 4.668 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   4.497 ms/op
                 getUser·p0.90:   5.915 ms/op
                 getUser·p0.95:   6.619 ms/op
                 getUser·p0.99:   9.159 ms/op
                 getUser·p0.999:  15.671 ms/op
                 getUser·p0.9999: 29.730 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   2: 4.665 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   4.481 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   6.570 ms/op
                 getUser·p0.99:   8.953 ms/op
                 getUser·p0.999:  13.431 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   3: 4.739 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   4.563 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   6.570 ms/op
                 getUser·p0.99:   8.864 ms/op
                 getUser·p0.999:  12.084 ms/op
                 getUser·p0.9999: 21.823 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 204511
  mean =      4.690 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4418 
    [ 2.500,  5.000) = 139501 
    [ 5.000,  7.500) = 55467 
    [ 7.500, 10.000) = 4026 
    [10.000, 12.500) = 750 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      6.586 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     27.619 ms/op
     p(99.9990) =     29.819 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 8.898 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 6.805 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.301 ±(99.9%) 0.027 ms/op
Iteration   1: 6.471 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   8.847 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   12.862 ms/op
                 listUser·p0.999:  17.580 ms/op
                 listUser·p0.9999: 19.009 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 6.074 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.774 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   8.356 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   12.780 ms/op
                 listUser·p0.999:  28.803 ms/op
                 listUser·p0.9999: 30.114 ms/op
                 listUser·p1.00:   32.997 ms/op

Iteration   3: 6.355 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   8.405 ms/op
                 listUser·p0.95:   9.486 ms/op
                 listUser·p0.99:   12.567 ms/op
                 listUser·p0.999:  21.936 ms/op
                 listUser·p0.9999: 31.977 ms/op
                 listUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 152454
  mean =      6.296 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 113 
    [ 2.500,  5.000) = 28766 
    [ 5.000,  7.500) = 95993 
    [ 7.500, 10.000) = 21251 
    [10.000, 12.500) = 4575 
    [12.500, 15.000) = 1118 
    [15.000, 17.500) = 316 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      5.865 ms/op
     p(90.0000) =      8.536 ms/op
     p(95.0000) =      9.683 ms/op
     p(99.0000) =     12.747 ms/op
     p(99.9000) =     20.989 ms/op
     p(99.9900) =     30.302 ms/op
     p(99.9990) =     32.705 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.594 ± 4.034  ops/ms
ClientGrpc.existUser                       thrpt       3   6.994 ± 5.350  ops/ms
ClientGrpc.getUser                         thrpt       3   5.791 ± 6.222  ops/ms
ClientGrpc.listUser                        thrpt       3   5.114 ± 0.495  ops/ms
ClientGrpc.createUser                       avgt       3   4.699 ± 0.504   ms/op
ClientGrpc.existUser                        avgt       3   4.460 ± 0.661   ms/op
ClientGrpc.getUser                          avgt       3   4.795 ± 2.225   ms/op
ClientGrpc.listUser                         avgt       3   6.068 ± 0.571   ms/op
ClientGrpc.createUser                     sample  198353   4.839 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.163           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.226           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.012           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.519           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.254           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.845           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.674           ms/op
ClientGrpc.existUser                      sample  219933   4.366 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.791           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.513           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.155           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.454           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.471           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.562           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.134           ms/op
ClientGrpc.getUser                        sample  204511   4.690 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.100           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.931           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.586           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.995           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.139           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.619           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.884           ms/op
ClientGrpc.listUser                       sample  152454   6.296 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.268           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.536           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.683           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.747           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.989           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.302           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.997           ms/op
