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
# Warmup Iteration   1: 4.912 ops/ms
# Warmup Iteration   2: 9.292 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.535 ops/ms
Iteration   2: 10.060 ops/ms
Iteration   3: 10.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.295 ±(99.9%) 4.340 ops/ms [Average]
  (min, avg, max) = (10.060, 10.295, 10.535), stdev = 0.238
  CI (99.9%): [5.956, 14.635] (assumes normal distribution)


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
# Warmup Iteration   1: 8.161 ops/ms
# Warmup Iteration   2: 10.760 ops/ms
# Warmup Iteration   3: 11.170 ops/ms
Iteration   1: 10.681 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.767 ±(99.9%) 1.348 ops/ms [Average]
  (min, avg, max) = (10.681, 10.767, 10.813), stdev = 0.074
  CI (99.9%): [9.418, 12.115] (assumes normal distribution)


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
# Warmup Iteration   1: 7.228 ops/ms
# Warmup Iteration   2: 10.355 ops/ms
# Warmup Iteration   3: 10.440 ops/ms
Iteration   1: 10.488 ops/ms
Iteration   2: 10.373 ops/ms
Iteration   3: 10.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.411 ±(99.9%) 1.218 ops/ms [Average]
  (min, avg, max) = (10.373, 10.411, 10.488), stdev = 0.067
  CI (99.9%): [9.194, 11.629] (assumes normal distribution)


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
# Warmup Iteration   1: 6.192 ops/ms
# Warmup Iteration   2: 7.871 ops/ms
# Warmup Iteration   3: 8.094 ops/ms
Iteration   1: 8.060 ops/ms
Iteration   2: 8.153 ops/ms
Iteration   3: 8.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.154 ±(99.9%) 1.718 ops/ms [Average]
  (min, avg, max) = (8.060, 8.154, 8.248), stdev = 0.094
  CI (99.9%): [6.435, 9.872] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.003 ms/op
Iteration   1: 3.082 ±(99.9%) 0.003 ms/op
Iteration   2: 3.136 ±(99.9%) 0.002 ms/op
Iteration   3: 3.161 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.126 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (3.082, 3.126, 3.161), stdev = 0.041
  CI (99.9%): [2.386, 3.866] (assumes normal distribution)


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.003 ms/op
Iteration   1: 2.938 ±(99.9%) 0.008 ms/op
Iteration   2: 2.941 ±(99.9%) 0.002 ms/op
Iteration   3: 2.996 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.958 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (2.938, 2.958, 2.996), stdev = 0.033
  CI (99.9%): [2.363, 3.553] (assumes normal distribution)


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.002 ms/op
Iteration   1: 3.078 ±(99.9%) 0.003 ms/op
Iteration   2: 3.069 ±(99.9%) 0.003 ms/op
Iteration   3: 3.142 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.096 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.069, 3.096, 3.142), stdev = 0.040
  CI (99.9%): [2.373, 3.819] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.017 ms/op
Iteration   1: 3.878 ±(99.9%) 0.020 ms/op
Iteration   2: 3.691 ±(99.9%) 0.007 ms/op
Iteration   3: 4.019 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.863 ±(99.9%) 2.997 ms/op [Average]
  (min, avg, max) = (3.691, 3.863, 4.019), stdev = 0.164
  CI (99.9%): [0.866, 6.860] (assumes normal distribution)


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.006 ms/op
Iteration   1: 3.084 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.065 ms/op
                 createUser·p0.9999: 15.166 ms/op
                 createUser·p1.00:   15.499 ms/op

Iteration   2: 3.155 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.511 ms/op
                 createUser·p0.9999: 15.511 ms/op
                 createUser·p1.00:   16.056 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  13.301 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308282
  mean =      3.116 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 876 
    [ 1.250,  2.500) = 18050 
    [ 2.500,  3.750) = 262173 
    [ 3.750,  5.000) = 26071 
    [ 5.000,  6.250) = 464 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 80 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     16.737 ms/op
     p(99.9990) =     18.017 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
Iteration   1: 2.960 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.774 ms/op
                 existUser·p0.9999: 10.519 ms/op
                 existUser·p1.00:   10.715 ms/op

Iteration   2: 2.943 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.155 ms/op
                 existUser·p0.9999: 21.271 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   3: 2.890 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  8.249 ms/op
                 existUser·p0.9999: 28.670 ms/op
                 existUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327291
  mean =      2.931 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56960 
    [ 2.500,  5.000) = 269540 
    [ 5.000,  7.500) = 520 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.895 ms/op
     p(99.9900) =     23.218 ms/op
     p(99.9990) =     29.024 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 3.735 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
Iteration   1: 3.135 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.685 ms/op
                 getUser·p0.9999: 14.860 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.281 ms/op
                 getUser·p0.9999: 15.980 ms/op
                 getUser·p1.00:   16.368 ms/op

Iteration   3: 2.967 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.221 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.939 ms/op
                 getUser·p0.9999: 21.143 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316124
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27312 
    [ 2.500,  5.000) = 287882 
    [ 5.000,  7.500) = 706 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.221 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.865 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     21.622 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 4.556 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.012 ms/op
Iteration   1: 3.901 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  12.878 ms/op
                 listUser·p0.9999: 18.697 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   2: 3.965 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.443 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.080 ms/op
                 listUser·p0.9999: 22.277 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   3: 3.779 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.755 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  14.404 ms/op
                 listUser·p0.9999: 18.092 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247517
  mean =      3.880 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5474 
    [ 2.500,  5.000) = 218806 
    [ 5.000,  7.500) = 22393 
    [ 7.500, 10.000) = 433 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     22.630 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.295 ± 4.340  ops/ms
ClientGrpc.existUser                       thrpt       3  10.767 ± 1.348  ops/ms
ClientGrpc.getUser                         thrpt       3  10.411 ± 1.218  ops/ms
ClientGrpc.listUser                        thrpt       3   8.154 ± 1.718  ops/ms
ClientGrpc.createUser                       avgt       3   3.126 ± 0.740   ms/op
ClientGrpc.existUser                        avgt       3   2.958 ± 0.595   ms/op
ClientGrpc.getUser                          avgt       3   3.096 ± 0.723   ms/op
ClientGrpc.listUser                         avgt       3   3.863 ± 2.997   ms/op
ClientGrpc.createUser                     sample  308282   3.116 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.617           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.208           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.737           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.153           ms/op
ClientGrpc.existUser                      sample  327291   2.931 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.663           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.895           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.218           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.098           ms/op
ClientGrpc.getUser                        sample  316124   3.036 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.221           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.865           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.431           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.889           ms/op
ClientGrpc.listUser                       sample  247517   3.880 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.443           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.992           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.809           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.741           ms/op
