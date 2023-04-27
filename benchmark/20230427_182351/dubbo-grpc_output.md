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
# Warmup Iteration   1: 4.415 ops/ms
# Warmup Iteration   2: 8.951 ops/ms
# Warmup Iteration   3: 10.305 ops/ms
Iteration   1: 10.624 ops/ms
Iteration   2: 10.602 ops/ms
Iteration   3: 10.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.680 ±(99.9%) 2.141 ops/ms [Average]
  (min, avg, max) = (10.602, 10.680, 10.815), stdev = 0.117
  CI (99.9%): [8.540, 12.821] (assumes normal distribution)


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
# Warmup Iteration   1: 7.475 ops/ms
# Warmup Iteration   2: 10.696 ops/ms
# Warmup Iteration   3: 11.229 ops/ms
Iteration   1: 11.232 ops/ms
Iteration   2: 11.398 ops/ms
Iteration   3: 11.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.366 ±(99.9%) 2.206 ops/ms [Average]
  (min, avg, max) = (11.232, 11.366, 11.467), stdev = 0.121
  CI (99.9%): [9.160, 13.571] (assumes normal distribution)


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
# Warmup Iteration   1: 7.404 ops/ms
# Warmup Iteration   2: 10.413 ops/ms
# Warmup Iteration   3: 10.611 ops/ms
Iteration   1: 10.714 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.748 ±(99.9%) 0.717 ops/ms [Average]
  (min, avg, max) = (10.714, 10.748, 10.791), stdev = 0.039
  CI (99.9%): [10.031, 11.466] (assumes normal distribution)


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
# Warmup Iteration   1: 6.025 ops/ms
# Warmup Iteration   2: 7.915 ops/ms
# Warmup Iteration   3: 8.136 ops/ms
Iteration   1: 8.223 ops/ms
Iteration   2: 8.107 ops/ms
Iteration   3: 8.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.190 ±(99.9%) 1.330 ops/ms [Average]
  (min, avg, max) = (8.107, 8.190, 8.240), stdev = 0.073
  CI (99.9%): [6.860, 9.520] (assumes normal distribution)


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.002 ms/op
Iteration   1: 2.980 ±(99.9%) 0.002 ms/op
Iteration   2: 2.966 ±(99.9%) 0.003 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.985 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (2.966, 2.985, 3.010), stdev = 0.022
  CI (99.9%): [2.579, 3.392] (assumes normal distribution)


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.956 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.828 ±(99.9%) 0.004 ms/op
Iteration   1: 2.877 ±(99.9%) 0.003 ms/op
Iteration   2: 2.865 ±(99.9%) 0.002 ms/op
Iteration   3: 2.851 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.864 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (2.851, 2.864, 2.877), stdev = 0.013
  CI (99.9%): [2.624, 3.104] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.002 ms/op
Iteration   1: 2.984 ±(99.9%) 0.003 ms/op
Iteration   2: 2.999 ±(99.9%) 0.004 ms/op
Iteration   3: 3.046 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.009 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (2.984, 3.009, 3.046), stdev = 0.032
  CI (99.9%): [2.419, 3.599] (assumes normal distribution)


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
# Warmup Iteration   1: 5.166 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.009 ms/op
Iteration   1: 3.960 ±(99.9%) 0.028 ms/op
Iteration   2: 3.925 ±(99.9%) 0.041 ms/op
Iteration   3: 3.868 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.918 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.868, 3.918, 3.960), stdev = 0.047
  CI (99.9%): [3.064, 4.771] (assumes normal distribution)


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.333 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.825 ms/op
                 createUser·p0.999:  8.696 ms/op
                 createUser·p0.9999: 13.189 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.816 ms/op
                 createUser·p0.9999: 14.718 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  10.509 ms/op
                 createUser·p0.9999: 15.691 ms/op
                 createUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318807
  mean =      3.012 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1548 
    [ 1.250,  2.500) = 21499 
    [ 2.500,  3.750) = 282390 
    [ 3.750,  5.000) = 11540 
    [ 5.000,  6.250) = 1048 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 106 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      9.560 ms/op
     p(99.9900) =     15.073 ms/op
     p(99.9990) =     16.313 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.005 ms/op
Iteration   1: 2.849 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   3.875 ms/op
                 existUser·p0.999:  6.034 ms/op
                 existUser·p0.9999: 15.669 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   2: 2.945 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 13.355 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.912 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.556 ms/op
                 existUser·p0.9999: 15.073 ms/op
                 existUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330680
  mean =      2.902 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2656 
    [ 1.250,  2.500) = 36890 
    [ 2.500,  3.750) = 280021 
    [ 3.750,  5.000) = 9981 
    [ 5.000,  6.250) = 504 
    [ 6.250,  7.500) = 256 
    [ 7.500,  8.750) = 111 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.670 ms/op
     p(99.9900) =     15.154 ms/op
     p(99.9990) =     17.108 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.005 ms/op
Iteration   1: 3.035 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  10.791 ms/op
                 getUser·p0.9999: 12.083 ms/op
                 getUser·p1.00:   12.386 ms/op

Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  8.505 ms/op
                 getUser·p0.9999: 17.531 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.565 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  7.891 ms/op
                 getUser·p0.9999: 23.134 ms/op
                 getUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319181
  mean =      3.008 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25564 
    [ 2.500,  5.000) = 292130 
    [ 5.000,  7.500) = 1045 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.861 ms/op
     p(99.9900) =     22.520 ms/op
     p(99.9990) =     23.167 ms/op
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
# Warmup Iteration   1: 5.163 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.011 ms/op
Iteration   1: 3.910 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  12.272 ms/op
                 listUser·p0.9999: 19.053 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 3.760 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.744 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 24.642 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 3.912 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  15.241 ms/op
                 listUser·p0.9999: 26.345 ms/op
                 listUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248578
  mean =      3.859 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4384 
    [ 2.500,  5.000) = 226082 
    [ 5.000,  7.500) = 17091 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     13.556 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.680 ± 2.141  ops/ms
ClientGrpc.existUser                       thrpt       3  11.366 ± 2.206  ops/ms
ClientGrpc.getUser                         thrpt       3  10.748 ± 0.717  ops/ms
ClientGrpc.listUser                        thrpt       3   8.190 ± 1.330  ops/ms
ClientGrpc.createUser                       avgt       3   2.985 ± 0.407   ms/op
ClientGrpc.existUser                        avgt       3   2.864 ± 0.240   ms/op
ClientGrpc.getUser                          avgt       3   3.009 ± 0.590   ms/op
ClientGrpc.listUser                         avgt       3   3.918 ± 0.853   ms/op
ClientGrpc.createUser                     sample  318807   3.012 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.333           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.560           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.073           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.466           ms/op
ClientGrpc.existUser                      sample  330680   2.902 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.649           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.670           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.154           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.924           ms/op
ClientGrpc.getUser                        sample  319181   3.008 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.565           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.861           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.520           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.167           ms/op
ClientGrpc.listUser                       sample  248578   3.859 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.744           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.556           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.740           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.739           ms/op
