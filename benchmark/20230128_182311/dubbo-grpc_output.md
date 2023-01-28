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
# Warmup Iteration   1: 4.084 ops/ms
# Warmup Iteration   2: 8.718 ops/ms
# Warmup Iteration   3: 9.900 ops/ms
Iteration   1: 10.206 ops/ms
Iteration   2: 10.126 ops/ms
Iteration   3: 10.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.160 ±(99.9%) 0.758 ops/ms [Average]
  (min, avg, max) = (10.126, 10.160, 10.206), stdev = 0.042
  CI (99.9%): [9.403, 10.918] (assumes normal distribution)


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
# Warmup Iteration   1: 6.991 ops/ms
# Warmup Iteration   2: 10.234 ops/ms
# Warmup Iteration   3: 10.346 ops/ms
Iteration   1: 10.405 ops/ms
Iteration   2: 10.852 ops/ms
Iteration   3: 10.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.540 ±(99.9%) 4.954 ops/ms [Average]
  (min, avg, max) = (10.362, 10.540, 10.852), stdev = 0.272
  CI (99.9%): [5.586, 15.494] (assumes normal distribution)


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
# Warmup Iteration   1: 6.588 ops/ms
# Warmup Iteration   2: 9.693 ops/ms
# Warmup Iteration   3: 9.894 ops/ms
Iteration   1: 9.769 ops/ms
Iteration   2: 9.884 ops/ms
Iteration   3: 10.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.885 ±(99.9%) 2.145 ops/ms [Average]
  (min, avg, max) = (9.769, 9.885, 10.004), stdev = 0.118
  CI (99.9%): [7.741, 12.030] (assumes normal distribution)


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
# Warmup Iteration   1: 5.290 ops/ms
# Warmup Iteration   2: 7.352 ops/ms
# Warmup Iteration   3: 7.437 ops/ms
Iteration   1: 7.598 ops/ms
Iteration   2: 7.713 ops/ms
Iteration   3: 7.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.648 ±(99.9%) 1.072 ops/ms [Average]
  (min, avg, max) = (7.598, 7.648, 7.713), stdev = 0.059
  CI (99.9%): [6.575, 8.720] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.565 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.002 ms/op
Iteration   1: 3.197 ±(99.9%) 0.002 ms/op
Iteration   2: 3.194 ±(99.9%) 0.002 ms/op
Iteration   3: 3.233 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.208 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (3.194, 3.208, 3.233), stdev = 0.021
  CI (99.9%): [2.817, 3.600] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.002 ms/op
Iteration   1: 3.054 ±(99.9%) 0.002 ms/op
Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.063 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (3.054, 3.063, 3.077), stdev = 0.012
  CI (99.9%): [2.837, 3.289] (assumes normal distribution)


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.003 ms/op
Iteration   1: 3.245 ±(99.9%) 0.002 ms/op
Iteration   2: 3.228 ±(99.9%) 0.002 ms/op
Iteration   3: 3.182 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.218 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.182, 3.218, 3.245), stdev = 0.033
  CI (99.9%): [2.619, 3.817] (assumes normal distribution)


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
# Warmup Iteration   1: 5.350 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.371 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.264 ±(99.9%) 0.033 ms/op
Iteration   1: 4.132 ±(99.9%) 0.012 ms/op
Iteration   2: 4.135 ±(99.9%) 0.015 ms/op
Iteration   3: 4.173 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.147 ±(99.9%) 0.420 ms/op [Average]
  (min, avg, max) = (4.132, 4.147, 4.173), stdev = 0.023
  CI (99.9%): [3.727, 4.567] (assumes normal distribution)


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
Iteration   1: 3.194 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.681 ms/op
                 createUser·p0.9999: 13.828 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 3.239 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.652 ms/op
                 createUser·p0.9999: 15.044 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   3: 3.247 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.486 ms/op
                 createUser·p0.9999: 18.158 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297525
  mean =      3.227 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 349 
    [ 1.250,  2.500) = 13328 
    [ 2.500,  3.750) = 241106 
    [ 3.750,  5.000) = 41751 
    [ 5.000,  6.250) = 406 
    [ 6.250,  7.500) = 231 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 89 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.942 ms/op
     p(99.9900) =     16.736 ms/op
     p(99.9990) =     18.516 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.209 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.023 ms/op
                 existUser·p0.9999: 15.090 ms/op
                 existUser·p1.00:   15.237 ms/op

Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.303 ms/op
                 existUser·p0.999:  7.819 ms/op
                 existUser·p0.9999: 15.445 ms/op
                 existUser·p1.00:   15.925 ms/op

Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.374 ms/op
                 existUser·p0.9999: 17.874 ms/op
                 existUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312609
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 909 
    [ 1.250,  2.500) = 33869 
    [ 2.500,  3.750) = 247139 
    [ 3.750,  5.000) = 29816 
    [ 5.000,  6.250) = 319 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 70 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.322 ms/op
     p(99.9900) =     15.855 ms/op
     p(99.9990) =     18.215 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.007 ms/op
Iteration   1: 3.245 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  7.893 ms/op
                 getUser·p0.9999: 14.385 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   2: 3.282 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  6.995 ms/op
                 getUser·p0.9999: 14.991 ms/op
                 getUser·p1.00:   15.925 ms/op

Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.970 ms/op
                 getUser·p0.9999: 18.449 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 295704
  mean =      3.244 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 331 
    [ 1.250,  2.500) = 13754 
    [ 2.500,  3.750) = 232513 
    [ 3.750,  5.000) = 47900 
    [ 5.000,  6.250) = 681 
    [ 6.250,  7.500) = 251 
    [ 7.500,  8.750) = 107 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.359 ms/op
     p(99.9900) =     16.450 ms/op
     p(99.9990) =     18.984 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 5.490 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.011 ms/op
Iteration   1: 4.255 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  15.135 ms/op
                 listUser·p0.9999: 24.673 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 4.320 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.242 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  17.428 ms/op
                 listUser·p0.9999: 24.438 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 4.199 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  20.011 ms/op
                 listUser·p0.9999: 24.602 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 225472
  mean =      4.257 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1464 
    [ 2.500,  5.000) = 191055 
    [ 5.000,  7.500) = 31044 
    [ 7.500, 10.000) = 1412 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     16.737 ms/op
     p(99.9900) =     24.540 ms/op
     p(99.9990) =     26.115 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.160 ± 0.758  ops/ms
ClientGrpc.existUser                       thrpt       3  10.540 ± 4.954  ops/ms
ClientGrpc.getUser                         thrpt       3   9.885 ± 2.145  ops/ms
ClientGrpc.listUser                        thrpt       3   7.648 ± 1.072  ops/ms
ClientGrpc.createUser                       avgt       3   3.208 ± 0.392   ms/op
ClientGrpc.existUser                        avgt       3   3.063 ± 0.226   ms/op
ClientGrpc.getUser                          avgt       3   3.218 ± 0.599   ms/op
ClientGrpc.listUser                         avgt       3   4.147 ± 0.420   ms/op
ClientGrpc.createUser                     sample  297525   3.227 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.687           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.195           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.104           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.942           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.736           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.711           ms/op
ClientGrpc.existUser                      sample  312609   3.071 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.710           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.056           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.322           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.855           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.350           ms/op
ClientGrpc.getUser                        sample  295704   3.244 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.782           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.211           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.940           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.141           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.359           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.450           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.268           ms/op
ClientGrpc.listUser                       sample  225472   4.257 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.033           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.067           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.095           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.348           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.737           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.540           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.280           ms/op
