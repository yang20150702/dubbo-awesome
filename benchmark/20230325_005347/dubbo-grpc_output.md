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
# Warmup Iteration   1: 4.358 ops/ms
# Warmup Iteration   2: 9.206 ops/ms
# Warmup Iteration   3: 10.245 ops/ms
Iteration   1: 10.413 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.630 ±(99.9%) 3.739 ops/ms [Average]
  (min, avg, max) = (10.413, 10.630, 10.820), stdev = 0.205
  CI (99.9%): [6.891, 14.369] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.907 ops/ms
# Warmup Iteration   2: 10.720 ops/ms
# Warmup Iteration   3: 10.965 ops/ms
Iteration   1: 11.254 ops/ms
Iteration   2: 11.144 ops/ms
Iteration   3: 11.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.220 ±(99.9%) 1.205 ops/ms [Average]
  (min, avg, max) = (11.144, 11.220, 11.262), stdev = 0.066
  CI (99.9%): [10.015, 12.425] (assumes normal distribution)


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
# Warmup Iteration   1: 8.412 ops/ms
# Warmup Iteration   2: 10.295 ops/ms
# Warmup Iteration   3: 10.623 ops/ms
Iteration   1: 10.599 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.635 ±(99.9%) 0.576 ops/ms [Average]
  (min, avg, max) = (10.599, 10.635, 10.655), stdev = 0.032
  CI (99.9%): [10.059, 11.211] (assumes normal distribution)


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
# Warmup Iteration   1: 6.056 ops/ms
# Warmup Iteration   2: 7.936 ops/ms
# Warmup Iteration   3: 8.312 ops/ms
Iteration   1: 8.160 ops/ms
Iteration   2: 8.194 ops/ms
Iteration   3: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.193 ±(99.9%) 0.595 ops/ms [Average]
  (min, avg, max) = (8.160, 8.193, 8.225), stdev = 0.033
  CI (99.9%): [7.598, 8.788] (assumes normal distribution)


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.003 ms/op
Iteration   1: 3.005 ±(99.9%) 0.003 ms/op
Iteration   2: 3.014 ±(99.9%) 0.003 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.010 ±(99.9%) 0.083 ms/op [Average]
  (min, avg, max) = (3.005, 3.010, 3.014), stdev = 0.005
  CI (99.9%): [2.926, 3.093] (assumes normal distribution)


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
# Warmup Iteration   1: 3.691 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.885 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.003 ms/op
Iteration   1: 2.816 ±(99.9%) 0.004 ms/op
Iteration   2: 2.951 ±(99.9%) 0.003 ms/op
Iteration   3: 2.899 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.889 ±(99.9%) 1.243 ms/op [Average]
  (min, avg, max) = (2.816, 2.889, 2.951), stdev = 0.068
  CI (99.9%): [1.646, 4.131] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.319 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.002 ms/op
Iteration   1: 3.029 ±(99.9%) 0.002 ms/op
Iteration   2: 3.074 ±(99.9%) 0.003 ms/op
Iteration   3: 2.986 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.030 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (2.986, 3.030, 3.074), stdev = 0.044
  CI (99.9%): [2.222, 3.837] (assumes normal distribution)


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.041 ms/op
Iteration   1: 3.858 ±(99.9%) 0.023 ms/op
Iteration   2: 3.899 ±(99.9%) 0.014 ms/op
Iteration   3: 3.791 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.849 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (3.791, 3.849, 3.899), stdev = 0.054
  CI (99.9%): [2.857, 4.841] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.007 ms/op
Iteration   1: 2.937 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.251 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  6.258 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.153 ms/op
                 createUser·p0.999:  6.921 ms/op
                 createUser·p0.9999: 16.891 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   3: 3.050 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.160 ms/op
                 createUser·p0.9999: 29.688 ms/op
                 createUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321607
  mean =      2.986 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24414 
    [ 2.500,  5.000) = 296259 
    [ 5.000,  7.500) = 647 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.251 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.909 ms/op
     p(99.9900) =     27.127 ms/op
     p(99.9990) =     29.713 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
Iteration   1: 2.966 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  7.496 ms/op
                 existUser·p0.9999: 16.856 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 2.906 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  5.872 ms/op
                 existUser·p0.9999: 15.515 ms/op
                 existUser·p1.00:   15.958 ms/op

Iteration   3: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  9.065 ms/op
                 existUser·p0.9999: 16.365 ms/op
                 existUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328748
  mean =      2.920 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1905 
    [ 1.250,  2.500) = 41262 
    [ 2.500,  3.750) = 275655 
    [ 3.750,  5.000) = 8865 
    [ 5.000,  6.250) = 669 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.808 ms/op
     p(99.9900) =     16.220 ms/op
     p(99.9990) =     17.063 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.214 ms/op
                 getUser·p0.9999: 11.963 ms/op
                 getUser·p1.00:   12.190 ms/op

Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.193 ms/op
                 getUser·p0.9999: 12.539 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.526 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.610 ms/op
                 getUser·p0.9999: 14.440 ms/op
                 getUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316919
  mean =      3.027 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1538 
    [ 1.250,  2.500) = 24882 
    [ 2.500,  3.750) = 271687 
    [ 3.750,  5.000) = 17615 
    [ 5.000,  6.250) = 695 
    [ 6.250,  7.500) = 230 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.029 ms/op
     p(99.9900) =     13.726 ms/op
     p(99.9990) =     14.691 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 4.964 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.009 ms/op
Iteration   1: 3.918 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  12.534 ms/op
                 listUser·p0.9999: 15.474 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   2: 3.701 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.738 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.724 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 14.664 ms/op
                 listUser·p1.00:   14.991 ms/op

Iteration   3: 3.928 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.305 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.785 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249863
  mean =      3.846 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 3195 
    [ 2.500,  3.750) = 127782 
    [ 3.750,  5.000) = 98924 
    [ 5.000,  6.250) = 15250 
    [ 6.250,  7.500) = 3528 
    [ 7.500,  8.750) = 556 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 171 
    [13.750, 15.000) = 117 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.305 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     16.503 ms/op
     p(99.9990) =     18.825 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.630 ± 3.739  ops/ms
ClientGrpc.existUser                       thrpt       3  11.220 ± 1.205  ops/ms
ClientGrpc.getUser                         thrpt       3  10.635 ± 0.576  ops/ms
ClientGrpc.listUser                        thrpt       3   8.193 ± 0.595  ops/ms
ClientGrpc.createUser                       avgt       3   3.010 ± 0.083   ms/op
ClientGrpc.existUser                        avgt       3   2.889 ± 1.243   ms/op
ClientGrpc.getUser                          avgt       3   3.030 ± 0.807   ms/op
ClientGrpc.listUser                         avgt       3   3.849 ± 0.992   ms/op
ClientGrpc.createUser                     sample  321607   2.986 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.251           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.909           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.127           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.048           ms/op
ClientGrpc.existUser                      sample  328748   2.920 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.694           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.808           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.220           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.138           ms/op
ClientGrpc.getUser                        sample  316919   3.027 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.526           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.029           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.726           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.729           ms/op
ClientGrpc.listUser                       sample  249863   3.846 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.305           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.723           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.173           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.503           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.907           ms/op
