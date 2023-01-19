# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ops/ms
# Warmup Iteration   2: 8.868 ops/ms
# Warmup Iteration   3: 10.129 ops/ms
Iteration   1: 10.548 ops/ms
Iteration   2: 10.094 ops/ms
Iteration   3: 10.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.308 ±(99.9%) 4.156 ops/ms [Average]
  (min, avg, max) = (10.094, 10.308, 10.548), stdev = 0.228
  CI (99.9%): [6.153, 14.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.941 ops/ms
# Warmup Iteration   2: 10.211 ops/ms
# Warmup Iteration   3: 10.742 ops/ms
Iteration   1: 10.872 ops/ms
Iteration   2: 11.066 ops/ms
Iteration   3: 10.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.841 ±(99.9%) 4.399 ops/ms [Average]
  (min, avg, max) = (10.586, 10.841, 11.066), stdev = 0.241
  CI (99.9%): [6.442, 15.240] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.582 ops/ms
# Warmup Iteration   2: 9.799 ops/ms
# Warmup Iteration   3: 10.084 ops/ms
Iteration   1: 10.170 ops/ms
Iteration   2: 10.487 ops/ms
Iteration   3: 10.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.308 ±(99.9%) 2.968 ops/ms [Average]
  (min, avg, max) = (10.170, 10.308, 10.487), stdev = 0.163
  CI (99.9%): [7.339, 13.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.599 ops/ms
# Warmup Iteration   2: 7.799 ops/ms
# Warmup Iteration   3: 7.913 ops/ms
Iteration   1: 7.939 ops/ms
Iteration   2: 8.151 ops/ms
Iteration   3: 7.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.008 ±(99.9%) 2.256 ops/ms [Average]
  (min, avg, max) = (7.935, 8.008, 8.151), stdev = 0.124
  CI (99.9%): [5.752, 10.265] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.372 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.005 ms/op
Iteration   1: 3.189 ±(99.9%) 0.010 ms/op
Iteration   2: 3.159 ±(99.9%) 0.002 ms/op
Iteration   3: 3.182 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.177 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (3.159, 3.177, 3.189), stdev = 0.016
  CI (99.9%): [2.893, 3.460] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.001 ms/op
Iteration   1: 3.044 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.003 ms/op
Iteration   3: 2.969 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.014 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (2.969, 3.014, 3.044), stdev = 0.040
  CI (99.9%): [2.292, 3.735] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.364 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.003 ms/op
Iteration   1: 3.147 ±(99.9%) 0.002 ms/op
Iteration   2: 3.157 ±(99.9%) 0.001 ms/op
Iteration   3: 3.095 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.133 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (3.095, 3.133, 3.157), stdev = 0.033
  CI (99.9%): [2.523, 3.743] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.315 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.020 ms/op
Iteration   1: 4.030 ±(99.9%) 0.008 ms/op
Iteration   2: 3.919 ±(99.9%) 0.005 ms/op
Iteration   3: 3.905 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.952 ±(99.9%) 1.249 ms/op [Average]
  (min, avg, max) = (3.905, 3.952, 4.030), stdev = 0.068
  CI (99.9%): [2.703, 5.201] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.864 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
Iteration   1: 3.155 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.053 ms/op
                 createUser·p0.9999: 12.307 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.869 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.207 ms/op
                 createUser·p0.9999: 15.035 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  11.190 ms/op
                 createUser·p0.9999: 26.872 ms/op
                 createUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302244
  mean =      3.175 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27137 
    [ 2.500,  5.000) = 273967 
    [ 5.000,  7.500) = 762 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.663 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  5.972 ms/op
                 existUser·p0.9999: 14.048 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.424 ms/op
                 existUser·p0.9999: 15.041 ms/op
                 existUser·p1.00:   15.401 ms/op

Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.898 ms/op
                 existUser·p0.9999: 16.695 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318521
  mean =      3.012 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2252 
    [ 1.250,  2.500) = 42121 
    [ 2.500,  3.750) = 246501 
    [ 3.750,  5.000) = 26764 
    [ 5.000,  6.250) = 445 
    [ 6.250,  7.500) = 195 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 80 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.877 ms/op
     p(99.9900) =     15.013 ms/op
     p(99.9990) =     17.001 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.282 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.007 ms/op
Iteration   1: 3.147 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.538 ms/op
                 getUser·p0.9999: 18.836 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   2: 3.190 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  9.523 ms/op
                 getUser·p0.9999: 15.597 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   3: 3.174 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.330 ms/op
                 getUser·p0.9999: 16.346 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302619
  mean =      3.170 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 719 
    [ 1.250,  2.500) = 21731 
    [ 2.500,  3.750) = 237474 
    [ 3.750,  5.000) = 40933 
    [ 5.000,  6.250) = 1025 
    [ 6.250,  7.500) = 383 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.877 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     19.103 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.226 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.241 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.011 ms/op
Iteration   1: 3.906 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  19.561 ms/op
                 listUser·p0.9999: 21.253 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 3.941 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   3: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  17.965 ms/op
                 listUser·p0.9999: 24.735 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244118
  mean =      3.937 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1897 
    [ 2.500,  5.000) = 222299 
    [ 5.000,  7.500) = 18763 
    [ 7.500, 10.000) = 713 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     19.722 ms/op
     p(99.9900) =     23.645 ms/op
     p(99.9990) =     25.071 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.308 ± 4.156  ops/ms
ClientGrpc.existUser                       thrpt       3  10.841 ± 4.399  ops/ms
ClientGrpc.getUser                         thrpt       3  10.308 ± 2.968  ops/ms
ClientGrpc.listUser                        thrpt       3   8.008 ± 2.256  ops/ms
ClientGrpc.createUser                       avgt       3   3.177 ± 0.283   ms/op
ClientGrpc.existUser                        avgt       3   3.014 ± 0.721   ms/op
ClientGrpc.getUser                          avgt       3   3.133 ± 0.610   ms/op
ClientGrpc.listUser                         avgt       3   3.952 ± 1.249   ms/op
ClientGrpc.createUser                     sample  302244   3.175 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.691           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.154           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.030           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.663           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.494           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.296           ms/op
ClientGrpc.existUser                      sample  318521   3.012 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.613           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.903           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.877           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.013           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.170           ms/op
ClientGrpc.getUser                        sample  302619   3.170 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.710           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.067           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.877           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.957           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.235           ms/op
ClientGrpc.listUser                       sample  244118   3.937 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.133           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.722           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.645           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.231           ms/op
