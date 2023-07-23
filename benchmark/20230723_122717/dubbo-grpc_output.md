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
# Warmup Iteration   1: 3.260 ops/ms
# Warmup Iteration   2: 6.491 ops/ms
# Warmup Iteration   3: 7.222 ops/ms
Iteration   1: 8.338 ops/ms
Iteration   2: 8.333 ops/ms
Iteration   3: 8.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.364 ±(99.9%) 0.893 ops/ms [Average]
  (min, avg, max) = (8.333, 8.364, 8.420), stdev = 0.049
  CI (99.9%): [7.470, 9.257] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.026 ops/ms
# Warmup Iteration   2: 8.513 ops/ms
# Warmup Iteration   3: 8.640 ops/ms
Iteration   1: 8.616 ops/ms
Iteration   2: 8.816 ops/ms
Iteration   3: 8.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.783 ±(99.9%) 2.786 ops/ms [Average]
  (min, avg, max) = (8.616, 8.783, 8.916), stdev = 0.153
  CI (99.9%): [5.997, 11.569] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.614 ops/ms
# Warmup Iteration   2: 7.878 ops/ms
# Warmup Iteration   3: 8.047 ops/ms
Iteration   1: 8.511 ops/ms
Iteration   2: 8.453 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.441 ±(99.9%) 1.403 ops/ms [Average]
  (min, avg, max) = (8.358, 8.441, 8.511), stdev = 0.077
  CI (99.9%): [7.037, 9.844] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.759 ops/ms
# Warmup Iteration   2: 5.964 ops/ms
# Warmup Iteration   3: 6.162 ops/ms
Iteration   1: 6.245 ops/ms
Iteration   2: 6.509 ops/ms
Iteration   3: 6.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.440 ±(99.9%) 3.122 ops/ms [Average]
  (min, avg, max) = (6.245, 6.440, 6.566), stdev = 0.171
  CI (99.9%): [3.318, 9.563] (assumes normal distribution)


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
# Warmup Iteration   1: 5.242 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.004 ms/op
Iteration   1: 3.841 ±(99.9%) 0.004 ms/op
Iteration   2: 3.709 ±(99.9%) 0.003 ms/op
Iteration   3: 3.688 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.746 ±(99.9%) 1.511 ms/op [Average]
  (min, avg, max) = (3.688, 3.746, 3.841), stdev = 0.083
  CI (99.9%): [2.235, 5.256] (assumes normal distribution)


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
# Warmup Iteration   1: 5.361 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.004 ms/op
Iteration   1: 3.509 ±(99.9%) 0.003 ms/op
Iteration   2: 3.572 ±(99.9%) 0.003 ms/op
Iteration   3: 3.707 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.596 ±(99.9%) 1.844 ms/op [Average]
  (min, avg, max) = (3.509, 3.596, 3.707), stdev = 0.101
  CI (99.9%): [1.752, 5.439] (assumes normal distribution)


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
# Warmup Iteration   1: 5.168 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.796 ±(99.9%) 0.005 ms/op
Iteration   1: 3.773 ±(99.9%) 0.005 ms/op
Iteration   2: 3.745 ±(99.9%) 0.005 ms/op
Iteration   3: 3.721 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.746 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (3.721, 3.746, 3.773), stdev = 0.026
  CI (99.9%): [3.269, 4.223] (assumes normal distribution)


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
# Warmup Iteration   1: 6.571 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.383 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.016 ±(99.9%) 0.020 ms/op
Iteration   1: 5.155 ±(99.9%) 0.024 ms/op
Iteration   2: 4.970 ±(99.9%) 0.015 ms/op
Iteration   3: 4.972 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.032 ±(99.9%) 1.937 ms/op [Average]
  (min, avg, max) = (4.970, 5.032, 5.155), stdev = 0.106
  CI (99.9%): [3.095, 6.969] (assumes normal distribution)


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
# Warmup Iteration   1: 5.029 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.011 ms/op
Iteration   1: 3.970 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.889 ms/op
                 createUser·p0.999:  13.861 ms/op
                 createUser·p0.9999: 15.254 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   2: 3.810 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  11.171 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   3: 3.820 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  12.587 ms/op
                 createUser·p0.9999: 22.204 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 248471
  mean =      3.865 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10390 
    [ 2.500,  5.000) = 219227 
    [ 5.000,  7.500) = 16601 
    [ 7.500, 10.000) = 1634 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.312 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     12.026 ms/op
     p(99.9900) =     21.599 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 5.083 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.830 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.010 ms/op
