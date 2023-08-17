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
# Warmup Iteration   1: 4.195 ops/ms
# Warmup Iteration   2: 9.308 ops/ms
# Warmup Iteration   3: 10.049 ops/ms
Iteration   1: 10.408 ops/ms
Iteration   2: 10.265 ops/ms
Iteration   3: 10.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.434 ±(99.9%) 3.342 ops/ms [Average]
  (min, avg, max) = (10.265, 10.434, 10.628), stdev = 0.183
  CI (99.9%): [7.092, 13.775] (assumes normal distribution)


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
# Warmup Iteration   1: 7.396 ops/ms
# Warmup Iteration   2: 10.411 ops/ms
# Warmup Iteration   3: 10.900 ops/ms
Iteration   1: 11.066 ops/ms
Iteration   2: 10.981 ops/ms
Iteration   3: 11.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.050 ±(99.9%) 1.130 ops/ms [Average]
  (min, avg, max) = (10.981, 11.050, 11.102), stdev = 0.062
  CI (99.9%): [9.920, 12.179] (assumes normal distribution)


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
# Warmup Iteration   1: 6.922 ops/ms
# Warmup Iteration   2: 10.242 ops/ms
# Warmup Iteration   3: 10.343 ops/ms
Iteration   1: 10.519 ops/ms
Iteration   2: 10.539 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.545 ±(99.9%) 0.532 ops/ms [Average]
  (min, avg, max) = (10.519, 10.545, 10.577), stdev = 0.029
  CI (99.9%): [10.013, 11.077] (assumes normal distribution)


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
# Warmup Iteration   1: 5.346 ops/ms
# Warmup Iteration   2: 7.732 ops/ms
# Warmup Iteration   3: 7.984 ops/ms
Iteration   1: 8.135 ops/ms
Iteration   2: 8.210 ops/ms
Iteration   3: 8.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.143 ±(99.9%) 1.166 ops/ms [Average]
  (min, avg, max) = (8.083, 8.143, 8.210), stdev = 0.064
  CI (99.9%): [6.977, 9.309] (assumes normal distribution)


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
# Warmup Iteration   1: 4.350 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.003 ms/op
Iteration   1: 3.097 ±(99.9%) 0.002 ms/op
Iteration   2: 3.034 ±(99.9%) 0.002 ms/op
Iteration   3: 3.043 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.058 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (3.034, 3.058, 3.097), stdev = 0.034
  CI (99.9%): [2.442, 3.674] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.002 ms/op
Iteration   1: 2.918 ±(99.9%) 0.003 ms/op
Iteration   2: 2.868 ±(99.9%) 0.003 ms/op
Iteration   3: 2.940 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.909 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (2.868, 2.909, 2.940), stdev = 0.037
  CI (99.9%): [2.236, 3.582] (assumes normal distribution)


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
# Warmup Iteration   1: 4.377 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.003 ms/op
Iteration   1: 3.037 ±(99.9%) 0.004 ms/op
Iteration   2: 3.070 ±(99.9%) 0.004 ms/op
Iteration   3: 3.031 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.046 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (3.031, 3.046, 3.070), stdev = 0.021
  CI (99.9%): [2.659, 3.433] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.958 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.022 ms/op
Iteration   1: 3.969 ±(99.9%) 0.020 ms/op
Iteration   2: 4.040 ±(99.9%) 0.025 ms/op
Iteration   3: 3.933 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.981 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (3.933, 3.981, 4.040), stdev = 0.054
  CI (99.9%): [2.991, 4.970] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.848 ms/op
                 createUser·p0.99:   4.796 ms/op
                 createUser·p0.999:  8.245 ms/op
                 createUser·p0.9999: 13.278 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  9.077 ms/op
                 createUser·p0.9999: 18.416 ms/op
                 createUser·p1.00:   19.988 ms/op

Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.680 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.061 ms/op
                 createUser·p0.9999: 17.017 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317339
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 938 
    [ 1.250,  2.500) = 21058 
    [ 2.500,  3.750) = 279612 
    [ 3.750,  5.000) = 13603 
    [ 5.000,  6.250) = 794 
    [ 6.250,  7.500) = 747 
    [ 7.500,  8.750) = 279 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     17.909 ms/op
     p(99.9990) =     19.694 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.406 ms/op
                 existUser·p0.9999: 14.330 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  9.760 ms/op
                 existUser·p0.9999: 19.359 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   3: 2.929 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.792 ms/op
                 existUser·p0.999:  7.854 ms/op
                 existUser·p0.9999: 20.646 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323595
  mean =      2.966 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31944 
    [ 2.500,  5.000) = 289204 
    [ 5.000,  7.500) = 1891 
    [ 7.500, 10.000) = 334 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      8.674 ms/op
     p(99.9900) =     20.108 ms/op
     p(99.9990) =     21.062 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
Iteration   1: 3.128 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.893 ms/op
                 getUser·p0.9999: 17.491 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.456 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.088 ms/op
                 getUser·p0.999:  9.218 ms/op
                 getUser·p0.9999: 20.307 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  8.038 ms/op
                 getUser·p0.9999: 20.382 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307893
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16545 
    [ 2.500,  5.000) = 288818 
    [ 5.000,  7.500) = 1948 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =      8.315 ms/op
     p(99.9900) =     20.251 ms/op
     p(99.9990) =     21.218 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 5.368 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.012 ms/op
Iteration   1: 3.986 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.562 ms/op
                 listUser·p0.9999: 16.661 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   2: 3.981 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  16.182 ms/op
                 listUser·p0.9999: 24.608 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   3: 4.031 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.767 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  16.360 ms/op
                 listUser·p0.9999: 24.021 ms/op
                 listUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240015
  mean =      3.999 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3006 
    [ 2.500,  5.000) = 211933 
    [ 5.000,  7.500) = 23249 
    [ 7.500, 10.000) = 1417 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.216 ms/op
     p(99.9000) =     15.302 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     25.638 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.434 ± 3.342  ops/ms
ClientGrpc.existUser                       thrpt       3  11.050 ± 1.130  ops/ms
ClientGrpc.getUser                         thrpt       3  10.545 ± 0.532  ops/ms
ClientGrpc.listUser                        thrpt       3   8.143 ± 1.166  ops/ms
ClientGrpc.createUser                       avgt       3   3.058 ± 0.616   ms/op
ClientGrpc.existUser                        avgt       3   2.909 ± 0.673   ms/op
ClientGrpc.getUser                          avgt       3   3.046 ± 0.387   ms/op
ClientGrpc.listUser                         avgt       3   3.981 ± 0.990   ms/op
ClientGrpc.createUser                     sample  317339   3.023 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.713           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.651           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.909           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.988           ms/op
ClientGrpc.existUser                      sample  323595   2.966 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.714           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.674           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.108           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.135           ms/op
ClientGrpc.getUser                        sample  307893   3.117 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.456           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.315           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.251           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.398           ms/op
ClientGrpc.listUser                       sample  240015   3.999 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.767           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.216           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.302           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.953           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.821           ms/op
