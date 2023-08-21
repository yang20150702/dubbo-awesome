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
# Warmup Iteration   1: 2.474 ops/ms
# Warmup Iteration   2: 6.559 ops/ms
# Warmup Iteration   3: 7.805 ops/ms
Iteration   1: 8.514 ops/ms
Iteration   2: 8.196 ops/ms
Iteration   3: 8.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.281 ±(99.9%) 3.732 ops/ms [Average]
  (min, avg, max) = (8.132, 8.281, 8.514), stdev = 0.205
  CI (99.9%): [4.548, 12.013] (assumes normal distribution)


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
# Warmup Iteration   1: 5.590 ops/ms
# Warmup Iteration   2: 8.364 ops/ms
# Warmup Iteration   3: 8.843 ops/ms
Iteration   1: 9.033 ops/ms
Iteration   2: 9.099 ops/ms
Iteration   3: 8.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.971 ±(99.9%) 3.074 ops/ms [Average]
  (min, avg, max) = (8.780, 8.971, 9.099), stdev = 0.168
  CI (99.9%): [5.897, 12.044] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.194 ops/ms
# Warmup Iteration   2: 7.446 ops/ms
# Warmup Iteration   3: 7.848 ops/ms
Iteration   1: 8.209 ops/ms
Iteration   2: 7.916 ops/ms
Iteration   3: 8.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.050 ±(99.9%) 2.702 ops/ms [Average]
  (min, avg, max) = (7.916, 8.050, 8.209), stdev = 0.148
  CI (99.9%): [5.347, 10.752] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ops/ms
# Warmup Iteration   2: 5.824 ops/ms
# Warmup Iteration   3: 6.060 ops/ms
Iteration   1: 6.268 ops/ms
Iteration   2: 6.302 ops/ms
Iteration   3: 6.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.263 ±(99.9%) 0.776 ops/ms [Average]
  (min, avg, max) = (6.218, 6.263, 6.302), stdev = 0.043
  CI (99.9%): [5.486, 7.039] (assumes normal distribution)


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
# Warmup Iteration   1: 5.856 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.017 ms/op
Iteration   1: 4.150 ±(99.9%) 0.003 ms/op
Iteration   2: 3.930 ±(99.9%) 0.002 ms/op
Iteration   3: 4.032 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.037 ±(99.9%) 2.006 ms/op [Average]
  (min, avg, max) = (3.930, 4.037, 4.150), stdev = 0.110
  CI (99.9%): [2.032, 6.043] (assumes normal distribution)


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
# Warmup Iteration   1: 5.412 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.003 ms/op
Iteration   1: 3.660 ±(99.9%) 0.002 ms/op
Iteration   2: 3.596 ±(99.9%) 0.002 ms/op
Iteration   3: 3.631 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.629 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.596, 3.629, 3.660), stdev = 0.032
  CI (99.9%): [3.043, 4.215] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.532 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.003 ms/op
Iteration   1: 3.831 ±(99.9%) 0.003 ms/op
Iteration   2: 3.799 ±(99.9%) 0.004 ms/op
Iteration   3: 3.858 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.829 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (3.799, 3.829, 3.858), stdev = 0.030
  CI (99.9%): [3.289, 4.370] (assumes normal distribution)


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
# Warmup Iteration   1: 8.078 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.674 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.314 ±(99.9%) 0.012 ms/op
Iteration   1: 5.169 ±(99.9%) 0.012 ms/op
Iteration   2: 5.039 ±(99.9%) 0.021 ms/op
Iteration   3: 4.956 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.055 ±(99.9%) 1.956 ms/op [Average]
  (min, avg, max) = (4.956, 5.055, 5.169), stdev = 0.107
  CI (99.9%): [3.099, 7.010] (assumes normal distribution)


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
# Warmup Iteration   1: 5.311 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.266 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.012 ms/op
Iteration   1: 3.950 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  11.535 ms/op
                 createUser·p0.9999: 21.326 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   2: 3.862 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  14.769 ms/op
                 createUser·p0.9999: 23.527 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.991 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   7.594 ms/op
                 createUser·p0.999:  12.491 ms/op
                 createUser·p0.9999: 27.459 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244034
  mean =      3.934 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4766 
    [ 2.500,  5.000) = 217261 
    [ 5.000,  7.500) = 19915 
    [ 7.500, 10.000) = 1568 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     12.173 ms/op
     p(99.9900) =     25.814 ms/op
     p(99.9990) =     27.460 ms/op
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
# Warmup Iteration   1: 5.379 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.009 ms/op
Iteration   1: 3.573 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  10.059 ms/op
                 existUser·p0.9999: 14.274 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   2: 3.582 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  8.965 ms/op
                 existUser·p0.9999: 19.282 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   3: 3.613 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   6.462 ms/op
                 existUser·p0.999:  12.132 ms/op
                 existUser·p0.9999: 21.899 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267522
  mean =      3.589 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9886 
    [ 2.500,  5.000) = 248922 
    [ 5.000,  7.500) = 7526 
    [ 7.500, 10.000) = 890 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     10.567 ms/op
     p(99.9900) =     20.857 ms/op
     p(99.9990) =     22.503 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 5.687 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.011 ms/op
