# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.663 ops/ms
# Warmup Iteration   2: 9.870 ops/ms
# Warmup Iteration   3: 10.479 ops/ms
Iteration   1: 10.904 ops/ms
Iteration   2: 11.151 ops/ms
Iteration   3: 10.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.933 ±(99.9%) 3.748 ops/ms [Average]
  (min, avg, max) = (10.744, 10.933, 11.151), stdev = 0.205
  CI (99.9%): [7.184, 14.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.204 ops/ms
# Warmup Iteration   2: 10.917 ops/ms
# Warmup Iteration   3: 11.297 ops/ms
Iteration   1: 11.268 ops/ms
Iteration   2: 11.178 ops/ms
Iteration   3: 11.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.255 ±(99.9%) 1.318 ops/ms [Average]
  (min, avg, max) = (11.178, 11.255, 11.321), stdev = 0.072
  CI (99.9%): [9.937, 12.573] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.023 ops/ms
# Warmup Iteration   2: 10.653 ops/ms
# Warmup Iteration   3: 11.019 ops/ms
Iteration   1: 11.004 ops/ms
Iteration   2: 10.927 ops/ms
Iteration   3: 11.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  11.015 ±(99.9%) 1.697 ops/ms [Average]
  (min, avg, max) = (10.927, 11.015, 11.112), stdev = 0.093
  CI (99.9%): [9.318, 12.712] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.564 ops/ms
# Warmup Iteration   2: 8.392 ops/ms
# Warmup Iteration   3: 8.351 ops/ms
Iteration   1: 8.588 ops/ms
Iteration   2: 8.676 ops/ms
Iteration   3: 8.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.587 ±(99.9%) 1.643 ops/ms [Average]
  (min, avg, max) = (8.496, 8.587, 8.676), stdev = 0.090
  CI (99.9%): [6.944, 10.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.944 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 2.971 ±(99.9%) 0.003 ms/op
Iteration   3: 3.021 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.978 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (2.943, 2.978, 3.021), stdev = 0.039
  CI (99.9%): [2.265, 3.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.898 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.858 ±(99.9%) 0.003 ms/op
Iteration   1: 2.831 ±(99.9%) 0.003 ms/op
Iteration   2: 2.808 ±(99.9%) 0.005 ms/op
Iteration   3: 2.793 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.811 ±(99.9%) 0.350 ms/op [Average]
  (min, avg, max) = (2.793, 2.811, 2.831), stdev = 0.019
  CI (99.9%): [2.461, 3.161] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.003 ms/op
Iteration   1: 2.896 ±(99.9%) 0.002 ms/op
Iteration   2: 2.923 ±(99.9%) 0.003 ms/op
Iteration   3: 2.895 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.905 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.895, 2.905, 2.923), stdev = 0.016
  CI (99.9%): [2.617, 3.192] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.778 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.719 ±(99.9%) 0.018 ms/op
Iteration   1: 3.741 ±(99.9%) 0.013 ms/op
Iteration   2: 3.678 ±(99.9%) 0.054 ms/op
Iteration   3: 3.638 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.686 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (3.638, 3.686, 3.741), stdev = 0.052
  CI (99.9%): [2.743, 4.628] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.088 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.007 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  6.758 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   2: 3.016 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.238 ms/op
                 createUser·p0.9999: 20.873 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   3: 2.947 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.453 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  10.313 ms/op
                 createUser·p0.9999: 23.078 ms/op
                 createUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323518
  mean =      2.969 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31732 
    [ 2.500,  5.000) = 290479 
    [ 5.000,  7.500) = 895 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     21.519 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.668 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.930 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.796 ±(99.9%) 0.006 ms/op
Iteration   1: 2.760 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.497 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.783 ms/op
                 existUser·p0.9999: 12.337 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 2.786 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.546 ms/op
                 existUser·p0.9999: 24.986 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   3: 2.916 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  8.129 ms/op
                 existUser·p0.9999: 16.745 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340620
  mean =      2.819 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61207 
    [ 2.500,  5.000) = 278492 
    [ 5.000,  7.500) = 527 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.715 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     25.322 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.922 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.007 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  10.913 ms/op
                 getUser·p0.9999: 13.212 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.949 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.603 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.828 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   3: 2.943 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  10.164 ms/op
                 getUser·p0.9999: 14.822 ms/op
                 getUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325043
  mean =      2.953 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30501 
    [ 2.500,  5.000) = 293593 
    [ 5.000,  7.500) = 550 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      8.814 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.108 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.889 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.010 ms/op
Iteration   1: 3.889 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  12.869 ms/op
                 listUser·p0.9999: 17.549 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 3.804 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.548 ms/op
                 listUser·p0.9999: 19.058 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.779 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.640 ms/op
                 listUser·p0.999:  14.227 ms/op
                 listUser·p0.9999: 35.752 ms/op
                 listUser·p1.00:   40.370 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250938
  mean =      3.824 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 229572 
    [ 5.000, 10.000) = 20895 
    [10.000, 15.000) = 273 
    [15.000, 20.000) = 164 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     14.173 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     35.946 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.933 ± 3.748  ops/ms
ClientGrpc.existUser                       thrpt       3  11.255 ± 1.318  ops/ms
ClientGrpc.getUser                         thrpt       3  11.015 ± 1.697  ops/ms
ClientGrpc.listUser                        thrpt       3   8.587 ± 1.643  ops/ms
ClientGrpc.createUser                       avgt       3   2.978 ± 0.713   ms/op
ClientGrpc.existUser                        avgt       3   2.811 ± 0.350   ms/op
ClientGrpc.getUser                          avgt       3   2.905 ± 0.287   ms/op
ClientGrpc.listUser                         avgt       3   3.686 ± 0.943   ms/op
ClientGrpc.createUser                     sample  323518   2.969 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.453           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.519           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.019           ms/op
ClientGrpc.existUser                      sample  340620   2.819 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.497           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.843           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.715           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.908           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.428           ms/op
ClientGrpc.getUser                        sample  325043   2.953 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.603           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.945           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.174           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.814           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.823           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.348           ms/op
ClientGrpc.listUser                       sample  250938   3.824 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.894           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.658           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.173           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.062           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.370           ms/op
