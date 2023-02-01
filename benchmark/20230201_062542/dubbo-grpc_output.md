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
# Warmup Iteration   1: 4.009 ops/ms
# Warmup Iteration   2: 8.938 ops/ms
# Warmup Iteration   3: 10.013 ops/ms
Iteration   1: 9.850 ops/ms
Iteration   2: 10.280 ops/ms
Iteration   3: 10.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.102 ±(99.9%) 4.089 ops/ms [Average]
  (min, avg, max) = (9.850, 10.102, 10.280), stdev = 0.224
  CI (99.9%): [6.013, 14.191] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.958 ops/ms
# Warmup Iteration   2: 10.066 ops/ms
# Warmup Iteration   3: 10.437 ops/ms
Iteration   1: 10.456 ops/ms
Iteration   2: 10.479 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.551 ±(99.9%) 2.668 ops/ms [Average]
  (min, avg, max) = (10.456, 10.551, 10.720), stdev = 0.146
  CI (99.9%): [7.884, 13.219] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.889 ops/ms
# Warmup Iteration   2: 9.551 ops/ms
# Warmup Iteration   3: 9.988 ops/ms
Iteration   1: 10.071 ops/ms
Iteration   2: 10.019 ops/ms
Iteration   3: 9.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.017 ±(99.9%) 1.010 ops/ms [Average]
  (min, avg, max) = (9.961, 10.017, 10.071), stdev = 0.055
  CI (99.9%): [9.007, 11.028] (assumes normal distribution)


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
# Warmup Iteration   1: 4.907 ops/ms
# Warmup Iteration   2: 7.368 ops/ms
# Warmup Iteration   3: 7.871 ops/ms
Iteration   1: 7.838 ops/ms
Iteration   2: 7.865 ops/ms
Iteration   3: 7.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.815 ±(99.9%) 1.196 ops/ms [Average]
  (min, avg, max) = (7.741, 7.815, 7.865), stdev = 0.066
  CI (99.9%): [6.618, 9.011] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.213 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.011 ms/op
Iteration   1: 3.183 ±(99.9%) 0.004 ms/op
Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
Iteration   3: 3.190 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.156 ±(99.9%) 0.961 ms/op [Average]
  (min, avg, max) = (3.095, 3.156, 3.190), stdev = 0.053
  CI (99.9%): [2.195, 4.117] (assumes normal distribution)


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.002 ms/op
Iteration   1: 3.101 ±(99.9%) 0.002 ms/op
Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
Iteration   3: 3.107 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.095 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.077, 3.095, 3.107), stdev = 0.016
  CI (99.9%): [2.808, 3.382] (assumes normal distribution)


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.002 ms/op
Iteration   1: 3.128 ±(99.9%) 0.002 ms/op
Iteration   2: 3.128 ±(99.9%) 0.004 ms/op
Iteration   3: 3.072 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.109 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (3.072, 3.109, 3.128), stdev = 0.032
  CI (99.9%): [2.517, 3.702] (assumes normal distribution)


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
# Warmup Iteration   1: 5.334 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.005 ms/op
Iteration   1: 4.059 ±(99.9%) 0.035 ms/op
Iteration   2: 4.078 ±(99.9%) 0.031 ms/op
Iteration   3: 3.979 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.039 ±(99.9%) 0.963 ms/op [Average]
  (min, avg, max) = (3.979, 4.039, 4.078), stdev = 0.053
  CI (99.9%): [3.075, 5.002] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.368 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.205 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.842 ms/op
                 createUser·p0.9999: 13.550 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  7.774 ms/op
                 createUser·p0.9999: 16.412 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  9.090 ms/op
                 createUser·p0.9999: 32.047 ms/op
                 createUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301141
  mean =      3.188 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23186 
    [ 2.500,  5.000) = 276836 
    [ 5.000,  7.500) = 724 
    [ 7.500, 10.000) = 170 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.214 ms/op
     p(99.9900) =     31.351 ms/op
     p(99.9990) =     32.374 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 4.291 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.765 ms/op
                 existUser·p0.9999: 20.357 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 27.014 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.681 ms/op
                 existUser·p0.9999: 19.516 ms/op
                 existUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317550
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45937 
    [ 2.500,  5.000) = 270603 
    [ 5.000,  7.500) = 666 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.914 ms/op
     p(99.9900) =     26.190 ms/op
     p(99.9990) =     27.415 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.006 ms/op
Iteration   1: 3.154 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.562 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  9.060 ms/op
                 getUser·p0.9999: 12.676 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   2: 3.165 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.577 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.863 ms/op
                 getUser·p0.9999: 14.957 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  10.062 ms/op
                 getUser·p0.9999: 16.141 ms/op
                 getUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305429
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 581 
    [ 1.250,  2.500) = 21283 
    [ 2.500,  3.750) = 251500 
    [ 3.750,  5.000) = 30577 
    [ 5.000,  6.250) = 728 
    [ 6.250,  7.500) = 281 
    [ 7.500,  8.750) = 138 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     15.598 ms/op
     p(99.9990) =     16.759 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 5.705 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.011 ms/op
Iteration   1: 4.089 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.478 ms/op
                 listUser·p0.9999: 21.305 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   2: 4.006 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.473 ms/op
                 listUser·p0.9999: 30.246 ms/op
                 listUser·p1.00:   30.802 ms/op

Iteration   3: 4.038 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  17.089 ms/op
                 listUser·p0.9999: 28.415 ms/op
                 listUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237263
  mean =      4.044 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1573 
    [ 2.500,  5.000) = 210904 
    [ 5.000,  7.500) = 23286 
    [ 7.500, 10.000) = 974 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     28.845 ms/op
     p(99.9990) =     30.450 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.102 ± 4.089  ops/ms
ClientGrpc.existUser                       thrpt       3  10.551 ± 2.668  ops/ms
ClientGrpc.getUser                         thrpt       3  10.017 ± 1.010  ops/ms
ClientGrpc.listUser                        thrpt       3   7.815 ± 1.196  ops/ms
ClientGrpc.createUser                       avgt       3   3.156 ± 0.961   ms/op
ClientGrpc.existUser                        avgt       3   3.095 ± 0.287   ms/op
ClientGrpc.getUser                          avgt       3   3.109 ± 0.593   ms/op
ClientGrpc.listUser                         avgt       3   4.039 ± 0.963   ms/op
ClientGrpc.createUser                     sample  301141   3.188 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.551           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.214           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.351           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.539           ms/op
ClientGrpc.existUser                      sample  317550   3.024 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.713           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.891           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.914           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.190           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.525           ms/op
ClientGrpc.getUser                        sample  305429   3.143 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.562           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.159           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.598           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.761           ms/op
ClientGrpc.listUser                       sample  237263   4.044 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.182           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.319           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.845           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.802           ms/op
