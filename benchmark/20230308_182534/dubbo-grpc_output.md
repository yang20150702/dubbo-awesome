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
# Warmup Iteration   1: 3.096 ops/ms
# Warmup Iteration   2: 6.634 ops/ms
# Warmup Iteration   3: 8.272 ops/ms
Iteration   1: 8.171 ops/ms
Iteration   2: 8.703 ops/ms
Iteration   3: 8.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.462 ±(99.9%) 4.913 ops/ms [Average]
  (min, avg, max) = (8.171, 8.462, 8.703), stdev = 0.269
  CI (99.9%): [3.548, 13.375] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.801 ops/ms
# Warmup Iteration   2: 8.416 ops/ms
# Warmup Iteration   3: 8.878 ops/ms
Iteration   1: 9.116 ops/ms
Iteration   2: 8.903 ops/ms
Iteration   3: 9.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.018 ±(99.9%) 1.955 ops/ms [Average]
  (min, avg, max) = (8.903, 9.018, 9.116), stdev = 0.107
  CI (99.9%): [7.062, 10.973] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.214 ops/ms
# Warmup Iteration   2: 8.141 ops/ms
# Warmup Iteration   3: 8.407 ops/ms
Iteration   1: 8.597 ops/ms
Iteration   2: 8.737 ops/ms
Iteration   3: 8.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.630 ±(99.9%) 1.731 ops/ms [Average]
  (min, avg, max) = (8.556, 8.630, 8.737), stdev = 0.095
  CI (99.9%): [6.899, 10.361] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.291 ops/ms
# Warmup Iteration   2: 6.273 ops/ms
# Warmup Iteration   3: 6.424 ops/ms
Iteration   1: 6.804 ops/ms
Iteration   2: 6.517 ops/ms
Iteration   3: 6.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.658 ±(99.9%) 2.612 ops/ms [Average]
  (min, avg, max) = (6.517, 6.658, 6.804), stdev = 0.143
  CI (99.9%): [4.045, 9.270] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.903 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.029 ms/op
Iteration   1: 3.690 ±(99.9%) 0.007 ms/op
Iteration   2: 3.623 ±(99.9%) 0.002 ms/op
Iteration   3: 3.765 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.693 ±(99.9%) 1.295 ms/op [Average]
  (min, avg, max) = (3.623, 3.693, 3.765), stdev = 0.071
  CI (99.9%): [2.398, 4.987] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.173 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.003 ms/op
Iteration   1: 3.452 ±(99.9%) 0.003 ms/op
Iteration   2: 3.432 ±(99.9%) 0.003 ms/op
Iteration   3: 3.397 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.427 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.397, 3.427, 3.452), stdev = 0.028
  CI (99.9%): [2.923, 3.931] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.996 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.665 ±(99.9%) 0.003 ms/op
Iteration   1: 3.616 ±(99.9%) 0.003 ms/op
Iteration   2: 3.667 ±(99.9%) 0.004 ms/op
Iteration   3: 3.554 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.612 ±(99.9%) 1.030 ms/op [Average]
  (min, avg, max) = (3.554, 3.612, 3.667), stdev = 0.056
  CI (99.9%): [2.582, 4.642] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.306 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.136 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.763 ±(99.9%) 0.018 ms/op
Iteration   1: 4.733 ±(99.9%) 0.009 ms/op
Iteration   2: 4.657 ±(99.9%) 0.013 ms/op
Iteration   3: 4.605 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.665 ±(99.9%) 1.174 ms/op [Average]
  (min, avg, max) = (4.605, 4.665, 4.733), stdev = 0.064
  CI (99.9%): [3.491, 5.839] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.073 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.010 ms/op
Iteration   1: 3.754 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  8.798 ms/op
                 createUser·p0.9999: 15.481 ms/op
                 createUser·p1.00:   15.761 ms/op

Iteration   2: 3.672 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  12.957 ms/op
                 createUser·p0.9999: 17.934 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   3: 3.820 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.553 ms/op
                 createUser·p0.999:  13.339 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256069
  mean =      3.748 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5462 
    [ 2.500,  5.000) = 240968 
    [ 5.000,  7.500) = 8511 
    [ 7.500, 10.000) = 816 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     10.748 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.481 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.008 ms/op
Iteration   1: 3.440 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.519 ms/op
                 existUser·p0.999:  12.253 ms/op
                 existUser·p0.9999: 16.030 ms/op
                 existUser·p1.00:   16.630 ms/op

Iteration   2: 3.382 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  7.848 ms/op
                 existUser·p0.9999: 15.714 ms/op
                 existUser·p1.00:   16.155 ms/op

Iteration   3: 3.498 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  10.142 ms/op
                 existUser·p0.9999: 29.351 ms/op
                 existUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279180
  mean =      3.439 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12421 
    [ 2.500,  5.000) = 262628 
    [ 5.000,  7.500) = 3489 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     10.395 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     29.584 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.545 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.009 ms/op
Iteration   1: 3.675 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  12.745 ms/op
                 getUser·p0.9999: 16.852 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   2: 3.619 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  9.020 ms/op
                 getUser·p0.9999: 15.518 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   3: 3.551 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.630 ms/op
                 getUser·p0.999:  11.053 ms/op
                 getUser·p0.9999: 26.729 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265723
  mean =      3.614 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12696 
    [ 2.500,  5.000) = 246004 
    [ 5.000,  7.500) = 5997 
    [ 7.500, 10.000) = 681 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     10.900 ms/op
     p(99.9900) =     25.620 ms/op
     p(99.9990) =     26.979 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 6.205 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.071 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.849 ±(99.9%) 0.015 ms/op
Iteration   1: 4.750 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.972 ms/op
                 listUser·p0.95:   6.767 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 19.276 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   2: 4.592 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   6.767 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  16.368 ms/op
                 listUser·p0.9999: 18.744 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 4.845 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   7.078 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  19.529 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203138
  mean =      4.727 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 352 
    [ 2.500,  5.000) = 151786 
    [ 5.000,  7.500) = 44812 
    [ 7.500, 10.000) = 5293 
    [10.000, 12.500) = 432 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     22.141 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.462 ± 4.913  ops/ms
ClientGrpc.existUser                       thrpt       3   9.018 ± 1.955  ops/ms
ClientGrpc.getUser                         thrpt       3   8.630 ± 1.731  ops/ms
ClientGrpc.listUser                        thrpt       3   6.658 ± 2.612  ops/ms
ClientGrpc.createUser                       avgt       3   3.693 ± 1.295   ms/op
ClientGrpc.existUser                        avgt       3   3.427 ± 0.504   ms/op
ClientGrpc.getUser                          avgt       3   3.612 ± 1.030   ms/op
ClientGrpc.listUser                         avgt       3   4.665 ± 1.174   ms/op
ClientGrpc.createUser                     sample  256069   3.748 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.945           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.833           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.226           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.748           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.840           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.529           ms/op
ClientGrpc.existUser                      sample  279180   3.439 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.770           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.395           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.197           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.721           ms/op
ClientGrpc.getUser                        sample  265723   3.614 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.660           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.849           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.900           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.620           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.329           ms/op
ClientGrpc.listUser                       sample  203138   4.727 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.053           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.733           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.072           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.141           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
