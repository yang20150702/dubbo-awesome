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
# Warmup Iteration   1: 3.500 ops/ms
# Warmup Iteration   2: 8.026 ops/ms
# Warmup Iteration   3: 9.638 ops/ms
Iteration   1: 10.019 ops/ms
Iteration   2: 10.306 ops/ms
Iteration   3: 10.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.183 ±(99.9%) 2.700 ops/ms [Average]
  (min, avg, max) = (10.019, 10.183, 10.306), stdev = 0.148
  CI (99.9%): [7.483, 12.883] (assumes normal distribution)


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
# Warmup Iteration   1: 5.911 ops/ms
# Warmup Iteration   2: 9.836 ops/ms
# Warmup Iteration   3: 10.179 ops/ms
Iteration   1: 10.136 ops/ms
Iteration   2: 10.375 ops/ms
Iteration   3: 10.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.339 ±(99.9%) 3.420 ops/ms [Average]
  (min, avg, max) = (10.136, 10.339, 10.506), stdev = 0.187
  CI (99.9%): [6.920, 13.759] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 5.680 ops/ms
# Warmup Iteration   2: 8.888 ops/ms
# Warmup Iteration   3: 10.014 ops/ms
Iteration   1: 10.148 ops/ms
Iteration   2: 9.841 ops/ms
Iteration   3: 9.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.920 ±(99.9%) 3.653 ops/ms [Average]
  (min, avg, max) = (9.772, 9.920, 10.148), stdev = 0.200
  CI (99.9%): [6.267, 13.574] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.801 ops/ms
# Warmup Iteration   2: 7.100 ops/ms
# Warmup Iteration   3: 7.338 ops/ms
Iteration   1: 7.443 ops/ms
Iteration   2: 7.638 ops/ms
Iteration   3: 7.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.554 ±(99.9%) 1.825 ops/ms [Average]
  (min, avg, max) = (7.443, 7.554, 7.638), stdev = 0.100
  CI (99.9%): [5.729, 9.378] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.435 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.003 ms/op
Iteration   1: 3.243 ±(99.9%) 0.003 ms/op
Iteration   2: 3.220 ±(99.9%) 0.002 ms/op
Iteration   3: 3.234 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.232 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (3.220, 3.232, 3.243), stdev = 0.012
  CI (99.9%): [3.019, 3.446] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.825 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.002 ms/op
Iteration   1: 3.039 ±(99.9%) 0.002 ms/op
Iteration   2: 2.940 ±(99.9%) 0.002 ms/op
Iteration   3: 3.090 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.023 ±(99.9%) 1.391 ms/op [Average]
  (min, avg, max) = (2.940, 3.023, 3.090), stdev = 0.076
  CI (99.9%): [1.632, 4.414] (assumes normal distribution)


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
# Warmup Iteration   1: 5.871 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.002 ms/op
Iteration   1: 3.421 ±(99.9%) 0.003 ms/op
Iteration   2: 3.510 ±(99.9%) 0.002 ms/op
Iteration   3: 3.423 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.452 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (3.421, 3.452, 3.510), stdev = 0.051
  CI (99.9%): [2.522, 4.382] (assumes normal distribution)


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
# Warmup Iteration   1: 6.932 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.903 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.415 ±(99.9%) 0.012 ms/op
Iteration   1: 4.427 ±(99.9%) 0.011 ms/op
Iteration   2: 4.454 ±(99.9%) 0.007 ms/op
Iteration   3: 3.988 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.290 ±(99.9%) 4.774 ms/op [Average]
  (min, avg, max) = (3.988, 4.290, 4.454), stdev = 0.262
  CI (99.9%): [≈ 0, 9.064] (assumes normal distribution)


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
# Warmup Iteration   1: 5.546 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.009 ms/op
Iteration   1: 3.414 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 17.912 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   2: 3.378 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  8.406 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   3: 3.472 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  8.171 ms/op
                 createUser·p0.9999: 30.460 ms/op
                 createUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 280386
  mean =      3.421 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5413 
    [ 2.500,  5.000) = 272585 
    [ 5.000,  7.500) = 1896 
    [ 7.500, 10.000) = 276 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =      8.579 ms/op
     p(99.9900) =     29.654 ms/op
     p(99.9990) =     30.821 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 4.940 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.007 ms/op
Iteration   1: 3.190 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  11.037 ms/op
                 existUser·p0.9999: 19.724 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   2: 3.264 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   4.865 ms/op
                 existUser·p0.999:  7.831 ms/op
                 existUser·p0.9999: 19.661 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   3: 3.265 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  9.617 ms/op
                 existUser·p0.9999: 22.721 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 296528
  mean =      3.239 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11516 
    [ 2.500,  5.000) = 283363 
    [ 5.000,  7.500) = 1116 
    [ 7.500, 10.000) = 261 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      9.347 ms/op
     p(99.9900) =     22.000 ms/op
     p(99.9990) =     23.010 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 5.149 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.027 ms/op
Iteration   1: 3.967 ±(99.9%) 0.059 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   21.222 ms/op
                 getUser·p0.999:  83.626 ms/op
                 getUser·p0.9999: 103.416 ms/op
                 getUser·p1.00:   111.149 ms/op

Iteration   2: 4.064 ±(99.9%) 0.065 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   32.119 ms/op
                 getUser·p0.999:  75.394 ms/op
                 getUser·p0.9999: 100.119 ms/op
                 getUser·p1.00:   125.305 ms/op

