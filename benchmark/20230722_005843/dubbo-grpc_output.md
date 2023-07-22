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
# Warmup Iteration   1: 2.538 ops/ms
# Warmup Iteration   2: 5.960 ops/ms
# Warmup Iteration   3: 7.121 ops/ms
Iteration   1: 7.389 ops/ms
Iteration   2: 7.740 ops/ms
Iteration   3: 7.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.577 ±(99.9%) 3.221 ops/ms [Average]
  (min, avg, max) = (7.389, 7.577, 7.740), stdev = 0.177
  CI (99.9%): [4.355, 10.798] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.084 ops/ms
# Warmup Iteration   2: 7.250 ops/ms
# Warmup Iteration   3: 7.799 ops/ms
Iteration   1: 7.907 ops/ms
Iteration   2: 7.746 ops/ms
Iteration   3: 7.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.797 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (7.737, 7.797, 7.907), stdev = 0.096
  CI (99.9%): [6.049, 9.545] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.935 ops/ms
# Warmup Iteration   2: 6.811 ops/ms
# Warmup Iteration   3: 7.460 ops/ms
Iteration   1: 7.670 ops/ms
Iteration   2: 7.535 ops/ms
Iteration   3: 7.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.610 ±(99.9%) 1.262 ops/ms [Average]
  (min, avg, max) = (7.535, 7.610, 7.670), stdev = 0.069
  CI (99.9%): [6.348, 8.873] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.930 ops/ms
# Warmup Iteration   2: 5.501 ops/ms
# Warmup Iteration   3: 6.070 ops/ms
Iteration   1: 6.011 ops/ms
Iteration   2: 6.124 ops/ms
Iteration   3: 6.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.161 ±(99.9%) 3.146 ops/ms [Average]
  (min, avg, max) = (6.011, 6.161, 6.349), stdev = 0.172
  CI (99.9%): [3.015, 9.308] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.454 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.396 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.319 ±(99.9%) 0.011 ms/op
Iteration   1: 4.143 ±(99.9%) 0.004 ms/op
Iteration   2: 4.186 ±(99.9%) 0.002 ms/op
Iteration   3: 4.091 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.140 ±(99.9%) 0.867 ms/op [Average]
  (min, avg, max) = (4.091, 4.140, 4.186), stdev = 0.048
  CI (99.9%): [3.273, 5.007] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.112 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.004 ms/op
Iteration   1: 3.882 ±(99.9%) 0.003 ms/op
Iteration   2: 3.818 ±(99.9%) 0.003 ms/op
Iteration   3: 3.940 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.880 ±(99.9%) 1.114 ms/op [Average]
  (min, avg, max) = (3.818, 3.880, 3.940), stdev = 0.061
  CI (99.9%): [2.766, 4.994] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.404 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.005 ms/op
Iteration   1: 4.094 ±(99.9%) 0.004 ms/op
Iteration   2: 4.111 ±(99.9%) 0.003 ms/op
Iteration   3: 4.139 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.115 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (4.094, 4.115, 4.139), stdev = 0.022
  CI (99.9%): [3.708, 4.521] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.602 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.532 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.276 ±(99.9%) 0.018 ms/op
Iteration   1: 5.266 ±(99.9%) 0.011 ms/op
Iteration   2: 5.268 ±(99.9%) 0.010 ms/op
Iteration   3: 5.228 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.254 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (5.228, 5.254, 5.268), stdev = 0.023
  CI (99.9%): [4.843, 5.665] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.622 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.293 ±(99.9%) 0.013 ms/op
Iteration   1: 4.146 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.554 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  12.579 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 4.125 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.620 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  12.293 ms/op
                 createUser·p0.9999: 22.061 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 4.139 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.440 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   7.545 ms/op
                 createUser·p0.999:  12.226 ms/op
                 createUser·p0.9999: 25.895 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 232198
  mean =      4.137 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4401 
    [ 2.500,  5.000) = 198526 
    [ 5.000,  7.500) = 27185 
    [ 7.500, 10.000) = 1606 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     12.252 ms/op
     p(99.9900) =     24.922 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.738 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.010 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  10.252 ms/op
                 existUser·p0.9999: 20.182 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   2: 3.791 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   6.717 ms/op
                 existUser·p0.999:  13.472 ms/op
                 existUser·p0.9999: 20.189 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   3: 4.043 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  12.106 ms/op
                 existUser·p0.9999: 25.398 ms/op
                 existUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243755
  mean =      3.936 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7647 
    [ 2.500,  5.000) = 213921 
    [ 5.000,  7.500) = 20488 
    [ 7.500, 10.000) = 1272 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     12.329 ms/op
     p(99.9900) =     23.289 ms/op
     p(99.9990) =     25.741 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.615 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.012 ms/op
Iteration   1: 4.153 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   7.840 ms/op
                 getUser·p0.999:  10.977 ms/op
                 getUser·p0.9999: 15.219 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 4.158 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  11.308 ms/op
                 getUser·p0.9999: 25.995 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 4.063 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.439 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  13.011 ms/op
                 getUser·p0.9999: 24.060 ms/op
                 getUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 232695
  mean =      4.124 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4904 
    [ 2.500,  5.000) = 199781 
    [ 5.000,  7.500) = 25819 
    [ 7.500, 10.000) = 1674 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      7.398 ms/op
     p(99.9000) =     12.123 ms/op
     p(99.9900) =     25.443 ms/op
     p(99.9990) =     26.171 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.592 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.682 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.624 ±(99.9%) 0.023 ms/op
Iteration   1: 5.544 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  18.340 ms/op
                 listUser·p0.9999: 23.576 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 5.624 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   7.864 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 23.808 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   3: 5.629 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   5.226 ms/op
                 listUser·p0.90:   7.660 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  31.556 ms/op
                 listUser·p0.9999: 40.214 ms/op
                 listUser·p1.00:   40.960 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171464
  mean =      5.599 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 71416 
    [ 5.000, 10.000) = 96694 
    [10.000, 15.000) = 2906 
    [15.000, 20.000) = 273 
    [20.000, 25.000) = 110 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 27 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.505 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      7.725 ms/op
     p(95.0000) =      8.700 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     20.203 ms/op
     p(99.9900) =     39.640 ms/op
     p(99.9990) =     40.726 ms/op
     p(99.9999) =     40.960 ms/op
    p(100.0000) =     40.960 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.577 ± 3.221  ops/ms
ClientGrpc.existUser                       thrpt       3   7.797 ± 1.748  ops/ms
ClientGrpc.getUser                         thrpt       3   7.610 ± 1.262  ops/ms
ClientGrpc.listUser                        thrpt       3   6.161 ± 3.146  ops/ms
ClientGrpc.createUser                       avgt       3   4.140 ± 0.867   ms/op
ClientGrpc.existUser                        avgt       3   3.880 ± 1.114   ms/op
ClientGrpc.getUser                          avgt       3   4.115 ± 0.406   ms/op
ClientGrpc.listUser                         avgt       3   5.254 ± 0.411   ms/op
ClientGrpc.createUser                     sample  232198   4.137 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.440           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.161           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.332           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.252           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.922           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.313           ms/op
ClientGrpc.existUser                      sample  243755   3.936 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.752           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.932           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.423           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.971           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.329           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.289           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.788           ms/op
ClientGrpc.getUser                        sample  232695   4.124 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.961           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.112           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.554           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.398           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.123           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.443           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.378           ms/op
ClientGrpc.listUser                       sample  171464   5.599 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.505           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.725           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.700           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.141           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.203           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          39.640           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.960           ms/op
