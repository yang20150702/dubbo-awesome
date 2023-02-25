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
# Warmup Iteration   1: 2.027 ops/ms
# Warmup Iteration   2: 4.894 ops/ms
# Warmup Iteration   3: 6.320 ops/ms
Iteration   1: 6.624 ops/ms
Iteration   2: 6.715 ops/ms
Iteration   3: 6.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.625 ±(99.9%) 1.638 ops/ms [Average]
  (min, avg, max) = (6.535, 6.625, 6.715), stdev = 0.090
  CI (99.9%): [4.987, 8.263] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.490 ops/ms
# Warmup Iteration   2: 6.496 ops/ms
# Warmup Iteration   3: 6.768 ops/ms
Iteration   1: 7.025 ops/ms
Iteration   2: 6.846 ops/ms
Iteration   3: 7.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.996 ±(99.9%) 2.512 ops/ms [Average]
  (min, avg, max) = (6.846, 6.996, 7.117), stdev = 0.138
  CI (99.9%): [4.484, 9.508] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ops/ms
# Warmup Iteration   2: 6.200 ops/ms
# Warmup Iteration   3: 6.703 ops/ms
Iteration   1: 6.766 ops/ms
Iteration   2: 6.877 ops/ms
Iteration   3: 6.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.827 ±(99.9%) 1.029 ops/ms [Average]
  (min, avg, max) = (6.766, 6.827, 6.877), stdev = 0.056
  CI (99.9%): [5.798, 7.856] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.279 ops/ms
# Warmup Iteration   2: 4.626 ops/ms
# Warmup Iteration   3: 5.045 ops/ms
Iteration   1: 5.205 ops/ms
Iteration   2: 5.484 ops/ms
Iteration   3: 5.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.276 ±(99.9%) 3.331 ops/ms [Average]
  (min, avg, max) = (5.140, 5.276, 5.484), stdev = 0.183
  CI (99.9%): [1.946, 8.607] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.515 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.010 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.826 ±(99.9%) 0.006 ms/op
Iteration   1: 4.942 ±(99.9%) 0.003 ms/op
Iteration   2: 4.900 ±(99.9%) 0.004 ms/op
Iteration   3: 4.935 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.926 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (4.900, 4.926, 4.942), stdev = 0.023
  CI (99.9%): [4.512, 5.339] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.536 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.888 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.563 ±(99.9%) 0.004 ms/op
Iteration   1: 4.450 ±(99.9%) 0.003 ms/op
Iteration   2: 4.476 ±(99.9%) 0.005 ms/op
Iteration   3: 4.325 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.417 ±(99.9%) 1.481 ms/op [Average]
  (min, avg, max) = (4.325, 4.417, 4.476), stdev = 0.081
  CI (99.9%): [2.937, 5.898] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.539 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.154 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.820 ±(99.9%) 0.012 ms/op
Iteration   1: 4.837 ±(99.9%) 0.003 ms/op
Iteration   2: 4.836 ±(99.9%) 0.006 ms/op
Iteration   3: 4.770 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.815 ±(99.9%) 0.700 ms/op [Average]
  (min, avg, max) = (4.770, 4.815, 4.837), stdev = 0.038
  CI (99.9%): [4.114, 5.515] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.595 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.799 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.456 ±(99.9%) 0.021 ms/op
Iteration   1: 6.529 ±(99.9%) 0.015 ms/op
Iteration   2: 6.353 ±(99.9%) 0.023 ms/op
Iteration   3: 6.307 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.396 ±(99.9%) 2.141 ms/op [Average]
  (min, avg, max) = (6.307, 6.396, 6.529), stdev = 0.117
  CI (99.9%): [4.255, 8.537] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.738 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.079 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.833 ±(99.9%) 0.016 ms/op
Iteration   1: 4.752 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   4.620 ms/op
                 createUser·p0.90:   5.956 ms/op
                 createUser·p0.95:   6.455 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  14.270 ms/op
                 createUser·p0.9999: 15.950 ms/op
                 createUser·p1.00:   16.499 ms/op

Iteration   2: 4.840 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   4.735 ms/op
                 createUser·p0.90:   6.177 ms/op
                 createUser·p0.95:   6.668 ms/op
                 createUser·p0.99:   8.375 ms/op
                 createUser·p0.999:  13.106 ms/op
                 createUser·p0.9999: 18.592 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   3: 4.726 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   4.588 ms/op
                 createUser·p0.90:   5.898 ms/op
                 createUser·p0.95:   6.431 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  15.062 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 201105
  mean =      4.772 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3525 
    [ 2.500,  5.000) = 126474 
    [ 5.000,  7.500) = 67188 
    [ 7.500, 10.000) = 3010 
    [10.000, 12.500) = 506 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.529 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     14.431 ms/op
     p(99.9900) =     21.518 ms/op
     p(99.9990) =     23.067 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.115 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.130 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.599 ±(99.9%) 0.015 ms/op