Iteration   3: 4.008 ±(99.9%) 0.070 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   19.257 ms/op
                 getUser·p0.999:  102.892 ms/op
                 getUser·p0.9999: 124.649 ms/op
                 getUser·p1.00:   129.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 239839
  mean =      4.013 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 236894 
    [ 12.500,  25.000) = 543 
    [ 25.000,  37.500) = 660 
    [ 37.500,  50.000) = 632 
    [ 50.000,  62.500) = 418 
    [ 62.500,  75.000) = 246 
    [ 75.000,  87.500) = 191 
    [ 87.500, 100.000) = 136 
    [100.000, 112.500) = 86 
    [112.500, 125.000) = 26 
    [125.000, 137.500) = 7 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =     25.068 ms/op
     p(99.9000) =     88.495 ms/op
     p(99.9900) =    116.394 ms/op
     p(99.9990) =    128.792 ms/op
     p(99.9999) =    129.761 ms/op
    p(100.0000) =    129.761 ms/op


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
# Warmup Iteration   1: 8.065 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.724 ±(99.9%) 0.102 ms/op
# Warmup Iteration   3: 5.160 ±(99.9%) 0.086 ms/op
Iteration   1: 5.158 ±(99.9%) 0.094 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   37.354 ms/op
                 listUser·p0.999:  98.435 ms/op
                 listUser·p0.9999: 113.980 ms/op
                 listUser·p1.00:   116.392 ms/op

Iteration   2: 5.134 ±(99.9%) 0.092 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   6.267 ms/op
                 listUser·p0.95:   7.143 ms/op
                 listUser·p0.99:   34.800 ms/op
                 listUser·p0.999:  98.100 ms/op
                 listUser·p0.9999: 112.400 ms/op
                 listUser·p1.00:   121.635 ms/op

Iteration   3: 5.084 ±(99.9%) 0.086 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   33.751 ms/op
                 listUser·p0.999:  91.797 ms/op
                 listUser·p0.9999: 105.603 ms/op
                 listUser·p1.00:   106.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 187407
  mean =      5.125 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 184285 
    [ 12.500,  25.000) = 865 
    [ 25.000,  37.500) = 470 
    [ 37.500,  50.000) = 323 
    [ 50.000,  62.500) = 405 
    [ 62.500,  75.000) = 387 
    [ 75.000,  87.500) = 312 
    [ 87.500, 100.000) = 203 
    [100.000, 112.500) = 142 
    [112.500, 125.000) = 15 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =     35.122 ms/op
     p(99.9000) =     97.124 ms/op
     p(99.9900) =    112.198 ms/op
     p(99.9990) =    121.062 ms/op
     p(99.9999) =    121.635 ms/op
    p(100.0000) =    121.635 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt    Score   Error   Units
ClientGrpc.createUser                      thrpt       3   10.183 ± 2.700  ops/ms
ClientGrpc.existUser                       thrpt       3   10.339 ± 3.420  ops/ms
ClientGrpc.getUser                         thrpt       3    9.920 ± 3.653  ops/ms
ClientGrpc.listUser                        thrpt       3    7.554 ± 1.825  ops/ms
ClientGrpc.createUser                       avgt       3    3.232 ± 0.214   ms/op
ClientGrpc.existUser                        avgt       3    3.023 ± 1.391   ms/op
ClientGrpc.getUser                          avgt       3    3.452 ± 0.930   ms/op
ClientGrpc.listUser                         avgt       3    4.290 ± 4.774   ms/op
ClientGrpc.createUser                     sample  280386    3.421 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample            0.766           ms/op
ClientGrpc.createUser:createUser·p0.50    sample            3.375           ms/op
ClientGrpc.createUser:createUser·p0.90    sample            4.035           ms/op
ClientGrpc.createUser:createUser·p0.95    sample            4.268           ms/op
ClientGrpc.createUser:createUser·p0.99    sample            4.907           ms/op
ClientGrpc.createUser:createUser·p0.999   sample            8.579           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample           29.654           ms/op
ClientGrpc.createUser:createUser·p1.00    sample           30.933           ms/op
ClientGrpc.existUser                      sample  296528    3.239 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample            0.695           ms/op
ClientGrpc.existUser:existUser·p0.50      sample            3.211           ms/op
ClientGrpc.existUser:existUser·p0.90      sample            3.785           ms/op
ClientGrpc.existUser:existUser·p0.95      sample            4.063           ms/op
ClientGrpc.existUser:existUser·p0.99      sample            4.710           ms/op
ClientGrpc.existUser:existUser·p0.999     sample            9.347           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample           22.000           ms/op
ClientGrpc.existUser:existUser·p1.00      sample           23.527           ms/op
ClientGrpc.getUser                        sample  239839    4.013 ± 0.037   ms/op
ClientGrpc.getUser:getUser·p0.00          sample            0.713           ms/op
ClientGrpc.getUser:getUser·p0.50          sample            3.437           ms/op
ClientGrpc.getUser:getUser·p0.90          sample            4.227           ms/op
ClientGrpc.getUser:getUser·p0.95          sample            4.588           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           25.068           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           88.495           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          116.394           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          129.761           ms/op
ClientGrpc.listUser                       sample  187407    5.125 ± 0.052   ms/op
ClientGrpc.listUser:listUser·p0.00        sample            1.227           ms/op
ClientGrpc.listUser:listUser·p0.50        sample            4.092           ms/op
ClientGrpc.listUser:listUser·p0.90        sample            6.275           ms/op
ClientGrpc.listUser:listUser·p0.95        sample            7.078           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           35.122           ms/op
ClientGrpc.listUser:listUser·p0.999       sample           97.124           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          112.198           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          121.635           ms/op
