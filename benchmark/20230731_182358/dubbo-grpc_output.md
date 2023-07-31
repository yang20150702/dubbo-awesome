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
# Warmup Iteration   1: 2.797 ops/ms
# Warmup Iteration   2: 6.759 ops/ms
# Warmup Iteration   3: 8.059 ops/ms
Iteration   1: 8.336 ops/ms
Iteration   2: 8.791 ops/ms
Iteration   3: 8.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.607 ±(99.9%) 4.370 ops/ms [Average]
  (min, avg, max) = (8.336, 8.607, 8.791), stdev = 0.240
  CI (99.9%): [4.237, 12.977] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.325 ops/ms
# Warmup Iteration   2: 8.063 ops/ms
# Warmup Iteration   3: 9.179 ops/ms
Iteration   1: 9.101 ops/ms
Iteration   2: 9.304 ops/ms
Iteration   3: 9.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.145 ±(99.9%) 2.600 ops/ms [Average]
  (min, avg, max) = (9.030, 9.145, 9.304), stdev = 0.142
  CI (99.9%): [6.545, 11.744] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.296 ops/ms
# Warmup Iteration   2: 7.978 ops/ms
# Warmup Iteration   3: 8.538 ops/ms
Iteration   1: 8.113 ops/ms
Iteration   2: 8.399 ops/ms
Iteration   3: 8.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.335 ±(99.9%) 3.608 ops/ms [Average]
  (min, avg, max) = (8.113, 8.335, 8.492), stdev = 0.198
  CI (99.9%): [4.727, 11.943] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.012 ops/ms
# Warmup Iteration   2: 6.205 ops/ms
# Warmup Iteration   3: 6.727 ops/ms
Iteration   1: 6.791 ops/ms
Iteration   2: 6.806 ops/ms
Iteration   3: 6.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.719 ±(99.9%) 2.512 ops/ms [Average]
  (min, avg, max) = (6.560, 6.719, 6.806), stdev = 0.138
  CI (99.9%): [4.207, 9.231] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.634 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.007 ms/op
Iteration   1: 3.769 ±(99.9%) 0.003 ms/op
Iteration   2: 3.785 ±(99.9%) 0.003 ms/op
Iteration   3: 3.743 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.766 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.743, 3.766, 3.785), stdev = 0.021
  CI (99.9%): [3.381, 4.151] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.070 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.002 ms/op
Iteration   1: 3.454 ±(99.9%) 0.003 ms/op
Iteration   2: 3.546 ±(99.9%) 0.004 ms/op
Iteration   3: 3.479 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.493 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (3.454, 3.493, 3.546), stdev = 0.048
  CI (99.9%): [2.621, 4.365] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.765 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.003 ms/op
Iteration   1: 3.954 ±(99.9%) 0.004 ms/op
Iteration   2: 3.860 ±(99.9%) 0.003 ms/op
Iteration   3: 3.859 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.891 ±(99.9%) 0.993 ms/op [Average]
  (min, avg, max) = (3.859, 3.891, 3.954), stdev = 0.054
  CI (99.9%): [2.899, 4.884] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.632 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.314 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.927 ±(99.9%) 0.020 ms/op
Iteration   1: 5.034 ±(99.9%) 0.024 ms/op
Iteration   2: 5.056 ±(99.9%) 0.020 ms/op
Iteration   3: 4.846 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.979 ±(99.9%) 2.099 ms/op [Average]
  (min, avg, max) = (4.846, 4.979, 5.056), stdev = 0.115
  CI (99.9%): [2.879, 7.078] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.769 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.010 ms/op
Iteration   1: 3.829 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   8.176 ms/op
                 createUser·p0.999:  12.361 ms/op
                 createUser·p0.9999: 17.400 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   2: 3.818 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  14.170 ms/op
                 createUser·p0.9999: 23.777 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.697 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  13.427 ms/op
                 createUser·p0.9999: 20.898 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253898
  mean =      3.780 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10375 
    [ 2.500,  5.000) = 223067 
    [ 5.000,  7.500) = 17814 
    [ 7.500, 10.000) = 1679 
    [10.000, 12.500) = 571 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     23.416 ms/op
     p(99.9990) =     24.130 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 5.198 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.010 ms/op
Iteration   1: 3.635 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  12.387 ms/op
                 existUser·p0.9999: 17.072 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   2: 3.575 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  10.377 ms/op
                 existUser·p0.9999: 16.779 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   3: 3.456 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  10.067 ms/op
                 existUser·p0.9999: 20.218 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270064
  mean =      3.554 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10245 
    [ 2.500,  5.000) = 247974 
    [ 5.000,  7.500) = 10194 
    [ 7.500, 10.000) = 1254 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     10.976 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     20.467 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 5.619 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.015 ms/op
Iteration   1: 3.726 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   7.193 ms/op
                 getUser·p0.999:  12.854 ms/op
                 getUser·p0.9999: 17.053 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   2: 3.710 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  10.011 ms/op
                 getUser·p0.9999: 15.966 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   3: 3.678 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  12.638 ms/op
                 getUser·p0.9999: 21.463 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259034
  mean =      3.705 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11046 
    [ 2.500,  5.000) = 232195 
    [ 5.000,  7.500) = 14184 
    [ 7.500, 10.000) = 1238 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     10.960 ms/op
     p(99.9900) =     20.591 ms/op
     p(99.9990) =     21.883 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 7.468 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.749 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.006 ±(99.9%) 0.019 ms/op
Iteration   1: 4.878 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.341 ms/op
                 listUser·p0.95:   7.250 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  16.995 ms/op
                 listUser·p0.9999: 22.722 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   2: 4.882 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.512 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  18.418 ms/op
                 listUser·p0.9999: 29.455 ms/op
                 listUser·p1.00:   29.852 ms/op

Iteration   3: 4.857 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.742 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.586 ms/op
                 listUser·p0.95:   7.426 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  20.814 ms/op
                 listUser·p0.9999: 33.423 ms/op
                 listUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196980
  mean =      4.872 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 441 
    [ 2.500,  5.000) = 134712 
    [ 5.000,  7.500) = 52776 
    [ 7.500, 10.000) = 7527 
    [10.000, 12.500) = 995 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      6.521 ms/op
     p(95.0000) =      7.397 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     17.762 ms/op
     p(99.9900) =     32.558 ms/op
     p(99.9990) =     33.753 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.607 ± 4.370  ops/ms
ClientGrpc.existUser                       thrpt       3   9.145 ± 2.600  ops/ms
ClientGrpc.getUser                         thrpt       3   8.335 ± 3.608  ops/ms
ClientGrpc.listUser                        thrpt       3   6.719 ± 2.512  ops/ms
ClientGrpc.createUser                       avgt       3   3.766 ± 0.385   ms/op
ClientGrpc.existUser                        avgt       3   3.493 ± 0.872   ms/op
ClientGrpc.getUser                          avgt       3   3.891 ± 0.993   ms/op
ClientGrpc.listUser                         avgt       3   4.979 ± 2.099   ms/op
ClientGrpc.createUser                     sample  253898   3.780 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.831           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.586           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.238           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.416           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.281           ms/op
ClientGrpc.existUser                      sample  270064   3.554 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.750           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.685           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.976           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.497           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.611           ms/op
ClientGrpc.getUser                        sample  259034   3.705 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.871           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.889           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.960           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.591           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  196980   4.872 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.742           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.521           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.397           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.568           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.762           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.558           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.817           ms/op
