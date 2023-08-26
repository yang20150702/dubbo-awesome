# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.123 ops/ms
# Warmup Iteration   2: 8.752 ops/ms
# Warmup Iteration   3: 9.984 ops/ms
Iteration   1: 10.547 ops/ms
Iteration   2: 10.446 ops/ms
Iteration   3: 10.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.451 ±(99.9%) 1.720 ops/ms [Average]
  (min, avg, max) = (10.359, 10.451, 10.547), stdev = 0.094
  CI (99.9%): [8.731, 12.170] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.583 ops/ms
# Warmup Iteration   2: 10.402 ops/ms
# Warmup Iteration   3: 11.016 ops/ms
Iteration   1: 10.967 ops/ms
Iteration   2: 10.798 ops/ms
Iteration   3: 10.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.881 ±(99.9%) 1.542 ops/ms [Average]
  (min, avg, max) = (10.798, 10.881, 10.967), stdev = 0.085
  CI (99.9%): [9.339, 12.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.054 ops/ms
# Warmup Iteration   2: 9.918 ops/ms
# Warmup Iteration   3: 10.537 ops/ms
Iteration   1: 10.344 ops/ms
Iteration   2: 10.295 ops/ms
Iteration   3: 10.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.365 ±(99.9%) 1.522 ops/ms [Average]
  (min, avg, max) = (10.295, 10.365, 10.457), stdev = 0.083
  CI (99.9%): [8.843, 11.887] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.494 ops/ms
# Warmup Iteration   2: 7.552 ops/ms
# Warmup Iteration   3: 7.826 ops/ms
Iteration   1: 7.844 ops/ms
Iteration   2: 7.782 ops/ms
Iteration   3: 7.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.741 ±(99.9%) 2.345 ops/ms [Average]
  (min, avg, max) = (7.597, 7.741, 7.844), stdev = 0.129
  CI (99.9%): [5.396, 10.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.679 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.011 ms/op
Iteration   1: 3.128 ±(99.9%) 0.003 ms/op
Iteration   2: 3.054 ±(99.9%) 0.004 ms/op
Iteration   3: 3.167 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.117 ±(99.9%) 1.046 ms/op [Average]
  (min, avg, max) = (3.054, 3.117, 3.167), stdev = 0.057
  CI (99.9%): [2.071, 4.163] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.222 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.003 ms/op
Iteration   1: 2.995 ±(99.9%) 0.002 ms/op
Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
Iteration   3: 2.980 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.012 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (2.980, 3.012, 3.061), stdev = 0.043
  CI (99.9%): [2.225, 3.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.746 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.002 ms/op
Iteration   1: 3.151 ±(99.9%) 0.002 ms/op
Iteration   2: 3.144 ±(99.9%) 0.003 ms/op
Iteration   3: 3.131 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.142 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.131, 3.142, 3.151), stdev = 0.010
  CI (99.9%): [2.953, 3.331] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.404 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.014 ms/op
Iteration   1: 4.226 ±(99.9%) 0.014 ms/op
Iteration   2: 3.849 ±(99.9%) 0.013 ms/op
Iteration   3: 4.058 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.044 ±(99.9%) 3.447 ms/op [Average]
  (min, avg, max) = (3.849, 4.044, 4.226), stdev = 0.189
  CI (99.9%): [0.598, 7.491] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.396 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.136 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.869 ms/op
                 createUser·p0.999:  9.809 ms/op
                 createUser·p0.9999: 20.112 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  11.641 ms/op
                 createUser·p0.9999: 16.450 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.789 ms/op
                 createUser·p0.999:  10.600 ms/op
                 createUser·p0.9999: 17.852 ms/op
                 createUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306694
  mean =      3.131 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11754 
    [ 2.500,  5.000) = 292187 
    [ 5.000,  7.500) = 1929 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =     10.955 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     20.248 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.064 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.005 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 16.554 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   2: 2.911 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  8.097 ms/op
                 existUser·p0.9999: 15.565 ms/op
                 existUser·p1.00:   16.384 ms/op

Iteration   3: 2.931 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  8.218 ms/op
                 existUser·p0.9999: 27.429 ms/op
                 existUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327815
  mean =      2.927 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35755 
    [ 2.500,  5.000) = 290191 
    [ 5.000,  7.500) = 1375 
    [ 7.500, 10.000) = 334 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.258 ms/op
     p(99.9900) =     19.663 ms/op
     p(99.9990) =     27.736 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.202 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
Iteration   1: 3.093 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.742 ms/op
                 getUser·p0.999:  9.494 ms/op
                 getUser·p0.9999: 13.554 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 3.074 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.879 ms/op
                 getUser·p0.9999: 14.483 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.313 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 16.059 ms/op
                 getUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311439
  mean =      3.083 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 367 
    [ 1.250,  2.500) = 13483 
    [ 2.500,  3.750) = 278071 
    [ 3.750,  5.000) = 17183 
    [ 5.000,  6.250) = 1261 
    [ 6.250,  7.500) = 543 
    [ 7.500,  8.750) = 178 
    [ 8.750, 10.000) = 129 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.313 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     15.530 ms/op
     p(99.9990) =     16.670 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.592 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.011 ms/op
Iteration   1: 4.125 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  14.294 ms/op
                 listUser·p0.9999: 21.250 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.937 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 29.852 ms/op
                 listUser·p1.00:   30.310 ms/op

Iteration   3: 4.140 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  16.544 ms/op
                 listUser·p0.9999: 26.371 ms/op
                 listUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233599
  mean =      4.108 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2372 
    [ 2.500,  5.000) = 202824 
    [ 5.000,  7.500) = 26275 
    [ 7.500, 10.000) = 1529 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     26.268 ms/op
     p(99.9990) =     31.096 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.451 ± 1.720  ops/ms
ClientGrpc.existUser                       thrpt       3  10.881 ± 1.542  ops/ms
ClientGrpc.getUser                         thrpt       3  10.365 ± 1.522  ops/ms
ClientGrpc.listUser                        thrpt       3   7.741 ± 2.345  ops/ms
ClientGrpc.createUser                       avgt       3   3.117 ± 1.046   ms/op
ClientGrpc.existUser                        avgt       3   3.012 ± 0.787   ms/op
ClientGrpc.getUser                          avgt       3   3.142 ± 0.189   ms/op
ClientGrpc.listUser                         avgt       3   4.044 ± 3.447   ms/op
ClientGrpc.createUser                     sample  306694   3.131 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.851           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.955           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.726           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.918           ms/op
ClientGrpc.existUser                      sample  327815   2.927 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.647           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.258           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.663           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.754           ms/op
ClientGrpc.getUser                        sample  311439   3.083 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.313           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.060           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.530           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.810           ms/op
ClientGrpc.listUser                       sample  233599   4.108 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.155           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.920           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.381           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.041           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.268           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.162           ms/op
