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
# Warmup Iteration   1: 3.375 ops/ms
# Warmup Iteration   2: 7.134 ops/ms
# Warmup Iteration   3: 8.299 ops/ms
Iteration   1: 8.594 ops/ms
Iteration   2: 8.582 ops/ms
Iteration   3: 8.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.593 ±(99.9%) 0.175 ops/ms [Average]
  (min, avg, max) = (8.582, 8.593, 8.601), stdev = 0.010
  CI (99.9%): [8.418, 8.768] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.934 ops/ms
# Warmup Iteration   2: 9.067 ops/ms
# Warmup Iteration   3: 9.365 ops/ms
Iteration   1: 9.344 ops/ms
Iteration   2: 9.311 ops/ms
Iteration   3: 9.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.242 ±(99.9%) 2.715 ops/ms [Average]
  (min, avg, max) = (9.071, 9.242, 9.344), stdev = 0.149
  CI (99.9%): [6.527, 11.957] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.440 ops/ms
# Warmup Iteration   2: 8.239 ops/ms
# Warmup Iteration   3: 8.523 ops/ms
Iteration   1: 8.893 ops/ms
Iteration   2: 8.853 ops/ms
Iteration   3: 9.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.927 ±(99.9%) 1.770 ops/ms [Average]
  (min, avg, max) = (8.853, 8.927, 9.037), stdev = 0.097
  CI (99.9%): [7.158, 10.697] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.584 ops/ms
# Warmup Iteration   2: 6.235 ops/ms
# Warmup Iteration   3: 6.573 ops/ms
Iteration   1: 6.934 ops/ms
Iteration   2: 6.738 ops/ms
Iteration   3: 6.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.872 ±(99.9%) 2.128 ops/ms [Average]
  (min, avg, max) = (6.738, 6.872, 6.945), stdev = 0.117
  CI (99.9%): [4.744, 9.001] (assumes normal distribution)


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
# Warmup Iteration   1: 5.256 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.016 ms/op
Iteration   1: 3.709 ±(99.9%) 0.003 ms/op
Iteration   2: 3.545 ±(99.9%) 0.004 ms/op
Iteration   3: 3.609 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.621 ±(99.9%) 1.508 ms/op [Average]
  (min, avg, max) = (3.545, 3.621, 3.709), stdev = 0.083
  CI (99.9%): [2.113, 5.129] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.034 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.003 ms/op
Iteration   1: 3.624 ±(99.9%) 0.002 ms/op
Iteration   2: 3.394 ±(99.9%) 0.004 ms/op
Iteration   3: 3.548 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.522 ±(99.9%) 2.138 ms/op [Average]
  (min, avg, max) = (3.394, 3.522, 3.624), stdev = 0.117
  CI (99.9%): [1.384, 5.660] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.298 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.004 ms/op
Iteration   1: 3.595 ±(99.9%) 0.003 ms/op
Iteration   2: 3.581 ±(99.9%) 0.005 ms/op
Iteration   3: 3.654 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.610 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (3.581, 3.610, 3.654), stdev = 0.039
  CI (99.9%): [2.903, 4.318] (assumes normal distribution)


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
# Warmup Iteration   1: 6.734 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.993 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.675 ±(99.9%) 0.011 ms/op
Iteration   1: 4.532 ±(99.9%) 0.013 ms/op
Iteration   2: 4.588 ±(99.9%) 0.018 ms/op
Iteration   3: 4.593 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.571 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (4.532, 4.571, 4.593), stdev = 0.034
  CI (99.9%): [3.954, 5.188] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.233 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.009 ms/op
Iteration   1: 3.553 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  10.026 ms/op
                 createUser·p0.9999: 14.926 ms/op
                 createUser·p1.00:   15.155 ms/op

Iteration   2: 3.645 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   5.742 ms/op
                 createUser·p0.999:  8.088 ms/op
                 createUser·p0.9999: 22.353 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   3: 3.643 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   3.559 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.659 ms/op
                 createUser·p0.999:  13.214 ms/op
                 createUser·p0.9999: 19.570 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265539
  mean =      3.613 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7783 
    [ 2.500,  5.000) = 251286 
    [ 5.000,  7.500) = 5686 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     11.418 ms/op
     p(99.9900) =     21.084 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 4.799 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.731 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.007 ms/op
Iteration   1: 3.689 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  11.441 ms/op
                 existUser·p0.9999: 18.252 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 3.467 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  8.662 ms/op
                 existUser·p0.9999: 15.803 ms/op
                 existUser·p1.00:   16.040 ms/op

Iteration   3: 3.486 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  9.142 ms/op
                 existUser·p0.9999: 19.983 ms/op
                 existUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270692
  mean =      3.545 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6914 
    [ 2.500,  5.000) = 257911 
    [ 5.000,  7.500) = 5070 
    [ 7.500, 10.000) = 592 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 5.208 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.010 ms/op
Iteration   1: 3.687 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.354 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  12.309 ms/op
                 getUser·p0.9999: 29.272 ms/op
                 getUser·p1.00:   30.245 ms/op

Iteration   2: 3.657 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  10.396 ms/op
                 getUser·p0.9999: 25.379 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   3: 3.695 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 26.990 ms/op
                 getUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260997
  mean =      3.680 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5602 
    [ 2.500,  5.000) = 247760 
    [ 5.000,  7.500) = 6718 
    [ 7.500, 10.000) = 605 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     26.998 ms/op
     p(99.9990) =     29.785 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 6.508 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.033 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.762 ±(99.9%) 0.015 ms/op
Iteration   1: 4.721 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  14.801 ms/op
                 listUser·p0.9999: 16.948 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   2: 4.715 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.799 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  15.587 ms/op
                 listUser·p0.9999: 25.599 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   3: 4.674 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.660 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  24.243 ms/op
                 listUser·p0.9999: 28.738 ms/op
                 listUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204150
  mean =      4.704 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 618 
    [ 2.500,  5.000) = 156167 
    [ 5.000,  7.500) = 42392 
    [ 7.500, 10.000) = 4239 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.898 ms/op
     p(95.0000) =      6.717 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     27.662 ms/op
     p(99.9990) =     29.094 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.593 ± 0.175  ops/ms
ClientGrpc.existUser                       thrpt       3   9.242 ± 2.715  ops/ms
ClientGrpc.getUser                         thrpt       3   8.927 ± 1.770  ops/ms
ClientGrpc.listUser                        thrpt       3   6.872 ± 2.128  ops/ms
ClientGrpc.createUser                       avgt       3   3.621 ± 1.508   ms/op
ClientGrpc.existUser                        avgt       3   3.522 ± 2.138   ms/op
ClientGrpc.getUser                          avgt       3   3.610 ± 0.707   ms/op
ClientGrpc.listUser                         avgt       3   4.571 ± 0.617   ms/op
ClientGrpc.createUser                     sample  265539   3.613 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.718           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.718           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.418           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.084           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.855           ms/op
ClientGrpc.existUser                      sample  270692   3.545 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.756           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.628           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.241           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.317           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.283           ms/op
ClientGrpc.getUser                        sample  260997   3.680 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.354           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.972           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.699           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.998           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.245           ms/op
ClientGrpc.listUser                       sample  204150   4.704 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.010           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.421           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.860           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.662           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.196           ms/op
