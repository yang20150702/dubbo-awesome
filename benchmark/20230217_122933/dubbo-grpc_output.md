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
# Warmup Iteration   1: 4.948 ops/ms
# Warmup Iteration   2: 9.083 ops/ms
# Warmup Iteration   3: 10.415 ops/ms
Iteration   1: 10.322 ops/ms
Iteration   2: 10.321 ops/ms
Iteration   3: 10.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.329 ±(99.9%) 0.237 ops/ms [Average]
  (min, avg, max) = (10.321, 10.329, 10.344), stdev = 0.013
  CI (99.9%): [10.092, 10.566] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.047 ops/ms
# Warmup Iteration   2: 10.527 ops/ms
# Warmup Iteration   3: 10.648 ops/ms
Iteration   1: 10.765 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.744 ±(99.9%) 3.457 ops/ms [Average]
  (min, avg, max) = (10.544, 10.744, 10.921), stdev = 0.189
  CI (99.9%): [7.287, 14.201] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.058 ops/ms
# Warmup Iteration   2: 10.065 ops/ms
# Warmup Iteration   3: 10.192 ops/ms
Iteration   1: 10.080 ops/ms
Iteration   2: 10.539 ops/ms
Iteration   3: 10.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.364 ±(99.9%) 4.537 ops/ms [Average]
  (min, avg, max) = (10.080, 10.364, 10.539), stdev = 0.249
  CI (99.9%): [5.828, 14.901] (assumes normal distribution)


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
# Warmup Iteration   1: 6.526 ops/ms
# Warmup Iteration   2: 7.636 ops/ms
# Warmup Iteration   3: 7.998 ops/ms
Iteration   1: 7.909 ops/ms
Iteration   2: 8.004 ops/ms
Iteration   3: 8.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.042 ±(99.9%) 2.855 ops/ms [Average]
  (min, avg, max) = (7.909, 8.042, 8.215), stdev = 0.156
  CI (99.9%): [5.188, 10.897] (assumes normal distribution)


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.003 ms/op
Iteration   1: 3.128 ±(99.9%) 0.003 ms/op
Iteration   2: 3.143 ±(99.9%) 0.003 ms/op
Iteration   3: 3.167 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.146 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (3.128, 3.146, 3.167), stdev = 0.020
  CI (99.9%): [2.787, 3.506] (assumes normal distribution)


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.003 ms/op
Iteration   1: 2.879 ±(99.9%) 0.003 ms/op
Iteration   2: 3.063 ±(99.9%) 0.002 ms/op
Iteration   3: 2.980 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 1.683 ms/op [Average]
  (min, avg, max) = (2.879, 2.974, 3.063), stdev = 0.092
  CI (99.9%): [1.291, 4.657] (assumes normal distribution)


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
# Warmup Iteration   1: 4.006 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.003 ms/op
Iteration   1: 3.084 ±(99.9%) 0.002 ms/op
Iteration   2: 2.982 ±(99.9%) 0.004 ms/op
Iteration   3: 3.082 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.049 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (2.982, 3.049, 3.084), stdev = 0.058
  CI (99.9%): [1.987, 4.112] (assumes normal distribution)


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
# Warmup Iteration   1: 5.569 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.015 ms/op
Iteration   1: 4.099 ±(99.9%) 0.023 ms/op
Iteration   2: 4.135 ±(99.9%) 0.014 ms/op
Iteration   3: 4.059 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.098 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (4.059, 4.098, 4.135), stdev = 0.038
  CI (99.9%): [3.412, 4.784] (assumes normal distribution)


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.008 ms/op
Iteration   1: 3.198 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.266 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   5.185 ms/op
                 createUser·p0.999:  9.666 ms/op
                 createUser·p0.9999: 15.811 ms/op
                 createUser·p1.00:   16.515 ms/op

Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.224 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.734 ms/op
                 createUser·p0.9999: 20.677 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  8.068 ms/op
                 createUser·p0.9999: 23.350 ms/op
                 createUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305856
  mean =      3.137 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23003 
    [ 2.500,  5.000) = 280471 
    [ 5.000,  7.500) = 1867 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.224 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     20.835 ms/op
     p(99.9990) =     23.755 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  5.751 ms/op
                 existUser·p0.9999: 15.894 ms/op
                 existUser·p1.00:   16.335 ms/op

Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  8.249 ms/op
                 existUser·p0.9999: 13.232 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  10.741 ms/op
                 existUser·p0.9999: 19.435 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314847
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1873 
    [ 1.250,  2.500) = 31076 
    [ 2.500,  3.750) = 256015 
    [ 3.750,  5.000) = 24711 
    [ 5.000,  6.250) = 534 
    [ 6.250,  7.500) = 230 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.349 ms/op
     p(99.9900) =     16.196 ms/op
     p(99.9990) =     19.651 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.006 ms/op
Iteration   1: 3.101 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.327 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.579 ms/op
                 getUser·p0.9999: 20.240 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   2: 3.112 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.980 ms/op
                 getUser·p0.9999: 13.447 ms/op
                 getUser·p1.00:   13.648 ms/op

Iteration   3: 3.069 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.652 ms/op
                 getUser·p0.9999: 14.650 ms/op
                 getUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310221
  mean =      3.094 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19849 
    [ 2.500,  5.000) = 289249 
    [ 5.000,  7.500) = 809 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.518 ms/op
     p(99.9900) =     19.627 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 5.106 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.013 ms/op
Iteration   1: 4.160 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.336 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 18.512 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   2: 4.182 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  15.944 ms/op
                 listUser·p0.9999: 19.696 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 4.061 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.737 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 23.167 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232058
  mean =      4.134 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3271 
    [ 2.500,  5.000) = 187636 
    [ 5.000,  7.500) = 39313 
    [ 7.500, 10.000) = 1376 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     16.285 ms/op
     p(99.9900) =     22.531 ms/op
     p(99.9990) =     25.419 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.329 ± 0.237  ops/ms
ClientGrpc.existUser                       thrpt       3  10.744 ± 3.457  ops/ms
ClientGrpc.getUser                         thrpt       3  10.364 ± 4.537  ops/ms
ClientGrpc.listUser                        thrpt       3   8.042 ± 2.855  ops/ms
ClientGrpc.createUser                       avgt       3   3.146 ± 0.359   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 1.683   ms/op
ClientGrpc.getUser                          avgt       3   3.049 ± 1.062   ms/op
ClientGrpc.listUser                         avgt       3   4.098 ± 0.686   ms/op
ClientGrpc.createUser                     sample  305856   3.137 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.224           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.011           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.835           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.855           ms/op
ClientGrpc.existUser                      sample  314847   3.047 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.608           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.349           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.196           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  310221   3.094 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.327           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.518           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.627           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.546           ms/op
ClientGrpc.listUser                       sample  232058   4.134 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.737           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.285           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.531           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.919           ms/op
