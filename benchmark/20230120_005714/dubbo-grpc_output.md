# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.448 ops/ms
# Warmup Iteration   2: 7.416 ops/ms
# Warmup Iteration   3: 8.519 ops/ms
Iteration   1: 8.900 ops/ms
Iteration   2: 8.855 ops/ms
Iteration   3: 9.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.943 ±(99.9%) 2.095 ops/ms [Average]
  (min, avg, max) = (8.855, 8.943, 9.072), stdev = 0.115
  CI (99.9%): [6.848, 11.037] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.547 ops/ms
# Warmup Iteration   2: 8.662 ops/ms
# Warmup Iteration   3: 9.193 ops/ms
Iteration   1: 8.927 ops/ms
Iteration   2: 8.860 ops/ms
Iteration   3: 9.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.004 ±(99.9%) 3.556 ops/ms [Average]
  (min, avg, max) = (8.860, 9.004, 9.226), stdev = 0.195
  CI (99.9%): [5.448, 12.560] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.888 ops/ms
# Warmup Iteration   2: 8.361 ops/ms
# Warmup Iteration   3: 8.580 ops/ms
Iteration   1: 8.637 ops/ms
Iteration   2: 8.649 ops/ms
Iteration   3: 8.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.600 ±(99.9%) 1.354 ops/ms [Average]
  (min, avg, max) = (8.515, 8.600, 8.649), stdev = 0.074
  CI (99.9%): [7.246, 9.954] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.922 ops/ms
# Warmup Iteration   2: 6.196 ops/ms
# Warmup Iteration   3: 6.821 ops/ms
Iteration   1: 6.631 ops/ms
Iteration   2: 6.791 ops/ms
Iteration   3: 6.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.740 ±(99.9%) 1.725 ops/ms [Average]
  (min, avg, max) = (6.631, 6.740, 6.798), stdev = 0.095
  CI (99.9%): [5.015, 8.465] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.553 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.004 ms/op
Iteration   1: 3.688 ±(99.9%) 0.006 ms/op
Iteration   2: 3.587 ±(99.9%) 0.003 ms/op
Iteration   3: 3.799 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.691 ±(99.9%) 1.940 ms/op [Average]
  (min, avg, max) = (3.587, 3.691, 3.799), stdev = 0.106
  CI (99.9%): [1.751, 5.632] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.765 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.003 ms/op
Iteration   1: 3.712 ±(99.9%) 0.002 ms/op
Iteration   2: 3.699 ±(99.9%) 0.002 ms/op
Iteration   3: 3.654 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.688 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.654, 3.688, 3.712), stdev = 0.030
  CI (99.9%): [3.134, 4.242] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.036 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.004 ms/op
Iteration   1: 3.625 ±(99.9%) 0.003 ms/op
Iteration   2: 3.599 ±(99.9%) 0.004 ms/op
Iteration   3: 3.666 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.630 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (3.599, 3.630, 3.666), stdev = 0.034
  CI (99.9%): [3.015, 4.245] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.081 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.003 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.750 ±(99.9%) 0.007 ms/op
Iteration   1: 4.694 ±(99.9%) 0.010 ms/op
Iteration   2: 4.642 ±(99.9%) 0.027 ms/op
Iteration   3: 4.769 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.702 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (4.642, 4.702, 4.769), stdev = 0.064
  CI (99.9%): [3.536, 5.867] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.144 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.010 ms/op
Iteration   1: 3.666 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  11.578 ms/op
                 createUser·p0.9999: 16.967 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   2: 3.575 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  7.905 ms/op
                 createUser·p0.9999: 15.879 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   3: 3.693 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.706 ms/op
                 createUser·p0.99:   5.771 ms/op
                 createUser·p0.999:  10.338 ms/op
                 createUser·p0.9999: 26.749 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263565
  mean =      3.644 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7840 
    [ 2.500,  5.000) = 249173 
    [ 5.000,  7.500) = 5702 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     10.526 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     27.069 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.510 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.008 ms/op
Iteration   1: 3.558 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  11.404 ms/op
                 existUser·p0.9999: 15.024 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   2: 3.674 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  10.595 ms/op
                 existUser·p0.9999: 17.779 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   3: 3.600 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  10.912 ms/op
                 existUser·p0.9999: 28.115 ms/op
                 existUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266016
  mean =      3.610 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11152 
    [ 2.500,  5.000) = 246863 
    [ 5.000,  7.500) = 6971 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     10.797 ms/op
     p(99.9900) =     27.243 ms/op
     p(99.9990) =     28.370 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.296 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.008 ms/op
Iteration   1: 3.608 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 19.370 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   2: 3.586 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  7.994 ms/op
                 getUser·p0.9999: 20.977 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   3: 3.724 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   5.973 ms/op
                 getUser·p0.999:  10.105 ms/op
                 getUser·p0.9999: 21.672 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263856
  mean =      3.639 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9431 
    [ 2.500,  5.000) = 247538 
    [ 5.000,  7.500) = 6179 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.014 ms/op
     p(99.9900) =     21.188 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.482 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.981 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.712 ±(99.9%) 0.014 ms/op
Iteration   1: 4.682 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  14.380 ms/op
                 listUser·p0.9999: 16.507 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   2: 4.818 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  19.471 ms/op
                 listUser·p0.9999: 30.224 ms/op
                 listUser·p1.00:   30.507 ms/op

Iteration   3: 4.811 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.406 ms/op
                 listUser·p0.95:   7.119 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  20.228 ms/op
                 listUser·p0.9999: 34.888 ms/op
                 listUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201270
  mean =      4.770 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 454 
    [ 2.500,  5.000) = 146420 
    [ 5.000,  7.500) = 48856 
    [ 7.500, 10.000) = 4622 
    [10.000, 12.500) = 509 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      6.152 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     16.371 ms/op
     p(99.9900) =     33.509 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.943 ± 2.095  ops/ms
ClientGrpc.existUser                       thrpt       3   9.004 ± 3.556  ops/ms
ClientGrpc.getUser                         thrpt       3   8.600 ± 1.354  ops/ms
ClientGrpc.listUser                        thrpt       3   6.740 ± 1.725  ops/ms
ClientGrpc.createUser                       avgt       3   3.691 ± 1.940   ms/op
ClientGrpc.existUser                        avgt       3   3.688 ± 0.554   ms/op
ClientGrpc.getUser                          avgt       3   3.630 ± 0.615   ms/op
ClientGrpc.listUser                         avgt       3   4.702 ± 1.165   ms/op
ClientGrpc.createUser                     sample  263565   3.644 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.798           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.526           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.247           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.197           ms/op
ClientGrpc.existUser                      sample  266016   3.610 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.772           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.735           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.038           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.797           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.243           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.770           ms/op
ClientGrpc.getUser                        sample  263856   3.639 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.867           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.014           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.188           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.839           ms/op
ClientGrpc.listUser                       sample  201270   4.770 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.963           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.152           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.700           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.371           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.509           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.127           ms/op
