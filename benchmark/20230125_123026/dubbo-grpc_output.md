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
# Warmup Iteration   1: 4.864 ops/ms
# Warmup Iteration   2: 9.545 ops/ms
# Warmup Iteration   3: 10.383 ops/ms
Iteration   1: 10.362 ops/ms
Iteration   2: 10.406 ops/ms
Iteration   3: 10.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.288 ±(99.9%) 3.064 ops/ms [Average]
  (min, avg, max) = (10.096, 10.288, 10.406), stdev = 0.168
  CI (99.9%): [7.224, 13.352] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.251 ops/ms
# Warmup Iteration   2: 10.823 ops/ms
# Warmup Iteration   3: 11.035 ops/ms
Iteration   1: 10.686 ops/ms
Iteration   2: 11.104 ops/ms
Iteration   3: 11.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.993 ±(99.9%) 4.909 ops/ms [Average]
  (min, avg, max) = (10.686, 10.993, 11.189), stdev = 0.269
  CI (99.9%): [6.084, 15.902] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.834 ops/ms
# Warmup Iteration   2: 10.386 ops/ms
# Warmup Iteration   3: 10.675 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.756 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.602 ±(99.9%) 2.614 ops/ms [Average]
  (min, avg, max) = (10.473, 10.602, 10.756), stdev = 0.143
  CI (99.9%): [7.988, 13.216] (assumes normal distribution)


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
# Warmup Iteration   1: 5.638 ops/ms
# Warmup Iteration   2: 7.803 ops/ms
# Warmup Iteration   3: 7.981 ops/ms
Iteration   1: 7.863 ops/ms
Iteration   2: 7.700 ops/ms
Iteration   3: 7.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.831 ±(99.9%) 2.157 ops/ms [Average]
  (min, avg, max) = (7.700, 7.831, 7.929), stdev = 0.118
  CI (99.9%): [5.674, 9.987] (assumes normal distribution)


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
# Warmup Iteration   1: 3.910 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.002 ms/op
Iteration   1: 3.050 ±(99.9%) 0.002 ms/op
Iteration   2: 3.129 ±(99.9%) 0.001 ms/op
Iteration   3: 3.115 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.098 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (3.050, 3.098, 3.129), stdev = 0.042
  CI (99.9%): [2.334, 3.862] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.612 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.003 ms/op
Iteration   1: 2.957 ±(99.9%) 0.003 ms/op
Iteration   2: 2.991 ±(99.9%) 0.002 ms/op
Iteration   3: 2.941 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.963 ±(99.9%) 0.465 ms/op [Average]
  (min, avg, max) = (2.941, 2.963, 2.991), stdev = 0.025
  CI (99.9%): [2.498, 3.428] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.004 ms/op
Iteration   1: 2.955 ±(99.9%) 0.002 ms/op
Iteration   2: 3.004 ±(99.9%) 0.002 ms/op
Iteration   3: 3.018 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.992 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.955, 2.992, 3.018), stdev = 0.033
  CI (99.9%): [2.388, 3.596] (assumes normal distribution)


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
# Warmup Iteration   1: 4.857 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.017 ms/op
Iteration   1: 3.971 ±(99.9%) 0.014 ms/op
Iteration   2: 3.891 ±(99.9%) 0.017 ms/op
Iteration   3: 3.862 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.908 ±(99.9%) 1.023 ms/op [Average]
  (min, avg, max) = (3.862, 3.908, 3.971), stdev = 0.056
  CI (99.9%): [2.885, 4.931] (assumes normal distribution)


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.008 ms/op
Iteration   1: 3.124 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.929 ms/op
                 createUser·p0.9999: 30.221 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  5.792 ms/op
                 createUser·p0.9999: 21.020 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   3: 3.099 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.506 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  10.351 ms/op
                 createUser·p0.9999: 25.416 ms/op
                 createUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309468
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24115 
    [ 2.500,  5.000) = 284450 
    [ 5.000,  7.500) = 535 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.528 ms/op
     p(99.9900) =     29.069 ms/op
     p(99.9990) =     30.569 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 3.554 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  8.450 ms/op
                 existUser·p0.9999: 15.618 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.358 ms/op
                 existUser·p0.9999: 14.192 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   3: 2.931 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.610 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.337 ms/op
                 existUser·p0.9999: 28.478 ms/op
                 existUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324656
  mean =      2.955 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51436 
    [ 2.500,  5.000) = 272521 
    [ 5.000,  7.500) = 412 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      6.639 ms/op
     p(99.9900) =     22.745 ms/op
     p(99.9990) =     28.820 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.346 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.127 ms/op
                 getUser·p0.9999: 33.121 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  6.742 ms/op
                 getUser·p0.9999: 18.686 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.478 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.298 ms/op
                 getUser·p0.9999: 36.929 ms/op
                 getUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318784
  mean =      3.012 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34879 
    [ 2.500,  5.000) = 282968 
    [ 5.000,  7.500) = 727 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.744 ms/op
     p(99.9900) =     35.461 ms/op
     p(99.9990) =     37.265 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 5.205 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.011 ms/op
Iteration   1: 4.025 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  11.261 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 3.934 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 15.352 ms/op
                 listUser·p1.00:   15.876 ms/op

Iteration   3: 3.923 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  15.001 ms/op
                 listUser·p0.9999: 19.322 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242452
  mean =      3.960 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 3555 
    [ 2.500,  3.750) = 104920 
    [ 3.750,  5.000) = 109706 
    [ 5.000,  6.250) = 19865 
    [ 6.250,  7.500) = 3436 
    [ 7.500,  8.750) = 410 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 103 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     13.952 ms/op
     p(99.9900) =     18.539 ms/op
     p(99.9990) =     19.731 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.288 ± 3.064  ops/ms
ClientGrpc.existUser                       thrpt       3  10.993 ± 4.909  ops/ms
ClientGrpc.getUser                         thrpt       3  10.602 ± 2.614  ops/ms
ClientGrpc.listUser                        thrpt       3   7.831 ± 2.157  ops/ms
ClientGrpc.createUser                       avgt       3   3.098 ± 0.764   ms/op
ClientGrpc.existUser                        avgt       3   2.963 ± 0.465   ms/op
ClientGrpc.getUser                          avgt       3   2.992 ± 0.604   ms/op
ClientGrpc.listUser                         avgt       3   3.908 ± 1.023   ms/op
ClientGrpc.createUser                     sample  309468   3.106 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.506           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.528           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.069           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.671           ms/op
ClientGrpc.existUser                      sample  324656   2.955 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.610           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.639           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.745           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.934           ms/op
ClientGrpc.getUser                        sample  318784   3.012 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.346           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.744           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.461           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.356           ms/op
ClientGrpc.listUser                       sample  242452   3.960 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.059           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.952           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.539           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.857           ms/op
