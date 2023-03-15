# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.378 ops/ms
# Warmup Iteration   2: 9.025 ops/ms
# Warmup Iteration   3: 10.231 ops/ms
Iteration   1: 10.622 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.586 ±(99.9%) 1.648 ops/ms [Average]
  (min, avg, max) = (10.483, 10.586, 10.652), stdev = 0.090
  CI (99.9%): [8.938, 12.234] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.027 ops/ms
# Warmup Iteration   2: 10.429 ops/ms
# Warmup Iteration   3: 10.695 ops/ms
Iteration   1: 10.866 ops/ms
Iteration   2: 10.947 ops/ms
Iteration   3: 10.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.883 ±(99.9%) 1.043 ops/ms [Average]
  (min, avg, max) = (10.836, 10.883, 10.947), stdev = 0.057
  CI (99.9%): [9.840, 11.926] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.662 ops/ms
# Warmup Iteration   2: 10.278 ops/ms
# Warmup Iteration   3: 10.392 ops/ms
Iteration   1: 10.535 ops/ms
Iteration   2: 10.519 ops/ms
Iteration   3: 10.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.553 ±(99.9%) 0.840 ops/ms [Average]
  (min, avg, max) = (10.519, 10.553, 10.605), stdev = 0.046
  CI (99.9%): [9.713, 11.393] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.187 ops/ms
# Warmup Iteration   2: 7.765 ops/ms
# Warmup Iteration   3: 8.186 ops/ms
Iteration   1: 8.139 ops/ms
Iteration   2: 7.907 ops/ms
Iteration   3: 7.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.993 ±(99.9%) 2.322 ops/ms [Average]
  (min, avg, max) = (7.907, 7.993, 8.139), stdev = 0.127
  CI (99.9%): [5.671, 10.314] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.313 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.002 ms/op
Iteration   1: 3.060 ±(99.9%) 0.002 ms/op
Iteration   2: 3.079 ±(99.9%) 0.004 ms/op
Iteration   3: 3.023 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.054 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (3.023, 3.054, 3.079), stdev = 0.028
  CI (99.9%): [2.539, 3.569] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
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
# Warmup Iteration   2: 3.038 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.003 ms/op
Iteration   1: 2.940 ±(99.9%) 0.002 ms/op
Iteration   2: 2.931 ±(99.9%) 0.003 ms/op
Iteration   3: 2.952 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.941 ±(99.9%) 0.190 ms/op [Average]
  (min, avg, max) = (2.931, 2.941, 2.952), stdev = 0.010
  CI (99.9%): [2.751, 3.131] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.292 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.003 ms/op
Iteration   1: 3.008 ±(99.9%) 0.003 ms/op
Iteration   2: 3.007 ±(99.9%) 0.004 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.003 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.994, 3.003, 3.008), stdev = 0.008
  CI (99.9%): [2.860, 3.146] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.531 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.018 ms/op
Iteration   1: 3.930 ±(99.9%) 0.009 ms/op
Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
Iteration   3: 3.918 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.944 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.918, 3.944, 3.985), stdev = 0.036
  CI (99.9%): [3.295, 4.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.509 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.250 ms/op
                 createUser·p0.9999: 12.889 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.371 ms/op
                 createUser·p0.9999: 13.631 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.453 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.469 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.046 ms/op
                 createUser·p0.9999: 24.640 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318754
  mean =      3.011 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16508 
    [ 2.500,  5.000) = 300916 
    [ 5.000,  7.500) = 1010 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.522 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     26.649 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.088 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.005 ms/op
Iteration   1: 2.935 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  5.727 ms/op
                 existUser·p0.9999: 12.881 ms/op
                 existUser·p1.00:   13.238 ms/op

Iteration   2: 2.863 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.314 ms/op
                 existUser·p0.99:   4.014 ms/op
                 existUser·p0.999:  6.797 ms/op
                 existUser·p0.9999: 13.907 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   3: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  7.012 ms/op
                 existUser·p0.9999: 17.266 ms/op
                 existUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331162
  mean =      2.898 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 858 
    [ 1.250,  2.500) = 35976 
    [ 2.500,  3.750) = 286497 
    [ 3.750,  5.000) = 6857 
    [ 5.000,  6.250) = 553 
    [ 6.250,  7.500) = 211 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      6.577 ms/op
     p(99.9900) =     16.184 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.204 ms/op
                 getUser·p0.999:  7.684 ms/op
                 getUser·p0.9999: 22.623 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.786 ms/op
                 getUser·p0.9999: 22.020 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.411 ms/op
                 getUser·p0.9999: 23.921 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314463
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16106 
    [ 2.500,  5.000) = 297068 
    [ 5.000,  7.500) = 934 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.893 ms/op
     p(99.9900) =     22.989 ms/op
     p(99.9990) =     24.304 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.186 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.010 ms/op
Iteration   1: 3.976 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  14.943 ms/op
                 listUser·p0.9999: 20.773 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 3.902 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.255 ms/op
                 listUser·p0.9999: 17.616 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   3: 3.923 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.361 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243944
  mean =      3.934 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1900 
    [ 2.500,  5.000) = 224342 
    [ 5.000,  7.500) = 16503 
    [ 7.500, 10.000) = 747 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     19.844 ms/op
     p(99.9990) =     21.139 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.586 ± 1.648  ops/ms
ClientGrpc.existUser                       thrpt       3  10.883 ± 1.043  ops/ms
ClientGrpc.getUser                         thrpt       3  10.553 ± 0.840  ops/ms
ClientGrpc.listUser                        thrpt       3   7.993 ± 2.322  ops/ms
ClientGrpc.createUser                       avgt       3   3.054 ± 0.515   ms/op
ClientGrpc.existUser                        avgt       3   2.941 ± 0.190   ms/op
ClientGrpc.getUser                          avgt       3   3.003 ± 0.143   ms/op
ClientGrpc.listUser                         avgt       3   3.944 ± 0.649   ms/op
ClientGrpc.createUser                     sample  318754   3.011 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.453           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.404           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.522           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.248           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.935           ms/op
ClientGrpc.existUser                      sample  331162   2.898 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.796           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.577           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.184           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.695           ms/op
ClientGrpc.getUser                        sample  314463   3.051 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.701           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.893           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.989           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.609           ms/op
ClientGrpc.listUser                       sample  243944   3.934 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.984           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.434           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.844           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.430           ms/op
