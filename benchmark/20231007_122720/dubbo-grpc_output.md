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
# Warmup Iteration   1: 3.077 ops/ms
# Warmup Iteration   2: 7.227 ops/ms
# Warmup Iteration   3: 8.356 ops/ms
Iteration   1: 8.564 ops/ms
Iteration   2: 8.668 ops/ms
Iteration   3: 8.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.607 ±(99.9%) 0.991 ops/ms [Average]
  (min, avg, max) = (8.564, 8.607, 8.668), stdev = 0.054
  CI (99.9%): [7.616, 9.598] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.575 ops/ms
# Warmup Iteration   2: 8.910 ops/ms
# Warmup Iteration   3: 9.516 ops/ms
Iteration   1: 9.342 ops/ms
Iteration   2: 9.564 ops/ms
Iteration   3: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.426 ±(99.9%) 2.203 ops/ms [Average]
  (min, avg, max) = (9.342, 9.426, 9.564), stdev = 0.121
  CI (99.9%): [7.223, 11.629] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.628 ops/ms
# Warmup Iteration   2: 8.224 ops/ms
# Warmup Iteration   3: 8.434 ops/ms
Iteration   1: 8.638 ops/ms
Iteration   2: 8.890 ops/ms
Iteration   3: 8.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.803 ±(99.9%) 2.611 ops/ms [Average]
  (min, avg, max) = (8.638, 8.803, 8.890), stdev = 0.143
  CI (99.9%): [6.192, 11.414] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.294 ops/ms
# Warmup Iteration   2: 6.639 ops/ms
# Warmup Iteration   3: 6.503 ops/ms
Iteration   1: 6.595 ops/ms
Iteration   2: 6.628 ops/ms
Iteration   3: 7.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.744 ±(99.9%) 4.182 ops/ms [Average]
  (min, avg, max) = (6.595, 6.744, 7.008), stdev = 0.229
  CI (99.9%): [2.562, 10.925] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.437 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.002 ms/op
Iteration   1: 3.759 ±(99.9%) 0.005 ms/op
Iteration   2: 3.610 ±(99.9%) 0.003 ms/op
Iteration   3: 3.617 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.662 ±(99.9%) 1.531 ms/op [Average]
  (min, avg, max) = (3.610, 3.662, 3.759), stdev = 0.084
  CI (99.9%): [2.131, 5.193] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.755 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.002 ms/op
Iteration   1: 3.317 ±(99.9%) 0.002 ms/op
Iteration   2: 3.309 ±(99.9%) 0.002 ms/op
Iteration   3: 3.292 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.306 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (3.292, 3.306, 3.317), stdev = 0.013
  CI (99.9%): [3.068, 3.544] (assumes normal distribution)


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
# Warmup Iteration   1: 4.681 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.009 ms/op
Iteration   1: 3.610 ±(99.9%) 0.003 ms/op
Iteration   2: 3.645 ±(99.9%) 0.002 ms/op
Iteration   3: 3.651 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.635 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.610, 3.635, 3.651), stdev = 0.022
  CI (99.9%): [3.226, 4.045] (assumes normal distribution)


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
# Warmup Iteration   1: 7.074 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.908 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.737 ±(99.9%) 0.020 ms/op
Iteration   1: 4.708 ±(99.9%) 0.017 ms/op
Iteration   2: 4.642 ±(99.9%) 0.017 ms/op
Iteration   3: 4.799 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.716 ±(99.9%) 1.431 ms/op [Average]
  (min, avg, max) = (4.642, 4.716, 4.799), stdev = 0.078
  CI (99.9%): [3.285, 6.148] (assumes normal distribution)


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
# Warmup Iteration   1: 5.216 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.705 ±(99.9%) 0.009 ms/op
Iteration   1: 3.610 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  11.387 ms/op
                 createUser·p0.9999: 16.819 ms/op
                 createUser·p1.00:   17.400 ms/op

