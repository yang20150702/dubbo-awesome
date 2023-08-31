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
# Warmup Iteration   1: 3.857 ops/ms
# Warmup Iteration   2: 8.610 ops/ms
# Warmup Iteration   3: 9.686 ops/ms
Iteration   1: 10.158 ops/ms
Iteration   2: 10.024 ops/ms
Iteration   3: 10.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.094 ±(99.9%) 1.219 ops/ms [Average]
  (min, avg, max) = (10.024, 10.094, 10.158), stdev = 0.067
  CI (99.9%): [8.876, 11.313] (assumes normal distribution)


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
# Warmup Iteration   1: 7.302 ops/ms
# Warmup Iteration   2: 10.279 ops/ms
# Warmup Iteration   3: 10.392 ops/ms
Iteration   1: 10.893 ops/ms
Iteration   2: 10.987 ops/ms
Iteration   3: 10.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.896 ±(99.9%) 1.631 ops/ms [Average]
  (min, avg, max) = (10.809, 10.896, 10.987), stdev = 0.089
  CI (99.9%): [9.265, 12.528] (assumes normal distribution)


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
# Warmup Iteration   1: 7.340 ops/ms
# Warmup Iteration   2: 9.819 ops/ms
# Warmup Iteration   3: 10.057 ops/ms
Iteration   1: 10.120 ops/ms
Iteration   2: 10.190 ops/ms
Iteration   3: 10.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.176 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (10.120, 10.176, 10.218), stdev = 0.050
  CI (99.9%): [9.263, 11.089] (assumes normal distribution)


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
# Warmup Iteration   1: 4.963 ops/ms
# Warmup Iteration   2: 7.533 ops/ms
# Warmup Iteration   3: 7.540 ops/ms
Iteration   1: 7.558 ops/ms
Iteration   2: 7.639 ops/ms
Iteration   3: 7.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.649 ±(99.9%) 1.751 ops/ms [Average]
  (min, avg, max) = (7.558, 7.649, 7.749), stdev = 0.096
  CI (99.9%): [5.897, 9.400] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.375 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.003 ms/op
Iteration   1: 3.133 ±(99.9%) 0.003 ms/op
Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
Iteration   3: 3.128 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.133 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (3.128, 3.133, 3.138), stdev = 0.005
  CI (99.9%): [3.041, 3.224] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.099 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.002 ms/op
Iteration   1: 2.934 ±(99.9%) 0.003 ms/op
Iteration   2: 2.956 ±(99.9%) 0.002 ms/op
Iteration   3: 2.947 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.946 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (2.934, 2.946, 2.956), stdev = 0.011
  CI (99.9%): [2.741, 3.151] (assumes normal distribution)


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
# Warmup Iteration   1: 4.440 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.003 ms/op
Iteration   1: 3.187 ±(99.9%) 0.004 ms/op
Iteration   2: 3.154 ±(99.9%) 0.003 ms/op
Iteration   3: 3.155 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.165 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (3.154, 3.165, 3.187), stdev = 0.019
  CI (99.9%): [2.816, 3.515] (assumes normal distribution)


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
# Warmup Iteration   1: 5.690 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.190 ±(99.9%) 0.021 ms/op
Iteration   1: 4.217 ±(99.9%) 0.017 ms/op
Iteration   2: 4.192 ±(99.9%) 0.010 ms/op
Iteration   3: 4.121 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.177 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (4.121, 4.177, 4.217), stdev = 0.050
  CI (99.9%): [3.268, 5.086] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.499 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
Iteration   1: 3.110 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  8.200 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 15.304 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   3: 3.095 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.030 ms/op
                 createUser·p0.999:  13.621 ms/op
                 createUser·p0.9999: 26.269 ms/op
                 createUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307965
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15663 
    [ 2.500,  5.000) = 289197 
    [ 5.000,  7.500) = 2510 
    [ 7.500, 10.000) = 305 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     20.428 ms/op
     p(99.9990) =     28.175 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  9.004 ms/op
                 existUser·p0.9999: 17.869 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  7.904 ms/op
                 existUser·p0.9999: 14.951 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  12.745 ms/op
                 existUser·p0.9999: 17.170 ms/op
                 existUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320038
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1658 
    [ 1.250,  2.500) = 30756 
    [ 2.500,  3.750) = 270467 
    [ 3.750,  5.000) = 14095 
    [ 5.000,  6.250) = 1355 
    [ 6.250,  7.500) = 862 
    [ 7.500,  8.750) = 410 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      9.896 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     18.278 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 4.242 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.376 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
Iteration   1: 3.139 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  8.119 ms/op
                 getUser·p0.9999: 13.268 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  7.635 ms/op
                 getUser·p0.9999: 17.072 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  8.577 ms/op
                 getUser·p0.9999: 20.662 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307106
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13958 
    [ 2.500,  5.000) = 290386 
    [ 5.000,  7.500) = 2329 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.906 ms/op
     p(99.9000) =      8.085 ms/op
     p(99.9900) =     20.031 ms/op
     p(99.9990) =     20.969 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 5.034 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.012 ms/op
Iteration   1: 4.208 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.291 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  15.018 ms/op
                 listUser·p0.9999: 21.337 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   2: 4.206 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  16.179 ms/op
                 listUser·p0.9999: 28.017 ms/op
                 listUser·p1.00:   28.213 ms/op

Iteration   3: 4.178 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  15.457 ms/op
                 listUser·p0.9999: 18.274 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228850
  mean =      4.197 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1838 
    [ 2.500,  5.000) = 194306 
    [ 5.000,  7.500) = 29702 
    [ 7.500, 10.000) = 2140 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     15.403 ms/op
     p(99.9900) =     27.037 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.094 ± 1.219  ops/ms
ClientGrpc.existUser                       thrpt       3  10.896 ± 1.631  ops/ms
ClientGrpc.getUser                         thrpt       3  10.176 ± 0.913  ops/ms
ClientGrpc.listUser                        thrpt       3   7.649 ± 1.751  ops/ms
ClientGrpc.createUser                       avgt       3   3.133 ± 0.092   ms/op
ClientGrpc.existUser                        avgt       3   2.946 ± 0.205   ms/op
ClientGrpc.getUser                          avgt       3   3.165 ± 0.349   ms/op
ClientGrpc.listUser                         avgt       3   4.177 ± 0.909   ms/op
ClientGrpc.createUser                     sample  307965   3.117 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.866           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.716           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.428           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.246           ms/op
ClientGrpc.existUser                      sample  320038   2.997 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.577           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.896           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.170           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.579           ms/op
ClientGrpc.getUser                        sample  307106   3.124 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.766           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.906           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.085           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.031           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  228850   4.197 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.846           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.242           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.864           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.403           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.037           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.213           ms/op
