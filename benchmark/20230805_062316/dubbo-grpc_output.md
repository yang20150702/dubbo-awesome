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
# Warmup Iteration   1: 2.813 ops/ms
# Warmup Iteration   2: 6.686 ops/ms
# Warmup Iteration   3: 8.157 ops/ms
Iteration   1: 8.449 ops/ms
Iteration   2: 8.612 ops/ms
Iteration   3: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.547 ±(99.9%) 1.577 ops/ms [Average]
  (min, avg, max) = (8.449, 8.547, 8.612), stdev = 0.086
  CI (99.9%): [6.970, 10.124] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.673 ops/ms
# Warmup Iteration   2: 8.464 ops/ms
# Warmup Iteration   3: 8.776 ops/ms
Iteration   1: 9.015 ops/ms
Iteration   2: 8.973 ops/ms
Iteration   3: 9.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.129 ±(99.9%) 4.267 ops/ms [Average]
  (min, avg, max) = (8.973, 9.129, 9.398), stdev = 0.234
  CI (99.9%): [4.861, 13.396] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.870 ops/ms
# Warmup Iteration   2: 8.334 ops/ms
# Warmup Iteration   3: 8.615 ops/ms
Iteration   1: 8.690 ops/ms
Iteration   2: 8.654 ops/ms
Iteration   3: 8.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.693 ±(99.9%) 0.743 ops/ms [Average]
  (min, avg, max) = (8.654, 8.693, 8.735), stdev = 0.041
  CI (99.9%): [7.949, 9.436] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.075 ops/ms
# Warmup Iteration   2: 6.260 ops/ms
# Warmup Iteration   3: 6.550 ops/ms
Iteration   1: 6.708 ops/ms
Iteration   2: 6.781 ops/ms
Iteration   3: 6.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.720 ±(99.9%) 1.019 ops/ms [Average]
  (min, avg, max) = (6.671, 6.720, 6.781), stdev = 0.056
  CI (99.9%): [5.701, 7.739] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.238 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.954 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.719 ±(99.9%) 0.006 ms/op
Iteration   1: 3.783 ±(99.9%) 0.004 ms/op
Iteration   2: 3.650 ±(99.9%) 0.003 ms/op
Iteration   3: 3.589 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.674 ±(99.9%) 1.810 ms/op [Average]
  (min, avg, max) = (3.589, 3.674, 3.783), stdev = 0.099
  CI (99.9%): [1.864, 5.484] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.907 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.004 ms/op
Iteration   1: 3.486 ±(99.9%) 0.004 ms/op
Iteration   2: 3.302 ±(99.9%) 0.004 ms/op
Iteration   3: 3.473 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.420 ±(99.9%) 1.872 ms/op [Average]
  (min, avg, max) = (3.302, 3.420, 3.486), stdev = 0.103
  CI (99.9%): [1.548, 5.292] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.225 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.004 ms/op
Iteration   1: 3.707 ±(99.9%) 0.004 ms/op
Iteration   2: 3.626 ±(99.9%) 0.004 ms/op
Iteration   3: 3.619 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.651 ±(99.9%) 0.886 ms/op [Average]
  (min, avg, max) = (3.619, 3.651, 3.707), stdev = 0.049
  CI (99.9%): [2.765, 4.537] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.910 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 5.454 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.927 ±(99.9%) 0.016 ms/op
Iteration   1: 4.757 ±(99.9%) 0.014 ms/op
Iteration   2: 4.599 ±(99.9%) 0.008 ms/op
Iteration   3: 4.733 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.696 ±(99.9%) 1.560 ms/op [Average]
  (min, avg, max) = (4.599, 4.696, 4.757), stdev = 0.085
  CI (99.9%): [3.137, 6.256] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.051 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.709 ±(99.9%) 0.010 ms/op
Iteration   1: 3.614 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.559 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  12.377 ms/op
                 createUser·p0.9999: 18.790 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   2: 3.639 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  12.517 ms/op
                 createUser·p0.9999: 20.232 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   3: 3.533 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  9.809 ms/op
                 createUser·p0.9999: 23.495 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 267140
  mean =      3.595 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7901 
    [ 2.500,  5.000) = 253093 
    [ 5.000,  7.500) = 5233 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     12.105 ms/op
     p(99.9900) =     22.596 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.919 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.007 ms/op
Iteration   1: 3.351 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  11.282 ms/op
                 existUser·p0.9999: 21.135 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   2: 3.277 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  7.861 ms/op
                 existUser·p0.9999: 15.917 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  11.090 ms/op
                 existUser·p0.9999: 21.439 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 291723
  mean =      3.289 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13569 
    [ 2.500,  5.000) = 274970 
    [ 5.000,  7.500) = 2508 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.069 ms/op
     p(99.9000) =     10.507 ms/op
     p(99.9900) =     21.064 ms/op
     p(99.9990) =     21.829 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.053 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.009 ms/op
Iteration   1: 3.491 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  9.816 ms/op
                 getUser·p0.9999: 13.894 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 3.511 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  10.384 ms/op
                 getUser·p0.9999: 16.071 ms/op
                 getUser·p1.00:   16.466 ms/op

Iteration   3: 3.792 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  11.419 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267204
  mean =      3.593 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9637 
    [ 2.500,  5.000) = 249795 
    [ 5.000,  7.500) = 6949 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     10.420 ms/op
     p(99.9900) =     18.261 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 6.409 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.196 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.892 ±(99.9%) 0.014 ms/op
Iteration   1: 4.817 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 25.026 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   2: 4.773 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.567 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.726 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  15.956 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   3: 4.815 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.425 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.947 ms/op
                 listUser·p0.95:   6.898 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  19.366 ms/op
                 listUser·p0.9999: 23.572 ms/op
                 listUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199914
  mean =      4.801 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 374 
    [ 2.500,  5.000) = 149102 
    [ 5.000,  7.500) = 44870 
    [ 7.500, 10.000) = 4738 
    [10.000, 12.500) = 424 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.816 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     17.635 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.547 ± 1.577  ops/ms
ClientGrpc.existUser                       thrpt       3   9.129 ± 4.267  ops/ms
ClientGrpc.getUser                         thrpt       3   8.693 ± 0.743  ops/ms
ClientGrpc.listUser                        thrpt       3   6.720 ± 1.019  ops/ms
ClientGrpc.createUser                       avgt       3   3.674 ± 1.810   ms/op
ClientGrpc.existUser                        avgt       3   3.420 ± 1.872   ms/op
ClientGrpc.getUser                          avgt       3   3.651 ± 0.886   ms/op
ClientGrpc.listUser                         avgt       3   4.696 ± 1.560   ms/op
ClientGrpc.createUser                     sample  267140   3.595 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.672           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.105           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.596           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.527           ms/op
ClientGrpc.existUser                      sample  291723   3.289 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.632           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.269           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.069           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.507           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.064           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.955           ms/op
ClientGrpc.getUser                        sample  267204   3.593 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.535           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.420           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.261           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.938           ms/op
ClientGrpc.listUser                       sample  199914   4.801 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.425           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.635           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.345           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.886           ms/op
