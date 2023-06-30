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
# Warmup Iteration   1: 2.350 ops/ms
# Warmup Iteration   2: 5.669 ops/ms
# Warmup Iteration   3: 6.928 ops/ms
Iteration   1: 7.372 ops/ms
Iteration   2: 7.099 ops/ms
Iteration   3: 7.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.322 ±(99.9%) 3.684 ops/ms [Average]
  (min, avg, max) = (7.099, 7.322, 7.494), stdev = 0.202
  CI (99.9%): [3.638, 11.006] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.890 ops/ms
# Warmup Iteration   2: 7.486 ops/ms
# Warmup Iteration   3: 7.830 ops/ms
Iteration   1: 7.670 ops/ms
Iteration   2: 7.922 ops/ms
Iteration   3: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.859 ±(99.9%) 3.037 ops/ms [Average]
  (min, avg, max) = (7.670, 7.859, 7.984), stdev = 0.166
  CI (99.9%): [4.822, 10.895] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ops/ms
# Warmup Iteration   2: 6.759 ops/ms
# Warmup Iteration   3: 7.272 ops/ms
Iteration   1: 7.497 ops/ms
Iteration   2: 7.624 ops/ms
Iteration   3: 7.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.622 ±(99.9%) 2.266 ops/ms [Average]
  (min, avg, max) = (7.497, 7.622, 7.746), stdev = 0.124
  CI (99.9%): [5.357, 9.888] (assumes normal distribution)


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
# Warmup Iteration   1: 3.954 ops/ms
# Warmup Iteration   2: 5.362 ops/ms
# Warmup Iteration   3: 5.723 ops/ms
Iteration   1: 5.803 ops/ms
Iteration   2: 6.142 ops/ms
Iteration   3: 5.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.921 ±(99.9%) 3.493 ops/ms [Average]
  (min, avg, max) = (5.803, 5.921, 6.142), stdev = 0.191
  CI (99.9%): [2.428, 9.414] (assumes normal distribution)


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
# Warmup Iteration   1: 6.591 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.455 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.005 ms/op
Iteration   1: 4.354 ±(99.9%) 0.002 ms/op
Iteration   2: 4.193 ±(99.9%) 0.003 ms/op
Iteration   3: 4.210 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.252 ±(99.9%) 1.615 ms/op [Average]
  (min, avg, max) = (4.193, 4.252, 4.354), stdev = 0.089
  CI (99.9%): [2.637, 5.867] (assumes normal distribution)


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
# Warmup Iteration   1: 5.627 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.004 ms/op
Iteration   1: 4.035 ±(99.9%) 0.003 ms/op
Iteration   2: 4.133 ±(99.9%) 0.006 ms/op
Iteration   3: 4.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.080 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (4.035, 4.080, 4.133), stdev = 0.049
  CI (99.9%): [3.179, 4.981] (assumes normal distribution)


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
# Warmup Iteration   1: 6.553 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.358 ±(99.9%) 0.003 ms/op
Iteration   1: 4.291 ±(99.9%) 0.007 ms/op
Iteration   2: 4.395 ±(99.9%) 0.004 ms/op
Iteration   3: 4.356 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.347 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (4.291, 4.347, 4.395), stdev = 0.052
  CI (99.9%): [3.390, 5.305] (assumes normal distribution)


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
# Warmup Iteration   1: 7.697 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.906 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.593 ±(99.9%) 0.025 ms/op
Iteration   1: 5.520 ±(99.9%) 0.028 ms/op
Iteration   2: 5.543 ±(99.9%) 0.011 ms/op
Iteration   3: 5.457 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.506 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (5.457, 5.506, 5.543), stdev = 0.044
  CI (99.9%): [4.698, 6.315] (assumes normal distribution)


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
# Warmup Iteration   1: 6.500 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.645 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.408 ±(99.9%) 0.011 ms/op
Iteration   1: 4.285 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   4.162 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.075 ms/op
                 createUser·p0.999:  13.293 ms/op
                 createUser·p0.9999: 15.773 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   2: 4.352 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  13.441 ms/op
                 createUser·p0.9999: 17.585 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   3: 4.226 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   4.178 ms/op
                 createUser·p0.90:   5.218 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  10.043 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 223935
  mean =      4.287 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 3180 
    [ 2.500,  3.750) = 54812 
    [ 3.750,  5.000) = 129322 
    [ 5.000,  6.250) = 32620 
    [ 6.250,  7.500) = 2578 
    [ 7.500,  8.750) = 695 
    [ 8.750, 10.000) = 283 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     12.895 ms/op
     p(99.9900) =     18.370 ms/op
     p(99.9990) =     19.163 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 5.966 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.301 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.011 ms/op
