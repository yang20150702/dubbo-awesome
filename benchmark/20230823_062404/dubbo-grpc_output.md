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
# Warmup Iteration   1: 3.891 ops/ms
# Warmup Iteration   2: 8.666 ops/ms
# Warmup Iteration   3: 10.033 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.422 ops/ms
Iteration   3: 10.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.385 ±(99.9%) 1.785 ops/ms [Average]
  (min, avg, max) = (10.274, 10.385, 10.459), stdev = 0.098
  CI (99.9%): [8.600, 12.170] (assumes normal distribution)


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
# Warmup Iteration   1: 7.283 ops/ms
# Warmup Iteration   2: 10.736 ops/ms
# Warmup Iteration   3: 10.886 ops/ms
Iteration   1: 10.945 ops/ms
Iteration   2: 11.035 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.900 ±(99.9%) 2.956 ops/ms [Average]
  (min, avg, max) = (10.720, 10.900, 11.035), stdev = 0.162
  CI (99.9%): [7.944, 13.856] (assumes normal distribution)


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
# Warmup Iteration   1: 7.268 ops/ms
# Warmup Iteration   2: 10.038 ops/ms
# Warmup Iteration   3: 10.398 ops/ms
Iteration   1: 10.264 ops/ms
Iteration   2: 10.410 ops/ms
Iteration   3: 10.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.297 ±(99.9%) 1.834 ops/ms [Average]
  (min, avg, max) = (10.217, 10.297, 10.410), stdev = 0.101
  CI (99.9%): [8.463, 12.131] (assumes normal distribution)


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
# Warmup Iteration   1: 5.703 ops/ms
# Warmup Iteration   2: 7.574 ops/ms
# Warmup Iteration   3: 7.820 ops/ms
Iteration   1: 7.911 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 7.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.983 ±(99.9%) 2.141 ops/ms [Average]
  (min, avg, max) = (7.911, 7.983, 8.119), stdev = 0.117
  CI (99.9%): [5.842, 10.124] (assumes normal distribution)


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
# Warmup Iteration   1: 4.572 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.003 ms/op
Iteration   1: 3.071 ±(99.9%) 0.003 ms/op
Iteration   2: 3.095 ±(99.9%) 0.002 ms/op
Iteration   3: 3.078 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.081 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (3.071, 3.081, 3.095), stdev = 0.012
  CI (99.9%): [2.854, 3.308] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.002 ms/op
Iteration   2: 2.881 ±(99.9%) 0.003 ms/op
Iteration   3: 2.890 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.922 ±(99.9%) 1.145 ms/op [Average]
  (min, avg, max) = (2.881, 2.922, 2.994), stdev = 0.063
  CI (99.9%): [1.777, 4.066] (assumes normal distribution)


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
# Warmup Iteration   1: 4.322 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.004 ms/op
Iteration   1: 3.114 ±(99.9%) 0.003 ms/op
Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
Iteration   3: 3.157 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.116 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (3.078, 3.116, 3.157), stdev = 0.040
  CI (99.9%): [2.395, 3.837] (assumes normal distribution)


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
# Warmup Iteration   1: 5.565 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.012 ms/op
Iteration   1: 4.003 ±(99.9%) 0.013 ms/op
Iteration   2: 3.946 ±(99.9%) 0.005 ms/op
Iteration   3: 3.974 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.974 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.946, 3.974, 4.003), stdev = 0.028
  CI (99.9%): [3.459, 4.490] (assumes normal distribution)


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.008 ms/op
Iteration   1: 3.081 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  8.408 ms/op
                 createUser·p0.9999: 17.303 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   2: 3.093 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  11.167 ms/op
                 createUser·p0.9999: 21.604 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   3: 3.101 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  10.299 ms/op
                 createUser·p0.9999: 35.258 ms/op
                 createUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310453
  mean =      3.091 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24427 
    [ 2.500,  5.000) = 282070 
    [ 5.000,  7.500) = 3107 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     10.571 ms/op
     p(99.9900) =     34.246 ms/op
     p(99.9990) =     35.455 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.007 ms/op
Iteration   1: 2.960 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  8.598 ms/op
                 existUser·p0.9999: 17.144 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  7.425 ms/op
                 existUser·p0.9999: 14.193 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  8.684 ms/op
                 existUser·p0.9999: 18.853 ms/op
                 existUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323518
  mean =      2.967 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1408 
    [ 1.250,  2.500) = 35767 
    [ 2.500,  3.750) = 269687 
    [ 3.750,  5.000) = 13606 
    [ 5.000,  6.250) = 1863 
    [ 6.250,  7.500) = 623 
    [ 7.500,  8.750) = 311 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.948 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     17.946 ms/op
     p(99.9990) =     19.252 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.008 ms/op
Iteration   1: 3.100 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  9.421 ms/op
                 getUser·p0.9999: 13.267 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  8.074 ms/op
                 getUser·p0.9999: 16.448 ms/op
                 getUser·p1.00:   16.810 ms/op

Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  8.454 ms/op
                 getUser·p0.9999: 16.022 ms/op
                 getUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312395
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 816 
    [ 1.250,  2.500) = 16781 
    [ 2.500,  3.750) = 274086 
    [ 3.750,  5.000) = 17611 
    [ 5.000,  6.250) = 1723 
    [ 6.250,  7.500) = 634 
    [ 7.500,  8.750) = 463 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     16.081 ms/op
     p(99.9990) =     17.093 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 5.388 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.328 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.143 ±(99.9%) 0.013 ms/op
Iteration   1: 3.984 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  13.611 ms/op
                 listUser·p0.9999: 18.807 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   2: 4.012 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  16.728 ms/op
                 listUser·p0.9999: 19.728 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.135 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.600 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  19.009 ms/op
                 listUser·p0.9999: 27.509 ms/op
                 listUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237398
  mean =      4.043 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3835 
    [ 2.500,  5.000) = 204783 
    [ 5.000,  7.500) = 26302 
    [ 7.500, 10.000) = 1739 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     17.190 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     27.902 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.385 ± 1.785  ops/ms
ClientGrpc.existUser                       thrpt       3  10.900 ± 2.956  ops/ms
ClientGrpc.getUser                         thrpt       3  10.297 ± 1.834  ops/ms
ClientGrpc.listUser                        thrpt       3   7.983 ± 2.141  ops/ms
ClientGrpc.createUser                       avgt       3   3.081 ± 0.227   ms/op
ClientGrpc.existUser                        avgt       3   2.922 ± 1.145   ms/op
ClientGrpc.getUser                          avgt       3   3.116 ± 0.721   ms/op
ClientGrpc.listUser                         avgt       3   3.974 ± 0.516   ms/op
ClientGrpc.createUser                     sample  310453   3.091 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.653           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.292           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.571           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.246           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.586           ms/op
ClientGrpc.existUser                      sample  323518   2.967 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.691           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.948           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.389           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.946           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.431           ms/op
ClientGrpc.getUser                        sample  312395   3.072 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.701           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.997           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.602           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.081           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.203           ms/op
ClientGrpc.listUser                       sample  237398   4.043 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.600           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.561           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.190           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.034           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.951           ms/op
