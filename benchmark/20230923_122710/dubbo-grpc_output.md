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
# Warmup Iteration   1: 2.902 ops/ms
# Warmup Iteration   2: 6.355 ops/ms
# Warmup Iteration   3: 7.771 ops/ms
Iteration   1: 8.114 ops/ms
Iteration   2: 8.327 ops/ms
Iteration   3: 8.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.250 ±(99.9%) 2.153 ops/ms [Average]
  (min, avg, max) = (8.114, 8.250, 8.327), stdev = 0.118
  CI (99.9%): [6.097, 10.403] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.503 ops/ms
# Warmup Iteration   2: 8.006 ops/ms
# Warmup Iteration   3: 8.492 ops/ms
Iteration   1: 8.689 ops/ms
Iteration   2: 8.939 ops/ms
Iteration   3: 8.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.756 ±(99.9%) 2.918 ops/ms [Average]
  (min, avg, max) = (8.641, 8.756, 8.939), stdev = 0.160
  CI (99.9%): [5.838, 11.674] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ops/ms
# Warmup Iteration   2: 7.858 ops/ms
# Warmup Iteration   3: 8.313 ops/ms
Iteration   1: 8.433 ops/ms
Iteration   2: 8.648 ops/ms
Iteration   3: 8.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.531 ±(99.9%) 1.982 ops/ms [Average]
  (min, avg, max) = (8.433, 8.531, 8.648), stdev = 0.109
  CI (99.9%): [6.549, 10.513] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 4.569 ops/ms
# Warmup Iteration   2: 5.761 ops/ms
# Warmup Iteration   3: 6.318 ops/ms
Iteration   1: 6.275 ops/ms
Iteration   2: 6.319 ops/ms
Iteration   3: 6.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.233 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (6.105, 6.233, 6.319), stdev = 0.113
  CI (99.9%): [4.176, 8.290] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.943 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.014 ms/op
Iteration   1: 3.843 ±(99.9%) 0.006 ms/op
Iteration   2: 3.810 ±(99.9%) 0.004 ms/op
Iteration   3: 3.878 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.844 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.810, 3.844, 3.878), stdev = 0.034
  CI (99.9%): [3.224, 4.463] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.847 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.004 ms/op
Iteration   1: 3.574 ±(99.9%) 0.005 ms/op
Iteration   2: 3.694 ±(99.9%) 0.003 ms/op
Iteration   3: 3.573 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.614 ±(99.9%) 1.264 ms/op [Average]
  (min, avg, max) = (3.573, 3.614, 3.694), stdev = 0.069
  CI (99.9%): [2.349, 4.878] (assumes normal distribution)


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
# Warmup Iteration   1: 5.630 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.006 ms/op
Iteration   1: 3.917 ±(99.9%) 0.005 ms/op
Iteration   2: 3.927 ±(99.9%) 0.004 ms/op
Iteration   3: 3.904 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.916 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (3.904, 3.916, 3.927), stdev = 0.011
  CI (99.9%): [3.707, 4.125] (assumes normal distribution)


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
# Warmup Iteration   1: 6.419 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 5.317 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.901 ±(99.9%) 0.010 ms/op
Iteration   1: 4.807 ±(99.9%) 0.016 ms/op
Iteration   2: 4.929 ±(99.9%) 0.019 ms/op
Iteration   3: 4.909 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.882 ±(99.9%) 1.199 ms/op [Average]
  (min, avg, max) = (4.807, 4.882, 4.929), stdev = 0.066
  CI (99.9%): [3.683, 6.080] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.752 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.013 ms/op
Iteration   1: 3.861 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   6.843 ms/op
                 createUser·p0.999:  14.615 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   2: 3.830 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  10.576 ms/op
                 createUser·p0.9999: 22.227 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   3: 3.872 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.540 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  21.955 ms/op
                 createUser·p0.9999: 24.019 ms/op
                 createUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 248957
  mean =      3.854 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5307 
    [ 2.500,  5.000) = 230236 
    [ 5.000,  7.500) = 11780 
    [ 7.500, 10.000) = 1171 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     14.288 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     24.232 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 5.338 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.011 ms/op
