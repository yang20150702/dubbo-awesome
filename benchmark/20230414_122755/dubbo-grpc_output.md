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
# Warmup Iteration   1: 3.839 ops/ms
# Warmup Iteration   2: 8.533 ops/ms
# Warmup Iteration   3: 10.130 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.534 ±(99.9%) 1.234 ops/ms [Average]
  (min, avg, max) = (10.459, 10.534, 10.590), stdev = 0.068
  CI (99.9%): [9.300, 11.767] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.436 ops/ms
# Warmup Iteration   2: 10.468 ops/ms
# Warmup Iteration   3: 10.974 ops/ms
Iteration   1: 10.609 ops/ms
Iteration   2: 10.700 ops/ms
Iteration   3: 10.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.739 ±(99.9%) 2.799 ops/ms [Average]
  (min, avg, max) = (10.609, 10.739, 10.908), stdev = 0.153
  CI (99.9%): [7.940, 13.538] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.726 ops/ms
# Warmup Iteration   2: 10.131 ops/ms
# Warmup Iteration   3: 10.228 ops/ms
Iteration   1: 10.305 ops/ms
Iteration   2: 10.433 ops/ms
Iteration   3: 10.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.372 ±(99.9%) 1.168 ops/ms [Average]
  (min, avg, max) = (10.305, 10.372, 10.433), stdev = 0.064
  CI (99.9%): [9.204, 11.540] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.307 ops/ms
# Warmup Iteration   2: 7.415 ops/ms
# Warmup Iteration   3: 7.886 ops/ms
Iteration   1: 7.838 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 8.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.985 ±(99.9%) 3.582 ops/ms [Average]
  (min, avg, max) = (7.838, 7.985, 8.208), stdev = 0.196
  CI (99.9%): [4.403, 11.567] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.359 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.001 ms/op
Iteration   1: 3.140 ±(99.9%) 0.002 ms/op
Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
Iteration   3: 3.122 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.126 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (3.117, 3.126, 3.140), stdev = 0.012
  CI (99.9%): [2.903, 3.350] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.004 ms/op
Iteration   1: 2.937 ±(99.9%) 0.003 ms/op
Iteration   2: 2.848 ±(99.9%) 0.002 ms/op
Iteration   3: 2.910 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.898 ±(99.9%) 0.840 ms/op [Average]
  (min, avg, max) = (2.848, 2.898, 2.937), stdev = 0.046
  CI (99.9%): [2.058, 3.738] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.002 ms/op
Iteration   1: 3.067 ±(99.9%) 0.002 ms/op
Iteration   2: 3.065 ±(99.9%) 0.002 ms/op
Iteration   3: 3.042 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.058 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (3.042, 3.058, 3.067), stdev = 0.014
  CI (99.9%): [2.804, 3.312] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.561 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.016 ms/op
Iteration   1: 4.101 ±(99.9%) 0.022 ms/op
Iteration   2: 4.025 ±(99.9%) 0.021 ms/op
Iteration   3: 3.928 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.018 ±(99.9%) 1.581 ms/op [Average]
  (min, avg, max) = (3.928, 4.018, 4.101), stdev = 0.087
  CI (99.9%): [2.438, 5.599] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.388 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
Iteration   1: 3.146 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.246 ms/op
                 createUser·p0.9999: 16.742 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  8.034 ms/op
                 createUser·p0.9999: 19.923 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  11.440 ms/op
                 createUser·p0.9999: 28.624 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310022
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20940 
    [ 2.500,  5.000) = 287481 
    [ 5.000,  7.500) = 1204 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     31.614 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.219 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
Iteration   1: 2.926 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  5.792 ms/op
                 existUser·p0.9999: 18.680 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  7.432 ms/op
                 existUser·p0.9999: 20.316 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.444 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  10.220 ms/op
                 existUser·p0.9999: 16.330 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325159
  mean =      2.953 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30556 
    [ 2.500,  5.000) = 293375 
    [ 5.000,  7.500) = 855 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.927 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.450 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 3.112 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.567 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  9.777 ms/op
                 getUser·p0.9999: 26.706 ms/op
                 getUser·p1.00:   27.066 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.526 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.386 ms/op
                 getUser·p0.999:  6.714 ms/op
                 getUser·p0.9999: 32.014 ms/op
                 getUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309394
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13185 
    [ 2.500,  5.000) = 294100 
    [ 5.000,  7.500) = 1632 
    [ 7.500, 10.000) = 247 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.621 ms/op
     p(99.9000) =      8.361 ms/op
     p(99.9900) =     31.336 ms/op
     p(99.9990) =     32.798 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 5.421 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.300 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.011 ms/op
Iteration   1: 4.071 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  15.736 ms/op
                 listUser·p0.9999: 22.151 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 4.022 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  22.166 ms/op
                 listUser·p0.9999: 25.987 ms/op
                 listUser·p1.00:   30.114 ms/op

Iteration   3: 4.055 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236952
  mean =      4.049 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2323 
    [ 2.500,  5.000) = 210291 
    [ 5.000,  7.500) = 22806 
    [ 7.500, 10.000) = 986 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     16.385 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     26.170 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.534 ± 1.234  ops/ms
ClientGrpc.existUser                       thrpt       3  10.739 ± 2.799  ops/ms
ClientGrpc.getUser                         thrpt       3  10.372 ± 1.168  ops/ms
ClientGrpc.listUser                        thrpt       3   7.985 ± 3.582  ops/ms
ClientGrpc.createUser                       avgt       3   3.126 ± 0.224   ms/op
ClientGrpc.existUser                        avgt       3   2.898 ± 0.840   ms/op
ClientGrpc.getUser                          avgt       3   3.058 ± 0.254   ms/op
ClientGrpc.listUser                         avgt       3   4.018 ± 1.581   ms/op
ClientGrpc.createUser                     sample  310022   3.097 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.624           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.086           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.066           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.752           ms/op
ClientGrpc.existUser                      sample  325159   2.953 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.444           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.927           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.202           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.873           ms/op
ClientGrpc.getUser                        sample  309394   3.100 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.567           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.621           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.361           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.336           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.620           ms/op
ClientGrpc.listUser                       sample  236952   4.049 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.026           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.385           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.559           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.114           ms/op
