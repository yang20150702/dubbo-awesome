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
# Warmup Iteration   1: 4.802 ops/ms
# Warmup Iteration   2: 9.719 ops/ms
# Warmup Iteration   3: 10.431 ops/ms
Iteration   1: 10.571 ops/ms
Iteration   2: 10.885 ops/ms
Iteration   3: 10.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.765 ±(99.9%) 3.096 ops/ms [Average]
  (min, avg, max) = (10.571, 10.765, 10.885), stdev = 0.170
  CI (99.9%): [7.669, 13.860] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.849 ops/ms
# Warmup Iteration   2: 11.192 ops/ms
# Warmup Iteration   3: 11.311 ops/ms
Iteration   1: 11.298 ops/ms
Iteration   2: 11.320 ops/ms
Iteration   3: 11.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.261 ±(99.9%) 1.547 ops/ms [Average]
  (min, avg, max) = (11.164, 11.261, 11.320), stdev = 0.085
  CI (99.9%): [9.714, 12.808] (assumes normal distribution)


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
# Warmup Iteration   1: 7.622 ops/ms
# Warmup Iteration   2: 10.550 ops/ms
# Warmup Iteration   3: 10.773 ops/ms
Iteration   1: 10.741 ops/ms
Iteration   2: 10.977 ops/ms
Iteration   3: 10.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.781 ±(99.9%) 3.267 ops/ms [Average]
  (min, avg, max) = (10.625, 10.781, 10.977), stdev = 0.179
  CI (99.9%): [7.514, 14.048] (assumes normal distribution)


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
# Warmup Iteration   1: 6.872 ops/ms
# Warmup Iteration   2: 8.023 ops/ms
# Warmup Iteration   3: 8.213 ops/ms
Iteration   1: 8.236 ops/ms
Iteration   2: 8.276 ops/ms
Iteration   3: 8.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.234 ±(99.9%) 0.790 ops/ms [Average]
  (min, avg, max) = (8.189, 8.234, 8.276), stdev = 0.043
  CI (99.9%): [7.444, 9.024] (assumes normal distribution)


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
# Warmup Iteration   1: 3.877 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.004 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 2.958 ±(99.9%) 0.003 ms/op
Iteration   3: 3.026 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.992 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (2.958, 2.992, 3.026), stdev = 0.034
  CI (99.9%): [2.367, 3.617] (assumes normal distribution)


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
# Warmup Iteration   1: 3.652 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.002 ms/op
Iteration   1: 2.723 ±(99.9%) 0.004 ms/op
Iteration   2: 2.838 ±(99.9%) 0.003 ms/op
Iteration   3: 2.845 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.802 ±(99.9%) 1.249 ms/op [Average]
  (min, avg, max) = (2.723, 2.802, 2.845), stdev = 0.068
  CI (99.9%): [1.553, 4.052] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.038 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.003 ms/op
Iteration   1: 2.936 ±(99.9%) 0.003 ms/op
Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
Iteration   3: 3.040 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.994 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (2.936, 2.994, 3.040), stdev = 0.053
  CI (99.9%): [2.028, 3.960] (assumes normal distribution)


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
# Warmup Iteration   1: 5.241 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.020 ms/op
Iteration   1: 3.891 ±(99.9%) 0.017 ms/op
Iteration   2: 3.870 ±(99.9%) 0.021 ms/op
Iteration   3: 3.850 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.870 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.850, 3.870, 3.891), stdev = 0.020
  CI (99.9%): [3.503, 4.238] (assumes normal distribution)


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.007 ms/op
Iteration   1: 2.965 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  8.289 ms/op
                 createUser·p0.9999: 15.942 ms/op
                 createUser·p1.00:   16.597 ms/op

Iteration   2: 2.940 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.038 ms/op
                 createUser·p0.9999: 30.933 ms/op
                 createUser·p1.00:   31.752 ms/op

Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.860 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322353
  mean =      2.978 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29692 
    [ 2.500,  5.000) = 290909 
    [ 5.000,  7.500) = 1302 
    [ 7.500, 10.000) = 249 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.066 ms/op
     p(99.9900) =     22.756 ms/op
     p(99.9990) =     31.490 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.924 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.888 ±(99.9%) 0.006 ms/op
Iteration   1: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.676 ms/op
                 existUser·p0.9999: 11.582 ms/op
                 existUser·p1.00:   11.895 ms/op

Iteration   2: 2.809 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  6.995 ms/op
                 existUser·p0.9999: 22.138 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   3: 2.873 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.600 ms/op
                 existUser·p0.9999: 17.264 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335707
  mean =      2.859 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47922 
    [ 2.500,  5.000) = 286119 
    [ 5.000,  7.500) = 1329 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.506 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     22.303 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
Iteration   1: 3.013 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  10.789 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   2: 3.005 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  10.149 ms/op
                 getUser·p0.9999: 20.426 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   3: 3.001 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.472 ms/op
                 getUser·p0.999:  7.197 ms/op
                 getUser·p0.9999: 38.863 ms/op
                 getUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319242
  mean =      3.007 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27946 
    [ 2.500,  5.000) = 289516 
    [ 5.000,  7.500) = 1352 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      9.663 ms/op
     p(99.9900) =     37.950 ms/op
     p(99.9990) =     39.059 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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
# Warmup Iteration   1: 5.376 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.011 ms/op
Iteration   1: 3.920 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  12.409 ms/op
                 listUser·p0.9999: 13.681 ms/op
                 listUser·p1.00:   14.107 ms/op

Iteration   2: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.672 ms/op
                 listUser·p0.9999: 23.523 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 3.823 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  21.200 ms/op
                 listUser·p0.9999: 41.130 ms/op
                 listUser·p1.00:   42.664 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247140
  mean =      3.889 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 223940 
    [ 5.000, 10.000) = 22721 
    [10.000, 15.000) = 303 
    [15.000, 20.000) = 48 
    [20.000, 25.000) = 92 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     13.809 ms/op
     p(99.9900) =     40.211 ms/op
     p(99.9990) =     42.340 ms/op
     p(99.9999) =     42.664 ms/op
    p(100.0000) =     42.664 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.765 ± 3.096  ops/ms
ClientGrpc.existUser                       thrpt       3  11.261 ± 1.547  ops/ms
ClientGrpc.getUser                         thrpt       3  10.781 ± 3.267  ops/ms
ClientGrpc.listUser                        thrpt       3   8.234 ± 0.790  ops/ms
ClientGrpc.createUser                       avgt       3   2.992 ± 0.625   ms/op
ClientGrpc.existUser                        avgt       3   2.802 ± 1.249   ms/op
ClientGrpc.getUser                          avgt       3   2.994 ± 0.966   ms/op
ClientGrpc.listUser                         avgt       3   3.870 ± 0.367   ms/op
ClientGrpc.createUser                     sample  322353   2.978 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.659           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.066           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.756           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.752           ms/op
ClientGrpc.existUser                      sample  335707   2.859 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.693           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.506           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.235           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.381           ms/op
ClientGrpc.getUser                        sample  319242   3.007 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.569           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.663           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          37.950           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          39.191           ms/op
ClientGrpc.listUser                       sample  247140   3.889 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.761           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.809           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          40.211           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          42.664           ms/op
