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
# Warmup Iteration   1: 3.079 ops/ms
# Warmup Iteration   2: 6.799 ops/ms
# Warmup Iteration   3: 8.191 ops/ms
Iteration   1: 8.636 ops/ms
Iteration   2: 8.794 ops/ms
Iteration   3: 8.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.652 ±(99.9%) 2.440 ops/ms [Average]
  (min, avg, max) = (8.528, 8.652, 8.794), stdev = 0.134
  CI (99.9%): [6.212, 11.093] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.738 ops/ms
# Warmup Iteration   2: 8.678 ops/ms
# Warmup Iteration   3: 9.204 ops/ms
Iteration   1: 9.076 ops/ms
Iteration   2: 9.026 ops/ms
Iteration   3: 8.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.004 ±(99.9%) 1.563 ops/ms [Average]
  (min, avg, max) = (8.909, 9.004, 9.076), stdev = 0.086
  CI (99.9%): [7.441, 10.567] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.338 ops/ms
# Warmup Iteration   2: 8.306 ops/ms
# Warmup Iteration   3: 8.457 ops/ms
Iteration   1: 8.542 ops/ms
Iteration   2: 8.450 ops/ms
Iteration   3: 8.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.435 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (8.314, 8.435, 8.542), stdev = 0.115
  CI (99.9%): [6.343, 10.528] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.013 ops/ms
# Warmup Iteration   2: 6.332 ops/ms
# Warmup Iteration   3: 7.008 ops/ms
Iteration   1: 6.700 ops/ms
Iteration   2: 6.860 ops/ms
Iteration   3: 6.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.853 ±(99.9%) 2.712 ops/ms [Average]
  (min, avg, max) = (6.700, 6.853, 6.997), stdev = 0.149
  CI (99.9%): [4.141, 9.564] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.187 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.009 ms/op
Iteration   1: 3.542 ±(99.9%) 0.008 ms/op
Iteration   2: 3.583 ±(99.9%) 0.004 ms/op
Iteration   3: 3.617 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.581 ±(99.9%) 0.683 ms/op [Average]
  (min, avg, max) = (3.542, 3.581, 3.617), stdev = 0.037
  CI (99.9%): [2.897, 4.264] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.536 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.002 ms/op
Iteration   1: 3.391 ±(99.9%) 0.004 ms/op
Iteration   2: 3.430 ±(99.9%) 0.002 ms/op
Iteration   3: 3.466 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.429 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (3.391, 3.429, 3.466), stdev = 0.038
  CI (99.9%): [2.744, 4.114] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.160 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.004 ms/op
Iteration   1: 3.688 ±(99.9%) 0.004 ms/op
Iteration   2: 3.584 ±(99.9%) 0.004 ms/op
Iteration   3: 3.603 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.625 ±(99.9%) 1.007 ms/op [Average]
  (min, avg, max) = (3.584, 3.625, 3.688), stdev = 0.055
  CI (99.9%): [2.618, 4.632] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.151 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.966 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.621 ±(99.9%) 0.019 ms/op
Iteration   1: 4.517 ±(99.9%) 0.020 ms/op
Iteration   2: 4.631 ±(99.9%) 0.016 ms/op
Iteration   3: 4.759 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.635 ±(99.9%) 2.205 ms/op [Average]
  (min, avg, max) = (4.517, 4.635, 4.759), stdev = 0.121
  CI (99.9%): [2.430, 6.840] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.255 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.010 ms/op
Iteration   1: 3.677 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  13.008 ms/op
                 createUser·p0.9999: 19.900 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   2: 3.685 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  11.817 ms/op
                 createUser·p0.9999: 32.877 ms/op
                 createUser·p1.00:   33.161 ms/op

Iteration   3: 3.735 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  17.753 ms/op
                 createUser·p0.9999: 25.133 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259387
  mean =      3.699 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5635 
    [ 2.500,  5.000) = 245298 
    [ 5.000,  7.500) = 7196 
    [ 7.500, 10.000) = 827 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     12.282 ms/op
     p(99.9900) =     32.442 ms/op
     p(99.9990) =     33.076 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.928 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.009 ms/op
Iteration   1: 3.449 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  9.917 ms/op
                 existUser·p0.9999: 24.108 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   2: 3.538 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  9.724 ms/op
                 existUser·p0.9999: 37.877 ms/op
                 existUser·p1.00:   41.681 ms/op

Iteration   3: 3.634 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   7.037 ms/op
                 existUser·p0.999:  15.418 ms/op
                 existUser·p0.9999: 25.277 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271171
  mean =      3.539 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 263806 
    [ 5.000, 10.000) = 6868 
    [10.000, 15.000) = 309 
    [15.000, 20.000) = 41 
    [20.000, 25.000) = 102 
    [25.000, 30.000) = 13 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     38.585 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.923 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.011 ms/op
Iteration   1: 3.673 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 19.431 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   2: 3.587 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  11.272 ms/op
                 getUser·p0.9999: 22.326 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.791 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  10.224 ms/op
                 getUser·p0.9999: 18.780 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260538
  mean =      3.682 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7125 
    [ 2.500,  5.000) = 244431 
    [ 5.000,  7.500) = 7846 
    [ 7.500, 10.000) = 904 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =      9.854 ms/op
     p(99.9900) =     20.871 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 6.361 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.106 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.623 ±(99.9%) 0.014 ms/op
Iteration   1: 4.526 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.537 ms/op
                 listUser·p0.99:   8.368 ms/op
                 listUser·p0.999:  15.461 ms/op
                 listUser·p0.9999: 17.789 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   2: 4.610 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   4.444 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.382 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 18.422 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 4.775 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.988 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  19.694 ms/op
                 listUser·p0.9999: 24.094 ms/op
                 listUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206935
  mean =      4.635 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 201 
    [ 2.500,  5.000) = 165253 
    [ 5.000,  7.500) = 37226 
    [ 7.500, 10.000) = 3514 
    [10.000, 12.500) = 374 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.529 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     23.439 ms/op
     p(99.9990) =     26.122 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.652 ± 2.440  ops/ms
ClientGrpc.existUser                       thrpt       3   9.004 ± 1.563  ops/ms
ClientGrpc.getUser                         thrpt       3   8.435 ± 2.093  ops/ms
ClientGrpc.listUser                        thrpt       3   6.853 ± 2.712  ops/ms
ClientGrpc.createUser                       avgt       3   3.581 ± 0.683   ms/op
ClientGrpc.existUser                        avgt       3   3.429 ± 0.685   ms/op
ClientGrpc.getUser                          avgt       3   3.625 ± 1.007   ms/op
ClientGrpc.listUser                         avgt       3   4.635 ± 2.205   ms/op
ClientGrpc.createUser                     sample  259387   3.699 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.723           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.275           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.282           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.442           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.161           ms/op
ClientGrpc.existUser                      sample  271171   3.539 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.654           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.193           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.304           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          36.045           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          41.681           ms/op
ClientGrpc.getUser                        sample  260538   3.682 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.940           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.267           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.854           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.871           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.167           ms/op
ClientGrpc.listUser                       sample  206935   4.635 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.323           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.439           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.608           ms/op
