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
# Warmup Iteration   1: 4.115 ops/ms
# Warmup Iteration   2: 8.974 ops/ms
# Warmup Iteration   3: 10.113 ops/ms
Iteration   1: 10.305 ops/ms
Iteration   2: 10.390 ops/ms
Iteration   3: 10.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.450 ±(99.9%) 3.349 ops/ms [Average]
  (min, avg, max) = (10.305, 10.450, 10.656), stdev = 0.184
  CI (99.9%): [7.101, 13.799] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.514 ops/ms
# Warmup Iteration   2: 10.612 ops/ms
# Warmup Iteration   3: 10.756 ops/ms
Iteration   1: 11.144 ops/ms
Iteration   2: 11.071 ops/ms
Iteration   3: 11.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.139 ±(99.9%) 1.206 ops/ms [Average]
  (min, avg, max) = (11.071, 11.139, 11.203), stdev = 0.066
  CI (99.9%): [9.934, 12.345] (assumes normal distribution)


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
# Warmup Iteration   1: 7.549 ops/ms
# Warmup Iteration   2: 9.910 ops/ms
# Warmup Iteration   3: 10.443 ops/ms
Iteration   1: 10.392 ops/ms
Iteration   2: 10.593 ops/ms
Iteration   3: 10.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.492 ±(99.9%) 1.831 ops/ms [Average]
  (min, avg, max) = (10.392, 10.492, 10.593), stdev = 0.100
  CI (99.9%): [8.661, 12.323] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.884 ops/ms
# Warmup Iteration   2: 7.655 ops/ms
# Warmup Iteration   3: 7.997 ops/ms
Iteration   1: 8.137 ops/ms
Iteration   2: 8.123 ops/ms
Iteration   3: 8.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.112 ±(99.9%) 0.583 ops/ms [Average]
  (min, avg, max) = (8.076, 8.112, 8.137), stdev = 0.032
  CI (99.9%): [7.530, 8.695] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.371 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.001 ms/op
Iteration   1: 3.038 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
Iteration   3: 2.916 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.990 ±(99.9%) 1.195 ms/op [Average]
  (min, avg, max) = (2.916, 2.990, 3.038), stdev = 0.066
  CI (99.9%): [1.795, 4.186] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.920 ±(99.9%) 0.003 ms/op
Iteration   1: 2.930 ±(99.9%) 0.003 ms/op
Iteration   2: 2.895 ±(99.9%) 0.003 ms/op
Iteration   3: 2.879 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.902 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (2.879, 2.902, 2.930), stdev = 0.026
  CI (99.9%): [2.424, 3.379] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.200 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.004 ms/op
Iteration   1: 3.066 ±(99.9%) 0.002 ms/op
Iteration   2: 2.976 ±(99.9%) 0.003 ms/op
Iteration   3: 3.013 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.018 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (2.976, 3.018, 3.066), stdev = 0.045
  CI (99.9%): [2.201, 3.836] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.625 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.010 ms/op
Iteration   1: 3.951 ±(99.9%) 0.015 ms/op
Iteration   2: 3.894 ±(99.9%) 0.011 ms/op
Iteration   3: 3.973 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.939 ±(99.9%) 0.743 ms/op [Average]
  (min, avg, max) = (3.894, 3.939, 3.973), stdev = 0.041
  CI (99.9%): [3.196, 4.683] (assumes normal distribution)


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.077 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  7.685 ms/op
                 createUser·p0.9999: 30.809 ms/op
                 createUser·p1.00:   31.719 ms/op

Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.815 ms/op
                 createUser·p0.9999: 19.581 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   3: 3.051 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.898 ms/op
                 createUser·p0.999:  10.112 ms/op
                 createUser·p0.9999: 24.086 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313109
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26732 
    [ 2.500,  5.000) = 284035 
    [ 5.000,  7.500) = 1805 
    [ 7.500, 10.000) = 289 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      8.827 ms/op
     p(99.9900) =     30.202 ms/op
     p(99.9990) =     31.641 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  8.946 ms/op
                 existUser·p0.9999: 18.354 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   2: 2.894 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  6.783 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  8.161 ms/op
                 existUser·p0.9999: 15.813 ms/op
                 existUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328721
  mean =      2.918 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1304 
    [ 1.250,  2.500) = 35972 
    [ 2.500,  3.750) = 281717 
    [ 3.750,  5.000) = 8054 
    [ 5.000,  6.250) = 880 
    [ 6.250,  7.500) = 375 
    [ 7.500,  8.750) = 165 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.104 ms/op
     p(99.9900) =     16.621 ms/op
     p(99.9990) =     18.603 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
Iteration   1: 2.994 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.676 ms/op
                 getUser·p0.9999: 27.984 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   2: 2.983 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.322 ms/op
                 getUser·p0.95:   3.502 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.740 ms/op
                 getUser·p0.9999: 18.022 ms/op
                 getUser·p1.00:   18.678 ms/op

Iteration   3: 3.025 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  8.950 ms/op
                 getUser·p0.9999: 36.962 ms/op
                 getUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319661
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23737 
    [ 2.500,  5.000) = 294012 
    [ 5.000,  7.500) = 1504 
    [ 7.500, 10.000) = 241 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.908 ms/op
     p(99.9900) =     34.275 ms/op
     p(99.9990) =     37.159 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 5.355 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.011 ms/op
Iteration   1: 3.931 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  14.838 ms/op
                 listUser·p0.9999: 18.308 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   2: 3.932 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  14.161 ms/op
                 listUser·p0.9999: 15.380 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   3: 3.905 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.183 ms/op
                 listUser·p0.9999: 24.034 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244475
  mean =      3.922 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4362 
    [ 2.500,  5.000) = 216989 
    [ 5.000,  7.500) = 21364 
    [ 7.500, 10.000) = 1191 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.137 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     22.661 ms/op
     p(99.9990) =     25.151 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.450 ± 3.349  ops/ms
ClientGrpc.existUser                       thrpt       3  11.139 ± 1.206  ops/ms
ClientGrpc.getUser                         thrpt       3  10.492 ± 1.831  ops/ms
ClientGrpc.listUser                        thrpt       3   8.112 ± 0.583  ops/ms
ClientGrpc.createUser                       avgt       3   2.990 ± 1.195   ms/op
ClientGrpc.existUser                        avgt       3   2.902 ± 0.477   ms/op
ClientGrpc.getUser                          avgt       3   3.018 ± 0.817   ms/op
ClientGrpc.listUser                         avgt       3   3.939 ± 0.743   ms/op
ClientGrpc.createUser                     sample  313109   3.065 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.613           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.727           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.827           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.202           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.719           ms/op
ClientGrpc.existUser                      sample  328721   2.918 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.640           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.104           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.621           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.678           ms/op
ClientGrpc.getUser                        sample  319661   3.001 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.546           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.908           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.275           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.159           ms/op
ClientGrpc.listUser                       sample  244475   3.922 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.921           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.137           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.615           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.661           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.166           ms/op
