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
# Warmup Iteration   1: 3.954 ops/ms
# Warmup Iteration   2: 9.102 ops/ms
# Warmup Iteration   3: 10.272 ops/ms
Iteration   1: 10.435 ops/ms
Iteration   2: 10.619 ops/ms
Iteration   3: 10.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.484 ±(99.9%) 2.159 ops/ms [Average]
  (min, avg, max) = (10.398, 10.484, 10.619), stdev = 0.118
  CI (99.9%): [8.325, 12.643] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.353 ops/ms
# Warmup Iteration   2: 10.432 ops/ms
# Warmup Iteration   3: 11.005 ops/ms
Iteration   1: 10.969 ops/ms
Iteration   2: 11.075 ops/ms
Iteration   3: 10.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.926 ±(99.9%) 3.176 ops/ms [Average]
  (min, avg, max) = (10.735, 10.926, 11.075), stdev = 0.174
  CI (99.9%): [7.751, 14.102] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.526 ops/ms
# Warmup Iteration   2: 9.900 ops/ms
# Warmup Iteration   3: 10.414 ops/ms
Iteration   1: 10.367 ops/ms
Iteration   2: 10.606 ops/ms
Iteration   3: 10.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.516 ±(99.9%) 2.367 ops/ms [Average]
  (min, avg, max) = (10.367, 10.516, 10.606), stdev = 0.130
  CI (99.9%): [8.150, 12.883] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.083 ops/ms
# Warmup Iteration   2: 7.573 ops/ms
# Warmup Iteration   3: 7.929 ops/ms
Iteration   1: 7.944 ops/ms
Iteration   2: 7.996 ops/ms
Iteration   3: 7.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.895 ±(99.9%) 2.421 ops/ms [Average]
  (min, avg, max) = (7.745, 7.895, 7.996), stdev = 0.133
  CI (99.9%): [5.474, 10.316] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.557 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.026 ms/op
Iteration   2: 3.003 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.065 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (3.003, 3.065, 3.100), stdev = 0.054
  CI (99.9%): [2.078, 4.053] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.623 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.002 ms/op
Iteration   1: 2.946 ±(99.9%) 0.003 ms/op
Iteration   2: 2.886 ±(99.9%) 0.003 ms/op
Iteration   3: 2.931 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.921 ±(99.9%) 0.565 ms/op [Average]
  (min, avg, max) = (2.886, 2.921, 2.946), stdev = 0.031
  CI (99.9%): [2.356, 3.486] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.004 ms/op
Iteration   1: 3.067 ±(99.9%) 0.004 ms/op
Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
Iteration   3: 3.036 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.048 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (3.036, 3.048, 3.067), stdev = 0.016
  CI (99.9%): [2.751, 3.346] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.861 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.030 ms/op
Iteration   1: 4.036 ±(99.9%) 0.035 ms/op
Iteration   2: 4.034 ±(99.9%) 0.006 ms/op
Iteration   3: 3.995 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.022 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (3.995, 4.022, 4.036), stdev = 0.023
  CI (99.9%): [3.603, 4.441] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.396 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.052 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  8.351 ms/op
                 createUser·p0.9999: 24.331 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 17.269 ms/op
                 createUser·p1.00:   18.874 ms/op

Iteration   3: 3.051 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.456 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.912 ms/op
                 createUser·p0.999:  11.277 ms/op
                 createUser·p0.9999: 26.723 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315270
  mean =      3.045 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21780 
    [ 2.500,  5.000) = 291113 
    [ 5.000,  7.500) = 1874 
    [ 7.500, 10.000) = 238 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     24.493 ms/op
     p(99.9990) =     26.898 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.005 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.005 ms/op
Iteration   1: 2.908 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  8.143 ms/op
                 existUser·p0.9999: 14.451 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  7.305 ms/op
                 existUser·p0.9999: 16.710 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   3: 2.939 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.744 ms/op
                 existUser·p0.9999: 18.685 ms/op
                 existUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330091
  mean =      2.907 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2587 
    [ 1.250,  2.500) = 37346 
    [ 2.500,  3.750) = 278914 
    [ 3.750,  5.000) = 9288 
    [ 5.000,  6.250) = 1051 
    [ 6.250,  7.500) = 499 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.370 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      7.774 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     19.074 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.427 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.096 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  9.341 ms/op
                 getUser·p0.9999: 22.883 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 22.325 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  9.557 ms/op
                 getUser·p0.9999: 20.598 ms/op
                 getUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309433
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14669 
    [ 2.500,  5.000) = 292424 
    [ 5.000,  7.500) = 1613 
    [ 7.500, 10.000) = 447 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     22.382 ms/op
     p(99.9990) =     23.407 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.955 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.011 ms/op
Iteration   1: 4.085 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  13.592 ms/op
                 listUser·p0.9999: 15.961 ms/op
                 listUser·p1.00:   16.253 ms/op

Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 4.088 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.208 ms/op
                 listUser·p0.999:  18.329 ms/op
                 listUser·p0.9999: 30.012 ms/op
                 listUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235250
  mean =      4.080 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2336 
    [ 2.500,  5.000) = 205366 
    [ 5.000,  7.500) = 25397 
    [ 7.500, 10.000) = 1595 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     16.724 ms/op
     p(99.9900) =     25.949 ms/op
     p(99.9990) =     30.353 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.484 ± 2.159  ops/ms
ClientGrpc.existUser                       thrpt       3  10.926 ± 3.176  ops/ms
ClientGrpc.getUser                         thrpt       3  10.516 ± 2.367  ops/ms
ClientGrpc.listUser                        thrpt       3   7.895 ± 2.421  ops/ms
ClientGrpc.createUser                       avgt       3   3.065 ± 0.988   ms/op
ClientGrpc.existUser                        avgt       3   2.921 ± 0.565   ms/op
ClientGrpc.getUser                          avgt       3   3.048 ± 0.297   ms/op
ClientGrpc.listUser                         avgt       3   4.022 ± 0.419   ms/op
ClientGrpc.createUser                     sample  315270   3.045 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.456           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.602           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.493           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.034           ms/op
ClientGrpc.existUser                      sample  330091   2.907 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.668           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.370           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.774           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.941           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.268           ms/op
ClientGrpc.getUser                        sample  309433   3.100 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.680           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.355           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.382           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.216           ms/op
ClientGrpc.listUser                       sample  235250   4.080 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.829           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.724           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.949           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.605           ms/op
