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
# Warmup Iteration   1: 4.159 ops/ms
# Warmup Iteration   2: 9.011 ops/ms
# Warmup Iteration   3: 9.885 ops/ms
Iteration   1: 10.057 ops/ms
Iteration   2: 10.119 ops/ms
Iteration   3: 9.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.050 ±(99.9%) 1.338 ops/ms [Average]
  (min, avg, max) = (9.973, 10.050, 10.119), stdev = 0.073
  CI (99.9%): [8.712, 11.388] (assumes normal distribution)


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
# Warmup Iteration   1: 7.332 ops/ms
# Warmup Iteration   2: 9.874 ops/ms
# Warmup Iteration   3: 10.279 ops/ms
Iteration   1: 10.285 ops/ms
Iteration   2: 10.542 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.428 ±(99.9%) 2.383 ops/ms [Average]
  (min, avg, max) = (10.285, 10.428, 10.542), stdev = 0.131
  CI (99.9%): [8.046, 12.811] (assumes normal distribution)


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
# Warmup Iteration   1: 6.391 ops/ms
# Warmup Iteration   2: 9.616 ops/ms
# Warmup Iteration   3: 9.790 ops/ms
Iteration   1: 9.702 ops/ms
Iteration   2: 9.974 ops/ms
Iteration   3: 9.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.821 ±(99.9%) 2.536 ops/ms [Average]
  (min, avg, max) = (9.702, 9.821, 9.974), stdev = 0.139
  CI (99.9%): [7.285, 12.356] (assumes normal distribution)


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
# Warmup Iteration   1: 5.741 ops/ms
# Warmup Iteration   2: 7.303 ops/ms
# Warmup Iteration   3: 7.751 ops/ms
Iteration   1: 7.675 ops/ms
Iteration   2: 7.604 ops/ms
Iteration   3: 7.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.648 ±(99.9%) 0.705 ops/ms [Average]
  (min, avg, max) = (7.604, 7.648, 7.675), stdev = 0.039
  CI (99.9%): [6.943, 8.353] (assumes normal distribution)


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.002 ms/op
Iteration   1: 3.156 ±(99.9%) 0.004 ms/op
Iteration   2: 3.241 ±(99.9%) 0.003 ms/op
Iteration   3: 3.260 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.219 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (3.156, 3.219, 3.260), stdev = 0.056
  CI (99.9%): [2.205, 4.233] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.002 ms/op
Iteration   1: 3.004 ±(99.9%) 0.002 ms/op
Iteration   2: 3.061 ±(99.9%) 0.001 ms/op
Iteration   3: 3.074 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.046 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.004, 3.046, 3.074), stdev = 0.037
  CI (99.9%): [2.363, 3.730] (assumes normal distribution)


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
# Warmup Iteration   1: 4.509 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.002 ms/op
Iteration   1: 3.191 ±(99.9%) 0.002 ms/op
Iteration   2: 3.197 ±(99.9%) 0.002 ms/op
Iteration   3: 3.205 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.198 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (3.191, 3.198, 3.205), stdev = 0.007
  CI (99.9%): [3.067, 3.328] (assumes normal distribution)


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
# Warmup Iteration   1: 5.339 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.310 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.012 ms/op
Iteration   1: 4.188 ±(99.9%) 0.017 ms/op
Iteration   2: 4.044 ±(99.9%) 0.033 ms/op
Iteration   3: 4.129 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.120 ±(99.9%) 1.319 ms/op [Average]
  (min, avg, max) = (4.044, 4.120, 4.188), stdev = 0.072
  CI (99.9%): [2.801, 5.439] (assumes normal distribution)


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
# Warmup Iteration   1: 4.560 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
Iteration   1: 3.134 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.569 ms/op
                 createUser·p0.9999: 13.507 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   2: 3.175 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.100 ms/op
                 createUser·p0.9999: 15.333 ms/op
                 createUser·p1.00:   15.532 ms/op

Iteration   3: 3.155 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  16.318 ms/op
                 createUser·p0.9999: 20.508 ms/op
                 createUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304293
  mean =      3.154 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22093 
    [ 2.500,  5.000) = 280977 
    [ 5.000,  7.500) = 800 
    [ 7.500, 10.000) = 167 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.249 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     20.774 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
Iteration   1: 3.128 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.506 ms/op
                 existUser·p0.9999: 13.100 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.763 ms/op
                 existUser·p0.9999: 15.049 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.266 ms/op
                 existUser·p0.9999: 16.359 ms/op
                 existUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311783
  mean =      3.080 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 411 
    [ 1.250,  2.500) = 32088 
    [ 2.500,  3.750) = 247894 
    [ 3.750,  5.000) = 30517 
    [ 5.000,  6.250) = 416 
    [ 6.250,  7.500) = 218 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.993 ms/op
     p(99.9900) =     15.952 ms/op
     p(99.9990) =     16.509 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.007 ms/op
Iteration   1: 3.224 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  9.961 ms/op
                 getUser·p0.9999: 13.455 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 3.247 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.172 ms/op
                 getUser·p0.9999: 15.083 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.598 ms/op
                 getUser·p0.9999: 18.475 ms/op
                 getUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299487
  mean =      3.205 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 718 
    [ 1.250,  2.500) = 17723 
    [ 2.500,  3.750) = 234856 
    [ 3.750,  5.000) = 44974 
    [ 5.000,  6.250) = 620 
    [ 6.250,  7.500) = 252 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.069 ms/op
     p(99.9900) =     16.910 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 5.579 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.011 ms/op
Iteration   1: 4.160 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.811 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  15.237 ms/op
                 listUser·p0.9999: 21.490 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   2: 4.166 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  15.436 ms/op
                 listUser·p0.9999: 17.323 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 4.130 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  20.590 ms/op
                 listUser·p0.9999: 27.034 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231021
  mean =      4.152 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1585 
    [ 2.500,  5.000) = 203516 
    [ 5.000,  7.500) = 24246 
    [ 7.500, 10.000) = 1183 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     27.875 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.050 ± 1.338  ops/ms
ClientGrpc.existUser                       thrpt       3  10.428 ± 2.383  ops/ms
ClientGrpc.getUser                         thrpt       3   9.821 ± 2.536  ops/ms
ClientGrpc.listUser                        thrpt       3   7.648 ± 0.705  ops/ms
ClientGrpc.createUser                       avgt       3   3.219 ± 1.014   ms/op
ClientGrpc.existUser                        avgt       3   3.046 ± 0.684   ms/op
ClientGrpc.getUser                          avgt       3   3.198 ± 0.130   ms/op
ClientGrpc.listUser                         avgt       3   4.120 ± 1.319   ms/op
ClientGrpc.createUser                     sample  304293   3.154 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.839           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.249           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.678           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.873           ms/op
ClientGrpc.existUser                      sample  311783   3.080 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.622           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.047           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.957           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.993           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.952           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.055           ms/op
ClientGrpc.getUser                        sample  299487   3.205 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.614           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.178           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.069           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.910           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.300           ms/op
ClientGrpc.listUser                       sample  231021   4.152 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.167           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.994           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.302           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.362           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.886           ms/op
