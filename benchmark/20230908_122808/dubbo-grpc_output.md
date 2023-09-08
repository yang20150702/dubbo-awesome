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
# Warmup Iteration   1: 3.973 ops/ms
# Warmup Iteration   2: 8.495 ops/ms
# Warmup Iteration   3: 9.874 ops/ms
Iteration   1: 10.298 ops/ms
Iteration   2: 10.628 ops/ms
Iteration   3: 10.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.432 ±(99.9%) 3.159 ops/ms [Average]
  (min, avg, max) = (10.298, 10.432, 10.628), stdev = 0.173
  CI (99.9%): [7.273, 13.591] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.113 ops/ms
# Warmup Iteration   2: 10.411 ops/ms
# Warmup Iteration   3: 10.718 ops/ms
Iteration   1: 11.040 ops/ms
Iteration   2: 10.930 ops/ms
Iteration   3: 10.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.949 ±(99.9%) 1.514 ops/ms [Average]
  (min, avg, max) = (10.878, 10.949, 11.040), stdev = 0.083
  CI (99.9%): [9.436, 12.463] (assumes normal distribution)


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
# Warmup Iteration   1: 6.486 ops/ms
# Warmup Iteration   2: 9.672 ops/ms
# Warmup Iteration   3: 10.199 ops/ms
Iteration   1: 10.241 ops/ms
Iteration   2: 10.377 ops/ms
Iteration   3: 10.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.330 ±(99.9%) 1.404 ops/ms [Average]
  (min, avg, max) = (10.241, 10.330, 10.377), stdev = 0.077
  CI (99.9%): [8.926, 11.733] (assumes normal distribution)


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
# Warmup Iteration   1: 5.095 ops/ms
# Warmup Iteration   2: 7.556 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 7.887 ops/ms
Iteration   2: 7.833 ops/ms
Iteration   3: 7.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.853 ±(99.9%) 0.539 ops/ms [Average]
  (min, avg, max) = (7.833, 7.853, 7.887), stdev = 0.030
  CI (99.9%): [7.315, 8.392] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.553 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.003 ms/op
Iteration   1: 3.133 ±(99.9%) 0.003 ms/op
Iteration   2: 3.062 ±(99.9%) 0.003 ms/op
Iteration   3: 3.073 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.089 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (3.062, 3.089, 3.133), stdev = 0.038
  CI (99.9%): [2.396, 3.782] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.003 ms/op
Iteration   1: 2.910 ±(99.9%) 0.002 ms/op
Iteration   2: 2.951 ±(99.9%) 0.002 ms/op
Iteration   3: 2.919 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.927 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (2.910, 2.927, 2.951), stdev = 0.021
  CI (99.9%): [2.536, 3.318] (assumes normal distribution)


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.004 ms/op
Iteration   1: 3.156 ±(99.9%) 0.003 ms/op
Iteration   2: 3.079 ±(99.9%) 0.003 ms/op
Iteration   3: 3.029 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.088 ±(99.9%) 1.160 ms/op [Average]
  (min, avg, max) = (3.029, 3.088, 3.156), stdev = 0.064
  CI (99.9%): [1.928, 4.248] (assumes normal distribution)


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
# Warmup Iteration   1: 6.097 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.216 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.016 ms/op
Iteration   1: 4.011 ±(99.9%) 0.029 ms/op
Iteration   2: 4.046 ±(99.9%) 0.022 ms/op
Iteration   3: 3.888 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.982 ±(99.9%) 1.516 ms/op [Average]
  (min, avg, max) = (3.888, 3.982, 4.046), stdev = 0.083
  CI (99.9%): [2.466, 5.498] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  8.050 ms/op
                 createUser·p0.9999: 13.279 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.705 ms/op
                 createUser·p0.999:  8.636 ms/op
                 createUser·p0.9999: 14.696 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.362 ms/op
                 createUser·p0.999:  8.494 ms/op
                 createUser·p0.9999: 17.993 ms/op
                 createUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311485
  mean =      3.084 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 396 
    [ 1.250,  2.500) = 17660 
    [ 2.500,  3.750) = 272830 
    [ 3.750,  5.000) = 18679 
    [ 5.000,  6.250) = 874 
    [ 6.250,  7.500) = 469 
    [ 7.500,  8.750) = 310 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.319 ms/op
     p(99.9900) =     17.385 ms/op
     p(99.9990) =     18.375 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.006 ms/op
Iteration   1: 2.882 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.142 ms/op
                 existUser·p0.9999: 14.525 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.713 ms/op
                 existUser·p0.9999: 14.795 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   3: 2.924 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.749 ms/op
                 existUser·p0.9999: 23.630 ms/op
                 existUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326761
  mean =      2.938 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35377 
    [ 2.500,  5.000) = 289938 
    [ 5.000,  7.500) = 1019 
    [ 7.500, 10.000) = 203 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.948 ms/op
     p(99.9900) =     18.368 ms/op
     p(99.9990) =     23.936 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 4.217 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.782 ms/op
                 getUser·p0.999:  9.722 ms/op
                 getUser·p0.9999: 13.210 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  8.796 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.673 ms/op
                 getUser·p0.999:  8.789 ms/op
                 getUser·p0.9999: 24.728 ms/op
                 getUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310894
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18210 
    [ 2.500,  5.000) = 290533 
    [ 5.000,  7.500) = 1496 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      8.915 ms/op
     p(99.9900) =     24.263 ms/op
     p(99.9990) =     25.064 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 5.939 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.012 ms/op
Iteration   1: 4.178 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.043 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   2: 4.219 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.385 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.201 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  16.385 ms/op
                 listUser·p0.9999: 19.635 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 4.214 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  16.467 ms/op
                 listUser·p0.9999: 20.323 ms/op
                 listUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228432
  mean =      4.203 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1629 
    [ 2.500,  5.000) = 196071 
    [ 5.000,  7.500) = 28114 
    [ 7.500, 10.000) = 2026 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 204 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.385 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     19.928 ms/op
     p(99.9990) =     23.072 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.432 ± 3.159  ops/ms
ClientGrpc.existUser                       thrpt       3  10.949 ± 1.514  ops/ms
ClientGrpc.getUser                         thrpt       3  10.330 ± 1.404  ops/ms
ClientGrpc.listUser                        thrpt       3   7.853 ± 0.539  ops/ms
ClientGrpc.createUser                       avgt       3   3.089 ± 0.693   ms/op
ClientGrpc.existUser                        avgt       3   2.927 ± 0.391   ms/op
ClientGrpc.getUser                          avgt       3   3.088 ± 1.160   ms/op
ClientGrpc.listUser                         avgt       3   3.982 ± 1.516   ms/op
ClientGrpc.createUser                     sample  311485   3.084 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.691           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.319           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.385           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.481           ms/op
ClientGrpc.existUser                      sample  326761   2.938 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.579           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.948           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.368           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.084           ms/op
ClientGrpc.getUser                        sample  310894   3.087 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.744           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.915           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.263           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.100           ms/op
ClientGrpc.listUser                       sample  228432   4.203 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.385           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.998           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.218           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.643           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.155           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.928           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.953           ms/op