Iteration   1: 3.719 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  10.555 ms/op
                 existUser·p0.9999: 21.601 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   2: 3.638 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.685 ms/op
                 existUser·p0.999:  11.369 ms/op
                 existUser·p0.9999: 20.761 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   3: 3.699 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   6.474 ms/op
                 existUser·p0.999:  14.321 ms/op
                 existUser·p0.9999: 32.965 ms/op
                 existUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 260494
  mean =      3.685 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9597 
    [ 2.500,  5.000) = 239961 
    [ 5.000,  7.500) = 9353 
    [ 7.500, 10.000) = 1047 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     12.460 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     33.934 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 5.637 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.011 ms/op
Iteration   1: 3.822 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  13.538 ms/op
                 getUser·p0.9999: 22.172 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   2: 3.956 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.623 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   7.026 ms/op
                 getUser·p0.999:  15.715 ms/op
                 getUser·p0.9999: 27.910 ms/op
                 getUser·p1.00:   29.426 ms/op

Iteration   3: 3.987 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   7.030 ms/op
                 getUser·p0.999:  10.324 ms/op
                 getUser·p0.9999: 36.307 ms/op
                 getUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 244842
  mean =      3.921 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5096 
    [ 2.500,  5.000) = 223757 
    [ 5.000,  7.500) = 14035 
    [ 7.500, 10.000) = 1371 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.033 ms/op
     p(99.9000) =     13.552 ms/op
     p(99.9900) =     34.375 ms/op
     p(99.9990) =     36.576 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 6.912 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.395 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.115 ±(99.9%) 0.019 ms/op
Iteration   1: 4.941 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.615 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.537 ms/op
                 listUser·p0.95:   7.479 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  16.209 ms/op
                 listUser·p0.9999: 24.156 ms/op
                 listUser·p1.00:   29.164 ms/op

Iteration   2: 4.985 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.447 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  17.309 ms/op
                 listUser·p0.9999: 22.853 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 5.069 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.443 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  27.591 ms/op
                 listUser·p0.9999: 30.980 ms/op
                 listUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192072
  mean =      4.998 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 347 
    [ 2.500,  5.000) = 127152 
    [ 5.000,  7.500) = 54710 
    [ 7.500, 10.000) = 7982 
    [10.000, 12.500) = 1107 
    [12.500, 15.000) = 319 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.513 ms/op
     p(95.0000) =      7.537 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     29.143 ms/op
     p(99.9990) =     32.988 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.250 ± 2.153  ops/ms
ClientGrpc.existUser                       thrpt       3   8.756 ± 2.918  ops/ms
ClientGrpc.getUser                         thrpt       3   8.531 ± 1.982  ops/ms
ClientGrpc.listUser                        thrpt       3   6.233 ± 2.057  ops/ms
ClientGrpc.createUser                       avgt       3   3.844 ± 0.620   ms/op
ClientGrpc.existUser                        avgt       3   3.614 ± 1.264   ms/op
ClientGrpc.getUser                          avgt       3   3.916 ± 0.209   ms/op
ClientGrpc.listUser                         avgt       3   4.882 ± 1.199   ms/op
ClientGrpc.createUser                     sample  248957   3.854 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.540           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.701           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.288           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.872           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.510           ms/op
ClientGrpc.existUser                      sample  260494   3.685 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.755           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.874           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.652           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.460           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.490           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.079           ms/op
ClientGrpc.getUser                        sample  244842   3.921 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.623           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.177           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.033           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.552           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.375           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.356           ms/op
ClientGrpc.listUser                       sample  192072   4.998 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.443           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.513           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.537           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.978           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.416           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.143           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.260           ms/op
