# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ops/ms
# Warmup Iteration   2: 8.407 ops/ms
# Warmup Iteration   3: 9.939 ops/ms
Iteration   1: 9.824 ops/ms
Iteration   2: 9.787 ops/ms
Iteration   3: 9.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.870 ±(99.9%) 2.066 ops/ms [Average]
  (min, avg, max) = (9.787, 9.870, 9.999), stdev = 0.113
  CI (99.9%): [7.804, 11.936] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.262 ops/ms
# Warmup Iteration   2: 10.047 ops/ms
# Warmup Iteration   3: 10.490 ops/ms
Iteration   1: 10.148 ops/ms
Iteration   2: 10.257 ops/ms
Iteration   3: 10.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.270 ±(99.9%) 2.369 ops/ms [Average]
  (min, avg, max) = (10.148, 10.270, 10.406), stdev = 0.130
  CI (99.9%): [7.901, 12.639] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.184 ops/ms
# Warmup Iteration   2: 9.822 ops/ms
# Warmup Iteration   3: 9.771 ops/ms
Iteration   1: 10.061 ops/ms
Iteration   2: 9.751 ops/ms
Iteration   3: 9.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.910 ±(99.9%) 2.825 ops/ms [Average]
  (min, avg, max) = (9.751, 9.910, 10.061), stdev = 0.155
  CI (99.9%): [7.085, 12.735] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.143 ops/ms
# Warmup Iteration   2: 7.395 ops/ms
# Warmup Iteration   3: 7.734 ops/ms
Iteration   1: 7.819 ops/ms
Iteration   2: 7.620 ops/ms
Iteration   3: 7.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.719 ±(99.9%) 1.817 ops/ms [Average]
  (min, avg, max) = (7.620, 7.719, 7.819), stdev = 0.100
  CI (99.9%): [5.902, 9.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.583 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.002 ms/op
Iteration   1: 3.176 ±(99.9%) 0.003 ms/op
Iteration   2: 3.222 ±(99.9%) 0.002 ms/op
Iteration   3: 3.206 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.201 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (3.176, 3.201, 3.222), stdev = 0.023
  CI (99.9%): [2.774, 3.629] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.395 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.002 ms/op
Iteration   1: 3.122 ±(99.9%) 0.002 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 3.075 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.093 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (3.075, 3.093, 3.122), stdev = 0.025
  CI (99.9%): [2.630, 3.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.543 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.010 ms/op
Iteration   1: 3.249 ±(99.9%) 0.002 ms/op
Iteration   2: 3.202 ±(99.9%) 0.002 ms/op
Iteration   3: 3.206 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.219 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (3.202, 3.219, 3.249), stdev = 0.027
  CI (99.9%): [2.735, 3.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.297 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.462 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.010 ms/op
Iteration   1: 4.230 ±(99.9%) 0.021 ms/op
Iteration   2: 4.091 ±(99.9%) 0.024 ms/op
Iteration   3: 4.069 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.130 ±(99.9%) 1.584 ms/op [Average]
  (min, avg, max) = (4.069, 4.130, 4.230), stdev = 0.087
  CI (99.9%): [2.546, 5.714] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.339 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.006 ms/op
Iteration   1: 3.258 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.016 ms/op
                 createUser·p0.9999: 16.633 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   2: 3.272 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.892 ms/op
                 createUser·p0.9999: 19.478 ms/op
                 createUser·p1.00:   20.054 ms/op

Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  12.059 ms/op
                 createUser·p0.9999: 22.933 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294307
  mean =      3.261 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15375 
    [ 2.500,  5.000) = 277845 
    [ 5.000,  7.500) = 617 
    [ 7.500, 10.000) = 193 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      9.357 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.179 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
Iteration   1: 3.080 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.514 ms/op
                 existUser·p0.9999: 14.156 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   4.348 ms/op
                 existUser·p0.999:  8.370 ms/op
                 existUser·p0.9999: 15.848 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   3: 3.064 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.777 ms/op
                 existUser·p0.9999: 18.153 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 309217
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1040 
    [ 1.250,  2.500) = 29819 
    [ 2.500,  3.750) = 241945 
    [ 3.750,  5.000) = 35602 
    [ 5.000,  6.250) = 336 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.314 ms/op
     p(99.9900) =     16.949 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.384 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.007 ms/op
Iteration   1: 3.213 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  8.756 ms/op
                 getUser·p0.9999: 14.434 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 3.229 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  7.640 ms/op
                 getUser·p0.9999: 15.520 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   3: 3.236 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  6.353 ms/op
                 getUser·p0.9999: 17.440 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297612
  mean =      3.226 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 419 
    [ 1.250,  2.500) = 17724 
    [ 2.500,  3.750) = 231734 
    [ 3.750,  5.000) = 46335 
    [ 5.000,  6.250) = 812 
    [ 6.250,  7.500) = 226 
    [ 7.500,  8.750) = 146 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.900 ms/op
     p(99.9900) =     16.851 ms/op
     p(99.9990) =     17.696 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.765 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.012 ms/op
Iteration   1: 4.134 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.206 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  13.472 ms/op
                 listUser·p0.9999: 23.077 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 4.116 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 17.473 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 4.142 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  17.380 ms/op
                 listUser·p0.9999: 23.817 ms/op
                 listUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232288
  mean =      4.130 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1224 
    [ 2.500,  5.000) = 204323 
    [ 5.000,  7.500) = 25011 
    [ 7.500, 10.000) = 1282 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     15.626 ms/op
     p(99.9900) =     22.963 ms/op
     p(99.9990) =     24.239 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.870 ± 2.066  ops/ms
ClientGrpc.existUser                       thrpt       3  10.270 ± 2.369  ops/ms
ClientGrpc.getUser                         thrpt       3   9.910 ± 2.825  ops/ms
ClientGrpc.listUser                        thrpt       3   7.719 ± 1.817  ops/ms
ClientGrpc.createUser                       avgt       3   3.201 ± 0.427   ms/op
ClientGrpc.existUser                        avgt       3   3.093 ± 0.463   ms/op
ClientGrpc.getUser                          avgt       3   3.219 ± 0.484   ms/op
ClientGrpc.listUser                         avgt       3   4.130 ± 1.584   ms/op
ClientGrpc.createUser                     sample  294307   3.261 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.783           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.224           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.170           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.357           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.529           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.953           ms/op
ClientGrpc.existUser                      sample  309217   3.104 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.634           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.088           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.314           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.949           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.645           ms/op
ClientGrpc.getUser                        sample  297612   3.226 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.911           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.199           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.145           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.900           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.851           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.957           ms/op
ClientGrpc.listUser                       sample  232288   4.130 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.253           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.957           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.250           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.626           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.963           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.379           ms/op
