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
# Warmup Iteration   1: 4.778 ops/ms
# Warmup Iteration   2: 9.097 ops/ms
# Warmup Iteration   3: 10.113 ops/ms
Iteration   1: 10.607 ops/ms
Iteration   2: 10.766 ops/ms
Iteration   3: 10.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.683 ±(99.9%) 1.455 ops/ms [Average]
  (min, avg, max) = (10.607, 10.683, 10.766), stdev = 0.080
  CI (99.9%): [9.229, 12.138] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.772 ops/ms
# Warmup Iteration   2: 10.961 ops/ms
# Warmup Iteration   3: 10.910 ops/ms
Iteration   1: 10.870 ops/ms
Iteration   2: 11.139 ops/ms
Iteration   3: 11.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.039 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (10.870, 11.039, 11.139), stdev = 0.147
  CI (99.9%): [8.351, 13.727] (assumes normal distribution)


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
# Warmup Iteration   1: 7.738 ops/ms
# Warmup Iteration   2: 10.425 ops/ms
# Warmup Iteration   3: 10.597 ops/ms
Iteration   1: 10.688 ops/ms
Iteration   2: 10.788 ops/ms
Iteration   3: 10.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.767 ±(99.9%) 1.308 ops/ms [Average]
  (min, avg, max) = (10.688, 10.767, 10.827), stdev = 0.072
  CI (99.9%): [9.459, 12.076] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.848 ops/ms
# Warmup Iteration   2: 8.177 ops/ms
# Warmup Iteration   3: 8.240 ops/ms
Iteration   1: 8.372 ops/ms
Iteration   2: 8.306 ops/ms
Iteration   3: 8.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.330 ±(99.9%) 0.664 ops/ms [Average]
  (min, avg, max) = (8.306, 8.330, 8.372), stdev = 0.036
  CI (99.9%): [7.666, 8.994] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.143 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.004 ms/op
Iteration   1: 3.065 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
Iteration   3: 3.079 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.064 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (3.047, 3.064, 3.079), stdev = 0.016
  CI (99.9%): [2.767, 3.360] (assumes normal distribution)


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
# Warmup Iteration   1: 3.694 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.861 ±(99.9%) 0.003 ms/op
Iteration   1: 2.875 ±(99.9%) 0.003 ms/op
Iteration   2: 2.819 ±(99.9%) 0.005 ms/op
Iteration   3: 2.864 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.853 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (2.819, 2.853, 2.875), stdev = 0.030
  CI (99.9%): [2.306, 3.399] (assumes normal distribution)


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.003 ms/op
Iteration   1: 2.957 ±(99.9%) 0.003 ms/op
Iteration   2: 2.961 ±(99.9%) 0.003 ms/op
Iteration   3: 2.957 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.959 ±(99.9%) 0.045 ms/op [Average]
  (min, avg, max) = (2.957, 2.959, 2.961), stdev = 0.002
  CI (99.9%): [2.914, 3.003] (assumes normal distribution)


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
# Warmup Iteration   1: 4.856 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.027 ms/op
Iteration   1: 3.883 ±(99.9%) 0.013 ms/op
Iteration   2: 3.903 ±(99.9%) 0.017 ms/op
Iteration   3: 3.866 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.884 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (3.866, 3.884, 3.903), stdev = 0.019
  CI (99.9%): [3.540, 4.228] (assumes normal distribution)


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
Iteration   1: 3.018 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  8.152 ms/op
                 createUser·p0.9999: 15.942 ms/op
                 createUser·p1.00:   16.433 ms/op

Iteration   2: 2.968 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  11.101 ms/op
                 createUser·p0.9999: 15.621 ms/op
                 createUser·p1.00:   16.597 ms/op

Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.392 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 21.791 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320050
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34537 
    [ 2.500,  5.000) = 281170 
    [ 5.000,  7.500) = 3764 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     10.256 ms/op
     p(99.9900) =     19.327 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.931 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.834 ±(99.9%) 0.007 ms/op
Iteration   1: 2.882 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  7.354 ms/op
                 existUser·p0.9999: 22.664 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   2: 2.888 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  7.283 ms/op
                 existUser·p0.9999: 25.948 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 2.904 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.928 ms/op
                 existUser·p0.999:  10.052 ms/op
                 existUser·p0.9999: 24.769 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332045
  mean =      2.891 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48694 
    [ 2.500,  5.000) = 280022 
    [ 5.000,  7.500) = 2884 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =      8.961 ms/op
     p(99.9900) =     25.375 ms/op
     p(99.9990) =     26.652 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
Iteration   1: 2.988 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  8.020 ms/op
                 getUser·p0.9999: 20.195 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.145 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 14.421 ms/op
                 getUser·p1.00:   15.090 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  9.175 ms/op
                 getUser·p0.9999: 16.187 ms/op
                 getUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319853
  mean =      3.000 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29384 
    [ 2.500,  5.000) = 286666 
    [ 5.000,  7.500) = 3277 
    [ 7.500, 10.000) = 278 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =      9.063 ms/op
     p(99.9900) =     17.468 ms/op
     p(99.9990) =     21.483 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 5.121 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.011 ms/op
Iteration   1: 3.818 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 14.815 ms/op
                 listUser·p1.00:   15.319 ms/op

Iteration   2: 3.819 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.288 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.133 ms/op
                 listUser·p0.9999: 17.775 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   3: 3.851 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.799 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.547 ms/op
                 listUser·p0.9999: 28.170 ms/op
                 listUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250754
  mean =      3.829 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6210 
    [ 2.500,  5.000) = 220681 
    [ 5.000,  7.500) = 22165 
    [ 7.500, 10.000) = 1100 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.288 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     27.195 ms/op
     p(99.9990) =     28.360 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.683 ± 1.455  ops/ms
ClientGrpc.existUser                       thrpt       3  11.039 ± 2.688  ops/ms
ClientGrpc.getUser                         thrpt       3  10.767 ± 1.308  ops/ms
ClientGrpc.listUser                        thrpt       3   8.330 ± 0.664  ops/ms
ClientGrpc.createUser                       avgt       3   3.064 ± 0.296   ms/op
ClientGrpc.existUser                        avgt       3   2.853 ± 0.546   ms/op
ClientGrpc.getUser                          avgt       3   2.959 ± 0.045   ms/op
ClientGrpc.listUser                         avgt       3   3.884 ± 0.344   ms/op
ClientGrpc.createUser                     sample  320050   2.997 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.521           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.333           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.256           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.327           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.889           ms/op
ClientGrpc.existUser                      sample  332045   2.891 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.521           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.005           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.961           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.375           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.787           ms/op
ClientGrpc.getUser                        sample  319853   3.000 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.654           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.169           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.063           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.468           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.823           ms/op
ClientGrpc.listUser                       sample  250754   3.829 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.288           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.631           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.195           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.409           ms/op
