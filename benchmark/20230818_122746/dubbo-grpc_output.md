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
# Warmup Iteration   1: 3.638 ops/ms
# Warmup Iteration   2: 8.451 ops/ms
# Warmup Iteration   3: 9.864 ops/ms
Iteration   1: 10.269 ops/ms
Iteration   2: 10.949 ops/ms
Iteration   3: 10.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.501 ±(99.9%) 7.073 ops/ms [Average]
  (min, avg, max) = (10.269, 10.501, 10.949), stdev = 0.388
  CI (99.9%): [3.428, 17.575] (assumes normal distribution)


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
# Warmup Iteration   1: 7.304 ops/ms
# Warmup Iteration   2: 10.554 ops/ms
# Warmup Iteration   3: 11.002 ops/ms
Iteration   1: 11.060 ops/ms
Iteration   2: 11.028 ops/ms
Iteration   3: 11.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.121 ±(99.9%) 2.435 ops/ms [Average]
  (min, avg, max) = (11.028, 11.121, 11.274), stdev = 0.133
  CI (99.9%): [8.686, 13.556] (assumes normal distribution)


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
# Warmup Iteration   1: 6.641 ops/ms
# Warmup Iteration   2: 9.607 ops/ms
# Warmup Iteration   3: 10.429 ops/ms
Iteration   1: 10.341 ops/ms
Iteration   2: 10.417 ops/ms
Iteration   3: 10.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.358 ±(99.9%) 0.951 ops/ms [Average]
  (min, avg, max) = (10.317, 10.358, 10.417), stdev = 0.052
  CI (99.9%): [9.407, 11.309] (assumes normal distribution)


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
# Warmup Iteration   1: 5.943 ops/ms
# Warmup Iteration   2: 7.316 ops/ms
# Warmup Iteration   3: 7.680 ops/ms
Iteration   1: 7.757 ops/ms
Iteration   2: 7.762 ops/ms
Iteration   3: 7.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.833 ±(99.9%) 2.337 ops/ms [Average]
  (min, avg, max) = (7.757, 7.833, 7.981), stdev = 0.128
  CI (99.9%): [5.496, 10.171] (assumes normal distribution)


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
# Warmup Iteration   1: 4.344 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.002 ms/op
Iteration   1: 3.067 ±(99.9%) 0.003 ms/op
Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
Iteration   3: 3.050 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.053 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (3.042, 3.053, 3.067), stdev = 0.012
  CI (99.9%): [2.826, 3.281] (assumes normal distribution)


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.004 ms/op
Iteration   1: 3.002 ±(99.9%) 0.002 ms/op
Iteration   2: 2.936 ±(99.9%) 0.002 ms/op
Iteration   3: 2.933 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.957 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (2.933, 2.957, 3.002), stdev = 0.039
  CI (99.9%): [2.244, 3.670] (assumes normal distribution)


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
# Warmup Iteration   1: 4.543 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.001 ms/op
Iteration   1: 3.085 ±(99.9%) 0.003 ms/op
Iteration   2: 3.068 ±(99.9%) 0.003 ms/op
Iteration   3: 3.067 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.073 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (3.067, 3.073, 3.085), stdev = 0.010
  CI (99.9%): [2.894, 3.252] (assumes normal distribution)


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
# Warmup Iteration   1: 5.422 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.022 ms/op
Iteration   1: 4.133 ±(99.9%) 0.024 ms/op
Iteration   2: 4.141 ±(99.9%) 0.012 ms/op
Iteration   3: 4.177 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.150 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (4.133, 4.150, 4.177), stdev = 0.024
  CI (99.9%): [3.715, 4.585] (assumes normal distribution)


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
# Warmup Iteration   1: 4.436 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  10.366 ms/op
                 createUser·p0.9999: 12.992 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.272 ms/op
                 createUser·p0.9999: 26.397 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   3: 3.076 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.701 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  10.402 ms/op
                 createUser·p0.9999: 19.142 ms/op
                 createUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313565
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22446 
    [ 2.500,  5.000) = 288674 
    [ 5.000,  7.500) = 1771 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =     10.109 ms/op
     p(99.9900) =     25.941 ms/op
     p(99.9990) =     26.599 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.005 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  7.897 ms/op
                 existUser·p0.9999: 13.559 ms/op
                 existUser·p1.00:   16.368 ms/op

Iteration   2: 2.947 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  8.593 ms/op
                 existUser·p0.9999: 14.168 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   3: 2.892 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.355 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  8.015 ms/op
                 existUser·p0.9999: 18.774 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325143
  mean =      2.951 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 886 
    [ 1.250,  2.500) = 26582 
    [ 2.500,  3.750) = 285449 
    [ 3.750,  5.000) = 10529 
    [ 5.000,  6.250) = 846 
    [ 6.250,  7.500) = 391 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     16.598 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 4.664 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  8.315 ms/op
                 getUser·p0.9999: 14.274 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  9.231 ms/op
                 getUser·p0.9999: 14.119 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 3.128 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.050 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308846
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 704 
    [ 1.250,  2.500) = 15005 
    [ 2.500,  3.750) = 270120 
    [ 3.750,  5.000) = 20910 
    [ 5.000,  6.250) = 1064 
    [ 6.250,  7.500) = 545 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     16.255 ms/op
     p(99.9990) =     17.495 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 5.820 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.011 ms/op
Iteration   1: 4.102 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.469 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 25.914 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   2: 4.052 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 16.091 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   3: 4.136 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  14.847 ms/op
                 listUser·p0.9999: 26.428 ms/op
                 listUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234262
  mean =      4.097 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2082 
    [ 2.500,  5.000) = 206128 
    [ 5.000,  7.500) = 23955 
    [ 7.500, 10.000) = 1612 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     14.339 ms/op
     p(99.9900) =     25.807 ms/op
     p(99.9990) =     26.738 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.501 ± 7.073  ops/ms
ClientGrpc.existUser                       thrpt       3  11.121 ± 2.435  ops/ms
ClientGrpc.getUser                         thrpt       3  10.358 ± 0.951  ops/ms
ClientGrpc.listUser                        thrpt       3   7.833 ± 2.337  ops/ms
ClientGrpc.createUser                       avgt       3   3.053 ± 0.228   ms/op
ClientGrpc.existUser                        avgt       3   2.957 ± 0.713   ms/op
ClientGrpc.getUser                          avgt       3   3.073 ± 0.179   ms/op
ClientGrpc.listUser                         avgt       3   4.150 ± 0.435   ms/op
ClientGrpc.createUser                     sample  313565   3.062 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.701           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.768           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.109           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.941           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.673           ms/op
ClientGrpc.existUser                      sample  325143   2.951 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.736           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.086           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.598           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.235           ms/op
ClientGrpc.getUser                        sample  308846   3.109 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.702           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.569           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.255           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.596           ms/op
ClientGrpc.listUser                       sample  234262   4.097 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.182           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.356           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.339           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.807           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.837           ms/op
