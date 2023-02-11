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
# Warmup Iteration   1: 4.836 ops/ms
# Warmup Iteration   2: 9.214 ops/ms
# Warmup Iteration   3: 9.997 ops/ms
Iteration   1: 10.398 ops/ms
Iteration   2: 10.028 ops/ms
Iteration   3: 9.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.089 ±(99.9%) 5.160 ops/ms [Average]
  (min, avg, max) = (9.843, 10.089, 10.398), stdev = 0.283
  CI (99.9%): [4.930, 15.249] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.260 ops/ms
# Warmup Iteration   2: 10.455 ops/ms
# Warmup Iteration   3: 10.570 ops/ms
Iteration   1: 10.905 ops/ms
Iteration   2: 10.831 ops/ms
Iteration   3: 10.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.830 ±(99.9%) 1.370 ops/ms [Average]
  (min, avg, max) = (10.755, 10.830, 10.905), stdev = 0.075
  CI (99.9%): [9.460, 12.201] (assumes normal distribution)


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
# Warmup Iteration   1: 7.728 ops/ms
# Warmup Iteration   2: 9.982 ops/ms
# Warmup Iteration   3: 10.211 ops/ms
Iteration   1: 10.137 ops/ms
Iteration   2: 9.831 ops/ms
Iteration   3: 10.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.001 ±(99.9%) 2.837 ops/ms [Average]
  (min, avg, max) = (9.831, 10.001, 10.137), stdev = 0.155
  CI (99.9%): [7.164, 12.838] (assumes normal distribution)


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
# Warmup Iteration   1: 7.190 ops/ms
# Warmup Iteration   2: 7.226 ops/ms
# Warmup Iteration   3: 7.684 ops/ms
Iteration   1: 7.727 ops/ms
Iteration   2: 7.756 ops/ms
Iteration   3: 7.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.687 ±(99.9%) 1.741 ops/ms [Average]
  (min, avg, max) = (7.578, 7.687, 7.756), stdev = 0.095
  CI (99.9%): [5.946, 9.428] (assumes normal distribution)


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.002 ms/op
Iteration   1: 3.148 ±(99.9%) 0.003 ms/op
Iteration   2: 3.167 ±(99.9%) 0.003 ms/op
Iteration   3: 3.223 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.179 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (3.148, 3.179, 3.223), stdev = 0.039
  CI (99.9%): [2.463, 3.896] (assumes normal distribution)


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.002 ms/op
Iteration   1: 3.021 ±(99.9%) 0.002 ms/op
Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
Iteration   3: 2.999 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.998 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (2.975, 2.998, 3.021), stdev = 0.023
  CI (99.9%): [2.580, 3.417] (assumes normal distribution)


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
# Warmup Iteration   1: 4.057 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.002 ms/op
Iteration   1: 3.095 ±(99.9%) 0.002 ms/op
Iteration   2: 3.126 ±(99.9%) 0.002 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.106 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (3.095, 3.106, 3.126), stdev = 0.017
  CI (99.9%): [2.796, 3.417] (assumes normal distribution)


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
# Warmup Iteration   1: 5.307 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.016 ms/op
Iteration   1: 4.129 ±(99.9%) 0.015 ms/op
Iteration   2: 4.088 ±(99.9%) 0.014 ms/op
Iteration   3: 4.146 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.121 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (4.088, 4.121, 4.146), stdev = 0.029
  CI (99.9%): [3.583, 4.659] (assumes normal distribution)


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  6.872 ms/op
                 createUser·p0.9999: 11.508 ms/op
                 createUser·p1.00:   11.878 ms/op

Iteration   2: 3.211 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  9.383 ms/op
                 createUser·p0.9999: 13.173 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   3: 3.150 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.363 ms/op
                 createUser·p0.9999: 23.883 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303325
  mean =      3.164 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22161 
    [ 2.500,  5.000) = 279936 
    [ 5.000,  7.500) = 790 
    [ 7.500, 10.000) = 182 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     22.861 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.007 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.322 ms/op
                 existUser·p0.9999: 12.894 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   2: 3.021 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  9.525 ms/op
                 existUser·p0.9999: 24.753 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  7.887 ms/op
                 existUser·p0.9999: 15.878 ms/op
                 existUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318365
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37856 
    [ 2.500,  5.000) = 279681 
    [ 5.000,  7.500) = 457 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.945 ms/op
     p(99.9900) =     23.986 ms/op
     p(99.9990) =     24.963 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
Iteration   1: 3.093 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.318 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  10.577 ms/op
                 getUser·p0.9999: 14.920 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.076 ms/op
                 getUser·p0.9999: 24.476 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   3: 3.138 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.179 ms/op
                 getUser·p0.9999: 15.444 ms/op
                 getUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305564
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20830 
    [ 2.500,  5.000) = 283726 
    [ 5.000,  7.500) = 543 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.318 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     23.819 ms/op
     p(99.9990) =     24.804 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 4.895 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.169 ±(99.9%) 0.013 ms/op
Iteration   1: 4.133 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 19.875 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   2: 3.992 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.722 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 22.707 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   3: 4.148 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.156 ms/op
                 listUser·p0.999:  14.594 ms/op
                 listUser·p0.9999: 16.912 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234731
  mean =      4.090 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4321 
    [ 2.500,  5.000) = 195161 
    [ 5.000,  7.500) = 33773 
    [ 7.500, 10.000) = 1000 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     14.717 ms/op
     p(99.9900) =     22.168 ms/op
     p(99.9990) =     22.980 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.089 ± 5.160  ops/ms
ClientGrpc.existUser                       thrpt       3  10.830 ± 1.370  ops/ms
ClientGrpc.getUser                         thrpt       3  10.001 ± 2.837  ops/ms
ClientGrpc.listUser                        thrpt       3   7.687 ± 1.741  ops/ms
ClientGrpc.createUser                       avgt       3   3.179 ± 0.717   ms/op
ClientGrpc.existUser                        avgt       3   2.998 ± 0.419   ms/op
ClientGrpc.getUser                          avgt       3   3.106 ± 0.310   ms/op
ClientGrpc.listUser                         avgt       3   4.121 ± 0.538   ms/op
ClientGrpc.createUser                     sample  303325   3.164 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.679           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.047           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.487           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.861           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.084           ms/op
ClientGrpc.existUser                      sample  318365   3.014 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.584           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.945           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.986           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.559           ms/op
ClientGrpc.getUser                        sample  305564   3.140 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.318           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.716           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.819           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.904           ms/op
ClientGrpc.listUser                       sample  234731   4.090 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.722           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.717           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.168           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.101           ms/op
