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
# Warmup Iteration   1: 4.246 ops/ms
# Warmup Iteration   2: 8.887 ops/ms
# Warmup Iteration   3: 9.968 ops/ms
Iteration   1: 10.304 ops/ms
Iteration   2: 10.388 ops/ms
Iteration   3: 10.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.309 ±(99.9%) 1.381 ops/ms [Average]
  (min, avg, max) = (10.237, 10.309, 10.388), stdev = 0.076
  CI (99.9%): [8.929, 11.690] (assumes normal distribution)


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
# Warmup Iteration   1: 7.231 ops/ms
# Warmup Iteration   2: 10.442 ops/ms
# Warmup Iteration   3: 11.186 ops/ms
Iteration   1: 10.992 ops/ms
Iteration   2: 11.023 ops/ms
Iteration   3: 11.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.065 ±(99.9%) 1.835 ops/ms [Average]
  (min, avg, max) = (10.992, 11.065, 11.179), stdev = 0.101
  CI (99.9%): [9.229, 12.900] (assumes normal distribution)


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
# Warmup Iteration   1: 6.646 ops/ms
# Warmup Iteration   2: 10.061 ops/ms
# Warmup Iteration   3: 10.512 ops/ms
Iteration   1: 10.281 ops/ms
Iteration   2: 10.448 ops/ms
Iteration   3: 10.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.410 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (10.281, 10.410, 10.501), stdev = 0.115
  CI (99.9%): [8.310, 12.510] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.854 ops/ms
# Warmup Iteration   2: 7.772 ops/ms
# Warmup Iteration   3: 7.692 ops/ms
Iteration   1: 8.015 ops/ms
Iteration   2: 7.739 ops/ms
Iteration   3: 7.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.861 ±(99.9%) 2.565 ops/ms [Average]
  (min, avg, max) = (7.739, 7.861, 8.015), stdev = 0.141
  CI (99.9%): [5.296, 10.426] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.235 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.003 ms/op
Iteration   1: 3.098 ±(99.9%) 0.002 ms/op
Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
Iteration   3: 3.082 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.105 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (3.082, 3.105, 3.135), stdev = 0.027
  CI (99.9%): [2.608, 3.602] (assumes normal distribution)


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
# Warmup Iteration   1: 3.729 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.003 ms/op
Iteration   1: 2.906 ±(99.9%) 0.002 ms/op
Iteration   2: 2.919 ±(99.9%) 0.003 ms/op
Iteration   3: 2.911 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.912 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (2.906, 2.912, 2.919), stdev = 0.007
  CI (99.9%): [2.783, 3.041] (assumes normal distribution)


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
# Warmup Iteration   1: 4.323 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.005 ms/op
Iteration   1: 3.083 ±(99.9%) 0.005 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 3.061 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.060 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (3.036, 3.060, 3.083), stdev = 0.024
  CI (99.9%): [2.628, 3.492] (assumes normal distribution)


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
# Warmup Iteration   1: 5.699 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.015 ms/op
Iteration   1: 4.044 ±(99.9%) 0.011 ms/op
Iteration   2: 4.119 ±(99.9%) 0.020 ms/op
Iteration   3: 4.060 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.075 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (4.044, 4.075, 4.119), stdev = 0.040
  CI (99.9%): [3.351, 4.798] (assumes normal distribution)


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
# Warmup Iteration   1: 4.480 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.019 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.544 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.825 ms/op
                 createUser·p0.999:  7.636 ms/op
                 createUser·p0.9999: 13.317 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.764 ms/op
                 createUser·p0.999:  8.077 ms/op
                 createUser·p0.9999: 14.934 ms/op
                 createUser·p1.00:   16.237 ms/op

Iteration   3: 3.087 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.943 ms/op
                 createUser·p0.9999: 16.351 ms/op
                 createUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314756
  mean =      3.050 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 873 
    [ 1.250,  2.500) = 17905 
    [ 2.500,  3.750) = 279295 
    [ 3.750,  5.000) = 14515 
    [ 5.000,  6.250) = 1102 
    [ 6.250,  7.500) = 625 
    [ 7.500,  8.750) = 248 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 88 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      7.891 ms/op
     p(99.9900) =     15.991 ms/op
     p(99.9990) =     16.508 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.508 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 12.161 ms/op
                 existUser·p1.00:   12.845 ms/op

Iteration   2: 2.960 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  7.012 ms/op
                 existUser·p0.9999: 21.103 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   3: 2.893 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.970 ms/op
                 existUser·p0.9999: 17.070 ms/op
                 existUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327515
  mean =      2.931 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34148 
    [ 2.500,  5.000) = 291865 
    [ 5.000,  7.500) = 1042 
    [ 7.500, 10.000) = 288 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      8.163 ms/op
     p(99.9900) =     18.887 ms/op
     p(99.9990) =     21.356 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 3.060 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.646 ms/op
                 getUser·p0.999:  7.946 ms/op
                 getUser·p0.9999: 12.632 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.411 ms/op
                 getUser·p0.9999: 22.694 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.584 ms/op
                 getUser·p0.9999: 16.161 ms/op
                 getUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315012
  mean =      3.045 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23148 
    [ 2.500,  5.000) = 289905 
    [ 5.000,  7.500) = 1621 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      7.619 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     23.064 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 5.692 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.012 ms/op
Iteration   1: 4.046 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.249 ms/op
                 listUser·p0.999:  13.362 ms/op
                 listUser·p0.9999: 18.853 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 4.053 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  15.433 ms/op
                 listUser·p0.9999: 18.263 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 4.086 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  17.191 ms/op
                 listUser·p0.9999: 25.865 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236393
  mean =      4.062 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3157 
    [ 2.500,  5.000) = 206753 
    [ 5.000,  7.500) = 24751 
    [ 7.500, 10.000) = 1272 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     25.246 ms/op
     p(99.9990) =     26.179 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.309 ± 1.381  ops/ms
ClientGrpc.existUser                       thrpt       3  11.065 ± 1.835  ops/ms
ClientGrpc.getUser                         thrpt       3  10.410 ± 2.100  ops/ms
ClientGrpc.listUser                        thrpt       3   7.861 ± 2.565  ops/ms
ClientGrpc.createUser                       avgt       3   3.105 ± 0.497   ms/op
ClientGrpc.existUser                        avgt       3   2.912 ± 0.129   ms/op
ClientGrpc.getUser                          avgt       3   3.060 ± 0.432   ms/op
ClientGrpc.listUser                         avgt       3   4.075 ± 0.723   ms/op
ClientGrpc.createUser                     sample  314756   3.050 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.544           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.891           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.991           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.597           ms/op
ClientGrpc.existUser                      sample  327515   2.931 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.508           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.163           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.887           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.151           ms/op
ClientGrpc.getUser                        sample  315012   3.045 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.829           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.619           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.856           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.167           ms/op
ClientGrpc.listUser                       sample  236393   4.062 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.094           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.516           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.246           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.280           ms/op
