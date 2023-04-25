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
# Warmup Iteration   1: 4.857 ops/ms
# Warmup Iteration   2: 9.403 ops/ms
# Warmup Iteration   3: 10.320 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.801 ops/ms
Iteration   3: 10.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.747 ±(99.9%) 2.348 ops/ms [Average]
  (min, avg, max) = (10.600, 10.747, 10.840), stdev = 0.129
  CI (99.9%): [8.399, 13.095] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.018 ops/ms
# Warmup Iteration   2: 10.702 ops/ms
# Warmup Iteration   3: 11.312 ops/ms
Iteration   1: 11.306 ops/ms
Iteration   2: 11.454 ops/ms
Iteration   3: 11.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.330 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (11.228, 11.330, 11.454), stdev = 0.115
  CI (99.9%): [9.237, 13.423] (assumes normal distribution)


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
# Warmup Iteration   1: 7.794 ops/ms
# Warmup Iteration   2: 10.633 ops/ms
# Warmup Iteration   3: 10.713 ops/ms
Iteration   1: 10.870 ops/ms
Iteration   2: 10.795 ops/ms
Iteration   3: 10.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.785 ±(99.9%) 1.649 ops/ms [Average]
  (min, avg, max) = (10.690, 10.785, 10.870), stdev = 0.090
  CI (99.9%): [9.136, 12.435] (assumes normal distribution)


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
# Warmup Iteration   1: 5.584 ops/ms
# Warmup Iteration   2: 8.175 ops/ms
# Warmup Iteration   3: 8.307 ops/ms
Iteration   1: 8.360 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.337 ±(99.9%) 1.006 ops/ms [Average]
  (min, avg, max) = (8.274, 8.337, 8.376), stdev = 0.055
  CI (99.9%): [7.331, 9.342] (assumes normal distribution)


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.005 ms/op
Iteration   1: 3.025 ±(99.9%) 0.003 ms/op
Iteration   2: 2.993 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.010 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (2.993, 3.010, 3.025), stdev = 0.016
  CI (99.9%): [2.717, 3.303] (assumes normal distribution)


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.938 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.844 ±(99.9%) 0.004 ms/op
Iteration   1: 2.845 ±(99.9%) 0.004 ms/op
Iteration   2: 2.919 ±(99.9%) 0.002 ms/op
Iteration   3: 2.852 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.872 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (2.845, 2.872, 2.919), stdev = 0.041
  CI (99.9%): [2.122, 3.623] (assumes normal distribution)


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.003 ms/op
Iteration   1: 2.931 ±(99.9%) 0.002 ms/op
Iteration   2: 2.982 ±(99.9%) 0.002 ms/op
Iteration   3: 3.005 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.973 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (2.931, 2.973, 3.005), stdev = 0.038
  CI (99.9%): [2.279, 3.667] (assumes normal distribution)


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.027 ms/op
Iteration   1: 3.848 ±(99.9%) 0.039 ms/op
Iteration   2: 3.757 ±(99.9%) 0.016 ms/op
Iteration   3: 3.797 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.801 ±(99.9%) 0.835 ms/op [Average]
  (min, avg, max) = (3.757, 3.801, 3.848), stdev = 0.046
  CI (99.9%): [2.966, 4.636] (assumes normal distribution)


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.247 ms/op
                 createUser·p0.9999: 19.394 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  8.032 ms/op
                 createUser·p0.9999: 15.704 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   3: 2.953 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  13.038 ms/op
                 createUser·p0.9999: 20.064 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321846
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32201 
    [ 2.500,  5.000) = 288289 
    [ 5.000,  7.500) = 893 
    [ 7.500, 10.000) = 178 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.462 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     20.404 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.882 ±(99.9%) 0.006 ms/op
Iteration   1: 2.871 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.609 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  5.408 ms/op
                 existUser·p0.9999: 14.825 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 2.828 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  6.708 ms/op
                 existUser·p0.9999: 16.138 ms/op
                 existUser·p1.00:   16.417 ms/op

Iteration   3: 2.869 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.168 ms/op
                 existUser·p0.999:  6.164 ms/op
                 existUser·p0.9999: 18.186 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336058
  mean =      2.855 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3648 
    [ 1.250,  2.500) = 47508 
    [ 2.500,  3.750) = 277062 
    [ 3.750,  5.000) = 6844 
    [ 5.000,  6.250) = 673 
    [ 6.250,  7.500) = 144 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.209 ms/op
     p(99.9900) =     16.309 ms/op
     p(99.9990) =     18.261 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.443 ms/op
                 getUser·p0.9999: 13.571 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   2: 2.999 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  6.865 ms/op
                 getUser·p0.9999: 12.517 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.397 ms/op
                 getUser·p0.9999: 14.374 ms/op
                 getUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322140
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1191 
    [ 1.250,  2.500) = 25914 
    [ 2.500,  3.750) = 282453 
    [ 3.750,  5.000) = 11441 
    [ 5.000,  6.250) = 504 
    [ 6.250,  7.500) = 368 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.290 ms/op
     p(99.9900) =     13.628 ms/op
     p(99.9990) =     14.571 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.010 ms/op
Iteration   1: 3.920 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  12.901 ms/op
                 listUser·p0.9999: 19.219 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 3.829 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   6.515 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 19.944 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 3.891 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.773 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 16.234 ms/op
                 listUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247385
  mean =      3.880 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3874 
    [ 2.500,  5.000) = 225210 
    [ 5.000,  7.500) = 17245 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     22.446 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.747 ± 2.348  ops/ms
ClientGrpc.existUser                       thrpt       3  11.330 ± 2.093  ops/ms
ClientGrpc.getUser                         thrpt       3  10.785 ± 1.649  ops/ms
ClientGrpc.listUser                        thrpt       3   8.337 ± 1.006  ops/ms
ClientGrpc.createUser                       avgt       3   3.010 ± 0.293   ms/op
ClientGrpc.existUser                        avgt       3   2.872 ± 0.750   ms/op
ClientGrpc.getUser                          avgt       3   2.973 ± 0.694   ms/op
ClientGrpc.listUser                         avgt       3   3.801 ± 0.835   ms/op
ClientGrpc.createUser                     sample  321846   2.983 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.685           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.462           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.628           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.249           ms/op
ClientGrpc.existUser                      sample  336058   2.855 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.609           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.209           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.309           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.416           ms/op
ClientGrpc.getUser                        sample  322140   2.979 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.720           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.290           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.628           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.696           ms/op
ClientGrpc.listUser                       sample  247385   3.880 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.773           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.598           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.530           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.675           ms/op