Iteration   1: 3.585 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  9.759 ms/op
                 existUser·p0.9999: 14.931 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   2: 3.676 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  12.239 ms/op
                 existUser·p0.9999: 32.843 ms/op
                 existUser·p1.00:   33.292 ms/op

Iteration   3: 3.788 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   7.947 ms/op
                 existUser·p0.999:  12.921 ms/op
                 existUser·p0.9999: 23.549 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 260616
  mean =      3.681 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17486 
    [ 2.500,  5.000) = 229546 
    [ 5.000,  7.500) = 11493 
    [ 7.500, 10.000) = 1583 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     12.120 ms/op
     p(99.9900) =     31.916 ms/op
     p(99.9990) =     33.134 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 5.339 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.011 ms/op
Iteration   1: 3.834 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   6.989 ms/op
                 getUser·p0.999:  13.127 ms/op
                 getUser·p0.9999: 18.110 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   2: 3.721 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   7.289 ms/op
                 getUser·p0.999:  11.471 ms/op
                 getUser·p0.9999: 18.678 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   3: 3.892 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   7.219 ms/op
                 getUser·p0.999:  10.139 ms/op
                 getUser·p0.9999: 20.473 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251493
  mean =      3.815 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9556 
    [ 2.500,  5.000) = 227209 
    [ 5.000,  7.500) = 12667 
    [ 7.500, 10.000) = 1648 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     18.706 ms/op
     p(99.9990) =     20.708 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 6.341 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.411 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.005 ±(99.9%) 0.018 ms/op
Iteration   1: 5.185 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   7.004 ms/op
                 listUser·p0.95:   7.979 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  16.745 ms/op
                 listUser·p0.9999: 20.114 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   2: 5.101 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.906 ms/op
                 listUser·p0.95:   7.873 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  20.088 ms/op
                 listUser·p0.9999: 39.715 ms/op
                 listUser·p1.00:   40.108 ms/op

Iteration   3: 5.240 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   6.955 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   10.366 ms/op
                 listUser·p0.999:  25.853 ms/op
                 listUser·p0.9999: 39.059 ms/op
                 listUser·p1.00:   39.977 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 185399
  mean =      5.175 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 108149 
    [ 5.000, 10.000) = 74703 
    [10.000, 15.000) = 2134 
    [15.000, 20.000) = 229 
    [20.000, 25.000) = 83 
    [25.000, 30.000) = 47 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 50 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     19.975 ms/op
     p(99.9900) =     39.059 ms/op
     p(99.9990) =     39.996 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.364 ± 0.893  ops/ms
ClientGrpc.existUser                       thrpt       3   8.783 ± 2.786  ops/ms
ClientGrpc.getUser                         thrpt       3   8.441 ± 1.403  ops/ms
ClientGrpc.listUser                        thrpt       3   6.440 ± 3.122  ops/ms
ClientGrpc.createUser                       avgt       3   3.746 ± 1.511   ms/op
ClientGrpc.existUser                        avgt       3   3.596 ± 1.844   ms/op
ClientGrpc.getUser                          avgt       3   3.746 ± 0.477   ms/op
ClientGrpc.listUser                         avgt       3   5.032 ± 1.937   ms/op
ClientGrpc.createUser                     sample  248471   3.865 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.771           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.312           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.340           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.026           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.599           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.479           ms/op
ClientGrpc.existUser                      sample  260616   3.681 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.731           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.160           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.120           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.916           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.292           ms/op
ClientGrpc.getUser                        sample  251493   3.815 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.803           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.120           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.160           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.502           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.706           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  185399   5.175 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.939           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.913           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.633           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.975           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          39.059           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.108           ms/op
