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
# Warmup Iteration   1: 2.998 ops/ms
# Warmup Iteration   2: 6.740 ops/ms
# Warmup Iteration   3: 8.085 ops/ms
Iteration   1: 8.288 ops/ms
Iteration   2: 8.224 ops/ms
Iteration   3: 8.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.366 ±(99.9%) 3.520 ops/ms [Average]
  (min, avg, max) = (8.224, 8.366, 8.586), stdev = 0.193
  CI (99.9%): [4.846, 11.886] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 6.502 ops/ms
# Warmup Iteration   2: 8.670 ops/ms
# Warmup Iteration   3: 9.150 ops/ms
Iteration   1: 9.303 ops/ms
Iteration   2: 9.104 ops/ms
Iteration   3: 9.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.213 ±(99.9%) 1.841 ops/ms [Average]
  (min, avg, max) = (9.104, 9.213, 9.303), stdev = 0.101
  CI (99.9%): [7.372, 11.053] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.311 ops/ms
# Warmup Iteration   2: 8.019 ops/ms
# Warmup Iteration   3: 8.247 ops/ms
Iteration   1: 8.636 ops/ms
Iteration   2: 8.400 ops/ms
Iteration   3: 8.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.431 ±(99.9%) 3.493 ops/ms [Average]
  (min, avg, max) = (8.257, 8.431, 8.636), stdev = 0.191
  CI (99.9%): [4.937, 11.924] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.866 ops/ms
# Warmup Iteration   2: 5.935 ops/ms
# Warmup Iteration   3: 6.750 ops/ms
Iteration   1: 6.915 ops/ms
Iteration   2: 7.114 ops/ms
Iteration   3: 6.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.951 ±(99.9%) 2.694 ops/ms [Average]
  (min, avg, max) = (6.825, 6.951, 7.114), stdev = 0.148
  CI (99.9%): [4.258, 9.645] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.070 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.006 ms/op
Iteration   1: 3.831 ±(99.9%) 0.027 ms/op
Iteration   2: 3.643 ±(99.9%) 0.001 ms/op
Iteration   3: 3.670 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.715 ±(99.9%) 1.846 ms/op [Average]
  (min, avg, max) = (3.643, 3.715, 3.831), stdev = 0.101
  CI (99.9%): [1.868, 5.561] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.915 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.002 ms/op
Iteration   1: 3.625 ±(99.9%) 0.003 ms/op
Iteration   2: 3.564 ±(99.9%) 0.002 ms/op
Iteration   3: 3.433 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.541 ±(99.9%) 1.785 ms/op [Average]
  (min, avg, max) = (3.433, 3.541, 3.625), stdev = 0.098
  CI (99.9%): [1.756, 5.325] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.529 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.011 ms/op
Iteration   1: 3.628 ±(99.9%) 0.003 ms/op
Iteration   2: 3.776 ±(99.9%) 0.004 ms/op
Iteration   3: 3.730 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.711 ±(99.9%) 1.384 ms/op [Average]
  (min, avg, max) = (3.628, 3.711, 3.776), stdev = 0.076
  CI (99.9%): [2.327, 5.096] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.933 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 5.361 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.977 ±(99.9%) 0.030 ms/op
Iteration   1: 4.966 ±(99.9%) 0.019 ms/op
Iteration   2: 4.861 ±(99.9%) 0.013 ms/op
Iteration   3: 4.700 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.842 ±(99.9%) 2.442 ms/op [Average]
  (min, avg, max) = (4.700, 4.842, 4.966), stdev = 0.134
  CI (99.9%): [2.400, 7.285] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.849 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.011 ms/op
Iteration   1: 3.781 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.274 ms/op
                 createUser·p0.999:  10.256 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   20.054 ms/op

Iteration   2: 3.751 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 21.413 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   3: 3.784 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  10.984 ms/op
                 createUser·p0.9999: 25.856 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254547
  mean =      3.772 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6514 
    [ 2.500,  5.000) = 239184 
    [ 5.000,  7.500) = 7897 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     10.288 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     26.375 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.015 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.008 ms/op
Iteration   1: 3.590 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 15.054 ms/op
                 existUser·p1.00:   15.499 ms/op

Iteration   2: 3.619 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  11.468 ms/op
                 existUser·p0.9999: 15.917 ms/op
                 existUser·p1.00:   16.450 ms/op

Iteration   3: 3.700 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  8.733 ms/op
                 existUser·p0.9999: 18.984 ms/op
                 existUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264051
  mean =      3.636 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 215 
    [ 1.250,  2.500) = 6471 
    [ 2.500,  3.750) = 159601 
    [ 3.750,  5.000) = 91520 
    [ 5.000,  6.250) = 4470 
    [ 6.250,  7.500) = 1042 
    [ 7.500,  8.750) = 368 
    [ 8.750, 10.000) = 149 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      9.584 ms/op
     p(99.9900) =     16.666 ms/op
     p(99.9990) =     19.258 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.464 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.009 ms/op
Iteration   1: 3.834 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.486 ms/op
                 getUser·p0.999:  10.013 ms/op
                 getUser·p0.9999: 12.555 ms/op
                 getUser·p1.00:   12.960 ms/op

Iteration   2: 3.790 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  10.380 ms/op
                 getUser·p0.9999: 18.943 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   3: 3.792 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  9.235 ms/op
                 getUser·p0.9999: 19.431 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252204
  mean =      3.805 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5283 
    [ 2.500,  5.000) = 237361 
    [ 5.000,  7.500) = 8573 
    [ 7.500, 10.000) = 748 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =      9.925 ms/op
     p(99.9900) =     19.195 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 6.471 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.096 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.752 ±(99.9%) 0.014 ms/op
Iteration   1: 4.740 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   6.390 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  15.197 ms/op
                 listUser·p0.9999: 17.244 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   2: 4.781 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   6.816 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  16.237 ms/op
                 listUser·p0.9999: 19.516 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 4.746 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   6.447 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  21.254 ms/op
                 listUser·p0.9999: 24.478 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201863
  mean =      4.755 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 193 
    [ 2.500,  5.000) = 154446 
    [ 5.000,  7.500) = 42624 
    [ 7.500, 10.000) = 3874 
    [10.000, 12.500) = 352 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.521 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     16.175 ms/op
     p(99.9900) =     23.489 ms/op
     p(99.9990) =     26.114 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.366 ± 3.520  ops/ms
ClientGrpc.existUser                       thrpt       3   9.213 ± 1.841  ops/ms
ClientGrpc.getUser                         thrpt       3   8.431 ± 3.493  ops/ms
ClientGrpc.listUser                        thrpt       3   6.951 ± 2.694  ops/ms
ClientGrpc.createUser                       avgt       3   3.715 ± 1.846   ms/op
ClientGrpc.existUser                        avgt       3   3.541 ± 1.785   ms/op
ClientGrpc.getUser                          avgt       3   3.711 ± 1.384   ms/op
ClientGrpc.listUser                         avgt       3   4.842 ± 2.442   ms/op
ClientGrpc.createUser                     sample  254547   3.772 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.895           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.103           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.288           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.707           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.525           ms/op
ClientGrpc.existUser                      sample  264051   3.636 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.864           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.734           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.584           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.666           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.333           ms/op
ClientGrpc.getUser                        sample  252204   3.805 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.971           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.226           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.925           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.195           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.135           ms/op
ClientGrpc.listUser                       sample  201863   4.755 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.094           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.389           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.175           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.489           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
