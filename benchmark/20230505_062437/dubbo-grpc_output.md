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
# Warmup Iteration   1: 3.802 ops/ms
# Warmup Iteration   2: 8.337 ops/ms
# Warmup Iteration   3: 9.845 ops/ms
Iteration   1: 10.411 ops/ms
Iteration   2: 10.422 ops/ms
Iteration   3: 10.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.375 ±(99.9%) 1.314 ops/ms [Average]
  (min, avg, max) = (10.292, 10.375, 10.422), stdev = 0.072
  CI (99.9%): [9.061, 11.688] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.945 ops/ms
# Warmup Iteration   2: 10.166 ops/ms
# Warmup Iteration   3: 11.012 ops/ms
Iteration   1: 10.872 ops/ms
Iteration   2: 10.925 ops/ms
Iteration   3: 11.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.019 ±(99.9%) 3.855 ops/ms [Average]
  (min, avg, max) = (10.872, 11.019, 11.261), stdev = 0.211
  CI (99.9%): [7.165, 14.874] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.317 ops/ms
# Warmup Iteration   2: 9.823 ops/ms
# Warmup Iteration   3: 10.297 ops/ms
Iteration   1: 10.279 ops/ms
Iteration   2: 10.414 ops/ms
Iteration   3: 10.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.358 ±(99.9%) 1.288 ops/ms [Average]
  (min, avg, max) = (10.279, 10.358, 10.414), stdev = 0.071
  CI (99.9%): [9.070, 11.646] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.435 ops/ms
# Warmup Iteration   2: 7.579 ops/ms
# Warmup Iteration   3: 7.860 ops/ms
Iteration   1: 7.944 ops/ms
Iteration   2: 7.871 ops/ms
Iteration   3: 7.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.836 ±(99.9%) 2.372 ops/ms [Average]
  (min, avg, max) = (7.691, 7.836, 7.944), stdev = 0.130
  CI (99.9%): [5.463, 10.208] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.334 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.002 ms/op
Iteration   1: 3.119 ±(99.9%) 0.002 ms/op
Iteration   2: 3.172 ±(99.9%) 0.001 ms/op
Iteration   3: 3.131 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.141 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (3.119, 3.141, 3.172), stdev = 0.028
  CI (99.9%): [2.629, 3.653] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.320 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.001 ms/op
Iteration   1: 2.906 ±(99.9%) 0.002 ms/op
Iteration   2: 2.973 ±(99.9%) 0.001 ms/op
Iteration   3: 2.989 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.956 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (2.906, 2.956, 2.989), stdev = 0.044
  CI (99.9%): [2.152, 3.759] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.313 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.004 ms/op
Iteration   1: 3.084 ±(99.9%) 0.009 ms/op
Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
Iteration   3: 3.018 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (3.018, 3.066, 3.098), stdev = 0.042
  CI (99.9%): [2.293, 3.840] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.037 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.560 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.015 ms/op
Iteration   1: 4.164 ±(99.9%) 0.012 ms/op
Iteration   2: 4.155 ±(99.9%) 0.010 ms/op
Iteration   3: 4.076 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.132 ±(99.9%) 0.883 ms/op [Average]
  (min, avg, max) = (4.076, 4.132, 4.164), stdev = 0.048
  CI (99.9%): [3.249, 5.014] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.639 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
Iteration   1: 3.118 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  9.525 ms/op
                 createUser·p0.9999: 19.880 ms/op
                 createUser·p1.00:   20.054 ms/op

Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  8.228 ms/op
                 createUser·p0.9999: 19.792 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.543 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.469 ms/op
                 createUser·p0.9999: 23.289 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308115
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16135 
    [ 2.500,  5.000) = 290140 
    [ 5.000,  7.500) = 1270 
    [ 7.500, 10.000) = 302 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.525 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.862 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
Iteration   1: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  7.436 ms/op
                 existUser·p0.9999: 14.975 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   2: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  7.315 ms/op
                 existUser·p0.9999: 14.516 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.397 ms/op
                 existUser·p0.9999: 23.207 ms/op
                 existUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327055
  mean =      2.934 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29383 
    [ 2.500,  5.000) = 296498 
    [ 5.000,  7.500) = 884 
    [ 7.500, 10.000) = 130 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      7.365 ms/op
     p(99.9900) =     19.419 ms/op
     p(99.9990) =     23.486 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.128 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.323 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  8.700 ms/op
                 getUser·p0.9999: 17.786 ms/op
                 getUser·p1.00:   17.990 ms/op

Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.045 ms/op
                 getUser·p0.9999: 15.030 ms/op
                 getUser·p1.00:   16.581 ms/op

Iteration   3: 3.107 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  7.620 ms/op
                 getUser·p0.9999: 19.674 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308391
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14944 
    [ 2.500,  5.000) = 291011 
    [ 5.000,  7.500) = 1952 
    [ 7.500, 10.000) = 308 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.323 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.801 ms/op
     p(99.9000) =      8.135 ms/op
     p(99.9900) =     18.252 ms/op
     p(99.9990) =     20.144 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 5.440 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.012 ms/op
Iteration   1: 4.086 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  15.005 ms/op
                 listUser·p0.9999: 26.018 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 4.063 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.147 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  18.359 ms/op
                 listUser·p0.9999: 27.144 ms/op
                 listUser·p1.00:   27.689 ms/op

Iteration   3: 4.041 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  20.279 ms/op
                 listUser·p0.9999: 25.630 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236268
  mean =      4.063 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2740 
    [ 2.500,  5.000) = 208557 
    [ 5.000,  7.500) = 23026 
    [ 7.500, 10.000) = 1443 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     27.653 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.375 ± 1.314  ops/ms
ClientGrpc.existUser                       thrpt       3  11.019 ± 3.855  ops/ms
ClientGrpc.getUser                         thrpt       3  10.358 ± 1.288  ops/ms
ClientGrpc.listUser                        thrpt       3   7.836 ± 2.372  ops/ms
ClientGrpc.createUser                       avgt       3   3.141 ± 0.512   ms/op
ClientGrpc.existUser                        avgt       3   2.956 ± 0.803   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.774   ms/op
ClientGrpc.listUser                         avgt       3   4.132 ± 0.883   ms/op
ClientGrpc.createUser                     sample  308115   3.115 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.543           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.741           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.626           ms/op
ClientGrpc.existUser                      sample  327055   2.934 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.762           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.365           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.419           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.626           ms/op
ClientGrpc.getUser                        sample  308391   3.111 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.323           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.801           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.135           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.252           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  236268   4.063 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.862           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.416           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.739           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.689           ms/op
