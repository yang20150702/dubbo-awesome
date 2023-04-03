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
# Warmup Iteration   1: 2.775 ops/ms
# Warmup Iteration   2: 5.684 ops/ms
# Warmup Iteration   3: 7.604 ops/ms
Iteration   1: 8.238 ops/ms
Iteration   2: 7.897 ops/ms
Iteration   3: 8.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.109 ±(99.9%) 3.378 ops/ms [Average]
  (min, avg, max) = (7.897, 8.109, 8.238), stdev = 0.185
  CI (99.9%): [4.731, 11.487] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.763 ops/ms
# Warmup Iteration   2: 7.454 ops/ms
# Warmup Iteration   3: 7.855 ops/ms
Iteration   1: 8.167 ops/ms
Iteration   2: 8.378 ops/ms
Iteration   3: 8.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.280 ±(99.9%) 1.945 ops/ms [Average]
  (min, avg, max) = (8.167, 8.280, 8.378), stdev = 0.107
  CI (99.9%): [6.336, 10.225] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.352 ops/ms
# Warmup Iteration   2: 7.174 ops/ms
# Warmup Iteration   3: 7.839 ops/ms
Iteration   1: 7.765 ops/ms
Iteration   2: 7.829 ops/ms
Iteration   3: 7.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.861 ±(99.9%) 2.113 ops/ms [Average]
  (min, avg, max) = (7.765, 7.861, 7.990), stdev = 0.116
  CI (99.9%): [5.749, 9.974] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ops/ms
# Warmup Iteration   2: 5.801 ops/ms
# Warmup Iteration   3: 6.331 ops/ms
Iteration   1: 6.365 ops/ms
Iteration   2: 6.391 ops/ms
Iteration   3: 6.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.311 ±(99.9%) 2.124 ops/ms [Average]
  (min, avg, max) = (6.177, 6.311, 6.391), stdev = 0.116
  CI (99.9%): [4.187, 8.435] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 4.931 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.002 ms/op
Iteration   1: 2.879 ±(99.9%) 0.002 ms/op
Iteration   2: 2.903 ±(99.9%) 0.003 ms/op
Iteration   3: 2.900 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.894 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (2.879, 2.894, 2.903), stdev = 0.013
  CI (99.9%): [2.656, 3.132] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.773 ±(99.9%) 0.002 ms/op
Iteration   1: 2.888 ±(99.9%) 0.001 ms/op
Iteration   2: 3.093 ±(99.9%) 0.003 ms/op
Iteration   3: 3.331 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.104 ±(99.9%) 4.052 ms/op [Average]
  (min, avg, max) = (2.888, 3.104, 3.331), stdev = 0.222
  CI (99.9%): [≈ 0, 7.156] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.751 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.003 ms/op
Iteration   1: 4.382 ±(99.9%) 0.003 ms/op
Iteration   2: 4.489 ±(99.9%) 0.002 ms/op
Iteration   3: 4.437 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.436 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (4.382, 4.436, 4.489), stdev = 0.054
  CI (99.9%): [3.456, 5.416] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.308 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 6.159 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.539 ±(99.9%) 0.021 ms/op
Iteration   1: 5.326 ±(99.9%) 0.010 ms/op
Iteration   2: 5.076 ±(99.9%) 0.006 ms/op
Iteration   3: 5.174 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.192 ±(99.9%) 2.303 ms/op [Average]
  (min, avg, max) = (5.076, 5.192, 5.326), stdev = 0.126
  CI (99.9%): [2.889, 7.495] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.833 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.852 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.339 ±(99.9%) 0.011 ms/op
Iteration   1: 4.204 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   4.133 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.250 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  9.642 ms/op
                 createUser·p0.9999: 15.840 ms/op
                 createUser·p1.00:   16.220 ms/op

Iteration   2: 4.328 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.226 ms/op
                 createUser·p0.95:   5.554 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  10.620 ms/op
                 createUser·p0.9999: 22.269 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 4.504 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.308 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  16.040 ms/op
                 createUser·p0.9999: 31.031 ms/op
                 createUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 221124
  mean =      4.342 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 919 
    [ 2.500,  5.000) = 190287 
    [ 5.000,  7.500) = 28437 
    [ 7.500, 10.000) = 1087 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     12.210 ms/op
     p(99.9900) =     30.966 ms/op
     p(99.9990) =     31.031 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.077 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.434 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.354 ±(99.9%) 0.010 ms/op
Iteration   1: 4.108 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  9.435 ms/op
                 existUser·p0.9999: 15.068 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   2: 4.142 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   4.059 ms/op
                 existUser·p0.90:   4.956 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  12.976 ms/op
                 existUser·p0.9999: 17.081 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   3: 4.119 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   4.891 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  9.515 ms/op
                 existUser·p0.9999: 23.797 ms/op
                 existUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 232612
  mean =      4.123 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3571 
    [ 2.500,  5.000) = 208306 
    [ 5.000,  7.500) = 19722 
    [ 7.500, 10.000) = 757 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     10.289 ms/op
     p(99.9900) =     22.814 ms/op
     p(99.9990) =     24.382 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.503 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.784 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.009 ms/op
Iteration   1: 4.332 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.587 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  11.788 ms/op
                 getUser·p0.9999: 25.035 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   2: 4.272 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.022 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  11.188 ms/op
                 getUser·p0.9999: 19.498 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   3: 4.434 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   7.051 ms/op
                 getUser·p0.999:  9.941 ms/op
                 getUser·p0.9999: 19.857 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 220785
  mean =      4.345 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2313 
    [ 2.500,  5.000) = 187659 
    [ 5.000,  7.500) = 29346 
    [ 7.500, 10.000) = 1154 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     10.788 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     25.068 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 7.705 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.975 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.334 ±(99.9%) 0.018 ms/op
Iteration   1: 5.390 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   5.054 ms/op
                 listUser·p0.90:   7.143 ms/op
                 listUser·p0.95:   7.905 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 29.590 ms/op
                 listUser·p1.00:   34.931 ms/op

Iteration   2: 5.524 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  19.042 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 5.409 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  22.965 ms/op
                 listUser·p0.9999: 29.633 ms/op
                 listUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176432
  mean =      5.440 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 74268 
    [ 5.000,  7.500) = 90609 
    [ 7.500, 10.000) = 9701 
    [10.000, 12.500) = 1150 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      7.840 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     29.374 ms/op
     p(99.9990) =     31.249 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.109 ± 3.378  ops/ms
ClientGrpc.existUser                       thrpt       3   8.280 ± 1.945  ops/ms
ClientGrpc.getUser                         thrpt       3   7.861 ± 2.113  ops/ms
ClientGrpc.listUser                        thrpt       3   6.311 ± 2.124  ops/ms
ClientGrpc.createUser                       avgt       3   2.894 ± 0.238   ms/op
ClientGrpc.existUser                        avgt       3   3.104 ± 4.052   ms/op
ClientGrpc.getUser                          avgt       3   4.436 ± 0.980   ms/op
ClientGrpc.listUser                         avgt       3   5.192 ± 2.303   ms/op
ClientGrpc.createUser                     sample  221124   4.342 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.937           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.161           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.865           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.210           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.966           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.031           ms/op
ClientGrpc.existUser                      sample  232612   4.123 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.997           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.423           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.289           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.814           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.510           ms/op
ClientGrpc.getUser                        sample  220785   4.345 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.059           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.177           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.538           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.914           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.788           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.825           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.100           ms/op
ClientGrpc.listUser                       sample  176432   5.440 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.624           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.840           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.011           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.366           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.374           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.931           ms/op
