# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.477 ops/ms
# Warmup Iteration   2: 9.747 ops/ms
# Warmup Iteration   3: 10.387 ops/ms
Iteration   1: 10.749 ops/ms
Iteration   2: 10.810 ops/ms
Iteration   3: 10.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.767 ±(99.9%) 0.688 ops/ms [Average]
  (min, avg, max) = (10.742, 10.767, 10.810), stdev = 0.038
  CI (99.9%): [10.079, 11.455] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.255 ops/ms
# Warmup Iteration   2: 10.930 ops/ms
# Warmup Iteration   3: 11.192 ops/ms
Iteration   1: 11.447 ops/ms
Iteration   2: 11.608 ops/ms
Iteration   3: 11.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.485 ±(99.9%) 1.988 ops/ms [Average]
  (min, avg, max) = (11.400, 11.485, 11.608), stdev = 0.109
  CI (99.9%): [9.497, 13.473] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.596 ops/ms
# Warmup Iteration   2: 10.445 ops/ms
# Warmup Iteration   3: 10.731 ops/ms
Iteration   1: 10.839 ops/ms
Iteration   2: 10.871 ops/ms
Iteration   3: 10.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.853 ±(99.9%) 0.304 ops/ms [Average]
  (min, avg, max) = (10.839, 10.853, 10.871), stdev = 0.017
  CI (99.9%): [10.549, 11.157] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.739 ops/ms
# Warmup Iteration   2: 7.804 ops/ms
# Warmup Iteration   3: 8.240 ops/ms
Iteration   1: 8.062 ops/ms
Iteration   2: 8.278 ops/ms
Iteration   3: 8.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.182 ±(99.9%) 2.009 ops/ms [Average]
  (min, avg, max) = (8.062, 8.182, 8.278), stdev = 0.110
  CI (99.9%): [6.174, 10.191] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.056 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.004 ms/op
Iteration   1: 3.055 ±(99.9%) 0.003 ms/op
Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
Iteration   3: 2.992 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (2.992, 3.013, 3.055), stdev = 0.036
  CI (99.9%): [2.351, 3.674] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.003 ms/op
Iteration   1: 2.928 ±(99.9%) 0.003 ms/op
Iteration   2: 2.914 ±(99.9%) 0.004 ms/op
Iteration   3: 2.917 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.920 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (2.914, 2.920, 2.928), stdev = 0.007
  CI (99.9%): [2.787, 3.052] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.071 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.003 ms/op
Iteration   1: 3.068 ±(99.9%) 0.002 ms/op
Iteration   2: 3.084 ±(99.9%) 0.002 ms/op
Iteration   3: 3.107 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.086 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (3.068, 3.086, 3.107), stdev = 0.020
  CI (99.9%): [2.726, 3.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.857 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.031 ms/op
Iteration   1: 4.145 ±(99.9%) 0.019 ms/op
Iteration   2: 4.066 ±(99.9%) 0.006 ms/op
Iteration   3: 4.052 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.088 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (4.052, 4.088, 4.145), stdev = 0.050
  CI (99.9%): [3.174, 5.001] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.366 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.008 ms/op
Iteration   1: 3.118 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 28.303 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.711 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.149 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  8.492 ms/op
                 createUser·p0.9999: 25.854 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305756
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15264 
    [ 2.500,  5.000) = 288374 
    [ 5.000,  7.500) = 1728 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      8.194 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     28.606 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  7.225 ms/op
                 existUser·p0.9999: 12.632 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.709 ms/op
                 existUser·p0.9999: 14.860 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 2.953 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.801 ms/op
                 existUser·p0.9999: 28.934 ms/op
                 existUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324502
  mean =      2.956 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34102 
    [ 2.500,  5.000) = 289198 
    [ 5.000,  7.500) = 934 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      6.922 ms/op
     p(99.9900) =     25.092 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.271 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
Iteration   1: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  7.458 ms/op
                 getUser·p0.9999: 14.353 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.377 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.442 ms/op
                 getUser·p0.9999: 14.695 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.618 ms/op
                 getUser·p0.9999: 15.786 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309406
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1903 
    [ 1.250,  2.500) = 16479 
    [ 2.500,  3.750) = 269782 
    [ 3.750,  5.000) = 19307 
    [ 5.000,  6.250) = 1129 
    [ 6.250,  7.500) = 443 
    [ 7.500,  8.750) = 139 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 105 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.735 ms/op
     p(99.9900) =     14.960 ms/op
     p(99.9990) =     17.066 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.186 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.011 ms/op
Iteration   1: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.300 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 22.906 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 3.989 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  16.281 ms/op
                 listUser·p0.9999: 19.521 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 3.981 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.519 ms/op
                 listUser·p0.9999: 20.242 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240263
  mean =      3.997 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3202 
    [ 2.500,  5.000) = 212044 
    [ 5.000,  7.500) = 23578 
    [ 7.500, 10.000) = 959 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.300 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     15.474 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     23.324 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.767 ± 0.688  ops/ms
ClientGrpc.existUser                       thrpt       3  11.485 ± 1.988  ops/ms
ClientGrpc.getUser                         thrpt       3  10.853 ± 0.304  ops/ms
ClientGrpc.listUser                        thrpt       3   8.182 ± 2.009  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.662   ms/op
ClientGrpc.existUser                        avgt       3   2.920 ± 0.133   ms/op
ClientGrpc.getUser                          avgt       3   3.086 ± 0.360   ms/op
ClientGrpc.listUser                         avgt       3   4.088 ± 0.914   ms/op
ClientGrpc.createUser                     sample  305756   3.140 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.603           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.194           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.706           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.770           ms/op
ClientGrpc.existUser                      sample  324502   2.956 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.582           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.922           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.092           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.622           ms/op
ClientGrpc.getUser                        sample  309406   3.100 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.377           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.735           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.960           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.695           ms/op
ClientGrpc.listUser                       sample  240263   3.997 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.300           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.474           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.561           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.396           ms/op
