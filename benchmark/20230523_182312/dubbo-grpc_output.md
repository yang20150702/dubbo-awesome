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
# Warmup Iteration   1: 4.455 ops/ms
# Warmup Iteration   2: 9.135 ops/ms
# Warmup Iteration   3: 10.169 ops/ms
Iteration   1: 10.540 ops/ms
Iteration   2: 10.486 ops/ms
Iteration   3: 10.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.488 ±(99.9%) 0.931 ops/ms [Average]
  (min, avg, max) = (10.438, 10.488, 10.540), stdev = 0.051
  CI (99.9%): [9.557, 11.418] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.372 ops/ms
# Warmup Iteration   2: 10.823 ops/ms
# Warmup Iteration   3: 11.082 ops/ms
Iteration   1: 11.256 ops/ms
Iteration   2: 11.078 ops/ms
Iteration   3: 11.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.188 ±(99.9%) 1.749 ops/ms [Average]
  (min, avg, max) = (11.078, 11.188, 11.256), stdev = 0.096
  CI (99.9%): [9.439, 12.936] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.220 ops/ms
# Warmup Iteration   2: 10.334 ops/ms
# Warmup Iteration   3: 10.517 ops/ms
Iteration   1: 10.631 ops/ms
Iteration   2: 10.670 ops/ms
Iteration   3: 10.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.637 ±(99.9%) 0.545 ops/ms [Average]
  (min, avg, max) = (10.611, 10.637, 10.670), stdev = 0.030
  CI (99.9%): [10.092, 11.182] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.063 ops/ms
# Warmup Iteration   2: 7.879 ops/ms
# Warmup Iteration   3: 8.157 ops/ms
Iteration   1: 8.145 ops/ms
Iteration   2: 8.327 ops/ms
Iteration   3: 8.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.276 ±(99.9%) 2.076 ops/ms [Average]
  (min, avg, max) = (8.145, 8.276, 8.355), stdev = 0.114
  CI (99.9%): [6.199, 10.352] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.050 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 3.017 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
Iteration   3: 2.994 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.994, 3.013, 3.028), stdev = 0.018
  CI (99.9%): [2.689, 3.337] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.516 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.003 ms/op
Iteration   1: 2.954 ±(99.9%) 0.003 ms/op
Iteration   2: 2.920 ±(99.9%) 0.003 ms/op
Iteration   3: 2.865 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.913 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (2.865, 2.913, 2.954), stdev = 0.045
  CI (99.9%): [2.092, 3.734] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.002 ms/op
Iteration   1: 2.976 ±(99.9%) 0.002 ms/op
Iteration   2: 3.007 ±(99.9%) 0.002 ms/op
Iteration   3: 2.985 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.989 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.976, 2.989, 3.007), stdev = 0.016
  CI (99.9%): [2.697, 3.281] (assumes normal distribution)


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
# Warmup Iteration   1: 4.833 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.015 ms/op
Iteration   1: 3.946 ±(99.9%) 0.042 ms/op
Iteration   2: 3.917 ±(99.9%) 0.007 ms/op
Iteration   3: 3.890 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.918 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (3.890, 3.918, 3.946), stdev = 0.028
  CI (99.9%): [3.413, 4.423] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.007 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.313 ms/op
                 createUser·p0.9999: 14.746 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.875 ms/op
                 createUser·p0.9999: 16.596 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  12.072 ms/op
                 createUser·p0.9999: 20.774 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317328
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25860 
    [ 2.500,  5.000) = 289686 
    [ 5.000,  7.500) = 1380 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      9.033 ms/op
     p(99.9900) =     18.507 ms/op
     p(99.9990) =     21.130 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.005 ms/op
Iteration   1: 2.875 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  5.853 ms/op
                 existUser·p0.9999: 12.188 ms/op
                 existUser·p1.00:   12.435 ms/op

Iteration   2: 2.910 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.449 ms/op
                 existUser·p0.9999: 14.517 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  6.528 ms/op
                 existUser·p0.9999: 25.197 ms/op
                 existUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331464
  mean =      2.894 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43281 
    [ 2.500,  5.000) = 287157 
    [ 5.000,  7.500) = 853 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.255 ms/op
     p(99.9900) =     18.083 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.437 ms/op
                 getUser·p0.9999: 14.050 ms/op
                 getUser·p1.00:   15.958 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.053 ms/op
                 getUser·p0.9999: 18.440 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 2.985 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  9.201 ms/op
                 getUser·p0.9999: 20.882 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318879
  mean =      3.012 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23296 
    [ 2.500,  5.000) = 294474 
    [ 5.000,  7.500) = 757 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     20.389 ms/op
     p(99.9990) =     21.221 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 5.596 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.009 ms/op
Iteration   1: 3.900 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  12.739 ms/op
                 listUser·p0.9999: 14.189 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   2: 3.897 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.106 ms/op
                 listUser·p0.9999: 14.234 ms/op
                 listUser·p1.00:   14.959 ms/op

Iteration   3: 3.897 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.526 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.835 ms/op
                 listUser·p0.9999: 25.643 ms/op
                 listUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246328
  mean =      3.898 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4546 
    [ 2.500,  5.000) = 220550 
    [ 5.000,  7.500) = 20048 
    [ 7.500, 10.000) = 693 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     23.998 ms/op
     p(99.9990) =     26.007 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.488 ± 0.931  ops/ms
ClientGrpc.existUser                       thrpt       3  11.188 ± 1.749  ops/ms
ClientGrpc.getUser                         thrpt       3  10.637 ± 0.545  ops/ms
ClientGrpc.listUser                        thrpt       3   8.276 ± 2.076  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.324   ms/op
ClientGrpc.existUser                        avgt       3   2.913 ± 0.821   ms/op
ClientGrpc.getUser                          avgt       3   2.989 ± 0.292   ms/op
ClientGrpc.listUser                         avgt       3   3.918 ± 0.505   ms/op
ClientGrpc.createUser                     sample  317328   3.024 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.569           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.033           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.507           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.234           ms/op
ClientGrpc.existUser                      sample  331464   2.894 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.513           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.255           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.083           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.428           ms/op
ClientGrpc.getUser                        sample  318879   3.012 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.815           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.389           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.299           ms/op
ClientGrpc.listUser                       sample  246328   3.898 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.526           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.058           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.998           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.149           ms/op
