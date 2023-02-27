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
# Warmup Iteration   1: 4.766 ops/ms
# Warmup Iteration   2: 9.440 ops/ms
# Warmup Iteration   3: 10.172 ops/ms
Iteration   1: 10.744 ops/ms
Iteration   2: 10.285 ops/ms
Iteration   3: 10.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.662 ±(99.9%) 6.256 ops/ms [Average]
  (min, avg, max) = (10.285, 10.662, 10.956), stdev = 0.343
  CI (99.9%): [4.406, 16.918] (assumes normal distribution)


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
# Warmup Iteration   1: 9.767 ops/ms
# Warmup Iteration   2: 10.864 ops/ms
# Warmup Iteration   3: 10.785 ops/ms
Iteration   1: 11.143 ops/ms
Iteration   2: 10.667 ops/ms
Iteration   3: 10.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.905 ±(99.9%) 4.343 ops/ms [Average]
  (min, avg, max) = (10.667, 10.905, 11.143), stdev = 0.238
  CI (99.9%): [6.562, 15.249] (assumes normal distribution)


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
# Warmup Iteration   1: 7.307 ops/ms
# Warmup Iteration   2: 10.756 ops/ms
# Warmup Iteration   3: 10.521 ops/ms
Iteration   1: 10.739 ops/ms
Iteration   2: 10.446 ops/ms
Iteration   3: 10.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.525 ±(99.9%) 3.405 ops/ms [Average]
  (min, avg, max) = (10.391, 10.525, 10.739), stdev = 0.187
  CI (99.9%): [7.120, 13.931] (assumes normal distribution)


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
# Warmup Iteration   1: 5.888 ops/ms
# Warmup Iteration   2: 7.854 ops/ms
# Warmup Iteration   3: 7.752 ops/ms
Iteration   1: 7.944 ops/ms
Iteration   2: 8.357 ops/ms
Iteration   3: 7.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.064 ±(99.9%) 4.651 ops/ms [Average]
  (min, avg, max) = (7.891, 8.064, 8.357), stdev = 0.255
  CI (99.9%): [3.413, 12.714] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.032 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.002 ms/op
Iteration   1: 3.114 ±(99.9%) 0.001 ms/op
Iteration   2: 3.098 ±(99.9%) 0.002 ms/op
Iteration   3: 3.099 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.104 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (3.098, 3.104, 3.114), stdev = 0.009
  CI (99.9%): [2.939, 3.269] (assumes normal distribution)


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
# Warmup Iteration   1: 3.785 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.003 ms/op
Iteration   1: 2.966 ±(99.9%) 0.003 ms/op
Iteration   2: 2.986 ±(99.9%) 0.003 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.972 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.963, 2.972, 2.986), stdev = 0.012
  CI (99.9%): [2.747, 3.196] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.002 ms/op
Iteration   1: 3.109 ±(99.9%) 0.002 ms/op
Iteration   2: 3.031 ±(99.9%) 0.002 ms/op
Iteration   3: 3.158 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.100 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (3.031, 3.100, 3.158), stdev = 0.064
  CI (99.9%): [1.935, 4.264] (assumes normal distribution)


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.024 ms/op
Iteration   1: 4.008 ±(99.9%) 0.050 ms/op
Iteration   2: 3.734 ±(99.9%) 0.026 ms/op
Iteration   3: 4.083 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.941 ±(99.9%) 3.354 ms/op [Average]
  (min, avg, max) = (3.734, 3.941, 4.083), stdev = 0.184
  CI (99.9%): [0.588, 7.295] (assumes normal distribution)


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
# Warmup Iteration   1: 4.389 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
Iteration   1: 3.124 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  9.668 ms/op
                 createUser·p0.9999: 15.139 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   2: 3.183 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.118 ms/op
                 createUser·p0.9999: 15.987 ms/op
                 createUser·p1.00:   16.564 ms/op

Iteration   3: 3.169 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.803 ms/op
                 createUser·p0.9999: 30.957 ms/op
                 createUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303837
  mean =      3.159 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18629 
    [ 2.500,  5.000) = 283630 
    [ 5.000,  7.500) = 1171 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     29.590 ms/op
     p(99.9990) =     31.842 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.008 ms/op
Iteration   1: 3.002 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  8.602 ms/op
                 existUser·p0.9999: 17.805 ms/op
                 existUser·p1.00:   18.350 ms/op

Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.987 ms/op
                 existUser·p0.9999: 23.069 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  8.091 ms/op
                 existUser·p0.9999: 13.821 ms/op
                 existUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314820
  mean =      3.049 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31222 
    [ 2.500,  5.000) = 282588 
    [ 5.000,  7.500) = 660 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.941 ms/op
     p(99.9900) =     21.000 ms/op
     p(99.9990) =     23.485 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
Iteration   1: 3.100 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.911 ms/op
                 getUser·p0.9999: 12.087 ms/op
                 getUser·p1.00:   12.386 ms/op

Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.377 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  9.008 ms/op
                 getUser·p0.9999: 12.979 ms/op
                 getUser·p1.00:   13.304 ms/op

Iteration   3: 3.163 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.102 ms/op
                 getUser·p0.9999: 13.621 ms/op
                 getUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308536
  mean =      3.111 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1222 
    [ 1.250,  2.500) = 20138 
    [ 2.500,  3.750) = 257421 
    [ 3.750,  5.000) = 28763 
    [ 5.000,  6.250) = 555 
    [ 6.250,  7.500) = 153 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.188 ms/op
     p(99.9900) =     13.014 ms/op
     p(99.9990) =     15.331 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 5.528 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.011 ms/op
Iteration   1: 4.091 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  13.252 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   2: 3.993 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  21.942 ms/op
                 listUser·p0.9999: 25.919 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   3: 4.078 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.099 ms/op
                 listUser·p0.9999: 25.875 ms/op
                 listUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236732
  mean =      4.054 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3371 
    [ 2.500,  5.000) = 205788 
    [ 5.000,  7.500) = 26061 
    [ 7.500, 10.000) = 1005 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     25.372 ms/op
     p(99.9990) =     26.789 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.662 ± 6.256  ops/ms
ClientGrpc.existUser                       thrpt       3  10.905 ± 4.343  ops/ms
ClientGrpc.getUser                         thrpt       3  10.525 ± 3.405  ops/ms
ClientGrpc.listUser                        thrpt       3   8.064 ± 4.651  ops/ms
ClientGrpc.createUser                       avgt       3   3.104 ± 0.165   ms/op
ClientGrpc.existUser                        avgt       3   2.972 ± 0.225   ms/op
ClientGrpc.getUser                          avgt       3   3.100 ± 1.165   ms/op
ClientGrpc.listUser                         avgt       3   3.941 ± 3.354   ms/op
ClientGrpc.createUser                     sample  303837   3.159 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.567           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.733           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.590           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.113           ms/op
ClientGrpc.existUser                      sample  314820   3.049 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.526           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.941           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.000           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.593           ms/op
ClientGrpc.getUser                        sample  308536   3.111 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.377           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.188           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.014           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.434           ms/op
ClientGrpc.listUser                       sample  236732   4.054 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.096           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.372           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.066           ms/op
