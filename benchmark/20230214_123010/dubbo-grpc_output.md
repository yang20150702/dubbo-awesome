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
# Warmup Iteration   1: 3.358 ops/ms
# Warmup Iteration   2: 7.072 ops/ms
# Warmup Iteration   3: 8.283 ops/ms
Iteration   1: 8.300 ops/ms
Iteration   2: 8.257 ops/ms
Iteration   3: 8.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.284 ±(99.9%) 0.426 ops/ms [Average]
  (min, avg, max) = (8.257, 8.284, 8.300), stdev = 0.023
  CI (99.9%): [7.858, 8.710] (assumes normal distribution)


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
# Warmup Iteration   1: 5.942 ops/ms
# Warmup Iteration   2: 8.363 ops/ms
# Warmup Iteration   3: 8.858 ops/ms
Iteration   1: 8.679 ops/ms
Iteration   2: 9.206 ops/ms
Iteration   3: 8.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.834 ±(99.9%) 5.909 ops/ms [Average]
  (min, avg, max) = (8.616, 8.834, 9.206), stdev = 0.324
  CI (99.9%): [2.925, 14.743] (assumes normal distribution)


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
# Warmup Iteration   1: 5.311 ops/ms
# Warmup Iteration   2: 8.071 ops/ms
# Warmup Iteration   3: 8.404 ops/ms
Iteration   1: 8.301 ops/ms
Iteration   2: 8.371 ops/ms
Iteration   3: 8.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.340 ±(99.9%) 0.652 ops/ms [Average]
  (min, avg, max) = (8.301, 8.340, 8.371), stdev = 0.036
  CI (99.9%): [7.688, 8.993] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.463 ops/ms
# Warmup Iteration   2: 6.290 ops/ms
# Warmup Iteration   3: 6.595 ops/ms
Iteration   1: 6.743 ops/ms
Iteration   2: 6.635 ops/ms
Iteration   3: 6.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.667 ±(99.9%) 1.191 ops/ms [Average]
  (min, avg, max) = (6.625, 6.667, 6.743), stdev = 0.065
  CI (99.9%): [5.476, 7.859] (assumes normal distribution)


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
# Warmup Iteration   1: 5.271 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.010 ms/op
Iteration   1: 3.744 ±(99.9%) 0.003 ms/op
Iteration   2: 3.661 ±(99.9%) 0.003 ms/op
Iteration   3: 3.850 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.752 ±(99.9%) 1.732 ms/op [Average]
  (min, avg, max) = (3.661, 3.752, 3.850), stdev = 0.095
  CI (99.9%): [2.020, 5.484] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.856 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.003 ms/op
Iteration   1: 3.658 ±(99.9%) 0.004 ms/op
Iteration   2: 3.676 ±(99.9%) 0.003 ms/op
Iteration   3: 3.712 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.682 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.658, 3.682, 3.712), stdev = 0.027
  CI (99.9%): [3.181, 4.184] (assumes normal distribution)


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
# Warmup Iteration   1: 5.227 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.003 ms/op
Iteration   1: 3.895 ±(99.9%) 0.003 ms/op
Iteration   2: 3.853 ±(99.9%) 0.003 ms/op
Iteration   3: 3.793 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.847 ±(99.9%) 0.937 ms/op [Average]
  (min, avg, max) = (3.793, 3.847, 3.895), stdev = 0.051
  CI (99.9%): [2.910, 4.784] (assumes normal distribution)


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
# Warmup Iteration   1: 7.090 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.090 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.875 ±(99.9%) 0.011 ms/op
Iteration   1: 4.737 ±(99.9%) 0.013 ms/op
Iteration   2: 4.804 ±(99.9%) 0.006 ms/op
Iteration   3: 4.742 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.761 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (4.737, 4.761, 4.804), stdev = 0.037
  CI (99.9%): [4.084, 5.438] (assumes normal distribution)


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
# Warmup Iteration   1: 5.389 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.010 ms/op
Iteration   1: 3.765 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.018 ms/op
                 createUser·p0.999:  9.408 ms/op
                 createUser·p0.9999: 19.235 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.756 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  9.763 ms/op
                 createUser·p0.9999: 19.381 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   3: 3.821 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  12.384 ms/op
                 createUser·p0.9999: 24.957 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253610
  mean =      3.781 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7688 
    [ 2.500,  5.000) = 235349 
    [ 5.000,  7.500) = 9787 
    [ 7.500, 10.000) = 530 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     10.033 ms/op
     p(99.9900) =     23.799 ms/op
     p(99.9990) =     26.620 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.738 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.009 ms/op
Iteration   1: 3.564 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   5.585 ms/op
                 existUser·p0.999:  8.086 ms/op
                 existUser·p0.9999: 14.042 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 3.624 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  10.756 ms/op
                 existUser·p0.9999: 17.170 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   3: 3.607 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.329 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  9.224 ms/op
                 existUser·p0.9999: 20.713 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266779
  mean =      3.598 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19321 
    [ 2.500,  5.000) = 241539 
    [ 5.000,  7.500) = 5212 
    [ 7.500, 10.000) = 481 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     19.977 ms/op
     p(99.9990) =     21.736 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 5.580 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.010 ms/op
Iteration   1: 3.782 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  11.164 ms/op
                 getUser·p0.9999: 23.235 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   2: 4.058 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  12.726 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   3: 3.902 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  15.647 ms/op
                 getUser·p0.9999: 28.528 ms/op
                 getUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 245395
  mean =      3.911 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5507 
    [ 2.500,  5.000) = 221203 
    [ 5.000,  7.500) = 17336 
    [ 7.500, 10.000) = 941 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     12.547 ms/op
     p(99.9900) =     27.820 ms/op
     p(99.9990) =     29.068 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 6.685 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.099 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.826 ±(99.9%) 0.013 ms/op
Iteration   1: 4.935 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.349 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  16.025 ms/op
                 listUser·p0.9999: 23.662 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 4.759 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  16.402 ms/op
                 listUser·p0.9999: 19.089 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 4.867 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.701 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  19.671 ms/op
                 listUser·p0.9999: 24.899 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197709
  mean =      4.853 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 351 
    [ 2.500,  5.000) = 138194 
    [ 5.000,  7.500) = 54064 
    [ 7.500, 10.000) = 4381 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.152 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     23.605 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.284 ± 0.426  ops/ms
ClientGrpc.existUser                       thrpt       3   8.834 ± 5.909  ops/ms
ClientGrpc.getUser                         thrpt       3   8.340 ± 0.652  ops/ms
ClientGrpc.listUser                        thrpt       3   6.667 ± 1.191  ops/ms
ClientGrpc.createUser                       avgt       3   3.752 ± 1.732   ms/op
ClientGrpc.existUser                        avgt       3   3.682 ± 0.502   ms/op
ClientGrpc.getUser                          avgt       3   3.847 ± 0.937   ms/op
ClientGrpc.listUser                         avgt       3   4.761 ± 0.677   ms/op
ClientGrpc.createUser                     sample  253610   3.781 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.746           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.915           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.033           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.799           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.673           ms/op
ClientGrpc.existUser                      sample  266779   3.598 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.329           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.702           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.355           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.977           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.086           ms/op
ClientGrpc.getUser                        sample  245395   3.911 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.806           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.801           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.791           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.547           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.820           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.196           ms/op
ClientGrpc.listUser                       sample  197709   4.853 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.100           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.152           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.471           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.605           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.231           ms/op
