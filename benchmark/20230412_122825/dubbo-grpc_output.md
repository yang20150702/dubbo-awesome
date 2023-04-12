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
# Warmup Iteration   1: 4.073 ops/ms
# Warmup Iteration   2: 8.836 ops/ms
# Warmup Iteration   3: 9.869 ops/ms
Iteration   1: 10.294 ops/ms
Iteration   2: 10.618 ops/ms
Iteration   3: 10.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.501 ±(99.9%) 3.279 ops/ms [Average]
  (min, avg, max) = (10.294, 10.501, 10.618), stdev = 0.180
  CI (99.9%): [7.222, 13.779] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.431 ops/ms
# Warmup Iteration   2: 10.404 ops/ms
# Warmup Iteration   3: 11.026 ops/ms
Iteration   1: 11.055 ops/ms
Iteration   2: 11.258 ops/ms
Iteration   3: 11.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.114 ±(99.9%) 2.289 ops/ms [Average]
  (min, avg, max) = (11.029, 11.114, 11.258), stdev = 0.125
  CI (99.9%): [8.825, 13.403] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.877 ops/ms
# Warmup Iteration   2: 9.909 ops/ms
# Warmup Iteration   3: 10.400 ops/ms
Iteration   1: 10.379 ops/ms
Iteration   2: 10.471 ops/ms
Iteration   3: 10.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.358 ±(99.9%) 2.279 ops/ms [Average]
  (min, avg, max) = (10.224, 10.358, 10.471), stdev = 0.125
  CI (99.9%): [8.080, 12.637] (assumes normal distribution)


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
# Warmup Iteration   1: 5.052 ops/ms
# Warmup Iteration   2: 7.486 ops/ms
# Warmup Iteration   3: 7.908 ops/ms
Iteration   1: 7.921 ops/ms
Iteration   2: 7.829 ops/ms
Iteration   3: 7.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.882 ±(99.9%) 0.870 ops/ms [Average]
  (min, avg, max) = (7.829, 7.882, 7.921), stdev = 0.048
  CI (99.9%): [7.012, 8.753] (assumes normal distribution)


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.004 ms/op
Iteration   1: 3.050 ±(99.9%) 0.004 ms/op
Iteration   2: 3.014 ±(99.9%) 0.004 ms/op
Iteration   3: 2.945 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.003 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (2.945, 3.003, 3.050), stdev = 0.053
  CI (99.9%): [2.029, 3.977] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.279 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.004 ms/op
Iteration   1: 2.889 ±(99.9%) 0.003 ms/op
Iteration   2: 2.906 ±(99.9%) 0.005 ms/op
Iteration   3: 2.956 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.917 ±(99.9%) 0.640 ms/op [Average]
  (min, avg, max) = (2.889, 2.917, 2.956), stdev = 0.035
  CI (99.9%): [2.277, 3.557] (assumes normal distribution)


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.003 ms/op
Iteration   1: 3.106 ±(99.9%) 0.003 ms/op
Iteration   2: 3.044 ±(99.9%) 0.001 ms/op
Iteration   3: 3.045 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.065 ±(99.9%) 0.645 ms/op [Average]
  (min, avg, max) = (3.044, 3.065, 3.106), stdev = 0.035
  CI (99.9%): [2.420, 3.710] (assumes normal distribution)


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
# Warmup Iteration   1: 5.375 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.013 ms/op
Iteration   1: 4.064 ±(99.9%) 0.015 ms/op
Iteration   2: 4.051 ±(99.9%) 0.031 ms/op
Iteration   3: 4.047 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.054 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (4.047, 4.054, 4.064), stdev = 0.009
  CI (99.9%): [3.893, 4.216] (assumes normal distribution)


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
Iteration   1: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  16.777 ms/op
                 createUser·p0.9999: 20.742 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  6.856 ms/op
                 createUser·p0.9999: 21.413 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   3: 3.070 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  9.236 ms/op
                 createUser·p0.9999: 23.153 ms/op
                 createUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314121
  mean =      3.057 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20174 
    [ 2.500,  5.000) = 292294 
    [ 5.000,  7.500) = 1264 
    [ 7.500, 10.000) = 100 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.616 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     23.485 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 2.964 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.436 ms/op
                 existUser·p0.999:  6.553 ms/op
                 existUser·p0.9999: 14.457 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.962 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.291 ms/op
                 existUser·p0.9999: 14.090 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   3: 2.946 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  5.918 ms/op
                 existUser·p0.9999: 16.431 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324704
  mean =      2.957 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 899 
    [ 1.250,  2.500) = 23697 
    [ 2.500,  3.750) = 291433 
    [ 3.750,  5.000) = 7841 
    [ 5.000,  6.250) = 504 
    [ 6.250,  7.500) = 168 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.277 ms/op
     p(99.9900) =     15.803 ms/op
     p(99.9990) =     17.343 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.006 ms/op
Iteration   1: 3.072 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.631 ms/op
                 getUser·p0.9999: 12.812 ms/op
                 getUser·p1.00:   13.009 ms/op

Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  6.955 ms/op
                 getUser·p0.9999: 17.072 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.158 ms/op
                 getUser·p0.9999: 17.650 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311242
  mean =      3.083 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 378 
    [ 1.250,  2.500) = 13620 
    [ 2.500,  3.750) = 280344 
    [ 3.750,  5.000) = 15194 
    [ 5.000,  6.250) = 1083 
    [ 6.250,  7.500) = 342 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.166 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     19.329 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 5.207 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.010 ms/op
Iteration   1: 4.047 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  12.009 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 4.065 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.799 ms/op
                 listUser·p0.9999: 18.752 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 4.061 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  18.750 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236548
  mean =      4.058 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1828 
    [ 2.500,  5.000) = 211742 
    [ 5.000,  7.500) = 21684 
    [ 7.500, 10.000) = 887 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.684 ms/op
     p(99.9900) =     21.212 ms/op
     p(99.9990) =     22.518 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.501 ± 3.279  ops/ms
ClientGrpc.existUser                       thrpt       3  11.114 ± 2.289  ops/ms
ClientGrpc.getUser                         thrpt       3  10.358 ± 2.279  ops/ms
ClientGrpc.listUser                        thrpt       3   7.882 ± 0.870  ops/ms
ClientGrpc.createUser                       avgt       3   3.003 ± 0.974   ms/op
ClientGrpc.existUser                        avgt       3   2.917 ± 0.640   ms/op
ClientGrpc.getUser                          avgt       3   3.065 ± 0.645   ms/op
ClientGrpc.listUser                         avgt       3   4.054 ± 0.161   ms/op
ClientGrpc.createUser                     sample  314121   3.057 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.659           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.616           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.315           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.593           ms/op
ClientGrpc.existUser                      sample  324704   2.957 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.668           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.277           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.803           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.760           ms/op
ClientGrpc.getUser                        sample  311242   3.083 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.727           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.166           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.908           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.497           ms/op
ClientGrpc.listUser                       sample  236548   4.058 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.157           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.684           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.212           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.265           ms/op
