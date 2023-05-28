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
# Warmup Iteration   1: 3.991 ops/ms
# Warmup Iteration   2: 8.616 ops/ms
# Warmup Iteration   3: 9.773 ops/ms
Iteration   1: 10.674 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.616 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (10.524, 10.616, 10.674), stdev = 0.081
  CI (99.9%): [9.143, 12.089] (assumes normal distribution)


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
# Warmup Iteration   1: 8.220 ops/ms
# Warmup Iteration   2: 10.429 ops/ms
# Warmup Iteration   3: 10.822 ops/ms
Iteration   1: 10.957 ops/ms
Iteration   2: 10.989 ops/ms
Iteration   3: 11.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.035 ±(99.9%) 1.966 ops/ms [Average]
  (min, avg, max) = (10.957, 11.035, 11.158), stdev = 0.108
  CI (99.9%): [9.069, 13.001] (assumes normal distribution)


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
# Warmup Iteration   1: 6.542 ops/ms
# Warmup Iteration   2: 10.120 ops/ms
# Warmup Iteration   3: 10.485 ops/ms
Iteration   1: 10.499 ops/ms
Iteration   2: 10.523 ops/ms
Iteration   3: 10.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.531 ±(99.9%) 0.685 ops/ms [Average]
  (min, avg, max) = (10.499, 10.531, 10.572), stdev = 0.038
  CI (99.9%): [9.846, 11.216] (assumes normal distribution)


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
# Warmup Iteration   1: 5.522 ops/ms
# Warmup Iteration   2: 8.129 ops/ms
# Warmup Iteration   3: 7.948 ops/ms
Iteration   1: 8.654 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.266 ±(99.9%) 6.123 ops/ms [Average]
  (min, avg, max) = (8.060, 8.266, 8.654), stdev = 0.336
  CI (99.9%): [2.143, 14.389] (assumes normal distribution)


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
# Warmup Iteration   1: 4.447 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.057 ±(99.9%) 0.003 ms/op
Iteration   2: 3.036 ±(99.9%) 0.002 ms/op
Iteration   3: 3.022 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.039 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.022, 3.039, 3.057), stdev = 0.017
  CI (99.9%): [2.722, 3.355] (assumes normal distribution)


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.920 ±(99.9%) 0.002 ms/op
Iteration   1: 2.840 ±(99.9%) 0.002 ms/op
Iteration   2: 2.768 ±(99.9%) 0.003 ms/op
Iteration   3: 2.882 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.830 ±(99.9%) 1.048 ms/op [Average]
  (min, avg, max) = (2.768, 2.830, 2.882), stdev = 0.057
  CI (99.9%): [1.782, 3.878] (assumes normal distribution)


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
# Warmup Iteration   1: 4.380 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.003 ms/op
Iteration   1: 3.047 ±(99.9%) 0.003 ms/op
Iteration   2: 3.055 ±(99.9%) 0.003 ms/op
Iteration   3: 2.991 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.031 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (2.991, 3.031, 3.055), stdev = 0.035
  CI (99.9%): [2.390, 3.672] (assumes normal distribution)


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
# Warmup Iteration   1: 5.602 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.022 ms/op
Iteration   1: 3.919 ±(99.9%) 0.012 ms/op
Iteration   2: 3.960 ±(99.9%) 0.009 ms/op
Iteration   3: 3.775 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.885 ±(99.9%) 1.773 ms/op [Average]
  (min, avg, max) = (3.775, 3.885, 3.960), stdev = 0.097
  CI (99.9%): [2.112, 5.658] (assumes normal distribution)


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.064 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.956 ms/op
                 createUser·p0.9999: 13.861 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.799 ms/op
                 createUser·p0.9999: 14.959 ms/op
                 createUser·p1.00:   15.172 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  12.277 ms/op
                 createUser·p0.9999: 23.416 ms/op
                 createUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313340
  mean =      3.066 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16925 
    [ 2.500,  5.000) = 295042 
    [ 5.000,  7.500) = 1004 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.347 ms/op
     p(99.9000) =      9.432 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.873 ±(99.9%) 0.006 ms/op
Iteration   1: 2.886 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  7.424 ms/op
                 existUser·p0.9999: 15.725 ms/op
                 existUser·p1.00:   16.122 ms/op

Iteration   2: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.505 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.421 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  9.617 ms/op
                 existUser·p0.9999: 15.170 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   3: 2.832 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.260 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  7.047 ms/op
                 existUser·p0.9999: 15.772 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334120
  mean =      2.871 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1443 
    [ 1.250,  2.500) = 44245 
    [ 2.500,  3.750) = 281466 
    [ 3.750,  5.000) = 5998 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 227 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 66 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.486 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      7.429 ms/op
     p(99.9900) =     15.535 ms/op
     p(99.9990) =     16.951 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.006 ms/op
Iteration   1: 3.135 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.119 ms/op
                 getUser·p0.9999: 15.480 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   2: 3.146 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.294 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.065 ms/op
                 getUser·p0.9999: 17.859 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.184 ms/op
                 getUser·p0.9999: 19.399 ms/op
                 getUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308172
  mean =      3.114 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 362 
    [ 1.250,  2.500) = 13588 
    [ 2.500,  3.750) = 273312 
    [ 3.750,  5.000) = 19305 
    [ 5.000,  6.250) = 980 
    [ 6.250,  7.500) = 294 
    [ 7.500,  8.750) = 112 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.294 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.601 ms/op
     p(99.9900) =     17.832 ms/op
     p(99.9990) =     19.527 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 5.301 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.602 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.011 ms/op
Iteration   1: 4.036 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.965 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  15.244 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 3.870 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   6.698 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 23.724 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  16.311 ms/op
                 listUser·p0.9999: 20.508 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243292
  mean =      3.944 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2039 
    [ 2.500,  5.000) = 221798 
    [ 5.000,  7.500) = 18033 
    [ 7.500, 10.000) = 960 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 224 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.956 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     23.080 ms/op
     p(99.9990) =     23.925 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.616 ± 1.473  ops/ms
ClientGrpc.existUser                       thrpt       3  11.035 ± 1.966  ops/ms
ClientGrpc.getUser                         thrpt       3  10.531 ± 0.685  ops/ms
ClientGrpc.listUser                        thrpt       3   8.266 ± 6.123  ops/ms
ClientGrpc.createUser                       avgt       3   3.039 ± 0.316   ms/op
ClientGrpc.existUser                        avgt       3   2.830 ± 1.048   ms/op
ClientGrpc.getUser                          avgt       3   3.031 ± 0.641   ms/op
ClientGrpc.listUser                         avgt       3   3.885 ± 1.773   ms/op
ClientGrpc.createUser                     sample  313340   3.066 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.895           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.347           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.432           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.741           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.790           ms/op
ClientGrpc.existUser                      sample  334120   2.871 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.505           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.010           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.429           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.535           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  308172   3.114 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.294           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.601           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.832           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.530           ms/op
ClientGrpc.listUser                       sample  243292   3.944 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.090           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.956           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.925           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.080           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.052           ms/op
