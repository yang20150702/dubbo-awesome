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
# Warmup Iteration   1: 3.742 ops/ms
# Warmup Iteration   2: 8.506 ops/ms
# Warmup Iteration   3: 9.951 ops/ms
Iteration   1: 10.124 ops/ms
Iteration   2: 10.147 ops/ms
Iteration   3: 9.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.006 ±(99.9%) 4.111 ops/ms [Average]
  (min, avg, max) = (9.746, 10.006, 10.147), stdev = 0.225
  CI (99.9%): [5.894, 14.117] (assumes normal distribution)


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
# Warmup Iteration   1: 7.799 ops/ms
# Warmup Iteration   2: 10.489 ops/ms
# Warmup Iteration   3: 10.460 ops/ms
Iteration   1: 10.778 ops/ms
Iteration   2: 10.625 ops/ms
Iteration   3: 10.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.737 ±(99.9%) 1.785 ops/ms [Average]
  (min, avg, max) = (10.625, 10.737, 10.808), stdev = 0.098
  CI (99.9%): [8.951, 12.522] (assumes normal distribution)


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
# Warmup Iteration   1: 6.696 ops/ms
# Warmup Iteration   2: 9.744 ops/ms
# Warmup Iteration   3: 9.936 ops/ms
Iteration   1: 9.963 ops/ms
Iteration   2: 10.061 ops/ms
Iteration   3: 10.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.041 ±(99.9%) 1.270 ops/ms [Average]
  (min, avg, max) = (9.963, 10.041, 10.098), stdev = 0.070
  CI (99.9%): [8.771, 11.311] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.404 ops/ms
# Warmup Iteration   2: 7.551 ops/ms
# Warmup Iteration   3: 7.686 ops/ms
Iteration   1: 7.969 ops/ms
Iteration   2: 7.939 ops/ms
Iteration   3: 7.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.951 ±(99.9%) 0.293 ops/ms [Average]
  (min, avg, max) = (7.939, 7.951, 7.969), stdev = 0.016
  CI (99.9%): [7.658, 8.244] (assumes normal distribution)


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
# Warmup Iteration   1: 4.303 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.002 ms/op
Iteration   1: 3.188 ±(99.9%) 0.011 ms/op
Iteration   2: 3.161 ±(99.9%) 0.002 ms/op
Iteration   3: 3.157 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.169 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (3.157, 3.169, 3.188), stdev = 0.017
  CI (99.9%): [2.866, 3.471] (assumes normal distribution)


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 3.056 ±(99.9%) 0.002 ms/op
Iteration   2: 2.996 ±(99.9%) 0.002 ms/op
Iteration   3: 2.975 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.009 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (2.975, 3.009, 3.056), stdev = 0.042
  CI (99.9%): [2.244, 3.774] (assumes normal distribution)


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.001 ms/op
Iteration   1: 3.154 ±(99.9%) 0.002 ms/op
Iteration   2: 3.104 ±(99.9%) 0.001 ms/op
Iteration   3: 3.120 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.126 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (3.104, 3.126, 3.154), stdev = 0.025
  CI (99.9%): [2.665, 3.587] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.098 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.012 ms/op
Iteration   1: 4.042 ±(99.9%) 0.011 ms/op
Iteration   2: 3.985 ±(99.9%) 0.006 ms/op
Iteration   3: 4.049 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.025 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.985, 4.025, 4.049), stdev = 0.035
  CI (99.9%): [3.383, 4.668] (assumes normal distribution)


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
# Warmup Iteration   1: 4.309 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
Iteration   1: 3.161 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  6.706 ms/op
                 createUser·p0.9999: 15.106 ms/op
                 createUser·p1.00:   16.204 ms/op

Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  8.351 ms/op
                 createUser·p0.9999: 18.208 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  12.311 ms/op
                 createUser·p0.9999: 20.252 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306025
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29389 
    [ 2.500,  5.000) = 275409 
    [ 5.000,  7.500) = 909 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.619 ms/op
     p(99.9900) =     19.176 ms/op
     p(99.9990) =     20.445 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  5.956 ms/op
                 existUser·p0.9999: 15.799 ms/op
                 existUser·p1.00:   16.105 ms/op

Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.620 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.037 ms/op
                 existUser·p0.9999: 17.531 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   3: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  6.758 ms/op
                 existUser·p0.9999: 19.927 ms/op
                 existUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319317
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42855 
    [ 2.500,  5.000) = 275661 
    [ 5.000,  7.500) = 598 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.734 ms/op
     p(99.9900) =     17.601 ms/op
     p(99.9990) =     20.015 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 4.299 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.006 ms/op
Iteration   1: 3.114 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.769 ms/op
                 getUser·p0.9999: 12.827 ms/op
                 getUser·p1.00:   13.484 ms/op

Iteration   2: 3.077 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.454 ms/op
                 getUser·p0.9999: 14.142 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.480 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  6.132 ms/op
                 getUser·p0.9999: 20.327 ms/op
                 getUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313468
  mean =      3.062 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27185 
    [ 2.500,  5.000) = 285184 
    [ 5.000,  7.500) = 752 
    [ 7.500, 10.000) = 172 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.619 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     20.414 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.042 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.396 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.010 ms/op
Iteration   1: 3.935 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.765 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  13.544 ms/op
                 listUser·p0.9999: 15.282 ms/op
                 listUser·p1.00:   15.548 ms/op

Iteration   2: 4.090 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.250 ms/op
                 listUser·p0.9999: 23.233 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   3: 4.061 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.764 ms/op
                 listUser·p0.9999: 16.815 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238408
  mean =      4.027 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3143 
    [ 2.500,  5.000) = 207545 
    [ 5.000,  7.500) = 26494 
    [ 7.500, 10.000) = 827 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     21.108 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.006 ± 4.111  ops/ms
ClientGrpc.existUser                       thrpt       3  10.737 ± 1.785  ops/ms
ClientGrpc.getUser                         thrpt       3  10.041 ± 1.270  ops/ms
ClientGrpc.listUser                        thrpt       3   7.951 ± 0.293  ops/ms
ClientGrpc.createUser                       avgt       3   3.169 ± 0.302   ms/op
ClientGrpc.existUser                        avgt       3   3.009 ± 0.765   ms/op
ClientGrpc.getUser                          avgt       3   3.126 ± 0.461   ms/op
ClientGrpc.listUser                         avgt       3   4.025 ± 0.643   ms/op
ClientGrpc.createUser                     sample  306025   3.136 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.710           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.619           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.176           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.513           ms/op
ClientGrpc.existUser                      sample  319317   3.005 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.620           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.734           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.601           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.185           ms/op
ClientGrpc.getUser                        sample  313468   3.062 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.480           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.619           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.743           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.873           ms/op
ClientGrpc.listUser                       sample  238408   4.027 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.765           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.238           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.108           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.658           ms/op
