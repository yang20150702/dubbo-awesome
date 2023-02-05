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
# Warmup Iteration   1: 3.987 ops/ms
# Warmup Iteration   2: 8.963 ops/ms
# Warmup Iteration   3: 9.973 ops/ms
Iteration   1: 10.520 ops/ms
Iteration   2: 10.300 ops/ms
Iteration   3: 10.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.406 ±(99.9%) 2.011 ops/ms [Average]
  (min, avg, max) = (10.300, 10.406, 10.520), stdev = 0.110
  CI (99.9%): [8.395, 12.417] (assumes normal distribution)


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
# Warmup Iteration   1: 7.350 ops/ms
# Warmup Iteration   2: 10.553 ops/ms
# Warmup Iteration   3: 11.012 ops/ms
Iteration   1: 10.915 ops/ms
Iteration   2: 10.949 ops/ms
Iteration   3: 11.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.082 ±(99.9%) 4.756 ops/ms [Average]
  (min, avg, max) = (10.915, 11.082, 11.382), stdev = 0.261
  CI (99.9%): [6.326, 15.838] (assumes normal distribution)


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
# Warmup Iteration   1: 7.736 ops/ms
# Warmup Iteration   2: 10.037 ops/ms
# Warmup Iteration   3: 10.286 ops/ms
Iteration   1: 10.219 ops/ms
Iteration   2: 10.470 ops/ms
Iteration   3: 10.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.465 ±(99.9%) 4.444 ops/ms [Average]
  (min, avg, max) = (10.219, 10.465, 10.706), stdev = 0.244
  CI (99.9%): [6.021, 14.909] (assumes normal distribution)


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
# Warmup Iteration   1: 6.439 ops/ms
# Warmup Iteration   2: 7.701 ops/ms
# Warmup Iteration   3: 7.912 ops/ms
Iteration   1: 8.285 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 8.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.212 ±(99.9%) 1.623 ops/ms [Average]
  (min, avg, max) = (8.113, 8.212, 8.285), stdev = 0.089
  CI (99.9%): [6.589, 9.835] (assumes normal distribution)


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.004 ms/op
Iteration   1: 3.118 ±(99.9%) 0.003 ms/op
Iteration   2: 3.159 ±(99.9%) 0.001 ms/op
Iteration   3: 3.032 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.103 ±(99.9%) 1.177 ms/op [Average]
  (min, avg, max) = (3.032, 3.103, 3.159), stdev = 0.065
  CI (99.9%): [1.926, 4.280] (assumes normal distribution)


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
# Warmup Iteration   1: 3.769 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
Iteration   3: 2.950 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.963 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (2.943, 2.963, 2.995), stdev = 0.028
  CI (99.9%): [2.450, 3.475] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.002 ms/op
Iteration   1: 2.978 ±(99.9%) 0.002 ms/op
Iteration   2: 3.049 ±(99.9%) 0.003 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.036 ±(99.9%) 0.947 ms/op [Average]
  (min, avg, max) = (2.978, 3.036, 3.080), stdev = 0.052
  CI (99.9%): [2.088, 3.983] (assumes normal distribution)


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
# Warmup Iteration   1: 4.661 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.008 ms/op
Iteration   1: 3.958 ±(99.9%) 0.013 ms/op
Iteration   2: 3.818 ±(99.9%) 0.007 ms/op
Iteration   3: 3.783 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.853 ±(99.9%) 1.692 ms/op [Average]
  (min, avg, max) = (3.783, 3.853, 3.958), stdev = 0.093
  CI (99.9%): [2.161, 5.544] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   3.013 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.616 ms/op
                 createUser·p0.9999: 13.575 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.773 ms/op
                 createUser·p0.9999: 14.386 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.156 ms/op
                 createUser·p0.9999: 18.441 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310144
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 818 
    [ 1.250,  2.500) = 32542 
    [ 2.500,  3.750) = 243616 
    [ 3.750,  5.000) = 32109 
    [ 5.000,  6.250) = 423 
    [ 6.250,  7.500) = 260 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.840 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     18.802 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.388 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.118 ms/op
                 existUser·p0.9999: 13.118 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.773 ms/op
                 existUser·p0.9999: 15.296 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   3: 3.079 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.393 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  8.159 ms/op
                 existUser·p0.9999: 29.327 ms/op
                 existUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312629
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33938 
    [ 2.500,  5.000) = 277652 
    [ 5.000,  7.500) = 635 
    [ 7.500, 10.000) = 229 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.020 ms/op
     p(99.9900) =     28.500 ms/op
     p(99.9990) =     29.585 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 4.219 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.007 ms/op
Iteration   1: 3.251 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  8.019 ms/op
                 getUser·p0.9999: 19.573 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   2: 3.223 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.375 ms/op
                 getUser·p0.9999: 14.927 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   3: 3.182 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.293 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.338 ms/op
                 getUser·p0.999:  6.879 ms/op
                 getUser·p0.9999: 17.758 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298236
  mean =      3.218 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13665 
    [ 2.500,  5.000) = 283511 
    [ 5.000,  7.500) = 737 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.293 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.686 ms/op
     p(99.9900) =     18.695 ms/op
     p(99.9990) =     19.957 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 5.274 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.357 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.260 ±(99.9%) 0.013 ms/op
Iteration   1: 4.186 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  14.820 ms/op
                 listUser·p0.9999: 18.373 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   2: 4.173 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  17.047 ms/op
                 listUser·p0.9999: 21.353 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 4.145 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  16.959 ms/op
                 listUser·p0.9999: 23.832 ms/op
                 listUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230345
  mean =      4.168 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1602 
    [ 2.500,  5.000) = 197311 
    [ 5.000,  7.500) = 29864 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     16.247 ms/op
     p(99.9900) =     21.918 ms/op
     p(99.9990) =     24.196 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.406 ± 2.011  ops/ms
ClientGrpc.existUser                       thrpt       3  11.082 ± 4.756  ops/ms
ClientGrpc.getUser                         thrpt       3  10.465 ± 4.444  ops/ms
ClientGrpc.listUser                        thrpt       3   8.212 ± 1.623  ops/ms
ClientGrpc.createUser                       avgt       3   3.103 ± 1.177   ms/op
ClientGrpc.existUser                        avgt       3   2.963 ± 0.513   ms/op
ClientGrpc.getUser                          avgt       3   3.036 ± 0.947   ms/op
ClientGrpc.listUser                         avgt       3   3.853 ± 1.692   ms/op
ClientGrpc.createUser                     sample  310144   3.094 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.662           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.840           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.465           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.973           ms/op
ClientGrpc.existUser                      sample  312629   3.073 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.388           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.060           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.020           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.500           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.655           ms/op
ClientGrpc.getUser                        sample  298236   3.218 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.293           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.187           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.071           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.686           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.695           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.021           ms/op
ClientGrpc.listUser                       sample  230345   4.168 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.950           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.981           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.247           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.918           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.314           ms/op
