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
# Warmup Iteration   1: 2.515 ops/ms
# Warmup Iteration   2: 5.832 ops/ms
# Warmup Iteration   3: 7.260 ops/ms
Iteration   1: 7.407 ops/ms
Iteration   2: 7.694 ops/ms
Iteration   3: 7.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.521 ±(99.9%) 2.783 ops/ms [Average]
  (min, avg, max) = (7.407, 7.521, 7.694), stdev = 0.153
  CI (99.9%): [4.738, 10.304] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.234 ops/ms
# Warmup Iteration   2: 7.432 ops/ms
# Warmup Iteration   3: 7.861 ops/ms
Iteration   1: 7.890 ops/ms
Iteration   2: 8.080 ops/ms
Iteration   3: 8.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.056 ±(99.9%) 2.834 ops/ms [Average]
  (min, avg, max) = (7.890, 8.056, 8.198), stdev = 0.155
  CI (99.9%): [5.222, 10.890] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.597 ops/ms
# Warmup Iteration   2: 6.602 ops/ms
# Warmup Iteration   3: 7.445 ops/ms
Iteration   1: 7.460 ops/ms
Iteration   2: 7.378 ops/ms
Iteration   3: 7.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.430 ±(99.9%) 0.828 ops/ms [Average]
  (min, avg, max) = (7.378, 7.430, 7.460), stdev = 0.045
  CI (99.9%): [6.602, 8.257] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ops/ms
# Warmup Iteration   2: 5.741 ops/ms
# Warmup Iteration   3: 5.972 ops/ms
Iteration   1: 6.208 ops/ms
Iteration   2: 6.161 ops/ms
Iteration   3: 6.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.170 ±(99.9%) 0.632 ops/ms [Average]
  (min, avg, max) = (6.141, 6.170, 6.208), stdev = 0.035
  CI (99.9%): [5.538, 6.801] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.580 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.009 ms/op
Iteration   1: 4.312 ±(99.9%) 0.004 ms/op
Iteration   2: 4.222 ±(99.9%) 0.003 ms/op
Iteration   3: 4.320 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.285 ±(99.9%) 0.993 ms/op [Average]
  (min, avg, max) = (4.222, 4.285, 4.320), stdev = 0.054
  CI (99.9%): [3.291, 5.278] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.839 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.003 ms/op
Iteration   1: 4.003 ±(99.9%) 0.004 ms/op
Iteration   2: 3.906 ±(99.9%) 0.003 ms/op
Iteration   3: 4.090 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.000 ±(99.9%) 1.678 ms/op [Average]
  (min, avg, max) = (3.906, 4.000, 4.090), stdev = 0.092
  CI (99.9%): [2.322, 5.677] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.855 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.592 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.321 ±(99.9%) 0.014 ms/op
Iteration   1: 4.340 ±(99.9%) 0.010 ms/op
Iteration   2: 4.017 ±(99.9%) 0.005 ms/op
Iteration   3: 3.922 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.093 ±(99.9%) 4.002 ms/op [Average]
  (min, avg, max) = (3.922, 4.093, 4.340), stdev = 0.219
  CI (99.9%): [0.091, 8.095] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.433 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.619 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.557 ±(99.9%) 0.022 ms/op
Iteration   1: 5.349 ±(99.9%) 0.024 ms/op
Iteration   2: 5.412 ±(99.9%) 0.053 ms/op
Iteration   3: 5.498 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.420 ±(99.9%) 1.367 ms/op [Average]
  (min, avg, max) = (5.349, 5.420, 5.498), stdev = 0.075
  CI (99.9%): [4.053, 6.786] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.962 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.545 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.440 ±(99.9%) 0.015 ms/op
