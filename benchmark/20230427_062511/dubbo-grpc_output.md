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
# Warmup Iteration   1: 2.592 ops/ms
# Warmup Iteration   2: 6.253 ops/ms
# Warmup Iteration   3: 7.737 ops/ms
Iteration   1: 7.986 ops/ms
Iteration   2: 8.036 ops/ms
Iteration   3: 7.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.983 ±(99.9%) 1.007 ops/ms [Average]
  (min, avg, max) = (7.926, 7.983, 8.036), stdev = 0.055
  CI (99.9%): [6.976, 8.989] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.861 ops/ms
# Warmup Iteration   2: 8.153 ops/ms
# Warmup Iteration   3: 8.630 ops/ms
Iteration   1: 9.109 ops/ms
Iteration   2: 8.768 ops/ms
Iteration   3: 8.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.709 ±(99.9%) 7.898 ops/ms [Average]
  (min, avg, max) = (8.249, 8.709, 9.109), stdev = 0.433
  CI (99.9%): [0.811, 16.606] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ops/ms
# Warmup Iteration   2: 6.899 ops/ms
# Warmup Iteration   3: 7.688 ops/ms
Iteration   1: 7.951 ops/ms
Iteration   2: 8.049 ops/ms
Iteration   3: 8.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.031 ±(99.9%) 1.325 ops/ms [Average]
  (min, avg, max) = (7.951, 8.031, 8.093), stdev = 0.073
  CI (99.9%): [6.706, 9.357] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ops/ms
# Warmup Iteration   2: 5.453 ops/ms
# Warmup Iteration   3: 5.739 ops/ms
Iteration   1: 5.987 ops/ms
Iteration   2: 6.313 ops/ms
Iteration   3: 6.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.242 ±(99.9%) 4.165 ops/ms [Average]
  (min, avg, max) = (5.987, 6.242, 6.427), stdev = 0.228
  CI (99.9%): [2.077, 10.408] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.258 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.231 ±(99.9%) 0.010 ms/op
Iteration   1: 4.137 ±(99.9%) 0.003 ms/op
Iteration   2: 4.104 ±(99.9%) 0.003 ms/op
Iteration   3: 3.989 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.077 ±(99.9%) 1.421 ms/op [Average]
  (min, avg, max) = (3.989, 4.077, 4.137), stdev = 0.078
  CI (99.9%): [2.656, 5.498] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.431 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.003 ms/op
Iteration   1: 4.080 ±(99.9%) 0.004 ms/op
Iteration   2: 3.857 ±(99.9%) 0.003 ms/op
Iteration   3: 4.126 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.021 ±(99.9%) 2.630 ms/op [Average]
  (min, avg, max) = (3.857, 4.021, 4.126), stdev = 0.144
  CI (99.9%): [1.391, 6.651] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.279 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.008 ms/op
Iteration   1: 3.983 ±(99.9%) 0.003 ms/op
Iteration   2: 3.919 ±(99.9%) 0.002 ms/op
Iteration   3: 3.900 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.934 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (3.900, 3.934, 3.983), stdev = 0.044
  CI (99.9%): [3.140, 4.728] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.068 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.545 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.529 ±(99.9%) 0.019 ms/op
Iteration   1: 5.491 ±(99.9%) 0.014 ms/op
Iteration   2: 5.241 ±(99.9%) 0.010 ms/op
Iteration   3: 5.567 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.433 ±(99.9%) 3.114 ms/op [Average]
  (min, avg, max) = (5.241, 5.433, 5.567), stdev = 0.171
  CI (99.9%): [2.319, 8.547] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.586 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.013 ms/op
Iteration   1: 4.347 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   4.143 ms/op
                 createUser·p0.90:   5.743 ms/op
                 createUser·p0.95:   6.439 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  12.462 ms/op
                 createUser·p0.9999: 18.391 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   2: 4.133 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   5.374 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   7.963 ms/op
                 createUser·p0.999:  12.467 ms/op
                 createUser·p0.9999: 38.159 ms/op
                 createUser·p1.00:   39.191 ms/op

