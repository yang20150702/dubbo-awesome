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
# Warmup Iteration   1: 4.451 ops/ms
# Warmup Iteration   2: 8.892 ops/ms
# Warmup Iteration   3: 10.301 ops/ms
Iteration   1: 10.432 ops/ms
Iteration   2: 10.554 ops/ms
Iteration   3: 10.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.550 ±(99.9%) 2.101 ops/ms [Average]
  (min, avg, max) = (10.432, 10.550, 10.663), stdev = 0.115
  CI (99.9%): [8.448, 12.651] (assumes normal distribution)


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
# Warmup Iteration   1: 7.787 ops/ms
# Warmup Iteration   2: 10.719 ops/ms
# Warmup Iteration   3: 11.131 ops/ms
Iteration   1: 11.021 ops/ms
Iteration   2: 11.211 ops/ms
Iteration   3: 11.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.167 ±(99.9%) 2.367 ops/ms [Average]
  (min, avg, max) = (11.021, 11.167, 11.270), stdev = 0.130
  CI (99.9%): [8.800, 13.535] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.936 ops/ms
# Warmup Iteration   2: 10.196 ops/ms
# Warmup Iteration   3: 10.598 ops/ms
Iteration   1: 10.690 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.668 ±(99.9%) 0.358 ops/ms [Average]
  (min, avg, max) = (10.651, 10.668, 10.690), stdev = 0.020
  CI (99.9%): [10.310, 11.026] (assumes normal distribution)


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
# Warmup Iteration   1: 5.866 ops/ms
# Warmup Iteration   2: 7.836 ops/ms
# Warmup Iteration   3: 8.130 ops/ms
Iteration   1: 8.414 ops/ms
Iteration   2: 8.222 ops/ms
Iteration   3: 8.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.293 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (8.222, 8.293, 8.414), stdev = 0.105
  CI (99.9%): [6.381, 10.206] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.002 ms/op
Iteration   1: 2.954 ±(99.9%) 0.003 ms/op
Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
Iteration   3: 2.971 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.967 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (2.954, 2.967, 2.975), stdev = 0.011
  CI (99.9%): [2.763, 3.171] (assumes normal distribution)


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.920 ±(99.9%) 0.005 ms/op
Iteration   1: 2.992 ±(99.9%) 0.002 ms/op
Iteration   2: 2.932 ±(99.9%) 0.003 ms/op
Iteration   3: 2.913 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.946 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (2.913, 2.946, 2.992), stdev = 0.041
  CI (99.9%): [2.191, 3.701] (assumes normal distribution)


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.003 ms/op
Iteration   1: 3.012 ±(99.9%) 0.001 ms/op
Iteration   2: 3.031 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.028 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.012, 3.028, 3.041), stdev = 0.015
  CI (99.9%): [2.760, 3.297] (assumes normal distribution)


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
# Warmup Iteration   1: 5.285 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.021 ms/op
Iteration   1: 3.894 ±(99.9%) 0.025 ms/op
Iteration   2: 3.913 ±(99.9%) 0.014 ms/op
Iteration   3: 3.871 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.893 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (3.871, 3.893, 3.913), stdev = 0.021
  CI (99.9%): [3.512, 4.273] (assumes normal distribution)


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.864 ms/op
                 createUser·p0.9999: 11.686 ms/op
                 createUser·p1.00:   12.009 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.200 ms/op
                 createUser·p0.9999: 12.714 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   3: 3.008 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  10.843 ms/op
                 createUser·p0.9999: 34.865 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319847
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26855 
    [ 2.500,  5.000) = 291763 
    [ 5.000,  7.500) = 807 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.770 ms/op
     p(99.9900) =     34.407 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 2.890 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.372 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  6.122 ms/op
                 existUser·p0.9999: 15.397 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   2: 2.924 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  5.673 ms/op
                 existUser·p0.9999: 13.191 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.952 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.469 ms/op
                 existUser·p0.9999: 18.978 ms/op
                 existUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328462
  mean =      2.922 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3676 
    [ 1.250,  2.500) = 41711 
    [ 2.500,  3.750) = 265271 
    [ 3.750,  5.000) = 16777 
    [ 5.000,  6.250) = 747 
    [ 6.250,  7.500) = 115 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      6.070 ms/op
     p(99.9900) =     16.322 ms/op
     p(99.9990) =     19.314 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.365 ms/op
                 getUser·p0.9999: 13.472 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.094 ms/op
                 getUser·p0.9999: 14.844 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   3: 3.032 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.572 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  7.381 ms/op
                 getUser·p0.9999: 16.047 ms/op
                 getUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319987
  mean =      3.000 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1420 
    [ 1.250,  2.500) = 20529 
    [ 2.500,  3.750) = 285094 
    [ 3.750,  5.000) = 11793 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 287 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.225 ms/op
     p(99.9900) =     15.204 ms/op
     p(99.9990) =     16.358 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 4.510 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.012 ms/op
Iteration   1: 3.894 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.272 ms/op
                 listUser·p0.9999: 16.518 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   2: 3.924 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.017 ms/op
                 listUser·p0.9999: 23.462 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   3: 3.902 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 29.511 ms/op
                 listUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245657
  mean =      3.907 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4613 
    [ 2.500,  5.000) = 219981 
    [ 5.000,  7.500) = 19987 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.473 ms/op
     p(99.9900) =     26.477 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.550 ± 2.101  ops/ms
ClientGrpc.existUser                       thrpt       3  11.167 ± 2.367  ops/ms
ClientGrpc.getUser                         thrpt       3  10.668 ± 0.358  ops/ms
ClientGrpc.listUser                        thrpt       3   8.293 ± 1.912  ops/ms
ClientGrpc.createUser                       avgt       3   2.967 ± 0.204   ms/op
ClientGrpc.existUser                        avgt       3   2.946 ± 0.755   ms/op
ClientGrpc.getUser                          avgt       3   3.028 ± 0.269   ms/op
ClientGrpc.listUser                         avgt       3   3.893 ± 0.380   ms/op
ClientGrpc.createUser                     sample  319847   3.001 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.541           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.770           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.407           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.193           ms/op
ClientGrpc.existUser                      sample  328462   2.922 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.372           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.070           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.322           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.464           ms/op
ClientGrpc.getUser                        sample  319987   3.000 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.572           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.225           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.204           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.450           ms/op
ClientGrpc.listUser                       sample  245657   3.907 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.982           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.473           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.477           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.786           ms/op
