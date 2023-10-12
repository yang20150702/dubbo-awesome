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
# Warmup Iteration   1: 3.763 ops/ms
# Warmup Iteration   2: 8.468 ops/ms
# Warmup Iteration   3: 9.801 ops/ms
Iteration   1: 10.038 ops/ms
Iteration   2: 10.143 ops/ms
Iteration   3: 10.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.151 ±(99.9%) 2.126 ops/ms [Average]
  (min, avg, max) = (10.038, 10.151, 10.271), stdev = 0.117
  CI (99.9%): [8.024, 12.277] (assumes normal distribution)


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
# Warmup Iteration   1: 7.183 ops/ms
# Warmup Iteration   2: 10.248 ops/ms
# Warmup Iteration   3: 10.648 ops/ms
Iteration   1: 11.042 ops/ms
Iteration   2: 10.898 ops/ms
Iteration   3: 10.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.911 ±(99.9%) 2.271 ops/ms [Average]
  (min, avg, max) = (10.794, 10.911, 11.042), stdev = 0.124
  CI (99.9%): [8.640, 13.182] (assumes normal distribution)


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
# Warmup Iteration   1: 6.868 ops/ms
# Warmup Iteration   2: 9.933 ops/ms
# Warmup Iteration   3: 10.080 ops/ms
Iteration   1: 10.268 ops/ms
Iteration   2: 10.225 ops/ms
Iteration   3: 10.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.274 ±(99.9%) 0.962 ops/ms [Average]
  (min, avg, max) = (10.225, 10.274, 10.330), stdev = 0.053
  CI (99.9%): [9.313, 11.236] (assumes normal distribution)


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
# Warmup Iteration   1: 5.655 ops/ms
# Warmup Iteration   2: 7.629 ops/ms
# Warmup Iteration   3: 7.889 ops/ms
Iteration   1: 8.026 ops/ms
Iteration   2: 7.947 ops/ms
Iteration   3: 7.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.984 ±(99.9%) 0.732 ops/ms [Average]
  (min, avg, max) = (7.947, 7.984, 8.026), stdev = 0.040
  CI (99.9%): [7.252, 8.717] (assumes normal distribution)


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
# Warmup Iteration   1: 4.364 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.004 ms/op
Iteration   1: 3.097 ±(99.9%) 0.004 ms/op
Iteration   2: 3.116 ±(99.9%) 0.002 ms/op
Iteration   3: 3.126 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.113 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (3.097, 3.113, 3.126), stdev = 0.015
  CI (99.9%): [2.848, 3.378] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.004 ms/op
Iteration   1: 2.989 ±(99.9%) 0.003 ms/op
Iteration   2: 2.971 ±(99.9%) 0.002 ms/op
Iteration   3: 3.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.988 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (2.971, 2.988, 3.005), stdev = 0.017
  CI (99.9%): [2.686, 3.291] (assumes normal distribution)


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.011 ms/op
Iteration   1: 3.116 ±(99.9%) 0.003 ms/op
Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
Iteration   3: 3.141 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.111 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (3.075, 3.111, 3.141), stdev = 0.034
  CI (99.9%): [2.498, 3.723] (assumes normal distribution)


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
# Warmup Iteration   1: 5.084 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.026 ms/op
Iteration   1: 3.915 ±(99.9%) 0.021 ms/op
Iteration   2: 3.866 ±(99.9%) 0.018 ms/op
Iteration   3: 4.034 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.938 ±(99.9%) 1.578 ms/op [Average]
  (min, avg, max) = (3.866, 3.938, 4.034), stdev = 0.087
  CI (99.9%): [2.360, 5.517] (assumes normal distribution)


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.825 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 19.161 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   2: 3.162 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  10.482 ms/op
                 createUser·p0.9999: 16.020 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  15.029 ms/op
                 createUser·p0.9999: 19.128 ms/op
                 createUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308026
  mean =      3.116 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 695 
    [ 1.250,  2.500) = 16320 
    [ 2.500,  3.750) = 266489 
    [ 3.750,  5.000) = 22381 
    [ 5.000,  6.250) = 1080 
    [ 6.250,  7.500) = 472 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =     12.075 ms/op
     p(99.9900) =     18.848 ms/op
     p(99.9990) =     19.754 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 2.958 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.847 ms/op
                 existUser·p0.9999: 12.258 ms/op
                 existUser·p1.00:   12.517 ms/op

Iteration   2: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 14.031 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.754 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  13.009 ms/op
                 existUser·p0.9999: 16.876 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322337
  mean =      2.976 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 965 
    [ 1.250,  2.500) = 28688 
    [ 2.500,  3.750) = 279550 
    [ 3.750,  5.000) = 11489 
    [ 5.000,  6.250) = 809 
    [ 6.250,  7.500) = 352 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      9.907 ms/op
     p(99.9900) =     15.657 ms/op
     p(99.9990) =     17.320 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.008 ms/op
Iteration   1: 3.116 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.957 ms/op
                 getUser·p0.9999: 21.070 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   2: 3.144 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.684 ms/op
                 getUser·p0.9999: 19.721 ms/op
                 getUser·p1.00:   20.054 ms/op

Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.463 ms/op
                 getUser·p0.999:  9.208 ms/op
                 getUser·p0.9999: 20.864 ms/op
                 getUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307078
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10980 
    [ 2.500,  5.000) = 294364 
    [ 5.000,  7.500) = 1337 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     20.653 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 6.245 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.011 ms/op
Iteration   1: 3.944 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.286 ms/op
                 listUser·p0.9999: 16.053 ms/op
                 listUser·p1.00:   16.384 ms/op

Iteration   2: 3.963 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.437 ms/op
                 listUser·p0.9999: 23.852 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   3: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.336 ms/op
                 listUser·p0.9999: 18.439 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242852
  mean =      3.954 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2634 
    [ 2.500,  5.000) = 222063 
    [ 5.000,  7.500) = 16700 
    [ 7.500, 10.000) = 854 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     18.495 ms/op
     p(99.9990) =     25.283 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.151 ± 2.126  ops/ms
ClientGrpc.existUser                       thrpt       3  10.911 ± 2.271  ops/ms
ClientGrpc.getUser                         thrpt       3  10.274 ± 0.962  ops/ms
ClientGrpc.listUser                        thrpt       3   7.984 ± 0.732  ops/ms
ClientGrpc.createUser                       avgt       3   3.113 ± 0.265   ms/op
ClientGrpc.existUser                        avgt       3   2.988 ± 0.303   ms/op
ClientGrpc.getUser                          avgt       3   3.111 ± 0.612   ms/op
ClientGrpc.listUser                         avgt       3   3.938 ± 1.578   ms/op
ClientGrpc.createUser                     sample  308026   3.116 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.763           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.075           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.848           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.956           ms/op
ClientGrpc.existUser                      sample  322337   2.976 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.611           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.907           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.657           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.465           ms/op
ClientGrpc.getUser                        sample  307078   3.125 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.726           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.897           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.653           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.561           ms/op
ClientGrpc.listUser                       sample  242852   3.954 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.855           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.008           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.495           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.297           ms/op
