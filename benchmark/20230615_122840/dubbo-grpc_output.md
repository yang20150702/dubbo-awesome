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
# Warmup Iteration   1: 4.997 ops/ms
# Warmup Iteration   2: 9.554 ops/ms
# Warmup Iteration   3: 10.441 ops/ms
Iteration   1: 10.713 ops/ms
Iteration   2: 10.715 ops/ms
Iteration   3: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.716 ±(99.9%) 0.057 ops/ms [Average]
  (min, avg, max) = (10.713, 10.716, 10.719), stdev = 0.003
  CI (99.9%): [10.659, 10.772] (assumes normal distribution)


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
# Warmup Iteration   1: 8.531 ops/ms
# Warmup Iteration   2: 10.966 ops/ms
# Warmup Iteration   3: 11.408 ops/ms
Iteration   1: 11.263 ops/ms
Iteration   2: 11.357 ops/ms
Iteration   3: 11.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.291 ±(99.9%) 1.040 ops/ms [Average]
  (min, avg, max) = (11.253, 11.291, 11.357), stdev = 0.057
  CI (99.9%): [10.251, 12.331] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.198 ops/ms
# Warmup Iteration   2: 10.300 ops/ms
# Warmup Iteration   3: 10.676 ops/ms
Iteration   1: 10.722 ops/ms
Iteration   2: 10.742 ops/ms
Iteration   3: 10.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.698 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (10.630, 10.698, 10.742), stdev = 0.060
  CI (99.9%): [9.603, 11.792] (assumes normal distribution)


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
# Warmup Iteration   1: 5.922 ops/ms
# Warmup Iteration   2: 7.948 ops/ms
# Warmup Iteration   3: 8.190 ops/ms
Iteration   1: 8.288 ops/ms
Iteration   2: 8.351 ops/ms
Iteration   3: 8.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.270 ±(99.9%) 1.676 ops/ms [Average]
  (min, avg, max) = (8.170, 8.270, 8.351), stdev = 0.092
  CI (99.9%): [6.594, 9.945] (assumes normal distribution)


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.003 ms/op
Iteration   2: 2.973 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.999 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (2.973, 2.999, 3.016), stdev = 0.023
  CI (99.9%): [2.588, 3.410] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.808 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.828 ±(99.9%) 0.004 ms/op
Iteration   1: 2.876 ±(99.9%) 0.003 ms/op
Iteration   2: 2.873 ±(99.9%) 0.003 ms/op
Iteration   3: 2.863 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.871 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (2.863, 2.871, 2.876), stdev = 0.007
  CI (99.9%): [2.751, 2.991] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.003 ms/op
Iteration   1: 2.925 ±(99.9%) 0.003 ms/op
Iteration   2: 2.949 ±(99.9%) 0.003 ms/op
Iteration   3: 2.945 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.940 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (2.925, 2.940, 2.949), stdev = 0.013
  CI (99.9%): [2.704, 3.175] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.112 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.008 ms/op
Iteration   1: 3.860 ±(99.9%) 0.042 ms/op
Iteration   2: 3.887 ±(99.9%) 0.008 ms/op
Iteration   3: 3.741 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.829 ±(99.9%) 1.410 ms/op [Average]
  (min, avg, max) = (3.741, 3.829, 3.887), stdev = 0.077
  CI (99.9%): [2.419, 5.239] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.017 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.568 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.164 ms/op
                 createUser·p0.999:  6.278 ms/op
                 createUser·p0.9999: 12.441 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.979 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.178 ms/op
                 createUser·p0.9999: 15.730 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.096 ms/op
                 createUser·p0.999:  8.085 ms/op
                 createUser·p0.9999: 16.061 ms/op
                 createUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321320
  mean =      2.987 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1400 
    [ 1.250,  2.500) = 20476 
    [ 2.500,  3.750) = 287200 
    [ 3.750,  5.000) = 11307 
    [ 5.000,  6.250) = 422 
    [ 6.250,  7.500) = 148 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      8.009 ms/op
     p(99.9900) =     15.909 ms/op
     p(99.9990) =     17.141 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.797 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.006 ms/op
Iteration   1: 2.870 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  5.526 ms/op
                 existUser·p0.9999: 11.272 ms/op
                 existUser·p1.00:   11.518 ms/op

Iteration   2: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.019 ms/op
                 existUser·p0.999:  7.709 ms/op
                 existUser·p0.9999: 12.479 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   3: 2.819 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.587 ms/op
                 existUser·p0.9999: 16.843 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336692
  mean =      2.851 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3134 
    [ 1.250,  2.500) = 41720 
    [ 2.500,  3.750) = 283806 
    [ 3.750,  5.000) = 6895 
    [ 5.000,  6.250) = 644 
    [ 6.250,  7.500) = 182 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.416 ms/op
     p(99.9900) =     14.680 ms/op
     p(99.9990) =     17.114 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 4.126 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
Iteration   1: 2.996 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  8.720 ms/op
                 getUser·p0.9999: 18.416 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.291 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.195 ms/op
                 getUser·p0.999:  8.143 ms/op
                 getUser·p0.9999: 25.166 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  8.264 ms/op
                 getUser·p0.9999: 20.983 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318209
  mean =      3.017 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22639 
    [ 2.500,  5.000) = 294402 
    [ 5.000,  7.500) = 708 
    [ 7.500, 10.000) = 204 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.291 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      8.342 ms/op
     p(99.9900) =     23.637 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 4.162 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.008 ms/op
Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  12.042 ms/op
                 listUser·p0.9999: 14.251 ms/op
                 listUser·p1.00:   15.352 ms/op

Iteration   2: 3.853 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  12.911 ms/op
                 listUser·p0.9999: 16.708 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 3.910 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.634 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.665 ms/op
                 listUser·p0.999:  13.675 ms/op
                 listUser·p0.9999: 24.734 ms/op
                 listUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246503
  mean =      3.895 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6141 
    [ 2.500,  5.000) = 216167 
    [ 5.000,  7.500) = 23021 
    [ 7.500, 10.000) = 729 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     23.932 ms/op
     p(99.9990) =     24.954 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.716 ± 0.057  ops/ms
ClientGrpc.existUser                       thrpt       3  11.291 ± 1.040  ops/ms
ClientGrpc.getUser                         thrpt       3  10.698 ± 1.094  ops/ms
ClientGrpc.listUser                        thrpt       3   8.270 ± 1.676  ops/ms
ClientGrpc.createUser                       avgt       3   2.999 ± 0.411   ms/op
ClientGrpc.existUser                        avgt       3   2.871 ± 0.120   ms/op
ClientGrpc.getUser                          avgt       3   2.940 ± 0.236   ms/op
ClientGrpc.listUser                         avgt       3   3.829 ± 1.410   ms/op
ClientGrpc.createUser                     sample  321320   2.987 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.568           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.445           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.166           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.009           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.909           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.465           ms/op
ClientGrpc.existUser                      sample  336692   2.851 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.532           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.252           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.416           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.680           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.203           ms/op
ClientGrpc.getUser                        sample  318209   3.017 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.291           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.342           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.637           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.706           ms/op
ClientGrpc.listUser                       sample  246503   3.895 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.634           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.698           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.932           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.035           ms/op
