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
# Warmup Iteration   1: 3.874 ops/ms
# Warmup Iteration   2: 9.303 ops/ms
# Warmup Iteration   3: 9.889 ops/ms
Iteration   1: 10.250 ops/ms
Iteration   2: 10.131 ops/ms
Iteration   3: 10.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.148 ±(99.9%) 1.720 ops/ms [Average]
  (min, avg, max) = (10.064, 10.148, 10.250), stdev = 0.094
  CI (99.9%): [8.428, 11.868] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.328 ops/ms
# Warmup Iteration   2: 10.621 ops/ms
# Warmup Iteration   3: 10.538 ops/ms
Iteration   1: 10.694 ops/ms
Iteration   2: 10.596 ops/ms
Iteration   3: 10.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.641 ±(99.9%) 0.899 ops/ms [Average]
  (min, avg, max) = (10.596, 10.641, 10.694), stdev = 0.049
  CI (99.9%): [9.742, 11.540] (assumes normal distribution)


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
# Warmup Iteration   1: 7.594 ops/ms
# Warmup Iteration   2: 9.929 ops/ms
# Warmup Iteration   3: 10.246 ops/ms
Iteration   1: 10.286 ops/ms
Iteration   2: 10.312 ops/ms
Iteration   3: 10.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.255 ±(99.9%) 1.395 ops/ms [Average]
  (min, avg, max) = (10.168, 10.255, 10.312), stdev = 0.076
  CI (99.9%): [8.860, 11.650] (assumes normal distribution)


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
# Warmup Iteration   1: 5.781 ops/ms
# Warmup Iteration   2: 7.713 ops/ms
# Warmup Iteration   3: 7.954 ops/ms
Iteration   1: 7.982 ops/ms
Iteration   2: 8.246 ops/ms
Iteration   3: 8.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.094 ±(99.9%) 2.496 ops/ms [Average]
  (min, avg, max) = (7.982, 8.094, 8.246), stdev = 0.137
  CI (99.9%): [5.597, 10.590] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.328 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.331 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.001 ms/op
Iteration   1: 3.121 ±(99.9%) 0.008 ms/op
Iteration   2: 3.125 ±(99.9%) 0.001 ms/op
Iteration   3: 3.126 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.124 ±(99.9%) 0.047 ms/op [Average]
  (min, avg, max) = (3.121, 3.124, 3.126), stdev = 0.003
  CI (99.9%): [3.078, 3.171] (assumes normal distribution)


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.001 ms/op
Iteration   1: 3.020 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.002 ms/op
Iteration   3: 3.033 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.032 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (3.020, 3.032, 3.044), stdev = 0.012
  CI (99.9%): [2.812, 3.253] (assumes normal distribution)


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.004 ms/op
Iteration   2: 3.136 ±(99.9%) 0.002 ms/op
Iteration   3: 3.142 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.125 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (3.098, 3.125, 3.142), stdev = 0.024
  CI (99.9%): [2.694, 3.557] (assumes normal distribution)


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
# Warmup Iteration   1: 5.444 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.029 ms/op
Iteration   1: 3.979 ±(99.9%) 0.020 ms/op
Iteration   2: 3.853 ±(99.9%) 0.009 ms/op
Iteration   3: 3.904 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.912 ±(99.9%) 1.160 ms/op [Average]
  (min, avg, max) = (3.853, 3.912, 3.979), stdev = 0.064
  CI (99.9%): [2.752, 5.072] (assumes normal distribution)


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.006 ms/op
Iteration   1: 3.131 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  7.912 ms/op
                 createUser·p0.9999: 13.550 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   2: 3.121 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  8.135 ms/op
                 createUser·p0.9999: 13.705 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   3: 3.196 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  8.878 ms/op
                 createUser·p0.9999: 18.186 ms/op
                 createUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304641
  mean =      3.149 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 265 
    [ 1.250,  2.500) = 10783 
    [ 2.500,  3.750) = 267628 
    [ 3.750,  5.000) = 23542 
    [ 5.000,  6.250) = 1377 
    [ 6.250,  7.500) = 647 
    [ 7.500,  8.750) = 146 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.830 ms/op
     p(99.9000) =      8.152 ms/op
     p(99.9900) =     16.155 ms/op
     p(99.9990) =     18.477 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.504 ms/op
                 existUser·p0.9999: 12.765 ms/op
                 existUser·p1.00:   13.222 ms/op

Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  7.859 ms/op
                 existUser·p0.9999: 14.174 ms/op
                 existUser·p1.00:   15.843 ms/op

Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  11.019 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313506
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1010 
    [ 1.250,  2.500) = 19569 
    [ 2.500,  3.750) = 273673 
    [ 3.750,  5.000) = 17119 
    [ 5.000,  6.250) = 1021 
    [ 6.250,  7.500) = 594 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      9.052 ms/op
     p(99.9900) =     16.449 ms/op
     p(99.9990) =     17.428 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.237 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
Iteration   1: 3.182 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  7.748 ms/op
                 getUser·p0.9999: 21.559 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.979 ms/op
                 getUser·p0.99:   4.808 ms/op
                 getUser·p0.999:  8.634 ms/op
                 getUser·p0.9999: 20.739 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  9.808 ms/op
                 getUser·p0.9999: 20.045 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302926
  mean =      3.170 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8206 
    [ 2.500,  5.000) = 292251 
    [ 5.000,  7.500) = 2021 
    [ 7.500, 10.000) = 225 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =      8.145 ms/op
     p(99.9900) =     20.887 ms/op
     p(99.9990) =     21.691 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 4.974 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.010 ms/op
Iteration   1: 3.895 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.287 ms/op
                 listUser·p0.9999: 14.600 ms/op
                 listUser·p1.00:   15.516 ms/op

Iteration   2: 3.946 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.548 ms/op
                 listUser·p0.9999: 16.368 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   3: 3.982 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  15.212 ms/op
                 listUser·p0.9999: 17.560 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243721
  mean =      3.941 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1795 
    [ 2.500,  3.750) = 96530 
    [ 3.750,  5.000) = 131523 
    [ 5.000,  6.250) = 8547 
    [ 6.250,  7.500) = 4080 
    [ 7.500,  8.750) = 491 
    [ 8.750, 10.000) = 164 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 169 
    [15.000, 16.250) = 114 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     16.519 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.148 ± 1.720  ops/ms
ClientGrpc.existUser                       thrpt       3  10.641 ± 0.899  ops/ms
ClientGrpc.getUser                         thrpt       3  10.255 ± 1.395  ops/ms
ClientGrpc.listUser                        thrpt       3   8.094 ± 2.496  ops/ms
ClientGrpc.createUser                       avgt       3   3.124 ± 0.047   ms/op
ClientGrpc.existUser                        avgt       3   3.032 ± 0.220   ms/op
ClientGrpc.getUser                          avgt       3   3.125 ± 0.432   ms/op
ClientGrpc.listUser                         avgt       3   3.912 ± 1.160   ms/op
ClientGrpc.createUser                     sample  304641   3.149 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.867           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.830           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.152           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.155           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.612           ms/op
ClientGrpc.existUser                      sample  313506   3.063 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.687           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.019           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.052           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.449           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.564           ms/op
ClientGrpc.getUser                        sample  302926   3.170 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.605           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.145           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.887           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.823           ms/op
ClientGrpc.listUser                       sample  243721   3.941 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.118           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.415           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.189           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.519           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.186           ms/op
