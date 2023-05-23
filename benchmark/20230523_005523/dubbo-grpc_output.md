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
# Warmup Iteration   1: 4.117 ops/ms
# Warmup Iteration   2: 8.895 ops/ms
# Warmup Iteration   3: 10.066 ops/ms
Iteration   1: 10.607 ops/ms
Iteration   2: 10.321 ops/ms
Iteration   3: 10.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.510 ±(99.9%) 2.998 ops/ms [Average]
  (min, avg, max) = (10.321, 10.510, 10.607), stdev = 0.164
  CI (99.9%): [7.512, 13.508] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.278 ops/ms
# Warmup Iteration   2: 10.472 ops/ms
# Warmup Iteration   3: 10.957 ops/ms
Iteration   1: 11.030 ops/ms
Iteration   2: 11.075 ops/ms
Iteration   3: 11.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.052 ±(99.9%) 0.416 ops/ms [Average]
  (min, avg, max) = (11.030, 11.052, 11.075), stdev = 0.023
  CI (99.9%): [10.636, 11.468] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.771 ops/ms
# Warmup Iteration   2: 9.977 ops/ms
# Warmup Iteration   3: 10.417 ops/ms
Iteration   1: 10.611 ops/ms
Iteration   2: 10.656 ops/ms
Iteration   3: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.662 ±(99.9%) 0.997 ops/ms [Average]
  (min, avg, max) = (10.611, 10.662, 10.719), stdev = 0.055
  CI (99.9%): [9.665, 11.659] (assumes normal distribution)


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
# Warmup Iteration   1: 5.188 ops/ms
# Warmup Iteration   2: 7.843 ops/ms
# Warmup Iteration   3: 8.050 ops/ms
Iteration   1: 8.080 ops/ms
Iteration   2: 8.341 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.190 ±(99.9%) 2.467 ops/ms [Average]
  (min, avg, max) = (8.080, 8.190, 8.341), stdev = 0.135
  CI (99.9%): [5.723, 10.657] (assumes normal distribution)


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
# Warmup Iteration   1: 4.712 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.002 ms/op
Iteration   1: 3.059 ±(99.9%) 0.003 ms/op
Iteration   2: 3.044 ±(99.9%) 0.003 ms/op
Iteration   3: 3.052 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.052 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (3.044, 3.052, 3.059), stdev = 0.008
  CI (99.9%): [2.909, 3.194] (assumes normal distribution)


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
# Warmup Iteration   1: 3.810 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.003 ms/op
Iteration   1: 2.874 ±(99.9%) 0.003 ms/op
Iteration   2: 2.864 ±(99.9%) 0.002 ms/op
Iteration   3: 2.876 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.871 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (2.864, 2.871, 2.876), stdev = 0.006
  CI (99.9%): [2.755, 2.988] (assumes normal distribution)


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
# Warmup Iteration   1: 4.331 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.002 ms/op
Iteration   1: 3.025 ±(99.9%) 0.003 ms/op
Iteration   2: 3.019 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.007 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (2.976, 3.007, 3.025), stdev = 0.027
  CI (99.9%): [2.517, 3.496] (assumes normal distribution)


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
# Warmup Iteration   1: 5.513 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.018 ms/op
Iteration   1: 3.955 ±(99.9%) 0.019 ms/op
Iteration   2: 3.922 ±(99.9%) 0.011 ms/op
Iteration   3: 3.919 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.932 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (3.919, 3.932, 3.955), stdev = 0.020
  CI (99.9%): [3.566, 4.298] (assumes normal distribution)


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
# Warmup Iteration   1: 4.419 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  9.580 ms/op
                 createUser·p0.9999: 14.024 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.882 ms/op
                 createUser·p0.9999: 21.621 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  6.816 ms/op
                 createUser·p0.9999: 24.651 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318243
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26262 
    [ 2.500,  5.000) = 290222 
    [ 5.000,  7.500) = 1347 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.832 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     24.957 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 3.699 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
Iteration   1: 2.875 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  6.592 ms/op
                 existUser·p0.9999: 17.433 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   2: 2.857 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.310 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  6.975 ms/op
                 existUser·p0.9999: 14.074 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   3: 2.880 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  9.898 ms/op
                 existUser·p0.9999: 18.114 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334424
  mean =      2.871 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1462 
    [ 1.250,  2.500) = 41916 
    [ 2.500,  3.750) = 283933 
    [ 3.750,  5.000) = 6169 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 225 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.096 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     18.186 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.281 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
Iteration   1: 3.013 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.732 ms/op
                 getUser·p0.9999: 31.949 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   2: 3.019 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.426 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.937 ms/op
                 getUser·p0.9999: 24.438 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  10.699 ms/op
                 getUser·p0.9999: 21.710 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316972
  mean =      3.027 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24064 
    [ 2.500,  5.000) = 291285 
    [ 5.000,  7.500) = 1219 
    [ 7.500, 10.000) = 148 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.045 ms/op
     p(99.9900) =     31.412 ms/op
     p(99.9990) =     32.107 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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
# Warmup Iteration   1: 5.185 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.011 ms/op
Iteration   1: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.598 ms/op
                 listUser·p0.9999: 20.221 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.811 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  16.186 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 3.964 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.728 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  18.323 ms/op
                 listUser·p0.9999: 22.607 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240677
  mean =      3.989 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2701 
    [ 2.500,  5.000) = 214647 
    [ 5.000,  7.500) = 21948 
    [ 7.500, 10.000) = 951 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.510 ± 2.998  ops/ms
ClientGrpc.existUser                       thrpt       3  11.052 ± 0.416  ops/ms
ClientGrpc.getUser                         thrpt       3  10.662 ± 0.997  ops/ms
ClientGrpc.listUser                        thrpt       3   8.190 ± 2.467  ops/ms
ClientGrpc.createUser                       avgt       3   3.052 ± 0.142   ms/op
ClientGrpc.existUser                        avgt       3   2.871 ± 0.116   ms/op
ClientGrpc.getUser                          avgt       3   3.007 ± 0.489   ms/op
ClientGrpc.listUser                         avgt       3   3.932 ± 0.366   ms/op
ClientGrpc.createUser                     sample  318243   3.016 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.641           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.498           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.832           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.003           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.166           ms/op
ClientGrpc.existUser                      sample  334424   2.871 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.699           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.096           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.594           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.465           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  316972   3.027 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.426           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.045           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.412           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.145           ms/op
ClientGrpc.listUser                       sample  240677   3.989 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.728           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.482           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.922           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.069           ms/op
