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
# Warmup Iteration   1: 3.682 ops/ms
# Warmup Iteration   2: 8.203 ops/ms
# Warmup Iteration   3: 9.138 ops/ms
Iteration   1: 9.286 ops/ms
Iteration   2: 9.129 ops/ms
Iteration   3: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.262 ±(99.9%) 2.239 ops/ms [Average]
  (min, avg, max) = (9.129, 9.262, 9.371), stdev = 0.123
  CI (99.9%): [7.023, 11.501] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.486 ops/ms
# Warmup Iteration   2: 9.675 ops/ms
# Warmup Iteration   3: 10.242 ops/ms
Iteration   1: 10.067 ops/ms
Iteration   2: 10.415 ops/ms
Iteration   3: 10.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.323 ±(99.9%) 4.098 ops/ms [Average]
  (min, avg, max) = (10.067, 10.323, 10.486), stdev = 0.225
  CI (99.9%): [6.225, 14.421] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.352 ops/ms
# Warmup Iteration   2: 9.226 ops/ms
# Warmup Iteration   3: 9.766 ops/ms
Iteration   1: 9.996 ops/ms
Iteration   2: 9.736 ops/ms
Iteration   3: 10.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.936 ±(99.9%) 3.239 ops/ms [Average]
  (min, avg, max) = (9.736, 9.936, 10.076), stdev = 0.178
  CI (99.9%): [6.697, 13.175] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.282 ops/ms
# Warmup Iteration   2: 7.149 ops/ms
# Warmup Iteration   3: 7.772 ops/ms
Iteration   1: 7.495 ops/ms
Iteration   2: 7.677 ops/ms
Iteration   3: 7.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.525 ±(99.9%) 2.531 ops/ms [Average]
  (min, avg, max) = (7.405, 7.525, 7.677), stdev = 0.139
  CI (99.9%): [4.995, 10.056] (assumes normal distribution)


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.004 ms/op
Iteration   1: 3.285 ±(99.9%) 0.004 ms/op
Iteration   2: 3.304 ±(99.9%) 0.005 ms/op
Iteration   3: 3.389 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.326 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (3.285, 3.326, 3.389), stdev = 0.055
  CI (99.9%): [2.315, 4.337] (assumes normal distribution)


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.362 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.004 ms/op
Iteration   1: 3.227 ±(99.9%) 0.003 ms/op
Iteration   2: 3.195 ±(99.9%) 0.004 ms/op
Iteration   3: 3.331 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.251 ±(99.9%) 1.294 ms/op [Average]
  (min, avg, max) = (3.195, 3.251, 3.331), stdev = 0.071
  CI (99.9%): [1.957, 4.545] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.672 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.003 ms/op
Iteration   1: 3.438 ±(99.9%) 0.003 ms/op
Iteration   2: 3.376 ±(99.9%) 0.003 ms/op
Iteration   3: 3.359 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.391 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.359, 3.391, 3.438), stdev = 0.042
  CI (99.9%): [2.632, 4.150] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.073 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.556 ±(99.9%) 0.014 ms/op
Iteration   1: 4.443 ±(99.9%) 0.016 ms/op
Iteration   2: 4.364 ±(99.9%) 0.016 ms/op
Iteration   3: 4.512 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.440 ±(99.9%) 1.353 ms/op [Average]
  (min, avg, max) = (4.364, 4.440, 4.512), stdev = 0.074
  CI (99.9%): [3.087, 5.793] (assumes normal distribution)


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
# Warmup Iteration   1: 4.826 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.009 ms/op
Iteration   1: 3.347 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  10.870 ms/op
                 createUser·p0.9999: 14.500 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   2: 3.347 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  12.000 ms/op
                 createUser·p0.9999: 14.232 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   3: 3.328 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 287225
  mean =      3.340 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14669 
    [ 2.500,  5.000) = 267281 
    [ 5.000,  7.500) = 4499 
    [ 7.500, 10.000) = 471 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     10.351 ms/op
     p(99.9900) =     20.311 ms/op
     p(99.9990) =     22.188 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 4.752 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.008 ms/op
Iteration   1: 3.133 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  9.450 ms/op
                 existUser·p0.9999: 15.898 ms/op
                 existUser·p1.00:   16.204 ms/op

Iteration   2: 3.262 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 14.755 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 3.095 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  10.185 ms/op
                 existUser·p0.9999: 16.477 ms/op
                 existUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 303593
  mean =      3.162 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2802 
    [ 1.250,  2.500) = 23179 
    [ 2.500,  3.750) = 242859 
    [ 3.750,  5.000) = 29741 
    [ 5.000,  6.250) = 3089 
    [ 6.250,  7.500) = 809 
    [ 7.500,  8.750) = 485 
    [ 8.750, 10.000) = 305 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 65 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     10.263 ms/op
     p(99.9900) =     16.067 ms/op
     p(99.9990) =     16.694 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.764 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.378 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
Iteration   1: 3.528 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  9.575 ms/op
                 getUser·p0.9999: 17.498 ms/op
                 getUser·p1.00:   18.678 ms/op

Iteration   2: 3.483 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.171 ms/op
                 getUser·p0.999:  8.750 ms/op
                 getUser·p0.9999: 19.872 ms/op
                 getUser·p1.00:   22.151 ms/op

Iteration   3: 3.692 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.634 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  10.164 ms/op
                 getUser·p0.9999: 20.775 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 269500
  mean =      3.565 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14273 
    [ 2.500,  5.000) = 246672 
    [ 5.000,  7.500) = 7381 
    [ 7.500, 10.000) = 970 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     20.219 ms/op
     p(99.9990) =     22.040 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 6.125 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.395 ±(99.9%) 0.015 ms/op
Iteration   1: 4.365 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.540 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  16.089 ms/op
                 listUser·p0.9999: 25.472 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   2: 4.394 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   5.726 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.570 ms/op
                 listUser·p0.999:  19.399 ms/op
                 listUser·p0.9999: 28.761 ms/op
                 listUser·p1.00:   32.768 ms/op

Iteration   3: 4.316 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   5.702 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 29.150 ms/op
                 listUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 220295
  mean =      4.358 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1946 
    [ 2.500,  5.000) = 177073 
    [ 5.000,  7.500) = 36779 
    [ 7.500, 10.000) = 3664 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.792 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     17.675 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     32.689 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.262 ± 2.239  ops/ms
ClientGrpc.existUser                       thrpt       3  10.323 ± 4.098  ops/ms
ClientGrpc.getUser                         thrpt       3   9.936 ± 3.239  ops/ms
ClientGrpc.listUser                        thrpt       3   7.525 ± 2.531  ops/ms
ClientGrpc.createUser                       avgt       3   3.326 ± 1.011   ms/op
ClientGrpc.existUser                        avgt       3   3.251 ± 1.294   ms/op
ClientGrpc.getUser                          avgt       3   3.391 ± 0.759   ms/op
ClientGrpc.listUser                         avgt       3   4.440 ± 1.353   ms/op
ClientGrpc.createUser                     sample  287225   3.340 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.569           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.285           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.051           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.554           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.351           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.311           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.708           ms/op
ClientGrpc.existUser                      sample  303593   3.162 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.680           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.133           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.263           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.067           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.810           ms/op
ClientGrpc.getUser                        sample  269500   3.565 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.634           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.185           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.404           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.219           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.151           ms/op
ClientGrpc.listUser                       sample  220295   4.358 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.540           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.080           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.348           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.675           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.705           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.768           ms/op
