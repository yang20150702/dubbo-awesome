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
# Warmup Iteration   1: 4.304 ops/ms
# Warmup Iteration   2: 9.049 ops/ms
# Warmup Iteration   3: 9.978 ops/ms
Iteration   1: 10.386 ops/ms
Iteration   2: 10.710 ops/ms
Iteration   3: 10.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.597 ±(99.9%) 3.346 ops/ms [Average]
  (min, avg, max) = (10.386, 10.597, 10.710), stdev = 0.183
  CI (99.9%): [7.251, 13.943] (assumes normal distribution)


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
# Warmup Iteration   1: 8.197 ops/ms
# Warmup Iteration   2: 10.816 ops/ms
# Warmup Iteration   3: 11.138 ops/ms
Iteration   1: 11.008 ops/ms
Iteration   2: 11.070 ops/ms
Iteration   3: 11.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.099 ±(99.9%) 1.989 ops/ms [Average]
  (min, avg, max) = (11.008, 11.099, 11.220), stdev = 0.109
  CI (99.9%): [9.110, 13.089] (assumes normal distribution)


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
# Warmup Iteration   1: 7.424 ops/ms
# Warmup Iteration   2: 10.346 ops/ms
# Warmup Iteration   3: 10.645 ops/ms
Iteration   1: 10.569 ops/ms
Iteration   2: 10.601 ops/ms
Iteration   3: 10.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.571 ±(99.9%) 0.529 ops/ms [Average]
  (min, avg, max) = (10.544, 10.571, 10.601), stdev = 0.029
  CI (99.9%): [10.042, 11.101] (assumes normal distribution)


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
# Warmup Iteration   1: 6.750 ops/ms
# Warmup Iteration   2: 7.926 ops/ms
# Warmup Iteration   3: 8.400 ops/ms
Iteration   1: 8.221 ops/ms
Iteration   2: 8.339 ops/ms
Iteration   3: 8.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.272 ±(99.9%) 1.108 ops/ms [Average]
  (min, avg, max) = (8.221, 8.272, 8.339), stdev = 0.061
  CI (99.9%): [7.164, 9.381] (assumes normal distribution)


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.003 ms/op
Iteration   1: 3.067 ±(99.9%) 0.002 ms/op
Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.036 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (2.994, 3.036, 3.067), stdev = 0.038
  CI (99.9%): [2.349, 3.723] (assumes normal distribution)


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.004 ms/op
Iteration   1: 2.910 ±(99.9%) 0.004 ms/op
Iteration   2: 2.865 ±(99.9%) 0.004 ms/op
Iteration   3: 2.886 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.887 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (2.865, 2.887, 2.910), stdev = 0.023
  CI (99.9%): [2.472, 3.302] (assumes normal distribution)


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.003 ms/op
Iteration   1: 2.959 ±(99.9%) 0.003 ms/op
Iteration   2: 2.972 ±(99.9%) 0.002 ms/op
Iteration   3: 2.986 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.972 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (2.959, 2.972, 2.986), stdev = 0.013
  CI (99.9%): [2.731, 3.214] (assumes normal distribution)


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
# Warmup Iteration   1: 5.220 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.012 ms/op
Iteration   1: 3.778 ±(99.9%) 0.041 ms/op
Iteration   2: 3.796 ±(99.9%) 0.035 ms/op
Iteration   3: 3.863 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.812 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (3.778, 3.812, 3.863), stdev = 0.045
  CI (99.9%): [2.995, 4.630] (assumes normal distribution)


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  9.886 ms/op
                 createUser·p0.9999: 16.603 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.768 ms/op
                 createUser·p0.9999: 13.445 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.484 ms/op
                 createUser·p0.9999: 15.047 ms/op
                 createUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318566
  mean =      3.015 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1226 
    [ 1.250,  2.500) = 21841 
    [ 2.500,  3.750) = 279533 
    [ 3.750,  5.000) = 14874 
    [ 5.000,  6.250) = 458 
    [ 6.250,  7.500) = 297 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      8.260 ms/op
     p(99.9900) =     15.998 ms/op
     p(99.9990) =     16.962 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.859 ±(99.9%) 0.006 ms/op
Iteration   1: 2.915 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  5.942 ms/op
                 existUser·p0.9999: 15.730 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   2: 2.853 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.512 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.334 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  5.734 ms/op
                 existUser·p0.9999: 20.506 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   3: 2.881 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.305 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  6.741 ms/op
                 existUser·p0.9999: 17.531 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332945
  mean =      2.882 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30091 
    [ 2.500,  5.000) = 301790 
    [ 5.000,  7.500) = 867 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.512 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.248 ms/op
     p(95.0000) =      3.412 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.325 ms/op
     p(99.9900) =     17.970 ms/op
     p(99.9990) =     20.699 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.978 ms/op
                 getUser·p0.9999: 16.195 ms/op
                 getUser·p1.00:   16.581 ms/op

Iteration   2: 2.964 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.729 ms/op
                 getUser·p0.9999: 13.343 ms/op
                 getUser·p1.00:   13.648 ms/op

Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.686 ms/op
                 getUser·p0.9999: 17.873 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319235
  mean =      3.007 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1325 
    [ 1.250,  2.500) = 19710 
    [ 2.500,  3.750) = 284358 
    [ 3.750,  5.000) = 12620 
    [ 5.000,  6.250) = 628 
    [ 6.250,  7.500) = 250 
    [ 7.500,  8.750) = 90 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.703 ms/op
     p(99.9900) =     16.306 ms/op
     p(99.9990) =     18.208 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 5.235 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
Iteration   1: 3.874 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  12.484 ms/op
                 listUser·p0.9999: 14.606 ms/op
                 listUser·p1.00:   14.975 ms/op

Iteration   2: 3.908 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.123 ms/op
                 listUser·p0.9999: 17.262 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.821 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.678 ms/op
                 listUser·p0.9999: 17.060 ms/op
                 listUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248374
  mean =      3.868 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 4705 
    [ 2.500,  3.750) = 127410 
    [ 3.750,  5.000) = 93740 
    [ 5.000,  6.250) = 17515 
    [ 6.250,  7.500) = 3790 
    [ 7.500,  8.750) = 555 
    [ 8.750, 10.000) = 221 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 139 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 62 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     13.822 ms/op
     p(99.9900) =     17.012 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.597 ± 3.346  ops/ms
ClientGrpc.existUser                       thrpt       3  11.099 ± 1.989  ops/ms
ClientGrpc.getUser                         thrpt       3  10.571 ± 0.529  ops/ms
ClientGrpc.listUser                        thrpt       3   8.272 ± 1.108  ops/ms
ClientGrpc.createUser                       avgt       3   3.036 ± 0.687   ms/op
ClientGrpc.existUser                        avgt       3   2.887 ± 0.415   ms/op
ClientGrpc.getUser                          avgt       3   2.972 ± 0.242   ms/op
ClientGrpc.listUser                         avgt       3   3.812 ± 0.817   ms/op
ClientGrpc.createUser                     sample  318566   3.015 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.669           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.260           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.998           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.105           ms/op
ClientGrpc.existUser                      sample  332945   2.882 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.512           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.248           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.325           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.970           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.808           ms/op
ClientGrpc.getUser                        sample  319235   3.007 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.609           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.703           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.306           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.711           ms/op
ClientGrpc.listUser                       sample  248374   3.868 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.963           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.822           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.012           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.596           ms/op
