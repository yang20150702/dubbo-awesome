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
# Warmup Iteration   1: 3.709 ops/ms
# Warmup Iteration   2: 8.379 ops/ms
# Warmup Iteration   3: 9.863 ops/ms
Iteration   1: 10.090 ops/ms
Iteration   2: 10.259 ops/ms
Iteration   3: 10.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.192 ±(99.9%) 1.636 ops/ms [Average]
  (min, avg, max) = (10.090, 10.192, 10.259), stdev = 0.090
  CI (99.9%): [8.557, 11.828] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.008 ops/ms
# Warmup Iteration   2: 9.961 ops/ms
# Warmup Iteration   3: 10.701 ops/ms
Iteration   1: 10.652 ops/ms
Iteration   2: 10.721 ops/ms
Iteration   3: 10.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.777 ±(99.9%) 2.921 ops/ms [Average]
  (min, avg, max) = (10.652, 10.777, 10.957), stdev = 0.160
  CI (99.9%): [7.856, 13.697] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.690 ops/ms
# Warmup Iteration   2: 9.684 ops/ms
# Warmup Iteration   3: 10.056 ops/ms
Iteration   1: 9.884 ops/ms
Iteration   2: 9.936 ops/ms
Iteration   3: 9.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.933 ±(99.9%) 0.878 ops/ms [Average]
  (min, avg, max) = (9.884, 9.933, 9.980), stdev = 0.048
  CI (99.9%): [9.056, 10.811] (assumes normal distribution)


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
# Warmup Iteration   1: 5.034 ops/ms
# Warmup Iteration   2: 7.231 ops/ms
# Warmup Iteration   3: 7.649 ops/ms
Iteration   1: 7.646 ops/ms
Iteration   2: 7.630 ops/ms
Iteration   3: 7.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.658 ±(99.9%) 0.642 ops/ms [Average]
  (min, avg, max) = (7.630, 7.658, 7.697), stdev = 0.035
  CI (99.9%): [7.016, 8.300] (assumes normal distribution)


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
# Warmup Iteration   1: 4.261 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.002 ms/op
Iteration   1: 3.020 ±(99.9%) 0.007 ms/op
Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
Iteration   3: 2.981 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.021 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (2.981, 3.021, 3.061), stdev = 0.040
  CI (99.9%): [2.291, 3.751] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.004 ms/op
Iteration   1: 2.968 ±(99.9%) 0.002 ms/op
Iteration   2: 2.903 ±(99.9%) 0.003 ms/op
Iteration   3: 2.954 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.942 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (2.903, 2.942, 2.968), stdev = 0.034
  CI (99.9%): [2.316, 3.567] (assumes normal distribution)


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
# Warmup Iteration   1: 4.137 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.331 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.005 ms/op
Iteration   1: 3.166 ±(99.9%) 0.003 ms/op
Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
Iteration   3: 3.135 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.126 ±(99.9%) 0.822 ms/op [Average]
  (min, avg, max) = (3.077, 3.126, 3.166), stdev = 0.045
  CI (99.9%): [2.304, 3.948] (assumes normal distribution)


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
# Warmup Iteration   1: 5.831 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.017 ms/op
Iteration   1: 4.145 ±(99.9%) 0.027 ms/op
Iteration   2: 4.059 ±(99.9%) 0.036 ms/op
Iteration   3: 4.152 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.119 ±(99.9%) 0.937 ms/op [Average]
  (min, avg, max) = (4.059, 4.119, 4.152), stdev = 0.051
  CI (99.9%): [3.181, 5.056] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.488 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  9.621 ms/op
                 createUser·p0.9999: 13.315 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  9.723 ms/op
                 createUser·p0.9999: 17.909 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 17.330 ms/op
                 createUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310317
  mean =      3.095 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 884 
    [ 1.250,  2.500) = 18928 
    [ 2.500,  3.750) = 265373 
    [ 3.750,  5.000) = 22902 
    [ 5.000,  6.250) = 986 
    [ 6.250,  7.500) = 543 
    [ 7.500,  8.750) = 251 
    [ 8.750, 10.000) = 190 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 70 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.956 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.005 ms/op
Iteration   1: 2.949 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  9.215 ms/op
                 existUser·p0.9999: 12.829 ms/op
                 existUser·p1.00:   12.993 ms/op

Iteration   2: 2.971 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  10.496 ms/op
                 existUser·p0.9999: 18.338 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  10.142 ms/op
                 existUser·p0.9999: 18.640 ms/op
                 existUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323560
  mean =      2.966 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24332 
    [ 2.500,  5.000) = 297187 
    [ 5.000,  7.500) = 1379 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     19.827 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  8.847 ms/op
                 getUser·p0.9999: 13.486 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  7.907 ms/op
                 getUser·p0.9999: 14.926 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  8.073 ms/op
                 getUser·p0.9999: 17.886 ms/op
                 getUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312930
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1299 
    [ 1.250,  2.500) = 22623 
    [ 2.500,  3.750) = 266636 
    [ 3.750,  5.000) = 19568 
    [ 5.000,  6.250) = 1663 
    [ 6.250,  7.500) = 630 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.923 ms/op
     p(99.9000) =      8.340 ms/op
     p(99.9900) =     16.245 ms/op
     p(99.9990) =     19.558 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 5.382 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.013 ms/op
Iteration   1: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  14.622 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   2: 4.090 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 28.263 ms/op
                 listUser·p1.00:   28.705 ms/op

Iteration   3: 4.048 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236017
  mean =      4.069 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2388 
    [ 2.500,  5.000) = 208346 
    [ 5.000,  7.500) = 23112 
    [ 7.500, 10.000) = 1548 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.420 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     28.693 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.192 ± 1.636  ops/ms
ClientGrpc.existUser                       thrpt       3  10.777 ± 2.921  ops/ms
ClientGrpc.getUser                         thrpt       3   9.933 ± 0.878  ops/ms
ClientGrpc.listUser                        thrpt       3   7.658 ± 0.642  ops/ms
ClientGrpc.createUser                       avgt       3   3.021 ± 0.730   ms/op
ClientGrpc.existUser                        avgt       3   2.942 ± 0.625   ms/op
ClientGrpc.getUser                          avgt       3   3.126 ± 0.822   ms/op
ClientGrpc.listUser                         avgt       3   4.119 ± 0.937   ms/op
ClientGrpc.createUser                     sample  310317   3.095 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.855           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.634           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.400           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.350           ms/op
ClientGrpc.existUser                      sample  323560   2.966 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.440           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.617           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.957           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.021           ms/op
ClientGrpc.getUser                        sample  312930   3.065 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.663           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.923           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.340           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.245           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.694           ms/op
ClientGrpc.listUser                       sample  236017   4.069 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.949           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.420           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.647           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.444           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.705           ms/op
