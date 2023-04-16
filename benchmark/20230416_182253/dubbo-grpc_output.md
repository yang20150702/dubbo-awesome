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
# Warmup Iteration   1: 4.172 ops/ms
# Warmup Iteration   2: 9.046 ops/ms
# Warmup Iteration   3: 10.163 ops/ms
Iteration   1: 10.480 ops/ms
Iteration   2: 10.786 ops/ms
Iteration   3: 10.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.636 ±(99.9%) 2.790 ops/ms [Average]
  (min, avg, max) = (10.480, 10.636, 10.786), stdev = 0.153
  CI (99.9%): [7.846, 13.426] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.923 ops/ms
# Warmup Iteration   2: 10.713 ops/ms
# Warmup Iteration   3: 11.084 ops/ms
Iteration   1: 11.145 ops/ms
Iteration   2: 11.415 ops/ms
Iteration   3: 11.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.240 ±(99.9%) 2.766 ops/ms [Average]
  (min, avg, max) = (11.145, 11.240, 11.415), stdev = 0.152
  CI (99.9%): [8.474, 14.005] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.848 ops/ms
# Warmup Iteration   2: 10.158 ops/ms
# Warmup Iteration   3: 10.382 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.476 ops/ms
Iteration   3: 10.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.605 ±(99.9%) 2.033 ops/ms [Average]
  (min, avg, max) = (10.476, 10.605, 10.674), stdev = 0.111
  CI (99.9%): [8.571, 12.638] (assumes normal distribution)


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
# Warmup Iteration   1: 6.104 ops/ms
# Warmup Iteration   2: 7.940 ops/ms
# Warmup Iteration   3: 8.166 ops/ms
Iteration   1: 8.389 ops/ms
Iteration   2: 8.319 ops/ms
Iteration   3: 8.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.321 ±(99.9%) 1.213 ops/ms [Average]
  (min, avg, max) = (8.256, 8.321, 8.389), stdev = 0.066
  CI (99.9%): [7.108, 9.534] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.004 ms/op
Iteration   1: 3.002 ±(99.9%) 0.004 ms/op
Iteration   2: 2.995 ±(99.9%) 0.004 ms/op
Iteration   3: 2.978 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.992 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.978, 2.992, 3.002), stdev = 0.012
  CI (99.9%): [2.772, 3.212] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.119 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.002 ms/op
Iteration   1: 2.889 ±(99.9%) 0.004 ms/op
Iteration   2: 2.891 ±(99.9%) 0.003 ms/op
Iteration   3: 2.865 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.882 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.865, 2.882, 2.891), stdev = 0.014
  CI (99.9%): [2.618, 3.146] (assumes normal distribution)


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
# Warmup Iteration   1: 4.353 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.004 ms/op
Iteration   1: 2.976 ±(99.9%) 0.003 ms/op
Iteration   2: 2.992 ±(99.9%) 0.005 ms/op
Iteration   3: 2.958 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.975 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.958, 2.975, 2.992), stdev = 0.017
  CI (99.9%): [2.664, 3.286] (assumes normal distribution)


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
# Warmup Iteration   1: 5.052 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.008 ms/op
Iteration   1: 3.889 ±(99.9%) 0.016 ms/op
Iteration   2: 3.909 ±(99.9%) 0.013 ms/op
Iteration   3: 3.853 ±(99.9%) 0.047 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.884 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (3.853, 3.884, 3.909), stdev = 0.028
  CI (99.9%): [3.373, 4.394] (assumes normal distribution)


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
# Warmup Iteration   1: 4.362 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.676 ms/op
                 createUser·p0.9999: 17.350 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  6.812 ms/op
                 createUser·p0.9999: 13.821 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  10.289 ms/op
                 createUser·p0.9999: 20.117 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317713
  mean =      3.020 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28593 
    [ 2.500,  5.000) = 287875 
    [ 5.000,  7.500) = 917 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.414 ms/op
     p(99.9000) =      7.569 ms/op
     p(99.9900) =     17.138 ms/op
     p(99.9990) =     21.089 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
Iteration   1: 2.869 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.434 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.512 ms/op
                 existUser·p0.9999: 12.709 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.853 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  6.799 ms/op
                 existUser·p0.9999: 16.528 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   3: 2.876 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.850 ms/op
                 existUser·p0.9999: 16.937 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334953
  mean =      2.866 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1116 
    [ 1.250,  2.500) = 43847 
    [ 2.500,  3.750) = 282327 
    [ 3.750,  5.000) = 6879 
    [ 5.000,  6.250) = 318 
    [ 6.250,  7.500) = 184 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.070 ms/op
     p(99.9900) =     16.638 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.667 ms/op
                 getUser·p0.9999: 15.752 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.834 ms/op
                 getUser·p0.9999: 14.082 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 3.007 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  6.768 ms/op
                 getUser·p0.9999: 27.427 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317609
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26470 
    [ 2.500,  5.000) = 289598 
    [ 5.000,  7.500) = 1256 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.114 ms/op
     p(99.9900) =     25.206 ms/op
     p(99.9990) =     27.749 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 5.282 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.012 ms/op
Iteration   1: 3.878 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.691 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 21.414 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   2: 3.894 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 19.757 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 22.092 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247399
  mean =      3.879 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2767 
    [ 2.500,  5.000) = 226482 
    [ 5.000,  7.500) = 17055 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     14.834 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     23.151 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.636 ± 2.790  ops/ms
ClientGrpc.existUser                       thrpt       3  11.240 ± 2.766  ops/ms
ClientGrpc.getUser                         thrpt       3  10.605 ± 2.033  ops/ms
ClientGrpc.listUser                        thrpt       3   8.321 ± 1.213  ops/ms
ClientGrpc.createUser                       avgt       3   2.992 ± 0.220   ms/op
ClientGrpc.existUser                        avgt       3   2.882 ± 0.264   ms/op
ClientGrpc.getUser                          avgt       3   2.975 ± 0.311   ms/op
ClientGrpc.listUser                         avgt       3   3.884 ± 0.511   ms/op
ClientGrpc.createUser                     sample  317713   3.020 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.571           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.414           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.569           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.138           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.234           ms/op
ClientGrpc.existUser                      sample  334953   2.866 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.434           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.070           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.638           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  317609   3.021 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.751           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.114           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.206           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.886           ms/op
ClientGrpc.listUser                       sample  247399   3.879 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.108           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.694           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.834           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.594           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.233           ms/op
