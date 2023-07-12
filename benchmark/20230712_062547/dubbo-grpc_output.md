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
# Warmup Iteration   1: 3.707 ops/ms
# Warmup Iteration   2: 8.802 ops/ms
# Warmup Iteration   3: 9.994 ops/ms
Iteration   1: 10.697 ops/ms
Iteration   2: 10.403 ops/ms
Iteration   3: 10.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.496 ±(99.9%) 3.170 ops/ms [Average]
  (min, avg, max) = (10.389, 10.496, 10.697), stdev = 0.174
  CI (99.9%): [7.327, 13.666] (assumes normal distribution)


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
# Warmup Iteration   1: 7.582 ops/ms
# Warmup Iteration   2: 10.447 ops/ms
# Warmup Iteration   3: 10.003 ops/ms
Iteration   1: 10.147 ops/ms
Iteration   2: 10.269 ops/ms
Iteration   3: 10.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.260 ±(99.9%) 1.985 ops/ms [Average]
  (min, avg, max) = (10.147, 10.260, 10.364), stdev = 0.109
  CI (99.9%): [8.275, 12.244] (assumes normal distribution)


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
# Warmup Iteration   1: 5.657 ops/ms
# Warmup Iteration   2: 9.028 ops/ms
# Warmup Iteration   3: 9.427 ops/ms
Iteration   1: 9.760 ops/ms
Iteration   2: 9.346 ops/ms
Iteration   3: 9.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.595 ±(99.9%) 4.005 ops/ms [Average]
  (min, avg, max) = (9.346, 9.595, 9.760), stdev = 0.220
  CI (99.9%): [5.590, 13.600] (assumes normal distribution)


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
# Warmup Iteration   1: 4.593 ops/ms
# Warmup Iteration   2: 6.826 ops/ms
# Warmup Iteration   3: 7.362 ops/ms
Iteration   1: 7.368 ops/ms
Iteration   2: 7.365 ops/ms
Iteration   3: 7.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.372 ±(99.9%) 0.172 ops/ms [Average]
  (min, avg, max) = (7.365, 7.372, 7.382), stdev = 0.009
  CI (99.9%): [7.199, 7.544] (assumes normal distribution)


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
# Warmup Iteration   1: 4.741 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.002 ms/op
Iteration   1: 3.356 ±(99.9%) 0.004 ms/op
Iteration   2: 3.264 ±(99.9%) 0.002 ms/op
Iteration   3: 3.234 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.285 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (3.234, 3.285, 3.356), stdev = 0.064
  CI (99.9%): [2.117, 4.452] (assumes normal distribution)


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
# Warmup Iteration   1: 4.500 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.137 ±(99.9%) 0.002 ms/op
Iteration   2: 3.008 ±(99.9%) 0.004 ms/op
Iteration   3: 3.076 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.074 ±(99.9%) 1.173 ms/op [Average]
  (min, avg, max) = (3.008, 3.074, 3.137), stdev = 0.064
  CI (99.9%): [1.901, 4.247] (assumes normal distribution)


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.002 ms/op
Iteration   1: 3.132 ±(99.9%) 0.003 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.083 ±(99.9%) 0.780 ms/op [Average]
  (min, avg, max) = (3.055, 3.083, 3.132), stdev = 0.043
  CI (99.9%): [2.304, 3.863] (assumes normal distribution)


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
# Warmup Iteration   1: 6.378 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.620 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.283 ±(99.9%) 0.013 ms/op
Iteration   1: 4.379 ±(99.9%) 0.016 ms/op
Iteration   2: 4.287 ±(99.9%) 0.019 ms/op
Iteration   3: 4.183 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.283 ±(99.9%) 1.792 ms/op [Average]
  (min, avg, max) = (4.183, 4.283, 4.379), stdev = 0.098
  CI (99.9%): [2.491, 6.075] (assumes normal distribution)


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
# Warmup Iteration   1: 4.908 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.007 ms/op
Iteration   1: 3.261 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  10.108 ms/op
                 createUser·p0.9999: 13.749 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 3.303 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  8.766 ms/op
                 createUser·p0.9999: 14.505 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   3: 3.318 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.481 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  7.911 ms/op
                 createUser·p0.9999: 26.849 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 291430
  mean =      3.293 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7607 
    [ 2.500,  5.000) = 281786 
    [ 5.000,  7.500) = 1587 
    [ 7.500, 10.000) = 216 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     27.039 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 4.642 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.007 ms/op
Iteration   1: 3.224 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.010 ms/op
                 existUser·p0.9999: 22.615 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.137 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.307 ms/op
                 existUser·p0.9999: 15.574 ms/op
                 existUser·p1.00:   15.860 ms/op

Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  10.240 ms/op
                 existUser·p0.9999: 18.466 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 305984
  mean =      3.137 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9472 
    [ 2.500,  5.000) = 295105 
    [ 5.000,  7.500) = 978 
    [ 7.500, 10.000) = 219 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.504 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     22.934 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.326 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.008 ms/op
Iteration   1: 3.346 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  7.745 ms/op
                 getUser·p0.9999: 14.252 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   2: 3.280 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  7.590 ms/op
                 getUser·p0.9999: 22.953 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 3.184 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  6.925 ms/op
                 getUser·p0.9999: 18.315 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 293614
  mean =      3.269 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13097 
    [ 2.500,  5.000) = 278233 
    [ 5.000,  7.500) = 1984 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      7.556 ms/op
     p(99.9900) =     22.095 ms/op
     p(99.9990) =     23.269 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 6.415 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.598 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.012 ms/op
Iteration   1: 4.263 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  14.663 ms/op
                 listUser·p0.9999: 23.085 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   2: 4.289 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   4.121 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.357 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  14.963 ms/op
                 listUser·p0.9999: 19.383 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 4.518 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  18.223 ms/op
                 listUser·p0.9999: 33.483 ms/op
                 listUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 220611
  mean =      4.354 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1109 
    [ 2.500,  5.000) = 184742 
    [ 5.000,  7.500) = 32466 
    [ 7.500, 10.000) = 1800 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      4.157 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      6.250 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     15.243 ms/op
     p(99.9900) =     31.720 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.496 ± 3.170  ops/ms
ClientGrpc.existUser                       thrpt       3  10.260 ± 1.985  ops/ms
ClientGrpc.getUser                         thrpt       3   9.595 ± 4.005  ops/ms
ClientGrpc.listUser                        thrpt       3   7.372 ± 0.172  ops/ms
ClientGrpc.createUser                       avgt       3   3.285 ± 1.167   ms/op
ClientGrpc.existUser                        avgt       3   3.074 ± 1.173   ms/op
ClientGrpc.getUser                          avgt       3   3.083 ± 0.780   ms/op
ClientGrpc.listUser                         avgt       3   4.283 ± 1.792   ms/op
ClientGrpc.createUser                     sample  291430   3.293 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.481           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.260           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.071           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.962           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.214           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.165           ms/op
ClientGrpc.existUser                      sample  305984   3.137 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.113           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.504           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.020           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.069           ms/op
ClientGrpc.getUser                        sample  293614   3.269 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.696           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.240           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.088           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.556           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.095           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.364           ms/op
ClientGrpc.listUser                       sample  220611   4.354 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.155           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.157           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.250           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.537           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.243           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.720           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.882           ms/op
