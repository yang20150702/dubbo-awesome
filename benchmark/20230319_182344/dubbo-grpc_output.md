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
# Warmup Iteration   1: 4.409 ops/ms
# Warmup Iteration   2: 9.734 ops/ms
# Warmup Iteration   3: 10.160 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.549 ops/ms
Iteration   3: 10.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.618 ±(99.9%) 1.204 ops/ms [Average]
  (min, avg, max) = (10.549, 10.618, 10.680), stdev = 0.066
  CI (99.9%): [9.414, 11.821] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.767 ops/ms
# Warmup Iteration   2: 10.737 ops/ms
# Warmup Iteration   3: 11.310 ops/ms
Iteration   1: 11.201 ops/ms
Iteration   2: 11.109 ops/ms
Iteration   3: 11.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.130 ±(99.9%) 1.155 ops/ms [Average]
  (min, avg, max) = (11.079, 11.130, 11.201), stdev = 0.063
  CI (99.9%): [9.975, 12.285] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.556 ops/ms
# Warmup Iteration   2: 10.465 ops/ms
# Warmup Iteration   3: 10.694 ops/ms
Iteration   1: 10.843 ops/ms
Iteration   2: 10.678 ops/ms
Iteration   3: 10.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.780 ±(99.9%) 1.622 ops/ms [Average]
  (min, avg, max) = (10.678, 10.780, 10.843), stdev = 0.089
  CI (99.9%): [9.157, 12.402] (assumes normal distribution)


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
# Warmup Iteration   1: 6.115 ops/ms
# Warmup Iteration   2: 8.069 ops/ms
# Warmup Iteration   3: 8.272 ops/ms
Iteration   1: 8.350 ops/ms
Iteration   2: 8.296 ops/ms
Iteration   3: 8.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.409 ±(99.9%) 2.786 ops/ms [Average]
  (min, avg, max) = (8.296, 8.409, 8.583), stdev = 0.153
  CI (99.9%): [5.624, 11.195] (assumes normal distribution)


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.003 ms/op
Iteration   1: 2.980 ±(99.9%) 0.009 ms/op
Iteration   2: 2.976 ±(99.9%) 0.005 ms/op
Iteration   3: 2.988 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.981 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (2.976, 2.981, 2.988), stdev = 0.006
  CI (99.9%): [2.867, 3.095] (assumes normal distribution)


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.868 ±(99.9%) 0.004 ms/op
Iteration   1: 2.893 ±(99.9%) 0.003 ms/op
Iteration   2: 2.844 ±(99.9%) 0.003 ms/op
Iteration   3: 2.841 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.859 ±(99.9%) 0.529 ms/op [Average]
  (min, avg, max) = (2.841, 2.859, 2.893), stdev = 0.029
  CI (99.9%): [2.331, 3.388] (assumes normal distribution)


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
# Warmup Iteration   1: 3.948 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.003 ms/op
Iteration   1: 2.953 ±(99.9%) 0.002 ms/op
Iteration   2: 2.963 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.959 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (2.953, 2.959, 2.963), stdev = 0.005
  CI (99.9%): [2.861, 3.058] (assumes normal distribution)


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
# Warmup Iteration   1: 5.096 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.033 ms/op
Iteration   1: 3.843 ±(99.9%) 0.020 ms/op
Iteration   2: 3.801 ±(99.9%) 0.018 ms/op
Iteration   3: 3.878 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.840 ±(99.9%) 0.704 ms/op [Average]
  (min, avg, max) = (3.801, 3.840, 3.878), stdev = 0.039
  CI (99.9%): [3.137, 4.544] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.895 ms/op
                 createUser·p0.9999: 18.612 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  5.766 ms/op
                 createUser·p0.9999: 12.932 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   3: 2.992 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  9.485 ms/op
                 createUser·p0.9999: 24.366 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321514
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28897 
    [ 2.500,  5.000) = 291633 
    [ 5.000,  7.500) = 709 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.041 ms/op
     p(99.9900) =     22.799 ms/op
     p(99.9990) =     24.660 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.006 ms/op
Iteration   1: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  5.284 ms/op
                 existUser·p0.9999: 13.334 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   2: 2.875 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  6.927 ms/op
                 existUser·p0.9999: 12.796 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   3: 2.936 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.438 ms/op
                 existUser·p0.9999: 25.563 ms/op
                 existUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330760
  mean =      2.901 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44537 
    [ 2.500,  5.000) = 285316 
    [ 5.000,  7.500) = 683 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.785 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 2.961 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.615 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  6.619 ms/op
                 getUser·p0.9999: 22.623 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   2: 2.936 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  8.327 ms/op
                 getUser·p0.9999: 14.063 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.521 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.085 ms/op
                 getUser·p0.9999: 25.231 ms/op
                 getUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322962
  mean =      2.970 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26697 
    [ 2.500,  5.000) = 294911 
    [ 5.000,  7.500) = 1049 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.161 ms/op
     p(99.9900) =     23.832 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 4.977 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.009 ms/op
Iteration   1: 3.843 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  11.698 ms/op
                 listUser·p0.9999: 16.636 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   2: 3.833 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.595 ms/op
                 listUser·p0.9999: 14.740 ms/op
                 listUser·p1.00:   15.565 ms/op

Iteration   3: 3.790 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.025 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.330 ms/op
                 listUser·p0.9999: 23.992 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251007
  mean =      3.822 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6286 
    [ 2.500,  5.000) = 225473 
    [ 5.000,  7.500) = 18048 
    [ 7.500, 10.000) = 659 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     22.190 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.618 ± 1.204  ops/ms
ClientGrpc.existUser                       thrpt       3  11.130 ± 1.155  ops/ms
ClientGrpc.getUser                         thrpt       3  10.780 ± 1.622  ops/ms
ClientGrpc.listUser                        thrpt       3   8.409 ± 2.786  ops/ms
ClientGrpc.createUser                       avgt       3   2.981 ± 0.114   ms/op
ClientGrpc.existUser                        avgt       3   2.859 ± 0.529   ms/op
ClientGrpc.getUser                          avgt       3   2.959 ± 0.098   ms/op
ClientGrpc.listUser                         avgt       3   3.840 ± 0.704   ms/op
ClientGrpc.createUser                     sample  321514   2.986 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.668           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.041           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.799           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.740           ms/op
ClientGrpc.existUser                      sample  330760   2.901 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.482           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.785           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.859           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.854           ms/op
ClientGrpc.getUser                        sample  322962   2.970 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.521           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.161           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.832           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.559           ms/op
ClientGrpc.listUser                       sample  251007   3.822 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.002           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.698           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.190           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.100           ms/op
