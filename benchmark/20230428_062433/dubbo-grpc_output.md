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
# Warmup Iteration   1: 4.868 ops/ms
# Warmup Iteration   2: 9.200 ops/ms
# Warmup Iteration   3: 10.095 ops/ms
Iteration   1: 10.656 ops/ms
Iteration   2: 10.763 ops/ms
Iteration   3: 11.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.867 ±(99.9%) 5.072 ops/ms [Average]
  (min, avg, max) = (10.656, 10.867, 11.182), stdev = 0.278
  CI (99.9%): [5.795, 15.938] (assumes normal distribution)


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
# Warmup Iteration   1: 7.999 ops/ms
# Warmup Iteration   2: 10.911 ops/ms
# Warmup Iteration   3: 12.010 ops/ms
Iteration   1: 11.669 ops/ms
Iteration   2: 11.451 ops/ms
Iteration   3: 11.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.576 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (11.451, 11.576, 11.669), stdev = 0.113
  CI (99.9%): [9.519, 13.633] (assumes normal distribution)


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
# Warmup Iteration   1: 7.472 ops/ms
# Warmup Iteration   2: 10.552 ops/ms
# Warmup Iteration   3: 10.882 ops/ms
Iteration   1: 10.930 ops/ms
Iteration   2: 10.871 ops/ms
Iteration   3: 10.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.886 ±(99.9%) 0.693 ops/ms [Average]
  (min, avg, max) = (10.858, 10.886, 10.930), stdev = 0.038
  CI (99.9%): [10.193, 11.580] (assumes normal distribution)


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
# Warmup Iteration   1: 5.627 ops/ms
# Warmup Iteration   2: 8.119 ops/ms
# Warmup Iteration   3: 8.163 ops/ms
Iteration   1: 8.256 ops/ms
Iteration   2: 8.109 ops/ms
Iteration   3: 8.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.281 ±(99.9%) 3.390 ops/ms [Average]
  (min, avg, max) = (8.109, 8.281, 8.478), stdev = 0.186
  CI (99.9%): [4.891, 11.671] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.002 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
Iteration   2: 2.988 ±(99.9%) 0.004 ms/op
Iteration   3: 3.036 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.002 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (2.983, 3.002, 3.036), stdev = 0.029
  CI (99.9%): [2.471, 3.534] (assumes normal distribution)


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
# Warmup Iteration   1: 3.658 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.821 ±(99.9%) 0.005 ms/op
Iteration   1: 2.853 ±(99.9%) 0.004 ms/op
Iteration   2: 2.874 ±(99.9%) 0.004 ms/op
Iteration   3: 2.865 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.864 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (2.853, 2.864, 2.874), stdev = 0.011
  CI (99.9%): [2.671, 3.057] (assumes normal distribution)


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.003 ms/op
Iteration   1: 2.928 ±(99.9%) 0.003 ms/op
Iteration   2: 2.914 ±(99.9%) 0.003 ms/op
Iteration   3: 2.935 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.926 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (2.914, 2.926, 2.935), stdev = 0.010
  CI (99.9%): [2.737, 3.114] (assumes normal distribution)


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
# Warmup Iteration   1: 5.248 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.029 ms/op
Iteration   1: 3.920 ±(99.9%) 0.020 ms/op
Iteration   2: 3.871 ±(99.9%) 0.019 ms/op
Iteration   3: 3.861 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.884 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.861, 3.884, 3.920), stdev = 0.032
  CI (99.9%): [3.302, 4.466] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.943 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.351 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.547 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  7.722 ms/op
                 createUser·p0.9999: 11.602 ms/op
                 createUser·p1.00:   12.534 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  10.458 ms/op
                 createUser·p0.9999: 16.253 ms/op
                 createUser·p1.00:   16.482 ms/op

Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  10.771 ms/op
                 createUser·p0.9999: 13.621 ms/op
                 createUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321955
  mean =      2.981 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1883 
    [ 1.250,  2.500) = 21734 
    [ 2.500,  3.750) = 287707 
    [ 3.750,  5.000) = 9163 
    [ 5.000,  6.250) = 726 
    [ 6.250,  7.500) = 190 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 164 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =     10.454 ms/op
     p(99.9900) =     15.558 ms/op
     p(99.9990) =     16.442 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 3.752 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.923 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.870 ±(99.9%) 0.009 ms/op
Iteration   1: 2.881 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  5.789 ms/op
                 existUser·p0.9999: 11.924 ms/op
                 existUser·p1.00:   12.255 ms/op

Iteration   2: 2.859 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.439 ms/op
                 existUser·p0.9999: 12.989 ms/op
                 existUser·p1.00:   13.222 ms/op

Iteration   3: 2.890 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  9.262 ms/op
                 existUser·p0.9999: 27.291 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333722
  mean =      2.877 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44836 
    [ 2.500,  5.000) = 288069 
    [ 5.000,  7.500) = 563 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     14.306 ms/op
     p(99.9990) =     27.655 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.007 ms/op
Iteration   1: 2.961 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.569 ms/op
                 getUser·p0.9999: 11.403 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   2: 3.007 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.103 ms/op
                 getUser·p0.9999: 24.326 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.466 ms/op
                 getUser·p0.9999: 20.235 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319212
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27173 
    [ 2.500,  5.000) = 290617 
    [ 5.000,  7.500) = 1076 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     22.320 ms/op
     p(99.9990) =     24.629 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 5.142 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.010 ms/op
Iteration   1: 3.859 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  12.321 ms/op
                 listUser·p0.9999: 15.943 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 3.866 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 21.117 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   3: 3.887 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  15.181 ms/op
                 listUser·p0.9999: 22.708 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248153
  mean =      3.870 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5450 
    [ 2.500,  5.000) = 223772 
    [ 5.000,  7.500) = 17917 
    [ 7.500, 10.000) = 605 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     22.256 ms/op
     p(99.9990) =     23.055 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.867 ± 5.072  ops/ms
ClientGrpc.existUser                       thrpt       3  11.576 ± 2.057  ops/ms
ClientGrpc.getUser                         thrpt       3  10.886 ± 0.693  ops/ms
ClientGrpc.listUser                        thrpt       3   8.281 ± 3.390  ops/ms
ClientGrpc.createUser                       avgt       3   3.002 ± 0.532   ms/op
ClientGrpc.existUser                        avgt       3   2.864 ± 0.193   ms/op
ClientGrpc.getUser                          avgt       3   2.926 ± 0.189   ms/op
ClientGrpc.listUser                         avgt       3   3.884 ± 0.582   ms/op
ClientGrpc.createUser                     sample  321955   2.981 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.351           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.428           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.454           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.558           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.482           ms/op
ClientGrpc.existUser                      sample  333722   2.877 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.604           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.652           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.306           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.951           ms/op
ClientGrpc.getUser                        sample  319212   3.007 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.671           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.668           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.320           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.773           ms/op
ClientGrpc.listUser                       sample  248153   3.870 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.161           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.041           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.256           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.200           ms/op
