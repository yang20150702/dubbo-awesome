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
# Warmup Iteration   1: 4.545 ops/ms
# Warmup Iteration   2: 9.222 ops/ms
# Warmup Iteration   3: 10.274 ops/ms
Iteration   1: 10.475 ops/ms
Iteration   2: 10.444 ops/ms
Iteration   3: 10.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.479 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (10.444, 10.479, 10.519), stdev = 0.038
  CI (99.9%): [9.787, 11.171] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.655 ops/ms
# Warmup Iteration   2: 11.139 ops/ms
# Warmup Iteration   3: 11.054 ops/ms
Iteration   1: 11.135 ops/ms
Iteration   2: 11.410 ops/ms
Iteration   3: 11.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.225 ±(99.9%) 2.923 ops/ms [Average]
  (min, avg, max) = (11.131, 11.225, 11.410), stdev = 0.160
  CI (99.9%): [8.302, 14.149] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.487 ops/ms
# Warmup Iteration   2: 10.488 ops/ms
# Warmup Iteration   3: 10.485 ops/ms
Iteration   1: 10.744 ops/ms
Iteration   2: 10.732 ops/ms
Iteration   3: 10.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.732 ±(99.9%) 0.204 ops/ms [Average]
  (min, avg, max) = (10.721, 10.732, 10.744), stdev = 0.011
  CI (99.9%): [10.528, 10.936] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.842 ops/ms
# Warmup Iteration   2: 7.952 ops/ms
# Warmup Iteration   3: 8.158 ops/ms
Iteration   1: 8.148 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.263 ±(99.9%) 2.060 ops/ms [Average]
  (min, avg, max) = (8.148, 8.263, 8.374), stdev = 0.113
  CI (99.9%): [6.203, 10.324] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.181 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.080 ±(99.9%) 0.003 ms/op
Iteration   2: 2.982 ±(99.9%) 0.003 ms/op
Iteration   3: 2.974 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.012 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (2.974, 3.012, 3.080), stdev = 0.059
  CI (99.9%): [1.932, 4.092] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.767 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.003 ms/op
Iteration   1: 2.925 ±(99.9%) 0.003 ms/op
Iteration   2: 2.876 ±(99.9%) 0.004 ms/op
Iteration   3: 2.836 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.879 ±(99.9%) 0.813 ms/op [Average]
  (min, avg, max) = (2.836, 2.879, 2.925), stdev = 0.045
  CI (99.9%): [2.066, 3.692] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.002 ms/op
Iteration   1: 3.100 ±(99.9%) 0.003 ms/op
Iteration   2: 3.006 ±(99.9%) 0.002 ms/op
Iteration   3: 2.998 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.035 ±(99.9%) 1.029 ms/op [Average]
  (min, avg, max) = (2.998, 3.035, 3.100), stdev = 0.056
  CI (99.9%): [2.005, 4.064] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.012 ms/op
Iteration   1: 3.926 ±(99.9%) 0.027 ms/op
Iteration   2: 3.912 ±(99.9%) 0.018 ms/op
Iteration   3: 3.890 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.909 ±(99.9%) 0.325 ms/op [Average]
  (min, avg, max) = (3.890, 3.909, 3.926), stdev = 0.018
  CI (99.9%): [3.584, 4.235] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
Iteration   1: 2.974 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  5.931 ms/op
                 createUser·p0.9999: 14.327 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 16.134 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.676 ms/op
                 createUser·p0.9999: 26.435 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318748
  mean =      3.013 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25293 
    [ 2.500,  5.000) = 292048 
    [ 5.000,  7.500) = 1030 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.913 ms/op
     p(99.9900) =     25.477 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.866 ±(99.9%) 0.007 ms/op
Iteration   1: 2.843 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.589 ms/op
                 existUser·p0.9999: 18.014 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   2: 2.789 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  6.490 ms/op
                 existUser·p0.9999: 21.004 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   3: 2.824 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.600 ms/op
                 existUser·p0.999:  8.700 ms/op
                 existUser·p0.9999: 26.378 ms/op
                 existUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340808
  mean =      2.819 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65474 
    [ 2.500,  5.000) = 273983 
    [ 5.000,  7.500) = 1005 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.586 ms/op
     p(99.9900) =     22.187 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.007 ms/op
Iteration   1: 3.072 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.847 ms/op
                 getUser·p0.9999: 12.337 ms/op
                 getUser·p1.00:   12.354 ms/op

Iteration   2: 2.940 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.685 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.223 ms/op
                 getUser·p0.9999: 12.648 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.320 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.180 ms/op
                 getUser·p0.9999: 14.838 ms/op
                 getUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319523
  mean =      3.001 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2476 
    [ 1.250,  2.500) = 23346 
    [ 2.500,  3.750) = 276364 
    [ 3.750,  5.000) = 16310 
    [ 5.000,  6.250) = 593 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.320 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.582 ms/op
     p(99.9900) =     14.387 ms/op
     p(99.9990) =     15.391 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


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
# Warmup Iteration   1: 4.656 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
Iteration   1: 3.884 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 18.990 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 3.883 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.572 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  16.958 ms/op
                 listUser·p0.9999: 24.429 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   3: 3.950 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.827 ms/op
                 listUser·p0.9999: 20.536 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245902
  mean =      3.906 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5083 
    [ 2.500,  5.000) = 217878 
    [ 5.000,  7.500) = 21562 
    [ 7.500, 10.000) = 816 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.550 ms/op
     p(99.9900) =     23.732 ms/op
     p(99.9990) =     25.416 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.479 ± 0.692  ops/ms
ClientGrpc.existUser                       thrpt       3  11.225 ± 2.923  ops/ms
ClientGrpc.getUser                         thrpt       3  10.732 ± 0.204  ops/ms
ClientGrpc.listUser                        thrpt       3   8.263 ± 2.060  ops/ms
ClientGrpc.createUser                       avgt       3   3.012 ± 1.080   ms/op
ClientGrpc.existUser                        avgt       3   2.879 ± 0.813   ms/op
ClientGrpc.getUser                          avgt       3   3.035 ± 1.029   ms/op
ClientGrpc.listUser                         avgt       3   3.909 ± 0.325   ms/op
ClientGrpc.createUser                     sample  318748   3.013 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.753           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.913           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.477           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.525           ms/op
ClientGrpc.existUser                      sample  340808   2.819 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.531           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.586           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.187           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.509           ms/op
ClientGrpc.getUser                        sample  319523   3.001 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.320           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.582           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.387           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.729           ms/op
ClientGrpc.listUser                       sample  245902   3.906 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.572           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.550           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.732           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.559           ms/op
