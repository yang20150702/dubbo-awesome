# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.051 ops/ms
# Warmup Iteration   2: 6.477 ops/ms
# Warmup Iteration   3: 7.902 ops/ms
Iteration   1: 8.224 ops/ms
Iteration   2: 8.205 ops/ms
Iteration   3: 8.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.242 ±(99.9%) 0.875 ops/ms [Average]
  (min, avg, max) = (8.205, 8.242, 8.296), stdev = 0.048
  CI (99.9%): [7.367, 9.118] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.052 ops/ms
# Warmup Iteration   2: 8.235 ops/ms
# Warmup Iteration   3: 8.511 ops/ms
Iteration   1: 8.700 ops/ms
Iteration   2: 8.520 ops/ms
Iteration   3: 8.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.539 ±(99.9%) 2.777 ops/ms [Average]
  (min, avg, max) = (8.398, 8.539, 8.700), stdev = 0.152
  CI (99.9%): [5.763, 11.316] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.472 ops/ms
# Warmup Iteration   2: 8.052 ops/ms
# Warmup Iteration   3: 8.160 ops/ms
Iteration   1: 8.155 ops/ms
Iteration   2: 8.368 ops/ms
Iteration   3: 8.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.335 ±(99.9%) 3.017 ops/ms [Average]
  (min, avg, max) = (8.155, 8.335, 8.481), stdev = 0.165
  CI (99.9%): [5.317, 11.352] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.129 ops/ms
# Warmup Iteration   2: 6.261 ops/ms
# Warmup Iteration   3: 6.775 ops/ms
Iteration   1: 6.610 ops/ms
Iteration   2: 6.700 ops/ms
Iteration   3: 6.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.725 ±(99.9%) 2.361 ops/ms [Average]
  (min, avg, max) = (6.610, 6.725, 6.865), stdev = 0.129
  CI (99.9%): [4.364, 9.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.463 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.008 ms/op
Iteration   1: 3.788 ±(99.9%) 0.003 ms/op
Iteration   2: 3.842 ±(99.9%) 0.003 ms/op
Iteration   3: 3.922 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.851 ±(99.9%) 1.226 ms/op [Average]
  (min, avg, max) = (3.788, 3.851, 3.922), stdev = 0.067
  CI (99.9%): [2.625, 5.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.641 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.012 ms/op
Iteration   1: 3.665 ±(99.9%) 0.002 ms/op
Iteration   2: 3.708 ±(99.9%) 0.002 ms/op
Iteration   3: 3.855 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.743 ±(99.9%) 1.815 ms/op [Average]
  (min, avg, max) = (3.665, 3.743, 3.855), stdev = 0.099
  CI (99.9%): [1.928, 5.558] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.439 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.006 ms/op
Iteration   1: 3.851 ±(99.9%) 0.005 ms/op
Iteration   2: 3.850 ±(99.9%) 0.005 ms/op
Iteration   3: 3.868 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.856 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (3.850, 3.856, 3.868), stdev = 0.010
  CI (99.9%): [3.678, 4.035] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.800 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.117 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.823 ±(99.9%) 0.013 ms/op
Iteration   1: 4.782 ±(99.9%) 0.011 ms/op
Iteration   2: 4.741 ±(99.9%) 0.010 ms/op
Iteration   3: 4.900 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.808 ±(99.9%) 1.502 ms/op [Average]
  (min, avg, max) = (4.741, 4.808, 4.900), stdev = 0.082
  CI (99.9%): [3.306, 6.310] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.029 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.010 ms/op
Iteration   1: 3.872 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  13.114 ms/op
                 createUser·p0.9999: 15.462 ms/op
                 createUser·p1.00:   15.778 ms/op

Iteration   2: 3.862 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  11.817 ms/op
                 createUser·p0.9999: 17.479 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   3: 3.885 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.253 ms/op
                 createUser·p0.999:  10.633 ms/op
                 createUser·p0.9999: 20.497 ms/op
                 createUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 247860
  mean =      3.873 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6477 
    [ 2.500,  5.000) = 229457 
    [ 5.000,  7.500) = 10884 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     11.494 ms/op
     p(99.9900) =     20.323 ms/op
     p(99.9990) =     20.694 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.080 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.009 ms/op
Iteration   1: 3.658 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   5.542 ms/op
                 existUser·p0.999:  10.894 ms/op
                 existUser·p0.9999: 16.535 ms/op
                 existUser·p1.00:   18.416 ms/op

Iteration   2: 3.701 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  8.230 ms/op
                 existUser·p0.9999: 14.276 ms/op
                 existUser·p1.00:   15.974 ms/op

Iteration   3: 3.746 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  8.613 ms/op
                 existUser·p0.9999: 25.869 ms/op
                 existUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 259424
  mean =      3.701 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6007 
    [ 2.500,  5.000) = 246158 
    [ 5.000,  7.500) = 6654 
    [ 7.500, 10.000) = 436 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     26.372 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.454 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.010 ms/op
Iteration   1: 3.808 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  11.552 ms/op
                 getUser·p0.9999: 19.622 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   2: 3.762 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  8.781 ms/op
                 getUser·p0.9999: 20.790 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   3: 3.846 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  11.114 ms/op
                 getUser·p0.9999: 25.057 ms/op
                 getUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252194
  mean =      3.805 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5576 
    [ 2.500,  5.000) = 236051 
    [ 5.000,  7.500) = 9638 
    [ 7.500, 10.000) = 644 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     10.777 ms/op
     p(99.9900) =     23.979 ms/op
     p(99.9990) =     25.360 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.240 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.147 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.683 ±(99.9%) 0.014 ms/op
Iteration   1: 4.830 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.070 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  15.850 ms/op
                 listUser·p0.9999: 17.043 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   2: 4.573 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.316 ms/op
                 listUser·p0.99:   8.011 ms/op
                 listUser·p0.999:  15.763 ms/op
                 listUser·p0.9999: 19.596 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 4.534 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.414 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  20.068 ms/op
                 listUser·p0.9999: 31.062 ms/op
                 listUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206739
  mean =      4.642 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 424 
    [ 2.500,  5.000) = 163634 
    [ 5.000,  7.500) = 38094 
    [ 7.500, 10.000) = 3844 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      8.298 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     30.594 ms/op
     p(99.9990) =     32.368 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.242 ± 0.875  ops/ms
ClientGrpc.existUser                       thrpt       3   8.539 ± 2.777  ops/ms
ClientGrpc.getUser                         thrpt       3   8.335 ± 3.017  ops/ms
ClientGrpc.listUser                        thrpt       3   6.725 ± 2.361  ops/ms
ClientGrpc.createUser                       avgt       3   3.851 ± 1.226   ms/op
ClientGrpc.existUser                        avgt       3   3.743 ± 1.815   ms/op
ClientGrpc.getUser                          avgt       3   3.856 ± 0.178   ms/op
ClientGrpc.listUser                         avgt       3   4.808 ± 1.502   ms/op
ClientGrpc.createUser                     sample  247860   3.873 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.038           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.727           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.989           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.029           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.494           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.323           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.808           ms/op
ClientGrpc.existUser                      sample  259424   3.701 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.602           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.644           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.880           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.281           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.509           ms/op
ClientGrpc.getUser                        sample  252194   3.805 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.817           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.890           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.777           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.979           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.625           ms/op
ClientGrpc.listUser                       sample  206739   4.642 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.051           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.465           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.298           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.335           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.594           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.440           ms/op
