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
# Warmup Iteration   1: 4.330 ops/ms
# Warmup Iteration   2: 9.255 ops/ms
# Warmup Iteration   3: 10.046 ops/ms
Iteration   1: 10.432 ops/ms
Iteration   2: 10.438 ops/ms
Iteration   3: 10.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.408 ±(99.9%) 0.848 ops/ms [Average]
  (min, avg, max) = (10.354, 10.408, 10.438), stdev = 0.046
  CI (99.9%): [9.560, 11.255] (assumes normal distribution)


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
# Warmup Iteration   1: 7.486 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 10.832 ops/ms
Iteration   1: 10.852 ops/ms
Iteration   2: 10.815 ops/ms
Iteration   3: 10.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.751 ±(99.9%) 2.619 ops/ms [Average]
  (min, avg, max) = (10.587, 10.751, 10.852), stdev = 0.144
  CI (99.9%): [8.132, 13.370] (assumes normal distribution)


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
# Warmup Iteration   1: 7.027 ops/ms
# Warmup Iteration   2: 10.141 ops/ms
# Warmup Iteration   3: 10.219 ops/ms
Iteration   1: 10.585 ops/ms
Iteration   2: 10.304 ops/ms
Iteration   3: 10.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.401 ±(99.9%) 2.913 ops/ms [Average]
  (min, avg, max) = (10.304, 10.401, 10.585), stdev = 0.160
  CI (99.9%): [7.488, 13.314] (assumes normal distribution)


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
# Warmup Iteration   1: 5.839 ops/ms
# Warmup Iteration   2: 7.914 ops/ms
# Warmup Iteration   3: 8.219 ops/ms
Iteration   1: 8.204 ops/ms
Iteration   2: 8.324 ops/ms
Iteration   3: 8.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.271 ±(99.9%) 1.111 ops/ms [Average]
  (min, avg, max) = (8.204, 8.271, 8.324), stdev = 0.061
  CI (99.9%): [7.159, 9.382] (assumes normal distribution)


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.004 ms/op
Iteration   1: 3.034 ±(99.9%) 0.004 ms/op
Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
Iteration   3: 3.131 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.094 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (3.034, 3.094, 3.131), stdev = 0.052
  CI (99.9%): [2.139, 4.050] (assumes normal distribution)


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.004 ms/op
Iteration   1: 2.939 ±(99.9%) 0.003 ms/op
Iteration   2: 2.992 ±(99.9%) 0.004 ms/op
Iteration   3: 2.966 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.966 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (2.939, 2.966, 2.992), stdev = 0.027
  CI (99.9%): [2.482, 3.450] (assumes normal distribution)


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.005 ms/op
Iteration   1: 3.073 ±(99.9%) 0.002 ms/op
Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
Iteration   3: 3.060 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.078 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.060, 3.078, 3.101), stdev = 0.021
  CI (99.9%): [2.692, 3.464] (assumes normal distribution)


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
# Warmup Iteration   1: 5.091 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.041 ms/op
Iteration   1: 3.864 ±(99.9%) 0.041 ms/op
Iteration   2: 3.874 ±(99.9%) 0.028 ms/op
Iteration   3: 3.847 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.862 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (3.847, 3.862, 3.874), stdev = 0.013
  CI (99.9%): [3.617, 4.106] (assumes normal distribution)


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
Iteration   1: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.469 ms/op
                 createUser·p0.999:  9.650 ms/op
                 createUser·p0.9999: 15.723 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.200 ms/op
                 createUser·p0.999:  7.284 ms/op
                 createUser·p0.9999: 16.732 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   3: 3.108 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  9.028 ms/op
                 createUser·p0.9999: 30.434 ms/op
                 createUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310921
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14220 
    [ 2.500,  5.000) = 295139 
    [ 5.000,  7.500) = 1069 
    [ 7.500, 10.000) = 238 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.078 ms/op
     p(99.9900) =     29.354 ms/op
     p(99.9990) =     31.734 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  9.766 ms/op
                 existUser·p0.9999: 19.900 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   2: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  8.373 ms/op
                 existUser·p0.9999: 18.973 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  11.440 ms/op
                 existUser·p0.9999: 16.400 ms/op
                 existUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324131
  mean =      2.964 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31120 
    [ 2.500,  5.000) = 291293 
    [ 5.000,  7.500) = 1129 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     19.156 ms/op
     p(99.9990) =     23.749 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.007 ms/op
Iteration   1: 3.205 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.891 ms/op
                 getUser·p0.9999: 15.042 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 3.123 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.926 ms/op
                 getUser·p0.9999: 15.999 ms/op
                 getUser·p1.00:   16.417 ms/op

Iteration   3: 3.084 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.143 ms/op
                 getUser·p0.9999: 16.263 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306021
  mean =      3.137 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 594 
    [ 1.250,  2.500) = 8529 
    [ 2.500,  3.750) = 270114 
    [ 3.750,  5.000) = 25375 
    [ 5.000,  6.250) = 686 
    [ 6.250,  7.500) = 312 
    [ 7.500,  8.750) = 157 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 90 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.971 ms/op
     p(99.9900) =     15.942 ms/op
     p(99.9990) =     17.824 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 5.289 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
Iteration   1: 3.871 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   5.263 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  14.797 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 3.852 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.357 ms/op
                 listUser·p0.999:  12.482 ms/op
                 listUser·p0.9999: 27.681 ms/op
                 listUser·p1.00:   32.178 ms/op

Iteration   3: 3.874 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   6.835 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 22.626 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248333
  mean =      3.866 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5369 
    [ 2.500,  5.000) = 227353 
    [ 5.000,  7.500) = 14572 
    [ 7.500, 10.000) = 481 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     31.576 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.408 ± 0.848  ops/ms
ClientGrpc.existUser                       thrpt       3  10.751 ± 2.619  ops/ms
ClientGrpc.getUser                         thrpt       3  10.401 ± 2.913  ops/ms
ClientGrpc.listUser                        thrpt       3   8.271 ± 1.111  ops/ms
ClientGrpc.createUser                       avgt       3   3.094 ± 0.955   ms/op
ClientGrpc.existUser                        avgt       3   2.966 ± 0.484   ms/op
ClientGrpc.getUser                          avgt       3   3.078 ± 0.386   ms/op
ClientGrpc.listUser                         avgt       3   3.862 ± 0.244   ms/op
ClientGrpc.createUser                     sample  310921   3.089 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.559           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.078           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.354           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.342           ms/op
ClientGrpc.existUser                      sample  324131   2.964 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.699           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.156           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.888           ms/op
ClientGrpc.getUser                        sample  306021   3.137 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.554           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.971           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.942           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  248333   3.866 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.961           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.309           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.057           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.296           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.178           ms/op
