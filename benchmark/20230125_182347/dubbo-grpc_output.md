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
# Warmup Iteration   1: 4.691 ops/ms
# Warmup Iteration   2: 9.358 ops/ms
# Warmup Iteration   3: 10.814 ops/ms
Iteration   1: 10.216 ops/ms
Iteration   2: 10.229 ops/ms
Iteration   3: 10.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.240 ±(99.9%) 0.561 ops/ms [Average]
  (min, avg, max) = (10.216, 10.240, 10.275), stdev = 0.031
  CI (99.9%): [9.679, 10.801] (assumes normal distribution)


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
# Warmup Iteration   1: 10.613 ops/ms
# Warmup Iteration   2: 10.449 ops/ms
# Warmup Iteration   3: 10.889 ops/ms
Iteration   1: 10.568 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.684 ±(99.9%) 2.457 ops/ms [Average]
  (min, avg, max) = (10.568, 10.684, 10.832), stdev = 0.135
  CI (99.9%): [8.227, 13.141] (assumes normal distribution)


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
# Warmup Iteration   1: 7.847 ops/ms
# Warmup Iteration   2: 10.350 ops/ms
# Warmup Iteration   3: 10.408 ops/ms
Iteration   1: 10.505 ops/ms
Iteration   2: 10.273 ops/ms
Iteration   3: 10.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.381 ±(99.9%) 2.126 ops/ms [Average]
  (min, avg, max) = (10.273, 10.381, 10.505), stdev = 0.117
  CI (99.9%): [8.256, 12.507] (assumes normal distribution)


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
# Warmup Iteration   1: 5.539 ops/ms
# Warmup Iteration   2: 7.638 ops/ms
# Warmup Iteration   3: 7.771 ops/ms
Iteration   1: 7.919 ops/ms
Iteration   2: 7.874 ops/ms
Iteration   3: 7.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.924 ±(99.9%) 0.955 ops/ms [Average]
  (min, avg, max) = (7.874, 7.924, 7.979), stdev = 0.052
  CI (99.9%): [6.969, 8.879] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.002 ms/op
Iteration   1: 2.986 ±(99.9%) 0.004 ms/op
Iteration   2: 3.021 ±(99.9%) 0.003 ms/op
Iteration   3: 3.130 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.046 ±(99.9%) 1.376 ms/op [Average]
  (min, avg, max) = (2.986, 3.046, 3.130), stdev = 0.075
  CI (99.9%): [1.669, 4.422] (assumes normal distribution)


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.002 ms/op
Iteration   1: 2.969 ±(99.9%) 0.004 ms/op
Iteration   2: 3.054 ±(99.9%) 0.002 ms/op
Iteration   3: 2.932 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.985 ±(99.9%) 1.142 ms/op [Average]
  (min, avg, max) = (2.932, 2.985, 3.054), stdev = 0.063
  CI (99.9%): [1.843, 4.127] (assumes normal distribution)


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
# Warmup Iteration   1: 3.583 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.003 ms/op
Iteration   1: 3.131 ±(99.9%) 0.002 ms/op
Iteration   2: 3.096 ±(99.9%) 0.004 ms/op
Iteration   3: 3.120 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.116 ±(99.9%) 0.326 ms/op [Average]
  (min, avg, max) = (3.096, 3.116, 3.131), stdev = 0.018
  CI (99.9%): [2.789, 3.442] (assumes normal distribution)


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
# Warmup Iteration   1: 5.087 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.022 ms/op
Iteration   1: 3.983 ±(99.9%) 0.030 ms/op
Iteration   2: 4.015 ±(99.9%) 0.010 ms/op
Iteration   3: 4.142 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.047 ±(99.9%) 1.529 ms/op [Average]
  (min, avg, max) = (3.983, 4.047, 4.142), stdev = 0.084
  CI (99.9%): [2.518, 5.575] (assumes normal distribution)


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
# Warmup Iteration   1: 4.098 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.135 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  8.910 ms/op
                 createUser·p0.9999: 12.319 ms/op
                 createUser·p1.00:   13.140 ms/op

Iteration   2: 3.184 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.168 ms/op
                 createUser·p0.9999: 12.629 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.329 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.000 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  11.132 ms/op
                 createUser·p0.9999: 23.953 ms/op
                 createUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304160
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20991 
    [ 2.500,  5.000) = 281973 
    [ 5.000,  7.500) = 707 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =     10.289 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     24.379 ms/op
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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  6.210 ms/op
                 existUser·p0.9999: 21.440 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   2: 2.929 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.480 ms/op
                 existUser·p0.999:  11.208 ms/op
                 existUser·p0.9999: 18.811 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   3: 2.906 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.444 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  4.960 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326535
  mean =      2.941 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47106 
    [ 2.500,  5.000) = 278530 
    [ 5.000,  7.500) = 633 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     20.000 ms/op
     p(99.9990) =     21.684 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.949 ms/op
                 getUser·p0.9999: 12.358 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.308 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.029 ms/op
                 getUser·p0.9999: 13.125 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  6.432 ms/op
                 getUser·p0.9999: 15.830 ms/op
                 getUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312960
  mean =      3.066 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1163 
    [ 1.250,  2.500) = 26865 
    [ 2.500,  3.750) = 260525 
    [ 3.750,  5.000) = 23615 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.415 ms/op
     p(99.9900) =     14.402 ms/op
     p(99.9990) =     16.455 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.011 ms/op
Iteration   1: 4.053 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  13.042 ms/op
                 listUser·p0.9999: 18.976 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 3.982 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.649 ms/op
                 listUser·p0.999:  13.447 ms/op
                 listUser·p0.9999: 15.696 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   3: 4.003 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.022 ms/op
                 listUser·p0.9999: 20.906 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239082
  mean =      4.013 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3893 
    [ 2.500,  5.000) = 206326 
    [ 5.000,  7.500) = 27686 
    [ 7.500, 10.000) = 769 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     13.610 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     21.064 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.240 ± 0.561  ops/ms
ClientGrpc.existUser                       thrpt       3  10.684 ± 2.457  ops/ms
ClientGrpc.getUser                         thrpt       3  10.381 ± 2.126  ops/ms
ClientGrpc.listUser                        thrpt       3   7.924 ± 0.955  ops/ms
ClientGrpc.createUser                       avgt       3   3.046 ± 1.376   ms/op
ClientGrpc.existUser                        avgt       3   2.985 ± 1.142   ms/op
ClientGrpc.getUser                          avgt       3   3.116 ± 0.326   ms/op
ClientGrpc.listUser                         avgt       3   4.047 ± 1.529   ms/op
ClientGrpc.createUser                     sample  304160   3.158 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.329           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.289           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.922           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.642           ms/op
ClientGrpc.existUser                      sample  326535   2.941 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.444           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.726           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.000           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.955           ms/op
ClientGrpc.getUser                        sample  312960   3.066 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.308           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.415           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.402           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.531           ms/op
ClientGrpc.listUser                       sample  239082   4.013 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.027           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.610           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.497           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.266           ms/op
