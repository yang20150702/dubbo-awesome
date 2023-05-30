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
# Warmup Iteration   1: 4.368 ops/ms
# Warmup Iteration   2: 9.055 ops/ms
# Warmup Iteration   3: 10.137 ops/ms
Iteration   1: 10.592 ops/ms
Iteration   2: 10.699 ops/ms
Iteration   3: 10.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.647 ±(99.9%) 0.979 ops/ms [Average]
  (min, avg, max) = (10.592, 10.647, 10.699), stdev = 0.054
  CI (99.9%): [9.668, 11.625] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.903 ops/ms
# Warmup Iteration   2: 10.596 ops/ms
# Warmup Iteration   3: 11.065 ops/ms
Iteration   1: 11.265 ops/ms
Iteration   2: 11.000 ops/ms
Iteration   3: 11.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.155 ±(99.9%) 2.517 ops/ms [Average]
  (min, avg, max) = (11.000, 11.155, 11.265), stdev = 0.138
  CI (99.9%): [8.637, 13.672] (assumes normal distribution)


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
# Warmup Iteration   1: 8.013 ops/ms
# Warmup Iteration   2: 10.096 ops/ms
# Warmup Iteration   3: 10.612 ops/ms
Iteration   1: 10.632 ops/ms
Iteration   2: 10.581 ops/ms
Iteration   3: 10.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.625 ±(99.9%) 0.756 ops/ms [Average]
  (min, avg, max) = (10.581, 10.625, 10.663), stdev = 0.041
  CI (99.9%): [9.869, 11.381] (assumes normal distribution)


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
# Warmup Iteration   1: 6.196 ops/ms
# Warmup Iteration   2: 7.805 ops/ms
# Warmup Iteration   3: 8.251 ops/ms
Iteration   1: 8.334 ops/ms
Iteration   2: 8.423 ops/ms
Iteration   3: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.353 ±(99.9%) 1.152 ops/ms [Average]
  (min, avg, max) = (8.301, 8.353, 8.423), stdev = 0.063
  CI (99.9%): [7.201, 9.505] (assumes normal distribution)


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 3.063 ±(99.9%) 0.019 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 2.983 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.027 ±(99.9%) 0.747 ms/op [Average]
  (min, avg, max) = (2.983, 3.027, 3.063), stdev = 0.041
  CI (99.9%): [2.280, 3.775] (assumes normal distribution)


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.953 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.004 ms/op
Iteration   1: 2.878 ±(99.9%) 0.004 ms/op
Iteration   2: 2.900 ±(99.9%) 0.002 ms/op
Iteration   3: 2.851 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.876 ±(99.9%) 0.449 ms/op [Average]
  (min, avg, max) = (2.851, 2.876, 2.900), stdev = 0.025
  CI (99.9%): [2.427, 3.326] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.003 ms/op
Iteration   1: 2.978 ±(99.9%) 0.003 ms/op
Iteration   2: 2.959 ±(99.9%) 0.003 ms/op
Iteration   3: 2.955 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.964 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (2.955, 2.964, 2.978), stdev = 0.012
  CI (99.9%): [2.737, 3.190] (assumes normal distribution)


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
# Warmup Iteration   1: 4.458 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.033 ms/op
Iteration   1: 3.772 ±(99.9%) 0.044 ms/op
Iteration   2: 3.761 ±(99.9%) 0.014 ms/op
Iteration   3: 3.823 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.786 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (3.761, 3.786, 3.823), stdev = 0.033
  CI (99.9%): [3.183, 4.388] (assumes normal distribution)


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.005 ms/op
Iteration   1: 2.990 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  10.194 ms/op
                 createUser·p0.9999: 13.555 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  9.049 ms/op
                 createUser·p0.9999: 12.911 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 3.087 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  8.254 ms/op
                 createUser·p0.9999: 14.041 ms/op
                 createUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317330
  mean =      3.024 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 805 
    [ 1.250,  2.500) = 14865 
    [ 2.500,  3.750) = 289662 
    [ 3.750,  5.000) = 10798 
    [ 5.000,  6.250) = 594 
    [ 6.250,  7.500) = 175 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     13.767 ms/op
     p(99.9990) =     14.907 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.006 ms/op
Iteration   1: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  7.475 ms/op
                 existUser·p0.9999: 17.377 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 2.881 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 20.176 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   3: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  6.038 ms/op
                 existUser·p0.9999: 15.008 ms/op
                 existUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330517
  mean =      2.902 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40191 
    [ 2.500,  5.000) = 289349 
    [ 5.000,  7.500) = 649 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.496 ms/op
     p(99.9900) =     17.988 ms/op
     p(99.9990) =     20.790 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 3.854 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.005 ms/op
Iteration   1: 2.990 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.291 ms/op
                 getUser·p0.9999: 13.276 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.668 ms/op
                 getUser·p0.9999: 13.361 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   3: 2.997 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.480 ms/op
                 getUser·p0.9999: 16.045 ms/op
                 getUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321265
  mean =      2.987 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1479 
    [ 1.250,  2.500) = 25548 
    [ 2.500,  3.750) = 280520 
    [ 3.750,  5.000) = 12383 
    [ 5.000,  6.250) = 710 
    [ 6.250,  7.500) = 313 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.346 ms/op
     p(99.9900) =     15.573 ms/op
     p(99.9990) =     16.237 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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
# Warmup Iteration   1: 4.864 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.010 ms/op
Iteration   1: 3.808 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.666 ms/op
                 listUser·p0.9999: 14.883 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   2: 3.892 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.439 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  17.191 ms/op
                 listUser·p0.9999: 22.819 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   3: 3.837 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.647 ms/op
                 listUser·p0.9999: 24.980 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249746
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4772 
    [ 2.500,  5.000) = 224706 
    [ 5.000,  7.500) = 19158 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     14.414 ms/op
     p(99.9900) =     24.447 ms/op
     p(99.9990) =     25.510 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.647 ± 0.979  ops/ms
ClientGrpc.existUser                       thrpt       3  11.155 ± 2.517  ops/ms
ClientGrpc.getUser                         thrpt       3  10.625 ± 0.756  ops/ms
ClientGrpc.listUser                        thrpt       3   8.353 ± 1.152  ops/ms
ClientGrpc.createUser                       avgt       3   3.027 ± 0.747   ms/op
ClientGrpc.existUser                        avgt       3   2.876 ± 0.449   ms/op
ClientGrpc.getUser                          avgt       3   2.964 ± 0.227   ms/op
ClientGrpc.listUser                         avgt       3   3.786 ± 0.603   ms/op
ClientGrpc.createUser                     sample  317330   3.024 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.600           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.441           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.290           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          13.767           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.106           ms/op
ClientGrpc.existUser                      sample  330517   2.902 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.693           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.496           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.988           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.972           ms/op
ClientGrpc.getUser                        sample  321265   2.987 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.637           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.346           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.573           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.253           ms/op
ClientGrpc.listUser                       sample  249746   3.845 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.439           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.695           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.414           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.447           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
