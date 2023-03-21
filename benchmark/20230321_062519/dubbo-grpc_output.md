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
# Warmup Iteration   1: 3.009 ops/ms
# Warmup Iteration   2: 6.636 ops/ms
# Warmup Iteration   3: 8.019 ops/ms
Iteration   1: 8.586 ops/ms
Iteration   2: 8.773 ops/ms
Iteration   3: 8.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.690 ±(99.9%) 1.730 ops/ms [Average]
  (min, avg, max) = (8.586, 8.690, 8.773), stdev = 0.095
  CI (99.9%): [6.960, 10.420] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.796 ops/ms
# Warmup Iteration   2: 8.508 ops/ms
# Warmup Iteration   3: 9.067 ops/ms
Iteration   1: 9.160 ops/ms
Iteration   2: 9.147 ops/ms
Iteration   3: 8.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.094 ±(99.9%) 1.880 ops/ms [Average]
  (min, avg, max) = (8.975, 9.094, 9.160), stdev = 0.103
  CI (99.9%): [7.214, 10.974] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.351 ops/ms
# Warmup Iteration   2: 8.133 ops/ms
# Warmup Iteration   3: 8.750 ops/ms
Iteration   1: 8.690 ops/ms
Iteration   2: 8.597 ops/ms
Iteration   3: 8.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.697 ±(99.9%) 1.902 ops/ms [Average]
  (min, avg, max) = (8.597, 8.697, 8.805), stdev = 0.104
  CI (99.9%): [6.795, 10.599] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.694 ops/ms
# Warmup Iteration   2: 6.097 ops/ms
# Warmup Iteration   3: 6.688 ops/ms
Iteration   1: 6.808 ops/ms
Iteration   2: 6.838 ops/ms
Iteration   3: 6.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.858 ±(99.9%) 1.123 ops/ms [Average]
  (min, avg, max) = (6.808, 6.858, 6.927), stdev = 0.062
  CI (99.9%): [5.735, 7.981] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.747 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.004 ms/op
Iteration   1: 3.834 ±(99.9%) 0.002 ms/op
Iteration   2: 3.696 ±(99.9%) 0.004 ms/op
Iteration   3: 3.632 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.721 ±(99.9%) 1.885 ms/op [Average]
  (min, avg, max) = (3.632, 3.721, 3.834), stdev = 0.103
  CI (99.9%): [1.836, 5.606] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.187 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.004 ms/op
Iteration   1: 3.803 ±(99.9%) 0.004 ms/op
Iteration   2: 3.865 ±(99.9%) 0.003 ms/op
Iteration   3: 4.090 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.919 ±(99.9%) 2.754 ms/op [Average]
  (min, avg, max) = (3.803, 3.919, 4.090), stdev = 0.151
  CI (99.9%): [1.165, 6.673] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.903 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.333 ±(99.9%) 0.005 ms/op
Iteration   1: 4.244 ±(99.9%) 0.003 ms/op
Iteration   2: 3.692 ±(99.9%) 0.004 ms/op
Iteration   3: 4.172 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.036 ±(99.9%) 5.478 ms/op [Average]
  (min, avg, max) = (3.692, 4.036, 4.244), stdev = 0.300
  CI (99.9%): [≈ 0, 9.514] (assumes normal distribution)


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
# Warmup Iteration   1: 5.966 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.638 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.417 ±(99.9%) 0.013 ms/op
Iteration   1: 5.433 ±(99.9%) 0.014 ms/op
Iteration   2: 5.286 ±(99.9%) 0.030 ms/op
Iteration   3: 5.335 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.351 ±(99.9%) 1.369 ms/op [Average]
  (min, avg, max) = (5.286, 5.351, 5.433), stdev = 0.075
  CI (99.9%): [3.982, 6.721] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.023 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.581 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.013 ms/op
