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
# Warmup Iteration   1: 3.961 ops/ms
# Warmup Iteration   2: 9.237 ops/ms
# Warmup Iteration   3: 10.330 ops/ms
Iteration   1: 10.659 ops/ms
Iteration   2: 10.560 ops/ms
Iteration   3: 10.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.725 ±(99.9%) 3.778 ops/ms [Average]
  (min, avg, max) = (10.560, 10.725, 10.957), stdev = 0.207
  CI (99.9%): [6.947, 14.503] (assumes normal distribution)


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
# Warmup Iteration   1: 7.240 ops/ms
# Warmup Iteration   2: 10.798 ops/ms
# Warmup Iteration   3: 10.921 ops/ms
Iteration   1: 11.121 ops/ms
Iteration   2: 11.053 ops/ms
Iteration   3: 11.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.133 ±(99.9%) 1.581 ops/ms [Average]
  (min, avg, max) = (11.053, 11.133, 11.225), stdev = 0.087
  CI (99.9%): [9.552, 12.714] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.961 ops/ms
# Warmup Iteration   2: 10.282 ops/ms
# Warmup Iteration   3: 10.379 ops/ms
Iteration   1: 10.344 ops/ms
Iteration   2: 10.516 ops/ms
Iteration   3: 10.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.452 ±(99.9%) 1.718 ops/ms [Average]
  (min, avg, max) = (10.344, 10.452, 10.516), stdev = 0.094
  CI (99.9%): [8.735, 12.170] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.413 ops/ms
# Warmup Iteration   2: 7.649 ops/ms
# Warmup Iteration   3: 8.016 ops/ms
Iteration   1: 7.999 ops/ms
Iteration   2: 8.196 ops/ms
Iteration   3: 8.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.116 ±(99.9%) 1.882 ops/ms [Average]
  (min, avg, max) = (7.999, 8.116, 8.196), stdev = 0.103
  CI (99.9%): [6.234, 9.997] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.335 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.002 ms/op
Iteration   1: 3.042 ±(99.9%) 0.004 ms/op
Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
Iteration   3: 3.028 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.040 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (3.028, 3.040, 3.049), stdev = 0.011
  CI (99.9%): [2.842, 3.237] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.066 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.002 ms/op
Iteration   1: 2.904 ±(99.9%) 0.003 ms/op
Iteration   2: 2.884 ±(99.9%) 0.003 ms/op
Iteration   3: 2.873 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.887 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.873, 2.887, 2.904), stdev = 0.016
  CI (99.9%): [2.602, 3.172] (assumes normal distribution)


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
# Warmup Iteration   1: 4.252 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.003 ms/op
Iteration   1: 3.029 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.004 ms/op
Iteration   3: 3.000 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.003 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (2.981, 3.003, 3.029), stdev = 0.024
  CI (99.9%): [2.566, 3.441] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.547 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.014 ms/op
Iteration   1: 3.916 ±(99.9%) 0.008 ms/op
Iteration   2: 3.857 ±(99.9%) 0.042 ms/op
Iteration   3: 3.955 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.909 ±(99.9%) 0.905 ms/op [Average]
  (min, avg, max) = (3.857, 3.909, 3.955), stdev = 0.050
  CI (99.9%): [3.005, 4.814] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.296 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.554 ms/op
                 createUser·p0.9999: 21.266 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.649 ms/op
                 createUser·p0.9999: 28.049 ms/op
                 createUser·p1.00:   28.541 ms/op

Iteration   3: 2.982 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  9.224 ms/op
                 createUser·p0.9999: 22.654 ms/op
                 createUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321424
  mean =      2.986 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30366 
    [ 2.500,  5.000) = 289294 
    [ 5.000,  7.500) = 1361 
    [ 7.500, 10.000) = 167 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     26.923 ms/op
     p(99.9990) =     28.403 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.031 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.006 ms/op
Iteration   1: 2.873 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.018 ms/op
                 existUser·p0.999:  7.493 ms/op
                 existUser·p0.9999: 13.384 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   2: 2.862 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  6.439 ms/op
                 existUser·p0.9999: 13.206 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   3: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  6.302 ms/op
                 existUser·p0.9999: 16.503 ms/op
                 existUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331964
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 605 
    [ 1.250,  2.500) = 38454 
    [ 2.500,  3.750) = 286828 
    [ 3.750,  5.000) = 5346 
    [ 5.000,  6.250) = 293 
    [ 6.250,  7.500) = 208 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      6.701 ms/op
     p(99.9900) =     16.109 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 4.320 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.595 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  7.396 ms/op
                 getUser·p0.9999: 13.154 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  7.143 ms/op
                 getUser·p0.9999: 21.736 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.542 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.838 ms/op
                 getUser·p0.9999: 18.002 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320109
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30400 
    [ 2.500,  5.000) = 288300 
    [ 5.000,  7.500) = 1139 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      7.176 ms/op
     p(99.9900) =     20.527 ms/op
     p(99.9990) =     22.918 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 5.341 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.011 ms/op
Iteration   1: 3.978 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.350 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.246 ms/op
                 listUser·p0.999:  14.752 ms/op
                 listUser·p0.9999: 21.560 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 3.979 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  17.633 ms/op
                 listUser·p0.9999: 20.379 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 3.957 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.290 ms/op
                 listUser·p0.9999: 28.432 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241778
  mean =      3.971 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2971 
    [ 2.500,  5.000) = 215026 
    [ 5.000,  7.500) = 22188 
    [ 7.500, 10.000) = 1031 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.350 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     15.421 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     29.529 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.725 ± 3.778  ops/ms
ClientGrpc.existUser                       thrpt       3  11.133 ± 1.581  ops/ms
ClientGrpc.getUser                         thrpt       3  10.452 ± 1.718  ops/ms
ClientGrpc.listUser                        thrpt       3   8.116 ± 1.882  ops/ms
ClientGrpc.createUser                       avgt       3   3.040 ± 0.198   ms/op
ClientGrpc.existUser                        avgt       3   2.887 ± 0.285   ms/op
ClientGrpc.getUser                          avgt       3   3.003 ± 0.437   ms/op
ClientGrpc.listUser                         avgt       3   3.909 ± 0.905   ms/op
ClientGrpc.createUser                     sample  321424   2.986 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.662           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.651           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.923           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.541           ms/op
ClientGrpc.existUser                      sample  331964   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.556           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.701           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.109           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.843           ms/op
ClientGrpc.getUser                        sample  320109   2.997 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.542           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.176           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.527           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.167           ms/op
ClientGrpc.listUser                       sample  241778   3.971 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.350           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.421           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.689           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.655           ms/op
