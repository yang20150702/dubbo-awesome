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
# Warmup Iteration   1: 4.820 ops/ms
# Warmup Iteration   2: 9.223 ops/ms
# Warmup Iteration   3: 10.246 ops/ms
Iteration   1: 10.618 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.707 ±(99.9%) 2.212 ops/ms [Average]
  (min, avg, max) = (10.618, 10.707, 10.845), stdev = 0.121
  CI (99.9%): [8.495, 12.919] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.001 ops/ms
# Warmup Iteration   2: 10.793 ops/ms
# Warmup Iteration   3: 11.069 ops/ms
Iteration   1: 11.177 ops/ms
Iteration   2: 11.423 ops/ms
Iteration   3: 11.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.307 ±(99.9%) 2.262 ops/ms [Average]
  (min, avg, max) = (11.177, 11.307, 11.423), stdev = 0.124
  CI (99.9%): [9.045, 13.570] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.899 ops/ms
# Warmup Iteration   2: 10.404 ops/ms
# Warmup Iteration   3: 10.699 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 10.633 ops/ms
Iteration   3: 10.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.600 ±(99.9%) 1.435 ops/ms [Average]
  (min, avg, max) = (10.511, 10.600, 10.657), stdev = 0.079
  CI (99.9%): [9.166, 12.035] (assumes normal distribution)


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
# Warmup Iteration   1: 6.242 ops/ms
# Warmup Iteration   2: 7.836 ops/ms
# Warmup Iteration   3: 8.202 ops/ms
Iteration   1: 8.224 ops/ms
Iteration   2: 8.208 ops/ms
Iteration   3: 8.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.205 ±(99.9%) 0.366 ops/ms [Average]
  (min, avg, max) = (8.184, 8.205, 8.224), stdev = 0.020
  CI (99.9%): [7.840, 8.571] (assumes normal distribution)


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.003 ms/op
Iteration   1: 2.931 ±(99.9%) 0.003 ms/op
Iteration   2: 2.984 ±(99.9%) 0.003 ms/op
Iteration   3: 2.929 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.948 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (2.929, 2.948, 2.984), stdev = 0.031
  CI (99.9%): [2.379, 3.517] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.003 ms/op
Iteration   1: 2.904 ±(99.9%) 0.003 ms/op
Iteration   2: 2.828 ±(99.9%) 0.003 ms/op
Iteration   3: 2.858 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.863 ±(99.9%) 0.704 ms/op [Average]
  (min, avg, max) = (2.828, 2.863, 2.904), stdev = 0.039
  CI (99.9%): [2.160, 3.567] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 2.937 ±(99.9%) 0.003 ms/op
Iteration   2: 2.950 ±(99.9%) 0.002 ms/op
Iteration   3: 2.993 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.960 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (2.937, 2.960, 2.993), stdev = 0.029
  CI (99.9%): [2.429, 3.491] (assumes normal distribution)


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.028 ms/op
Iteration   1: 3.916 ±(99.9%) 0.011 ms/op
Iteration   2: 3.878 ±(99.9%) 0.050 ms/op
Iteration   3: 3.838 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.878 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.838, 3.878, 3.916), stdev = 0.039
  CI (99.9%): [3.165, 4.590] (assumes normal distribution)


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
Iteration   1: 2.978 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.391 ms/op
                 createUser·p0.9999: 18.940 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   2: 2.981 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.583 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  6.611 ms/op
                 createUser·p0.9999: 24.505 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   3: 3.003 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.525 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.379 ms/op
                 createUser·p0.999:  10.384 ms/op
                 createUser·p0.9999: 23.473 ms/op
                 createUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321477
  mean =      2.987 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30310 
    [ 2.500,  5.000) = 289928 
    [ 5.000,  7.500) = 866 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.254 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.859 ±(99.9%) 0.006 ms/op
Iteration   1: 2.836 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  9.232 ms/op
                 existUser·p0.9999: 12.812 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   2: 2.893 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  8.961 ms/op
                 existUser·p0.9999: 22.412 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 2.838 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.122 ms/op
                 existUser·p0.9999: 25.157 ms/op
                 existUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335958
  mean =      2.855 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56024 
    [ 2.500,  5.000) = 278871 
    [ 5.000,  7.500) = 704 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.352 ms/op
     p(99.9900) =     23.980 ms/op
     p(99.9990) =     25.330 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 3.456 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  10.056 ms/op
                 getUser·p0.9999: 12.612 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.264 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.725 ms/op
                 getUser·p0.9999: 14.111 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.004 ms/op
                 getUser·p0.9999: 14.590 ms/op
                 getUser·p1.00:   15.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319762
  mean =      3.002 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2046 
    [ 1.250,  2.500) = 26220 
    [ 2.500,  3.750) = 274294 
    [ 3.750,  5.000) = 15695 
    [ 5.000,  6.250) = 690 
    [ 6.250,  7.500) = 406 
    [ 7.500,  8.750) = 144 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.264 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.169 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     15.057 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 4.783 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.011 ms/op
Iteration   1: 3.906 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.238 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 3.875 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.900 ms/op
                 listUser·p0.9999: 19.783 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   3: 3.854 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.891 ms/op
                 listUser·p0.9999: 22.020 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247722
  mean =      3.878 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5827 
    [ 2.500,  5.000) = 220079 
    [ 5.000,  7.500) = 20586 
    [ 7.500, 10.000) = 750 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     14.242 ms/op
     p(99.9900) =     21.216 ms/op
     p(99.9990) =     22.317 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.707 ± 2.212  ops/ms
ClientGrpc.existUser                       thrpt       3  11.307 ± 2.262  ops/ms
ClientGrpc.getUser                         thrpt       3  10.600 ± 1.435  ops/ms
ClientGrpc.listUser                        thrpt       3   8.205 ± 0.366  ops/ms
ClientGrpc.createUser                       avgt       3   2.948 ± 0.569   ms/op
ClientGrpc.existUser                        avgt       3   2.863 ± 0.704   ms/op
ClientGrpc.getUser                          avgt       3   2.960 ± 0.531   ms/op
ClientGrpc.listUser                         avgt       3   3.878 ± 0.713   ms/op
ClientGrpc.createUser                     sample  321477   2.987 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.525           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.254           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.167           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.542           ms/op
ClientGrpc.existUser                      sample  335958   2.855 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.558           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.352           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.980           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.395           ms/op
ClientGrpc.getUser                        sample  319762   3.002 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.264           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.169           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.041           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.204           ms/op
ClientGrpc.listUser                       sample  247722   3.878 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.831           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.242           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.216           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.479           ms/op
