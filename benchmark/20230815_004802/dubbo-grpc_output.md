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
# Warmup Iteration   1: 3.262 ops/ms
# Warmup Iteration   2: 7.060 ops/ms
# Warmup Iteration   3: 8.225 ops/ms
Iteration   1: 8.853 ops/ms
Iteration   2: 8.652 ops/ms
Iteration   3: 8.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.739 ±(99.9%) 1.880 ops/ms [Average]
  (min, avg, max) = (8.652, 8.739, 8.853), stdev = 0.103
  CI (99.9%): [6.859, 10.619] (assumes normal distribution)


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
# Warmup Iteration   1: 5.908 ops/ms
# Warmup Iteration   2: 8.654 ops/ms
# Warmup Iteration   3: 9.160 ops/ms
Iteration   1: 9.288 ops/ms
Iteration   2: 9.228 ops/ms
Iteration   3: 9.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.252 ±(99.9%) 0.580 ops/ms [Average]
  (min, avg, max) = (9.228, 9.252, 9.288), stdev = 0.032
  CI (99.9%): [8.672, 9.832] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.745 ops/ms
# Warmup Iteration   2: 8.095 ops/ms
# Warmup Iteration   3: 8.654 ops/ms
Iteration   1: 8.843 ops/ms
Iteration   2: 8.859 ops/ms
Iteration   3: 8.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.821 ±(99.9%) 0.958 ops/ms [Average]
  (min, avg, max) = (8.761, 8.821, 8.859), stdev = 0.053
  CI (99.9%): [7.863, 9.779] (assumes normal distribution)


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
# Warmup Iteration   1: 4.426 ops/ms
# Warmup Iteration   2: 6.174 ops/ms
# Warmup Iteration   3: 6.601 ops/ms
Iteration   1: 6.647 ops/ms
Iteration   2: 6.574 ops/ms
Iteration   3: 6.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.630 ±(99.9%) 0.911 ops/ms [Average]
  (min, avg, max) = (6.574, 6.630, 6.670), stdev = 0.050
  CI (99.9%): [5.720, 7.541] (assumes normal distribution)


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
# Warmup Iteration   1: 5.189 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.026 ms/op
Iteration   1: 3.714 ±(99.9%) 0.004 ms/op
Iteration   2: 3.610 ±(99.9%) 0.004 ms/op
Iteration   3: 3.624 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.649 ±(99.9%) 1.028 ms/op [Average]
  (min, avg, max) = (3.610, 3.649, 3.714), stdev = 0.056
  CI (99.9%): [2.621, 4.677] (assumes normal distribution)


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
# Warmup Iteration   1: 4.965 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.004 ms/op
Iteration   1: 3.498 ±(99.9%) 0.002 ms/op
Iteration   2: 3.574 ±(99.9%) 0.002 ms/op
Iteration   3: 3.479 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.517 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (3.479, 3.517, 3.574), stdev = 0.050
  CI (99.9%): [2.599, 4.434] (assumes normal distribution)


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
# Warmup Iteration   1: 5.309 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.005 ms/op
Iteration   1: 3.688 ±(99.9%) 0.005 ms/op
Iteration   2: 3.671 ±(99.9%) 0.004 ms/op
Iteration   3: 3.705 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.688 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.671, 3.688, 3.705), stdev = 0.017
  CI (99.9%): [3.379, 3.997] (assumes normal distribution)


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
# Warmup Iteration   1: 6.609 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.169 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.930 ±(99.9%) 0.013 ms/op
Iteration   1: 4.855 ±(99.9%) 0.021 ms/op
Iteration   2: 4.844 ±(99.9%) 0.011 ms/op
Iteration   3: 4.803 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.834 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (4.803, 4.834, 4.855), stdev = 0.027
  CI (99.9%): [4.338, 5.329] (assumes normal distribution)


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
# Warmup Iteration   1: 5.125 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.008 ms/op
Iteration   1: 3.610 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  11.829 ms/op
                 createUser·p0.9999: 19.473 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   2: 3.695 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  11.272 ms/op
                 createUser·p0.9999: 16.553 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   3: 3.578 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  10.492 ms/op
                 createUser·p0.9999: 18.745 ms/op
                 createUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264800
  mean =      3.627 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8458 
    [ 2.500,  5.000) = 249381 
    [ 5.000,  7.500) = 5990 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     11.308 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     20.647 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 4.853 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.008 ms/op
Iteration   1: 3.478 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  12.523 ms/op
                 existUser·p0.9999: 18.711 ms/op
                 existUser·p1.00:   18.743 ms/op

Iteration   2: 3.416 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  8.542 ms/op
                 existUser·p0.9999: 15.510 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   3: 3.401 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  12.780 ms/op
                 existUser·p0.9999: 34.734 ms/op
                 existUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279734
  mean =      3.431 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15281 
    [ 2.500,  5.000) = 259889 
    [ 5.000,  7.500) = 3841 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     11.621 ms/op
     p(99.9900) =     34.018 ms/op
     p(99.9990) =     34.996 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 4.606 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.009 ms/op
Iteration   1: 3.708 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  13.218 ms/op
                 getUser·p0.9999: 15.249 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   2: 3.736 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.209 ms/op
                 getUser·p0.999:  8.179 ms/op
                 getUser·p0.9999: 18.252 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   3: 3.678 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 20.328 ms/op
                 getUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258820
  mean =      3.707 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7782 
    [ 2.500,  5.000) = 240707 
    [ 5.000,  7.500) = 9045 
    [ 7.500, 10.000) = 809 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     12.111 ms/op
     p(99.9900) =     19.665 ms/op
     p(99.9990) =     21.637 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 5.969 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.159 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.881 ±(99.9%) 0.015 ms/op
Iteration   1: 4.791 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   8.505 ms/op
                 listUser·p0.999:  16.840 ms/op
                 listUser·p0.9999: 23.898 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 4.787 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 19.868 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.855 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.078 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 28.338 ms/op
                 listUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199585
  mean =      4.811 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 403 
    [ 2.500,  5.000) = 149354 
    [ 5.000,  7.500) = 44429 
    [ 7.500, 10.000) = 4526 
    [10.000, 12.500) = 484 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     28.182 ms/op
     p(99.9990) =     28.509 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.739 ± 1.880  ops/ms
ClientGrpc.existUser                       thrpt       3   9.252 ± 0.580  ops/ms
ClientGrpc.getUser                         thrpt       3   8.821 ± 0.958  ops/ms
ClientGrpc.listUser                        thrpt       3   6.630 ± 0.911  ops/ms
ClientGrpc.createUser                       avgt       3   3.649 ± 1.028   ms/op
ClientGrpc.existUser                        avgt       3   3.517 ± 0.917   ms/op
ClientGrpc.getUser                          avgt       3   3.688 ± 0.309   ms/op
ClientGrpc.listUser                         avgt       3   4.834 ± 0.496   ms/op
ClientGrpc.createUser                     sample  264800   3.627 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.676           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.833           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.308           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.842           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.643           ms/op
ClientGrpc.existUser                      sample  279734   3.431 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.084           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.472           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.621           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          34.018           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.996           ms/op
ClientGrpc.getUser                        sample  258820   3.707 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.912           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.341           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.111           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.665           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.922           ms/op
ClientGrpc.listUser                       sample  199585   4.811 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.071           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.487           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.498           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.182           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.803           ms/op
