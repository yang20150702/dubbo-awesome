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
# Warmup Iteration   1: 4.285 ops/ms
# Warmup Iteration   2: 8.636 ops/ms
# Warmup Iteration   3: 9.890 ops/ms
Iteration   1: 9.921 ops/ms
Iteration   2: 10.091 ops/ms
Iteration   3: 10.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.006 ±(99.9%) 1.553 ops/ms [Average]
  (min, avg, max) = (9.921, 10.006, 10.091), stdev = 0.085
  CI (99.9%): [8.454, 11.559] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.339 ops/ms
# Warmup Iteration   2: 10.121 ops/ms
# Warmup Iteration   3: 10.621 ops/ms
Iteration   1: 10.487 ops/ms
Iteration   2: 10.618 ops/ms
Iteration   3: 10.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.696 ±(99.9%) 4.668 ops/ms [Average]
  (min, avg, max) = (10.487, 10.696, 10.981), stdev = 0.256
  CI (99.9%): [6.027, 15.364] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.995 ops/ms
# Warmup Iteration   2: 9.851 ops/ms
# Warmup Iteration   3: 10.105 ops/ms
Iteration   1: 10.289 ops/ms
Iteration   2: 10.237 ops/ms
Iteration   3: 10.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.274 ±(99.9%) 0.601 ops/ms [Average]
  (min, avg, max) = (10.237, 10.274, 10.297), stdev = 0.033
  CI (99.9%): [9.674, 10.875] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.291 ops/ms
# Warmup Iteration   2: 7.711 ops/ms
# Warmup Iteration   3: 7.862 ops/ms
Iteration   1: 8.044 ops/ms
Iteration   2: 8.019 ops/ms
Iteration   3: 8.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.036 ±(99.9%) 0.273 ops/ms [Average]
  (min, avg, max) = (8.019, 8.036, 8.045), stdev = 0.015
  CI (99.9%): [7.763, 8.309] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.799 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.002 ms/op
Iteration   1: 3.261 ±(99.9%) 0.002 ms/op
Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
Iteration   3: 3.161 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.198 ±(99.9%) 1.012 ms/op [Average]
  (min, avg, max) = (3.161, 3.198, 3.261), stdev = 0.055
  CI (99.9%): [2.185, 4.210] (assumes normal distribution)


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.002 ms/op
Iteration   1: 3.050 ±(99.9%) 0.003 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 2.943 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.025 ±(99.9%) 1.324 ms/op [Average]
  (min, avg, max) = (2.943, 3.025, 3.082), stdev = 0.073
  CI (99.9%): [1.701, 4.349] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.391 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.001 ms/op
Iteration   1: 3.215 ±(99.9%) 0.011 ms/op
Iteration   2: 3.215 ±(99.9%) 0.002 ms/op
Iteration   3: 3.144 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.191 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (3.144, 3.191, 3.215), stdev = 0.041
  CI (99.9%): [2.436, 3.946] (assumes normal distribution)


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
# Warmup Iteration   1: 5.029 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.007 ms/op
Iteration   1: 3.796 ±(99.9%) 0.018 ms/op
Iteration   2: 3.974 ±(99.9%) 0.010 ms/op
Iteration   3: 4.015 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.928 ±(99.9%) 2.123 ms/op [Average]
  (min, avg, max) = (3.796, 3.928, 4.015), stdev = 0.116
  CI (99.9%): [1.806, 6.051] (assumes normal distribution)


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
# Warmup Iteration   1: 4.478 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.005 ms/op
Iteration   1: 3.157 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.615 ms/op
                 createUser·p0.9999: 17.957 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 3.137 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  8.977 ms/op
                 createUser·p0.9999: 14.535 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.129 ms/op
                 createUser·p0.999:  6.980 ms/op
                 createUser·p0.9999: 17.072 ms/op
                 createUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305931
  mean =      3.139 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 9808 
    [ 2.500,  3.750) = 268570 
    [ 3.750,  5.000) = 25793 
    [ 5.000,  6.250) = 807 
    [ 6.250,  7.500) = 343 
    [ 7.500,  8.750) = 154 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      8.455 ms/op
     p(99.9900) =     17.479 ms/op
     p(99.9990) =     18.178 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.005 ms/op
Iteration   1: 3.056 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.327 ms/op
                 existUser·p0.9999: 13.379 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.657 ms/op
                 existUser·p0.999:  8.187 ms/op
                 existUser·p0.9999: 14.641 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  9.848 ms/op
                 existUser·p0.9999: 17.924 ms/op
                 existUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314270
  mean =      3.055 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 522 
    [ 1.250,  2.500) = 20593 
    [ 2.500,  3.750) = 275193 
    [ 3.750,  5.000) = 16313 
    [ 5.000,  6.250) = 887 
    [ 6.250,  7.500) = 320 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.200 ms/op
     p(99.9900) =     16.894 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.578 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
Iteration   1: 3.187 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  11.873 ms/op
                 getUser·p0.9999: 16.515 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   2: 3.180 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.036 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   3: 3.155 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.734 ms/op
                 getUser·p0.9999: 20.016 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302353
  mean =      3.174 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4574 
    [ 2.500,  5.000) = 295939 
    [ 5.000,  7.500) = 1380 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.038 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     20.511 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 5.183 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.023 ±(99.9%) 0.009 ms/op
Iteration   1: 3.961 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   6.809 ms/op
                 listUser·p0.999:  13.246 ms/op
                 listUser·p0.9999: 16.053 ms/op
                 listUser·p1.00:   16.712 ms/op

Iteration   2: 3.991 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.835 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 4.027 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.444 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240616
  mean =      3.993 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1293 
    [ 2.500,  5.000) = 225504 
    [ 5.000,  7.500) = 12424 
    [ 7.500, 10.000) = 816 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 211 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     14.244 ms/op
     p(99.9900) =     20.281 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.006 ± 1.553  ops/ms
ClientGrpc.existUser                       thrpt       3  10.696 ± 4.668  ops/ms
ClientGrpc.getUser                         thrpt       3  10.274 ± 0.601  ops/ms
ClientGrpc.listUser                        thrpt       3   8.036 ± 0.273  ops/ms
ClientGrpc.createUser                       avgt       3   3.198 ± 1.012   ms/op
ClientGrpc.existUser                        avgt       3   3.025 ± 1.324   ms/op
ClientGrpc.getUser                          avgt       3   3.191 ± 0.755   ms/op
ClientGrpc.listUser                         avgt       3   3.928 ± 2.123   ms/op
ClientGrpc.createUser                     sample  305931   3.139 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.794           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.455           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.479           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.711           ms/op
ClientGrpc.existUser                      sample  314270   3.055 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.781           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.006           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.200           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.894           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.612           ms/op
ClientGrpc.getUser                        sample  302353   3.174 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.712           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.038           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.874           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.709           ms/op
ClientGrpc.listUser                       sample  240616   3.993 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.171           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.244           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.281           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.922           ms/op