Iteration   2: 3.553 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 16.007 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   3: 3.616 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.479 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  11.354 ms/op
                 createUser·p0.9999: 17.312 ms/op
                 createUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 267109
  mean =      3.593 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 348 
    [ 1.250,  2.500) = 11044 
    [ 2.500,  3.750) = 162720 
    [ 3.750,  5.000) = 83500 
    [ 5.000,  6.250) = 7113 
    [ 6.250,  7.500) = 1197 
    [ 7.500,  8.750) = 628 
    [ 8.750, 10.000) = 198 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 98 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     11.072 ms/op
     p(99.9900) =     16.239 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 4.859 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.008 ms/op
Iteration   1: 3.491 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  9.509 ms/op
                 existUser·p0.9999: 15.349 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   2: 3.288 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  9.516 ms/op
                 existUser·p0.9999: 15.373 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   3: 3.356 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  9.781 ms/op
                 existUser·p0.9999: 14.966 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 284043
  mean =      3.376 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 485 
    [ 1.250,  2.500) = 11138 
    [ 2.500,  3.750) = 213813 
    [ 3.750,  5.000) = 52907 
    [ 5.000,  6.250) = 3586 
    [ 6.250,  7.500) = 1029 
    [ 7.500,  8.750) = 549 
    [ 8.750, 10.000) = 298 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     15.286 ms/op
     p(99.9990) =     16.990 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 4.945 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.010 ms/op
Iteration   1: 3.653 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  9.295 ms/op
                 getUser·p0.9999: 18.538 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   2: 3.636 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.602 ms/op
                 getUser·p0.999:  8.192 ms/op
                 getUser·p0.9999: 18.193 ms/op
                 getUser·p1.00:   20.578 ms/op

Iteration   3: 3.660 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  8.901 ms/op
                 getUser·p0.9999: 22.422 ms/op
                 getUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262940
  mean =      3.650 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4511 
    [ 2.500,  5.000) = 249694 
    [ 5.000,  7.500) = 7938 
    [ 7.500, 10.000) = 612 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      5.919 ms/op
     p(99.9000) =      8.766 ms/op
     p(99.9900) =     20.704 ms/op
     p(99.9990) =     22.634 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 6.069 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.776 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.724 ±(99.9%) 0.015 ms/op
Iteration   1: 4.792 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.988 ms/op
                 listUser·p0.95:   6.898 ms/op
                 listUser·p0.99:   8.775 ms/op
                 listUser·p0.999:  13.972 ms/op
                 listUser·p0.9999: 17.574 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 4.853 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   9.030 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 28.570 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   3: 4.876 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.423 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  18.856 ms/op
                 listUser·p0.9999: 25.981 ms/op
                 listUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198216
  mean =      4.840 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 426 
    [ 2.500,  5.000) = 135228 
    [ 5.000,  7.500) = 55597 
    [ 7.500, 10.000) = 5785 
    [10.000, 12.500) = 680 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     27.760 ms/op
     p(99.9990) =     29.100 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.607 ± 0.991  ops/ms
ClientGrpc.existUser                       thrpt       3   9.426 ± 2.203  ops/ms
ClientGrpc.getUser                         thrpt       3   8.803 ± 2.611  ops/ms
ClientGrpc.listUser                        thrpt       3   6.744 ± 4.182  ops/ms
ClientGrpc.createUser                       avgt       3   3.662 ± 1.531   ms/op
ClientGrpc.existUser                        avgt       3   3.306 ± 0.238   ms/op
ClientGrpc.getUser                          avgt       3   3.635 ± 0.410   ms/op
ClientGrpc.listUser                         avgt       3   4.716 ± 1.431   ms/op
ClientGrpc.createUser                     sample  267109   3.593 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.755           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.103           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.072           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.239           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.564           ms/op
ClientGrpc.existUser                      sample  284043   3.376 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.614           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.718           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.634           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.286           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.400           ms/op
ClientGrpc.getUser                        sample  262940   3.650 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.861           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.919           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.766           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.704           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.774           ms/op
ClientGrpc.listUser                       sample  198216   4.840 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.448           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.193           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.224           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.498           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.760           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.229           ms/op
