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
# Warmup Iteration   1: 1.881 ops/ms
# Warmup Iteration   2: 4.844 ops/ms
# Warmup Iteration   3: 6.086 ops/ms
Iteration   1: 6.410 ops/ms
Iteration   2: 6.386 ops/ms
Iteration   3: 6.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.445 ±(99.9%) 1.493 ops/ms [Average]
  (min, avg, max) = (6.386, 6.445, 6.538), stdev = 0.082
  CI (99.9%): [4.952, 7.937] (assumes normal distribution)


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
# Warmup Iteration   1: 4.364 ops/ms
# Warmup Iteration   2: 6.599 ops/ms
# Warmup Iteration   3: 6.806 ops/ms
Iteration   1: 6.738 ops/ms
Iteration   2: 6.802 ops/ms
Iteration   3: 6.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.803 ±(99.9%) 1.190 ops/ms [Average]
  (min, avg, max) = (6.738, 6.803, 6.868), stdev = 0.065
  CI (99.9%): [5.613, 7.992] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.958 ops/ms
# Warmup Iteration   2: 6.012 ops/ms
# Warmup Iteration   3: 6.180 ops/ms
Iteration   1: 6.321 ops/ms
Iteration   2: 6.223 ops/ms
Iteration   3: 6.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.293 ±(99.9%) 1.110 ops/ms [Average]
  (min, avg, max) = (6.223, 6.293, 6.334), stdev = 0.061
  CI (99.9%): [5.183, 7.402] (assumes normal distribution)


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
# Warmup Iteration   1: 3.249 ops/ms
# Warmup Iteration   2: 4.393 ops/ms
# Warmup Iteration   3: 4.886 ops/ms
Iteration   1: 4.895 ops/ms
Iteration   2: 4.939 ops/ms
Iteration   3: 5.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.979 ±(99.9%) 1.992 ops/ms [Average]
  (min, avg, max) = (4.895, 4.979, 5.102), stdev = 0.109
  CI (99.9%): [2.986, 6.971] (assumes normal distribution)


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
# Warmup Iteration   1: 8.440 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.255 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.027 ±(99.9%) 0.006 ms/op
Iteration   1: 4.999 ±(99.9%) 0.003 ms/op
Iteration   2: 4.797 ±(99.9%) 0.005 ms/op
Iteration   3: 4.948 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.915 ±(99.9%) 1.908 ms/op [Average]
  (min, avg, max) = (4.797, 4.915, 4.999), stdev = 0.105
  CI (99.9%): [3.006, 6.823] (assumes normal distribution)


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
# Warmup Iteration   1: 6.873 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.034 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.009 ±(99.9%) 0.005 ms/op
Iteration   1: 4.745 ±(99.9%) 0.008 ms/op
Iteration   2: 4.731 ±(99.9%) 0.005 ms/op
Iteration   3: 4.631 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.703 ±(99.9%) 1.133 ms/op [Average]
  (min, avg, max) = (4.631, 4.703, 4.745), stdev = 0.062
  CI (99.9%): [3.570, 5.836] (assumes normal distribution)


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
# Warmup Iteration   1: 7.382 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.475 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.122 ±(99.9%) 0.004 ms/op
Iteration   1: 5.107 ±(99.9%) 0.004 ms/op
Iteration   2: 4.914 ±(99.9%) 0.004 ms/op
Iteration   3: 5.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.016 ±(99.9%) 1.767 ms/op [Average]
  (min, avg, max) = (4.914, 5.016, 5.107), stdev = 0.097
  CI (99.9%): [3.249, 6.782] (assumes normal distribution)


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
# Warmup Iteration   1: 9.943 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 7.043 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 6.421 ±(99.9%) 0.024 ms/op
Iteration   1: 6.116 ±(99.9%) 0.016 ms/op
Iteration   2: 6.174 ±(99.9%) 0.024 ms/op
Iteration   3: 6.087 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.125 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (6.087, 6.125, 6.174), stdev = 0.044
  CI (99.9%): [5.319, 6.932] (assumes normal distribution)


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
# Warmup Iteration   1: 7.341 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.119 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.121 ±(99.9%) 0.018 ms/op
Iteration   1: 5.078 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   4.792 ms/op
                 createUser·p0.90:   6.668 ms/op
                 createUser·p0.95:   7.553 ms/op
                 createUser·p0.99:   10.109 ms/op
                 createUser·p0.999:  16.073 ms/op
                 createUser·p0.9999: 24.593 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 4.935 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   6.382 ms/op
                 createUser·p0.95:   7.078 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  17.139 ms/op
                 createUser·p0.9999: 22.446 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   3: 4.754 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   4.579 ms/op
                 createUser·p0.90:   6.062 ms/op
                 createUser·p0.95:   6.775 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  21.618 ms/op
                 createUser·p0.9999: 27.719 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 195145
  mean =      4.918 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2465 
    [ 2.500,  5.000) = 117423 
    [ 5.000,  7.500) = 67897 
    [ 7.500, 10.000) = 5960 
    [10.000, 12.500) = 879 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.152 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     18.313 ms/op
     p(99.9900) =     26.819 ms/op
     p(99.9990) =     28.781 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 6.784 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.855 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.849 ±(99.9%) 0.017 ms/op
