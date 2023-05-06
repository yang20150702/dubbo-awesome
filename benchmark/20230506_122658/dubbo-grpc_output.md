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
# Warmup Iteration   1: 3.467 ops/ms
# Warmup Iteration   2: 7.763 ops/ms
# Warmup Iteration   3: 9.729 ops/ms
Iteration   1: 10.361 ops/ms
Iteration   2: 10.404 ops/ms
Iteration   3: 10.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.409 ±(99.9%) 0.933 ops/ms [Average]
  (min, avg, max) = (10.361, 10.409, 10.462), stdev = 0.051
  CI (99.9%): [9.476, 11.341] (assumes normal distribution)


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
# Warmup Iteration   1: 7.356 ops/ms
# Warmup Iteration   2: 10.474 ops/ms
# Warmup Iteration   3: 10.814 ops/ms
Iteration   1: 11.012 ops/ms
Iteration   2: 10.973 ops/ms
Iteration   3: 11.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.000 ±(99.9%) 0.416 ops/ms [Average]
  (min, avg, max) = (10.973, 11.000, 11.014), stdev = 0.023
  CI (99.9%): [10.584, 11.415] (assumes normal distribution)


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
# Warmup Iteration   1: 6.255 ops/ms
# Warmup Iteration   2: 9.953 ops/ms
# Warmup Iteration   3: 10.369 ops/ms
Iteration   1: 10.496 ops/ms
Iteration   2: 10.522 ops/ms
Iteration   3: 10.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.521 ±(99.9%) 0.447 ops/ms [Average]
  (min, avg, max) = (10.496, 10.521, 10.545), stdev = 0.025
  CI (99.9%): [10.074, 10.968] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.390 ops/ms
# Warmup Iteration   2: 7.584 ops/ms
# Warmup Iteration   3: 7.768 ops/ms
Iteration   1: 7.889 ops/ms
Iteration   2: 7.916 ops/ms
Iteration   3: 7.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.919 ±(99.9%) 0.583 ops/ms [Average]
  (min, avg, max) = (7.889, 7.919, 7.953), stdev = 0.032
  CI (99.9%): [7.336, 8.502] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.711 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.003 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.108 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.072 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.055, 3.072, 3.108), stdev = 0.030
  CI (99.9%): [2.519, 3.626] (assumes normal distribution)


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
# Warmup Iteration   1: 4.311 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.002 ms/op
Iteration   1: 2.875 ±(99.9%) 0.002 ms/op
Iteration   2: 2.954 ±(99.9%) 0.002 ms/op
Iteration   3: 2.961 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.930 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (2.875, 2.930, 2.961), stdev = 0.048
  CI (99.9%): [2.055, 3.805] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.002 ms/op
Iteration   1: 3.029 ±(99.9%) 0.003 ms/op
Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
Iteration   3: 3.087 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.064 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (3.029, 3.064, 3.087), stdev = 0.031
  CI (99.9%): [2.504, 3.624] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.656 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.017 ms/op
Iteration   1: 4.040 ±(99.9%) 0.013 ms/op
Iteration   2: 4.046 ±(99.9%) 0.010 ms/op
Iteration   3: 4.041 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.042 ±(99.9%) 0.057 ms/op [Average]
  (min, avg, max) = (4.040, 4.042, 4.046), stdev = 0.003
  CI (99.9%): [3.985, 4.099] (assumes normal distribution)


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
# Warmup Iteration   1: 4.607 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.535 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.323 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 16.961 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  10.578 ms/op
                 createUser·p0.9999: 22.413 ms/op
                 createUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307838
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11069 
    [ 2.500,  5.000) = 294957 
    [ 5.000,  7.500) = 1127 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =     10.016 ms/op
     p(99.9900) =     21.903 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 4.713 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
Iteration   1: 3.156 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.521 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   2: 3.218 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  9.372 ms/op
                 existUser·p0.9999: 16.057 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   3: 3.220 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  8.796 ms/op
                 existUser·p0.9999: 17.842 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 300216
  mean =      3.198 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 518 
    [ 1.250,  2.500) = 9523 
    [ 2.500,  3.750) = 257542 
    [ 3.750,  5.000) = 31126 
    [ 5.000,  6.250) = 906 
    [ 6.250,  7.500) = 196 
    [ 7.500,  8.750) = 143 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 63 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.401 ms/op
     p(99.9900) =     16.627 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 4.803 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.005 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  9.968 ms/op
                 getUser·p0.9999: 13.202 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.620 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  8.372 ms/op
                 getUser·p0.9999: 14.139 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.340 ms/op
                 getUser·p0.9999: 18.055 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310755
  mean =      3.087 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 536 
    [ 1.250,  2.500) = 18045 
    [ 2.500,  3.750) = 272085 
    [ 3.750,  5.000) = 18345 
    [ 5.000,  6.250) = 1078 
    [ 6.250,  7.500) = 307 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.360 ms/op
     p(99.9900) =     16.709 ms/op
     p(99.9990) =     18.620 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 5.761 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.011 ms/op
Iteration   1: 4.043 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.795 ms/op
                 listUser·p0.99:   7.103 ms/op
                 listUser·p0.999:  13.704 ms/op
                 listUser·p0.9999: 16.878 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   2: 3.939 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.313 ms/op
                 listUser·p0.9999: 23.516 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   3: 4.056 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  18.024 ms/op
                 listUser·p0.9999: 26.186 ms/op
                 listUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239241
  mean =      4.012 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2526 
    [ 2.500,  5.000) = 214611 
    [ 5.000,  7.500) = 20606 
    [ 7.500, 10.000) = 1082 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     15.344 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     26.595 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.409 ± 0.933  ops/ms
ClientGrpc.existUser                       thrpt       3  11.000 ± 0.416  ops/ms
ClientGrpc.getUser                         thrpt       3  10.521 ± 0.447  ops/ms
ClientGrpc.listUser                        thrpt       3   7.919 ± 0.583  ops/ms
ClientGrpc.createUser                       avgt       3   3.072 ± 0.554   ms/op
ClientGrpc.existUser                        avgt       3   2.930 ± 0.875   ms/op
ClientGrpc.getUser                          avgt       3   3.064 ± 0.560   ms/op
ClientGrpc.listUser                         avgt       3   4.042 ± 0.057   ms/op
ClientGrpc.createUser                     sample  307838   3.118 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.535           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.016           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.903           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.003           ms/op
ClientGrpc.existUser                      sample  300216   3.198 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.739           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.154           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.043           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.604           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.401           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.627           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.973           ms/op
ClientGrpc.getUser                        sample  310755   3.087 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.620           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.360           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.709           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.678           ms/op
ClientGrpc.listUser                       sample  239241   4.012 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.104           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.344           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.362           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.739           ms/op