Iteration   3: 4.150 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   5.857 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  11.484 ms/op
                 createUser·p0.9999: 21.889 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 228105
  mean =      4.208 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6540 
    [ 2.500,  5.000) = 181553 
    [ 5.000,  7.500) = 36709 
    [ 7.500, 10.000) = 2649 
    [10.000, 12.500) = 443 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      8.060 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     35.586 ms/op
     p(99.9990) =     38.844 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.251 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.013 ms/op
Iteration   1: 4.121 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.386 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   7.274 ms/op
                 existUser·p0.999:  9.892 ms/op
                 existUser·p0.9999: 25.567 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 3.937 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.422 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  13.166 ms/op
                 existUser·p0.9999: 26.885 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   3: 3.883 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  10.379 ms/op
                 existUser·p0.9999: 29.778 ms/op
                 existUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 241303
  mean =      3.978 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9738 
    [ 2.500,  5.000) = 206537 
    [ 5.000,  7.500) = 23203 
    [ 7.500, 10.000) = 1420 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.386 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     11.136 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     30.185 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.227 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.409 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.012 ms/op
Iteration   1: 4.036 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.922 ms/op
                 getUser·p0.999:  13.165 ms/op
                 getUser·p0.9999: 16.598 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   2: 4.269 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   4.129 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   6.038 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  14.254 ms/op
                 getUser·p0.9999: 21.856 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   3: 4.006 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   7.225 ms/op
                 getUser·p0.999:  9.929 ms/op
                 getUser·p0.9999: 23.692 ms/op
                 getUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 234276
  mean =      4.100 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10113 
    [ 2.500,  5.000) = 193722 
    [ 5.000,  7.500) = 27564 
    [ 7.500, 10.000) = 2306 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.840 ms/op
     p(99.9000) =     12.328 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     24.193 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 7.682 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.818 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.500 ±(99.9%) 0.022 ms/op
Iteration   1: 5.156 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   6.963 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   9.929 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 20.277 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   2: 5.210 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   7.053 ms/op
                 listUser·p0.95:   8.012 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  18.619 ms/op
                 listUser·p0.9999: 22.531 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 5.555 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   7.332 ms/op
                 listUser·p0.95:   8.380 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  21.239 ms/op
                 listUser·p0.9999: 23.687 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180959
  mean =      5.302 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 278 
    [ 2.500,  5.000) = 90075 
    [ 5.000,  7.500) = 76850 
    [ 7.500, 10.000) = 11398 
    [10.000, 12.500) = 1694 
    [12.500, 15.000) = 333 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      7.119 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     18.417 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     24.908 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.983 ± 1.007  ops/ms
ClientGrpc.existUser                       thrpt       3   8.709 ± 7.898  ops/ms
ClientGrpc.getUser                         thrpt       3   8.031 ± 1.325  ops/ms
ClientGrpc.listUser                        thrpt       3   6.242 ± 4.165  ops/ms
ClientGrpc.createUser                       avgt       3   4.077 ± 1.421   ms/op
ClientGrpc.existUser                        avgt       3   4.021 ± 2.630   ms/op
ClientGrpc.getUser                          avgt       3   3.934 ± 0.794   ms/op
ClientGrpc.listUser                         avgt       3   5.433 ± 3.114   ms/op
ClientGrpc.createUser                     sample  228105   4.208 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.963           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.472           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.087           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.060           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.288           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.586           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          39.191           ms/op
ClientGrpc.existUser                      sample  241303   3.978 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.386           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.513           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.135           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.136           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.131           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.310           ms/op
ClientGrpc.getUser                        sample  234276   4.100 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.948           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.985           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.751           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.840           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.328           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.561           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.314           ms/op
ClientGrpc.listUser                       sample  180959   5.302 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.891           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.077           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.404           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.417           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.134           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
