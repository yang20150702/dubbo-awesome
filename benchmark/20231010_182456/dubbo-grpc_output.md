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
# Warmup Iteration   1: 4.140 ops/ms
# Warmup Iteration   2: 8.691 ops/ms
# Warmup Iteration   3: 9.754 ops/ms
Iteration   1: 10.096 ops/ms
Iteration   2: 10.069 ops/ms
Iteration   3: 10.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.098 ±(99.9%) 0.549 ops/ms [Average]
  (min, avg, max) = (10.069, 10.098, 10.129), stdev = 0.030
  CI (99.9%): [9.550, 10.647] (assumes normal distribution)


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
# Warmup Iteration   1: 7.044 ops/ms
# Warmup Iteration   2: 10.321 ops/ms
# Warmup Iteration   3: 10.519 ops/ms
Iteration   1: 10.589 ops/ms
Iteration   2: 10.718 ops/ms
Iteration   3: 10.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.729 ±(99.9%) 2.652 ops/ms [Average]
  (min, avg, max) = (10.589, 10.729, 10.879), stdev = 0.145
  CI (99.9%): [8.077, 13.381] (assumes normal distribution)


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
# Warmup Iteration   1: 7.334 ops/ms
# Warmup Iteration   2: 9.937 ops/ms
# Warmup Iteration   3: 10.100 ops/ms
Iteration   1: 10.136 ops/ms
Iteration   2: 10.233 ops/ms
Iteration   3: 10.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.203 ±(99.9%) 1.060 ops/ms [Average]
  (min, avg, max) = (10.136, 10.203, 10.239), stdev = 0.058
  CI (99.9%): [9.143, 11.262] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.569 ops/ms
# Warmup Iteration   2: 7.790 ops/ms
# Warmup Iteration   3: 8.036 ops/ms
Iteration   1: 7.961 ops/ms
Iteration   2: 8.130 ops/ms
Iteration   3: 7.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.980 ±(99.9%) 2.587 ops/ms [Average]
  (min, avg, max) = (7.849, 7.980, 8.130), stdev = 0.142
  CI (99.9%): [5.393, 10.567] (assumes normal distribution)


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
# Warmup Iteration   1: 4.520 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.005 ms/op
Iteration   1: 3.160 ±(99.9%) 0.012 ms/op
Iteration   2: 3.199 ±(99.9%) 0.004 ms/op
Iteration   3: 3.092 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.150 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (3.092, 3.150, 3.199), stdev = 0.054
  CI (99.9%): [2.158, 4.142] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 3.021 ±(99.9%) 0.004 ms/op
Iteration   2: 3.031 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.005 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (2.963, 3.005, 3.031), stdev = 0.037
  CI (99.9%): [2.326, 3.685] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.452 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.007 ms/op
Iteration   1: 3.122 ±(99.9%) 0.004 ms/op
Iteration   2: 3.168 ±(99.9%) 0.002 ms/op
Iteration   3: 3.181 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.157 ±(99.9%) 0.563 ms/op [Average]
  (min, avg, max) = (3.122, 3.157, 3.181), stdev = 0.031
  CI (99.9%): [2.594, 3.720] (assumes normal distribution)


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
# Warmup Iteration   1: 5.490 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.012 ms/op
Iteration   1: 3.768 ±(99.9%) 0.017 ms/op
Iteration   2: 3.950 ±(99.9%) 0.021 ms/op
Iteration   3: 3.956 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.891 ±(99.9%) 1.951 ms/op [Average]
  (min, avg, max) = (3.768, 3.891, 3.956), stdev = 0.107
  CI (99.9%): [1.940, 5.843] (assumes normal distribution)


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
# Warmup Iteration   1: 4.448 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.362 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  10.519 ms/op
                 createUser·p0.9999: 17.982 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   2: 3.181 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  8.126 ms/op
                 createUser·p0.9999: 14.594 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.626 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  14.582 ms/op
                 createUser·p0.9999: 20.239 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305137
  mean =      3.144 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12581 
    [ 2.500,  5.000) = 290130 
    [ 5.000,  7.500) = 1964 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =     10.975 ms/op
     p(99.9900) =     19.480 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.005 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.786 ms/op
                 existUser·p0.9999: 15.072 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  9.265 ms/op
                 existUser·p0.9999: 16.704 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  10.446 ms/op
                 existUser·p0.9999: 16.930 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320705
  mean =      2.993 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1425 
    [ 1.250,  2.500) = 25877 
    [ 2.500,  3.750) = 278629 
    [ 3.750,  5.000) = 13299 
    [ 5.000,  6.250) = 707 
    [ 6.250,  7.500) = 358 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 72 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     15.890 ms/op
     p(99.9990) =     18.016 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.006 ms/op
Iteration   1: 3.103 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.668 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  12.190 ms/op
                 getUser·p0.9999: 32.528 ms/op
                 getUser·p1.00:   32.932 ms/op

Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.646 ms/op
                 getUser·p0.9999: 21.120 ms/op
                 getUser·p1.00:   21.266 ms/op

Iteration   3: 3.107 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.503 ms/op
                 getUser·p0.9999: 20.868 ms/op
                 getUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310779
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14613 
    [ 2.500,  5.000) = 294265 
    [ 5.000,  7.500) = 1418 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.622 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     32.823 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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
# Warmup Iteration   1: 5.949 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.013 ms/op
Iteration   1: 3.977 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.494 ms/op
                 listUser·p0.9999: 19.393 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 3.807 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 29.688 ms/op
                 listUser·p1.00:   29.917 ms/op

Iteration   3: 3.820 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.736 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  15.568 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248222
  mean =      3.867 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2884 
    [ 2.500,  5.000) = 230883 
    [ 5.000,  7.500) = 13337 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     22.191 ms/op
     p(99.9990) =     29.901 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.098 ± 0.549  ops/ms
ClientGrpc.existUser                       thrpt       3  10.729 ± 2.652  ops/ms
ClientGrpc.getUser                         thrpt       3  10.203 ± 1.060  ops/ms
ClientGrpc.listUser                        thrpt       3   7.980 ± 2.587  ops/ms
ClientGrpc.createUser                       avgt       3   3.150 ± 0.992   ms/op
ClientGrpc.existUser                        avgt       3   3.005 ± 0.679   ms/op
ClientGrpc.getUser                          avgt       3   3.157 ± 0.563   ms/op
ClientGrpc.listUser                         avgt       3   3.891 ± 1.951   ms/op
ClientGrpc.createUser                     sample  305137   3.144 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.626           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.975           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.480           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.037           ms/op
ClientGrpc.existUser                      sample  320705   2.993 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.695           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.438           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.890           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  310779   3.089 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.668           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.622           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.452           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.201           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.932           ms/op
ClientGrpc.listUser                       sample  248222   3.867 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.736           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.358           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.025           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.191           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.917           ms/op
