# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.198 ops/ms
# Warmup Iteration   2: 8.983 ops/ms
# Warmup Iteration   3: 9.760 ops/ms
Iteration   1: 10.268 ops/ms
Iteration   2: 10.016 ops/ms
Iteration   3: 10.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.276 ±(99.9%) 4.812 ops/ms [Average]
  (min, avg, max) = (10.016, 10.276, 10.543), stdev = 0.264
  CI (99.9%): [5.464, 15.087] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.728 ops/ms
# Warmup Iteration   2: 10.600 ops/ms
# Warmup Iteration   3: 10.924 ops/ms
Iteration   1: 10.933 ops/ms
Iteration   2: 11.069 ops/ms
Iteration   3: 10.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.996 ±(99.9%) 1.248 ops/ms [Average]
  (min, avg, max) = (10.933, 10.996, 11.069), stdev = 0.068
  CI (99.9%): [9.748, 12.245] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.184 ops/ms
# Warmup Iteration   2: 9.818 ops/ms
# Warmup Iteration   3: 10.318 ops/ms
Iteration   1: 10.186 ops/ms
Iteration   2: 9.923 ops/ms
Iteration   3: 10.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.158 ±(99.9%) 4.053 ops/ms [Average]
  (min, avg, max) = (9.923, 10.158, 10.364), stdev = 0.222
  CI (99.9%): [6.105, 14.211] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.212 ops/ms
# Warmup Iteration   2: 7.612 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 7.806 ops/ms
Iteration   2: 8.050 ops/ms
Iteration   3: 7.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.913 ±(99.9%) 2.279 ops/ms [Average]
  (min, avg, max) = (7.806, 7.913, 8.050), stdev = 0.125
  CI (99.9%): [5.633, 10.192] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.248 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.001 ms/op
Iteration   1: 3.132 ±(99.9%) 0.002 ms/op
Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
Iteration   3: 3.133 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.118 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.088, 3.118, 3.133), stdev = 0.026
  CI (99.9%): [2.645, 3.590] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.141 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.003 ms/op
Iteration   1: 2.889 ±(99.9%) 0.003 ms/op
Iteration   2: 2.905 ±(99.9%) 0.003 ms/op
Iteration   3: 2.913 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.902 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.889, 2.902, 2.913), stdev = 0.012
  CI (99.9%): [2.684, 3.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.123 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.003 ms/op
Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
Iteration   3: 3.125 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.096 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.070, 3.096, 3.125), stdev = 0.028
  CI (99.9%): [2.592, 3.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.291 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.025 ms/op
Iteration   1: 4.122 ±(99.9%) 0.017 ms/op
Iteration   2: 4.046 ±(99.9%) 0.014 ms/op
Iteration   3: 3.953 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.040 ±(99.9%) 1.538 ms/op [Average]
  (min, avg, max) = (3.953, 4.040, 4.122), stdev = 0.084
  CI (99.9%): [2.502, 5.579] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.313 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
Iteration   1: 3.077 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  8.291 ms/op
                 createUser·p0.9999: 14.668 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  8.296 ms/op
                 createUser·p0.9999: 13.891 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   3: 3.041 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  9.249 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311138
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18627 
    [ 2.500,  5.000) = 290259 
    [ 5.000,  7.500) = 1761 
    [ 7.500, 10.000) = 229 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      8.370 ms/op
     p(99.9900) =     19.883 ms/op
     p(99.9990) =     20.735 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.873 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
Iteration   1: 2.954 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 12.673 ms/op
                 existUser·p1.00:   12.993 ms/op

Iteration   2: 2.945 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  6.655 ms/op
                 existUser·p0.9999: 12.651 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   3: 2.921 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  11.616 ms/op
                 existUser·p0.9999: 15.812 ms/op
                 existUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326323
  mean =      2.940 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2181 
    [ 1.250,  2.500) = 32014 
    [ 2.500,  3.750) = 279043 
    [ 3.750,  5.000) = 11721 
    [ 5.000,  6.250) = 664 
    [ 6.250,  7.500) = 331 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.447 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.064 ms/op
     p(99.9900) =     15.352 ms/op
     p(99.9990) =     16.076 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.893 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
Iteration   1: 3.120 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  11.272 ms/op
                 getUser·p0.9999: 14.320 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.387 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  8.137 ms/op
                 getUser·p0.9999: 13.625 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.507 ms/op
                 getUser·p0.9999: 16.652 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312839
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1356 
    [ 1.250,  2.500) = 17698 
    [ 2.500,  3.750) = 273974 
    [ 3.750,  5.000) = 17534 
    [ 5.000,  6.250) = 1340 
    [ 6.250,  7.500) = 392 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     15.960 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.378 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
Iteration   1: 3.920 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.376 ms/op
                 listUser·p0.9999: 18.428 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   2: 3.778 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.194 ms/op
                 listUser·p0.9999: 16.205 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 4.031 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.641 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.213 ms/op
                 listUser·p0.9999: 17.653 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245699
  mean =      3.907 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 4254 
    [ 2.500,  3.750) = 116285 
    [ 3.750,  5.000) = 103232 
    [ 5.000,  6.250) = 15945 
    [ 6.250,  7.500) = 4593 
    [ 7.500,  8.750) = 770 
    [ 8.750, 10.000) = 167 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 101 
    [15.000, 16.250) = 97 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     18.153 ms/op
     p(99.9990) =     18.779 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.276 ± 4.812  ops/ms
ClientGrpc.existUser                       thrpt       3  10.996 ± 1.248  ops/ms
ClientGrpc.getUser                         thrpt       3  10.158 ± 4.053  ops/ms
ClientGrpc.listUser                        thrpt       3   7.913 ± 2.279  ops/ms
ClientGrpc.createUser                       avgt       3   3.118 ± 0.472   ms/op
ClientGrpc.existUser                        avgt       3   2.902 ± 0.219   ms/op
ClientGrpc.getUser                          avgt       3   3.096 ± 0.504   ms/op
ClientGrpc.listUser                         avgt       3   4.040 ± 1.538   ms/op
ClientGrpc.createUser                     sample  311138   3.085 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.753           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.727           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.370           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.883           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.906           ms/op
ClientGrpc.existUser                      sample  326323   2.940 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.733           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.447           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.064           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.352           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.204           ms/op
ClientGrpc.getUser                        sample  312839   3.069 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.387           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.028           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.960           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.186           ms/op
ClientGrpc.listUser                       sample  245699   3.907 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.641           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.172           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.153           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.874           ms/op
