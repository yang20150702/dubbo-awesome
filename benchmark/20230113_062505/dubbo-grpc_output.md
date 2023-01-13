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
# Warmup Iteration   1: 4.379 ops/ms
# Warmup Iteration   2: 9.948 ops/ms
# Warmup Iteration   3: 10.236 ops/ms
Iteration   1: 10.330 ops/ms
Iteration   2: 10.328 ops/ms
Iteration   3: 10.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.316 ±(99.9%) 0.434 ops/ms [Average]
  (min, avg, max) = (10.288, 10.316, 10.330), stdev = 0.024
  CI (99.9%): [9.881, 10.750] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.904 ops/ms
# Warmup Iteration   2: 10.727 ops/ms
# Warmup Iteration   3: 10.693 ops/ms
Iteration   1: 10.763 ops/ms
Iteration   2: 10.942 ops/ms
Iteration   3: 10.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.876 ±(99.9%) 1.794 ops/ms [Average]
  (min, avg, max) = (10.763, 10.876, 10.942), stdev = 0.098
  CI (99.9%): [9.082, 12.670] (assumes normal distribution)


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
# Warmup Iteration   1: 7.699 ops/ms
# Warmup Iteration   2: 9.732 ops/ms
# Warmup Iteration   3: 10.429 ops/ms
Iteration   1: 10.387 ops/ms
Iteration   2: 10.424 ops/ms
Iteration   3: 10.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.428 ±(99.9%) 0.782 ops/ms [Average]
  (min, avg, max) = (10.387, 10.428, 10.473), stdev = 0.043
  CI (99.9%): [9.646, 11.210] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.837 ops/ms
# Warmup Iteration   2: 7.781 ops/ms
# Warmup Iteration   3: 7.955 ops/ms
Iteration   1: 8.264 ops/ms
Iteration   2: 8.530 ops/ms
Iteration   3: 8.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.276 ±(99.9%) 4.533 ops/ms [Average]
  (min, avg, max) = (8.034, 8.276, 8.530), stdev = 0.248
  CI (99.9%): [3.743, 12.809] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.002 ms/op
Iteration   1: 3.062 ±(99.9%) 0.003 ms/op
Iteration   2: 3.124 ±(99.9%) 0.002 ms/op
Iteration   3: 3.144 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.110 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.062, 3.110, 3.144), stdev = 0.043
  CI (99.9%): [2.324, 3.896] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.670 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.003 ms/op
Iteration   1: 2.942 ±(99.9%) 0.002 ms/op
Iteration   2: 2.941 ±(99.9%) 0.003 ms/op
Iteration   3: 2.924 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.936 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (2.924, 2.936, 2.942), stdev = 0.010
  CI (99.9%): [2.747, 3.124] (assumes normal distribution)


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.002 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 3.137 ±(99.9%) 0.002 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.073 ±(99.9%) 1.068 ms/op [Average]
  (min, avg, max) = (3.023, 3.073, 3.137), stdev = 0.059
  CI (99.9%): [2.004, 4.141] (assumes normal distribution)


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
# Warmup Iteration   1: 4.974 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.019 ms/op
Iteration   1: 3.991 ±(99.9%) 0.029 ms/op
Iteration   2: 4.082 ±(99.9%) 0.013 ms/op
Iteration   3: 4.027 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.033 ±(99.9%) 0.830 ms/op [Average]
  (min, avg, max) = (3.991, 4.033, 4.082), stdev = 0.045
  CI (99.9%): [3.203, 4.863] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
Iteration   1: 3.099 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.313 ms/op
                 createUser·p0.999:  6.226 ms/op
                 createUser·p0.9999: 20.917 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   2: 3.201 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 16.515 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  8.163 ms/op
                 createUser·p0.9999: 20.393 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309816
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25837 
    [ 2.500,  5.000) = 282948 
    [ 5.000,  7.500) = 649 
    [ 7.500, 10.000) = 188 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.159 ms/op
     p(99.9900) =     20.448 ms/op
     p(99.9990) =     21.227 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 3.639 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
Iteration   1: 2.935 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  5.848 ms/op
                 existUser·p0.9999: 13.146 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.525 ms/op
                 existUser·p0.9999: 14.047 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   3: 2.901 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.320 ms/op
                 existUser·p0.9999: 17.465 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327793
  mean =      2.929 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3988 
    [ 1.250,  2.500) = 47356 
    [ 2.500,  3.750) = 261100 
    [ 3.750,  5.000) = 14530 
    [ 5.000,  6.250) = 429 
    [ 6.250,  7.500) = 134 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      6.637 ms/op
     p(99.9900) =     15.876 ms/op
     p(99.9990) =     17.775 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 3.009 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 17.314 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.917 ms/op
                 getUser·p0.9999: 16.175 ms/op
                 getUser·p1.00:   16.712 ms/op

Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.229 ms/op
                 getUser·p0.9999: 18.077 ms/op
                 getUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312485
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1130 
    [ 1.250,  2.500) = 25905 
    [ 2.500,  3.750) = 260306 
    [ 3.750,  5.000) = 24092 
    [ 5.000,  6.250) = 505 
    [ 6.250,  7.500) = 229 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 74 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.549 ms/op
     p(99.9900) =     17.457 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 4.557 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.011 ms/op
Iteration   1: 3.975 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  12.525 ms/op
                 listUser·p0.9999: 16.776 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 4.157 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.123 ms/op
                 listUser·p0.999:  16.943 ms/op
                 listUser·p0.9999: 22.292 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   3: 4.079 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.315 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.894 ms/op
                 listUser·p0.9999: 26.662 ms/op
                 listUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235835
  mean =      4.069 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3408 
    [ 2.500,  5.000) = 196472 
    [ 5.000,  7.500) = 34537 
    [ 7.500, 10.000) = 901 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.315 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     15.223 ms/op
     p(99.9900) =     25.010 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.316 ± 0.434  ops/ms
ClientGrpc.existUser                       thrpt       3  10.876 ± 1.794  ops/ms
ClientGrpc.getUser                         thrpt       3  10.428 ± 0.782  ops/ms
ClientGrpc.listUser                        thrpt       3   8.276 ± 4.533  ops/ms
ClientGrpc.createUser                       avgt       3   3.110 ± 0.786   ms/op
ClientGrpc.existUser                        avgt       3   2.936 ± 0.189   ms/op
ClientGrpc.getUser                          avgt       3   3.073 ± 1.068   ms/op
ClientGrpc.listUser                         avgt       3   4.033 ± 0.830   ms/op
ClientGrpc.createUser                     sample  309816   3.099 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.676           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.159           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.448           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.365           ms/op
ClientGrpc.existUser                      sample  327793   2.929 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.621           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.637           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.876           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.924           ms/op
ClientGrpc.getUser                        sample  312485   3.071 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.639           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.549           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.457           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.448           ms/op
ClientGrpc.listUser                       sample  235835   4.069 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.315           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.223           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.010           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.968           ms/op
