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
# Warmup Iteration   1: 3.733 ops/ms
# Warmup Iteration   2: 8.288 ops/ms
# Warmup Iteration   3: 9.560 ops/ms
Iteration   1: 10.159 ops/ms
Iteration   2: 10.119 ops/ms
Iteration   3: 10.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.179 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (10.119, 10.179, 10.260), stdev = 0.073
  CI (99.9%): [8.852, 11.506] (assumes normal distribution)


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
# Warmup Iteration   1: 7.161 ops/ms
# Warmup Iteration   2: 10.290 ops/ms
# Warmup Iteration   3: 10.371 ops/ms
Iteration   1: 10.701 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.753 ±(99.9%) 1.028 ops/ms [Average]
  (min, avg, max) = (10.701, 10.753, 10.813), stdev = 0.056
  CI (99.9%): [9.726, 11.781] (assumes normal distribution)


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
# Warmup Iteration   1: 6.726 ops/ms
# Warmup Iteration   2: 9.783 ops/ms
# Warmup Iteration   3: 10.053 ops/ms
Iteration   1: 10.275 ops/ms
Iteration   2: 10.217 ops/ms
Iteration   3: 10.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.220 ±(99.9%) 0.981 ops/ms [Average]
  (min, avg, max) = (10.168, 10.220, 10.275), stdev = 0.054
  CI (99.9%): [9.239, 11.201] (assumes normal distribution)


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
# Warmup Iteration   1: 5.306 ops/ms
# Warmup Iteration   2: 7.914 ops/ms
# Warmup Iteration   3: 8.016 ops/ms
Iteration   1: 7.988 ops/ms
Iteration   2: 7.902 ops/ms
Iteration   3: 8.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.976 ±(99.9%) 1.260 ops/ms [Average]
  (min, avg, max) = (7.902, 7.976, 8.038), stdev = 0.069
  CI (99.9%): [6.716, 9.236] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.002 ms/op
Iteration   1: 3.292 ±(99.9%) 0.008 ms/op
Iteration   2: 3.102 ±(99.9%) 0.001 ms/op
Iteration   3: 3.170 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.188 ±(99.9%) 1.755 ms/op [Average]
  (min, avg, max) = (3.102, 3.188, 3.292), stdev = 0.096
  CI (99.9%): [1.434, 4.943] (assumes normal distribution)


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.002 ms/op
Iteration   1: 2.970 ±(99.9%) 0.002 ms/op
Iteration   2: 2.991 ±(99.9%) 0.003 ms/op
Iteration   3: 3.056 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.006 ±(99.9%) 0.822 ms/op [Average]
  (min, avg, max) = (2.970, 3.006, 3.056), stdev = 0.045
  CI (99.9%): [2.184, 3.827] (assumes normal distribution)


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.002 ms/op
Iteration   1: 3.234 ±(99.9%) 0.002 ms/op
Iteration   2: 3.178 ±(99.9%) 0.002 ms/op
Iteration   3: 3.209 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.207 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (3.178, 3.207, 3.234), stdev = 0.028
  CI (99.9%): [2.694, 3.720] (assumes normal distribution)


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
# Warmup Iteration   1: 5.316 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.011 ms/op
Iteration   1: 3.970 ±(99.9%) 0.021 ms/op
Iteration   2: 3.967 ±(99.9%) 0.021 ms/op
Iteration   3: 3.964 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.967 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (3.964, 3.967, 3.970), stdev = 0.003
  CI (99.9%): [3.911, 4.023] (assumes normal distribution)


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
# Warmup Iteration   1: 4.593 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.383 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.006 ms/op
Iteration   1: 3.190 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.449 ms/op
                 createUser·p0.999:  7.980 ms/op
                 createUser·p0.9999: 13.319 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.684 ms/op
                 createUser·p0.999:  7.356 ms/op
                 createUser·p0.9999: 14.234 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   3: 3.175 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  11.018 ms/op
                 createUser·p0.9999: 18.115 ms/op
                 createUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303132
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 309 
    [ 1.250,  2.500) = 10416 
    [ 2.500,  3.750) = 263055 
    [ 3.750,  5.000) = 27250 
    [ 5.000,  6.250) = 1180 
    [ 6.250,  7.500) = 471 
    [ 7.500,  8.750) = 160 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.476 ms/op
     p(99.9900) =     17.390 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
Iteration   1: 3.048 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.324 ms/op
                 existUser·p0.9999: 13.205 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.431 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.676 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  8.282 ms/op
                 existUser·p0.9999: 14.070 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   3: 2.972 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  9.191 ms/op
                 existUser·p0.9999: 15.518 ms/op
                 existUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318879
  mean =      3.012 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 359 
    [ 1.250,  2.500) = 17015 
    [ 2.500,  3.750) = 289886 
    [ 3.750,  5.000) = 10185 
    [ 5.000,  6.250) = 567 
    [ 6.250,  7.500) = 413 
    [ 7.500,  8.750) = 167 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.053 ms/op
     p(99.9900) =     14.507 ms/op
     p(99.9990) =     16.430 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.492 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
Iteration   1: 3.138 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.115 ms/op
                 getUser·p0.9999: 18.114 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 3.181 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  8.862 ms/op
                 getUser·p0.9999: 17.791 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  8.245 ms/op
                 getUser·p0.9999: 20.808 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305017
  mean =      3.145 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5732 
    [ 2.500,  5.000) = 297835 
    [ 5.000,  7.500) = 1062 
    [ 7.500, 10.000) = 225 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.946 ms/op
     p(99.9900) =     20.332 ms/op
     p(99.9990) =     21.689 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 5.724 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.011 ms/op
Iteration   1: 4.023 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 22.315 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   2: 3.918 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  15.168 ms/op
                 listUser·p0.9999: 17.558 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 3.913 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.651 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242930
  mean =      3.951 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2056 
    [ 2.500,  5.000) = 227408 
    [ 5.000,  7.500) = 12074 
    [ 7.500, 10.000) = 799 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     21.945 ms/op
     p(99.9990) =     24.946 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.179 ± 1.327  ops/ms
ClientGrpc.existUser                       thrpt       3  10.753 ± 1.028  ops/ms
ClientGrpc.getUser                         thrpt       3  10.220 ± 0.981  ops/ms
ClientGrpc.listUser                        thrpt       3   7.976 ± 1.260  ops/ms
ClientGrpc.createUser                       avgt       3   3.188 ± 1.755   ms/op
ClientGrpc.existUser                        avgt       3   3.006 ± 0.822   ms/op
ClientGrpc.getUser                          avgt       3   3.207 ± 0.513   ms/op
ClientGrpc.listUser                         avgt       3   3.967 ± 0.056   ms/op
ClientGrpc.createUser                     sample  303132   3.167 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.767           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.476           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.390           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.448           ms/op
ClientGrpc.existUser                      sample  318879   3.012 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.431           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.053           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.507           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.138           ms/op
ClientGrpc.getUser                        sample  305017   3.145 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.580           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.946           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.332           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.856           ms/op
ClientGrpc.listUser                       sample  242930   3.951 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.041           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.945           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.002           ms/op
