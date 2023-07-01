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
# Warmup Iteration   1: 4.832 ops/ms
# Warmup Iteration   2: 9.812 ops/ms
# Warmup Iteration   3: 10.269 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.829 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.732 ±(99.9%) 1.613 ops/ms [Average]
  (min, avg, max) = (10.655, 10.732, 10.829), stdev = 0.088
  CI (99.9%): [9.119, 12.345] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.777 ops/ms
# Warmup Iteration   2: 10.909 ops/ms
# Warmup Iteration   3: 11.047 ops/ms
Iteration   1: 11.191 ops/ms
Iteration   2: 11.222 ops/ms
Iteration   3: 11.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.192 ±(99.9%) 0.541 ops/ms [Average]
  (min, avg, max) = (11.163, 11.192, 11.222), stdev = 0.030
  CI (99.9%): [10.650, 11.733] (assumes normal distribution)


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
# Warmup Iteration   1: 7.147 ops/ms
# Warmup Iteration   2: 10.263 ops/ms
# Warmup Iteration   3: 10.908 ops/ms
Iteration   1: 10.730 ops/ms
Iteration   2: 10.760 ops/ms
Iteration   3: 10.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.743 ±(99.9%) 0.281 ops/ms [Average]
  (min, avg, max) = (10.730, 10.743, 10.760), stdev = 0.015
  CI (99.9%): [10.462, 11.024] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.229 ops/ms
# Warmup Iteration   2: 7.951 ops/ms
# Warmup Iteration   3: 8.246 ops/ms
Iteration   1: 8.344 ops/ms
Iteration   2: 8.446 ops/ms
Iteration   3: 8.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.389 ±(99.9%) 0.949 ops/ms [Average]
  (min, avg, max) = (8.344, 8.389, 8.446), stdev = 0.052
  CI (99.9%): [7.440, 9.338] (assumes normal distribution)


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.002 ms/op
Iteration   3: 3.071 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.027 ±(99.9%) 0.822 ms/op [Average]
  (min, avg, max) = (2.981, 3.027, 3.071), stdev = 0.045
  CI (99.9%): [2.205, 3.849] (assumes normal distribution)


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
# Warmup Iteration   1: 3.695 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.888 ±(99.9%) 0.003 ms/op
Iteration   1: 2.909 ±(99.9%) 0.003 ms/op
Iteration   2: 2.876 ±(99.9%) 0.003 ms/op
Iteration   3: 2.880 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.888 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.876, 2.888, 2.909), stdev = 0.018
  CI (99.9%): [2.565, 3.212] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.120 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.002 ms/op
Iteration   1: 2.997 ±(99.9%) 0.002 ms/op
Iteration   2: 3.004 ±(99.9%) 0.003 ms/op
Iteration   3: 2.960 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.987 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (2.960, 2.987, 3.004), stdev = 0.024
  CI (99.9%): [2.551, 3.423] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.769 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.032 ms/op
Iteration   1: 3.870 ±(99.9%) 0.013 ms/op
Iteration   2: 3.886 ±(99.9%) 0.012 ms/op
Iteration   3: 3.867 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.874 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (3.867, 3.874, 3.886), stdev = 0.011
  CI (99.9%): [3.681, 4.068] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  11.600 ms/op
                 createUser·p0.9999: 23.470 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  8.041 ms/op
                 createUser·p0.9999: 19.235 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   3: 2.980 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.250 ms/op
                 createUser·p0.9999: 23.700 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319927
  mean =      2.999 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27382 
    [ 2.500,  5.000) = 290657 
    [ 5.000,  7.500) = 1483 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.217 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 3.702 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.903 ±(99.9%) 0.005 ms/op
Iteration   1: 2.876 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.867 ms/op
                 existUser·p0.9999: 12.479 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   2: 2.897 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.087 ms/op
                 existUser·p0.9999: 11.927 ms/op
                 existUser·p1.00:   12.108 ms/op

Iteration   3: 2.884 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.570 ms/op
                 existUser·p0.9999: 15.183 ms/op
                 existUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332634
  mean =      2.886 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1640 
    [ 1.250,  2.500) = 38795 
    [ 2.500,  3.750) = 281987 
    [ 3.750,  5.000) = 9213 
    [ 5.000,  6.250) = 558 
    [ 6.250,  7.500) = 175 
    [ 7.500,  8.750) = 96 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.854 ms/op
     p(99.9900) =     14.811 ms/op
     p(99.9990) =     15.576 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.619 ms/op
                 getUser·p0.9999: 14.675 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.438 ms/op
                 getUser·p0.9999: 23.036 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   3: 2.987 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  5.890 ms/op
                 getUser·p0.9999: 25.208 ms/op
                 getUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318592
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23095 
    [ 2.500,  5.000) = 294166 
    [ 5.000,  7.500) = 1051 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.225 ms/op
     p(99.9900) =     24.300 ms/op
     p(99.9990) =     25.514 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.010 ms/op
Iteration   1: 3.844 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  12.531 ms/op
                 listUser·p0.9999: 13.550 ms/op
                 listUser·p1.00:   15.827 ms/op

Iteration   2: 3.878 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.470 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 3.816 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  13.879 ms/op
                 listUser·p0.9999: 22.577 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249686
  mean =      3.846 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3388 
    [ 2.500,  5.000) = 229054 
    [ 5.000,  7.500) = 16145 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     21.530 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.732 ± 1.613  ops/ms
ClientGrpc.existUser                       thrpt       3  11.192 ± 0.541  ops/ms
ClientGrpc.getUser                         thrpt       3  10.743 ± 0.281  ops/ms
ClientGrpc.listUser                        thrpt       3   8.389 ± 0.949  ops/ms
ClientGrpc.createUser                       avgt       3   3.027 ± 0.822   ms/op
ClientGrpc.existUser                        avgt       3   2.888 ± 0.324   ms/op
ClientGrpc.getUser                          avgt       3   2.987 ± 0.436   ms/op
ClientGrpc.listUser                         avgt       3   3.874 ± 0.193   ms/op
ClientGrpc.createUser                     sample  319927   2.999 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.653           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.217           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.462           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.214           ms/op
ClientGrpc.existUser                      sample  332634   2.886 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.536           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.854           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.811           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.892           ms/op
ClientGrpc.getUser                        sample  318592   3.014 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.636           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.225           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.300           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.592           ms/op
ClientGrpc.listUser                       sample  249686   3.846 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.470           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.627           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.255           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.530           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.708           ms/op
