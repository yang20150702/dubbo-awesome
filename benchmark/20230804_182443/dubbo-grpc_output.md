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
# Warmup Iteration   1: 4.000 ops/ms
# Warmup Iteration   2: 8.589 ops/ms
# Warmup Iteration   3: 9.725 ops/ms
Iteration   1: 10.209 ops/ms
Iteration   2: 10.462 ops/ms
Iteration   3: 10.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.302 ±(99.9%) 2.534 ops/ms [Average]
  (min, avg, max) = (10.209, 10.302, 10.462), stdev = 0.139
  CI (99.9%): [7.768, 12.836] (assumes normal distribution)


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
# Warmup Iteration   1: 7.121 ops/ms
# Warmup Iteration   2: 10.237 ops/ms
# Warmup Iteration   3: 10.632 ops/ms
Iteration   1: 10.730 ops/ms
Iteration   2: 10.836 ops/ms
Iteration   3: 11.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.879 ±(99.9%) 3.193 ops/ms [Average]
  (min, avg, max) = (10.730, 10.879, 11.072), stdev = 0.175
  CI (99.9%): [7.686, 14.072] (assumes normal distribution)


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
# Warmup Iteration   1: 6.849 ops/ms
# Warmup Iteration   2: 9.826 ops/ms
# Warmup Iteration   3: 10.345 ops/ms
Iteration   1: 10.479 ops/ms
Iteration   2: 10.161 ops/ms
Iteration   3: 10.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.282 ±(99.9%) 3.149 ops/ms [Average]
  (min, avg, max) = (10.161, 10.282, 10.479), stdev = 0.173
  CI (99.9%): [7.133, 13.430] (assumes normal distribution)


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
# Warmup Iteration   1: 5.677 ops/ms
# Warmup Iteration   2: 7.530 ops/ms
# Warmup Iteration   3: 7.805 ops/ms
Iteration   1: 7.832 ops/ms
Iteration   2: 7.971 ops/ms
Iteration   3: 7.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.897 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (7.832, 7.897, 7.971), stdev = 0.070
  CI (99.9%): [6.618, 9.176] (assumes normal distribution)


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.003 ms/op
Iteration   1: 3.127 ±(99.9%) 0.004 ms/op
Iteration   2: 3.066 ±(99.9%) 0.002 ms/op
Iteration   3: 3.066 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.086 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (3.066, 3.086, 3.127), stdev = 0.035
  CI (99.9%): [2.439, 3.733] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.225 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.003 ms/op
Iteration   1: 2.959 ±(99.9%) 0.002 ms/op
Iteration   2: 2.947 ±(99.9%) 0.003 ms/op
Iteration   3: 2.940 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.949 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.940, 2.949, 2.959), stdev = 0.010
  CI (99.9%): [2.766, 3.132] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.004 ms/op
Iteration   1: 3.110 ±(99.9%) 0.004 ms/op
Iteration   2: 3.102 ±(99.9%) 0.004 ms/op
Iteration   3: 3.121 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.111 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (3.102, 3.111, 3.121), stdev = 0.009
  CI (99.9%): [2.940, 3.282] (assumes normal distribution)


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
# Warmup Iteration   1: 5.689 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.038 ms/op
Iteration   1: 4.084 ±(99.9%) 0.027 ms/op
Iteration   2: 4.045 ±(99.9%) 0.011 ms/op
Iteration   3: 4.042 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.057 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (4.042, 4.057, 4.084), stdev = 0.023
  CI (99.9%): [3.638, 4.476] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.410 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  8.061 ms/op
                 createUser·p0.9999: 13.854 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.518 ms/op
                 createUser·p0.9999: 18.111 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  10.878 ms/op
                 createUser·p0.9999: 17.760 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311386
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 16052 
    [ 2.500,  3.750) = 276185 
    [ 3.750,  5.000) = 15876 
    [ 5.000,  6.250) = 1588 
    [ 6.250,  7.500) = 501 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 138 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =      9.349 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     18.314 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.061 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  9.241 ms/op
                 existUser·p0.9999: 13.492 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  12.291 ms/op
                 existUser·p0.9999: 15.248 ms/op
                 existUser·p1.00:   15.745 ms/op

Iteration   3: 3.024 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.370 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 16.781 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317040
  mean =      3.027 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 453 
    [ 1.250,  2.500) = 17577 
    [ 2.500,  3.750) = 285906 
    [ 3.750,  5.000) = 11041 
    [ 5.000,  6.250) = 897 
    [ 6.250,  7.500) = 364 
    [ 7.500,  8.750) = 351 
    [ 8.750, 10.000) = 190 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     16.036 ms/op
     p(99.9990) =     17.820 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 5.013 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.007 ms/op
Iteration   1: 3.251 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  10.011 ms/op
                 getUser·p0.9999: 19.169 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.323 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  8.371 ms/op
                 getUser·p0.9999: 24.705 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.749 ms/op
                 getUser·p0.9999: 23.359 ms/op
                 getUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300768
  mean =      3.195 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11748 
    [ 2.500,  5.000) = 286678 
    [ 5.000,  7.500) = 1657 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.323 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     26.825 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 6.305 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.261 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.011 ms/op
Iteration   1: 4.197 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  15.560 ms/op
                 listUser·p0.9999: 20.963 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   2: 4.173 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   7.665 ms/op
                 listUser·p0.999:  16.144 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 4.148 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 19.811 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230004
  mean =      4.173 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2152 
    [ 2.500,  5.000) = 199621 
    [ 5.000,  7.500) = 25698 
    [ 7.500, 10.000) = 1948 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      6.169 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     16.236 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.790 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.302 ± 2.534  ops/ms
ClientGrpc.existUser                       thrpt       3  10.879 ± 3.193  ops/ms
ClientGrpc.getUser                         thrpt       3  10.282 ± 3.149  ops/ms
ClientGrpc.listUser                        thrpt       3   7.897 ± 1.279  ops/ms
ClientGrpc.createUser                       avgt       3   3.086 ± 0.647   ms/op
ClientGrpc.existUser                        avgt       3   2.949 ± 0.183   ms/op
ClientGrpc.getUser                          avgt       3   3.111 ± 0.171   ms/op
ClientGrpc.listUser                         avgt       3   4.057 ± 0.419   ms/op
ClientGrpc.createUser                     sample  311386   3.084 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.636           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.349           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.793           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.481           ms/op
ClientGrpc.existUser                      sample  317040   3.027 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.370           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.388           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.036           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.317           ms/op
ClientGrpc.getUser                        sample  300768   3.195 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.323           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.154           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.990           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.735           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.257           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.576           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.837           ms/op
ClientGrpc.listUser                       sample  230004   4.173 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.217           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.990           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.259           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.169           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.627           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.236           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.627           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.003           ms/op
