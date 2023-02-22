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
# Warmup Iteration   1: 4.801 ops/ms
# Warmup Iteration   2: 9.252 ops/ms
# Warmup Iteration   3: 10.215 ops/ms
Iteration   1: 10.158 ops/ms
Iteration   2: 10.038 ops/ms
Iteration   3: 10.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.136 ±(99.9%) 1.625 ops/ms [Average]
  (min, avg, max) = (10.038, 10.136, 10.213), stdev = 0.089
  CI (99.9%): [8.511, 11.761] (assumes normal distribution)


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
# Warmup Iteration   1: 7.708 ops/ms
# Warmup Iteration   2: 10.570 ops/ms
# Warmup Iteration   3: 11.014 ops/ms
Iteration   1: 11.026 ops/ms
Iteration   2: 11.306 ops/ms
Iteration   3: 11.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.129 ±(99.9%) 2.812 ops/ms [Average]
  (min, avg, max) = (11.026, 11.129, 11.306), stdev = 0.154
  CI (99.9%): [8.317, 13.941] (assumes normal distribution)


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
# Warmup Iteration   1: 7.729 ops/ms
# Warmup Iteration   2: 10.222 ops/ms
# Warmup Iteration   3: 10.312 ops/ms
Iteration   1: 10.515 ops/ms
Iteration   2: 10.127 ops/ms
Iteration   3: 10.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.413 ±(99.9%) 4.578 ops/ms [Average]
  (min, avg, max) = (10.127, 10.413, 10.596), stdev = 0.251
  CI (99.9%): [5.834, 14.991] (assumes normal distribution)


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
# Warmup Iteration   1: 5.931 ops/ms
# Warmup Iteration   2: 7.769 ops/ms
# Warmup Iteration   3: 7.879 ops/ms
Iteration   1: 8.094 ops/ms
Iteration   2: 7.875 ops/ms
Iteration   3: 7.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.949 ±(99.9%) 2.292 ops/ms [Average]
  (min, avg, max) = (7.875, 7.949, 8.094), stdev = 0.126
  CI (99.9%): [5.658, 10.241] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.140 ±(99.9%) 0.010 ms/op
Iteration   2: 3.069 ±(99.9%) 0.003 ms/op
Iteration   3: 3.110 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.106 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.069, 3.106, 3.140), stdev = 0.035
  CI (99.9%): [2.463, 3.749] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.003 ms/op
Iteration   1: 2.922 ±(99.9%) 0.002 ms/op
Iteration   2: 2.952 ±(99.9%) 0.002 ms/op
Iteration   3: 2.935 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.936 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (2.922, 2.936, 2.952), stdev = 0.015
  CI (99.9%): [2.660, 3.213] (assumes normal distribution)


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.002 ms/op
Iteration   1: 3.004 ±(99.9%) 0.003 ms/op
Iteration   2: 3.125 ±(99.9%) 0.002 ms/op
Iteration   3: 3.208 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.112 ±(99.9%) 1.875 ms/op [Average]
  (min, avg, max) = (3.004, 3.112, 3.208), stdev = 0.103
  CI (99.9%): [1.237, 4.987] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.225 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.008 ms/op
Iteration   1: 4.083 ±(99.9%) 0.017 ms/op
Iteration   2: 4.058 ±(99.9%) 0.010 ms/op
Iteration   3: 3.983 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.041 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (3.983, 4.041, 4.083), stdev = 0.052
  CI (99.9%): [3.088, 4.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
Iteration   1: 3.169 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.768 ms/op
                 createUser·p0.9999: 18.153 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.070 ms/op
                 createUser·p0.9999: 17.849 ms/op
                 createUser·p1.00:   18.317 ms/op

Iteration   3: 3.184 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  11.671 ms/op
                 createUser·p0.9999: 24.410 ms/op
                 createUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304374
  mean =      3.153 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16526 
    [ 2.500,  5.000) = 286881 
    [ 5.000,  7.500) = 591 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     24.543 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 3.731 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.919 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.892 ms/op
                 existUser·p0.9999: 16.270 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.758 ms/op
                 existUser·p0.9999: 13.079 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   3: 2.967 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.104 ms/op
                 existUser·p0.9999: 27.401 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325141
  mean =      2.954 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45432 
    [ 2.500,  5.000) = 278724 
    [ 5.000,  7.500) = 761 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     27.648 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  7.086 ms/op
                 getUser·p0.9999: 18.219 ms/op
                 getUser·p1.00:   18.711 ms/op

Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.848 ms/op
                 getUser·p0.9999: 19.356 ms/op
                 getUser·p1.00:   19.923 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.457 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.063 ms/op
                 getUser·p0.999:  6.918 ms/op
                 getUser·p0.9999: 18.527 ms/op
                 getUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314028
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1258 
    [ 1.250,  2.500) = 20716 
    [ 2.500,  3.750) = 273666 
    [ 3.750,  5.000) = 17368 
    [ 5.000,  6.250) = 401 
    [ 6.250,  7.500) = 321 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 54 
    [17.500, 18.750) = 72 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.348 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     19.815 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.011 ms/op
Iteration   1: 4.138 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  13.410 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   2: 3.992 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.966 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 4.045 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.307 ms/op
                 listUser·p0.9999: 17.503 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236712
  mean =      4.057 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 6602 
    [ 2.500,  3.750) = 95275 
    [ 3.750,  5.000) = 95399 
    [ 5.000,  6.250) = 33146 
    [ 6.250,  7.500) = 4881 
    [ 7.500,  8.750) = 889 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 86 
    [15.000, 16.250) = 98 
    [16.250, 17.500) = 73 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     17.935 ms/op
     p(99.9990) =     19.222 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.136 ± 1.625  ops/ms
ClientGrpc.existUser                       thrpt       3  11.129 ± 2.812  ops/ms
ClientGrpc.getUser                         thrpt       3  10.413 ± 4.578  ops/ms
ClientGrpc.listUser                        thrpt       3   7.949 ± 2.292  ops/ms
ClientGrpc.createUser                       avgt       3   3.106 ± 0.643   ms/op
ClientGrpc.existUser                        avgt       3   2.936 ± 0.277   ms/op
ClientGrpc.getUser                          avgt       3   3.112 ± 1.875   ms/op
ClientGrpc.listUser                         avgt       3   4.041 ± 0.953   ms/op
ClientGrpc.createUser                     sample  304374   3.153 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.737           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.634           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.150           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.642           ms/op
ClientGrpc.existUser                      sample  325141   2.954 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.593           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.750           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.444           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.787           ms/op
ClientGrpc.getUser                        sample  314028   3.056 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.457           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.174           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.348           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.678           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.923           ms/op
ClientGrpc.listUser                       sample  236712   4.057 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.878           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.935           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.464           ms/op
