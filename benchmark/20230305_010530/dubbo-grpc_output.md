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
# Warmup Iteration   1: 3.562 ops/ms
# Warmup Iteration   2: 8.744 ops/ms
# Warmup Iteration   3: 10.026 ops/ms
Iteration   1: 10.263 ops/ms
Iteration   2: 10.266 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.379 ±(99.9%) 3.624 ops/ms [Average]
  (min, avg, max) = (10.263, 10.379, 10.608), stdev = 0.199
  CI (99.9%): [6.754, 14.003] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 6.365 ops/ms
# Warmup Iteration   2: 10.019 ops/ms
# Warmup Iteration   3: 10.378 ops/ms
Iteration   1: 10.141 ops/ms
Iteration   2: 10.509 ops/ms
Iteration   3: 10.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.313 ±(99.9%) 3.378 ops/ms [Average]
  (min, avg, max) = (10.141, 10.313, 10.509), stdev = 0.185
  CI (99.9%): [6.934, 13.691] (assumes normal distribution)


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
# Warmup Iteration   1: 5.861 ops/ms
# Warmup Iteration   2: 9.841 ops/ms
# Warmup Iteration   3: 10.013 ops/ms
Iteration   1: 10.170 ops/ms
Iteration   2: 10.045 ops/ms
Iteration   3: 10.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.131 ±(99.9%) 1.365 ops/ms [Average]
  (min, avg, max) = (10.045, 10.131, 10.179), stdev = 0.075
  CI (99.9%): [8.766, 11.497] (assumes normal distribution)


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
# Warmup Iteration   1: 4.746 ops/ms
# Warmup Iteration   2: 7.500 ops/ms
# Warmup Iteration   3: 7.709 ops/ms
Iteration   1: 7.767 ops/ms
Iteration   2: 7.912 ops/ms
Iteration   3: 7.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.846 ±(99.9%) 1.349 ops/ms [Average]
  (min, avg, max) = (7.767, 7.846, 7.912), stdev = 0.074
  CI (99.9%): [6.498, 9.195] (assumes normal distribution)


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.343 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.004 ms/op
Iteration   1: 3.185 ±(99.9%) 0.006 ms/op
Iteration   2: 3.193 ±(99.9%) 0.001 ms/op
Iteration   3: 3.144 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.174 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (3.144, 3.174, 3.193), stdev = 0.026
  CI (99.9%): [2.693, 3.655] (assumes normal distribution)


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.003 ms/op
Iteration   1: 3.078 ±(99.9%) 0.002 ms/op
Iteration   2: 3.104 ±(99.9%) 0.002 ms/op
Iteration   3: 3.061 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.081 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (3.061, 3.081, 3.104), stdev = 0.022
  CI (99.9%): [2.686, 3.476] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.709 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.447 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.003 ms/op
Iteration   1: 3.130 ±(99.9%) 0.003 ms/op
Iteration   2: 3.159 ±(99.9%) 0.001 ms/op
Iteration   3: 3.162 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.150 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.130, 3.150, 3.162), stdev = 0.018
  CI (99.9%): [2.823, 3.478] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.033 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.544 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.015 ms/op
Iteration   1: 4.008 ±(99.9%) 0.015 ms/op
Iteration   2: 4.034 ±(99.9%) 0.008 ms/op
Iteration   3: 3.960 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.001 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (3.960, 4.001, 4.034), stdev = 0.038
  CI (99.9%): [3.315, 4.686] (assumes normal distribution)


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.006 ms/op
Iteration   1: 3.147 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.930 ms/op
                 createUser·p0.9999: 13.088 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   2: 3.239 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.538 ms/op
                 createUser·p0.9999: 15.800 ms/op
                 createUser·p1.00:   16.187 ms/op

Iteration   3: 3.166 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  10.551 ms/op
                 createUser·p0.9999: 24.609 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301786
  mean =      3.183 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22566 
    [ 2.500,  5.000) = 278032 
    [ 5.000,  7.500) = 806 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.785 ms/op
     p(99.9900) =     24.142 ms/op
     p(99.9990) =     25.130 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.437 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
Iteration   1: 3.126 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  8.575 ms/op
                 existUser·p0.9999: 14.254 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 3.045 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.995 ms/op
                 existUser·p0.9999: 17.711 ms/op
                 existUser·p1.00:   17.760 ms/op

Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 18.485 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313520
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1264 
    [ 1.250,  2.500) = 33181 
    [ 2.500,  3.750) = 250977 
    [ 3.750,  5.000) = 27042 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 252 
    [ 7.500,  8.750) = 87 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     17.356 ms/op
     p(99.9990) =     18.870 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.007 ms/op
Iteration   1: 3.205 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  8.504 ms/op
                 getUser·p0.9999: 13.631 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   2: 3.152 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.124 ms/op
                 getUser·p0.9999: 16.406 ms/op
                 getUser·p1.00:   16.679 ms/op

Iteration   3: 3.199 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.938 ms/op
                 getUser·p0.9999: 18.219 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301674
  mean =      3.185 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 369 
    [ 1.250,  2.500) = 16092 
    [ 2.500,  3.750) = 245513 
    [ 3.750,  5.000) = 38468 
    [ 5.000,  6.250) = 520 
    [ 6.250,  7.500) = 313 
    [ 7.500,  8.750) = 164 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.979 ms/op
     p(99.9900) =     16.586 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 5.820 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.643 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.012 ms/op
Iteration   1: 4.073 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  14.933 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   2: 4.086 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 4.005 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  24.052 ms/op
                 listUser·p0.9999: 33.065 ms/op
                 listUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236812
  mean =      4.054 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2368 
    [ 2.500,  5.000) = 206582 
    [ 5.000,  7.500) = 26234 
    [ 7.500, 10.000) = 1096 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     15.732 ms/op
     p(99.9900) =     31.997 ms/op
     p(99.9990) =     33.375 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.379 ± 3.624  ops/ms
ClientGrpc.existUser                       thrpt       3  10.313 ± 3.378  ops/ms
ClientGrpc.getUser                         thrpt       3  10.131 ± 1.365  ops/ms
ClientGrpc.listUser                        thrpt       3   7.846 ± 1.349  ops/ms
ClientGrpc.createUser                       avgt       3   3.174 ± 0.481   ms/op
ClientGrpc.existUser                        avgt       3   3.081 ± 0.395   ms/op
ClientGrpc.getUser                          avgt       3   3.150 ± 0.328   ms/op
ClientGrpc.listUser                         avgt       3   4.001 ± 0.685   ms/op
ClientGrpc.createUser                     sample  301786   3.183 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.593           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.150           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.047           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.785           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.142           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.166           ms/op
ClientGrpc.existUser                      sample  313520   3.059 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.637           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.039           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.503           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.356           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.973           ms/op
ClientGrpc.getUser                        sample  301674   3.185 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.706           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.150           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.026           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.979           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.586           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.317           ms/op
ClientGrpc.listUser                       sample  236812   4.054 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.920           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.732           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.997           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.489           ms/op
