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
# Warmup Iteration   1: 4.036 ops/ms
# Warmup Iteration   2: 8.380 ops/ms
# Warmup Iteration   3: 9.809 ops/ms
Iteration   1: 10.379 ops/ms
Iteration   2: 10.291 ops/ms
Iteration   3: 10.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.379 ±(99.9%) 1.608 ops/ms [Average]
  (min, avg, max) = (10.291, 10.379, 10.467), stdev = 0.088
  CI (99.9%): [8.771, 11.988] (assumes normal distribution)


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
# Warmup Iteration   1: 7.081 ops/ms
# Warmup Iteration   2: 10.317 ops/ms
# Warmup Iteration   3: 10.812 ops/ms
Iteration   1: 10.442 ops/ms
Iteration   2: 10.902 ops/ms
Iteration   3: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.688 ±(99.9%) 4.228 ops/ms [Average]
  (min, avg, max) = (10.442, 10.688, 10.902), stdev = 0.232
  CI (99.9%): [6.460, 14.916] (assumes normal distribution)


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
# Warmup Iteration   1: 6.875 ops/ms
# Warmup Iteration   2: 10.025 ops/ms
# Warmup Iteration   3: 10.218 ops/ms
Iteration   1: 10.320 ops/ms
Iteration   2: 10.271 ops/ms
Iteration   3: 10.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.318 ±(99.9%) 0.835 ops/ms [Average]
  (min, avg, max) = (10.271, 10.318, 10.362), stdev = 0.046
  CI (99.9%): [9.483, 11.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.845 ops/ms
# Warmup Iteration   2: 7.426 ops/ms
# Warmup Iteration   3: 7.598 ops/ms
Iteration   1: 7.779 ops/ms
Iteration   2: 7.830 ops/ms
Iteration   3: 7.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.804 ±(99.9%) 0.467 ops/ms [Average]
  (min, avg, max) = (7.779, 7.804, 7.830), stdev = 0.026
  CI (99.9%): [7.337, 8.270] (assumes normal distribution)


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
# Warmup Iteration   1: 4.586 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.003 ms/op
Iteration   1: 3.048 ±(99.9%) 0.004 ms/op
Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
Iteration   3: 3.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.066 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (3.048, 3.066, 3.088), stdev = 0.020
  CI (99.9%): [2.698, 3.434] (assumes normal distribution)


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.003 ms/op
Iteration   1: 2.928 ±(99.9%) 0.003 ms/op
Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
Iteration   3: 2.979 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.959 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (2.928, 2.959, 2.979), stdev = 0.027
  CI (99.9%): [2.466, 3.452] (assumes normal distribution)


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.003 ms/op
Iteration   1: 3.111 ±(99.9%) 0.002 ms/op
Iteration   2: 3.093 ±(99.9%) 0.003 ms/op
Iteration   3: 3.073 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.093 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (3.073, 3.093, 3.111), stdev = 0.019
  CI (99.9%): [2.746, 3.439] (assumes normal distribution)


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
# Warmup Iteration   1: 5.627 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.017 ms/op
Iteration   1: 4.016 ±(99.9%) 0.014 ms/op
Iteration   2: 4.104 ±(99.9%) 0.025 ms/op
Iteration   3: 4.002 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.041 ±(99.9%) 1.012 ms/op [Average]
  (min, avg, max) = (4.002, 4.041, 4.104), stdev = 0.055
  CI (99.9%): [3.029, 5.053] (assumes normal distribution)


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
# Warmup Iteration   1: 4.709 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.344 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.006 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.291 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  8.102 ms/op
                 createUser·p0.9999: 14.285 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  7.963 ms/op
                 createUser·p0.9999: 15.046 ms/op
                 createUser·p1.00:   15.319 ms/op

Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  10.097 ms/op
                 createUser·p0.9999: 18.338 ms/op
                 createUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308943
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 495 
    [ 1.250,  2.500) = 19938 
    [ 2.500,  3.750) = 263878 
    [ 3.750,  5.000) = 22374 
    [ 5.000,  6.250) = 1268 
    [ 6.250,  7.500) = 448 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.291 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     17.600 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.208 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.490 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 14.638 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  8.637 ms/op
                 existUser·p0.9999: 14.094 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.287 ms/op
                 existUser·p0.999:  7.702 ms/op
                 existUser·p0.9999: 18.075 ms/op
                 existUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320771
  mean =      2.993 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 860 
    [ 1.250,  2.500) = 26888 
    [ 2.500,  3.750) = 280541 
    [ 3.750,  5.000) = 10814 
    [ 5.000,  6.250) = 754 
    [ 6.250,  7.500) = 400 
    [ 7.500,  8.750) = 218 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.573 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     18.311 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 4.407 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.677 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  9.388 ms/op
                 getUser·p0.9999: 14.488 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.785 ms/op
                 getUser·p0.999:  10.054 ms/op
                 getUser·p0.9999: 15.439 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   3: 3.112 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  15.831 ms/op
                 getUser·p0.9999: 18.481 ms/op
                 getUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307349
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 612 
    [ 1.250,  2.500) = 15883 
    [ 2.500,  3.750) = 267347 
    [ 3.750,  5.000) = 21026 
    [ 5.000,  6.250) = 1308 
    [ 6.250,  7.500) = 454 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 203 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 100 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =      9.819 ms/op
     p(99.9900) =     18.040 ms/op
     p(99.9990) =     18.643 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 5.461 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.271 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.118 ±(99.9%) 0.012 ms/op
Iteration   1: 4.156 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  15.780 ms/op
                 listUser·p0.9999: 22.096 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   2: 4.110 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 19.582 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   3: 4.112 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 23.377 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232846
  mean =      4.126 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1725 
    [ 2.500,  5.000) = 206876 
    [ 5.000,  7.500) = 21808 
    [ 7.500, 10.000) = 1737 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     22.624 ms/op
     p(99.9990) =     23.736 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.379 ± 1.608  ops/ms
ClientGrpc.existUser                       thrpt       3  10.688 ± 4.228  ops/ms
ClientGrpc.getUser                         thrpt       3  10.318 ± 0.835  ops/ms
ClientGrpc.listUser                        thrpt       3   7.804 ± 0.467  ops/ms
ClientGrpc.createUser                       avgt       3   3.066 ± 0.368   ms/op
ClientGrpc.existUser                        avgt       3   2.959 ± 0.493   ms/op
ClientGrpc.getUser                          avgt       3   3.093 ± 0.347   ms/op
ClientGrpc.listUser                         avgt       3   4.041 ± 1.012   ms/op
ClientGrpc.createUser                     sample  308943   3.107 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.291           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.831           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.600           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.448           ms/op
ClientGrpc.existUser                      sample  320771   2.993 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.662           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.573           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.465           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.448           ms/op
ClientGrpc.getUser                        sample  307349   3.121 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.655           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.819           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.040           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.743           ms/op
ClientGrpc.listUser                       sample  232846   4.126 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.871           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.949           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.561           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.624           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.985           ms/op
