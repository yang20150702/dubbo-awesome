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
# Warmup Iteration   1: 4.095 ops/ms
# Warmup Iteration   2: 8.907 ops/ms
# Warmup Iteration   3: 10.028 ops/ms
Iteration   1: 10.316 ops/ms
Iteration   2: 10.276 ops/ms
Iteration   3: 10.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.380 ±(99.9%) 2.680 ops/ms [Average]
  (min, avg, max) = (10.276, 10.380, 10.548), stdev = 0.147
  CI (99.9%): [7.700, 13.060] (assumes normal distribution)


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
# Warmup Iteration   1: 7.318 ops/ms
# Warmup Iteration   2: 10.673 ops/ms
# Warmup Iteration   3: 10.979 ops/ms
Iteration   1: 10.836 ops/ms
Iteration   2: 10.643 ops/ms
Iteration   3: 10.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.718 ±(99.9%) 1.880 ops/ms [Average]
  (min, avg, max) = (10.643, 10.718, 10.836), stdev = 0.103
  CI (99.9%): [8.838, 12.599] (assumes normal distribution)


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
# Warmup Iteration   1: 6.859 ops/ms
# Warmup Iteration   2: 9.959 ops/ms
# Warmup Iteration   3: 10.243 ops/ms
Iteration   1: 10.419 ops/ms
Iteration   2: 10.337 ops/ms
Iteration   3: 10.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.419 ±(99.9%) 1.478 ops/ms [Average]
  (min, avg, max) = (10.337, 10.419, 10.499), stdev = 0.081
  CI (99.9%): [8.941, 11.897] (assumes normal distribution)


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
# Warmup Iteration   1: 5.442 ops/ms
# Warmup Iteration   2: 7.389 ops/ms
# Warmup Iteration   3: 7.768 ops/ms
Iteration   1: 7.774 ops/ms
Iteration   2: 7.849 ops/ms
Iteration   3: 7.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.793 ±(99.9%) 0.884 ops/ms [Average]
  (min, avg, max) = (7.758, 7.793, 7.849), stdev = 0.048
  CI (99.9%): [6.909, 8.678] (assumes normal distribution)


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
# Warmup Iteration   1: 4.385 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.002 ms/op
Iteration   1: 3.081 ±(99.9%) 0.006 ms/op
Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
Iteration   3: 3.113 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.079 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (3.042, 3.079, 3.113), stdev = 0.036
  CI (99.9%): [2.425, 3.732] (assumes normal distribution)


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
# Warmup Iteration   1: 3.972 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.840 ±(99.9%) 0.003 ms/op
Iteration   1: 2.837 ±(99.9%) 0.003 ms/op
Iteration   2: 2.901 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.900 ±(99.9%) 1.144 ms/op [Average]
  (min, avg, max) = (2.837, 2.900, 2.962), stdev = 0.063
  CI (99.9%): [1.756, 4.044] (assumes normal distribution)


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.004 ms/op
Iteration   1: 3.053 ±(99.9%) 0.003 ms/op
Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.061 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (3.053, 3.061, 3.071), stdev = 0.009
  CI (99.9%): [2.889, 3.233] (assumes normal distribution)


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
# Warmup Iteration   1: 5.516 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.331 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.020 ms/op
Iteration   1: 4.099 ±(99.9%) 0.009 ms/op
Iteration   2: 4.040 ±(99.9%) 0.019 ms/op
Iteration   3: 4.101 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.080 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (4.040, 4.080, 4.101), stdev = 0.034
  CI (99.9%): [3.453, 4.707] (assumes normal distribution)


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
Iteration   1: 3.075 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 14.959 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  8.603 ms/op
                 createUser·p0.9999: 16.493 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   3: 3.061 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  8.136 ms/op
                 createUser·p0.9999: 47.186 ms/op
                 createUser·p1.00:   47.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311896
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 309773 
    [ 5.000, 10.000) = 1898 
    [10.000, 15.000) = 89 
    [15.000, 20.000) = 104 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      8.521 ms/op
     p(99.9900) =     46.571 ms/op
     p(99.9990) =     47.440 ms/op
     p(99.9999) =     47.645 ms/op
    p(100.0000) =     47.645 ms/op


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.007 ms/op
Iteration   1: 2.906 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.209 ms/op
                 existUser·p0.9999: 12.927 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.328 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.561 ms/op
                 existUser·p0.999:  7.487 ms/op
                 existUser·p0.9999: 14.421 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   3: 2.924 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  7.586 ms/op
                 existUser·p0.9999: 17.564 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327396
  mean =      2.931 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1378 
    [ 1.250,  2.500) = 30297 
    [ 2.500,  3.750) = 285866 
    [ 3.750,  5.000) = 8102 
    [ 5.000,  6.250) = 906 
    [ 6.250,  7.500) = 526 
    [ 7.500,  8.750) = 122 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.328 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.479 ms/op
     p(99.9900) =     16.323 ms/op
     p(99.9990) =     17.751 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
Iteration   1: 3.076 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  8.210 ms/op
                 getUser·p0.9999: 14.421 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.948 ms/op
                 getUser·p0.999:  8.545 ms/op
                 getUser·p0.9999: 23.052 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  8.192 ms/op
                 getUser·p0.9999: 16.424 ms/op
                 getUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311861
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18035 
    [ 2.500,  5.000) = 291421 
    [ 5.000,  7.500) = 1883 
    [ 7.500, 10.000) = 341 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.801 ms/op
     p(99.9000) =      8.308 ms/op
     p(99.9900) =     22.041 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 5.746 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.014 ms/op
Iteration   1: 4.096 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.595 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  18.664 ms/op
                 listUser·p0.9999: 28.461 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   2: 4.065 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  15.697 ms/op
                 listUser·p0.9999: 23.532 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   3: 4.131 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 32.244 ms/op
                 listUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234235
  mean =      4.097 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2504 
    [ 2.500,  5.000) = 205708 
    [ 5.000,  7.500) = 24112 
    [ 7.500, 10.000) = 1320 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     16.368 ms/op
     p(99.9900) =     31.378 ms/op
     p(99.9990) =     33.134 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.380 ± 2.680  ops/ms
ClientGrpc.existUser                       thrpt       3  10.718 ± 1.880  ops/ms
ClientGrpc.getUser                         thrpt       3  10.419 ± 1.478  ops/ms
ClientGrpc.listUser                        thrpt       3   7.793 ± 0.884  ops/ms
ClientGrpc.createUser                       avgt       3   3.079 ± 0.654   ms/op
ClientGrpc.existUser                        avgt       3   2.900 ± 1.144   ms/op
ClientGrpc.getUser                          avgt       3   3.061 ± 0.172   ms/op
ClientGrpc.listUser                         avgt       3   4.080 ± 0.627   ms/op
ClientGrpc.createUser                     sample  311896   3.077 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.635           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.521           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          46.571           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          47.645           ms/op
ClientGrpc.existUser                      sample  327396   2.931 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.328           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.479           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.323           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.891           ms/op
ClientGrpc.getUser                        sample  311861   3.076 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.755           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.801           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.308           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.041           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.625           ms/op
ClientGrpc.listUser                       sample  234235   4.097 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.595           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.283           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.368           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.378           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.554           ms/op
