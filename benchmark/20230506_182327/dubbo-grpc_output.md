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
# Warmup Iteration   1: 1.908 ops/ms
# Warmup Iteration   2: 4.629 ops/ms
# Warmup Iteration   3: 6.146 ops/ms
Iteration   1: 6.491 ops/ms
Iteration   2: 6.614 ops/ms
Iteration   3: 6.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.604 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (6.491, 6.604, 6.706), stdev = 0.108
  CI (99.9%): [4.638, 8.569] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ops/ms
# Warmup Iteration   2: 6.495 ops/ms
# Warmup Iteration   3: 7.123 ops/ms
Iteration   1: 7.121 ops/ms
Iteration   2: 7.381 ops/ms
Iteration   3: 7.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.313 ±(99.9%) 3.078 ops/ms [Average]
  (min, avg, max) = (7.121, 7.313, 7.437), stdev = 0.169
  CI (99.9%): [4.236, 10.391] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.588 ops/ms
# Warmup Iteration   2: 6.053 ops/ms
# Warmup Iteration   3: 6.584 ops/ms
Iteration   1: 6.942 ops/ms
Iteration   2: 6.909 ops/ms
Iteration   3: 6.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.875 ±(99.9%) 1.610 ops/ms [Average]
  (min, avg, max) = (6.775, 6.875, 6.942), stdev = 0.088
  CI (99.9%): [5.266, 8.485] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.937 ops/ms
# Warmup Iteration   2: 4.567 ops/ms
# Warmup Iteration   3: 5.117 ops/ms
Iteration   1: 5.138 ops/ms
Iteration   2: 5.232 ops/ms
Iteration   3: 5.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.225 ±(99.9%) 1.511 ops/ms [Average]
  (min, avg, max) = (5.138, 5.225, 5.303), stdev = 0.083
  CI (99.9%): [3.714, 6.736] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.821 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.130 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.861 ±(99.9%) 0.020 ms/op
Iteration   1: 4.590 ±(99.9%) 0.005 ms/op
Iteration   2: 4.652 ±(99.9%) 0.005 ms/op
Iteration   3: 4.592 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.611 ±(99.9%) 0.640 ms/op [Average]
  (min, avg, max) = (4.590, 4.611, 4.652), stdev = 0.035
  CI (99.9%): [3.971, 5.252] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.184 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 4.727 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.403 ±(99.9%) 0.013 ms/op
Iteration   1: 4.504 ±(99.9%) 0.005 ms/op
Iteration   2: 4.192 ±(99.9%) 0.007 ms/op
Iteration   3: 4.415 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.370 ±(99.9%) 2.928 ms/op [Average]
  (min, avg, max) = (4.192, 4.370, 4.504), stdev = 0.160
  CI (99.9%): [1.442, 7.298] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.597 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.092 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.815 ±(99.9%) 0.006 ms/op
Iteration   1: 4.752 ±(99.9%) 0.005 ms/op
Iteration   2: 4.847 ±(99.9%) 0.004 ms/op
Iteration   3: 4.809 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.803 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (4.752, 4.803, 4.847), stdev = 0.048
  CI (99.9%): [3.924, 5.681] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.562 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 6.759 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.287 ±(99.9%) 0.031 ms/op
Iteration   1: 6.265 ±(99.9%) 0.018 ms/op
Iteration   2: 6.252 ±(99.9%) 0.017 ms/op
Iteration   3: 6.132 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.216 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (6.132, 6.216, 6.265), stdev = 0.073
  CI (99.9%): [4.880, 7.553] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.462 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.261 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.992 ±(99.9%) 0.018 ms/op
Iteration   1: 4.881 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   4.719 ms/op
                 createUser·p0.90:   6.250 ms/op
                 createUser·p0.95:   6.816 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  16.187 ms/op
                 createUser·p0.9999: 20.527 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   2: 4.919 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.439 ms/op
                 createUser·p0.50:   4.735 ms/op
                 createUser·p0.90:   6.382 ms/op
                 createUser·p0.95:   7.004 ms/op
                 createUser·p0.99:   9.372 ms/op
                 createUser·p0.999:  16.023 ms/op
                 createUser·p0.9999: 20.726 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 4.741 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   4.579 ms/op
                 createUser·p0.90:   6.062 ms/op
                 createUser·p0.95:   6.717 ms/op
                 createUser·p0.99:   9.568 ms/op
                 createUser·p0.999:  18.412 ms/op
                 createUser·p0.9999: 25.829 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 198069
  mean =      4.846 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4231 
    [ 2.500,  5.000) = 119786 
    [ 5.000,  7.500) = 68578 
    [ 7.500, 10.000) = 4103 
    [10.000, 12.500) = 816 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.242 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     17.161 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     26.281 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.730 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.874 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.543 ±(99.9%) 0.014 ms/op
