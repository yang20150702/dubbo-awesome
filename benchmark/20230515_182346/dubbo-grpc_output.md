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
# Warmup Iteration   1: 4.819 ops/ms
# Warmup Iteration   2: 9.936 ops/ms
# Warmup Iteration   3: 10.456 ops/ms
Iteration   1: 10.876 ops/ms
Iteration   2: 10.905 ops/ms
Iteration   3: 10.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.869 ±(99.9%) 0.728 ops/ms [Average]
  (min, avg, max) = (10.826, 10.869, 10.905), stdev = 0.040
  CI (99.9%): [10.141, 11.597] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.543 ops/ms
# Warmup Iteration   2: 11.005 ops/ms
# Warmup Iteration   3: 11.374 ops/ms
Iteration   1: 11.778 ops/ms
Iteration   2: 11.576 ops/ms
Iteration   3: 11.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.574 ±(99.9%) 3.721 ops/ms [Average]
  (min, avg, max) = (11.370, 11.574, 11.778), stdev = 0.204
  CI (99.9%): [7.853, 15.296] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.759 ops/ms
# Warmup Iteration   2: 10.465 ops/ms
# Warmup Iteration   3: 11.042 ops/ms
Iteration   1: 10.977 ops/ms
Iteration   2: 10.888 ops/ms
Iteration   3: 11.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.965 ±(99.9%) 1.315 ops/ms [Average]
  (min, avg, max) = (10.888, 10.965, 11.031), stdev = 0.072
  CI (99.9%): [9.650, 12.280] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.194 ops/ms
# Warmup Iteration   2: 8.434 ops/ms
# Warmup Iteration   3: 8.526 ops/ms
Iteration   1: 8.377 ops/ms
Iteration   2: 8.605 ops/ms
Iteration   3: 8.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.525 ±(99.9%) 2.345 ops/ms [Average]
  (min, avg, max) = (8.377, 8.525, 8.605), stdev = 0.129
  CI (99.9%): [6.180, 10.870] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.733 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.003 ms/op
Iteration   1: 2.884 ±(99.9%) 0.004 ms/op
Iteration   2: 2.938 ±(99.9%) 0.003 ms/op
Iteration   3: 2.926 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.916 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (2.884, 2.916, 2.938), stdev = 0.028
  CI (99.9%): [2.397, 3.435] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.492 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.848 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.793 ±(99.9%) 0.003 ms/op
Iteration   1: 2.780 ±(99.9%) 0.003 ms/op
Iteration   2: 2.807 ±(99.9%) 0.003 ms/op
Iteration   3: 2.781 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.790 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (2.780, 2.790, 2.807), stdev = 0.015
  CI (99.9%): [2.510, 3.070] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.727 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.003 ms/op
Iteration   1: 2.964 ±(99.9%) 0.002 ms/op
Iteration   2: 2.973 ±(99.9%) 0.004 ms/op
Iteration   3: 2.972 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.970 ±(99.9%) 0.084 ms/op [Average]
  (min, avg, max) = (2.964, 2.970, 2.973), stdev = 0.005
  CI (99.9%): [2.885, 3.054] (assumes normal distribution)


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.830 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.008 ms/op
Iteration   1: 3.791 ±(99.9%) 0.041 ms/op
Iteration   2: 3.787 ±(99.9%) 0.018 ms/op
Iteration   3: 3.698 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.759 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (3.698, 3.759, 3.791), stdev = 0.053
  CI (99.9%): [2.792, 4.725] (assumes normal distribution)


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.427 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.638 ms/op
                 createUser·p0.9999: 19.727 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   2: 2.904 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  8.035 ms/op
                 createUser·p0.9999: 14.369 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   3: 2.933 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.568 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.256 ms/op
                 createUser·p0.95:   3.498 ms/op
                 createUser·p0.99:   4.088 ms/op
                 createUser·p0.999:  9.142 ms/op
                 createUser·p0.9999: 26.378 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 328858
  mean =      2.917 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35836 
    [ 2.500,  5.000) = 292073 
    [ 5.000,  7.500) = 491 
    [ 7.500, 10.000) = 189 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.427 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     20.691 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 3.671 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.848 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.829 ±(99.9%) 0.005 ms/op
