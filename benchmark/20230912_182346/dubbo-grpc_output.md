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
# Warmup Iteration   1: 4.275 ops/ms
# Warmup Iteration   2: 8.936 ops/ms
# Warmup Iteration   3: 10.087 ops/ms
Iteration   1: 10.507 ops/ms
Iteration   2: 10.553 ops/ms
Iteration   3: 10.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.496 ±(99.9%) 1.145 ops/ms [Average]
  (min, avg, max) = (10.429, 10.496, 10.553), stdev = 0.063
  CI (99.9%): [9.352, 11.641] (assumes normal distribution)


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
# Warmup Iteration   1: 7.538 ops/ms
# Warmup Iteration   2: 10.903 ops/ms
# Warmup Iteration   3: 11.098 ops/ms
Iteration   1: 11.036 ops/ms
Iteration   2: 11.076 ops/ms
Iteration   3: 10.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.946 ±(99.9%) 3.501 ops/ms [Average]
  (min, avg, max) = (10.726, 10.946, 11.076), stdev = 0.192
  CI (99.9%): [7.445, 14.447] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.114 ops/ms
# Warmup Iteration   2: 10.197 ops/ms
# Warmup Iteration   3: 10.492 ops/ms
Iteration   1: 10.429 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.487 ±(99.9%) 1.054 ops/ms [Average]
  (min, avg, max) = (10.429, 10.487, 10.544), stdev = 0.058
  CI (99.9%): [9.433, 11.541] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.786 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 7.999 ops/ms
Iteration   1: 8.191 ops/ms
Iteration   2: 8.155 ops/ms
Iteration   3: 8.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.124 ±(99.9%) 1.586 ops/ms [Average]
  (min, avg, max) = (8.025, 8.124, 8.191), stdev = 0.087
  CI (99.9%): [6.538, 9.709] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.903 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.003 ms/op
Iteration   1: 3.037 ±(99.9%) 0.025 ms/op
Iteration   2: 3.005 ±(99.9%) 0.004 ms/op
Iteration   3: 2.990 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.011 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (2.990, 3.011, 3.037), stdev = 0.024
  CI (99.9%): [2.573, 3.449] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.854 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.004 ms/op
Iteration   1: 2.888 ±(99.9%) 0.004 ms/op
Iteration   2: 3.013 ±(99.9%) 0.003 ms/op
Iteration   3: 2.916 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.939 ±(99.9%) 1.200 ms/op [Average]
  (min, avg, max) = (2.888, 2.939, 3.013), stdev = 0.066
  CI (99.9%): [1.739, 4.139] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.210 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.003 ms/op
Iteration   1: 3.095 ±(99.9%) 0.003 ms/op
Iteration   2: 3.079 ±(99.9%) 0.003 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.063 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (3.016, 3.063, 3.095), stdev = 0.042
  CI (99.9%): [2.301, 3.826] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.487 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.289 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.022 ms/op
Iteration   1: 3.914 ±(99.9%) 0.008 ms/op
Iteration   2: 3.945 ±(99.9%) 0.032 ms/op
Iteration   3: 3.937 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.932 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.914, 3.932, 3.945), stdev = 0.016
  CI (99.9%): [3.645, 4.219] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.099 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
Iteration   1: 3.013 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.673 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 14.817 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.618 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.453 ms/op
                 createUser·p0.9999: 20.988 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  13.894 ms/op
                 createUser·p0.9999: 15.737 ms/op
                 createUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315790
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23991 
    [ 2.500,  5.000) = 289371 
    [ 5.000,  7.500) = 1802 
    [ 7.500, 10.000) = 282 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     10.289 ms/op
     p(99.9900) =     20.199 ms/op
     p(99.9990) =     21.261 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 17.601 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   2: 2.947 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.620 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  8.569 ms/op
                 existUser·p0.9999: 13.484 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  8.065 ms/op
                 existUser·p0.9999: 13.664 ms/op
                 existUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326276
  mean =      2.942 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1785 
    [ 1.250,  2.500) = 34284 
    [ 2.500,  3.750) = 275356 
    [ 3.750,  5.000) = 12976 
    [ 5.000,  6.250) = 867 
    [ 6.250,  7.500) = 412 
    [ 7.500,  8.750) = 277 
    [ 8.750, 10.000) = 151 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     15.663 ms/op
     p(99.9990) =     17.907 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 13.402 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.495 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  10.630 ms/op
                 getUser·p0.9999: 24.347 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.430 ms/op
                 getUser·p0.9999: 30.728 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314879
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21012 
    [ 2.500,  5.000) = 292063 
    [ 5.000,  7.500) = 1212 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      9.232 ms/op
     p(99.9900) =     28.951 ms/op
     p(99.9990) =     31.153 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 5.194 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
Iteration   1: 3.975 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.490 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  13.074 ms/op
                 listUser·p0.9999: 15.185 ms/op
                 listUser·p1.00:   15.466 ms/op

Iteration   2: 3.946 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  15.513 ms/op
                 listUser·p0.9999: 22.017 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 3.917 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  14.773 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243555
  mean =      3.946 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4545 
    [ 2.500,  5.000) = 217227 
    [ 5.000,  7.500) = 19995 
    [ 7.500, 10.000) = 1084 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     26.912 ms/op
     p(99.9990) =     27.759 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.496 ± 1.145  ops/ms
ClientGrpc.existUser                       thrpt       3  10.946 ± 3.501  ops/ms
ClientGrpc.getUser                         thrpt       3  10.487 ± 1.054  ops/ms
ClientGrpc.listUser                        thrpt       3   8.124 ± 1.586  ops/ms
ClientGrpc.createUser                       avgt       3   3.011 ± 0.438   ms/op
ClientGrpc.existUser                        avgt       3   2.939 ± 1.200   ms/op
ClientGrpc.getUser                          avgt       3   3.063 ± 0.763   ms/op
ClientGrpc.listUser                         avgt       3   3.932 ± 0.287   ms/op
ClientGrpc.createUser                     sample  315790   3.038 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.618           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.289           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.199           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.332           ms/op
ClientGrpc.existUser                      sample  326276   2.942 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.620           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.716           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.663           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.022           ms/op
ClientGrpc.getUser                        sample  314879   3.046 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.495           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.232           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.951           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.293           ms/op
ClientGrpc.listUser                       sample  243555   3.946 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.490           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.912           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.820           ms/op