Iteration   1: 4.631 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.882 ms/op
                 existUser·p0.95:   6.398 ms/op
                 existUser·p0.99:   8.298 ms/op
                 existUser·p0.999:  13.615 ms/op
                 existUser·p0.9999: 19.837 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   2: 4.529 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   5.767 ms/op
                 existUser·p0.95:   6.226 ms/op
                 existUser·p0.99:   8.281 ms/op
                 existUser·p0.999:  12.025 ms/op
                 existUser·p0.9999: 19.562 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   3: 4.554 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   4.448 ms/op
                 existUser·p0.90:   5.718 ms/op
                 existUser·p0.95:   6.210 ms/op
                 existUser·p0.99:   8.782 ms/op
                 existUser·p0.999:  12.419 ms/op
                 existUser·p0.9999: 22.050 ms/op
                 existUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 209970
  mean =      4.571 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6247 
    [ 2.500,  5.000) = 141155 
    [ 5.000,  7.500) = 59013 
    [ 7.500, 10.000) = 2558 
    [10.000, 12.500) = 779 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.792 ms/op
     p(95.0000) =      6.283 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     21.693 ms/op
     p(99.9990) =     23.216 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.268 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.297 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.868 ±(99.9%) 0.016 ms/op
Iteration   1: 4.927 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   6.242 ms/op
                 getUser·p0.95:   6.816 ms/op
                 getUser·p0.99:   9.224 ms/op
                 getUser·p0.999:  14.287 ms/op
                 getUser·p0.9999: 19.367 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   2: 4.872 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   4.792 ms/op
                 getUser·p0.90:   6.177 ms/op
                 getUser·p0.95:   6.652 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  13.764 ms/op
                 getUser·p0.9999: 20.705 ms/op
                 getUser·p1.00:   21.266 ms/op

Iteration   3: 4.927 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   4.792 ms/op
                 getUser·p0.90:   6.324 ms/op
                 getUser·p0.95:   6.799 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  19.414 ms/op
                 getUser·p0.9999: 26.854 ms/op
                 getUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 195462
  mean =      4.909 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3450 
    [ 2.500,  5.000) = 109937 
    [ 5.000,  7.500) = 77397 
    [ 7.500, 10.000) = 3579 
    [10.000, 12.500) = 739 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.250 ms/op
     p(95.0000) =      6.750 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     14.501 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     30.547 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.164 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 6.977 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.170 ±(99.9%) 0.025 ms/op
Iteration   1: 6.442 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   6.062 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   9.732 ms/op
                 listUser·p0.99:   12.468 ms/op
                 listUser·p0.999:  21.594 ms/op
                 listUser·p0.9999: 28.082 ms/op
                 listUser·p1.00:   29.622 ms/op

Iteration   2: 6.175 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   8.233 ms/op
                 listUser·p0.95:   9.290 ms/op
                 listUser·p0.99:   12.386 ms/op
                 listUser·p0.999:  18.891 ms/op
                 listUser·p0.9999: 21.445 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 6.006 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   7.807 ms/op
                 listUser·p0.95:   8.782 ms/op
                 listUser·p0.99:   11.338 ms/op
                 listUser·p0.999:  21.861 ms/op
                 listUser·p0.9999: 24.773 ms/op
                 listUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 154739
  mean =      6.202 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 29525 
    [ 5.000,  7.500) = 100919 
    [ 7.500, 10.000) = 19341 
    [10.000, 12.500) = 3618 
    [12.500, 15.000) = 796 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      5.874 ms/op
     p(90.0000) =      8.225 ms/op
     p(95.0000) =      9.290 ms/op
     p(99.0000) =     12.091 ms/op
     p(99.9000) =     20.161 ms/op
     p(99.9900) =     27.103 ms/op
     p(99.9990) =     29.533 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.625 ± 1.638  ops/ms
ClientGrpc.existUser                       thrpt       3   6.996 ± 2.512  ops/ms
ClientGrpc.getUser                         thrpt       3   6.827 ± 1.029  ops/ms
ClientGrpc.listUser                        thrpt       3   5.276 ± 3.331  ops/ms
ClientGrpc.createUser                       avgt       3   4.926 ± 0.413   ms/op
ClientGrpc.existUser                        avgt       3   4.417 ± 1.481   ms/op
ClientGrpc.getUser                          avgt       3   4.815 ± 0.700   ms/op
ClientGrpc.listUser                         avgt       3   6.396 ± 2.141   ms/op
ClientGrpc.createUser                     sample  201105   4.772 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.926           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.021           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.529           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.520           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.431           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.518           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.069           ms/op
ClientGrpc.existUser                      sample  209970   4.571 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.872           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.792           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.283           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.454           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.550           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.693           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.429           ms/op
ClientGrpc.getUser                        sample  195462   4.909 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.945           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.250           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.750           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.946           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.501           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.821           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.768           ms/op
ClientGrpc.listUser                       sample  154739   6.202 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.401           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.225           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.290           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.091           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.161           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.103           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.622           ms/op
