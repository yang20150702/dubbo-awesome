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
# Warmup Iteration   1: 4.420 ops/ms
# Warmup Iteration   2: 9.525 ops/ms
# Warmup Iteration   3: 10.041 ops/ms
Iteration   1: 10.204 ops/ms
Iteration   2: 10.665 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.468 ±(99.9%) 4.331 ops/ms [Average]
  (min, avg, max) = (10.204, 10.468, 10.665), stdev = 0.237
  CI (99.9%): [6.137, 14.798] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.997 ops/ms
# Warmup Iteration   2: 10.674 ops/ms
# Warmup Iteration   3: 11.112 ops/ms
Iteration   1: 11.229 ops/ms
Iteration   2: 11.185 ops/ms
Iteration   3: 11.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.168 ±(99.9%) 1.292 ops/ms [Average]
  (min, avg, max) = (11.091, 11.168, 11.229), stdev = 0.071
  CI (99.9%): [9.876, 12.460] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.482 ops/ms
# Warmup Iteration   2: 10.306 ops/ms
# Warmup Iteration   3: 10.600 ops/ms
Iteration   1: 10.605 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.695 ±(99.9%) 1.511 ops/ms [Average]
  (min, avg, max) = (10.605, 10.695, 10.767), stdev = 0.083
  CI (99.9%): [9.184, 12.206] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.920 ops/ms
# Warmup Iteration   2: 8.110 ops/ms
# Warmup Iteration   3: 8.128 ops/ms
Iteration   1: 8.083 ops/ms
Iteration   2: 8.229 ops/ms
Iteration   3: 8.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.142 ±(99.9%) 1.404 ops/ms [Average]
  (min, avg, max) = (8.083, 8.142, 8.229), stdev = 0.077
  CI (99.9%): [6.738, 9.546] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.025 ms/op
Iteration   1: 2.949 ±(99.9%) 0.003 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 3.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.000 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (2.949, 3.000, 3.033), stdev = 0.045
  CI (99.9%): [2.176, 3.824] (assumes normal distribution)


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.855 ±(99.9%) 0.004 ms/op
Iteration   1: 2.870 ±(99.9%) 0.004 ms/op
Iteration   2: 2.861 ±(99.9%) 0.003 ms/op
Iteration   3: 2.845 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.859 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (2.845, 2.859, 2.870), stdev = 0.013
  CI (99.9%): [2.622, 3.095] (assumes normal distribution)


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.004 ms/op
Iteration   1: 2.977 ±(99.9%) 0.002 ms/op
Iteration   2: 2.966 ±(99.9%) 0.003 ms/op
Iteration   3: 2.978 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.974 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (2.966, 2.974, 2.978), stdev = 0.006
  CI (99.9%): [2.855, 3.092] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.076 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.011 ms/op
Iteration   1: 3.843 ±(99.9%) 0.020 ms/op
Iteration   2: 3.859 ±(99.9%) 0.043 ms/op
Iteration   3: 3.882 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.861 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (3.843, 3.861, 3.882), stdev = 0.019
  CI (99.9%): [3.506, 4.217] (assumes normal distribution)


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  7.495 ms/op
                 createUser·p0.9999: 11.242 ms/op
                 createUser·p1.00:   11.895 ms/op

Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.573 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  8.426 ms/op
                 createUser·p0.9999: 16.381 ms/op
                 createUser·p1.00:   16.663 ms/op

Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.542 ms/op
                 createUser·p0.999:  7.055 ms/op
                 createUser·p0.9999: 14.713 ms/op
                 createUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317144
  mean =      3.026 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2227 
    [ 1.250,  2.500) = 25837 
    [ 2.500,  3.750) = 268677 
    [ 3.750,  5.000) = 18417 
    [ 5.000,  6.250) = 1310 
    [ 6.250,  7.500) = 344 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     15.815 ms/op
     p(99.9990) =     16.591 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.850 ±(99.9%) 0.007 ms/op
Iteration   1: 2.850 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  7.556 ms/op
                 existUser·p0.9999: 15.466 ms/op
                 existUser·p1.00:   16.663 ms/op

Iteration   2: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.595 ms/op
                 existUser·p0.999:  7.551 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   3: 2.846 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.969 ms/op
                 existUser·p0.9999: 21.398 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334981
  mean =      2.865 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49312 
    [ 2.500,  5.000) = 284077 
    [ 5.000,  7.500) = 1267 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =     18.154 ms/op
     p(99.9990) =     21.855 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.007 ms/op
Iteration   1: 2.996 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.516 ms/op
                 getUser·p0.9999: 10.043 ms/op
                 getUser·p1.00:   11.682 ms/op

Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  8.728 ms/op
                 getUser·p0.9999: 13.624 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.336 ms/op
                 getUser·p0.9999: 17.546 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318392
  mean =      3.013 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1524 
    [ 1.250,  2.500) = 23396 
    [ 2.500,  3.750) = 277031 
    [ 3.750,  5.000) = 14604 
    [ 5.000,  6.250) = 862 
    [ 6.250,  7.500) = 564 
    [ 7.500,  8.750) = 175 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.976 ms/op
     p(99.9900) =     16.111 ms/op
     p(99.9990) =     17.787 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.010 ms/op
Iteration   1: 3.894 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.988 ms/op
                 listUser·p0.9999: 19.286 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   2: 3.848 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  13.924 ms/op
                 listUser·p0.9999: 18.451 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.682 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 25.110 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246473
  mean =      3.894 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4311 
    [ 2.500,  5.000) = 221111 
    [ 5.000,  7.500) = 19639 
    [ 7.500, 10.000) = 892 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     14.861 ms/op
     p(99.9900) =     20.077 ms/op
     p(99.9990) =     27.043 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.468 ± 4.331  ops/ms
ClientGrpc.existUser                       thrpt       3  11.168 ± 1.292  ops/ms
ClientGrpc.getUser                         thrpt       3  10.695 ± 1.511  ops/ms
ClientGrpc.listUser                        thrpt       3   8.142 ± 1.404  ops/ms
ClientGrpc.createUser                       avgt       3   3.000 ± 0.824   ms/op
ClientGrpc.existUser                        avgt       3   2.859 ± 0.236   ms/op
ClientGrpc.getUser                          avgt       3   2.974 ± 0.118   ms/op
ClientGrpc.listUser                         avgt       3   3.861 ± 0.355   ms/op
ClientGrpc.createUser                     sample  317144   3.026 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.573           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.594           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.815           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.663           ms/op
ClientGrpc.existUser                      sample  334981   2.865 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.494           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.438           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.154           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.839           ms/op
ClientGrpc.getUser                        sample  318392   3.013 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.554           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.976           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.111           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.859           ms/op
ClientGrpc.listUser                       sample  246473   3.894 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.682           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.861           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.077           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.230           ms/op
