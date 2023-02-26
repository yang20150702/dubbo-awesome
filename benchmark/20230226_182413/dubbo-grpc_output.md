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
# Warmup Iteration   1: 5.072 ops/ms
# Warmup Iteration   2: 9.791 ops/ms
# Warmup Iteration   3: 10.517 ops/ms
Iteration   1: 10.724 ops/ms
Iteration   2: 9.997 ops/ms
Iteration   3: 10.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.307 ±(99.9%) 6.844 ops/ms [Average]
  (min, avg, max) = (9.997, 10.307, 10.724), stdev = 0.375
  CI (99.9%): [3.463, 17.151] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.061 ops/ms
# Warmup Iteration   2: 10.896 ops/ms
# Warmup Iteration   3: 10.834 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 11.319 ops/ms
Iteration   3: 10.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.943 ±(99.9%) 6.085 ops/ms [Average]
  (min, avg, max) = (10.682, 10.943, 11.319), stdev = 0.334
  CI (99.9%): [4.858, 17.028] (assumes normal distribution)


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
# Warmup Iteration   1: 8.144 ops/ms
# Warmup Iteration   2: 10.145 ops/ms
# Warmup Iteration   3: 10.585 ops/ms
Iteration   1: 10.753 ops/ms
Iteration   2: 10.376 ops/ms
Iteration   3: 10.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.496 ±(99.9%) 4.068 ops/ms [Average]
  (min, avg, max) = (10.358, 10.496, 10.753), stdev = 0.223
  CI (99.9%): [6.428, 14.563] (assumes normal distribution)


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
# Warmup Iteration   1: 5.786 ops/ms
# Warmup Iteration   2: 7.672 ops/ms
# Warmup Iteration   3: 8.146 ops/ms
Iteration   1: 8.185 ops/ms
Iteration   2: 8.177 ops/ms
Iteration   3: 7.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.073 ±(99.9%) 3.415 ops/ms [Average]
  (min, avg, max) = (7.857, 8.073, 8.185), stdev = 0.187
  CI (99.9%): [4.658, 11.487] (assumes normal distribution)


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.003 ms/op
Iteration   1: 2.937 ±(99.9%) 0.003 ms/op
Iteration   2: 2.991 ±(99.9%) 0.003 ms/op
Iteration   3: 3.136 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.021 ±(99.9%) 1.877 ms/op [Average]
  (min, avg, max) = (2.937, 3.021, 3.136), stdev = 0.103
  CI (99.9%): [1.145, 4.898] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.698 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.002 ms/op
Iteration   1: 2.951 ±(99.9%) 0.002 ms/op
Iteration   2: 2.910 ±(99.9%) 0.002 ms/op
Iteration   3: 2.874 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.912 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (2.874, 2.912, 2.951), stdev = 0.039
  CI (99.9%): [2.205, 3.618] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.002 ms/op
Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
Iteration   3: 3.059 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.023 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (2.986, 3.023, 3.059), stdev = 0.037
  CI (99.9%): [2.355, 3.692] (assumes normal distribution)


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
# Warmup Iteration   1: 4.986 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.012 ms/op
Iteration   1: 3.949 ±(99.9%) 0.012 ms/op
Iteration   2: 4.085 ±(99.9%) 0.010 ms/op
Iteration   3: 4.061 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.032 ±(99.9%) 1.327 ms/op [Average]
  (min, avg, max) = (3.949, 4.032, 4.085), stdev = 0.073
  CI (99.9%): [2.705, 5.358] (assumes normal distribution)


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.007 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.592 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.116 ms/op
                 createUser·p0.999:  6.504 ms/op
                 createUser·p0.9999: 16.854 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   2: 2.989 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.721 ms/op
                 createUser·p0.9999: 28.115 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  6.930 ms/op
                 createUser·p0.9999: 21.346 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319055
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33209 
    [ 2.500,  5.000) = 284945 
    [ 5.000,  7.500) = 672 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.709 ms/op
     p(99.9900) =     26.102 ms/op
     p(99.9990) =     28.371 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 3.713 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 2.931 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.949 ms/op
                 existUser·p0.9999: 11.634 ms/op
                 existUser·p1.00:   11.960 ms/op

Iteration   2: 2.896 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  6.382 ms/op
                 existUser·p0.9999: 22.807 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   3: 2.838 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.402 ms/op
                 existUser·p0.9999: 15.916 ms/op
                 existUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332451
  mean =      2.888 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59532 
    [ 2.500,  5.000) = 272018 
    [ 5.000,  7.500) = 643 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.640 ms/op
     p(99.9900) =     16.278 ms/op
     p(99.9990) =     23.233 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.703 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.487 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.291 ms/op
                 getUser·p0.9999: 14.963 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.570 ms/op
                 getUser·p0.9999: 16.639 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   3: 2.919 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.296 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.014 ms/op
                 getUser·p0.999:  8.782 ms/op
                 getUser·p0.9999: 19.792 ms/op
                 getUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321381
  mean =      2.986 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3546 
    [ 1.250,  2.500) = 28482 
    [ 2.500,  3.750) = 272146 
    [ 3.750,  5.000) = 16195 
    [ 5.000,  6.250) = 545 
    [ 6.250,  7.500) = 169 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.296 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.230 ms/op
     p(99.9900) =     18.479 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 5.195 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.010 ms/op
Iteration   1: 3.992 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  12.527 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   2: 3.999 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.563 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 4.019 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.724 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.076 ms/op
                 listUser·p0.9999: 21.170 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239827
  mean =      4.003 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3830 
    [ 2.500,  5.000) = 207527 
    [ 5.000,  7.500) = 27263 
    [ 7.500, 10.000) = 754 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     19.925 ms/op
     p(99.9990) =     21.424 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.307 ± 6.844  ops/ms
ClientGrpc.existUser                       thrpt       3  10.943 ± 6.085  ops/ms
ClientGrpc.getUser                         thrpt       3  10.496 ± 4.068  ops/ms
ClientGrpc.listUser                        thrpt       3   8.073 ± 3.415  ops/ms
ClientGrpc.createUser                       avgt       3   3.021 ± 1.877   ms/op
ClientGrpc.existUser                        avgt       3   2.912 ± 0.706   ms/op
ClientGrpc.getUser                          avgt       3   3.023 ± 0.668   ms/op
ClientGrpc.listUser                         avgt       3   4.032 ± 1.327   ms/op
ClientGrpc.createUser                     sample  319055   3.005 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.592           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.709           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.102           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.475           ms/op
ClientGrpc.existUser                      sample  332451   2.888 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.588           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.640           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.278           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.396           ms/op
ClientGrpc.getUser                        sample  321381   2.986 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.296           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.230           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.479           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.956           ms/op
ClientGrpc.listUser                       sample  239827   4.003 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.724           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.746           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.925           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.529           ms/op