Iteration   1: 4.493 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.455 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.775 ms/op
                 createUser·p0.95:   6.210 ms/op
                 createUser·p0.99:   8.039 ms/op
                 createUser·p0.999:  14.107 ms/op
                 createUser·p0.9999: 19.158 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 4.324 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.628 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   8.634 ms/op
                 createUser·p0.999:  14.978 ms/op
                 createUser·p0.9999: 20.500 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   3: 4.144 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   7.234 ms/op
                 createUser·p0.999:  10.818 ms/op
                 createUser·p0.9999: 24.374 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222308
  mean =      4.315 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5608 
    [ 2.500,  5.000) = 170530 
    [ 5.000,  7.500) = 43195 
    [ 7.500, 10.000) = 2212 
    [10.000, 12.500) = 424 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      4.166 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     13.982 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     25.107 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.085 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.010 ms/op
Iteration   1: 3.864 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  13.110 ms/op
                 existUser·p0.9999: 19.478 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   2: 3.847 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.850 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  9.876 ms/op
                 existUser·p0.9999: 16.526 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   3: 3.866 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.891 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  11.654 ms/op
                 existUser·p0.9999: 21.118 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 248785
  mean =      3.859 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8300 
    [ 2.500,  5.000) = 219596 
    [ 5.000,  7.500) = 19140 
    [ 7.500, 10.000) = 1328 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     11.525 ms/op
     p(99.9900) =     19.644 ms/op
     p(99.9990) =     21.546 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 6.245 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.777 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.284 ±(99.9%) 0.014 ms/op
Iteration   1: 4.227 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   5.926 ms/op
                 getUser·p0.99:   8.380 ms/op
                 getUser·p0.999:  13.064 ms/op
                 getUser·p0.9999: 20.518 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   2: 4.047 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  12.468 ms/op
                 getUser·p0.9999: 21.387 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   3: 3.981 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  10.841 ms/op
                 getUser·p0.9999: 35.975 ms/op
                 getUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235097
  mean =      4.082 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5829 
    [ 2.500,  5.000) = 197626 
    [ 5.000,  7.500) = 29469 
    [ 7.500, 10.000) = 1659 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     12.385 ms/op
     p(99.9900) =     35.422 ms/op
     p(99.9990) =     36.651 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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
# Warmup Iteration   1: 7.682 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.676 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.517 ±(99.9%) 0.023 ms/op
Iteration   1: 5.347 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.126 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  17.937 ms/op
                 listUser·p0.9999: 20.809 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   2: 5.307 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   4.973 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   10.396 ms/op
                 listUser·p0.999:  19.530 ms/op
                 listUser·p0.9999: 22.511 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   3: 5.504 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   5.079 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  22.887 ms/op
                 listUser·p0.9999: 26.665 ms/op
                 listUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178131
  mean =      5.385 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 360 
    [ 2.500,  5.000) = 87884 
    [ 5.000,  7.500) = 73335 
    [ 7.500, 10.000) = 14161 
    [10.000, 12.500) = 1590 
    [12.500, 15.000) = 420 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      7.397 ms/op
     p(95.0000) =      8.298 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     25.932 ms/op
     p(99.9990) =     27.121 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.521 ± 2.783  ops/ms
ClientGrpc.existUser                       thrpt       3   8.056 ± 2.834  ops/ms
ClientGrpc.getUser                         thrpt       3   7.430 ± 0.828  ops/ms
ClientGrpc.listUser                        thrpt       3   6.170 ± 0.632  ops/ms
ClientGrpc.createUser                       avgt       3   4.285 ± 0.993   ms/op
ClientGrpc.existUser                        avgt       3   4.000 ± 1.678   ms/op
ClientGrpc.getUser                          avgt       3   4.093 ± 4.002   ms/op
ClientGrpc.listUser                         avgt       3   5.420 ± 1.367   ms/op
ClientGrpc.createUser                     sample  222308   4.315 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.455           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.166           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.562           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.038           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.930           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.982           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.839           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.771           ms/op
ClientGrpc.existUser                      sample  248785   3.859 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.819           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.914           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.525           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.644           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.692           ms/op
ClientGrpc.getUser                        sample  235097   4.082 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.863           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.628           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.356           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.385           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.422           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.897           ms/op
ClientGrpc.listUser                       sample  178131   5.385 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.397           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.298           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.535           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.268           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.932           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
