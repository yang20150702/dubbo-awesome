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
# Warmup Iteration   1: 3.972 ops/ms
# Warmup Iteration   2: 8.564 ops/ms
# Warmup Iteration   3: 9.589 ops/ms
Iteration   1: 9.896 ops/ms
Iteration   2: 10.099 ops/ms
Iteration   3: 9.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.978 ±(99.9%) 1.953 ops/ms [Average]
  (min, avg, max) = (9.896, 9.978, 10.099), stdev = 0.107
  CI (99.9%): [8.025, 11.931] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.304 ops/ms
# Warmup Iteration   2: 9.796 ops/ms
# Warmup Iteration   3: 10.403 ops/ms
Iteration   1: 10.926 ops/ms
Iteration   2: 10.898 ops/ms
Iteration   3: 10.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.886 ±(99.9%) 0.853 ops/ms [Average]
  (min, avg, max) = (10.835, 10.886, 10.926), stdev = 0.047
  CI (99.9%): [10.033, 11.740] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.608 ops/ms
# Warmup Iteration   2: 9.904 ops/ms
# Warmup Iteration   3: 10.440 ops/ms
Iteration   1: 10.367 ops/ms
Iteration   2: 10.305 ops/ms
Iteration   3: 10.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.346 ±(99.9%) 0.659 ops/ms [Average]
  (min, avg, max) = (10.305, 10.346, 10.367), stdev = 0.036
  CI (99.9%): [9.687, 11.006] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.160 ops/ms
# Warmup Iteration   2: 7.725 ops/ms
# Warmup Iteration   3: 7.945 ops/ms
Iteration   1: 7.761 ops/ms
Iteration   2: 7.885 ops/ms
Iteration   3: 7.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.818 ±(99.9%) 1.139 ops/ms [Average]
  (min, avg, max) = (7.761, 7.818, 7.885), stdev = 0.062
  CI (99.9%): [6.679, 8.957] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.290 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.002 ms/op
Iteration   1: 3.108 ±(99.9%) 0.002 ms/op
Iteration   2: 2.971 ±(99.9%) 0.003 ms/op
Iteration   3: 3.072 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.050 ±(99.9%) 1.298 ms/op [Average]
  (min, avg, max) = (2.971, 3.050, 3.108), stdev = 0.071
  CI (99.9%): [1.752, 4.348] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.023 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.002 ms/op
Iteration   1: 2.945 ±(99.9%) 0.002 ms/op
Iteration   2: 2.890 ±(99.9%) 0.003 ms/op
Iteration   3: 2.878 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.904 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (2.878, 2.904, 2.945), stdev = 0.036
  CI (99.9%): [2.256, 3.552] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.591 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.003 ms/op
Iteration   1: 3.058 ±(99.9%) 0.003 ms/op
Iteration   2: 3.077 ±(99.9%) 0.004 ms/op
Iteration   3: 3.064 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (3.058, 3.066, 3.077), stdev = 0.010
  CI (99.9%): [2.885, 3.247] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.561 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.018 ms/op
Iteration   1: 4.049 ±(99.9%) 0.019 ms/op
Iteration   2: 4.048 ±(99.9%) 0.014 ms/op
Iteration   3: 4.125 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.074 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (4.048, 4.074, 4.125), stdev = 0.044
  CI (99.9%): [3.267, 4.881] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.418 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.008 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.047 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 19.191 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  12.157 ms/op
                 createUser·p0.9999: 14.806 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   3: 3.057 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.038 ms/op
                 createUser·p0.999:  11.018 ms/op
                 createUser·p0.9999: 25.185 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311391
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22230 
    [ 2.500,  5.000) = 286058 
    [ 5.000,  7.500) = 2295 
    [ 7.500, 10.000) = 466 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =     10.420 ms/op
     p(99.9900) =     23.949 ms/op
     p(99.9990) =     25.654 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.007 ms/op
Iteration   1: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.672 ms/op
                 existUser·p0.9999: 15.222 ms/op
                 existUser·p1.00:   15.598 ms/op

Iteration   2: 2.885 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  7.292 ms/op
                 existUser·p0.9999: 15.806 ms/op
                 existUser·p1.00:   16.073 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.415 ms/op
                 existUser·p0.9999: 17.440 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328176
  mean =      2.924 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1559 
    [ 1.250,  2.500) = 34905 
    [ 2.500,  3.750) = 280585 
    [ 3.750,  5.000) = 9268 
    [ 5.000,  6.250) = 962 
    [ 6.250,  7.500) = 563 
    [ 7.500,  8.750) = 141 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.519 ms/op
     p(99.9900) =     16.338 ms/op
     p(99.9990) =     19.226 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.308 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  8.088 ms/op
                 getUser·p0.9999: 13.013 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  9.765 ms/op
                 getUser·p0.9999: 20.004 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   3: 3.110 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  9.395 ms/op
                 getUser·p0.9999: 32.324 ms/op
                 getUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310890
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17810 
    [ 2.500,  5.000) = 289877 
    [ 5.000,  7.500) = 2591 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =      9.242 ms/op
     p(99.9900) =     31.449 ms/op
     p(99.9990) =     32.630 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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
# Warmup Iteration   1: 5.551 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.284 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.012 ms/op
Iteration   1: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  13.967 ms/op
                 listUser·p0.9999: 24.314 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   2: 4.074 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.357 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  15.220 ms/op
                 listUser·p0.9999: 23.172 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  16.005 ms/op
                 listUser·p0.9999: 19.010 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237193
  mean =      4.045 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2924 
    [ 2.500,  5.000) = 208685 
    [ 5.000,  7.500) = 23613 
    [ 7.500, 10.000) = 1500 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     14.916 ms/op
     p(99.9900) =     23.995 ms/op
     p(99.9990) =     24.552 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.978 ± 1.953  ops/ms
ClientGrpc.existUser                       thrpt       3  10.886 ± 0.853  ops/ms
ClientGrpc.getUser                         thrpt       3  10.346 ± 0.659  ops/ms
ClientGrpc.listUser                        thrpt       3   7.818 ± 1.139  ops/ms
ClientGrpc.createUser                       avgt       3   3.050 ± 1.298   ms/op
ClientGrpc.existUser                        avgt       3   2.904 ± 0.648   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.181   ms/op
ClientGrpc.listUser                         avgt       3   4.074 ± 0.807   ms/op
ClientGrpc.createUser                     sample  311391   3.084 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.796           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.997           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.420           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.949           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.723           ms/op
ClientGrpc.existUser                      sample  328176   2.924 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.713           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.519           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.338           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.235           ms/op
ClientGrpc.getUser                        sample  310890   3.087 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.571           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.030           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.242           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.449           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.063           ms/op
ClientGrpc.listUser                       sample  237193   4.045 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.357           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.916           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.995           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.609           ms/op
