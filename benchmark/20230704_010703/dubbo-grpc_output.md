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
# Warmup Iteration   1: 4.117 ops/ms
# Warmup Iteration   2: 8.544 ops/ms
# Warmup Iteration   3: 9.875 ops/ms
Iteration   1: 10.240 ops/ms
Iteration   2: 10.259 ops/ms
Iteration   3: 10.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.299 ±(99.9%) 1.559 ops/ms [Average]
  (min, avg, max) = (10.240, 10.299, 10.397), stdev = 0.085
  CI (99.9%): [8.740, 11.857] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.130 ops/ms
# Warmup Iteration   2: 10.379 ops/ms
# Warmup Iteration   3: 10.970 ops/ms
Iteration   1: 10.992 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.820 ±(99.9%) 2.840 ops/ms [Average]
  (min, avg, max) = (10.689, 10.820, 10.992), stdev = 0.156
  CI (99.9%): [7.980, 13.659] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.004 ops/ms
# Warmup Iteration   2: 9.841 ops/ms
# Warmup Iteration   3: 10.127 ops/ms
Iteration   1: 10.302 ops/ms
Iteration   2: 10.412 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.389 ±(99.9%) 1.415 ops/ms [Average]
  (min, avg, max) = (10.302, 10.389, 10.452), stdev = 0.078
  CI (99.9%): [8.974, 11.804] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.805 ops/ms
# Warmup Iteration   2: 7.170 ops/ms
# Warmup Iteration   3: 7.665 ops/ms
Iteration   1: 7.784 ops/ms
Iteration   2: 7.940 ops/ms
Iteration   3: 7.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.866 ±(99.9%) 1.426 ops/ms [Average]
  (min, avg, max) = (7.784, 7.866, 7.940), stdev = 0.078
  CI (99.9%): [6.441, 9.292] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.570 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.002 ms/op
Iteration   1: 3.080 ±(99.9%) 0.003 ms/op
Iteration   2: 3.047 ±(99.9%) 0.001 ms/op
Iteration   3: 3.076 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.068 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.047, 3.068, 3.080), stdev = 0.018
  CI (99.9%): [2.745, 3.390] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.311 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.002 ms/op
Iteration   1: 2.916 ±(99.9%) 0.002 ms/op
Iteration   2: 2.889 ±(99.9%) 0.002 ms/op
Iteration   3: 2.905 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.904 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (2.889, 2.904, 2.916), stdev = 0.014
  CI (99.9%): [2.656, 3.151] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.171 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.002 ms/op
Iteration   1: 3.134 ±(99.9%) 0.003 ms/op
Iteration   2: 3.067 ±(99.9%) 0.001 ms/op
Iteration   3: 3.056 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.086 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (3.056, 3.086, 3.134), stdev = 0.042
  CI (99.9%): [2.316, 3.856] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.222 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.011 ms/op
Iteration   1: 4.109 ±(99.9%) 0.006 ms/op
Iteration   2: 3.965 ±(99.9%) 0.017 ms/op
Iteration   3: 4.119 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.064 ±(99.9%) 1.566 ms/op [Average]
  (min, avg, max) = (3.965, 4.064, 4.119), stdev = 0.086
  CI (99.9%): [2.499, 5.630] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.455 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
Iteration   1: 3.053 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.358 ms/op
                 createUser·p0.9999: 27.230 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.521 ms/op
                 createUser·p0.999:  8.417 ms/op
                 createUser·p0.9999: 23.265 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  8.946 ms/op
                 createUser·p0.9999: 25.821 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305853
  mean =      3.137 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11504 
    [ 2.500,  5.000) = 292792 
    [ 5.000,  7.500) = 1179 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.095 ms/op
     p(99.9900) =     26.490 ms/op
     p(99.9990) =     28.271 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.162 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.890 ms/op
                 existUser·p0.9999: 13.176 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   2: 2.924 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.980 ms/op
                 existUser·p0.9999: 15.697 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  6.521 ms/op
                 existUser·p0.9999: 29.630 ms/op
                 existUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325091
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22864 
    [ 2.500,  5.000) = 301078 
    [ 5.000,  7.500) = 896 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.062 ms/op
     p(99.9900) =     23.444 ms/op
     p(99.9990) =     29.884 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.450 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.006 ms/op
Iteration   1: 3.075 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  9.077 ms/op
                 getUser·p0.9999: 13.871 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 3.071 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.374 ms/op
                 getUser·p0.999:  6.896 ms/op
                 getUser·p0.9999: 14.446 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   3: 3.141 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.339 ms/op
                 getUser·p0.9999: 18.737 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310029
  mean =      3.095 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12646 
    [ 2.500,  5.000) = 295795 
    [ 5.000,  7.500) = 1244 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.905 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     20.149 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 5.425 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.012 ms/op
Iteration   1: 4.108 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.238 ms/op
                 listUser·p0.999:  15.125 ms/op
                 listUser·p0.9999: 24.354 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   2: 4.187 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.323 ms/op
                 listUser·p0.999:  15.507 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 4.095 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 26.325 ms/op
                 listUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232502
  mean =      4.130 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1141 
    [ 2.500,  5.000) = 203885 
    [ 5.000,  7.500) = 25803 
    [ 7.500, 10.000) = 1265 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     15.999 ms/op
     p(99.9900) =     25.387 ms/op
     p(99.9990) =     26.531 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.299 ± 1.559  ops/ms
ClientGrpc.existUser                       thrpt       3  10.820 ± 2.840  ops/ms
ClientGrpc.getUser                         thrpt       3  10.389 ± 1.415  ops/ms
ClientGrpc.listUser                        thrpt       3   7.866 ± 1.426  ops/ms
ClientGrpc.createUser                       avgt       3   3.068 ± 0.322   ms/op
ClientGrpc.existUser                        avgt       3   2.904 ± 0.248   ms/op
ClientGrpc.getUser                          avgt       3   3.086 ± 0.770   ms/op
ClientGrpc.listUser                         avgt       3   4.064 ± 1.566   ms/op
ClientGrpc.createUser                     sample  305853   3.137 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.769           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.095           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.490           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.869           ms/op
ClientGrpc.existUser                      sample  325091   2.952 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.568           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.062           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.444           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.917           ms/op
ClientGrpc.getUser                        sample  310029   3.095 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.786           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.905           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.826           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.283           ms/op
ClientGrpc.listUser                       sample  232502   4.130 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.004           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.949           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.999           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.387           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.575           ms/op
