# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.641 ops/ms
# Warmup Iteration   2: 6.281 ops/ms
# Warmup Iteration   3: 7.301 ops/ms
Iteration   1: 7.883 ops/ms
Iteration   2: 7.789 ops/ms
Iteration   3: 8.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.896 ±(99.9%) 2.082 ops/ms [Average]
  (min, avg, max) = (7.789, 7.896, 8.016), stdev = 0.114
  CI (99.9%): [5.814, 9.978] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.381 ops/ms
# Warmup Iteration   2: 7.747 ops/ms
# Warmup Iteration   3: 8.618 ops/ms
Iteration   1: 8.704 ops/ms
Iteration   2: 8.370 ops/ms
Iteration   3: 8.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.544 ±(99.9%) 3.054 ops/ms [Average]
  (min, avg, max) = (8.370, 8.544, 8.704), stdev = 0.167
  CI (99.9%): [5.490, 11.598] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ops/ms
# Warmup Iteration   2: 6.740 ops/ms
# Warmup Iteration   3: 7.188 ops/ms
Iteration   1: 7.517 ops/ms
Iteration   2: 7.609 ops/ms
Iteration   3: 7.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.556 ±(99.9%) 0.872 ops/ms [Average]
  (min, avg, max) = (7.517, 7.556, 7.609), stdev = 0.048
  CI (99.9%): [6.684, 8.428] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.567 ops/ms
# Warmup Iteration   2: 5.569 ops/ms
# Warmup Iteration   3: 6.021 ops/ms
Iteration   1: 5.845 ops/ms
Iteration   2: 5.690 ops/ms
Iteration   3: 5.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.822 ±(99.9%) 2.217 ops/ms [Average]
  (min, avg, max) = (5.690, 5.822, 5.930), stdev = 0.122
  CI (99.9%): [3.604, 8.039] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.437 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.619 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.007 ms/op
Iteration   1: 4.341 ±(99.9%) 0.003 ms/op
Iteration   2: 4.307 ±(99.9%) 0.003 ms/op
Iteration   3: 4.319 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.322 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (4.307, 4.322, 4.341), stdev = 0.017
  CI (99.9%): [4.012, 4.632] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.763 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.003 ms/op
Iteration   1: 3.603 ±(99.9%) 0.002 ms/op
Iteration   2: 3.614 ±(99.9%) 0.002 ms/op
Iteration   3: 3.593 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.603 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (3.593, 3.603, 3.614), stdev = 0.010
  CI (99.9%): [3.419, 3.787] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.827 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.004 ms/op
Iteration   1: 3.890 ±(99.9%) 0.002 ms/op
Iteration   2: 3.944 ±(99.9%) 0.012 ms/op
Iteration   3: 3.966 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.934 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (3.890, 3.934, 3.966), stdev = 0.039
  CI (99.9%): [3.219, 4.648] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.427 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.400 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.184 ±(99.9%) 0.014 ms/op
Iteration   1: 5.073 ±(99.9%) 0.014 ms/op
Iteration   2: 5.009 ±(99.9%) 0.009 ms/op
Iteration   3: 5.059 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.047 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (5.009, 5.047, 5.073), stdev = 0.033
  CI (99.9%): [4.438, 5.656] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.054 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.296 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.012 ms/op
Iteration   1: 4.098 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   7.713 ms/op
                 createUser·p0.999:  11.468 ms/op
                 createUser·p0.9999: 18.619 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   2: 3.889 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   6.344 ms/op
                 createUser·p0.999:  12.141 ms/op
                 createUser·p0.9999: 16.766 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   3: 3.806 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  12.370 ms/op
                 createUser·p0.9999: 24.353 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244322
  mean =      3.927 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4249 
    [ 2.500,  5.000) = 221437 
    [ 5.000,  7.500) = 16876 
    [ 7.500, 10.000) = 1304 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     12.004 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     24.664 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.503 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
Iteration   1: 3.770 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  11.999 ms/op
                 existUser·p0.9999: 18.629 ms/op
                 existUser·p1.00:   18.842 ms/op

Iteration   2: 3.670 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  9.468 ms/op
                 existUser·p0.9999: 18.336 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   3: 3.672 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  11.680 ms/op
                 existUser·p0.9999: 17.606 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 259051
  mean =      3.704 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 4299 
    [ 2.500,  3.750) = 148901 
    [ 3.750,  5.000) = 94092 
    [ 5.000,  6.250) = 9524 
    [ 6.250,  7.500) = 1204 
    [ 7.500,  8.750) = 407 
    [ 8.750, 10.000) = 223 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     11.288 ms/op
     p(99.9900) =     18.353 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.182 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.011 ms/op
Iteration   1: 4.059 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   5.063 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  10.718 ms/op
                 getUser·p0.9999: 16.144 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   2: 4.026 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  10.520 ms/op
                 getUser·p0.9999: 20.352 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.960 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  9.830 ms/op
                 getUser·p0.9999: 18.839 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 239020
  mean =      4.015 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4827 
    [ 2.500,  5.000) = 209228 
    [ 5.000,  7.500) = 23370 
    [ 7.500, 10.000) = 1306 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     10.322 ms/op
     p(99.9900) =     19.074 ms/op
     p(99.9990) =     22.421 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.906 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.294 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.167 ±(99.9%) 0.020 ms/op
Iteration   1: 5.102 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  15.919 ms/op
                 listUser·p0.9999: 22.929 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 5.073 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.349 ms/op
                 listUser·p0.95:   7.168 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  17.945 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   3: 5.073 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   6.259 ms/op
                 listUser·p0.95:   7.160 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  19.239 ms/op
                 listUser·p0.9999: 21.856 ms/op
                 listUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 189034
  mean =      5.083 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 305 
    [ 2.500,  5.000) = 104786 
    [ 5.000,  7.500) = 76357 
    [ 7.500, 10.000) = 6658 
    [10.000, 12.500) = 563 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     16.973 ms/op
     p(99.9900) =     21.532 ms/op
     p(99.9990) =     24.087 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.896 ± 2.082  ops/ms
ClientGrpc.existUser                       thrpt       3   8.544 ± 3.054  ops/ms
ClientGrpc.getUser                         thrpt       3   7.556 ± 0.872  ops/ms
ClientGrpc.listUser                        thrpt       3   5.822 ± 2.217  ops/ms
ClientGrpc.createUser                       avgt       3   4.322 ± 0.310   ms/op
ClientGrpc.existUser                        avgt       3   3.603 ± 0.184   ms/op
ClientGrpc.getUser                          avgt       3   3.934 ± 0.715   ms/op
ClientGrpc.listUser                         avgt       3   5.047 ± 0.609   ms/op
ClientGrpc.createUser                     sample  244322   3.927 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.799           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.259           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.840           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.004           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.414           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.740           ms/op
ClientGrpc.existUser                      sample  259051   3.704 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.041           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.054           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.288           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.353           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.874           ms/op
ClientGrpc.getUser                        sample  239020   4.015 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.978           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.030           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.021           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.322           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.074           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.512           ms/op
ClientGrpc.listUser                       sample  189034   5.083 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.339           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.357           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.011           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.973           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.532           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.034           ms/op
