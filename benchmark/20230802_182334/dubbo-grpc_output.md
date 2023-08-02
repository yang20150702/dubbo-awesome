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
# Warmup Iteration   1: 4.141 ops/ms
# Warmup Iteration   2: 8.979 ops/ms
# Warmup Iteration   3: 9.875 ops/ms
Iteration   1: 10.548 ops/ms
Iteration   2: 10.120 ops/ms
Iteration   3: 10.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.354 ±(99.9%) 3.947 ops/ms [Average]
  (min, avg, max) = (10.120, 10.354, 10.548), stdev = 0.216
  CI (99.9%): [6.407, 14.300] (assumes normal distribution)


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
# Warmup Iteration   1: 7.409 ops/ms
# Warmup Iteration   2: 10.337 ops/ms
# Warmup Iteration   3: 10.829 ops/ms
Iteration   1: 10.911 ops/ms
Iteration   2: 11.015 ops/ms
Iteration   3: 10.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.970 ±(99.9%) 0.968 ops/ms [Average]
  (min, avg, max) = (10.911, 10.970, 11.015), stdev = 0.053
  CI (99.9%): [10.001, 11.938] (assumes normal distribution)


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
# Warmup Iteration   1: 7.143 ops/ms
# Warmup Iteration   2: 9.765 ops/ms
# Warmup Iteration   3: 10.243 ops/ms
Iteration   1: 10.479 ops/ms
Iteration   2: 10.380 ops/ms
Iteration   3: 10.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.361 ±(99.9%) 2.332 ops/ms [Average]
  (min, avg, max) = (10.225, 10.361, 10.479), stdev = 0.128
  CI (99.9%): [8.030, 12.693] (assumes normal distribution)


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
# Warmup Iteration   1: 5.872 ops/ms
# Warmup Iteration   2: 6.979 ops/ms
# Warmup Iteration   3: 7.591 ops/ms
Iteration   1: 7.712 ops/ms
Iteration   2: 7.721 ops/ms
Iteration   3: 7.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.728 ±(99.9%) 0.370 ops/ms [Average]
  (min, avg, max) = (7.712, 7.728, 7.751), stdev = 0.020
  CI (99.9%): [7.357, 8.098] (assumes normal distribution)


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
# Warmup Iteration   1: 4.522 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.002 ms/op
Iteration   1: 3.079 ±(99.9%) 0.003 ms/op
Iteration   2: 3.079 ±(99.9%) 0.003 ms/op
Iteration   3: 3.079 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.079 ±(99.9%) 0.006 ms/op [Average]
  (min, avg, max) = (3.079, 3.079, 3.079), stdev = 0.001
  CI (99.9%): [3.074, 3.085] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.002 ms/op
Iteration   1: 2.923 ±(99.9%) 0.003 ms/op
Iteration   2: 2.923 ±(99.9%) 0.002 ms/op
Iteration   3: 2.914 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.920 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (2.914, 2.920, 2.923), stdev = 0.005
  CI (99.9%): [2.822, 3.018] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.002 ms/op
Iteration   1: 3.117 ±(99.9%) 0.003 ms/op
Iteration   2: 3.040 ±(99.9%) 0.002 ms/op
Iteration   3: 2.990 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.049 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (2.990, 3.049, 3.117), stdev = 0.064
  CI (99.9%): [1.883, 4.214] (assumes normal distribution)


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
# Warmup Iteration   1: 4.871 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.289 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.118 ±(99.9%) 0.027 ms/op
Iteration   1: 4.102 ±(99.9%) 0.009 ms/op
Iteration   2: 4.149 ±(99.9%) 0.016 ms/op
Iteration   3: 4.127 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.126 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (4.102, 4.126, 4.149), stdev = 0.023
  CI (99.9%): [3.703, 4.549] (assumes normal distribution)


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
# Warmup Iteration   1: 4.463 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  7.178 ms/op
                 createUser·p0.9999: 18.022 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 19.089 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   3: 3.072 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  13.287 ms/op
                 createUser·p0.9999: 21.286 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314376
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24028 
    [ 2.500,  5.000) = 288174 
    [ 5.000,  7.500) = 1667 
    [ 7.500, 10.000) = 218 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      9.480 ms/op
     p(99.9900) =     20.484 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
Iteration   1: 2.890 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.425 ms/op
                 existUser·p0.9999: 17.856 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.651 ms/op
                 existUser·p0.9999: 14.882 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   3: 2.954 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.792 ms/op
                 existUser·p0.999:  11.478 ms/op
                 existUser·p0.9999: 18.979 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325738
  mean =      2.946 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35078 
    [ 2.500,  5.000) = 288644 
    [ 5.000,  7.500) = 1484 
    [ 7.500, 10.000) = 281 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.827 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
Iteration   1: 3.097 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.791 ms/op
                 getUser·p0.999:  7.660 ms/op
                 getUser·p0.9999: 13.740 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  8.383 ms/op
                 getUser·p0.9999: 14.689 ms/op
                 getUser·p1.00:   15.761 ms/op

Iteration   3: 3.093 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.189 ms/op
                 getUser·p0.9999: 17.826 ms/op
                 getUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311144
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 676 
    [ 1.250,  2.500) = 18918 
    [ 2.500,  3.750) = 269033 
    [ 3.750,  5.000) = 19996 
    [ 5.000,  6.250) = 1460 
    [ 6.250,  7.500) = 584 
    [ 7.500,  8.750) = 261 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =      8.135 ms/op
     p(99.9900) =     15.758 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 4.995 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.012 ms/op
Iteration   1: 4.065 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  14.166 ms/op
                 listUser·p0.9999: 16.358 ms/op
                 listUser·p1.00:   16.712 ms/op

Iteration   2: 4.104 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.347 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  14.398 ms/op
                 listUser·p0.9999: 17.549 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 4.116 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  16.984 ms/op
                 listUser·p0.9999: 19.872 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234643
  mean =      4.095 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1903 
    [ 2.500,  5.000) = 206888 
    [ 5.000,  7.500) = 23823 
    [ 7.500, 10.000) = 1497 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     14.987 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     20.214 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.354 ± 3.947  ops/ms
ClientGrpc.existUser                       thrpt       3  10.970 ± 0.968  ops/ms
ClientGrpc.getUser                         thrpt       3  10.361 ± 2.332  ops/ms
ClientGrpc.listUser                        thrpt       3   7.728 ± 0.370  ops/ms
ClientGrpc.createUser                       avgt       3   3.079 ± 0.006   ms/op
ClientGrpc.existUser                        avgt       3   2.920 ± 0.098   ms/op
ClientGrpc.getUser                          avgt       3   3.049 ± 1.165   ms/op
ClientGrpc.listUser                         avgt       3   4.126 ± 0.423   ms/op
ClientGrpc.createUser                     sample  314376   3.051 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.814           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.480           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.484           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.660           ms/op
ClientGrpc.existUser                      sample  325738   2.946 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.618           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.827           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.055           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.791           ms/op
ClientGrpc.getUser                        sample  311144   3.085 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.663           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.135           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.758           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.071           ms/op
ClientGrpc.listUser                       sample  234643   4.095 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.347           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.365           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.987           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.219           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.578           ms/op
