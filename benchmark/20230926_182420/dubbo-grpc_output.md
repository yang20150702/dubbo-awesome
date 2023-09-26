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
# Warmup Iteration   1: 4.539 ops/ms
# Warmup Iteration   2: 9.055 ops/ms
# Warmup Iteration   3: 10.159 ops/ms
Iteration   1: 10.538 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.586 ±(99.9%) 0.838 ops/ms [Average]
  (min, avg, max) = (10.538, 10.586, 10.629), stdev = 0.046
  CI (99.9%): [9.748, 11.424] (assumes normal distribution)


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
# Warmup Iteration   1: 8.070 ops/ms
# Warmup Iteration   2: 10.426 ops/ms
# Warmup Iteration   3: 10.763 ops/ms
Iteration   1: 10.934 ops/ms
Iteration   2: 11.154 ops/ms
Iteration   3: 10.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.974 ±(99.9%) 2.973 ops/ms [Average]
  (min, avg, max) = (10.836, 10.974, 11.154), stdev = 0.163
  CI (99.9%): [8.001, 13.948] (assumes normal distribution)


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
# Warmup Iteration   1: 7.615 ops/ms
# Warmup Iteration   2: 10.152 ops/ms
# Warmup Iteration   3: 10.264 ops/ms
Iteration   1: 10.452 ops/ms
Iteration   2: 10.549 ops/ms
Iteration   3: 10.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.486 ±(99.9%) 0.995 ops/ms [Average]
  (min, avg, max) = (10.452, 10.486, 10.549), stdev = 0.055
  CI (99.9%): [9.491, 11.481] (assumes normal distribution)


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
# Warmup Iteration   1: 6.134 ops/ms
# Warmup Iteration   2: 8.068 ops/ms
# Warmup Iteration   3: 8.245 ops/ms
Iteration   1: 8.404 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.332 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (8.274, 8.332, 8.404), stdev = 0.066
  CI (99.9%): [7.120, 9.544] (assumes normal distribution)


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.003 ms/op
Iteration   1: 3.094 ±(99.9%) 0.003 ms/op
Iteration   2: 3.041 ±(99.9%) 0.002 ms/op
Iteration   3: 3.113 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.083 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (3.041, 3.083, 3.113), stdev = 0.038
  CI (99.9%): [2.397, 3.768] (assumes normal distribution)


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
# Warmup Iteration   1: 3.457 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.002 ms/op
Iteration   1: 2.963 ±(99.9%) 0.003 ms/op
Iteration   2: 2.942 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.967 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (2.942, 2.967, 2.996), stdev = 0.027
  CI (99.9%): [2.476, 3.458] (assumes normal distribution)


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
# Warmup Iteration   1: 4.174 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.002 ms/op
Iteration   1: 3.046 ±(99.9%) 0.004 ms/op
Iteration   2: 3.104 ±(99.9%) 0.002 ms/op
Iteration   3: 3.126 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.092 ±(99.9%) 0.751 ms/op [Average]
  (min, avg, max) = (3.046, 3.092, 3.126), stdev = 0.041
  CI (99.9%): [2.342, 3.843] (assumes normal distribution)


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
# Warmup Iteration   1: 4.666 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.034 ms/op
Iteration   1: 3.862 ±(99.9%) 0.029 ms/op
Iteration   2: 3.853 ±(99.9%) 0.013 ms/op
Iteration   3: 3.889 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.868 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (3.853, 3.868, 3.889), stdev = 0.019
  CI (99.9%): [3.525, 4.211] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.180 ms/op
                 createUser·p0.9999: 17.605 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.246 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.506 ms/op
                 createUser·p0.9999: 16.253 ms/op
                 createUser·p1.00:   16.744 ms/op

Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.620 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  9.419 ms/op
                 createUser·p0.9999: 18.142 ms/op
                 createUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308764
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 793 
    [ 1.250,  2.500) = 12918 
    [ 2.500,  3.750) = 270162 
    [ 3.750,  5.000) = 23302 
    [ 5.000,  6.250) = 921 
    [ 6.250,  7.500) = 310 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 76 
    [16.250, 17.500) = 72 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.246 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.468 ms/op
     p(99.9000) =      8.178 ms/op
     p(99.9900) =     17.539 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.005 ms/op
Iteration   1: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 11.549 ms/op
                 existUser·p1.00:   11.944 ms/op

Iteration   2: 3.017 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.521 ms/op
                 existUser·p0.9999: 16.063 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  10.748 ms/op
                 existUser·p0.9999: 16.068 ms/op
                 existUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324232
  mean =      2.960 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1971 
    [ 1.250,  2.500) = 28983 
    [ 2.500,  3.750) = 279190 
    [ 3.750,  5.000) = 12587 
    [ 5.000,  6.250) = 934 
    [ 6.250,  7.500) = 186 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.221 ms/op
     p(99.9900) =     15.925 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.006 ms/op
Iteration   1: 3.146 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.963 ms/op
                 getUser·p0.9999: 15.351 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.196 ms/op
                 getUser·p0.9999: 12.639 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 14.891 ms/op
                 getUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311160
  mean =      3.084 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1495 
    [ 1.250,  2.500) = 14385 
    [ 2.500,  3.750) = 271050 
    [ 3.750,  5.000) = 22719 
    [ 5.000,  6.250) = 686 
    [ 6.250,  7.500) = 343 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.533 ms/op
     p(99.9900) =     14.893 ms/op
     p(99.9990) =     15.596 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 5.220 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.008 ms/op
Iteration   1: 3.880 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  12.251 ms/op
                 listUser·p0.9999: 14.705 ms/op
                 listUser·p1.00:   15.073 ms/op

Iteration   2: 3.819 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  12.491 ms/op
                 listUser·p0.9999: 14.261 ms/op
                 listUser·p1.00:   15.827 ms/op

Iteration   3: 3.849 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.482 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 16.313 ms/op
                 listUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249317
  mean =      3.849 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 3014 
    [ 2.500,  3.750) = 116985 
    [ 3.750,  5.000) = 116814 
    [ 5.000,  6.250) = 8538 
    [ 6.250,  7.500) = 2978 
    [ 7.500,  8.750) = 297 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 205 
    [12.500, 13.750) = 153 
    [13.750, 15.000) = 105 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     12.823 ms/op
     p(99.9900) =     15.731 ms/op
     p(99.9990) =     16.482 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.586 ± 0.838  ops/ms
ClientGrpc.existUser                       thrpt       3  10.974 ± 2.973  ops/ms
ClientGrpc.getUser                         thrpt       3  10.486 ± 0.995  ops/ms
ClientGrpc.listUser                        thrpt       3   8.332 ± 1.212  ops/ms
ClientGrpc.createUser                       avgt       3   3.083 ± 0.685   ms/op
ClientGrpc.existUser                        avgt       3   2.967 ± 0.491   ms/op
ClientGrpc.getUser                          avgt       3   3.092 ± 0.751   ms/op
ClientGrpc.listUser                         avgt       3   3.868 ± 0.343   ms/op
ClientGrpc.createUser                     sample  308764   3.109 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.246           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.468           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.178           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.539           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.857           ms/op
ClientGrpc.existUser                      sample  324232   2.960 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.634           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.221           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.925           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.318           ms/op
ClientGrpc.getUser                        sample  311160   3.084 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.761           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.533           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.893           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.696           ms/op
ClientGrpc.listUser                       sample  249317   3.849 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.106           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.276           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.480           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.823           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.731           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          16.646           ms/op
