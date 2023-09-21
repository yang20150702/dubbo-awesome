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
# Warmup Iteration   1: 4.739 ops/ms
# Warmup Iteration   2: 9.500 ops/ms
# Warmup Iteration   3: 9.822 ops/ms
Iteration   1: 10.288 ops/ms
Iteration   2: 10.004 ops/ms
Iteration   3: 10.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.152 ±(99.9%) 2.601 ops/ms [Average]
  (min, avg, max) = (10.004, 10.152, 10.288), stdev = 0.143
  CI (99.9%): [7.551, 12.753] (assumes normal distribution)


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
# Warmup Iteration   1: 8.050 ops/ms
# Warmup Iteration   2: 10.378 ops/ms
# Warmup Iteration   3: 10.623 ops/ms
Iteration   1: 10.693 ops/ms
Iteration   2: 10.712 ops/ms
Iteration   3: 10.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.644 ±(99.9%) 1.849 ops/ms [Average]
  (min, avg, max) = (10.528, 10.644, 10.712), stdev = 0.101
  CI (99.9%): [8.796, 12.493] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.651 ops/ms
# Warmup Iteration   2: 10.150 ops/ms
# Warmup Iteration   3: 10.247 ops/ms
Iteration   1: 10.237 ops/ms
Iteration   2: 10.059 ops/ms
Iteration   3: 10.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.153 ±(99.9%) 1.625 ops/ms [Average]
  (min, avg, max) = (10.059, 10.153, 10.237), stdev = 0.089
  CI (99.9%): [8.528, 11.777] (assumes normal distribution)


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
# Warmup Iteration   1: 6.419 ops/ms
# Warmup Iteration   2: 8.189 ops/ms
# Warmup Iteration   3: 8.421 ops/ms
Iteration   1: 8.457 ops/ms
Iteration   2: 8.627 ops/ms
Iteration   3: 8.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.540 ±(99.9%) 1.555 ops/ms [Average]
  (min, avg, max) = (8.457, 8.540, 8.627), stdev = 0.085
  CI (99.9%): [6.985, 10.095] (assumes normal distribution)


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.002 ms/op
Iteration   1: 3.114 ±(99.9%) 0.011 ms/op
Iteration   2: 3.066 ±(99.9%) 0.002 ms/op
Iteration   3: 3.148 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.109 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (3.066, 3.109, 3.148), stdev = 0.041
  CI (99.9%): [2.355, 3.864] (assumes normal distribution)


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.002 ms/op
Iteration   1: 2.941 ±(99.9%) 0.004 ms/op
Iteration   2: 3.022 ±(99.9%) 0.002 ms/op
Iteration   3: 2.961 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (2.941, 2.974, 3.022), stdev = 0.042
  CI (99.9%): [2.210, 3.739] (assumes normal distribution)


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
# Warmup Iteration   1: 3.364 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.002 ms/op
Iteration   2: 3.058 ±(99.9%) 0.003 ms/op
Iteration   3: 3.164 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.093 ±(99.9%) 1.136 ms/op [Average]
  (min, avg, max) = (3.055, 3.093, 3.164), stdev = 0.062
  CI (99.9%): [1.956, 4.229] (assumes normal distribution)


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
# Warmup Iteration   1: 4.924 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.036 ms/op
Iteration   1: 3.700 ±(99.9%) 0.024 ms/op
Iteration   2: 3.673 ±(99.9%) 0.009 ms/op
Iteration   3: 3.765 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.712 ±(99.9%) 0.861 ms/op [Average]
  (min, avg, max) = (3.673, 3.712, 3.765), stdev = 0.047
  CI (99.9%): [2.852, 4.573] (assumes normal distribution)


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.006 ms/op
Iteration   1: 3.076 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.109 ms/op
                 createUser·p0.9999: 15.247 ms/op
                 createUser·p1.00:   16.040 ms/op

Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.209 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.762 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.463 ms/op
                 createUser·p0.9999: 20.932 ms/op
                 createUser·p1.00:   21.398 ms/op

Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 17.390 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309051
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12454 
    [ 2.500,  5.000) = 294723 
    [ 5.000,  7.500) = 1564 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.209 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.504 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     21.263 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 2.966 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  6.898 ms/op
                 existUser·p0.9999: 14.127 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.980 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  9.890 ms/op
                 existUser·p0.9999: 15.164 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.659 ms/op
                 existUser·p0.9999: 18.235 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322612
  mean =      2.974 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 735 
    [ 1.250,  2.500) = 19189 
    [ 2.500,  3.750) = 290935 
    [ 3.750,  5.000) = 10395 
    [ 5.000,  6.250) = 720 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      8.166 ms/op
     p(99.9900) =     16.989 ms/op
     p(99.9990) =     19.719 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
Iteration   1: 3.127 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.590 ms/op
                 getUser·p0.999:  9.579 ms/op
                 getUser·p0.9999: 11.363 ms/op
                 getUser·p1.00:   11.944 ms/op

Iteration   2: 3.082 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.881 ms/op
                 getUser·p0.9999: 12.190 ms/op
                 getUser·p1.00:   12.337 ms/op

Iteration   3: 3.064 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.496 ms/op
                 getUser·p0.9999: 14.254 ms/op
                 getUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310467
  mean =      3.091 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 582 
    [ 1.250,  2.500) = 10517 
    [ 2.500,  3.750) = 278356 
    [ 3.750,  5.000) = 19519 
    [ 5.000,  6.250) = 782 
    [ 6.250,  7.500) = 397 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.549 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     14.509 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 4.876 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.869 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.009 ms/op
Iteration   1: 3.758 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  14.365 ms/op
                 listUser·p0.9999: 16.367 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   2: 3.761 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.267 ms/op
                 listUser·p0.999:  12.632 ms/op
                 listUser·p0.9999: 14.401 ms/op
                 listUser·p1.00:   14.713 ms/op

Iteration   3: 3.754 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.194 ms/op
                 listUser·p0.999:  13.229 ms/op
                 listUser·p0.9999: 15.720 ms/op
                 listUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 255379
  mean =      3.757 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 2964 
    [ 2.500,  3.750) = 145495 
    [ 3.750,  5.000) = 96667 
    [ 5.000,  6.250) = 7373 
    [ 6.250,  7.500) = 1987 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 156 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 164 
    [13.750, 15.000) = 99 
    [15.000, 16.250) = 75 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     15.925 ms/op
     p(99.9990) =     17.541 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.152 ± 2.601  ops/ms
ClientGrpc.existUser                       thrpt       3  10.644 ± 1.849  ops/ms
ClientGrpc.getUser                         thrpt       3  10.153 ± 1.625  ops/ms
ClientGrpc.listUser                        thrpt       3   8.540 ± 1.555  ops/ms
ClientGrpc.createUser                       avgt       3   3.109 ± 0.754   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 0.765   ms/op
ClientGrpc.getUser                          avgt       3   3.093 ± 1.136   ms/op
ClientGrpc.listUser                         avgt       3   3.712 ± 0.861   ms/op
ClientGrpc.createUser                     sample  309051   3.106 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.209           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.504           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.564           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.398           ms/op
ClientGrpc.existUser                      sample  322612   2.974 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.660           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.166           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.989           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.825           ms/op
ClientGrpc.getUser                        sample  310467   3.091 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.639           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.549           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.877           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.647           ms/op
ClientGrpc.listUser                       sample  255379   3.757 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.844           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.682           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.166           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.308           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.156           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.925           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.547           ms/op
