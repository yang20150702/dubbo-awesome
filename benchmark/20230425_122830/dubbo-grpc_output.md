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
# Warmup Iteration   1: 4.704 ops/ms
# Warmup Iteration   2: 9.427 ops/ms
# Warmup Iteration   3: 10.288 ops/ms
Iteration   1: 10.583 ops/ms
Iteration   2: 10.893 ops/ms
Iteration   3: 10.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.756 ±(99.9%) 2.889 ops/ms [Average]
  (min, avg, max) = (10.583, 10.756, 10.893), stdev = 0.158
  CI (99.9%): [7.867, 13.646] (assumes normal distribution)


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
# Warmup Iteration   1: 7.898 ops/ms
# Warmup Iteration   2: 11.065 ops/ms
# Warmup Iteration   3: 11.302 ops/ms
Iteration   1: 11.146 ops/ms
Iteration   2: 11.556 ops/ms
Iteration   3: 11.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.374 ±(99.9%) 3.811 ops/ms [Average]
  (min, avg, max) = (11.146, 11.374, 11.556), stdev = 0.209
  CI (99.9%): [7.564, 15.185] (assumes normal distribution)


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
# Warmup Iteration   1: 7.883 ops/ms
# Warmup Iteration   2: 10.479 ops/ms
# Warmup Iteration   3: 10.763 ops/ms
Iteration   1: 10.750 ops/ms
Iteration   2: 10.940 ops/ms
Iteration   3: 10.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.853 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (10.750, 10.853, 10.940), stdev = 0.096
  CI (99.9%): [9.105, 12.601] (assumes normal distribution)


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
# Warmup Iteration   1: 5.589 ops/ms
# Warmup Iteration   2: 8.053 ops/ms
# Warmup Iteration   3: 8.215 ops/ms
Iteration   1: 8.375 ops/ms
Iteration   2: 8.300 ops/ms
Iteration   3: 8.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.332 ±(99.9%) 0.712 ops/ms [Average]
  (min, avg, max) = (8.300, 8.332, 8.375), stdev = 0.039
  CI (99.9%): [7.620, 9.044] (assumes normal distribution)


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.003 ms/op
Iteration   1: 2.949 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.002 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.002 ±(99.9%) 0.827 ms/op [Average]
  (min, avg, max) = (2.949, 3.002, 3.028), stdev = 0.045
  CI (99.9%): [2.175, 3.828] (assumes normal distribution)


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
# Warmup Iteration   1: 3.375 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.923 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.832 ±(99.9%) 0.003 ms/op
Iteration   1: 2.812 ±(99.9%) 0.003 ms/op
Iteration   2: 2.860 ±(99.9%) 0.004 ms/op
Iteration   3: 2.850 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.841 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (2.812, 2.841, 2.860), stdev = 0.025
  CI (99.9%): [2.383, 3.299] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.003 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 2.988 ±(99.9%) 0.003 ms/op
Iteration   3: 2.943 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.979 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (2.943, 2.979, 3.007), stdev = 0.033
  CI (99.9%): [2.385, 3.574] (assumes normal distribution)


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
# Warmup Iteration   1: 5.209 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.010 ms/op
Iteration   1: 3.619 ±(99.9%) 0.014 ms/op
Iteration   2: 3.784 ±(99.9%) 0.017 ms/op
Iteration   3: 3.787 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.730 ±(99.9%) 1.753 ms/op [Average]
  (min, avg, max) = (3.619, 3.730, 3.787), stdev = 0.096
  CI (99.9%): [1.977, 5.483] (assumes normal distribution)


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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 2.957 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.192 ms/op
                 createUser·p0.9999: 17.936 ms/op
                 createUser·p1.00:   18.219 ms/op

Iteration   2: 2.924 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.380 ms/op
                 createUser·p0.9999: 17.338 ms/op
                 createUser·p1.00:   17.760 ms/op

Iteration   3: 2.953 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  9.903 ms/op
                 createUser·p0.9999: 14.424 ms/op
                 createUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325858
  mean =      2.945 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3093 
    [ 1.250,  2.500) = 32819 
    [ 2.500,  3.750) = 276833 
    [ 3.750,  5.000) = 11998 
    [ 5.000,  6.250) = 573 
    [ 6.250,  7.500) = 193 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.356 ms/op
     p(99.9900) =     17.577 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.007 ms/op
Iteration   1: 2.877 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.210 ms/op
                 existUser·p0.9999: 15.956 ms/op
                 existUser·p1.00:   16.728 ms/op

Iteration   2: 2.811 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.252 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  6.040 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   3: 2.853 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.927 ms/op
                 existUser·p0.9999: 33.187 ms/op
                 existUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337100
  mean =      2.847 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39290 
    [ 2.500,  5.000) = 296573 
    [ 5.000,  7.500) = 968 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.232 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.504 ms/op
     p(99.9900) =     25.719 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 3.882 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.803 ms/op
                 getUser·p0.9999: 11.653 ms/op
                 getUser·p1.00:   11.928 ms/op

Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.552 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.778 ms/op
                 getUser·p0.9999: 12.770 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.226 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.550 ms/op
                 getUser·p0.9999: 19.341 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322701
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2537 
    [ 1.250,  2.500) = 28760 
    [ 2.500,  3.750) = 279202 
    [ 3.750,  5.000) = 10922 
    [ 5.000,  6.250) = 766 
    [ 6.250,  7.500) = 243 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.226 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.930 ms/op
     p(99.9900) =     18.800 ms/op
     p(99.9990) =     19.679 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 5.087 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.010 ms/op
Iteration   1: 3.814 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  14.621 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   2: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  13.215 ms/op
                 listUser·p0.9999: 20.634 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   3: 3.860 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.914 ms/op
                 listUser·p0.9999: 21.731 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249795
  mean =      3.841 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5386 
    [ 2.500,  5.000) = 226272 
    [ 5.000,  7.500) = 17013 
    [ 7.500, 10.000) = 578 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     21.202 ms/op
     p(99.9990) =     24.003 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.756 ± 2.889  ops/ms
ClientGrpc.existUser                       thrpt       3  11.374 ± 3.811  ops/ms
ClientGrpc.getUser                         thrpt       3  10.853 ± 1.748  ops/ms
ClientGrpc.listUser                        thrpt       3   8.332 ± 0.712  ops/ms
ClientGrpc.createUser                       avgt       3   3.002 ± 0.827   ms/op
ClientGrpc.existUser                        avgt       3   2.841 ± 0.458   ms/op
ClientGrpc.getUser                          avgt       3   2.979 ± 0.594   ms/op
ClientGrpc.listUser                         avgt       3   3.730 ± 1.753   ms/op
ClientGrpc.createUser                     sample  325858   2.945 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.585           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.356           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.577           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.219           ms/op
ClientGrpc.existUser                      sample  337100   2.847 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.506           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.232           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.504           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.719           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.817           ms/op
ClientGrpc.getUser                        sample  322701   2.973 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.226           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.930           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.800           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.857           ms/op
ClientGrpc.listUser                       sample  249795   3.841 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.049           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.057           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.202           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.117           ms/op