Iteration   1: 4.394 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   4.268 ms/op
                 existUser·p0.90:   5.579 ms/op
                 existUser·p0.95:   6.267 ms/op
                 existUser·p0.99:   8.852 ms/op
                 existUser·p0.999:  16.306 ms/op
                 existUser·p0.9999: 21.126 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 4.417 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   4.243 ms/op
                 existUser·p0.90:   5.652 ms/op
                 existUser·p0.95:   6.365 ms/op
                 existUser·p0.99:   9.093 ms/op
                 existUser·p0.999:  13.599 ms/op
                 existUser·p0.9999: 30.671 ms/op
                 existUser·p1.00:   30.835 ms/op

Iteration   3: 4.346 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.415 ms/op
                 existUser·p0.95:   6.038 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  14.762 ms/op
                 existUser·p0.9999: 23.602 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 218856
  mean =      4.385 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8780 
    [ 2.500,  5.000) = 167959 
    [ 5.000,  7.500) = 37591 
    [ 7.500, 10.000) = 3331 
    [10.000, 12.500) = 687 
    [12.500, 15.000) = 313 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.554 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     30.249 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.894 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.965 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.871 ±(99.9%) 0.019 ms/op
Iteration   1: 4.860 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   4.661 ms/op
                 getUser·p0.90:   6.210 ms/op
                 getUser·p0.95:   6.947 ms/op
                 getUser·p0.99:   9.493 ms/op
                 getUser·p0.999:  12.798 ms/op
                 getUser·p0.9999: 17.787 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   2: 4.735 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   4.588 ms/op
                 getUser·p0.90:   5.956 ms/op
                 getUser·p0.95:   6.570 ms/op
                 getUser·p0.99:   9.172 ms/op
                 getUser·p0.999:  17.450 ms/op
                 getUser·p0.9999: 32.080 ms/op
                 getUser·p1.00:   32.342 ms/op

Iteration   3: 4.679 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   4.538 ms/op
                 getUser·p0.90:   5.874 ms/op
                 getUser·p0.95:   6.480 ms/op
                 getUser·p0.99:   8.520 ms/op
                 getUser·p0.999:  12.118 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 201858
  mean =      4.757 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4454 
    [ 2.500,  5.000) = 133082 
    [ 5.000,  7.500) = 59005 
    [ 7.500, 10.000) = 4141 
    [10.000, 12.500) = 815 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.660 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     31.183 ms/op
     p(99.9990) =     32.276 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.374 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 6.987 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.521 ±(99.9%) 0.032 ms/op
Iteration   1: 6.320 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   8.552 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   12.567 ms/op
                 listUser·p0.999:  19.037 ms/op
                 listUser·p0.9999: 29.714 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   2: 6.185 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   8.487 ms/op
                 listUser·p0.95:   9.617 ms/op
                 listUser·p0.99:   12.583 ms/op
                 listUser·p0.999:  21.540 ms/op
                 listUser·p0.9999: 28.175 ms/op
                 listUser·p1.00:   33.489 ms/op

Iteration   3: 6.303 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   8.684 ms/op
                 listUser·p0.95:   9.755 ms/op
                 listUser·p0.99:   12.610 ms/op
                 listUser·p0.999:  25.716 ms/op
                 listUser·p0.9999: 35.848 ms/op
                 listUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 153020
  mean =      6.269 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 137 
    [ 2.500,  5.000) = 32914 
    [ 5.000,  7.500) = 91419 
    [ 7.500, 10.000) = 22171 
    [10.000, 12.500) = 4763 
    [12.500, 15.000) = 1014 
    [15.000, 17.500) = 310 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      5.849 ms/op
     p(90.0000) =      8.569 ms/op
     p(95.0000) =      9.699 ms/op
     p(99.0000) =     12.599 ms/op
     p(99.9000) =     21.658 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     36.072 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.604 ± 1.965  ops/ms
ClientGrpc.existUser                       thrpt       3   7.313 ± 3.078  ops/ms
ClientGrpc.getUser                         thrpt       3   6.875 ± 1.610  ops/ms
ClientGrpc.listUser                        thrpt       3   5.225 ± 1.511  ops/ms
ClientGrpc.createUser                       avgt       3   4.611 ± 0.640   ms/op
ClientGrpc.existUser                        avgt       3   4.370 ± 2.928   ms/op
ClientGrpc.getUser                          avgt       3   4.803 ± 0.879   ms/op
ClientGrpc.listUser                         avgt       3   6.216 ± 1.337   ms/op
ClientGrpc.createUser                     sample  198069   4.846 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.439           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.242           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.857           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.322           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.161           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.526           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.313           ms/op
ClientGrpc.existUser                      sample  218856   4.385 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.893           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.554           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.218           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.929           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.762           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.249           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.835           ms/op
ClientGrpc.getUser                        sample  201858   4.757 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.945           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.021           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.660           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.093           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.008           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.183           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.342           ms/op
ClientGrpc.listUser                       sample  153020   6.269 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.260           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.569           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.699           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.599           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.658           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.521           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.176           ms/op
