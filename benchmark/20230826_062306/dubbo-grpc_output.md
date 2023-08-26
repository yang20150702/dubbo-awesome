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
# Warmup Iteration   1: 4.644 ops/ms
# Warmup Iteration   2: 9.472 ops/ms
# Warmup Iteration   3: 10.363 ops/ms
Iteration   1: 10.524 ops/ms
Iteration   2: 10.658 ops/ms
Iteration   3: 10.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.579 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (10.524, 10.579, 10.658), stdev = 0.070
  CI (99.9%): [9.308, 11.850] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.234 ops/ms
# Warmup Iteration   2: 10.723 ops/ms
# Warmup Iteration   3: 11.004 ops/ms
Iteration   1: 11.018 ops/ms
Iteration   2: 10.872 ops/ms
Iteration   3: 11.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.976 ±(99.9%) 1.641 ops/ms [Average]
  (min, avg, max) = (10.872, 10.976, 11.037), stdev = 0.090
  CI (99.9%): [9.335, 12.617] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.828 ops/ms
# Warmup Iteration   2: 10.280 ops/ms
# Warmup Iteration   3: 10.607 ops/ms
Iteration   1: 10.567 ops/ms
Iteration   2: 10.641 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.550 ±(99.9%) 1.844 ops/ms [Average]
  (min, avg, max) = (10.441, 10.550, 10.641), stdev = 0.101
  CI (99.9%): [8.705, 12.394] (assumes normal distribution)


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
# Warmup Iteration   1: 6.424 ops/ms
# Warmup Iteration   2: 7.456 ops/ms
# Warmup Iteration   3: 8.045 ops/ms
Iteration   1: 8.026 ops/ms
Iteration   2: 7.948 ops/ms
Iteration   3: 8.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.996 ±(99.9%) 0.774 ops/ms [Average]
  (min, avg, max) = (7.948, 7.996, 8.026), stdev = 0.042
  CI (99.9%): [7.222, 8.771] (assumes normal distribution)


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.004 ms/op
Iteration   2: 2.970 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.979 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.970, 2.979, 2.996), stdev = 0.014
  CI (99.9%): [2.715, 3.243] (assumes normal distribution)


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.744 ±(99.9%) 0.004 ms/op
Iteration   1: 2.940 ±(99.9%) 0.002 ms/op
Iteration   2: 2.883 ±(99.9%) 0.002 ms/op
Iteration   3: 2.886 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.903 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (2.883, 2.903, 2.940), stdev = 0.032
  CI (99.9%): [2.321, 3.484] (assumes normal distribution)


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.004 ms/op
Iteration   1: 2.971 ±(99.9%) 0.004 ms/op
Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
Iteration   3: 3.011 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.979 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (2.954, 2.979, 3.011), stdev = 0.029
  CI (99.9%): [2.446, 3.511] (assumes normal distribution)


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
# Warmup Iteration   1: 5.808 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.015 ms/op
Iteration   1: 3.920 ±(99.9%) 0.040 ms/op
Iteration   2: 3.892 ±(99.9%) 0.020 ms/op
Iteration   3: 3.947 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.920 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.892, 3.920, 3.947), stdev = 0.028
  CI (99.9%): [3.409, 4.430] (assumes normal distribution)


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.006 ms/op
Iteration   1: 3.112 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  11.768 ms/op
                 createUser·p0.9999: 13.402 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.959 ms/op
                 createUser·p0.9999: 21.855 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   3: 2.993 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  9.390 ms/op
                 createUser·p0.9999: 27.349 ms/op
                 createUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314822
  mean =      3.048 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21343 
    [ 2.500,  5.000) = 291524 
    [ 5.000,  7.500) = 1275 
    [ 7.500, 10.000) = 358 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     10.165 ms/op
     p(99.9900) =     26.461 ms/op
     p(99.9990) =     27.848 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 3.837 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.007 ms/op
Iteration   1: 2.933 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  7.197 ms/op
                 existUser·p0.9999: 12.486 ms/op
                 existUser·p1.00:   13.042 ms/op

Iteration   2: 2.836 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.414 ms/op
                 existUser·p0.9999: 15.106 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   3: 2.826 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.715 ms/op
                 existUser·p0.9999: 15.756 ms/op
                 existUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335243
  mean =      2.864 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2597 
    [ 1.250,  2.500) = 45955 
    [ 2.500,  3.750) = 278632 
    [ 3.750,  5.000) = 6576 
    [ 5.000,  6.250) = 674 
    [ 6.250,  7.500) = 484 
    [ 7.500,  8.750) = 131 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      7.463 ms/op
     p(99.9900) =     15.229 ms/op
     p(99.9990) =     16.055 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.005 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.774 ms/op
                 getUser·p0.9999: 12.743 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  7.651 ms/op
                 getUser·p0.9999: 26.919 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   3: 3.001 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  8.405 ms/op
                 getUser·p0.9999: 20.873 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318995
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26165 
    [ 2.500,  5.000) = 291022 
    [ 5.000,  7.500) = 1364 
    [ 7.500, 10.000) = 246 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      8.012 ms/op
     p(99.9900) =     26.480 ms/op
     p(99.9990) =     27.158 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 5.384 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.012 ms/op
Iteration   1: 3.948 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.443 ms/op
                 listUser·p0.9999: 18.019 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 3.957 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 3.915 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  22.727 ms/op
                 listUser·p0.9999: 26.400 ms/op
                 listUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243789
  mean =      3.940 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3569 
    [ 2.500,  5.000) = 218736 
    [ 5.000,  7.500) = 19821 
    [ 7.500, 10.000) = 1059 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     25.022 ms/op
     p(99.9990) =     26.874 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.579 ± 1.271  ops/ms
ClientGrpc.existUser                       thrpt       3  10.976 ± 1.641  ops/ms
ClientGrpc.getUser                         thrpt       3  10.550 ± 1.844  ops/ms
ClientGrpc.listUser                        thrpt       3   7.996 ± 0.774  ops/ms
ClientGrpc.createUser                       avgt       3   2.979 ± 0.264   ms/op
ClientGrpc.existUser                        avgt       3   2.903 ± 0.581   ms/op
ClientGrpc.getUser                          avgt       3   2.979 ± 0.532   ms/op
ClientGrpc.listUser                         avgt       3   3.920 ± 0.510   ms/op
ClientGrpc.createUser                     sample  314822   3.048 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.787           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.165           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.461           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.951           ms/op
ClientGrpc.existUser                      sample  335243   2.864 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.528           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.463           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.229           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.155           ms/op
ClientGrpc.getUser                        sample  318995   3.007 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.598           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.012           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.480           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.263           ms/op
ClientGrpc.listUser                       sample  243789   3.940 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.830           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.777           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.022           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.001           ms/op
