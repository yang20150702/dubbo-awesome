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
# Warmup Iteration   1: 3.782 ops/ms
# Warmup Iteration   2: 8.571 ops/ms
# Warmup Iteration   3: 9.951 ops/ms
Iteration   1: 10.201 ops/ms
Iteration   2: 10.447 ops/ms
Iteration   3: 10.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.330 ±(99.9%) 2.245 ops/ms [Average]
  (min, avg, max) = (10.201, 10.330, 10.447), stdev = 0.123
  CI (99.9%): [8.085, 12.575] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.066 ops/ms
# Warmup Iteration   2: 10.320 ops/ms
# Warmup Iteration   3: 11.283 ops/ms
Iteration   1: 10.999 ops/ms
Iteration   2: 10.947 ops/ms
Iteration   3: 10.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.945 ±(99.9%) 1.017 ops/ms [Average]
  (min, avg, max) = (10.888, 10.945, 10.999), stdev = 0.056
  CI (99.9%): [9.928, 11.961] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.342 ops/ms
# Warmup Iteration   2: 9.961 ops/ms
# Warmup Iteration   3: 10.515 ops/ms
Iteration   1: 10.404 ops/ms
Iteration   2: 10.412 ops/ms
Iteration   3: 10.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.408 ±(99.9%) 0.074 ops/ms [Average]
  (min, avg, max) = (10.404, 10.408, 10.412), stdev = 0.004
  CI (99.9%): [10.334, 10.482] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.057 ops/ms
# Warmup Iteration   2: 7.580 ops/ms
# Warmup Iteration   3: 7.840 ops/ms
Iteration   1: 7.722 ops/ms
Iteration   2: 7.915 ops/ms
Iteration   3: 8.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.922 ±(99.9%) 3.732 ops/ms [Average]
  (min, avg, max) = (7.722, 7.922, 8.131), stdev = 0.205
  CI (99.9%): [4.190, 11.654] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.345 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.003 ms/op
Iteration   1: 3.032 ±(99.9%) 0.003 ms/op
Iteration   2: 3.009 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.024 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (3.009, 3.024, 3.032), stdev = 0.013
  CI (99.9%): [2.786, 3.262] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.020 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.003 ms/op
Iteration   1: 2.832 ±(99.9%) 0.002 ms/op
Iteration   2: 2.936 ±(99.9%) 0.001 ms/op
Iteration   3: 2.888 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.885 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (2.832, 2.885, 2.936), stdev = 0.052
  CI (99.9%): [1.931, 3.839] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.415 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.003 ms/op
Iteration   1: 3.063 ±(99.9%) 0.002 ms/op
Iteration   2: 3.107 ±(99.9%) 0.004 ms/op
Iteration   3: 3.058 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.076 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (3.058, 3.076, 3.107), stdev = 0.027
  CI (99.9%): [2.583, 3.569] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.693 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.014 ms/op
Iteration   1: 4.124 ±(99.9%) 0.012 ms/op
Iteration   2: 4.098 ±(99.9%) 0.028 ms/op
Iteration   3: 4.145 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.122 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (4.098, 4.122, 4.145), stdev = 0.023
  CI (99.9%): [3.697, 4.547] (assumes normal distribution)


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
# Warmup Iteration   1: 4.571 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  8.272 ms/op
                 createUser·p0.9999: 18.156 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.700 ms/op
                 createUser·p0.9999: 20.397 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   3: 3.110 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  8.654 ms/op
                 createUser·p0.9999: 26.238 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312431
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24069 
    [ 2.500,  5.000) = 286590 
    [ 5.000,  7.500) = 1313 
    [ 7.500, 10.000) = 228 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      8.208 ms/op
     p(99.9900) =     24.273 ms/op
     p(99.9990) =     26.862 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
Iteration   1: 2.907 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.733 ms/op
                 existUser·p0.9999: 13.877 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 2.901 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.328 ms/op
                 existUser·p0.9999: 26.477 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   3: 2.904 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.367 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  7.512 ms/op
                 existUser·p0.9999: 29.032 ms/op
                 existUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330483
  mean =      2.904 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34562 
    [ 2.500,  5.000) = 295006 
    [ 5.000,  7.500) = 663 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.184 ms/op
     p(99.9900) =     28.210 ms/op
     p(99.9990) =     29.360 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  8.725 ms/op
                 getUser·p0.9999: 14.647 ms/op
                 getUser·p1.00:   16.761 ms/op

Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  8.230 ms/op
                 getUser·p0.9999: 17.307 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.733 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.104 ms/op
                 getUser·p0.9999: 20.840 ms/op
                 getUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312885
  mean =      3.066 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14730 
    [ 2.500,  5.000) = 296714 
    [ 5.000,  7.500) = 1017 
    [ 7.500, 10.000) = 261 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     18.815 ms/op
     p(99.9990) =     21.197 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 6.106 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.011 ms/op
Iteration   1: 4.095 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  14.956 ms/op
                 listUser·p0.9999: 16.522 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 4.120 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 17.980 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   3: 4.097 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  16.351 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233894
  mean =      4.104 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1636 
    [ 2.500,  5.000) = 206214 
    [ 5.000,  7.500) = 24093 
    [ 7.500, 10.000) = 1467 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     21.254 ms/op
     p(99.9990) =     23.505 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.330 ± 2.245  ops/ms
ClientGrpc.existUser                       thrpt       3  10.945 ± 1.017  ops/ms
ClientGrpc.getUser                         thrpt       3  10.408 ± 0.074  ops/ms
ClientGrpc.listUser                        thrpt       3   7.922 ± 3.732  ops/ms
ClientGrpc.createUser                       avgt       3   3.024 ± 0.238   ms/op
ClientGrpc.existUser                        avgt       3   2.885 ± 0.954   ms/op
ClientGrpc.getUser                          avgt       3   3.076 ± 0.493   ms/op
ClientGrpc.listUser                         avgt       3   4.122 ± 0.425   ms/op
ClientGrpc.createUser                     sample  312431   3.071 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.744           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.208           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.273           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.099           ms/op
ClientGrpc.existUser                      sample  330483   2.904 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.667           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.184           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.210           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.458           ms/op
ClientGrpc.getUser                        sample  312885   3.066 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.679           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.815           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.332           ms/op
ClientGrpc.listUser                       sample  233894   4.104 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.795           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.307           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.565           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.254           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.658           ms/op
