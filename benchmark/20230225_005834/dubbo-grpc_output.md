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
# Warmup Iteration   1: 4.192 ops/ms
# Warmup Iteration   2: 9.325 ops/ms
# Warmup Iteration   3: 9.866 ops/ms
Iteration   1: 10.197 ops/ms
Iteration   2: 10.294 ops/ms
Iteration   3: 9.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.136 ±(99.9%) 3.580 ops/ms [Average]
  (min, avg, max) = (9.916, 10.136, 10.294), stdev = 0.196
  CI (99.9%): [6.555, 13.716] (assumes normal distribution)


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
# Warmup Iteration   1: 7.626 ops/ms
# Warmup Iteration   2: 10.478 ops/ms
# Warmup Iteration   3: 11.369 ops/ms
Iteration   1: 10.430 ops/ms
Iteration   2: 10.843 ops/ms
Iteration   3: 11.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.802 ±(99.9%) 6.466 ops/ms [Average]
  (min, avg, max) = (10.430, 10.802, 11.135), stdev = 0.354
  CI (99.9%): [4.336, 17.269] (assumes normal distribution)


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
# Warmup Iteration   1: 6.711 ops/ms
# Warmup Iteration   2: 9.720 ops/ms
# Warmup Iteration   3: 10.215 ops/ms
Iteration   1: 10.151 ops/ms
Iteration   2: 9.973 ops/ms
Iteration   3: 10.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.179 ±(99.9%) 4.048 ops/ms [Average]
  (min, avg, max) = (9.973, 10.179, 10.414), stdev = 0.222
  CI (99.9%): [6.131, 14.227] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.719 ops/ms
# Warmup Iteration   2: 7.854 ops/ms
# Warmup Iteration   3: 8.007 ops/ms
Iteration   1: 8.184 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.106 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (8.048, 8.106, 8.184), stdev = 0.070
  CI (99.9%): [6.834, 9.378] (assumes normal distribution)


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.003 ms/op
Iteration   1: 3.113 ±(99.9%) 0.009 ms/op
Iteration   2: 3.126 ±(99.9%) 0.002 ms/op
Iteration   3: 3.223 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.154 ±(99.9%) 1.099 ms/op [Average]
  (min, avg, max) = (3.113, 3.154, 3.223), stdev = 0.060
  CI (99.9%): [2.055, 4.253] (assumes normal distribution)


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.002 ms/op
Iteration   1: 2.978 ±(99.9%) 0.003 ms/op
Iteration   2: 3.001 ±(99.9%) 0.002 ms/op
Iteration   3: 2.997 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.992 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.978, 2.992, 3.001), stdev = 0.012
  CI (99.9%): [2.771, 3.213] (assumes normal distribution)


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
# Warmup Iteration   1: 4.371 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.003 ms/op
Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
Iteration   3: 3.099 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.104 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (3.093, 3.104, 3.122), stdev = 0.015
  CI (99.9%): [2.826, 3.382] (assumes normal distribution)


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.011 ms/op
Iteration   1: 3.879 ±(99.9%) 0.008 ms/op
Iteration   2: 3.959 ±(99.9%) 0.039 ms/op
Iteration   3: 3.897 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.912 ±(99.9%) 0.767 ms/op [Average]
  (min, avg, max) = (3.879, 3.912, 3.959), stdev = 0.042
  CI (99.9%): [3.145, 4.679] (assumes normal distribution)


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.006 ms/op
Iteration   1: 3.191 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  6.985 ms/op
                 createUser·p0.9999: 20.806 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   2: 3.306 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.720 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  11.072 ms/op
                 createUser·p0.9999: 18.240 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  11.593 ms/op
                 createUser·p0.9999: 21.621 ms/op
                 createUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297908
  mean =      3.221 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20392 
    [ 2.500,  5.000) = 276350 
    [ 5.000,  7.500) = 785 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      9.194 ms/op
     p(99.9900) =     20.880 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 3.108 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.545 ms/op
                 existUser·p0.9999: 13.093 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.048 ms/op
                 existUser·p0.9999: 14.423 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  5.337 ms/op
                 existUser·p0.9999: 16.298 ms/op
                 existUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314434
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 913 
    [ 1.250,  2.500) = 40157 
    [ 2.500,  3.750) = 243715 
    [ 3.750,  5.000) = 28860 
    [ 5.000,  6.250) = 364 
    [ 6.250,  7.500) = 168 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.001 ms/op
     p(99.9900) =     14.518 ms/op
     p(99.9990) =     16.705 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 4.340 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.007 ms/op
Iteration   1: 3.153 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  11.808 ms/op
                 getUser·p0.9999: 13.580 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   2: 3.166 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  6.963 ms/op
                 getUser·p0.9999: 15.019 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.440 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  6.602 ms/op
                 getUser·p0.9999: 16.606 ms/op
                 getUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307142
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 500 
    [ 1.250,  2.500) = 22330 
    [ 2.500,  3.750) = 255683 
    [ 3.750,  5.000) = 27264 
    [ 5.000,  6.250) = 837 
    [ 6.250,  7.500) = 236 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.360 ms/op
     p(99.9900) =     15.717 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 5.367 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.012 ms/op
Iteration   1: 3.968 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 17.163 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 3.954 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.631 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  18.542 ms/op
                 listUser·p0.9999: 24.573 ms/op
                 listUser·p1.00:   27.460 ms/op

Iteration   3: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.823 ms/op
                 listUser·p0.999:  14.608 ms/op
                 listUser·p0.9999: 18.283 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242005
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1916 
    [ 2.500,  5.000) = 215920 
    [ 5.000,  7.500) = 23023 
    [ 7.500, 10.000) = 689 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     27.282 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.136 ± 3.580  ops/ms
ClientGrpc.existUser                       thrpt       3  10.802 ± 6.466  ops/ms
ClientGrpc.getUser                         thrpt       3  10.179 ± 4.048  ops/ms
ClientGrpc.listUser                        thrpt       3   8.106 ± 1.272  ops/ms
ClientGrpc.createUser                       avgt       3   3.154 ± 1.099   ms/op
ClientGrpc.existUser                        avgt       3   2.992 ± 0.221   ms/op
ClientGrpc.getUser                          avgt       3   3.104 ± 0.278   ms/op
ClientGrpc.listUser                         avgt       3   3.912 ± 0.767   ms/op
ClientGrpc.createUser                     sample  297908   3.221 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.613           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.178           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.940           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.149           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.194           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.880           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.282           ms/op
ClientGrpc.existUser                      sample  314434   3.052 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.654           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.035           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.001           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.518           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.843           ms/op
ClientGrpc.getUser                        sample  307142   3.125 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.440           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.360           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.717           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.399           ms/op
ClientGrpc.listUser                       sample  242005   3.967 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.631           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.942           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.953           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.460           ms/op
