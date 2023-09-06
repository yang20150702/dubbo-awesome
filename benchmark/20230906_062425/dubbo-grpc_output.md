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
# Warmup Iteration   1: 4.774 ops/ms
# Warmup Iteration   2: 9.268 ops/ms
# Warmup Iteration   3: 10.059 ops/ms
Iteration   1: 10.487 ops/ms
Iteration   2: 10.579 ops/ms
Iteration   3: 10.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.648 ±(99.9%) 3.731 ops/ms [Average]
  (min, avg, max) = (10.487, 10.648, 10.878), stdev = 0.205
  CI (99.9%): [6.916, 14.379] (assumes normal distribution)


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
# Warmup Iteration   1: 7.880 ops/ms
# Warmup Iteration   2: 10.660 ops/ms
# Warmup Iteration   3: 11.254 ops/ms
Iteration   1: 11.226 ops/ms
Iteration   2: 11.149 ops/ms
Iteration   3: 11.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.163 ±(99.9%) 1.054 ops/ms [Average]
  (min, avg, max) = (11.113, 11.163, 11.226), stdev = 0.058
  CI (99.9%): [10.109, 12.216] (assumes normal distribution)


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
# Warmup Iteration   1: 7.721 ops/ms
# Warmup Iteration   2: 10.236 ops/ms
# Warmup Iteration   3: 10.601 ops/ms
Iteration   1: 10.479 ops/ms
Iteration   2: 10.823 ops/ms
Iteration   3: 10.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.692 ±(99.9%) 3.402 ops/ms [Average]
  (min, avg, max) = (10.479, 10.692, 10.823), stdev = 0.186
  CI (99.9%): [7.290, 14.094] (assumes normal distribution)


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
# Warmup Iteration   1: 6.180 ops/ms
# Warmup Iteration   2: 7.948 ops/ms
# Warmup Iteration   3: 8.235 ops/ms
Iteration   1: 8.196 ops/ms
Iteration   2: 8.259 ops/ms
Iteration   3: 8.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.211 ±(99.9%) 0.774 ops/ms [Average]
  (min, avg, max) = (8.179, 8.211, 8.259), stdev = 0.042
  CI (99.9%): [7.437, 8.985] (assumes normal distribution)


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.003 ms/op
Iteration   1: 2.940 ±(99.9%) 0.003 ms/op
Iteration   2: 2.960 ±(99.9%) 0.003 ms/op
Iteration   3: 2.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.939 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (2.917, 2.939, 2.960), stdev = 0.022
  CI (99.9%): [2.539, 3.339] (assumes normal distribution)


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.945 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.004 ms/op
Iteration   1: 2.792 ±(99.9%) 0.003 ms/op
Iteration   2: 2.839 ±(99.9%) 0.003 ms/op
Iteration   3: 2.848 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.826 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (2.792, 2.826, 2.848), stdev = 0.030
  CI (99.9%): [2.277, 3.375] (assumes normal distribution)


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.002 ms/op
Iteration   1: 2.968 ±(99.9%) 0.002 ms/op
Iteration   2: 2.961 ±(99.9%) 0.004 ms/op
Iteration   3: 3.016 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.982 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (2.961, 2.982, 3.016), stdev = 0.030
  CI (99.9%): [2.434, 3.530] (assumes normal distribution)


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
# Warmup Iteration   1: 5.052 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.023 ms/op
Iteration   1: 3.925 ±(99.9%) 0.032 ms/op
Iteration   2: 3.901 ±(99.9%) 0.027 ms/op
Iteration   3: 3.924 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.916 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (3.901, 3.916, 3.925), stdev = 0.014
  CI (99.9%): [3.668, 4.165] (assumes normal distribution)


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.007 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.728 ms/op
                 createUser·p0.9999: 13.741 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  8.439 ms/op
                 createUser·p0.9999: 12.880 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.534 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 25.047 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316625
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23072 
    [ 2.500,  5.000) = 291192 
    [ 5.000,  7.500) = 1815 
    [ 7.500, 10.000) = 321 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.318 ms/op
     p(99.9900) =     24.128 ms/op
     p(99.9990) =     25.483 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.007 ms/op
Iteration   1: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  7.348 ms/op
                 existUser·p0.9999: 11.684 ms/op
                 existUser·p1.00:   12.059 ms/op

Iteration   2: 2.884 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.605 ms/op
                 existUser·p0.9999: 13.648 ms/op
                 existUser·p1.00:   16.089 ms/op

Iteration   3: 2.917 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  9.022 ms/op
                 existUser·p0.9999: 15.582 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330077
  mean =      2.907 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2493 
    [ 1.250,  2.500) = 40639 
    [ 2.500,  3.750) = 271260 
    [ 3.750,  5.000) = 13006 
    [ 5.000,  6.250) = 1446 
    [ 6.250,  7.500) = 804 
    [ 7.500,  8.750) = 191 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      7.855 ms/op
     p(99.9900) =     14.958 ms/op
     p(99.9990) =     17.357 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  10.900 ms/op
                 getUser·p0.9999: 12.836 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  9.609 ms/op
                 getUser·p0.9999: 16.569 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.611 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  8.305 ms/op
                 getUser·p0.9999: 20.447 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311407
  mean =      3.082 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22960 
    [ 2.500,  5.000) = 285228 
    [ 5.000,  7.500) = 2572 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     18.767 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 5.302 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
Iteration   1: 3.995 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  13.107 ms/op
                 listUser·p0.9999: 15.842 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   2: 3.941 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  15.280 ms/op
                 listUser·p0.9999: 24.298 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 3.994 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.625 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.415 ms/op
                 listUser·p0.999:  16.838 ms/op
                 listUser·p0.9999: 31.064 ms/op
                 listUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241341
  mean =      3.976 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5183 
    [ 2.500,  5.000) = 207711 
    [ 5.000,  7.500) = 26052 
    [ 7.500, 10.000) = 1653 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     14.975 ms/op
     p(99.9900) =     29.421 ms/op
     p(99.9990) =     31.436 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.648 ± 3.731  ops/ms
ClientGrpc.existUser                       thrpt       3  11.163 ± 1.054  ops/ms
ClientGrpc.getUser                         thrpt       3  10.692 ± 3.402  ops/ms
ClientGrpc.listUser                        thrpt       3   8.211 ± 0.774  ops/ms
ClientGrpc.createUser                       avgt       3   2.939 ± 0.400   ms/op
ClientGrpc.existUser                        avgt       3   2.826 ± 0.549   ms/op
ClientGrpc.getUser                          avgt       3   2.982 ± 0.548   ms/op
ClientGrpc.listUser                         avgt       3   3.916 ± 0.249   ms/op
ClientGrpc.createUser                     sample  316625   3.033 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.660           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.318           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.128           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.657           ms/op
ClientGrpc.existUser                      sample  330077   2.907 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.565           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.760           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.855           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.958           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.465           ms/op
ClientGrpc.getUser                        sample  311407   3.082 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.611           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.038           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.503           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.767           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.987           ms/op
ClientGrpc.listUser                       sample  241341   3.976 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.625           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.487           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.975           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.421           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.523           ms/op
