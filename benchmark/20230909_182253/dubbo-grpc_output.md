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
# Warmup Iteration   1: 4.854 ops/ms
# Warmup Iteration   2: 9.031 ops/ms
# Warmup Iteration   3: 10.310 ops/ms
Iteration   1: 10.402 ops/ms
Iteration   2: 10.768 ops/ms
Iteration   3: 10.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.563 ±(99.9%) 3.409 ops/ms [Average]
  (min, avg, max) = (10.402, 10.563, 10.768), stdev = 0.187
  CI (99.9%): [7.155, 13.972] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.314 ops/ms
# Warmup Iteration   2: 11.103 ops/ms
# Warmup Iteration   3: 11.076 ops/ms
Iteration   1: 11.318 ops/ms
Iteration   2: 11.118 ops/ms
Iteration   3: 11.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.217 ±(99.9%) 1.822 ops/ms [Average]
  (min, avg, max) = (11.118, 11.217, 11.318), stdev = 0.100
  CI (99.9%): [9.395, 13.039] (assumes normal distribution)


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
# Warmup Iteration   1: 7.278 ops/ms
# Warmup Iteration   2: 10.474 ops/ms
# Warmup Iteration   3: 10.567 ops/ms
Iteration   1: 10.755 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.675 ±(99.9%) 1.427 ops/ms [Average]
  (min, avg, max) = (10.599, 10.675, 10.755), stdev = 0.078
  CI (99.9%): [9.248, 12.103] (assumes normal distribution)


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
# Warmup Iteration   1: 6.024 ops/ms
# Warmup Iteration   2: 8.122 ops/ms
# Warmup Iteration   3: 8.008 ops/ms
Iteration   1: 8.088 ops/ms
Iteration   2: 8.080 ops/ms
Iteration   3: 8.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.085 ±(99.9%) 0.078 ops/ms [Average]
  (min, avg, max) = (8.080, 8.085, 8.088), stdev = 0.004
  CI (99.9%): [8.007, 8.163] (assumes normal distribution)


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.003 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 2.979 ±(99.9%) 0.003 ms/op
Iteration   3: 2.984 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.999 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (2.979, 2.999, 3.034), stdev = 0.030
  CI (99.9%): [2.448, 3.550] (assumes normal distribution)


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
# Warmup Iteration   1: 3.664 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.809 ±(99.9%) 0.005 ms/op
Iteration   1: 2.848 ±(99.9%) 0.004 ms/op
Iteration   2: 2.801 ±(99.9%) 0.003 ms/op
Iteration   3: 2.900 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.850 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (2.801, 2.850, 2.900), stdev = 0.049
  CI (99.9%): [1.953, 3.747] (assumes normal distribution)


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
# Warmup Iteration   1: 3.934 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.003 ms/op
Iteration   1: 3.079 ±(99.9%) 0.002 ms/op
Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
Iteration   3: 3.039 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.055 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.039, 3.055, 3.079), stdev = 0.021
  CI (99.9%): [2.681, 3.430] (assumes normal distribution)


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
# Warmup Iteration   1: 5.017 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.051 ms/op
Iteration   1: 3.953 ±(99.9%) 0.035 ms/op
Iteration   2: 3.878 ±(99.9%) 0.020 ms/op
Iteration   3: 3.838 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.890 ±(99.9%) 1.069 ms/op [Average]
  (min, avg, max) = (3.838, 3.890, 3.953), stdev = 0.059
  CI (99.9%): [2.820, 4.959] (assumes normal distribution)


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.008 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.544 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  7.916 ms/op
                 createUser·p0.9999: 16.810 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.052 ms/op
                 createUser·p0.9999: 16.269 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  12.681 ms/op
                 createUser·p0.9999: 20.794 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314019
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22293 
    [ 2.500,  5.000) = 289751 
    [ 5.000,  7.500) = 1424 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     18.861 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
Iteration   1: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  6.994 ms/op
                 existUser·p0.9999: 17.695 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   2: 2.791 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  6.636 ms/op
                 existUser·p0.9999: 12.337 ms/op
                 existUser·p1.00:   12.681 ms/op

Iteration   3: 2.946 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.574 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  8.609 ms/op
                 existUser·p0.9999: 16.744 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334565
  mean =      2.869 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6490 
    [ 1.250,  2.500) = 46686 
    [ 2.500,  3.750) = 266427 
    [ 3.750,  5.000) = 13001 
    [ 5.000,  6.250) = 1161 
    [ 6.250,  7.500) = 380 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 60 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     17.782 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  9.101 ms/op
                 getUser·p0.9999: 17.939 ms/op
                 getUser·p1.00:   18.219 ms/op

Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.620 ms/op
                 getUser·p0.9999: 13.104 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  7.021 ms/op
                 getUser·p0.9999: 24.062 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318458
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23443 
    [ 2.500,  5.000) = 292895 
    [ 5.000,  7.500) = 1741 
    [ 7.500, 10.000) = 219 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.816 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     24.210 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 5.114 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.011 ms/op
Iteration   1: 3.906 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  12.681 ms/op
                 listUser·p0.9999: 19.779 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 3.950 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.745 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 19.781 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.871 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 22.069 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245747
  mean =      3.909 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4422 
    [ 2.500,  5.000) = 219541 
    [ 5.000,  7.500) = 20262 
    [ 7.500, 10.000) = 1042 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.651 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     24.946 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.563 ± 3.409  ops/ms
ClientGrpc.existUser                       thrpt       3  11.217 ± 1.822  ops/ms
ClientGrpc.getUser                         thrpt       3  10.675 ± 1.427  ops/ms
ClientGrpc.listUser                        thrpt       3   8.085 ± 0.078  ops/ms
ClientGrpc.createUser                       avgt       3   2.999 ± 0.551   ms/op
ClientGrpc.existUser                        avgt       3   2.850 ± 0.897   ms/op
ClientGrpc.getUser                          avgt       3   3.055 ± 0.375   ms/op
ClientGrpc.listUser                         avgt       3   3.890 ± 1.069   ms/op
ClientGrpc.createUser                     sample  314019   3.060 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.544           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.176           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.861           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.332           ms/op
ClientGrpc.existUser                      sample  334565   2.869 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.574           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.758           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.941           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.826           ms/op
ClientGrpc.getUser                        sample  318458   3.016 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.644           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.816           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.003           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.478           ms/op
ClientGrpc.listUser                       sample  245747   3.909 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.745           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.651           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.594           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.756           ms/op