Iteration   1: 2.846 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  5.755 ms/op
                 existUser·p0.9999: 13.078 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   2: 2.768 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.781 ms/op
                 existUser·p0.90:   3.121 ms/op
                 existUser·p0.95:   3.285 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.275 ms/op
                 existUser·p0.9999: 13.042 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.799 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.798 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.342 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.605 ms/op
                 existUser·p0.9999: 13.353 ms/op
                 existUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 342403
  mean =      2.804 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2891 
    [ 1.250,  2.500) = 57955 
    [ 2.500,  3.750) = 273530 
    [ 3.750,  5.000) = 7327 
    [ 5.000,  6.250) = 373 
    [ 6.250,  7.500) = 122 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.236 ms/op
     p(95.0000) =      3.486 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.128 ms/op
     p(99.9900) =     13.185 ms/op
     p(99.9990) =     13.545 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
Iteration   1: 2.859 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   2.875 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.313 ms/op
                 getUser·p0.9999: 14.959 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  7.246 ms/op
                 getUser·p0.9999: 14.490 ms/op
                 getUser·p1.00:   16.302 ms/op

Iteration   3: 2.892 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   2.900 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.036 ms/op
                 getUser·p0.9999: 16.757 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 330303
  mean =      2.904 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2561 
    [ 1.250,  2.500) = 44013 
    [ 2.500,  3.750) = 270860 
    [ 3.750,  5.000) = 11497 
    [ 5.000,  6.250) = 935 
    [ 6.250,  7.500) = 179 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.748 ms/op
     p(99.9900) =     16.271 ms/op
     p(99.9990) =     18.396 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 4.915 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.010 ms/op
Iteration   1: 3.754 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.333 ms/op
                 listUser·p0.999:  11.498 ms/op
                 listUser·p0.9999: 18.628 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   2: 3.731 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  12.498 ms/op
                 listUser·p0.9999: 15.382 ms/op
                 listUser·p1.00:   15.696 ms/op

Iteration   3: 3.771 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  15.097 ms/op
                 listUser·p0.9999: 20.612 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 255709
  mean =      3.752 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5369 
    [ 2.500,  5.000) = 233599 
    [ 5.000,  7.500) = 15962 
    [ 7.500, 10.000) = 373 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     12.866 ms/op
     p(99.9900) =     19.834 ms/op
     p(99.9990) =     21.179 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.869 ± 0.728  ops/ms
ClientGrpc.existUser                       thrpt       3  11.574 ± 3.721  ops/ms
ClientGrpc.getUser                         thrpt       3  10.965 ± 1.315  ops/ms
ClientGrpc.listUser                        thrpt       3   8.525 ± 2.345  ops/ms
ClientGrpc.createUser                       avgt       3   2.916 ± 0.519   ms/op
ClientGrpc.existUser                        avgt       3   2.790 ± 0.280   ms/op
ClientGrpc.getUser                          avgt       3   2.970 ± 0.084   ms/op
ClientGrpc.listUser                         avgt       3   3.759 ± 0.966   ms/op
ClientGrpc.createUser                     sample  328858   2.917 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.427           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.904           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.363           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.651           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.691           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.640           ms/op
ClientGrpc.existUser                      sample  342403   2.804 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.611           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.798           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.236           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.128           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.185           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.402           ms/op
ClientGrpc.getUser                        sample  330303   2.904 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.667           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.908           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.748           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.271           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.416           ms/op
ClientGrpc.listUser                       sample  255709   3.752 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.629           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.390           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.866           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.834           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.299           ms/op
