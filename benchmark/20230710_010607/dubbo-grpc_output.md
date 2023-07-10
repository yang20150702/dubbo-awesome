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
# Warmup Iteration   1: 4.015 ops/ms
# Warmup Iteration   2: 8.918 ops/ms
# Warmup Iteration   3: 9.943 ops/ms
Iteration   1: 10.493 ops/ms
Iteration   2: 10.487 ops/ms
Iteration   3: 10.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.464 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (10.411, 10.464, 10.493), stdev = 0.046
  CI (99.9%): [9.627, 11.300] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.748 ops/ms
# Warmup Iteration   2: 10.707 ops/ms
# Warmup Iteration   3: 11.066 ops/ms
Iteration   1: 11.033 ops/ms
Iteration   2: 10.995 ops/ms
Iteration   3: 11.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.013 ±(99.9%) 0.346 ops/ms [Average]
  (min, avg, max) = (10.995, 11.013, 11.033), stdev = 0.019
  CI (99.9%): [10.667, 11.358] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.171 ops/ms
# Warmup Iteration   2: 9.854 ops/ms
# Warmup Iteration   3: 10.299 ops/ms
Iteration   1: 10.252 ops/ms
Iteration   2: 10.558 ops/ms
Iteration   3: 10.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.425 ±(99.9%) 2.868 ops/ms [Average]
  (min, avg, max) = (10.252, 10.425, 10.558), stdev = 0.157
  CI (99.9%): [7.557, 13.293] (assumes normal distribution)


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
# Warmup Iteration   1: 5.140 ops/ms
# Warmup Iteration   2: 7.689 ops/ms
# Warmup Iteration   3: 7.921 ops/ms
Iteration   1: 7.961 ops/ms
Iteration   2: 7.940 ops/ms
Iteration   3: 8.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.975 ±(99.9%) 0.807 ops/ms [Average]
  (min, avg, max) = (7.940, 7.975, 8.025), stdev = 0.044
  CI (99.9%): [7.169, 8.782] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.442 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.063 ±(99.9%) 0.003 ms/op
Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
Iteration   3: 3.081 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.046 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (2.995, 3.046, 3.081), stdev = 0.045
  CI (99.9%): [2.227, 3.865] (assumes normal distribution)


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.958 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.002 ms/op
Iteration   1: 2.924 ±(99.9%) 0.002 ms/op
Iteration   2: 2.937 ±(99.9%) 0.003 ms/op
Iteration   3: 2.913 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.925 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.913, 2.925, 2.937), stdev = 0.012
  CI (99.9%): [2.704, 3.145] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.003 ms/op
Iteration   1: 3.040 ±(99.9%) 0.003 ms/op
Iteration   2: 3.009 ±(99.9%) 0.003 ms/op
Iteration   3: 2.987 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.012 ±(99.9%) 0.492 ms/op [Average]
  (min, avg, max) = (2.987, 3.012, 3.040), stdev = 0.027
  CI (99.9%): [2.519, 3.504] (assumes normal distribution)


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
# Warmup Iteration   1: 5.134 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.012 ms/op
Iteration   1: 4.012 ±(99.9%) 0.014 ms/op
Iteration   2: 4.023 ±(99.9%) 0.010 ms/op
Iteration   3: 4.029 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.022 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (4.012, 4.022, 4.029), stdev = 0.009
  CI (99.9%): [3.866, 4.177] (assumes normal distribution)


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  6.511 ms/op
                 createUser·p0.9999: 14.080 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  10.125 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.743 ms/op
                 createUser·p0.9999: 29.957 ms/op
                 createUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315582
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20219 
    [ 2.500,  5.000) = 293924 
    [ 5.000,  7.500) = 1130 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.380 ms/op
     p(99.9900) =     28.271 ms/op
     p(99.9990) =     30.436 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 4.520 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
Iteration   1: 2.950 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  5.783 ms/op
                 existUser·p0.9999: 18.631 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   2: 2.933 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   3.895 ms/op
                 existUser·p0.999:  11.647 ms/op
                 existUser·p0.9999: 13.910 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  8.035 ms/op
                 existUser·p0.9999: 16.947 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326754
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 705 
    [ 1.250,  2.500) = 27413 
    [ 2.500,  3.750) = 290302 
    [ 3.750,  5.000) = 7211 
    [ 5.000,  6.250) = 405 
    [ 6.250,  7.500) = 205 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =     10.375 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     18.964 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.644 ms/op
                 getUser·p0.9999: 19.890 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.748 ms/op
                 getUser·p0.9999: 24.531 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   3: 3.132 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.550 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  10.262 ms/op
                 getUser·p0.9999: 28.246 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312022
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16057 
    [ 2.500,  5.000) = 294484 
    [ 5.000,  7.500) = 1106 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.430 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     28.832 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 5.155 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.010 ms/op
Iteration   1: 4.086 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.001 ms/op
                 listUser·p0.999:  13.822 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 4.025 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.312 ms/op
                 listUser·p0.9999: 21.909 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   3: 4.019 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  16.074 ms/op
                 listUser·p0.9999: 18.747 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237389
  mean =      4.043 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2055 
    [ 2.500,  5.000) = 211470 
    [ 5.000,  7.500) = 22401 
    [ 7.500, 10.000) = 1034 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     14.979 ms/op
     p(99.9900) =     22.815 ms/op
     p(99.9990) =     25.129 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.464 ± 0.837  ops/ms
ClientGrpc.existUser                       thrpt       3  11.013 ± 0.346  ops/ms
ClientGrpc.getUser                         thrpt       3  10.425 ± 2.868  ops/ms
ClientGrpc.listUser                        thrpt       3   7.975 ± 0.807  ops/ms
ClientGrpc.createUser                       avgt       3   3.046 ± 0.819   ms/op
ClientGrpc.existUser                        avgt       3   2.925 ± 0.221   ms/op
ClientGrpc.getUser                          avgt       3   3.012 ± 0.492   ms/op
ClientGrpc.listUser                         avgt       3   4.022 ± 0.155   ms/op
ClientGrpc.createUser                     sample  315582   3.040 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.635           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.380           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.271           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.507           ms/op
ClientGrpc.existUser                      sample  326754   2.938 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.602           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.375           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.367           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.759           ms/op
ClientGrpc.getUser                        sample  312022   3.077 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.550           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.430           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.716           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.231           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.901           ms/op
ClientGrpc.listUser                       sample  237389   4.043 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.969           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.979           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.815           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.231           ms/op
