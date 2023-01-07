# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.888 ops/ms
# Warmup Iteration   2: 9.237 ops/ms
# Warmup Iteration   3: 10.649 ops/ms
Iteration   1: 11.229 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.851 ±(99.9%) 5.992 ops/ms [Average]
  (min, avg, max) = (10.635, 10.851, 11.229), stdev = 0.328
  CI (99.9%): [4.860, 16.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.210 ops/ms
# Warmup Iteration   2: 10.855 ops/ms
# Warmup Iteration   3: 11.066 ops/ms
Iteration   1: 10.862 ops/ms
Iteration   2: 10.985 ops/ms
Iteration   3: 10.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.891 ±(99.9%) 1.527 ops/ms [Average]
  (min, avg, max) = (10.825, 10.891, 10.985), stdev = 0.084
  CI (99.9%): [9.364, 12.418] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.585 ops/ms
# Warmup Iteration   2: 10.516 ops/ms
# Warmup Iteration   3: 10.543 ops/ms
Iteration   1: 10.711 ops/ms
Iteration   2: 10.581 ops/ms
Iteration   3: 10.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.664 ±(99.9%) 1.313 ops/ms [Average]
  (min, avg, max) = (10.581, 10.664, 10.711), stdev = 0.072
  CI (99.9%): [9.351, 11.978] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.346 ops/ms
# Warmup Iteration   2: 7.958 ops/ms
# Warmup Iteration   3: 7.973 ops/ms
Iteration   1: 8.228 ops/ms
Iteration   2: 8.099 ops/ms
Iteration   3: 8.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.169 ±(99.9%) 1.187 ops/ms [Average]
  (min, avg, max) = (8.099, 8.169, 8.228), stdev = 0.065
  CI (99.9%): [6.982, 9.357] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.002 ms/op
Iteration   1: 2.935 ±(99.9%) 0.005 ms/op
Iteration   2: 2.960 ±(99.9%) 0.003 ms/op
Iteration   3: 3.020 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.972 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (2.935, 2.972, 3.020), stdev = 0.044
  CI (99.9%): [2.178, 3.765] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.691 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.918 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.004 ms/op
Iteration   1: 2.902 ±(99.9%) 0.003 ms/op
Iteration   2: 2.911 ±(99.9%) 0.002 ms/op
Iteration   3: 2.843 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.885 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (2.843, 2.885, 2.911), stdev = 0.037
  CI (99.9%): [2.212, 3.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.818 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.003 ms/op
Iteration   2: 3.021 ±(99.9%) 0.002 ms/op
Iteration   3: 3.115 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.069 ±(99.9%) 0.861 ms/op [Average]
  (min, avg, max) = (3.021, 3.069, 3.115), stdev = 0.047
  CI (99.9%): [2.207, 3.930] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.025 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.026 ms/op
Iteration   1: 4.009 ±(99.9%) 0.027 ms/op
Iteration   2: 3.900 ±(99.9%) 0.008 ms/op
Iteration   3: 3.879 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.929 ±(99.9%) 1.271 ms/op [Average]
  (min, avg, max) = (3.879, 3.929, 4.009), stdev = 0.070
  CI (99.9%): [2.659, 5.200] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  6.309 ms/op
                 createUser·p0.9999: 17.039 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  6.691 ms/op
                 createUser·p0.9999: 13.260 ms/op
                 createUser·p1.00:   13.615 ms/op

Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.443 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  7.473 ms/op
                 createUser·p0.9999: 15.761 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315379
  mean =      3.045 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1349 
    [ 1.250,  2.500) = 20257 
    [ 2.500,  3.750) = 277560 
    [ 3.750,  5.000) = 15498 
    [ 5.000,  6.250) = 312 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.777 ms/op
     p(99.9900) =     16.712 ms/op
     p(99.9990) =     17.460 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.943 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  6.938 ms/op
                 existUser·p0.9999: 12.920 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   2: 2.894 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  5.259 ms/op
                 existUser·p0.9999: 12.567 ms/op
                 existUser·p1.00:   12.878 ms/op

Iteration   3: 2.871 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 15.986 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329986
  mean =      2.907 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2628 
    [ 1.250,  2.500) = 51303 
    [ 2.500,  3.750) = 263955 
    [ 3.750,  5.000) = 11225 
    [ 5.000,  6.250) = 403 
    [ 6.250,  7.500) = 229 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     13.830 ms/op
     p(99.9990) =     17.764 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.968 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
Iteration   1: 3.057 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  9.385 ms/op
                 getUser·p0.9999: 16.032 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  7.147 ms/op
                 getUser·p0.9999: 31.733 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  9.286 ms/op
                 getUser·p0.9999: 20.195 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313761
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29726 
    [ 2.500,  5.000) = 283155 
    [ 5.000,  7.500) = 441 
    [ 7.500, 10.000) = 194 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.786 ms/op
     p(99.9900) =     30.450 ms/op
     p(99.9990) =     32.005 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.270 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.235 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.012 ms/op
Iteration   1: 4.081 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  12.485 ms/op
                 listUser·p0.9999: 16.649 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   2: 4.092 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  14.432 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 4.075 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  16.487 ms/op
                 listUser·p0.9999: 24.117 ms/op
                 listUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234970
  mean =      4.083 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3873 
    [ 2.500,  5.000) = 191425 
    [ 5.000,  7.500) = 38076 
    [ 7.500, 10.000) = 1218 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     14.108 ms/op
     p(99.9900) =     20.922 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.851 ± 5.992  ops/ms
ClientGrpc.existUser                       thrpt       3  10.891 ± 1.527  ops/ms
ClientGrpc.getUser                         thrpt       3  10.664 ± 1.313  ops/ms
ClientGrpc.listUser                        thrpt       3   8.169 ± 1.187  ops/ms
ClientGrpc.createUser                       avgt       3   2.972 ± 0.794   ms/op
ClientGrpc.existUser                        avgt       3   2.885 ± 0.673   ms/op
ClientGrpc.getUser                          avgt       3   3.069 ± 0.861   ms/op
ClientGrpc.listUser                         avgt       3   3.929 ± 1.271   ms/op
ClientGrpc.createUser                     sample  315379   3.045 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.443           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.777           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.712           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.727           ms/op
ClientGrpc.existUser                      sample  329986   2.907 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.672           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.881           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.830           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.891           ms/op
ClientGrpc.getUser                        sample  313761   3.058 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.636           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.786           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.450           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.145           ms/op
ClientGrpc.listUser                       sample  234970   4.083 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.761           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.108           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.922           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.281           ms/op