Iteration   1: 3.939 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   6.570 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 16.775 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   2: 4.012 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   3.932 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.243 ms/op
                 existUser·p0.99:   7.047 ms/op
                 existUser·p0.999:  12.456 ms/op
                 existUser·p0.9999: 18.319 ms/op
                 existUser·p1.00:   18.973 ms/op

Iteration   3: 4.085 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  12.668 ms/op
                 existUser·p0.9999: 20.453 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 239461
  mean =      4.011 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5112 
    [ 2.500,  5.000) = 216128 
    [ 5.000,  7.500) = 16870 
    [ 7.500, 10.000) = 903 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     12.117 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     20.834 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 6.098 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.730 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.388 ±(99.9%) 0.012 ms/op
Iteration   1: 4.378 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   5.841 ms/op
                 getUser·p0.99:   7.504 ms/op
                 getUser·p0.999:  15.219 ms/op
                 getUser·p0.9999: 17.849 ms/op
                 getUser·p1.00:   18.579 ms/op

Iteration   2: 4.345 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  12.435 ms/op
                 getUser·p0.9999: 16.548 ms/op
                 getUser·p1.00:   17.891 ms/op

Iteration   3: 4.395 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  12.342 ms/op
                 getUser·p0.9999: 21.496 ms/op
                 getUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 219506
  mean =      4.373 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2614 
    [ 2.500,  5.000) = 174097 
    [ 5.000,  7.500) = 40924 
    [ 7.500, 10.000) = 1339 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     13.279 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     23.241 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 7.781 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.821 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.608 ±(99.9%) 0.020 ms/op
Iteration   1: 5.578 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.907 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.364 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  15.842 ms/op
                 listUser·p0.9999: 19.350 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 5.661 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   7.389 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 21.263 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   3: 5.488 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.791 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  20.052 ms/op
                 listUser·p0.9999: 33.331 ms/op
                 listUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172131
  mean =      5.575 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 178 
    [ 2.500,  5.000) = 61679 
    [ 5.000,  7.500) = 95853 
    [ 7.500, 10.000) = 11800 
    [10.000, 12.500) = 1866 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.217 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     18.477 ms/op
     p(99.9900) =     30.795 ms/op
     p(99.9990) =     33.704 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.322 ± 3.684  ops/ms
ClientGrpc.existUser                       thrpt       3   7.859 ± 3.037  ops/ms
ClientGrpc.getUser                         thrpt       3   7.622 ± 2.266  ops/ms
ClientGrpc.listUser                        thrpt       3   5.921 ± 3.493  ops/ms
ClientGrpc.createUser                       avgt       3   4.252 ± 1.615   ms/op
ClientGrpc.existUser                        avgt       3   4.080 ± 0.901   ms/op
ClientGrpc.getUser                          avgt       3   4.347 ± 0.957   ms/op
ClientGrpc.listUser                         avgt       3   5.506 ± 0.808   ms/op
ClientGrpc.createUser                     sample  223935   4.287 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.858           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.276           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.636           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.783           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.895           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.370           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.202           ms/op
ClientGrpc.existUser                      sample  239461   4.011 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.547           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.858           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.226           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.685           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.117           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.104           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.972           ms/op
ClientGrpc.getUser                        sample  219506   4.373 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.997           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.431           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.225           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.279           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.218           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.462           ms/op
ClientGrpc.listUser                       sample  172131   5.575 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.458           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.217           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.682           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.477           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.795           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.751           ms/op
