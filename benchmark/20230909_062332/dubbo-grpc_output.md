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
# Warmup Iteration   1: 3.761 ops/ms
# Warmup Iteration   2: 8.967 ops/ms
# Warmup Iteration   3: 9.950 ops/ms
Iteration   1: 10.404 ops/ms
Iteration   2: 10.619 ops/ms
Iteration   3: 10.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.506 ±(99.9%) 1.966 ops/ms [Average]
  (min, avg, max) = (10.404, 10.506, 10.619), stdev = 0.108
  CI (99.9%): [8.540, 12.472] (assumes normal distribution)


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
# Warmup Iteration   1: 7.790 ops/ms
# Warmup Iteration   2: 10.409 ops/ms
# Warmup Iteration   3: 11.191 ops/ms
Iteration   1: 11.244 ops/ms
Iteration   2: 10.954 ops/ms
Iteration   3: 11.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.147 ±(99.9%) 3.049 ops/ms [Average]
  (min, avg, max) = (10.954, 11.147, 11.244), stdev = 0.167
  CI (99.9%): [8.098, 14.195] (assumes normal distribution)


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
# Warmup Iteration   1: 6.661 ops/ms
# Warmup Iteration   2: 10.086 ops/ms
# Warmup Iteration   3: 10.496 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.411 ops/ms
Iteration   3: 10.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.479 ±(99.9%) 1.096 ops/ms [Average]
  (min, avg, max) = (10.411, 10.479, 10.527), stdev = 0.060
  CI (99.9%): [9.383, 11.575] (assumes normal distribution)


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
# Warmup Iteration   1: 5.574 ops/ms
# Warmup Iteration   2: 7.646 ops/ms
# Warmup Iteration   3: 7.752 ops/ms
Iteration   1: 7.922 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 8.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.985 ±(99.9%) 1.687 ops/ms [Average]
  (min, avg, max) = (7.922, 7.985, 8.091), stdev = 0.092
  CI (99.9%): [6.298, 9.672] (assumes normal distribution)


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.004 ms/op
Iteration   1: 3.103 ±(99.9%) 0.004 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.083 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.083 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (3.064, 3.083, 3.103), stdev = 0.020
  CI (99.9%): [2.723, 3.443] (assumes normal distribution)


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
# Warmup Iteration   1: 3.646 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.003 ms/op
Iteration   1: 2.945 ±(99.9%) 0.003 ms/op
Iteration   2: 2.934 ±(99.9%) 0.003 ms/op
Iteration   3: 2.879 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.919 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (2.879, 2.919, 2.945), stdev = 0.036
  CI (99.9%): [2.270, 3.569] (assumes normal distribution)


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.003 ms/op
Iteration   1: 3.054 ±(99.9%) 0.003 ms/op
Iteration   2: 2.996 ±(99.9%) 0.009 ms/op
Iteration   3: 3.032 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.027 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (2.996, 3.027, 3.054), stdev = 0.029
  CI (99.9%): [2.489, 3.565] (assumes normal distribution)


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
# Warmup Iteration   1: 5.568 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.024 ms/op
Iteration   1: 4.022 ±(99.9%) 0.022 ms/op
Iteration   2: 3.990 ±(99.9%) 0.014 ms/op
Iteration   3: 3.951 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.988 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.951, 3.988, 4.022), stdev = 0.035
  CI (99.9%): [3.342, 4.633] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
Iteration   1: 3.062 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  8.200 ms/op
                 createUser·p0.9999: 18.485 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.717 ms/op
                 createUser·p0.999:  14.516 ms/op
                 createUser·p0.9999: 20.401 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   3: 3.096 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 24.326 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311670
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22705 
    [ 2.500,  5.000) = 286886 
    [ 5.000,  7.500) = 1464 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      9.656 ms/op
     p(99.9900) =     23.926 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
Iteration   1: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.955 ms/op
                 existUser·p0.9999: 12.779 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 2.913 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  7.650 ms/op
                 existUser·p0.9999: 13.976 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.895 ms/op
                 existUser·p0.9999: 17.722 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330557
  mean =      2.902 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1368 
    [ 1.250,  2.500) = 40115 
    [ 2.500,  3.750) = 280034 
    [ 3.750,  5.000) = 7471 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 567 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.827 ms/op
     p(99.9900) =     15.646 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.444 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.309 ms/op
                 getUser·p0.9999: 15.931 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  8.444 ms/op
                 getUser·p0.9999: 19.149 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  7.832 ms/op
                 getUser·p0.9999: 20.205 ms/op
                 getUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313578
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21120 
    [ 2.500,  5.000) = 290015 
    [ 5.000,  7.500) = 1959 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     19.551 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 5.127 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.012 ms/op
Iteration   1: 4.045 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.939 ms/op
                 listUser·p0.9999: 20.221 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 4.075 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 22.812 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 4.009 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.243 ms/op
                 listUser·p0.999:  19.373 ms/op
                 listUser·p0.9999: 22.678 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237267
  mean =      4.043 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3085 
    [ 2.500,  5.000) = 206759 
    [ 5.000,  7.500) = 25604 
    [ 7.500, 10.000) = 1365 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     16.171 ms/op
     p(99.9900) =     22.398 ms/op
     p(99.9990) =     23.184 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.506 ± 1.966  ops/ms
ClientGrpc.existUser                       thrpt       3  11.147 ± 3.049  ops/ms
ClientGrpc.getUser                         thrpt       3  10.479 ± 1.096  ops/ms
ClientGrpc.listUser                        thrpt       3   7.985 ± 1.687  ops/ms
ClientGrpc.createUser                       avgt       3   3.083 ± 0.360   ms/op
ClientGrpc.existUser                        avgt       3   2.919 ± 0.650   ms/op
ClientGrpc.getUser                          avgt       3   3.027 ± 0.538   ms/op
ClientGrpc.listUser                         avgt       3   3.988 ± 0.646   ms/op
ClientGrpc.createUser                     sample  311670   3.077 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.647           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.656           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.926           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.904           ms/op
ClientGrpc.existUser                      sample  330557   2.902 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.681           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.827           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.646           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.859           ms/op
ClientGrpc.getUser                        sample  313578   3.059 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.444           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.176           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.551           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.249           ms/op
ClientGrpc.listUser                       sample  237267   4.043 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.948           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.234           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.171           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.398           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.265           ms/op
