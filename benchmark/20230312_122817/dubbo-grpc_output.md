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
# Warmup Iteration   1: 4.645 ops/ms
# Warmup Iteration   2: 9.264 ops/ms
# Warmup Iteration   3: 10.397 ops/ms
Iteration   1: 10.625 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 10.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.578 ±(99.9%) 2.339 ops/ms [Average]
  (min, avg, max) = (10.433, 10.578, 10.677), stdev = 0.128
  CI (99.9%): [8.239, 12.917] (assumes normal distribution)


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
# Warmup Iteration   1: 7.812 ops/ms
# Warmup Iteration   2: 10.890 ops/ms
# Warmup Iteration   3: 11.256 ops/ms
Iteration   1: 11.205 ops/ms
Iteration   2: 11.249 ops/ms
Iteration   3: 10.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.112 ±(99.9%) 3.638 ops/ms [Average]
  (min, avg, max) = (10.884, 11.112, 11.249), stdev = 0.199
  CI (99.9%): [7.474, 14.751] (assumes normal distribution)


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
# Warmup Iteration   1: 7.349 ops/ms
# Warmup Iteration   2: 10.372 ops/ms
# Warmup Iteration   3: 10.588 ops/ms
Iteration   1: 10.537 ops/ms
Iteration   2: 10.832 ops/ms
Iteration   3: 10.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.681 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (10.537, 10.681, 10.832), stdev = 0.147
  CI (99.9%): [7.993, 13.370] (assumes normal distribution)


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
# Warmup Iteration   1: 5.818 ops/ms
# Warmup Iteration   2: 8.370 ops/ms
# Warmup Iteration   3: 8.365 ops/ms
Iteration   1: 8.612 ops/ms
Iteration   2: 8.342 ops/ms
Iteration   3: 8.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.464 ±(99.9%) 2.492 ops/ms [Average]
  (min, avg, max) = (8.342, 8.464, 8.612), stdev = 0.137
  CI (99.9%): [5.973, 10.956] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 3.009 ±(99.9%) 0.002 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.009 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.994, 3.009, 3.023), stdev = 0.015
  CI (99.9%): [2.744, 3.273] (assumes normal distribution)


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.846 ±(99.9%) 0.004 ms/op
Iteration   1: 2.890 ±(99.9%) 0.002 ms/op
Iteration   2: 2.899 ±(99.9%) 0.003 ms/op
Iteration   3: 2.761 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.850 ±(99.9%) 1.415 ms/op [Average]
  (min, avg, max) = (2.761, 2.850, 2.899), stdev = 0.078
  CI (99.9%): [1.435, 4.265] (assumes normal distribution)


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.002 ms/op
Iteration   1: 3.024 ±(99.9%) 0.002 ms/op
Iteration   2: 2.929 ±(99.9%) 0.003 ms/op
Iteration   3: 3.030 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.995 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (2.929, 2.995, 3.030), stdev = 0.057
  CI (99.9%): [1.963, 4.026] (assumes normal distribution)


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
# Warmup Iteration   1: 5.496 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.007 ms/op
Iteration   1: 3.774 ±(99.9%) 0.010 ms/op
Iteration   2: 3.737 ±(99.9%) 0.064 ms/op
Iteration   3: 3.785 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.765 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.737, 3.765, 3.785), stdev = 0.025
  CI (99.9%): [3.305, 4.225] (assumes normal distribution)


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.546 ms/op
                 createUser·p0.9999: 16.980 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.750 ms/op
                 createUser·p0.9999: 14.205 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  8.479 ms/op
                 createUser·p0.9999: 14.684 ms/op
                 createUser·p1.00:   15.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316567
  mean =      3.031 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1033 
    [ 1.250,  2.500) = 22810 
    [ 2.500,  3.750) = 275377 
    [ 3.750,  5.000) = 16263 
    [ 5.000,  6.250) = 529 
    [ 6.250,  7.500) = 190 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.081 ms/op
     p(99.9900) =     16.161 ms/op
     p(99.9990) =     17.689 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 3.196 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.925 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.005 ms/op
Iteration   1: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  7.319 ms/op
                 existUser·p0.9999: 12.304 ms/op
                 existUser·p1.00:   12.681 ms/op

Iteration   2: 2.866 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.216 ms/op
                 existUser·p0.999:  5.906 ms/op
                 existUser·p0.9999: 13.738 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.902 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.245 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  5.677 ms/op
                 existUser·p0.9999: 16.628 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332682
  mean =      2.887 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2871 
    [ 1.250,  2.500) = 42071 
    [ 2.500,  3.750) = 277136 
    [ 3.750,  5.000) = 9567 
    [ 5.000,  6.250) = 704 
    [ 6.250,  7.500) = 125 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.245 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      6.250 ms/op
     p(99.9900) =     15.293 ms/op
     p(99.9990) =     18.002 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  6.750 ms/op
                 getUser·p0.9999: 20.225 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.251 ms/op
                 getUser·p0.999:  11.551 ms/op
                 getUser·p0.9999: 13.763 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.977 ms/op
                 getUser·p0.9999: 29.360 ms/op
                 getUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317372
  mean =      3.025 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22846 
    [ 2.500,  5.000) = 293297 
    [ 5.000,  7.500) = 876 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.782 ms/op
     p(99.9900) =     28.558 ms/op
     p(99.9990) =     29.518 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.010 ms/op
Iteration   1: 3.780 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  11.775 ms/op
                 listUser·p0.9999: 16.794 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   2: 3.780 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.614 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  18.654 ms/op
                 listUser·p0.9999: 20.973 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   3: 3.796 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 22.629 ms/op
                 listUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253744
  mean =      3.785 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5231 
    [ 2.500,  5.000) = 230691 
    [ 5.000,  7.500) = 16850 
    [ 7.500, 10.000) = 551 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     13.513 ms/op
     p(99.9900) =     20.980 ms/op
     p(99.9990) =     25.113 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.578 ± 2.339  ops/ms
ClientGrpc.existUser                       thrpt       3  11.112 ± 3.638  ops/ms
ClientGrpc.getUser                         thrpt       3  10.681 ± 2.688  ops/ms
ClientGrpc.listUser                        thrpt       3   8.464 ± 2.492  ops/ms
ClientGrpc.createUser                       avgt       3   3.009 ± 0.265   ms/op
ClientGrpc.existUser                        avgt       3   2.850 ± 1.415   ms/op
ClientGrpc.getUser                          avgt       3   2.995 ± 1.031   ms/op
ClientGrpc.listUser                         avgt       3   3.765 ± 0.460   ms/op
ClientGrpc.createUser                     sample  316567   3.031 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.709           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.081           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.161           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.793           ms/op
ClientGrpc.existUser                      sample  332682   2.887 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.245           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.250           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.293           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  317372   3.025 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.670           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.782           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.558           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.557           ms/op
ClientGrpc.listUser                       sample  253744   3.785 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.614           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.658           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.678           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.513           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.980           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.297           ms/op
