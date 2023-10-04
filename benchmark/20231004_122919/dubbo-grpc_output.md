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
# Warmup Iteration   1: 3.634 ops/ms
# Warmup Iteration   2: 8.430 ops/ms
# Warmup Iteration   3: 9.530 ops/ms
Iteration   1: 9.652 ops/ms
Iteration   2: 9.954 ops/ms
Iteration   3: 9.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.836 ±(99.9%) 2.946 ops/ms [Average]
  (min, avg, max) = (9.652, 9.836, 9.954), stdev = 0.161
  CI (99.9%): [6.890, 12.783] (assumes normal distribution)


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
# Warmup Iteration   1: 6.959 ops/ms
# Warmup Iteration   2: 9.752 ops/ms
# Warmup Iteration   3: 10.296 ops/ms
Iteration   1: 10.702 ops/ms
Iteration   2: 10.642 ops/ms
Iteration   3: 10.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.618 ±(99.9%) 1.806 ops/ms [Average]
  (min, avg, max) = (10.509, 10.618, 10.702), stdev = 0.099
  CI (99.9%): [8.811, 12.424] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.410 ops/ms
# Warmup Iteration   2: 9.632 ops/ms
# Warmup Iteration   3: 9.839 ops/ms
Iteration   1: 9.939 ops/ms
Iteration   2: 9.779 ops/ms
Iteration   3: 10.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.933 ±(99.9%) 2.741 ops/ms [Average]
  (min, avg, max) = (9.779, 9.933, 10.079), stdev = 0.150
  CI (99.9%): [7.192, 12.673] (assumes normal distribution)


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
# Warmup Iteration   1: 5.149 ops/ms
# Warmup Iteration   2: 7.553 ops/ms
# Warmup Iteration   3: 7.935 ops/ms
Iteration   1: 7.910 ops/ms
Iteration   2: 7.897 ops/ms
Iteration   3: 7.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.927 ±(99.9%) 0.743 ops/ms [Average]
  (min, avg, max) = (7.897, 7.927, 7.973), stdev = 0.041
  CI (99.9%): [7.183, 8.670] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.765 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.002 ms/op
Iteration   1: 3.342 ±(99.9%) 0.004 ms/op
Iteration   2: 3.253 ±(99.9%) 0.003 ms/op
Iteration   3: 3.307 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.301 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.253, 3.301, 3.342), stdev = 0.045
  CI (99.9%): [2.485, 4.116] (assumes normal distribution)


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.002 ms/op
Iteration   1: 3.055 ±(99.9%) 0.005 ms/op
Iteration   2: 3.030 ±(99.9%) 0.003 ms/op
Iteration   3: 2.951 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.012 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (2.951, 3.012, 3.055), stdev = 0.054
  CI (99.9%): [2.022, 4.002] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.768 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.006 ms/op
Iteration   1: 3.170 ±(99.9%) 0.004 ms/op
Iteration   2: 3.156 ±(99.9%) 0.006 ms/op
Iteration   3: 3.255 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.193 ±(99.9%) 0.977 ms/op [Average]
  (min, avg, max) = (3.156, 3.193, 3.255), stdev = 0.054
  CI (99.9%): [2.217, 4.170] (assumes normal distribution)


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
# Warmup Iteration   1: 5.967 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.009 ms/op
Iteration   1: 4.113 ±(99.9%) 0.016 ms/op
Iteration   2: 4.117 ±(99.9%) 0.025 ms/op
Iteration   3: 4.112 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.114 ±(99.9%) 0.049 ms/op [Average]
  (min, avg, max) = (4.112, 4.114, 4.117), stdev = 0.003
  CI (99.9%): [4.065, 4.163] (assumes normal distribution)


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.007 ms/op
Iteration   1: 3.242 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  12.730 ms/op
                 createUser·p0.9999: 25.170 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  10.206 ms/op
                 createUser·p0.9999: 24.628 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.213 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.136 ms/op
                 createUser·p0.999:  15.630 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299260
  mean =      3.209 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8181 
    [ 2.500,  5.000) = 288106 
    [ 5.000,  7.500) = 2262 
    [ 7.500, 10.000) = 286 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.989 ms/op
     p(99.9000) =     13.541 ms/op
     p(99.9900) =     25.135 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.743 ms/op
                 existUser·p0.999:  8.329 ms/op
                 existUser·p0.9999: 13.649 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  8.118 ms/op
                 existUser·p0.9999: 17.701 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  12.267 ms/op
                 existUser·p0.9999: 19.716 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311868
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15076 
    [ 2.500,  5.000) = 294387 
    [ 5.000,  7.500) = 1777 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      9.034 ms/op
     p(99.9900) =     17.486 ms/op
     p(99.9990) =     20.804 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 4.781 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.007 ms/op
Iteration   1: 3.174 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.063 ms/op
                 getUser·p0.999:  8.065 ms/op
                 getUser·p0.9999: 13.812 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  13.629 ms/op
                 getUser·p0.9999: 24.052 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   3: 3.209 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  8.789 ms/op
                 getUser·p0.9999: 25.100 ms/op
                 getUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301323
  mean =      3.188 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11264 
    [ 2.500,  5.000) = 286995 
    [ 5.000,  7.500) = 2501 
    [ 7.500, 10.000) = 273 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     25.330 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 5.145 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.343 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.010 ms/op
Iteration   1: 4.065 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  14.484 ms/op
                 listUser·p0.9999: 25.526 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 4.001 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 4.008 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   7.128 ms/op
                 listUser·p0.999:  16.568 ms/op
                 listUser·p0.9999: 21.168 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238397
  mean =      4.024 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1520 
    [ 2.500,  5.000) = 220883 
    [ 5.000,  7.500) = 14277 
    [ 7.500, 10.000) = 989 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.408 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     21.915 ms/op
     p(99.9990) =     25.632 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.836 ± 2.946  ops/ms
ClientGrpc.existUser                       thrpt       3  10.618 ± 1.806  ops/ms
ClientGrpc.getUser                         thrpt       3   9.933 ± 2.741  ops/ms
ClientGrpc.listUser                        thrpt       3   7.927 ± 0.743  ops/ms
ClientGrpc.createUser                       avgt       3   3.301 ± 0.815   ms/op
ClientGrpc.existUser                        avgt       3   3.012 ± 0.990   ms/op
ClientGrpc.getUser                          avgt       3   3.193 ± 0.977   ms/op
ClientGrpc.listUser                         avgt       3   4.114 ± 0.049   ms/op
ClientGrpc.createUser                     sample  299260   3.209 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.708           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.989           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.541           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.135           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.296           ms/op
ClientGrpc.existUser                      sample  311868   3.079 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.724           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.035           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.743           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.034           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.486           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.972           ms/op
ClientGrpc.getUser                        sample  301323   3.188 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.650           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.014           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.535           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.019           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.428           ms/op
ClientGrpc.listUser                       sample  238397   4.024 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.897           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.408           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.270           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.915           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.788           ms/op
