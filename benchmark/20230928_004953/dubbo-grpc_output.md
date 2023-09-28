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
# Warmup Iteration   1: 4.156 ops/ms
# Warmup Iteration   2: 8.650 ops/ms
# Warmup Iteration   3: 9.393 ops/ms
Iteration   1: 9.835 ops/ms
Iteration   2: 10.033 ops/ms
Iteration   3: 9.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.930 ±(99.9%) 1.803 ops/ms [Average]
  (min, avg, max) = (9.835, 9.930, 10.033), stdev = 0.099
  CI (99.9%): [8.127, 11.733] (assumes normal distribution)


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
# Warmup Iteration   1: 6.995 ops/ms
# Warmup Iteration   2: 10.149 ops/ms
# Warmup Iteration   3: 10.251 ops/ms
Iteration   1: 10.692 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 10.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.491 ±(99.9%) 4.507 ops/ms [Average]
  (min, avg, max) = (10.215, 10.491, 10.692), stdev = 0.247
  CI (99.9%): [5.984, 14.997] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.826 ops/ms
# Warmup Iteration   2: 9.755 ops/ms
# Warmup Iteration   3: 10.012 ops/ms
Iteration   1: 10.218 ops/ms
Iteration   2: 10.232 ops/ms
Iteration   3: 10.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.206 ±(99.9%) 0.638 ops/ms [Average]
  (min, avg, max) = (10.166, 10.206, 10.232), stdev = 0.035
  CI (99.9%): [9.568, 10.843] (assumes normal distribution)


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
# Warmup Iteration   1: 5.492 ops/ms
# Warmup Iteration   2: 7.819 ops/ms
# Warmup Iteration   3: 7.995 ops/ms
Iteration   1: 8.043 ops/ms
Iteration   2: 8.072 ops/ms
Iteration   3: 8.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.109 ±(99.9%) 1.627 ops/ms [Average]
  (min, avg, max) = (8.043, 8.109, 8.210), stdev = 0.089
  CI (99.9%): [6.481, 9.736] (assumes normal distribution)


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.002 ms/op
Iteration   1: 3.104 ±(99.9%) 0.002 ms/op
Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
Iteration   3: 3.122 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.105 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.088, 3.105, 3.122), stdev = 0.017
  CI (99.9%): [2.789, 3.421] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.003 ms/op
Iteration   1: 3.024 ±(99.9%) 0.001 ms/op
Iteration   2: 3.031 ±(99.9%) 0.001 ms/op
Iteration   3: 2.944 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.000 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (2.944, 3.000, 3.031), stdev = 0.049
  CI (99.9%): [2.115, 3.885] (assumes normal distribution)


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
# Warmup Iteration   1: 4.475 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.002 ms/op
Iteration   1: 3.119 ±(99.9%) 0.012 ms/op
Iteration   2: 3.185 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.134 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.100, 3.134, 3.185), stdev = 0.045
  CI (99.9%): [2.320, 3.948] (assumes normal distribution)


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
# Warmup Iteration   1: 5.358 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.028 ms/op
Iteration   1: 3.928 ±(99.9%) 0.029 ms/op
Iteration   2: 3.904 ±(99.9%) 0.016 ms/op
Iteration   3: 3.841 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.891 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (3.841, 3.891, 3.928), stdev = 0.045
  CI (99.9%): [3.071, 4.711] (assumes normal distribution)


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
# Warmup Iteration   1: 4.257 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
Iteration   1: 3.123 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.170 ms/op
                 createUser·p0.9999: 25.420 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.033 ms/op
                 createUser·p0.9999: 17.375 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   3: 3.142 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  6.955 ms/op
                 createUser·p0.9999: 19.852 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307828
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13959 
    [ 2.500,  5.000) = 291980 
    [ 5.000,  7.500) = 1630 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     26.242 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 2.993 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.139 ms/op
                 existUser·p0.999:  6.473 ms/op
                 existUser·p0.9999: 13.817 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 2.891 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.752 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.559 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.578 ms/op
                 existUser·p0.9999: 14.913 ms/op
                 existUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325217
  mean =      2.951 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33605 
    [ 2.500,  5.000) = 289634 
    [ 5.000,  7.500) = 1673 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.430 ms/op
     p(99.9900) =     20.145 ms/op
     p(99.9990) =     24.920 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
Iteration   1: 3.162 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  7.805 ms/op
                 getUser·p0.9999: 18.543 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  7.449 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  7.905 ms/op
                 getUser·p0.9999: 27.210 ms/op
                 getUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307585
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14040 
    [ 2.500,  5.000) = 290946 
    [ 5.000,  7.500) = 2224 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      7.761 ms/op
     p(99.9900) =     26.132 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 5.434 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.009 ms/op
Iteration   1: 3.952 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.921 ms/op
                 listUser·p0.999:  13.158 ms/op
                 listUser·p0.9999: 17.322 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 3.999 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.444 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.270 ms/op
                 listUser·p0.9999: 15.827 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 3.981 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.040 ms/op
                 listUser·p0.999:  17.267 ms/op
                 listUser·p0.9999: 25.264 ms/op
                 listUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241200
  mean =      3.977 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3036 
    [ 2.500,  5.000) = 219303 
    [ 5.000,  7.500) = 17424 
    [ 7.500, 10.000) = 801 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     24.786 ms/op
     p(99.9990) =     26.912 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.930 ± 1.803  ops/ms
ClientGrpc.existUser                       thrpt       3  10.491 ± 4.507  ops/ms
ClientGrpc.getUser                         thrpt       3  10.206 ± 0.638  ops/ms
ClientGrpc.listUser                        thrpt       3   8.109 ± 1.627  ops/ms
ClientGrpc.createUser                       avgt       3   3.105 ± 0.316   ms/op
ClientGrpc.existUser                        avgt       3   3.000 ± 0.885   ms/op
ClientGrpc.getUser                          avgt       3   3.134 ± 0.814   ms/op
ClientGrpc.listUser                         avgt       3   3.891 ± 0.820   ms/op
ClientGrpc.createUser                     sample  307828   3.115 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.585           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.078           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.478           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.411           ms/op
ClientGrpc.existUser                      sample  325217   2.951 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.559           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.430           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.145           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.035           ms/op
ClientGrpc.getUser                        sample  307585   3.121 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.701           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.903           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.761           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.132           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.591           ms/op
ClientGrpc.listUser                       sample  241200   3.977 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.182           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.694           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.910           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.786           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.165           ms/op
