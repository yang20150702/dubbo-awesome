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
# Warmup Iteration   1: 4.357 ops/ms
# Warmup Iteration   2: 9.414 ops/ms
# Warmup Iteration   3: 10.395 ops/ms
Iteration   1: 10.337 ops/ms
Iteration   2: 10.444 ops/ms
Iteration   3: 10.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.497 ±(99.9%) 3.477 ops/ms [Average]
  (min, avg, max) = (10.337, 10.497, 10.708), stdev = 0.191
  CI (99.9%): [7.019, 13.974] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.110 ops/ms
# Warmup Iteration   2: 10.921 ops/ms
# Warmup Iteration   3: 11.393 ops/ms
Iteration   1: 11.168 ops/ms
Iteration   2: 11.315 ops/ms
Iteration   3: 11.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.180 ±(99.9%) 2.360 ops/ms [Average]
  (min, avg, max) = (11.058, 11.180, 11.315), stdev = 0.129
  CI (99.9%): [8.821, 13.540] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.478 ops/ms
# Warmup Iteration   2: 10.530 ops/ms
# Warmup Iteration   3: 10.794 ops/ms
Iteration   1: 10.681 ops/ms
Iteration   2: 10.867 ops/ms
Iteration   3: 10.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.741 ±(99.9%) 1.989 ops/ms [Average]
  (min, avg, max) = (10.674, 10.741, 10.867), stdev = 0.109
  CI (99.9%): [8.752, 12.729] (assumes normal distribution)


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
# Warmup Iteration   1: 6.395 ops/ms
# Warmup Iteration   2: 8.134 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.279 ops/ms
Iteration   2: 8.110 ops/ms
Iteration   3: 8.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.250 ±(99.9%) 2.342 ops/ms [Average]
  (min, avg, max) = (8.110, 8.250, 8.361), stdev = 0.128
  CI (99.9%): [5.908, 10.592] (assumes normal distribution)


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.008 ms/op
Iteration   1: 3.000 ±(99.9%) 0.003 ms/op
Iteration   2: 2.993 ±(99.9%) 0.003 ms/op
Iteration   3: 2.975 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.989 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (2.975, 2.989, 3.000), stdev = 0.013
  CI (99.9%): [2.755, 3.224] (assumes normal distribution)


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.948 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.003 ms/op
Iteration   1: 2.861 ±(99.9%) 0.003 ms/op
Iteration   2: 2.814 ±(99.9%) 0.004 ms/op
Iteration   3: 2.824 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.833 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (2.814, 2.833, 2.861), stdev = 0.025
  CI (99.9%): [2.386, 3.280] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.873 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.934 ±(99.9%) 0.005 ms/op
Iteration   3: 2.982 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.968 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (2.934, 2.968, 2.988), stdev = 0.030
  CI (99.9%): [2.422, 3.514] (assumes normal distribution)


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
# Warmup Iteration   1: 4.610 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.028 ms/op
Iteration   1: 3.783 ±(99.9%) 0.008 ms/op
Iteration   2: 3.860 ±(99.9%) 0.031 ms/op
Iteration   3: 3.828 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.824 ±(99.9%) 0.705 ms/op [Average]
  (min, avg, max) = (3.783, 3.824, 3.860), stdev = 0.039
  CI (99.9%): [3.118, 4.529] (assumes normal distribution)


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.445 ms/op
                 createUser·p0.999:  7.487 ms/op
                 createUser·p0.9999: 11.702 ms/op
                 createUser·p1.00:   12.206 ms/op

Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.699 ms/op
                 createUser·p0.9999: 12.784 ms/op
                 createUser·p1.00:   13.681 ms/op

Iteration   3: 2.934 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  8.287 ms/op
                 createUser·p0.9999: 25.526 ms/op
                 createUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321738
  mean =      2.984 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31195 
    [ 2.500,  5.000) = 289113 
    [ 5.000,  7.500) = 961 
    [ 7.500, 10.000) = 212 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.350 ms/op
     p(99.9900) =     23.375 ms/op
     p(99.9990) =     25.709 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.849 ±(99.9%) 0.006 ms/op
Iteration   1: 2.875 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.330 ms/op
                 existUser·p0.9999: 11.610 ms/op
                 existUser·p1.00:   11.977 ms/op

Iteration   2: 2.918 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 13.255 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   3: 2.832 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.931 ms/op
                 existUser·p0.9999: 15.492 ms/op
                 existUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333999
  mean =      2.874 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2419 
    [ 1.250,  2.500) = 40706 
    [ 2.500,  3.750) = 281946 
    [ 3.750,  5.000) = 8105 
    [ 5.000,  6.250) = 372 
    [ 6.250,  7.500) = 131 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     13.851 ms/op
     p(99.9990) =     15.936 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  9.219 ms/op
                 getUser·p0.9999: 11.801 ms/op
                 getUser·p1.00:   12.075 ms/op

Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.547 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  8.364 ms/op
                 getUser·p0.9999: 16.204 ms/op
                 getUser·p1.00:   16.581 ms/op

Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.271 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.357 ms/op
                 getUser·p0.9999: 23.658 ms/op
                 getUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321596
  mean =      2.984 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32525 
    [ 2.500,  5.000) = 287881 
    [ 5.000,  7.500) = 798 
    [ 7.500, 10.000) = 168 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.271 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.364 ms/op
     p(99.9900) =     21.974 ms/op
     p(99.9990) =     24.173 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.010 ms/op
Iteration   1: 3.789 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  11.908 ms/op
                 listUser·p0.9999: 14.844 ms/op
                 listUser·p1.00:   15.942 ms/op

Iteration   2: 3.780 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.755 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  13.417 ms/op
                 listUser·p0.9999: 19.696 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   3: 3.799 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.296 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.428 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.137 ms/op
                 listUser·p0.9999: 18.866 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253445
  mean =      3.789 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4035 
    [ 2.500,  5.000) = 232964 
    [ 5.000,  7.500) = 15328 
    [ 7.500, 10.000) = 686 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.296 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     19.376 ms/op
     p(99.9990) =     20.082 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.497 ± 3.477  ops/ms
ClientGrpc.existUser                       thrpt       3  11.180 ± 2.360  ops/ms
ClientGrpc.getUser                         thrpt       3  10.741 ± 1.989  ops/ms
ClientGrpc.listUser                        thrpt       3   8.250 ± 2.342  ops/ms
ClientGrpc.createUser                       avgt       3   2.989 ± 0.235   ms/op
ClientGrpc.existUser                        avgt       3   2.833 ± 0.447   ms/op
ClientGrpc.getUser                          avgt       3   2.968 ± 0.546   ms/op
ClientGrpc.listUser                         avgt       3   3.824 ± 0.705   ms/op
ClientGrpc.createUser                     sample  321738   2.984 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.662           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.350           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.375           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.821           ms/op
ClientGrpc.existUser                      sample  333999   2.874 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.629           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.152           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.851           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.040           ms/op
ClientGrpc.getUser                        sample  321596   2.984 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.271           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.364           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.974           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.969           ms/op
ClientGrpc.listUser                       sample  253445   3.789 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.296           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.674           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.402           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.376           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.185           ms/op