Iteration   1: 3.586 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.720 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 15.370 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   2: 3.999 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   5.022 ms/op
                 createUser·p0.95:   5.767 ms/op
                 createUser·p0.99:   8.348 ms/op
                 createUser·p0.999:  12.813 ms/op
                 createUser·p0.9999: 18.219 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   3: 3.927 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   5.022 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   7.274 ms/op
                 createUser·p0.999:  13.177 ms/op
                 createUser·p0.9999: 20.938 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250675
  mean =      3.829 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9759 
    [ 2.500,  5.000) = 221830 
    [ 5.000,  7.500) = 16741 
    [ 7.500, 10.000) = 1768 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     12.157 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 4.951 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.007 ms/op
Iteration   1: 3.841 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.733 ms/op
                 existUser·p0.999:  14.157 ms/op
                 existUser·p0.9999: 24.499 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   2: 3.816 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.776 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   7.201 ms/op
                 existUser·p0.999:  11.567 ms/op
                 existUser·p0.9999: 17.977 ms/op
                 existUser·p1.00:   18.481 ms/op

Iteration   3: 3.441 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  13.385 ms/op
                 existUser·p0.9999: 24.248 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 260312
  mean =      3.690 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11469 
    [ 2.500,  5.000) = 232854 
    [ 5.000,  7.500) = 13897 
    [ 7.500, 10.000) = 1575 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     12.594 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     24.700 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 5.323 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.014 ms/op
Iteration   1: 4.036 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   7.974 ms/op
                 getUser·p0.999:  10.906 ms/op
                 getUser·p0.9999: 19.040 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   2: 4.260 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   6.300 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  16.333 ms/op
                 getUser·p0.9999: 32.424 ms/op
                 getUser·p1.00:   35.062 ms/op

Iteration   3: 3.631 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  8.585 ms/op
                 getUser·p0.9999: 20.421 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 242559
  mean =      3.958 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9217 
    [ 2.500,  5.000) = 208802 
    [ 5.000,  7.500) = 21612 
    [ 7.500, 10.000) = 2386 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     11.853 ms/op
     p(99.9900) =     31.711 ms/op
     p(99.9990) =     33.082 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 6.491 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.906 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.216 ±(99.9%) 0.021 ms/op
Iteration   1: 5.331 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   4.932 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.208 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  19.825 ms/op
                 listUser·p0.9999: 21.465 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 5.167 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.938 ms/op
                 listUser·p0.99:   10.699 ms/op
                 listUser·p0.999:  20.097 ms/op
                 listUser·p0.9999: 22.768 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 4.812 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.341 ms/op
                 listUser·p0.95:   7.242 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  20.400 ms/op
                 listUser·p0.9999: 33.194 ms/op
                 listUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188330
  mean =      5.094 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 400 
    [ 2.500,  5.000) = 116390 
    [ 5.000,  7.500) = 59684 
    [ 7.500, 10.000) = 9400 
    [10.000, 12.500) = 1661 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.840 ms/op
     p(95.0000) =      7.815 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     32.806 ms/op
     p(99.9990) =     34.603 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.690 ± 1.730  ops/ms
ClientGrpc.existUser                       thrpt       3   9.094 ± 1.880  ops/ms
ClientGrpc.getUser                         thrpt       3   8.697 ± 1.902  ops/ms
ClientGrpc.listUser                        thrpt       3   6.858 ± 1.123  ops/ms
ClientGrpc.createUser                       avgt       3   3.721 ± 1.885   ms/op
ClientGrpc.existUser                        avgt       3   3.919 ± 2.754   ms/op
ClientGrpc.getUser                          avgt       3   4.036 ± 5.478   ms/op
ClientGrpc.listUser                         avgt       3   5.351 ± 1.369   ms/op
ClientGrpc.createUser                     sample  250675   3.829 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.658           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.792           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.349           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.389           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.157           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.202           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.889           ms/op
ClientGrpc.existUser                      sample  260312   3.690 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.734           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.186           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.160           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.594           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.248           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.133           ms/op
ClientGrpc.getUser                        sample  242559   3.958 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.895           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.014           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.799           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.853           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.711           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.062           ms/op
ClientGrpc.listUser                       sample  188330   5.094 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.159           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.815           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.469           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.956           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.806           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.603           ms/op
