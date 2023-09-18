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
# Warmup Iteration   1: 4.294 ops/ms
# Warmup Iteration   2: 9.206 ops/ms
# Warmup Iteration   3: 9.852 ops/ms
Iteration   1: 10.302 ops/ms
Iteration   2: 10.522 ops/ms
Iteration   3: 10.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.306 ±(99.9%) 3.926 ops/ms [Average]
  (min, avg, max) = (10.092, 10.306, 10.522), stdev = 0.215
  CI (99.9%): [6.380, 14.232] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.701 ops/ms
# Warmup Iteration   2: 10.478 ops/ms
# Warmup Iteration   3: 10.539 ops/ms
Iteration   1: 10.784 ops/ms
Iteration   2: 10.742 ops/ms
Iteration   3: 10.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.718 ±(99.9%) 1.481 ops/ms [Average]
  (min, avg, max) = (10.628, 10.718, 10.784), stdev = 0.081
  CI (99.9%): [9.237, 12.199] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.230 ops/ms
# Warmup Iteration   2: 10.202 ops/ms
# Warmup Iteration   3: 10.218 ops/ms
Iteration   1: 10.405 ops/ms
Iteration   2: 10.409 ops/ms
Iteration   3: 10.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.355 ±(99.9%) 1.664 ops/ms [Average]
  (min, avg, max) = (10.249, 10.355, 10.409), stdev = 0.091
  CI (99.9%): [8.690, 12.019] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.812 ops/ms
# Warmup Iteration   2: 8.247 ops/ms
# Warmup Iteration   3: 8.199 ops/ms
Iteration   1: 8.243 ops/ms
Iteration   2: 8.308 ops/ms
Iteration   3: 8.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.284 ±(99.9%) 0.648 ops/ms [Average]
  (min, avg, max) = (8.243, 8.284, 8.308), stdev = 0.036
  CI (99.9%): [7.636, 8.932] (assumes normal distribution)


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.008 ms/op
Iteration   1: 3.039 ±(99.9%) 0.003 ms/op
Iteration   2: 3.125 ±(99.9%) 0.002 ms/op
Iteration   3: 3.143 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.102 ±(99.9%) 1.016 ms/op [Average]
  (min, avg, max) = (3.039, 3.102, 3.143), stdev = 0.056
  CI (99.9%): [2.086, 4.119] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 2.956 ±(99.9%) 0.003 ms/op
Iteration   2: 2.940 ±(99.9%) 0.002 ms/op
Iteration   3: 3.032 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.976 ±(99.9%) 0.892 ms/op [Average]
  (min, avg, max) = (2.940, 2.976, 3.032), stdev = 0.049
  CI (99.9%): [2.083, 3.868] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.003 ms/op
Iteration   1: 3.071 ±(99.9%) 0.003 ms/op
Iteration   2: 3.106 ±(99.9%) 0.001 ms/op
Iteration   3: 3.126 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.101 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (3.071, 3.101, 3.126), stdev = 0.028
  CI (99.9%): [2.596, 3.606] (assumes normal distribution)


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
# Warmup Iteration   1: 5.097 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.809 ±(99.9%) 0.018 ms/op
Iteration   1: 3.856 ±(99.9%) 0.030 ms/op
Iteration   2: 3.744 ±(99.9%) 0.013 ms/op
Iteration   3: 3.749 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.783 ±(99.9%) 1.156 ms/op [Average]
  (min, avg, max) = (3.744, 3.783, 3.856), stdev = 0.063
  CI (99.9%): [2.628, 4.939] (assumes normal distribution)


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.005 ms/op
Iteration   1: 3.069 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  6.529 ms/op
                 createUser·p0.9999: 11.815 ms/op
                 createUser·p1.00:   12.042 ms/op

Iteration   2: 3.083 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  6.021 ms/op
                 createUser·p0.9999: 13.291 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.572 ms/op
                 createUser·p0.9999: 14.975 ms/op
                 createUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313048
  mean =      3.068 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 529 
    [ 1.250,  2.500) = 13955 
    [ 2.500,  3.750) = 281214 
    [ 3.750,  5.000) = 15989 
    [ 5.000,  6.250) = 903 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.150 ms/op
     p(99.9900) =     14.747 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  5.849 ms/op
                 existUser·p0.9999: 11.370 ms/op
                 existUser·p1.00:   11.731 ms/op

Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.896 ms/op
                 existUser·p0.9999: 12.275 ms/op
                 existUser·p1.00:   12.534 ms/op

Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  9.969 ms/op
                 existUser·p0.9999: 15.726 ms/op
                 existUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323818
  mean =      2.965 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 797 
    [ 1.250,  2.500) = 31618 
    [ 2.500,  3.750) = 280982 
    [ 3.750,  5.000) = 9045 
    [ 5.000,  6.250) = 750 
    [ 6.250,  7.500) = 197 
    [ 7.500,  8.750) = 134 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.382 ms/op
     p(99.9900) =     14.825 ms/op
     p(99.9990) =     16.077 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
Iteration   1: 3.145 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  8.639 ms/op
                 getUser·p0.9999: 11.876 ms/op
                 getUser·p1.00:   12.288 ms/op

Iteration   2: 3.115 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.060 ms/op
                 getUser·p0.9999: 12.988 ms/op
                 getUser·p1.00:   13.337 ms/op

Iteration   3: 3.114 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.488 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  8.490 ms/op
                 getUser·p0.9999: 15.635 ms/op
                 getUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307200
  mean =      3.125 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 561 
    [ 1.250,  2.500) = 7031 
    [ 2.500,  3.750) = 277016 
    [ 3.750,  5.000) = 21092 
    [ 5.000,  6.250) = 764 
    [ 6.250,  7.500) = 345 
    [ 7.500,  8.750) = 144 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.253 ms/op
     p(99.9900) =     14.635 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


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
# Warmup Iteration   1: 4.463 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.009 ms/op
Iteration   1: 3.858 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.255 ms/op
                 listUser·p0.9999: 15.142 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 3.802 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  12.924 ms/op
                 listUser·p0.9999: 15.614 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   3: 3.811 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.349 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 18.075 ms/op
                 listUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251179
  mean =      3.823 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 3267 
    [ 2.500,  3.750) = 125095 
    [ 3.750,  5.000) = 110635 
    [ 5.000,  6.250) = 8250 
    [ 6.250,  7.500) = 3022 
    [ 7.500,  8.750) = 322 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     18.218 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.306 ± 3.926  ops/ms
ClientGrpc.existUser                       thrpt       3  10.718 ± 1.481  ops/ms
ClientGrpc.getUser                         thrpt       3  10.355 ± 1.664  ops/ms
ClientGrpc.listUser                        thrpt       3   8.284 ± 0.648  ops/ms
ClientGrpc.createUser                       avgt       3   3.102 ± 1.016   ms/op
ClientGrpc.existUser                        avgt       3   2.976 ± 0.892   ms/op
ClientGrpc.getUser                          avgt       3   3.101 ± 0.505   ms/op
ClientGrpc.listUser                         avgt       3   3.783 ± 1.156   ms/op
ClientGrpc.createUser                     sample  313048   3.068 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.824           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.150           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.747           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.417           ms/op
ClientGrpc.existUser                      sample  323818   2.965 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.513           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.382           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.825           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.171           ms/op
ClientGrpc.getUser                        sample  307200   3.125 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.488           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.253           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.635           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.122           ms/op
ClientGrpc.listUser                       sample  251179   3.823 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.908           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.211           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.463           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.730           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.629           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.252           ms/op