Iteration   1: 3.811 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  10.540 ms/op
                 getUser·p0.9999: 19.648 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   2: 3.693 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  10.620 ms/op
                 getUser·p0.9999: 21.365 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   3: 3.890 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   6.874 ms/op
                 getUser·p0.999:  12.305 ms/op
                 getUser·p0.9999: 32.188 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252785
  mean =      3.796 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12019 
    [ 2.500,  5.000) = 224720 
    [ 5.000,  7.500) = 14369 
    [ 7.500, 10.000) = 1338 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     10.653 ms/op
     p(99.9900) =     28.601 ms/op
     p(99.9990) =     32.537 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 7.458 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.468 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.161 ±(99.9%) 0.018 ms/op
Iteration   1: 5.159 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.972 ms/op
                 listUser·p0.50:   4.882 ms/op
                 listUser·p0.90:   6.758 ms/op
                 listUser·p0.95:   7.619 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  16.612 ms/op
                 listUser·p0.9999: 23.488 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 5.186 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   6.726 ms/op
                 listUser·p0.95:   7.627 ms/op
                 listUser·p0.99:   9.617 ms/op
                 listUser·p0.999:  16.525 ms/op
                 listUser·p0.9999: 25.438 ms/op
                 listUser·p1.00:   26.247 ms/op

Iteration   3: 5.271 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   6.816 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   10.076 ms/op
                 listUser·p0.999:  19.518 ms/op
                 listUser·p0.9999: 28.501 ms/op
                 listUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184399
  mean =      5.205 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189 
    [ 2.500,  5.000) = 96882 
    [ 5.000,  7.500) = 76815 
    [ 7.500, 10.000) = 8892 
    [10.000, 12.500) = 1143 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      7.668 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     17.747 ms/op
     p(99.9900) =     27.865 ms/op
     p(99.9990) =     29.807 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.281 ± 3.732  ops/ms
ClientGrpc.existUser                       thrpt       3   8.971 ± 3.074  ops/ms
ClientGrpc.getUser                         thrpt       3   8.050 ± 2.702  ops/ms
ClientGrpc.listUser                        thrpt       3   6.263 ± 0.776  ops/ms
ClientGrpc.createUser                       avgt       3   4.037 ± 2.006   ms/op
ClientGrpc.existUser                        avgt       3   3.629 ± 0.586   ms/op
ClientGrpc.getUser                          avgt       3   3.829 ± 0.540   ms/op
ClientGrpc.listUser                         avgt       3   5.055 ± 1.956   ms/op
ClientGrpc.createUser                     sample  244034   3.934 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.923           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.932           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.390           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.234           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.173           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.814           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.525           ms/op
ClientGrpc.existUser                      sample  267522   3.589 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.715           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.988           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.567           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.857           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.265           ms/op
ClientGrpc.getUser                        sample  252785   3.796 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.766           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.145           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.701           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.653           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.601           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.670           ms/op
ClientGrpc.listUser                       sample  184399   5.205 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.255           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.668           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.830           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.747           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.865           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.917           ms/op