Iteration   1: 4.664 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   4.489 ms/op
                 existUser·p0.90:   6.242 ms/op
                 existUser·p0.95:   7.004 ms/op
                 existUser·p0.99:   9.159 ms/op
                 existUser·p0.999:  12.674 ms/op
                 existUser·p0.9999: 19.600 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   2: 4.716 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   4.555 ms/op
                 existUser·p0.90:   6.226 ms/op
                 existUser·p0.95:   6.914 ms/op
                 existUser·p0.99:   8.897 ms/op
                 existUser·p0.999:  13.880 ms/op
                 existUser·p0.9999: 27.263 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   3: 4.759 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   4.563 ms/op
                 existUser·p0.90:   6.201 ms/op
                 existUser·p0.95:   6.881 ms/op
                 existUser·p0.99:   9.306 ms/op
                 existUser·p0.999:  14.877 ms/op
                 existUser·p0.9999: 25.422 ms/op
                 existUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 203581
  mean =      4.713 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5756 
    [ 2.500,  5.000) = 128782 
    [ 5.000,  7.500) = 62582 
    [ 7.500, 10.000) = 5300 
    [10.000, 12.500) = 773 
    [12.500, 15.000) = 236 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     14.359 ms/op
     p(99.9900) =     26.769 ms/op
     p(99.9990) =     28.702 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 7.457 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.171 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.120 ±(99.9%) 0.019 ms/op
Iteration   1: 5.012 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   4.792 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.234 ms/op
                 getUser·p0.99:   9.601 ms/op
                 getUser·p0.999:  13.943 ms/op
                 getUser·p0.9999: 15.612 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   2: 4.879 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   4.669 ms/op
                 getUser·p0.90:   6.431 ms/op
                 getUser·p0.95:   7.143 ms/op
                 getUser·p0.99:   9.151 ms/op
                 getUser·p0.999:  16.036 ms/op
                 getUser·p0.9999: 19.478 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   3: 5.023 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   6.644 ms/op
                 getUser·p0.95:   7.422 ms/op
                 getUser·p0.99:   9.404 ms/op
                 getUser·p0.999:  20.972 ms/op
                 getUser·p0.9999: 23.253 ms/op
                 getUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 193108
  mean =      4.971 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2861 
    [ 2.500,  5.000) = 109821 
    [ 5.000,  7.500) = 72506 
    [ 7.500, 10.000) = 6598 
    [10.000, 12.500) = 912 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.274 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     22.075 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 9.747 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 7.204 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.469 ±(99.9%) 0.030 ms/op
Iteration   1: 6.423 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.036 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   8.798 ms/op
                 listUser·p0.95:   9.945 ms/op
                 listUser·p0.99:   12.648 ms/op
                 listUser·p0.999:  18.266 ms/op
                 listUser·p0.9999: 24.052 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 6.810 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   6.242 ms/op
                 listUser·p0.90:   9.699 ms/op
                 listUser·p0.95:   11.092 ms/op
                 listUser·p0.99:   14.483 ms/op
                 listUser·p0.999:  21.497 ms/op
                 listUser·p0.9999: 31.389 ms/op
                 listUser·p1.00:   31.916 ms/op

Iteration   3: 6.323 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   8.913 ms/op
                 listUser·p0.95:   10.156 ms/op
                 listUser·p0.99:   13.140 ms/op
                 listUser·p0.999:  20.447 ms/op
                 listUser·p0.9999: 43.057 ms/op
                 listUser·p1.00:   43.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 147398
  mean =      6.512 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 29550 
    [ 5.000, 10.000) = 108617 
    [10.000, 15.000) = 8495 
    [15.000, 20.000) = 580 
    [20.000, 25.000) = 90 
    [25.000, 30.000) = 22 
    [30.000, 35.000) = 12 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      6.005 ms/op
     p(90.0000) =      9.142 ms/op
     p(95.0000) =     10.420 ms/op
     p(99.0000) =     13.484 ms/op
     p(99.9000) =     20.205 ms/op
     p(99.9900) =     39.836 ms/op
     p(99.9990) =     43.488 ms/op
     p(99.9999) =     43.581 ms/op
    p(100.0000) =     43.581 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.445 ± 1.493  ops/ms
ClientGrpc.existUser                       thrpt       3   6.803 ± 1.190  ops/ms
ClientGrpc.getUser                         thrpt       3   6.293 ± 1.110  ops/ms
ClientGrpc.listUser                        thrpt       3   4.979 ± 1.992  ops/ms
ClientGrpc.createUser                       avgt       3   4.915 ± 1.908   ms/op
ClientGrpc.existUser                        avgt       3   4.703 ± 1.133   ms/op
ClientGrpc.getUser                          avgt       3   5.016 ± 1.767   ms/op
ClientGrpc.listUser                         avgt       3   6.125 ± 0.807   ms/op
ClientGrpc.createUser                     sample  195145   4.918 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.923           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.382           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.152           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.470           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          18.313           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.819           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.000           ms/op
ClientGrpc.existUser                      sample  203581   4.713 ± 0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.102           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.226           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.930           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.077           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.359           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.769           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.229           ms/op
ClientGrpc.getUser                        sample  193108   4.971 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.075           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.537           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.274           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.372           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.696           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.075           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.396           ms/op
ClientGrpc.listUser                       sample  147398   6.512 ± 0.018   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.311           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           6.005           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           9.142           ms/op
ClientGrpc.listUser:listUser·p0.95        sample          10.420           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          13.484           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.205           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          39.836           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          43.581           ms/op
